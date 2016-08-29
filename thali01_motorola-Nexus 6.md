#### Test 8291407379492e1_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-29 10:23:43.462  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 10:23:43.473  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 10:23:43.475  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 10:23:43.520  1527  2327 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-29 10:23:43.520  1527  2327 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-29 10:23:43.521  1527  2327 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 10:23:43.521  1527  2327 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-29 10:23:43.549  3710  3710 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-29 10:23:43.550  3710  3710 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-29 10:23:43.550  3710  3710 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
--------- beginning of system
08-29 10:23:44.094   872  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-29 10:23:44.126  4013  4013 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-29 10:23:44.130  4013  4013 D AndroidRuntime: CheckJNI is OFF
08-29 10:23:44.173  4013  4013 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-29 10:23:44.222  4013  4013 I Radio-JNI: register_android_hardware_Radio DONE
08-29 10:23:44.244  4013  4013 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-29 10:23:44.250   872  2744 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-29 10:23:44.309  1972  1983 W SearchService: Abort, client detached.
08-29 10:23:44.314  1972  1972 I HotwordDetector: Closing mic
08-29 10:23:44.314  1972  2338 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@3b234a9
08-29 10:23:44.315  1972  2345 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-29 10:23:44.353  4013  4013 D AndroidRuntime: Shutting down VM
08-29 10:23:44.368   872   882 I ActivityManager: Start proc 4023:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-29 10:23:44.377   374  2347 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-29 10:23:44.378   374  2347 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-29 10:23:44.386   374  1276 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-29 10:23:44.389  1972  2344 I MicroRecognitionRnrImpl: Detection finished
08-29 10:23:44.389  1972  2342 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-29 10:23:44.456  4023  4023 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-29 10:23:44.479  4023  4023 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-29 10:23:44.487  4023  4023 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9541-9544)
08-29 10:23:44.487  4023  4023 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 10:23:44.501  4023  4023 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8fdad32}
08-29 10:23:44.501  4023  4023 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 10:23:44.503  4023  4023 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 10:23:44.518  4023  4023 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-29 10:23:44.520  4023  4023 E SysUtils: ApplicationContext is null in ApplicationStatus
08-29 10:23:44.541  4023  4023 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-29 10:23:44.552  4023  4023 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 10:23:44.552  4023  4023 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 10:23:44.552  4023  4023 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 10:23:44.552  4023  4023 I Adreno  : Build Date                       : 10/20/15
08-29 10:23:44.552  4023  4023 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 10:23:44.552  4023  4023 I Adreno  : Local Branch                     : M14
08-29 10:23:44.552  4023  4023 I Adreno  : Remote Branch                    : 
08-29 10:23:44.552  4023  4023 I Adreno  : Remote Branch                    : 
08-29 10:23:44.552  4023  4023 I Adreno  : Reconstruct Branch               : 
,08-29 10:23:44.614   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f37a98d:true
,08-29 10:23:44.643  4023  4023 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-29 10:23:44.654  4023  4023 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-29 10:23:44.728  4023  4061 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-29 10:23:44.737  4023  4048 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-29 10:23:44.779  4023  4061 I OpenGLRenderer: Initialized EGL, version 1.4
,08-29 10:23:44.840   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +488ms
,08-29 10:23:44.852  1850  1850 I Keyboard.Facilitator: onFinishInput()
,08-29 10:23:44.938  4023  4023 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 4023
,08-29 10:23:45.077  4023  4023 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 10:23:45.193   872   883 I ActivityManager: Killing 3169:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-29 10:23:45.228  4023  4063 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1680934608
,08-29 10:23:45.238  4023  4063 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 10:23:45.238  4023  4063 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 10:23:45.238  4023  4063 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 10:23:45.238  4023  4063 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 10:23:45.238  4023  4063 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-29 10:23:45.238  4023  4063 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4925731 added. We now have 1 listener(s)
08-29 10:23:45.243  4023  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-29 10:23:45.244  4023  4063 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 10:23:45.248  4023  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 10:23:45.251  4023  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 10:23:45.257   872   883 I ActivityManager: Killing 3413:com.google.android.gm/u0a78 (adj 15): empty #18
,08-29 10:23:45.258  4023  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 10:23:45.258  4023  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 10:23:45.258  4023  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 10:23:45.258  4023  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-29 10:23:45.258  4023  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 10:23:45.258  4023  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 10:23:45.258  4023  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 10:23:45.258  4023  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 10:23:45.258  4023  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 10:23:45.258  4023  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 10:23:45.258  4023  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 10:23:45.258  4023  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 10:23:45.258  4023  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 10:23:45.258  4023  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-29 10:23:45.258  4023  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70c984 added. We now have 1 listener(s)
08-29 10:23:45.259  4023  4063 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 10:23:45.264   872  1305 D WifiService: New client listening to asynchronous messages
,08-29 10:23:45.266  4023  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 10:23:45.266  4023  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-29 10:23:45.266  4023  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-29 10:23:45.266  4023  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 10:23:45.266  4023  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-29 10:23:45.326  4023  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:23:45.327  4023  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-29 10:23:45.340  4023  4063 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-29 10:23:45.342  4023  4063 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:23:45.342  4023  4063 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:23:45.342  4023  4063 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:23:45.342  4023  4063 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:23:45.342  4023  4063 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:23:45.342  4023  4063 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:23:45.342  4023  4063 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:23:45.342  4023  4063 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:23:45.344  4023  4063 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-29 10:23:45.344  4023  4063 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 10:23:45.346  4023  4063 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-29 10:23:45.460  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:23:45.468  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:23:45.474  4023  4023 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 10:23:46.152  4023  4073 W jxcore-log: Initializing JXcore engine
,08-29 10:23:46.152  4023  4073 W jxcore-log: JXcore engine is ready
,08-29 10:23:46.193  4073  4073 W Thread-378: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8950 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-29 10:23:46.193  4073  4073 W Thread-378: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11718]" dev="sockfs" ino=11718 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-29 10:23:46.193  4073  4073 W Thread-378: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-29 10:23:46.193  4073  4073 W Thread-378: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[27872]" dev="sockfs" ino=27872 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-29 10:23:46.214  4023  4073 W jxcore-log: Starting JXcore engine
,08-29 10:23:46.306  4023  4073 W jxcore-log: Platform android
08-29 10:23:46.306  4023  4073 W jxcore-log: 
,08-29 10:23:46.306  4023  4073 W jxcore-log: Process ARCH arm
08-29 10:23:46.306  4023  4073 W jxcore-log: 
,08-29 10:23:46.555  4023  4073 I jxcore-log: JXcore Cordova bridge is ready!
08-29 10:23:46.555  4023  4073 I jxcore-log: 
,08-29 10:23:46.556  4023  4073 W jxcore-log: JXcore engine is started
,08-29 10:23:46.565  4023  4063 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-29 10:23:46.570  4023  4023 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 10:23:47.515   872  1304 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-29 10:23:50.158   872  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-29 10:23:53.191   872  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-29 10:23:54.617  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 10:23:54.618  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 10:23:54.638  1527  2112 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-29 10:23:54.638  1527  2112 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-29 10:23:54.638  1527  2112 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 10:23:54.639  1527  2112 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 10:23:54.651  3749  4085 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-29 10:23:54.651  3749  4085 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 10:23:54.651  3749  4085 E HttpOperation: 	at jdm.a(PG:82)
08-29 10:23:54.651  3749  4085 E HttpOperation: 	at jcs.o(PG:406)
08-29 10:23:54.651  3749  4085 E HttpOperation: 	at jcn.a(PG:1379)
08-29 10:23:54.651  3749  4085 E HttpOperation: 	at jcs.i(PG:143)
08-29 10:23:54.651  3749  4085 E HttpOperation: 	at blb.a(PG:3937)
08-29 10:23:54.651  3749  4085 E HttpOperation: 	at czp.a(PG:18188)
08-29 10:23:54.651  3749  4085 E HttpOperation: 	at czp.a(PG:9081)
08-29 10:23:54.651  3749  4085 E HttpOperation: 	at czq.run(PG:1686)
08-29 10:23:54.651  3749  4085 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 10:23:54.651  3749  4085 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 10:23:54.651  3749  4085 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 10:23:54.651  3749  4085 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 10:23:54.651  3749  4085 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 10:23:54.651  3749  4085 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 10:23:54.651  3749  4085 E HttpOperation: 	at jdj.a(PG:4091)
08-29 10:23:54.651  3749  4085 E HttpOperation: 	at jdj.a(PG:1125)
08-29 10:23:54.651  3749  4085 E HttpOperation: 	at jdm.a(PG:77)
08-29 10:23:54.651  3749  4085 E HttpOperation: 	... 12 more
08-29 10:23:54.651  3749  4085 E HttpOperation: Caused by: faj: BadAuthentication
08-29 10:23:54.651  3749  4085 E HttpOperation: 	at fal.a(PG:38)
08-29 10:23:54.651  3749  4085 E HttpOperation: 	at jdj.a(PG:4089)
08-29 10:23:54.651  3749  4085 E HttpOperation: 	... 14 more
,08-29 10:23:54.690  1527  2327 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-29 10:23:54.690  1527  2327 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-29 10:23:54.690  1527  2327 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 10:23:54.691  1527  2327 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 10:23:54.708  3749  4085 E HttpOperation: [getmobileexperiments] Unexpected exception
08-29 10:23:54.708  3749  4085 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 10:23:54.708  3749  4085 E HttpOperation: 	at jdm.a(PG:82)
08-29 10:23:54.708  3749  4085 E HttpOperation: 	at jcs.o(PG:406)
08-29 10:23:54.708  3749  4085 E HttpOperation: 	at jcn.a(PG:1379)
08-29 10:23:54.708  3749  4085 E HttpOperation: 	at jcs.i(PG:143)
08-29 10:23:54.708  3749  4085 E HttpOperation: 	at hec.a(PG:42)
08-29 10:23:54.708  3749  4085 E HttpOperation: 	at hee.a(PG:102)
08-29 10:23:54.708  3749  4085 E HttpOperation: 	at czr.a(PG:65)
08-29 10:23:54.708  3749  4085 E HttpOperation: 	at kka.a(PG:108)
08-29 10:23:54.708  3749  4085 E HttpOperation: 	at czp.a(PG:19176)
08-29 10:23:54.708  3749  4085 E HttpOperation: 	at czp.a(PG:9081)
08-29 10:23:54.708  3749  4085 E HttpOperation: 	at czq.run(PG:1686)
08-29 10:23:54.708  3749  4085 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 10:23:54.708  3749  4085 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 10:23:54.708  3749  4085 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 10:23:54.708  3749  4085 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 10:23:54.708  3749  4085 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 10:23:54.708  3749  4085 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 10:23:54.708  3749  4085 E HttpOperation: 	at jdj.a(PG:4091)
08-29 10:23:54.708  3749  4085 E HttpOperation: 	at jdj.a(PG:1125)
08-29 10:23:54.708  3749  4085 E HttpOperation: 	at jdm.a(PG:77)
08-29 10:23:54.708  3749  4085 E HttpOperation: 	... 15 more
08-29 10:23:54.708  3749  4085 E HttpOperation: Caused by: faj: BadAuthentication
08-29 10:23:54.708  3749  4085 E HttpOperation: 	at fal.a(PG:38)
08-29 10:23:54.708  3749  4085 E HttpOperation: 	at jdj.a(PG:4089)
08-29 10:23:54.708  3749  4085 E HttpOperation: 	... 17 more
,08-29 10:23:54.708  3749  4085 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-29 10:23:54.708  3749  4085 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-29 10:23:54.708  3749  4085 E ExperimentLoader: 	at jdm.a(PG:82)
08-29 10:23:54.708  3749  4085 E ExperimentLoader: 	at jcs.o(PG:406)
08-29 10:23:54.708  3749  4085 E ExperimentLoader: 	at jcn.a(PG:1379)
08-29 10:23:54.708  3749  4085 E ExperimentLoader: 	at jcs.i(PG:143),
08-29 10:23:54.708  3749  4085 E ExperimentLoader: 	at hec.a(PG:42)
08-29 10:23:54.708  3749  4085 E ExperimentLoader: 	at hee.a(PG:102)
08-29 10:23:54.708  3749  4085 E ExperimentLoader: 	at czr.a(PG:65)
08-29 10:23:54.708  3749  4085 E ExperimentLoader: 	at kka.a(PG:108)
08-29 10:23:54.708  3749  4085 E ExperimentLoader: 	at czp.a(PG:19176)
08-29 10:23:54.708  3749  4085 E ExperimentLoader: 	at czp.a(PG:9081)
08-29 10:23:54.708  3749  4085 E ExperimentLoader: 	at czq.run(PG:1686)
08-29 10:23:54.708  3749  4085 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 10:23:54.708  3749  4085 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 10:23:54.708  3749  4085 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 10:23:54.708  3749  4085 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
,08-29 10:23:54.708  3749  4085 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-29 10:23:54.708  3749  4085 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 10:23:54.708  3749  4085 E ExperimentLoader: 	at jdj.a(PG:4091)
08-29 10:23:54.708  3749  4085 E ExperimentLoader: 	at jdj.a(PG:1125)
08-29 10:23:54.708  3749  4085 E ExperimentLoader: 	at jdm.a(PG:77)
08-29 10:23:54.708  3749  4085 E ExperimentLoader: 	... 15 more
08-29 10:23:54.708  3749  4085 E ExperimentLoader: Caused by: faj: BadAuthentication
08-29 10:23:54.708  3749  4085 E ExperimentLoader: 	at fal.a(PG:38)
08-29 10:23:54.708  3749  4085 E ExperimentLoader: 	at jdj.a(PG:4089)
,08-29 10:23:54.708  3749  4085 E ExperimentLoader: 	... 17 more
,08-29 10:23:54.817   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 129451, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-29 10:23:56.351  4023  4073 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 10:23:56.351  4023  4073 I jxcore-log: 
,08-29 10:23:56.354  4023  4073 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 10:23:56.354  4023  4073 I jxcore-log: 
,08-29 10:23:56.364  4023  4073 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:23:56.364  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:23:56.364  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:23:56.364  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:23:56.364  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:23:56.364  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:23:56.364  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:23:56.364  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:23:56.370  4023  4073 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 10:23:56.372  4023  4073 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 10:23:56.372  4023  4073 I jxcore-log: 
08-29 10:23:56.374  4023  4073 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 10:23:56.374  4023  4073 I jxcore-log: 
,08-29 10:23:56.869  4023  4073 D executeNativeTests: Running unit tests
,08-29 10:23:56.927  4023  4073 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 10:23:56.927  4023  4073 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c6366 added. We now have 2 listener(s)
,08-29 10:23:56.928  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 10:23:56.928  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 10:23:56.929  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 10:23:56.929  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:23:56.929  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 added. We now have 2 listener(s)
08-29 10:23:56.929  4023  4073 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:23:56.929  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 10:23:56.932  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:23:56.947  4023  4073 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-29 10:23:56.947  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:23:56.947  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:23:56.947  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:23:56.947  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:23:56.947  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:23:56.947  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true,
08-29 10:23:56.947  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:23:56.950  4023  4073 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 10:23:56.950  4023  4073 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 10:23:56.952  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-29 10:23:56.954  4023  4073 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 10:23:56.954  4023  4073 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 10:23:56.955  4023  4073 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-29 10:23:56.956  4023  4073 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed,
08-29 10:23:56.956  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 10:23:56.956  4023  4073 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 10:23:56.956  4023  4073 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 10:23:56.956  4023  4073 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:23:56.957  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:23:56.957  4023  4073 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:23:56.957  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 10:23:56.957  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:56.957  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:23:56.957  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 10:23:56.958  4023  4073 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c6366 removed from the list
08-29 10:23:56.958  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:56.958  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 removed from the list
08-29 10:23:56.958  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:23:56.959  4023  4073 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:23:56.959  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:56.960  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:56.960  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:56.962  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:23:56.962  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:23:56.962  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:56.962  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
08-29 10:23:56.964  4023  4073 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-29 10:23:56.964  4023  4073 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:23:56.965  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:23:56.965  4023  4073 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:23:56.965  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:23:56.965  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:56.965  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:23:56.965  4023  4073 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c6366 not in the list
,08-29 10:23:56.965  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:23:56.965  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
,08-29 10:23:56.967  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-29 10:23:56.968  4023  4073 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 10:23:56.968  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:23:56.968  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:56.968  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:23:56.968  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:56.972  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:23:56.972  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:23:56.972  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:56.972  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
08-29 10:23:56.976  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 10:23:56.976  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-29 10:23:56.976  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 10:23:56.976  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 10:23:56.976  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 10:23:56.976  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 10:23:56.976  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 10:23:56.976  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 10:23:56.976  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 10:23:56.977  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 10:23:56.977  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 10:23:56.977  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 10:23:56.977  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 10:23:56.977  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 10:23:56.977  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 10:23:56.977  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 10:23:56.977  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 10:23:56.977  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 10:23:56.977  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 10:23:56.977  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-29 10:23:56.977  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 10:23:56.977  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 10:23:56.977  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 10:23:56.977  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 10:23:56.977  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 10:23:56.977  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 10:23:56.977  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 10:23:56.977  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 10:23:56.978  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 10:23:56.978  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 10:23:56.978  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 10:23:56.978  4023  4073 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:23:56.978  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:23:56.978  4023  4073 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:23:56.978  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:23:56.978  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:23:56.978  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:56.978  4023  4073 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c6366 not in the list
08-29 10:23:56.978  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:56.978  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
08-29 10:23:56.978  4023  4073 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:23:56.978  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:56.978  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:56.978  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:56.978  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:56.980  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:23:56.980  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:23:56.980  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:56.981  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
08-29 10:23:56.982  4023  4073 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-29 10:23:56.983  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:23:56.990  4023  4073 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:23:56.990  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:23:56.990  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:23:56.990  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:23:56.990  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:23:56.990  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:23:56.990  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:23:56.990  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:23:56.994  4023  4073 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 10:23:56.994  4023  4073 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 10:23:56.994  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 10:23:56.994  4023  4073 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 10:23:56.995  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 10:23:56.995  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:23:56.995  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 10:23:57.000  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:23:57.002  4023  4073 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 10:23:57.002  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 10:23:57.004  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:23:57.009  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 10:23:57.011  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 10:23:57.011  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 10:23:57.014  4023  4073 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-29 10:23:57.018  4023  4073 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-29 10:23:57.019  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 10:23:57.019  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 10:23:57.020  4023  4073 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 10:23:57.021  4023  4073 D BluetoothAdapter: STATE_ON
,08-29 10:23:57.031  2689  2875 D BtGatt.GattService: registerClient() - UUID=ce37a380-68d0-4c32-936b-47ff9247ac33
,08-29 10:23:57.033  2689  2725 D BtGatt.GattService: onClientRegistered() - UUID=ce37a380-68d0-4c32-936b-47ff9247ac33, clientIf=5
,08-29 10:23:57.034  4023  4034 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 10:23:57.035  2689  2701 D BtGatt.GattService: start scan with filters
,08-29 10:23:57.040  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 10:23:57.040  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 10:23:57.041  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 10:23:57.041  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 10:23:57.041  2689  2730 D BtGatt.ScanManager: handling starting scan
,08-29 10:23:57.045  4023  4073 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 10:23:57.045  2689  2730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b0902c
08-29 10:23:57.046  4023  4073 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 10:23:57.046  4023  4023 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 10:23:57.047  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 10:23:57.050  4023  4073 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 10:23:57.054  2689  2725 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 10:23:57.054  2689  2725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:23:57.056  2689  2730 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 10:23:57.057  4023  4073 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 10:23:57.058  4023  4073 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 10:23:57.058  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 10:23:57.058  4023  4073 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 10:23:57.058  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:23:57.058  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 10:23:57.058  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 10:23:57.058  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 10:23:57.058  4023  4073 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 10:23:57.059  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 10:23:57.060  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 10:23:57.060  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 10:23:57.061  4023  4073 D BluetoothAdapter: STATE_ON
,08-29 10:23:57.062  2689  2874 D BtGatt.GattService: stopScan() - queue size =1
08-29 10:23:57.063  2689  2700 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 10:23:57.063  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 10:23:57.064  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-29 10:23:57.064  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 10:23:57.064  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 10:23:57.064  2689  2725 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 10:23:57.064  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 10:23:57.064  2689  2725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:23:57.065  2689  2730 D BtGatt.ScanManager: Starting BLE batch scan
08-29 10:23:57.066  4023  4073 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 10:23:57.066  2689  2730 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 10:23:57.066  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 10:23:57.066  4023  4073 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 10:23:57.067  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 10:23:57.068  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:23:57.069  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 10:23:57.069  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:23:57.070  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:23:57.070  4023  4073 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c6366 not in the list
08-29 10:23:57.070  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:23:57.070  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
,08-29 10:23:57.070  4023  4073 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:23:57.070  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:57.070  4023  4023 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:23:57.071  4023  4023 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 10:23:57.071  4023  4023 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 10:23:57.071  4023  4073 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 10:23:57.074  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:23:57.076  2689  2725 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 10:23:57.077  2689  2725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:23:57.084  4023  4073 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:23:57.084  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:23:57.084  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:23:57.084  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:23:57.084  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:23:57.084  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:23:57.084  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:23:57.084  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:23:57.086  2689  2725 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 10:23:57.086  2689  2725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:23:57.087  4023  4073 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 10:23:57.088  4023  4073 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 10:23:57.088  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 10:23:57.088  4023  4073 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-29 10:23:57.088  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 10:23:57.088  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:23:57.088  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 10:23:57.091  4023  4073 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 10:23:57.091  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 10:23:57.093  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-29 10:23:57.098  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:23:57.098  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 10:23:57.099  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 10:23:57.099  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 10:23:57.100  2689  2725 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
08-29 10:23:57.100  2689  2725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:23:57.100  2689  2730 D BtGatt.ScanManager: stopping BLe Batch
,08-29 10:23:57.102  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 10:23:57.102  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 10:23:57.102  4023  4073 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 10:23:57.103  4023  4073 D BluetoothAdapter: STATE_ON
,08-29 10:23:57.105  2689  2701 D BtGatt.GattService: registerClient() - UUID=a1552639-4376-45ea-9ade-5f0eb4c83ba6
,08-29 10:23:57.106  2689  2725 D BtGatt.GattService: onClientRegistered() - UUID=a1552639-4376-45ea-9ade-5f0eb4c83ba6, clientIf=5
08-29 10:23:57.107  4023  4035 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 10:23:57.107  2689  2853 D BtGatt.GattService: start scan with filters
,08-29 10:23:57.110  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 10:23:57.110  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 10:23:57.110  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 10:23:57.110  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 10:23:57.111  2689  2725 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 10:23:57.111  2689  2725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:23:57.112  2689  2730 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 10:23:57.113  4023  4073 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 10:23:57.113  4023  4023 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 10:23:57.113  4023  4073 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 10:23:57.114  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 10:23:57.116  4023  4073 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 10:23:57.118  4023  4073 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 10:23:57.119  4023  4073 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 10:23:57.118  2689  2725 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 10:23:57.119  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 10:23:57.119  4023  4073 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 10:23:57.119  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:23:57.122  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 10:23:57.126  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-29 10:23:57.129  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 10:23:57.119  2689  2725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:23:57.129  4023  4073 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-29 10:23:57.129  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 10:23:57.129  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 10:23:57.129  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 10:23:57.130  4023  4073 D BluetoothAdapter: STATE_ON
08-29 10:23:57.130  2689  2875 D BtGatt.GattService: stopScan() - queue size =0
08-29 10:23:57.130  2689  2701 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 10:23:57.131  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 10:23:57.131  2689  2730 D BtGatt.ScanManager: handling starting scan
08-29 10:23:57.131  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-29 10:23:57.131  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 10:23:57.131  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 10:23:57.131  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED],
08-29 10:23:57.131  4023  4073 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 10:23:57.132  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 10:23:57.132  4023  4073 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-29 10:23:57.132  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 10:23:57.132  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:23:57.135  4023  4023 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:23:57.135  4023  4023 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:23:57.136  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:23:57.136  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.136  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:23:57.136  4023  4073 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c6366 not in the list
08-29 10:23:57.136  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:57.136  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
08-29 10:23:57.136  4023  4073 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:23:57.139  2689  2725 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 10:23:57.139  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:57.139  2689  2725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:23:57.136  4023  4023 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 10:23:57.139  2689  2730 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 10:23:57.139  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.139  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:23:57.141  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:23:57.141  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:23:57.141  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:57.141  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
08-29 10:23:57.143  4023  4073 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-29 10:23:57.144  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:23:57.145  2689  2725 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 10:23:57.145  2689  2725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:23:57.146  2689  2730 D BtGatt.ScanManager: Starting BLE batch scan
08-29 10:23:57.146  2689  2730 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 10:23:57.156  4023  4073 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:23:57.156  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:23:57.156  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:23:57.156  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:23:57.156  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:23:57.156  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:23:57.156  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:23:57.156  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:23:57.160  4023  4073 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 10:23:57.160  4023  4073 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 10:23:57.161  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 10:23:57.161  4023  4073 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-29 10:23:57.162  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 10:23:57.162  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:23:57.162  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 10:23:57.162  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:23:57.164  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:23:57.164  2689  2725 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 10:23:57.165  2689  2725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:23:57.165  4023  4073 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 10:23:57.165  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 10:23:57.170  2689  2725 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 10:23:57.170  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 10:23:57.170  2689  2725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:23:57.171  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 10:23:57.171  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 10:23:57.174  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 10:23:57.174  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 10:23:57.174  4023  4073 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 10:23:57.175  4023  4073 D BluetoothAdapter: STATE_ON
,08-29 10:23:57.176  2689  2701 D BtGatt.GattService: registerClient() - UUID=6cebcfcd-7d22-401d-a12f-ce01a0b4433e
,08-29 10:23:57.177  2689  2725 D BtGatt.GattService: onClientRegistered() - UUID=6cebcfcd-7d22-401d-a12f-ce01a0b4433e, clientIf=5
,08-29 10:23:57.177  4023  4034 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 10:23:57.177  2689  2875 D BtGatt.GattService: start scan with filters
,08-29 10:23:57.178  2689  2725 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 10:23:57.178  2689  2725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:23:57.178  2689  2730 D BtGatt.ScanManager: stopping BLe Batch
,08-29 10:23:57.179  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 10:23:57.179  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 10:23:57.179  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 10:23:57.179  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 10:23:57.181  4023  4073 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 10:23:57.181  4023  4023 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 10:23:57.181  4023  4073 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 10:23:57.182  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 10:23:57.184  4023  4073 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 10:23:57.184  4023  4073 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:23:57.184  4023  4073 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-29 10:23:57.184  2689  2725 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-29 10:23:57.185  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 10:23:57.185  2689  2725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:23:57.185  4023  4073 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 10:23:57.185  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.185  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left,
08-29 10:23:57.185  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 10:23:57.185  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 10:23:57.185  4023  4073 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 10:23:57.185  2689  2730 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 10:23:57.185  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 10:23:57.187  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 10:23:57.187  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 10:23:57.188  4023  4073 D BluetoothAdapter: STATE_ON
08-29 10:23:57.188  2689  2874 D BtGatt.GattService: stopScan() - queue size =0
,08-29 10:23:57.189  2689  2875 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 10:23:57.189  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 10:23:57.189  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 10:23:57.189  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
08-29 10:23:57.189  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 10:23:57.190  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 10:23:57.190  4023  4073 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 10:23:57.190  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 10:23:57.190  4023  4073 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 10:23:57.190  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 10:23:57.191  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:23:57.191  4023  4023 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:23:57.191  4023  4023 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:23:57.191  4023  4023 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 10:23:57.192  4023  4073 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:23:57.192  4023  4073 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 10:23:57.192  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:23:57.192  4023  4073 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 10:23:57.192  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:23:57.192  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.192  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:23:57.192  4023  4073 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c6366 not in the list
,08-29 10:23:57.192  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:57.192  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
08-29 10:23:57.193  4023  4073 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:23:57.193  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:23:57.193  2689  2725 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 10:23:57.193  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.193  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:23:57.193  2689  2725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:23:57.196  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:23:57.196  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-29 10:23:57.196  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:57.196  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
08-29 10:23:57.197  4023  4073 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-29 10:23:57.197  4023  4073 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:23:57.197  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:23:57.197  4023  4073 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:23:57.197  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:23:57.197  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.197  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:57.197  4023  4073 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c6366 not in the list
08-29 10:23:57.198  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:57.198  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
08-29 10:23:57.198  4023  4073 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:23:57.198  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.198  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:57.198  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.198  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:57.199  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:23:57.199  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:23:57.199  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:57.199  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
08-29 10:23:57.199  2689  2730 D BtGatt.ScanManager: handling starting scan
08-29 10:23:57.200  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 10:23:57.200  4023  4073 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:23:57.200  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:23:57.200  4023  4073 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:23:57.200  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:23:57.200  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.200  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:23:57.200  4023  4073 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c6366 not in the list
08-29 10:23:57.200  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:57.200  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
08-29 10:23:57.200  4023  4073 D io.jxcore.node.ConnectivityMonitor: stop,
08-29 10:23:57.200  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.200  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:57.201  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.201  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:23:57.201  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 10:23:57.201  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 10:23:57.201  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:57.201  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
,08-29 10:23:57.202  4023  4073 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-29 10:23:57.202  4023  4073 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 10:23:57.202  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 10:23:57.202  4023  4073 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:23:57.202  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-29 10:23:57.202  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:23:57.202  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:57.202  4023  4073 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c6366 not in the list
08-29 10:23:57.202  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:23:57.202  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
08-29 10:23:57.202  4023  4073 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 10:23:57.203  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.203  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:57.203  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:23:57.203  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:57.203  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 10:23:57.203  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:23:57.203  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:57.203  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
08-29 10:23:57.204  4023  4073 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-29 10:23:57.204  4023  4073 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:23:57.204  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 10:23:57.204  4023  4073 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:23:57.204  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:23:57.204  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.204  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:57.204  4023  4073 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c6366 not in the list
08-29 10:23:57.204  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:57.205  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
08-29 10:23:57.205  4023  4073 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:23:57.205  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.205  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:23:57.205  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.205  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:57.206  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:23:57.206  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:23:57.206  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:23:57.206  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
08-29 10:23:57.207  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 10:23:57.208  4023  4073 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 10:23:57.208  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 10:23:57.208  4023  4073 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-29 10:23:57.208  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 10:23:57.208  4023  4073 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 10:23:57.209  4023  4073 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:23:57.209  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:23:57.209  4023  4073 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 10:23:57.209  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:23:57.209  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.209  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:57.210  4023  4073 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c6366 not in the list
,08-29 10:23:57.210  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:57.210  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
08-29 10:23:57.210  4023  4073 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 10:23:57.210  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.210  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:57.210  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.210  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:57.211  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-29 10:23:57.211  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:23:57.211  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:57.211  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
08-29 10:23:57.211  4023  4073 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-29 10:23:57.211  4023  4073 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 10:23:57.211  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 10:23:57.215  4023  4073 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 10:23:57.215  4023  4073 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,08-29 10:23:57.215  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 10:23:57.215  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 10:23:57.215  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 10:23:57.215  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 10:23:57.215  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 10:23:57.215  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 10:23:57.215  2689  2725 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 10:23:57.216  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 10:23:57.216  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 10:23:57.216  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 10:23:57.216  2689  2725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:23:57.216  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 10:23:57.217  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-29 10:23:57.217  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 10:23:57.218  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 10:23:57.218  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-29 10:23:57.218  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 10:23:57.218  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 10:23:57.219  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 10:23:57.219  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 10:23:57.219  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810],
08-29 10:23:57.219  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 10:23:57.220  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 10:23:57.220  2689  2730 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 10:23:57.220  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 10:23:57.221  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 10:23:57.223  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 10:23:57.225  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 10:23:57.226  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-29 10:23:57.226  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 10:23:57.226  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 10:23:57.227  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 10:23:57.227  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-29 10:23:57.227  4023  4073 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 10:23:57.227  2689  2725 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 10:23:57.227  2689  2725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:23:57.228  2689  2730 D BtGatt.ScanManager: Starting BLE batch scan
08-29 10:23:57.228  2689  2730 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 10:23:57.228  4023  4073 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 10:23:57.228  4023  4073 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-29 10:23:57.229  4023  4073 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 10:23:57.229  4023  4073 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 10:23:57.229  4023  4073 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,08-29 10:23:57.229  4023  4073 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 10:23:57.230  4023  4073 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 10:23:57.230  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-29 10:23:57.241  2689  2725 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 10:23:57.241  2689  2725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:23:57.241  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-29 10:23:57.243  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,08-29 10:23:57.244  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-29 10:23:57.245  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,08-29 10:23:57.245  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,08-29 10:23:57.245  4023  4073 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55),
,08-29 10:23:57.246  2689  2725 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 10:23:57.246  4023  4073 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 10:23:57.246  2689  2725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-29 10:23:57.247  4023  4073 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-29 10:23:57.247  4023  4073 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 10:23:57.247  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 10:23:57.247  4023  4073 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 10:23:57.247  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:23:57.247  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.248  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:23:57.248  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-29 10:23:57.248  4023  4073 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c6366 not in the list
,08-29 10:23:57.248  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:23:57.248  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
08-29 10:23:57.248  4023  4073 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:23:57.248  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.248  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:57.249  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:23:57.249  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:23:57.249  4023  4086 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 442)
08-29 10:23:57.249  4023  4087 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 442
08-29 10:23:57.250  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:23:57.250  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:23:57.250  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:23:57.250  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
08-29 10:23:57.251  4023  4073 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-29 10:23:57.251  4023  4073 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:23:57.251  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:23:57.251  4023  4073 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:23:57.251  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:23:57.251  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.251  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:23:57.251  4023  4073 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c6366 not in the list
08-29 10:23:57.251  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:57.252  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
08-29 10:23:57.252  4023  4073 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:23:57.252  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.252  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:23:57.252  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.252  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:57.253  4023  4086 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 10:23:57.254  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:23:57.254  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 10:23:57.254  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:57.254  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
08-29 10:23:57.255  4023  4073 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-29 10:23:57.256  4023  4073 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:23:57.256  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 10:23:57.256  4023  4073 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:23:57.256  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:23:57.256  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.257  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:57.257  4023  4073 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c6366 not in the list
,08-29 10:23:57.257  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:57.257  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
08-29 10:23:57.257  4023  4073 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:23:57.257  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:23:57.257  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:57.257  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.257  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:57.260  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:23:57.260  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:23:57.260  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:23:57.260  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
08-29 10:23:57.261  4023  4073 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 10:23:57.261  4023  4073 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-29 10:23:57.262  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 10:23:57.262  4023  4073 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 10:23:57.262  4023  4073 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 10:23:57.262  4023  4073 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,08-29 10:23:57.262  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 10:23:57.262  4023  4073 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-29 10:23:57.262  4023  4073 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 10:23:57.262  4023  4073 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 10:23:57.262  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 10:23:57.262  4023  4073 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,08-29 10:23:57.263  4023  4073 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 10:23:57.263  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:23:57.263  4023  4073 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:23:57.263  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:23:57.263  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:23:57.263  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:57.263  4023  4073 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c6366 not in the list
08-29 10:23:57.263  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:57.263  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
08-29 10:23:57.264  4023  4073 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:23:57.264  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.264  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:57.264  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.264  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:57.265  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:23:57.265  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:23:57.265  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:57.265  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
08-29 10:23:57.266  2689  2725 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 10:23:57.266  2689  2725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:23:57.266  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:23:57.266  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.266  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:23:57.266  4023  4073 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c6366 not in the list
08-29 10:23:57.266  2689  2730 D BtGatt.ScanManager: stopping BLe Batch
,08-29 10:23:57.266  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:57.266  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
08-29 10:23:57.266  4023  4073 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:23:57.266  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:23:57.266  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:23:57.266  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:23:57.266  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
08-29 10:23:57.266  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 10:23:57.266  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.266  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:57.267  4023  4073 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c6366 not in the list
,08-29 10:23:57.267  4023  4073 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:23:57.267  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:23:57.267  4023  4073 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 10:23:57.267  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:23:57.267  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:23:57.267  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:57.267  4023  4073 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c6366 not in the list
,08-29 10:23:57.267  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:57.267  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
08-29 10:23:57.267  4023  4073 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 10:23:57.267  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.267  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:23:57.267  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.267  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:57.268  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 10:23:57.268  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:23:57.268  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:23:57.268  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
08-29 10:23:57.269  4023  4073 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-29 10:23:57.269  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:23:57.270  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 10:23:57.270  4023  4073 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-29 10:23:57.271  4023  4073 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 10:23:57.271  4023  4023 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-29 10:23:57.271  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 10:23:57.271  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 10:23:57.271  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 10:23:57.271  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 10:23:57.271  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-29 10:23:57.271  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-29 10:23:57.271  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:57.271  4023  4073 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 10:23:57.272  4023  4023 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-29 10:23:57.272  4023  4088 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 10:23:57.273  4023  4073 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c6366 not in the list
08-29 10:23:57.273  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-29 10:23:57.273  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 10:23:57.273  4023  4073 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 10:23:57.273  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 10:23:57.273  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:23:57.273  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:57.274  4023  4088 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-29 10:23:57.274  4023  4088 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 10:23:57.274  4023  4088 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-29 10:23:57.274  4023  4073 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 10:23:57.274  4023  4023 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:23:57.275  4023  4023 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 10:23:57.275  4023  4023 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 10:23:57.275  4023  4023 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 10:23:57.275  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
,08-29 10:23:57.275  4023  4073 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:23:57.275  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:23:57.275  4023  4073 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:23:57.275  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:23:57.275  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.275  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:57.275  4023  4073 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c6366 not in the list
08-29 10:23:57.275  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:57.275  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
08-29 10:23:57.275  4023  4073 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:23:57.275  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.275  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:57.276  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.276  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:57.281  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:23:57.282  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:23:57.282  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:57.282  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
08-29 10:23:57.283  4023  4073 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-29 10:23:57.283  4023  4073 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 10:23:57.284  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 10:23:57.284  2689  2725 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 10:23:57.284  2689  2725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:23:57.284  2689  2730 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 10:23:57.285  4023  4073 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 10:23:57.286  4023  4073 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:23:57.286  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:23:57.286  4023  4073 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The, current state already matches the desired outcome of this operation, skipping...
08-29 10:23:57.287  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:23:57.287  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.287  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:57.287  4023  4073 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c6366 not in the list
08-29 10:23:57.287  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:57.287  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
08-29 10:23:57.287  4023  4073 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:23:57.287  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.287  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:57.287  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.287  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:57.289  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:23:57.289  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:23:57.289  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:57.289  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
08-29 10:23:57.291  4023  4073 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:23:57.291  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:23:57.291  4023  4073 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:23:57.292  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:23:57.292  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.292  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:57.292  4023  4073 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c6366 not in the list
08-29 10:23:57.292  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:57.292  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
08-29 10:23:57.292  4023  4073 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:23:57.292  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.292  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:57.292  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.292  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:57.293  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:23:57.293  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:23:57.293  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:57.293  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
08-29 10:23:57.294  2689  2725 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 10:23:57.294  2689  2725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:23:57.295  4023  4073 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:23:57.295  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:23:57.295  4023  4073 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:23:57.295  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:23:57.295  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.295  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:57.295  4023  4073 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c6366 not in the list
08-29 10:23:57.295  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:57.295  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
08-29 10:23:57.295  4023  4073 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:23:57.296  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.296  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:57.296  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:57.296  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:57.296  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:23:57.296  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:23:57.296  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:57.296  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71396a7 not in the list
08-29 10:23:57.297  4023  4073 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-29 10:23:57.297  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 10:23:57.297  4023  4073 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-29 10:23:57.297  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 10:23:57.297  4023  4073 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 10:23:57.297  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 10:23:57.299  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 10:23:57.299  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-29 10:23:57.299  4023  4073 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-29 10:23:57.299  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 10:23:57.299  4023  4073 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-29 10:23:57.299  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 10:23:57.299  4023  4073 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 10:23:57.300  4023  4073 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-29 10:23:57.300  4023  4073 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 10:23:57.300  4023  4073 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-29 10:23:57.300  4023  4073 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-29 10:23:57.300  4023  4073 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-29 10:23:57.300  4023  4073 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-29 10:23:57.301  4023  4073 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-29 10:23:57.301  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:23:57.301  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@736db31 added. We now have 2 listener(s)
08-29 10:23:57.301  4023  4073 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:23:57.302  4023  4073 D BluetoothAdapter: enable(): BT is already enabled..!
08-29 10:23:57.302   872  2161 D WifiService: setWifiEnabled: true pid=4023, uid=10000
08-29 10:23:57.302   872  2161 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 10:23:57.303  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:23:57.303  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@20a7216 added. We now have 3 listener(s)
08-29 10:23:57.303  4023  4073 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:23:57.307  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:23:57.307  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@397797 added. We now have 4 listener(s)
08-29 10:23:57.307  4023  4073 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:23:57.308  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:23:57.308  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b21d84 added. We now have 5 listener(s)
08-29 10:23:57.308  4023  4073 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:23:57.309   872  2164 D WifiService: setWifiEnabled: false pid=4023, uid=10000
08-29 10:23:57.309   872  2164 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 10:23:57.312  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:23:57.313  2689  2721 D BluetoothAdapterState: Current state: ON, message: 23
08-29 10:23:57.313  2689  2721 D BluetoothAdapterProperties: Setting state to 13
08-29 10:23:57.313  2689  2721 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 10:23:57.314  2689  2721 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 10:23:57.315  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:23:57.315  2689  2721 I BluetoothAdapterState: Entering PendingCommandState
08-29 10:23:57.315  4023  4073 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:23:57.315  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:23:57.315  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:23:57.315  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:23:57.315  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:23:57.315  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:23:57.315  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:23:57.315  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 10:23:57.316  2689  2725 D BluetoothAdapterProperties: Scan Mode:20
08-29 10:23:57.316  2689  2721 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-29 10:23:57.317  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:23:57.317  4023  4073 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 10:23:57.317  4023  4073 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 10:23:57.321  2689  2689 D HeadsetService: Received stop request...Stopping profile...
08-29 10:23:57.324  1909  1920 D BluetoothHeadset: Proxy object disconnected
08-29 10:23:57.324  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:23:57.325  1359  2049 D BluetoothHeadset: Proxy object disconnected
08-29 10:23:57.325  1359  1359 D HeadsetProfile: Bluetooth service disconnected
08-29 10:23:57.326  2689  2689 V BluetoothAdapterState: isTurningOff()=true
08-29 10:23:57.326  2689  2689 V BluetoothAdapterState: isTurningOn()=false
08-29 10:23:57.326  2689  2689 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:23:57.326  2689  2689 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:23:57.326  2689  2689 D A2dpService: Received stop request...Stopping profile...
08-29 10:23:57.327   872   872 D BluetoothHeadset: Proxy object disconnected
08-29 10:23:57.327  2689  2856 D A2dpStateMachine: Exit Disconnected: -1
08-29 10:23:57.327   872   872 D BluetoothHeadset: Proxy object disconnected
08-29 10:23:57.327   872   872 D BluetoothHeadset: Proxy object disconnected
08-29 10:23:57.328  1485  1485 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 10:23:57.330   872  1304 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 10:23:57.331   872  1304 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-29 10:23:57.331   872  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 10:23:57.331   872  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 10:23:57.335  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:23:57.338  4023  4023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:23:57.339  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:23:57.339  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:23:57.339  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:23:57.339  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:23:57.339  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:23:57.339  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:23:57.339  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:23:57.339  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 10:23:57.339  4023  4023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:23:57.339   872  1962 D DhcpClient: Clearing IP address
08-29 10:23:57.339  4023  4023 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 10:23:57.339   370   870 D CommandListener: Clearing all IP addresses on wlan0
08-29 10:23:57.342  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:23:57.342   370   870 D CommandListener: Setting iface cfg
08-29 10:23:57.343   872  1965 D DhcpClient: Receive thread stopped
08-29 10:23:57.345  1527  2169 V NativeCrypto: Read error: ssl=0xaeb6ae00: I/O error during system call, Connection timed out
08-29 10:23:57.346  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:23:57.349  1527  2169 V NativeCrypto: SSL shutdown failed: ssl=0xaeb6ae00: I/O error during system call, Broken pipe
08-29 10:23:57.351  4023  4023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 10:23:57.351  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:23:57.351  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:23:57.351  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:23:57.351  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:23:57.351  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:23:57.351  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:23:57.351  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:23:57.351  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:23:57.352  4023  4023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 10:23:57.352  4023  4023 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:23:57.352   872   882 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-29 10:23:57.352   872  1948 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
,08-29 10:23:57.355   872  1948 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-29 10:23:57.356   872  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
08-29 10:23:57.356   872  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-29 10:23:57.357   872  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-29 10:23:57.359   872   885 I ActivityManager: Start proc 4091:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-29 10:23:57.361  1359  1359 D BluetoothA2dp: Proxy object disconnected
08-29 10:23:57.361   872   872 D BluetoothA2dp: Proxy object disconnected
,08-29 10:23:57.364   872  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 10:23:57.364   872  1304 D WifiStateMachine: Start Disconnecting Watchdog 1
08-29 10:23:57.364   872  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-29 10:23:57.365   872  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 10:23:57.369  2689  2689 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 10:23:57.369  2689  2689 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 10:23:57.369  2689  2725 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 10:23:57.369  2689  2838 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 10:23:57.370  2689  2838 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 10:23:57.370  2689  2838 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 10:23:57.370  2689  2725 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-29 10:23:57.370  2689  2689 D HidService: Received stop request...Stopping profile...
,08-29 10:23:57.370  2689  2689 D HidService: Stopping Bluetooth HidService
,08-29 10:23:57.370   370   870 D CommandListener: Clearing all IP addresses on wlan0
,08-29 10:23:57.371   397   397 E Parcel  : Reading a NULL string not supported here.
,08-29 10:23:57.374  2689  2689 D HealthService: Received stop request...Stopping profile...
,08-29 10:23:57.375  2689  2689 D PanService: Received stop request...Stopping profile...
08-29 10:23:57.375   872  1306 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-29 10:23:57.376  2689  2689 V BluetoothAdapterState: isTurningOff()=true
08-29 10:23:57.376  2689  2689 V BluetoothAdapterState: isTurningOn()=false
08-29 10:23:57.376  2689  2689 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 10:23:57.376  2689  2689 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:23:57.377  2689  2689 D BluetoothMapService: onReceive
08-29 10:23:57.377  2689  2689 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:23:57.377  2689  2689 D BluetoothMapService: STATE_TURNING_OFF
08-29 10:23:57.378  2689  2689 D BluetoothMapService: Received stop request...Stopping profile...
,08-29 10:23:57.378  2689  2689 D BluetoothMapService: stop()
08-29 10:23:57.381  1359  1359 D BluetoothInputDevice: Proxy object disconnected
08-29 10:23:57.381  1359  1359 D HidProfile: Bluetooth service disconnected
08-29 10:23:57.381  1359  1359 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-29 10:23:57.381  1359  1359 D PanProfile: Bluetooth service disconnected
08-29 10:23:57.381  2689  2689 D BluetoothMapAppObserver: deinitObservers()
,08-29 10:23:57.382  2689  2689 D BluetoothMapAppObserver: removeReceiver()
,08-29 10:23:57.383  1359  1359 D BluetoothMap: Proxy object disconnected
08-29 10:23:57.383  1359  1359 D MapProfile: Bluetooth service disconnected
08-29 10:23:57.384  2689  2838 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 10:23:57.384  2689  2725 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-29 10:23:57.384  2689  2838 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 10:23:57.384  2689  2838 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-29 10:23:57.384  2689  2838 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 10:23:57.384  2689  2838 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 10:23:57.384  2689  2838 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-29 10:23:57.384  2689  2689 V BluetoothAdapterState: isTurningOff()=true
08-29 10:23:57.384  2689  2689 V BluetoothAdapterState: isTurningOn()=false
08-29 10:23:57.384  2689  2689 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:23:57.384  2689  2689 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:23:57.385  2689  2689 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 10:23:57.385  2689  2689 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-29 10:23:57.385  2689  2689 V BluetoothAdapterState: isTurningOff()=true
08-29 10:23:57.385  2689  2689 V BluetoothAdapterState: isTurningOn()=false
08-29 10:23:57.385  2689  2689 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:23:57.385  2689  2689 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:23:57.385  2689  2689 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 10:23:57.385  2689  2725 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 10:23:57.385  2689  2725 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 10:23:57.386  2689  2689 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 10:23:57.386  2689  2689 V BluetoothAdapterState: isTurningOff()=true
08-29 10:23:57.386  2689  2689 V BluetoothAdapterState: isTurningOn()=false
08-29 10:23:57.386  2689  2689 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:23:57.386  2689  2689 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 10:23:57.386  2689  2689 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 10:23:57.386  2689  2689 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 10:23:57.390   872  1304 D WifiConfigStore: Retrieve network priorities after PNO.
08-29 10:23:57.390  2689  2689 I BtOppRfcommListener: stopping Accept Thread
08-29 10:23:57.390  2689  3614 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 10:23:57.391  2689  3614 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 10:23:57.392  4023  4023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 10:23:57.392  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:23:57.392  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:23:57.392  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:23:57.392  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:23:57.392  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:23:57.392  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:23:57.392  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:23:57.392  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:23:57.393  4023  4023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:23:57.393  4023  4023 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:23:57.394  2689  2689 D BluetoothMapService: MAP Service closeService in
08-29 10:23:57.394  2689  2689 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 10:23:57.394  2689  2689 D ObexServerSockets0: shutdown(block = true)
,08-29 10:23:57.394  2689  2876 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-29 10:23:57.395  4023  4023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:23:57.395  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:23:57.395  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:23:57.395  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:23:57.395  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:23:57.395  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:23:57.395  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:23:57.395  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:23:57.395  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:23:57.395  2689  2689 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 10:23:57.395  2689  2847 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-29 10:23:57.395  4023  4023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 10:23:57.395  4023  4023 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:23:57.395  2689  2689 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 10:23:57.397   872  1304 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 10:23:57.399  2689  2877 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 10:23:57.400  2689  2689 V BluetoothAdapterState: isTurningOff()=true
08-29 10:23:57.400  2689  2689 V BluetoothAdapterState: isTurningOn()=false
08-29 10:23:57.400  2689  2689 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 10:23:57.400  2689  2689 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:23:57.400  2689  2721 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 10:23:57.401  2689  2721 D BluetoothAdapterProperties: Setting state to 15
08-29 10:23:57.401  2689  2721 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 10:23:57.401  2689  2721 I BluetoothAdapterState: Entering BleOnState
08-29 10:23:57.401  2689  2689 D BluetoothMapService: cleanup()
,08-29 10:23:57.401  1359  1372 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 10:23:57.401  2689  2689 D BluetoothMapService: MAP Service closeService in
08-29 10:23:57.402  1909  2170 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 10:23:57.402   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 10:23:57.402  1359  2049 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 10:23:57.402   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 10:23:57.402  1359  2171 D BluetoothPan: onBluetoothStateChange on: false
,08-29 10:23:57.403   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 10:23:57.403  1359  1378 D BluetoothMap: onBluetoothStateChange: up=false
08-29 10:23:57.404  2134  2335 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:23:57.405  1359  1372 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 10:23:57.405  1359  2049 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 10:23:57.406   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 10:23:57.407  2689  2721 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 10:23:57.407  2689  2721 D BluetoothAdapterProperties: Setting state to 16
08-29 10:23:57.407  2689  2721 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-29 10:23:57.407  2689  2721 D BluetoothAdapterProperties: onBleDisable
08-29 10:23:57.409  2689  2721 I BluetoothAdapterState: Entering PendingCommandState
08-29 10:23:57.409  2689  2722 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 10:23:57.410  2689  2838 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 10:23:57.410  2689  2838 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 10:23:57.410  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:23:57.410  2689  2725 D BluetoothAdapterProperties: Scan Mode:20
08-29 10:23:57.410  4023  4086 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 442)
08-29 10:23:57.412  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:23:57.413  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:23:57.415  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:23:57.426   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 10:23:57.444   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 10:23:57.446   872  1306 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-29 10:23:57.447   872  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 10:23:57.452   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-29 10:23:57.455  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:23:57.456  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:23:57.464  3615  3615 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@9c63e16 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-29 10:23:57.497  4091  4091 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-29 10:23:57.506  4091  4091 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 10:23:57.511  1527  1527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 10:23:57.514   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e05ff03:true
,08-29 10:23:57.524   872  2744 I ActivityManager: Start proc 4112:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-29 10:23:57.532   370   870 E Netd    : netlink response contains error (No such file or directory)
,08-29 10:23:57.533   872  1306 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 10:23:57.551  4091  4091 D LocalBluetoothProfileManager: Adding local MAP profile
,08-29 10:23:57.559  4112  4112 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-29 10:23:57.560  4091  4091 D BluetoothMap: Create BluetoothMap proxy object
,08-29 10:23:57.564  4091  4091 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-29 10:23:57.578  4091  4091 D DockEventReceiver: finishStartingService: stopping service
,08-29 10:23:57.585   872   882 I ActivityManager: Killing 3256:com.google.android.talk/u0a61 (adj 15): empty #17
,08-29 10:23:57.614  2689  2725 I bt_hci  : shut_down
,08-29 10:23:57.649  2689  2746 I bt_vendor: low_power_mode_cb
,08-29 10:23:57.679  2689  2746 D bt_hwcfg: hw_epilog_process
,08-29 10:23:57.686  2689  2746 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-29 10:23:57.686  2689  2746 I bt_vendor: epilog_cb
,08-29 10:23:57.686  2689  2746 I bt_hci  : epilog_finished_callback
,08-29 10:23:57.693  2689  2725 I bt_hci_h4: hal_close
,08-29 10:23:57.693  2689  2725 I bt_userial_vendor: device fd = 51 close
,08-29 10:23:57.734  4112  4112 D StrictMode: StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 10:23:57.734  4112  4112 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 10:23:57.734  4112  4112 D StrictMode: StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 10:23:57.734  4112  4112 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 10:23:57.734  4112  4112 D StrictMode: StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 10:23:57.734  4112  4112 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 10:23:57.734  4112  4112 D StrictMode: StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 10:23:57.734  4112  4112 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 10:23:57.734  4112  4112 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 10:23:57.735  4112  4112 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 10:23:57.735  4112  4112 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.google.r.k.d(PG:583)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 10:23:57.735  4112  4112 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 10:23:57.735  4112  4112 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 10:23:57.735  4112  4112 D StrictMode: StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 10:23:57.735  4112  4112 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 10:23:57.735  4112  4112 D StrictMode: StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 10:23:57.735  4112  4112 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at android.app.ActivityThread$H.,handleMessage(ActivityThread.java:1405)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 10:23:57.735  4112  4112 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 10:23:57.771   872  1416 I ActivityManager: Start proc 4142:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-29 10:23:57.772   872  1416 I ActivityManager: Killing 3755:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-29 10:23:57.775  4023  4023 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 10:23:57.821  2689  2722 D bt_stack_manager: event_shut_down_stack finished.
,08-29 10:23:57.821  2689  2721 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 10:23:57.833  2689  2689 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 10:23:57.833  2689  2721 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-29 10:23:57.834  2689  2689 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 10:23:57.835  2689  2689 D BtGatt.GattService: stop()
,08-29 10:23:57.835  2689  2689 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 10:23:57.838  2689  2689 V BluetoothAdapterState: isTurningOff()=false
,08-29 10:23:57.838  2689  2689 V BluetoothAdapterState: isTurningOn()=false
,08-29 10:23:57.838  2689  2689 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:23:57.839  2689  2689 V BluetoothAdapterState: isBleTurningOff()=true
,08-29 10:23:57.839  2689  2721 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-29 10:23:57.840  2689  2721 D BluetoothAdapterProperties: Setting state to 10
,08-29 10:23:57.840  2689  2721 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-29 10:23:57.842  2689  2721 I BluetoothAdapterState: Entering OffState
,08-29 10:23:57.843   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-29 10:23:57.869  2689  2689 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-29 10:23:57.869  2689  2689 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 10:23:57.869  2689  2689 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-29 10:23:57.870  2689  2722 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-29 10:23:57.872  2689  2722 D bt_stack_manager: event_clean_up_stack finished.
,08-29 10:23:57.878  4142  4142 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-29 10:23:57.882  2689  2689 I art     : System.exit called, status: 0
,08-29 10:23:57.882  2689  2689 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 10:23:57.943   872  1694 I ActivityManager: Process com.android.bluetooth (pid 2689) has died
,08-29 10:23:58.142  4112  4132 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-29 10:23:58.149  4142  4162 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
08-29 10:23:58.150  4142  4162 I Babel_SMS: MmsConfig.loadMmsSettings
08-29 10:23:58.153  4142  4162 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
08-29 10:23:58.153  4142  4162 I Babel_SMS: MmsConfig.loadFromDatabase
,08-29 10:23:58.203  4142  4162 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-29 10:23:58.203  4142  4162 I Babel_SMS: MmsConfig.loadFromResources
08-29 10:23:58.204  4142  4162 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
08-29 10:23:58.205  4142  4162 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-29 10:23:58.240  4142  4142 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 10:23:58.243  4142  4142 I Babel_Crash: startup - clean
,08-29 10:23:58.266  4142  4142 I Babel_telephony: TeleModule.launchCompleted
,08-29 10:23:58.279   872  1929 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-29 10:23:58.300  4142  4142 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-29 10:23:58.313  4142  4142 W Babel   : BAM#gBA: invalid account id: -1
,08-29 10:23:58.313  4142  4142 W Babel   : BAM#gBA: invalid account id: -1
08-29 10:23:58.313  4142  4142 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null,
,08-29 10:23:58.328   872  1379 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-29 10:23:58.326  4142  4167 I Babel   : deleted: false for 0
,08-29 10:23:58.357   872  2161 I ActivityManager: Start proc 4169:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-29 10:23:58.359   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1ef235b:true
,08-29 10:23:58.432  4169  4169 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-29 10:23:58.443  4142  4142 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 10:23:58.523  4142  4142 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-29 10:23:58.534  4169  4169 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-29 10:23:58.539  4142  4142 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 10:23:58.547  4142  4142 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 10:23:58.574  4142  4142 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 10:23:58.585  4091  4091 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 10:23:58.610  4142  4142 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-29 10:23:58.614   872  2164 I ActivityManager: Start proc 4194:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-29 10:23:58.627  4091  4091 D DockEventReceiver: finishStartingService: stopping service
,08-29 10:23:58.640   872  2164 I ActivityManager: Killing 3615:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-29 10:23:58.715  4142  4142 I vclib   : onServiceConnected
,08-29 10:23:58.759  4194  4194 D AdapterServiceConfig: Adding HeadsetService
08-29 10:23:58.759  4194  4194 D AdapterServiceConfig: Adding A2dpService
08-29 10:23:58.759  4194  4194 D AdapterServiceConfig: Adding HidService
,08-29 10:23:58.759  4194  4194 D AdapterServiceConfig: Adding HealthService
08-29 10:23:58.761  4194  4194 D AdapterServiceConfig: Adding PanService
,08-29 10:23:58.761  4194  4194 D AdapterServiceConfig: Adding GattService
08-29 10:23:58.762  4194  4194 D AdapterServiceConfig: Adding BluetoothMapService
,08-29 10:23:58.768   872  2043 I ActivityManager: Killing 3657:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-29 10:23:58.802  1527  1527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 10:23:58.840  1749  1749 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 10:23:58.847  1749  1749 D SystemUpdateService: onCreate
,08-29 10:23:58.856  1749  1749 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 10:23:58.863  1749  4206 I SystemUpdateService: active receiver: enabled
,08-29 10:23:58.880  1749  4206 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 10:23:58.881  1749  4206 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-29 10:23:58.881  1749  4206 I SystemUpdateService: now status is 0 (complete)
08-29 10:23:58.881  1749  4206 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-29 10:23:58.882  1749  4206 I SystemUpdateService: file has been verified
,08-29 10:23:58.882  1749  4206 I SystemUpdateService: OTA package size = 12249756
08-29 10:23:58.883  1749  1749 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 10:23:58.885  1749  4206 I SystemUpdateService: showing system update notification
,08-29 10:23:58.886  1749  2476 I iu.UploadsManager: num queued entries: 0
,08-29 10:23:58.887  1749  2476 I iu.UploadsManager: num updated entries: 0
,08-29 10:23:58.887  1749  2476 I iu.SyncManager: NEXT; no task
,08-29 10:23:58.903  1749  1749 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 10:23:58.905  1749  1749 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 10:23:58.921   872  2161 I ActivityManager: Start proc 4208:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-29 10:23:58.923  1749  1749 D SystemUpdateService: onDestroy
,08-29 10:23:58.962  4208  4208 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-29 10:23:58.966  4208  4208 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 10:23:58.978  4208  4208 D SprintDMHelper: simOperator: 
08-29 10:23:58.978  4208  4208 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 10:23:59.013   872   882 I ActivityManager: Start proc 4220:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-29 10:23:59.016   872   882 I ActivityManager: Killing 3691:android.process.acore/u0a5 (adj 15): empty #17
,08-29 10:23:59.167   872   883 I ActivityManager: Start proc 4235:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-29 10:23:59.175  4142  4234 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-29 10:23:59.180   872  1694 I ActivityManager: Killing 3875:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-29 10:23:59.244  4235  4235 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-29 10:23:59.293  4235  4235 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-29 10:23:59.293  4235  4235 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-29 10:23:59.293  4235  4235 I GAv4    :   adb logcat -s GAv4
,08-29 10:23:59.310  4235  4235 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-29 10:23:59.315  4235  4235 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-29 10:23:59.346  4235  4252 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-29 10:23:59.452  4235  4235 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-29 10:23:59.489  4235  4235 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-29 10:23:59.500  4235  4235 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 4551-4557)
08-29 10:23:59.500  4235  4235 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-29 10:23:59.508  4235  4235 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7e858c6}
,08-29 10:23:59.508  4235  4235 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-29 10:23:59.510  4235  4235 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-29 10:23:59.518  4235  4235 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-29 10:23:59.519  4235  4235 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-29 10:23:59.537  4235  4235 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-29 10:23:59.551  4235  4235 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 10:23:59.551  4235  4235 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 10:23:59.551  4235  4235 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 10:23:59.551  4235  4235 I Adreno  : Build Date                       : 10/20/15
08-29 10:23:59.551  4235  4235 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 10:23:59.551  4235  4235 I Adreno  : Local Branch                     : M14
08-29 10:23:59.551  4235  4235 I Adreno  : Remote Branch                    : 
08-29 10:23:59.551  4235  4235 I Adreno  : Remote Branch                    : 
08-29 10:23:59.551  4235  4235 I Adreno  : Reconstruct Branch               : 
,08-29 10:23:59.613  4235  4235 I NSApplication: Starting up...
,08-29 10:23:59.623  4235  4281 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-29 10:23:59.656   872  1379 I ActivityManager: Start proc 4286:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-29 10:23:59.657   872  1379 I ActivityManager: Killing 3888:com.android.musicfx/u0a18 (adj 15): empty #17
,08-29 10:23:59.738  4286  4286 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-29 10:23:59.929   872  2744 I ActivityManager: Killing 2239:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-29 10:24:00.320   872  2043 D WifiService: setWifiEnabled: true pid=4023, uid=10000
,08-29 10:24:00.320   872  2043 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 10:24:00.336   872  1304 D WifiConfigStore: Loading config and enabling all networks 
,08-29 10:24:00.341  4023  4023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 10:24:00.341  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:24:00.341  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:00.341  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:24:00.341  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:24:00.341  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:24:00.341  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:00.341  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:00.341  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:24:00.342  4023  4023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 10:24:00.342  4023  4023 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:24:00.345  4023  4023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:24:00.346  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:24:00.346  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:00.346  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:24:00.346  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:24:00.346  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:24:00.346  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:00.346  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:00.346  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 10:24:00.346  4023  4023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:24:00.347  4023  4023 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 10:24:00.381   872  1304 D WifiConfigStore: loaded 0 passpoint configs
,08-29 10:24:00.383   872  1304 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-29 10:24:00.384   872  1304 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-29 10:24:00.385   872  1304 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-29 10:24:00.385   872  1304 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-29 10:24:00.386   872  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-29 10:24:00.386   872  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 10:24:00.401   370   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-29 10:24:00.402   872  1304 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.62 rxSuccessRate=10.75 delta 1000 -> 994
,08-29 10:24:00.403   370   870 D CommandListener: Setting iface cfg
,08-29 10:24:00.404   872  1303 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '138 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 138 Failed to set address (No such device)'
,08-29 10:24:00.404   872  1303 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 10:24:00.412   872  1304 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-29 10:24:00.412   872  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 10:24:00.412   872  1303 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 10:24:00.413   872  1303 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-29 10:24:00.430   872  1304 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-29 10:24:00.472   872  1304 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-29 10:24:00.474  1485  1485 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 10:24:00.909  1485  1485 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 10:24:00.955  1485  1485 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 10:24:00.955  1485  1485 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-29 10:24:00.960   872  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 10:24:00.969   872  1304 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 10:24:00.969   872  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 10:24:00.970   872  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-29 10:24:00.990   872  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 10:24:01.001   370   870 D CommandListener: Setting iface cfg
08-29 10:24:01.002   872  1304 D WifiStateMachine: Start Dhcp Watchdog 2
,08-29 10:24:01.024   872  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-29 10:24:01.024   872  1306 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-29 10:24:01.029   872  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 10:24:01.033   872  4309 D DhcpClient: Receive thread started
,08-29 10:24:01.123   872  1304 E native  : do suspend false
,08-29 10:24:01.143   872  1962 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 10:24:01.163   872  4309 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172686, domain null
,08-29 10:24:01.166   872  1962 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172686 seconds
,08-29 10:24:01.170   872  1962 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-29 10:24:01.192   872  4309 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 10:24:01.193   872  1962 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-29 10:24:01.203   370   870 D CommandListener: Setting iface cfg
,08-29 10:24:01.214   872  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-29 10:24:01.215   872  1962 D DhcpClient: Scheduling renewal in 86399s
,08-29 10:24:01.225   872  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-29 10:24:01.228   872  1304 D WifiConfigStore: No blacklist allowed without epno enabled
,08-29 10:24:01.229   872  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-29 10:24:01.231   872  1306 D ConnectivityService: Adding iface wlan0 to network 101
,08-29 10:24:01.238   872  1304 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 10:24:01.316   872  1306 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-29 10:24:01.317   872  1306 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-29 10:24:01.319   872  1306 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-29 10:24:01.321   872  1306 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-29 10:24:01.323   872  1306 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-29 10:24:01.339   872  1306 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-29 10:24:01.350   872  1306 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-29 10:24:01.351   872  1306 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-29 10:24:01.351   872  1304 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-29 10:24:01.352   872  1306 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-29 10:24:01.352   872  1306 D ConnectivityService:    accepting network in place of null
08-29 10:24:01.352   872  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 10:24:01.355   872  1306 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 10:24:01.364   872  4308 D NetlinkSocketObserver: NeighborEvent{elapsedMs=136421, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 10:24:01.406   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 10:24:01.437   872  4307 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.206,2a00:1450:4001:812::200e
,08-29 10:24:01.464   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 10:24:01.476   872  1306 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-29 10:24:01.476   872  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 10:24:01.486   872  1306 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-29 10:24:01.489   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-29 10:24:01.503  4023  4023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 10:24:01.504  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:24:01.504  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:01.504  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:24:01.504  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:24:01.504  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:24:01.504  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:24:01.504  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:24:01.504  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:24:01.504  4023  4023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:24:01.504  4023  4023 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 10:24:01.510  4023  4023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:24:01.511  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:24:01.511  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:01.511  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:24:01.511  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:24:01.511  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:24:01.511  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:24:01.511  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:24:01.511  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 10:24:01.511  4023  4023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:24:01.511  4023  4023 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 10:24:01.518  1749  1749 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 10:24:01.520  1749  1749 D SystemUpdateService: onCreate
,08-29 10:24:01.525  1749  1749 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 10:24:01.529  1749  4319 I SystemUpdateService: active receiver: enabled
,08-29 10:24:01.535  1749  4319 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 10:24:01.541  1749  4319 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-29 10:24:01.541  1749  4319 I SystemUpdateService: now status is 0 (complete)
08-29 10:24:01.541  1749  4319 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-29 10:24:01.541  1749  4319 I SystemUpdateService: file has been verified
08-29 10:24:01.541  1749  4319 I SystemUpdateService: OTA package size = 12249756
,08-29 10:24:01.549   872  4307 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 08:24:01 GMT], X-Android-Received-Millis=[1472459041548], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472459041492]}
,08-29 10:24:01.551   872  1306 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 10:24:01.551   872  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-29 10:24:01.551   872  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-29 10:24:01.551  1749  4319 I SystemUpdateService: showing system update notification
,08-29 10:24:01.552   872  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-29 10:24:01.553  1749  1749 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 10:24:01.557  1749  2476 I iu.UploadsManager: num queued entries: 0
08-29 10:24:01.558  1749  2476 I iu.UploadsManager: num updated entries: 0
,08-29 10:24:01.559  1749  1749 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 10:24:01.559  1749  2476 I iu.SyncManager: NEXT; no task
,08-29 10:24:01.560  1749  1749 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 10:24:01.562  1749  4323 I MDM     : [180] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-29 10:24:01.562  4208  4208 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-29 10:24:01.562  1749  4323 W BaseAppContext: Using Auth Proxy for data requests.
,08-29 10:24:01.563  1749  4323 V GoogleAuthProtoRequest: [180] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 10:24:01.566  4208  4208 D SprintDMHelper: simOperator: 
,08-29 10:24:01.566  4208  4208 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 10:24:01.571  1749  1749 D SystemUpdateService: onDestroy
,08-29 10:24:01.574  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 10:24:01.576  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 10:24:01.610  1527  2112 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-29 10:24:01.610  1527  2112 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-29 10:24:01.610  1527  2112 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 10:24:01.610  1527  2112 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 10:24:01.621  1749  4323 E MDM     : [180] SitrepService.a: Error sending sitrep.
,08-29 10:24:01.629  3807  4326 V KeepSync: Connecting to GoogleApiClient
,08-29 10:24:01.630   872  2164 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-29 10:24:01.674  1527  2296 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-29 10:24:01.674  1527  2296 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-29 10:24:01.674  1527  2296 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 10:24:01.674  1527  2296 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 10:24:01.695  1749  4331 V BaseAuthAsyncOperation: access token request failed
,08-29 10:24:01.696  3807  4326 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-29 10:24:01.717  4142  4327 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-29 10:24:01.752  1527  2296 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-29 10:24:01.752  1527  2296 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-29 10:24:01.752  1527  2296 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 10:24:01.753  1527  2296 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 10:24:01.763  3807  4326 E KeepSync: IOException
08-29 10:24:01.763  3807  4326 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-29 10:24:01.763  3807  4326 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-29 10:24:01.763  3807  4326 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-29 10:24:01.763  3807  4326 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-29 10:24:01.763  3807  4326 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-29 10:24:01.763  3807  4326 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-29 10:24:01.763  3807  4326 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-29 10:24:01.763  3807  4326 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-29 10:24:01.763  3807  4326 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-29 10:24:01.763  3807  4326 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-29 10:24:01.763  3807  4326 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-29 10:24:01.763  3807  4326 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-29 10:24:01.763  3807  4326 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-29 10:24:01.763  3807  4326 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-29 10:24:01.763  3807  4326 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 10:24:01.763  3807  4326 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 10:24:01.763  3807  4326 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-29 10:24:01.763  3807  4326 E KeepSync: 	... 10 more
,08-29 10:24:01.763  3807  4326 W KeepSync: Sync result 2
,08-29 10:24:01.773   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 131307, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 10:24:02.473   872  1306 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-29 10:24:03.145   872   882 I ActivityManager: Killing 3913:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-29 10:24:03.327   872  2043 D WifiService: setWifiEnabled: false pid=4023, uid=10000
,08-29 10:24:03.327   872  2043 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 10:24:03.351  1485  1485 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 10:24:03.354   872  1304 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-29 10:24:03.354   872  1304 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-29 10:24:03.354   872  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 10:24:03.355   872  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 10:24:03.375   872  1962 D DhcpClient: Clearing IP address
,08-29 10:24:03.377   370   870 D CommandListener: Clearing all IP addresses on wlan0
,08-29 10:24:03.380   370   870 D CommandListener: Setting iface cfg
,08-29 10:24:03.391  1527  4333 V NativeCrypto: Read error: ssl=0x9ae8b800: I/O error during system call, Connection timed out
,08-29 10:24:03.397  1527  4333 V NativeCrypto: SSL shutdown failed: ssl=0x9ae8b800: I/O error during system call, Broken pipe
,08-29 10:24:03.403   872  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-29 10:24:03.403   872  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-29 10:24:03.407   397   397 E Parcel  : Reading a NULL string not supported here.
08-29 10:24:03.411   872  1304 D WifiStateMachine: Start Disconnecting Watchdog 2
08-29 10:24:03.412   872  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 10:24:03.415   370   870 D CommandListener: Clearing all IP addresses on wlan0
,08-29 10:24:03.416   872  4309 D DhcpClient: Receive thread stopped
08-29 10:24:03.420   872  1306 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-29 10:24:03.426   872  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 10:24:03.428  4023  4023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 10:24:03.429  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:24:03.429  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:03.429  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:24:03.429  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:24:03.429  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:24:03.429  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:03.429  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:03.429  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:24:03.429  4023  4023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:24:03.429  4023  4023 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:24:03.430  4023  4023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:24:03.430  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:24:03.430  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:03.430  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:24:03.430  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:24:03.430  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:24:03.430  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:03.430  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:03.430  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 10:24:03.430  4023  4023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:24:03.430  4023  4023 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:24:03.431  2134  2335 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:03.437   872  1304 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-29 10:24:03.458   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 10:24:03.499   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 10:24:03.500   872  1306 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-29 10:24:03.500   872  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 10:24:03.504   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-29 10:24:03.504  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:03.505  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:24:03.520  1749  1749 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 10:24:03.522  1749  1749 D SystemUpdateService: onCreate
,08-29 10:24:03.525  1749  1749 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 10:24:03.533  1749  1749 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 10:24:03.535  1749  2476 I iu.UploadsManager: num queued entries: 0
,08-29 10:24:03.533  1749  4344 I SystemUpdateService: active receiver: enabled
,08-29 10:24:03.539  1749  2476 I iu.UploadsManager: num updated entries: 0
,08-29 10:24:03.541  1749  4344 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 10:24:03.542  1749  1749 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 10:24:03.544  1749  1749 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 10:24:03.546  4208  4208 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 10:24:03.548  1749  4344 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-29 10:24:03.548  1749  4344 I SystemUpdateService: now status is 0 (complete)
08-29 10:24:03.548  1749  4344 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 10:24:03.548  1749  4344 I SystemUpdateService: file has been verified
08-29 10:24:03.548  1749  4344 I SystemUpdateService: OTA package size = 12249756
,08-29 10:24:03.550  4208  4208 D SprintDMHelper: simOperator: 
08-29 10:24:03.550  4208  4208 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-29 10:24:03.547  1749  2476 I iu.SyncManager: NEXT; no task
,08-29 10:24:03.573  4142  4347 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-29 10:24:03.578  1749  4344 I SystemUpdateService: showing system update notification
,08-29 10:24:03.580   370   870 E Netd    : netlink response contains error (No such file or directory)
,08-29 10:24:03.581   872  1306 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-29 10:24:03.591  1749  1749 D SystemUpdateService: onDestroy
,08-29 10:24:06.377   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@790688c:true
,08-29 10:24:06.377  4194  4194 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 10:24:06.382  4194  4194 I bt_bluedroid: init
,08-29 10:24:06.383  4194  4351 I BluetoothAdapterState: Entering OffState
,08-29 10:24:06.387  4194  4352 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-29 10:24:06.387  4194  4352 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 10:24:06.387  4194  4352 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 10:24:06.387  4194  4352 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-29 10:24:06.388  4194  4194 I bt_bluedroid: get_profile_interface socket
,08-29 10:24:06.390  4194  4194 I bt_bluedroid: get_profile_interface sdp
,08-29 10:24:06.396  4194  4205 I bt_bluedroid: config_hci_snoop_log
,08-29 10:24:06.396  4194  4355 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 10:24:06.400   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 10:24:06.400  4194  4355 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 10:24:06.408  4194  4351 D BluetoothAdapterState: Current state: OFF, message: 0
,08-29 10:24:06.409  4194  4351 D BluetoothAdapterProperties: Setting state to 14
,08-29 10:24:06.409  4194  4351 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 10:24:06.414  4194  4351 D BluetoothBondStateMachine: make
,08-29 10:24:06.417  4194  4356 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 10:24:06.426  4194  4351 I BluetoothAdapterState: Entering PendingCommandState
,08-29 10:24:06.426  4194  4194 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 10:24:06.429  4194  4194 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b0902c
,08-29 10:24:06.430  4194  4194 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 10:24:06.431  4194  4194 D BtGatt.GattService: Received start request. Starting profile...
08-29 10:24:06.431  4194  4194 D BtGatt.GattService: start()
08-29 10:24:06.431  4194  4194 I bt_bluedroid: get_profile_interface gatt
,08-29 10:24:06.432  4194  4194 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b0902c
08-29 10:24:06.433  4194  4194 D BtGatt.AdvertiseManager: advertise manager created
,08-29 10:24:06.444  4194  4194 V BluetoothAdapterState: isTurningOff()=false
08-29 10:24:06.444  4194  4194 V BluetoothAdapterState: isTurningOn()=false
08-29 10:24:06.444  4194  4194 V BluetoothAdapterState: isBleTurningOn()=true
,08-29 10:24:06.444  4194  4194 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 10:24:06.445  4194  4351 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-29 10:24:06.445  4194  4351 I bt_bluedroid: enable
08-29 10:24:06.446  4194  4352 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-29 10:24:06.446  4194  4352 I bt_hci  : start_up
,08-29 10:24:06.457  4194  4352 I bt_vendor: alloc value 0xb3979189
08-29 10:24:06.457  4194  4352 I bt_vendor: init
08-29 10:24:06.458  4194  4352 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 10:24:06.458  4194  4352 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 10:24:06.564  4194  4352 D bt_hci  : start_up starting async portion
,08-29 10:24:06.565  4194  4359 I bt_hci  : event_finish_startup
,08-29 10:24:06.565  4194  4359 I bt_hci_h4: hal_open
08-29 10:24:06.566  4194  4359 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 10:24:06.577  4194  4359 I bt_userial_vendor: device fd = 51 open
,08-29 10:24:06.607  4194  4359 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 10:24:06.638  4194  4359 D bt_hwcfg: Chipset BCM4354A2
,08-29 10:24:06.639  4194  4359 D bt_hwcfg: Target name = [BCM4354A2]
,08-29 10:24:06.640  4194  4359 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-29 10:24:07.295  4194  4359 I bt_hwcfg: bt vendor lib: set UART baud 115200
08-29 10:24:07.297  4194  4359 D bt_hwcfg: Settlement delay -- 100 ms
08-29 10:24:07.297  4194  4359 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 10:24:07.414  4194  4359 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 10:24:07.415  4194  4359 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-29 10:24:07.445  4194  4359 I bt_hwcfg: vendor lib fwcfg completed
,08-29 10:24:07.445  4194  4359 I bt_vendor: firmware callback,
08-29 10:24:07.445  4194  4359 I bt_hci  : firmware_config_callback
,08-29 10:24:07.460  4194  4361 I bt_btu  : btu_task pending for preload complete event,
08-29 10:24:07.460  4194  4361 I bt_btu_task: Bluetooth chip preload is complete
08-29 10:24:07.460  4194  4361 I bt_btu  : btu_task received preload complete event
,08-29 10:24:07.470  4194  4361 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 10:24:07.470  4194  4361 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 10:24:07.471  4194  4361 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 10:24:07.471  4194  4361 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 10:24:07.471  4194  4361 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-29 10:24:07.472  4194  4361 I         : BTE_InitTraceLevels -- TRC_A2D
,08-29 10:24:07.472  4194  4361 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 10:24:07.472  4194  4361 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 10:24:07.472  4194  4361 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 10:24:07.473  4194  4361 I         : BTE_InitTraceLevels -- TRC_PAN
,08-29 10:24:07.473  4194  4361 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 10:24:07.473  4194  4361 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 10:24:07.473  4194  4361 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 10:24:07.474  4194  4361 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-29 10:24:07.474  4194  4361 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 10:24:07.609  4194  4361 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38f6d9d
08-29 10:24:07.609  4194  4361 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38f6d9d 
,08-29 10:24:07.621  4194  4355 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 10:24:07.623  4194  4355 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 10:24:07.623  4194  4355 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 10:24:07.626  4194  4355 D BluetoothAdapterProperties: Name is: Nexus 6
08-29 10:24:07.630  4194  4355 D BluetoothAdapterProperties: Scan Mode:20
08-29 10:24:07.631  4194  4355 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 10:24:07.631  4194  4355 D bt_hci  : do_postload posting postload work item
,08-29 10:24:07.631  4194  4359 I bt_hci  : event_postload
08-29 10:24:07.631  4194  4359 I bt_vendor: sco_config_cb
08-29 10:24:07.631  4194  4359 I bt_hci  : sco_config_callback postload finished.
,08-29 10:24:07.636  4194  4355 D bt_bte_conf: Device ID record 1 : primary
08-29 10:24:07.636  4194  4355 D bt_bte_conf:   vendorId            = 000f
08-29 10:24:07.636  4194  4355 D bt_bte_conf:   vendorIdSource      = 0001
08-29 10:24:07.636  4194  4355 D bt_bte_conf:   product             = 1200
08-29 10:24:07.636  4194  4355 D bt_bte_conf:   version             = 1436
08-29 10:24:07.636  4194  4355 D bt_bte_conf:   clientExecutableURL = 
,08-29 10:24:07.636  4194  4355 D bt_bte_conf:   serviceDescription  = 
08-29 10:24:07.636  4194  4355 D bt_bte_conf:   documentationURL    = 
08-29 10:24:07.637  4194  4355 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 10:24:07.636  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:07.637  4194  4352 D bt_stack_manager: event_start_up_stack finished
08-29 10:24:07.637  4194  4351 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-29 10:24:07.637  4194  4351 D BluetoothAdapterProperties: Setting state to 15
,08-29 10:24:07.638  4194  4351 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-29 10:24:07.638  4194  4351 I BluetoothAdapterState: Entering BleOnState
,08-29 10:24:07.643  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:24:07.644  4194  4359 I bt_vendor: low_power_mode_cb
,08-29 10:24:07.647  4194  4351 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-29 10:24:07.647  4194  4351 D BluetoothAdapterProperties: Setting state to 11
,08-29 10:24:07.647  4194  4351 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-29 10:24:07.656  4194  4194 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b0902c
,08-29 10:24:07.656  4194  4194 D HeadsetService: Received start request. Starting profile...
,08-29 10:24:07.659  4194  4194 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-29 10:24:07.660  4194  4194 D HeadsetStateMachine: make
,08-29 10:24:07.666  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:24:07.668  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:24:07.672  4194  4351 I BluetoothAdapterState: Entering PendingCommandState
,08-29 10:24:07.675  4194  4194 D HeadsetStateMachine: max_hf_connections = 1
,08-29 10:24:07.676  4194  4194 I bt_bluedroid: get_profile_interface handsfree
08-29 10:24:07.676  4194  4355 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-29 10:24:07.676  4194  4355 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-29 10:24:07.679  4194  4194 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b0902c
,08-29 10:24:07.680  4194  4194 D A2dpService: Received start request. Starting profile...
,08-29 10:24:07.681  4194  4194 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 10:24:07.681  4194  4194 I bt_bluedroid: get_profile_interface avrcp
,08-29 10:24:07.687  4194  4194 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 10:24:07.687  4194  4194 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 10:24:07.688  4194  4194 D A2dpStateMachine: make
,08-29 10:24:07.689  4194  4194 I bt_bluedroid: get_profile_interface a2dp
,08-29 10:24:07.690  4194  4355 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-29 10:24:07.694  4194  4194 I BluetoothHidServiceJni: classInitNative: succeeds
,08-29 10:24:07.695  4194  4194 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b0902c
08-29 10:24:07.696  4194  4370 D A2dpStateMachine: Enter Disconnected: -2
08-29 10:24:07.696  4091  4091 D BluetoothInputDevice: Proxy object connected
08-29 10:24:07.697  4194  4194 D HidService: Received start request. Starting profile...
08-29 10:24:07.697  4194  4194 I bt_bluedroid: get_profile_interface hidhost
,08-29 10:24:07.697  4194  4355 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38d83e5
08-29 10:24:07.697  4194  4355 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 10:24:07.697  4091  4091 D HidProfile: Bluetooth service connected
08-29 10:24:07.697  4194  4194 D HidService: setHidService(): set to: null
08-29 10:24:07.698  4194  4194 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-29 10:24:07.699  4194  4194 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b0902c
,08-29 10:24:07.700  4194  4194 D HealthService: Received start request. Starting profile...
08-29 10:24:07.702  4194  4194 I bt_bluedroid: get_profile_interface health
,08-29 10:24:07.703  4194  4194 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 10:24:07.704  4194  4194 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b0902c
,08-29 10:24:07.705  4091  4091 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 10:24:07.705  4194  4194 D PanService: Received start request. Starting profile...
08-29 10:24:07.705  4194  4194 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 10:24:07.705  4194  4194 I bt_bluedroid: get_profile_interface pan
,08-29 10:24:07.705  4091  4091 D PanProfile: Bluetooth service connected
08-29 10:24:07.706  4194  4355 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 10:24:07.709  4194  4194 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b0902c
,08-29 10:24:07.711  4091  4091 D BluetoothMap: Proxy object connected
,08-29 10:24:07.711  4091  4091 D MapProfile: Bluetooth service connected
08-29 10:24:07.711  4091  4091 D BluetoothMap: getConnectedDevices()
08-29 10:24:07.712  4091  4091 D BluetoothMap: Bluetooth is Not enabled
08-29 10:24:07.713  4194  4194 D BluetoothMapService: Received start request. Starting profile...
08-29 10:24:07.713  4194  4194 D BluetoothMapService: start()
,08-29 10:24:07.715  4194  4194 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-29 10:24:07.715  4194  4194 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-29 10:24:07.715  4194  4194 D BluetoothMapAppObserver: createReceiver()
,08-29 10:24:07.716  4194  4194 D BluetoothMapAppObserver: initObservers()
08-29 10:24:07.716  4194  4194 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-29 10:24:07.723  4194  4194 V BluetoothAdapterState: isTurningOff()=false
08-29 10:24:07.723  4194  4194 V BluetoothAdapterState: isTurningOn()=true
08-29 10:24:07.723  4194  4194 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:24:07.723  4194  4194 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:24:07.723  1527  1527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 10:24:07.725  4194  4367 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 10:24:07.725  4194  4194 V BluetoothAdapterState: isTurningOff()=false
,08-29 10:24:07.725  4194  4194 V BluetoothAdapterState: isTurningOn()=true
08-29 10:24:07.725  4194  4194 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 10:24:07.725  4194  4194 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:24:07.725  4194  4194 V BluetoothAdapterState: isTurningOff()=false
08-29 10:24:07.726  4194  4194 V BluetoothAdapterState: isTurningOn()=true
,08-29 10:24:07.726  4194  4194 V BluetoothAdapterState: isBleTurningOn()=false,
,08-29 10:24:07.726  4194  4194 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 10:24:07.726  4194  4194 V BluetoothAdapterState: isTurningOff()=false
08-29 10:24:07.726  4194  4194 V BluetoothAdapterState: isTurningOn()=true
,08-29 10:24:07.726  4194  4194 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 10:24:07.726  4194  4194 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 10:24:07.726  4194  4194 V BluetoothAdapterState: isTurningOff()=false
08-29 10:24:07.726  4194  4194 V BluetoothAdapterState: isTurningOn()=true
,08-29 10:24:07.726  4194  4194 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 10:24:07.726  4194  4194 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 10:24:07.726  4194  4194 V BluetoothAdapterState: isTurningOff()=false
08-29 10:24:07.727  4194  4194 V BluetoothAdapterState: isTurningOn()=true
08-29 10:24:07.727  4194  4194 V BluetoothAdapterState: isBleTurningOn()=false,
08-29 10:24:07.727  4194  4194 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:24:07.727  4194  4351 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 10:24:07.727  4194  4351 D BluetoothAdapterProperties: ScanMode =  20
08-29 10:24:07.727  4194  4351 D BluetoothAdapterProperties: State =  11
,08-29 10:24:07.729  4194  4355 D BluetoothAdapterProperties: Scan Mode:21
,08-29 10:24:07.729  4194  4355 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 10:24:07.730  4194  4351 D BluetoothAdapterProperties: Setting state to 12
08-29 10:24:07.730  4194  4351 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-29 10:24:07.730  4194  4351 I BluetoothAdapterState: Entering OnState
08-29 10:24:07.730  1359  2049 D BluetoothPbap: onBluetoothStateChange: up=true
,08-29 10:24:07.732  1909  1921 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 10:24:07.732   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 10:24:07.732  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:24:07.732  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:07.732  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:24:07.732  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:24:07.732  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:24:07.732  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:07.732  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:07.732  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 10:24:07.733  1359  1378 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 10:24:07.734   872   872 D BluetoothA2dp: Proxy object connected
,08-29 10:24:07.734  4091  4104 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-29 10:24:07.734   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 10:24:07.734  1359  2171 D BluetoothPan: onBluetoothStateChange on: true
08-29 10:24:07.735  4023  4023 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:24:07.736  1359  1359 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 10:24:07.736  1359  1359 D PanProfile: Bluetooth service connected
08-29 10:24:07.737  4091  4102 D BluetoothMap: onBluetoothStateChange: up=true
08-29 10:24:07.738  4091  4104 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 10:24:07.738  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:24:07.738  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:07.738  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:24:07.738  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:24:07.738  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:24:07.738  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:07.738  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:07.738  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:24:07.739  4091  4102 D BluetoothPan: onBluetoothStateChange on: true
,08-29 10:24:07.739   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 10:24:07.740  1359  2049 D BluetoothMap: onBluetoothStateChange: up=true
08-29 10:24:07.740  4023  4023 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:24:07.742  1359  1359 D BluetoothMap: Proxy object connected
08-29 10:24:07.742  1359  1359 D MapProfile: Bluetooth service connected
08-29 10:24:07.742  1359  1359 D BluetoothMap: getConnectedDevices()
08-29 10:24:07.742  1359  1372 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 10:24:07.743  4194  4194 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 10:24:07.743  4194  4194 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-29 10:24:07.744  1359  1359 D BluetoothInputDevice: Proxy object connected
08-29 10:24:07.744  1359  1359 D HidProfile: Bluetooth service connected
08-29 10:24:07.744  1359  1378 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 10:24:07.745  4194  4194 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 10:24:07.745   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 10:24:07.745  1359  1359 D BluetoothA2dp: Proxy object connected
08-29 10:24:07.747   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,08-29 10:24:07.749  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:07.750  4194  4194 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 10:24:07.751  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:07.751  4194  4194 D ObexServerSockets: Succeed to create listening sockets 
08-29 10:24:07.751  4194  4194 D ObexServerSockets0: startAccept()
08-29 10:24:07.751  4091  4091 D LocalBluetoothProfileManager: Adding local A2DP profile
08-29 10:24:07.751  4194  4194 D ObexServerSockets0: prepareForNewConnect()
08-29 10:24:07.753  4194  4194 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 10:24:07.753  4194  4194 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-29 10:24:07.753  4194  4194 D BluetoothMapService: onReceive
08-29 10:24:07.754  4194  4194 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:07.754  4194  4194 D BluetoothMapService: STATE_ON
08-29 10:24:07.754  4194  4379 D ObexServerSockets0: Accepting socket connection...
08-29 10:24:07.755  4194  4378 D ObexServerSockets0: Accepting socket connection...
08-29 10:24:07.755  4091  4091 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-29 10:24:07.765  4091  4091 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 10:24:07.768  4091  4091 D BluetoothA2dp: Proxy object connected
,08-29 10:24:07.771  1527  1527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 10:24:07.777  4091  4091 D DockEventReceiver: finishStartingService: stopping service
,08-29 10:24:07.782  4091  4091 D BluetoothPbap: Proxy object connected
,08-29 10:24:07.783  4091  4091 D PbapServerProfile: Bluetooth service connected
08-29 10:24:07.783  4194  4194 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 10:24:07.783  4194  4194 D ObexServerSockets0: prepareForNewConnect()
,08-29 10:24:07.785  1359  1359 D BluetoothPbap: Proxy object connected
08-29 10:24:07.785  1359  1359 D PbapServerProfile: Bluetooth service connected
,08-29 10:24:07.791  4194  4383 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 10:24:07.810  4194  4387 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 10:24:07.812  4194  4387 I BtOppRfcommListener: Accept thread started.
,08-29 10:24:07.833  1909  1920 D BluetoothHeadset: Proxy object connected
,08-29 10:24:07.833  1359  1378 D BluetoothHeadset: Proxy object connected
08-29 10:24:07.834   872   872 D BluetoothHeadset: Proxy object connected
08-29 10:24:07.834  1359  1359 D HeadsetProfile: Bluetooth service connected
08-29 10:24:07.834   872   872 D BluetoothHeadset: Proxy object connected
08-29 10:24:07.834   872   872 D BluetoothHeadset: Proxy object connected
,08-29 10:24:07.835  1359  1372 D BluetoothHeadset: Proxy object connected
08-29 10:24:07.836   872   889 D BluetoothHeadset: Proxy object connected
,08-29 10:24:07.836  1359  1359 D HeadsetProfile: Bluetooth service connected
,08-29 10:24:07.840   872   889 D BluetoothHeadset: Proxy object connected
,08-29 10:24:07.846   872   889 D BluetoothHeadset: Proxy object connected
,08-29 10:24:07.862  4091  4104 D BluetoothHeadset: Proxy object connected
,08-29 10:24:07.864  4091  4091 D HeadsetProfile: Bluetooth service connected
,08-29 10:24:09.347  4194  4351 D BluetoothAdapterState: Current state: ON, message: 23
08-29 10:24:09.347  4194  4351 D BluetoothAdapterProperties: Setting state to 13
08-29 10:24:09.348  4194  4351 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-29 10:24:09.350  4194  4351 D BluetoothAdapterProperties: onBluetoothDisable()
,08-29 10:24:09.352  4194  4351 I BluetoothAdapterState: Entering PendingCommandState
,08-29 10:24:09.356   872  1306 D ConnectivityService: handlePromptUnvalidated 101
,08-29 10:24:09.359  4194  4355 D BluetoothAdapterProperties: Scan Mode:20
,08-29 10:24:09.360  4194  4351 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-29 10:24:09.362  4194  4194 D BluetoothMapService: onReceive
,08-29 10:24:09.362  4194  4194 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:09.363  4194  4194 D BluetoothMapService: STATE_TURNING_OFF
08-29 10:24:09.363  4194  4194 D BluetoothMapService: MAP Service closeService in
,08-29 10:24:09.363  4194  4194 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 10:24:09.364  4194  4194 D ObexServerSockets0: shutdown(block = true)
,08-29 10:24:09.365  4194  4378 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-29 10:24:09.367  4023  4023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:24:09.367  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:24:09.367  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:09.367  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:24:09.367  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:24:09.367  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:24:09.367  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:09.367  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:09.367  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:24:09.370  4023  4023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:24:09.371  4023  4023 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:24:09.373  4194  4194 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 10:24:09.373  4194  4379 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 10:24:09.376  4194  4363 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-29 10:24:09.376  4194  4194 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 10:24:09.377  4091  4091 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 10:24:09.377  4023  4023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 10:24:09.377  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:24:09.377  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:09.377  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:24:09.377  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:24:09.377  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:24:09.377  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:09.377  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:09.377  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:24:09.378  4194  4194 D HeadsetService: Received stop request...Stopping profile...
08-29 10:24:09.378  4023  4023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:24:09.378  4023  4023 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:24:09.380  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:09.382  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:24:09.387  1909  2170 D BluetoothHeadset: Proxy object disconnected
,08-29 10:24:09.387  4194  4194 I BtOppRfcommListener: stopping Accept Thread
,08-29 10:24:09.387  4194  4387 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-29 10:24:09.387  4091  4102 D BluetoothHeadset: Proxy object disconnected
,08-29 10:24:09.388  4194  4387 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 10:24:09.388  1359  1372 D BluetoothHeadset: Proxy object disconnected
08-29 10:24:09.389   872   872 D BluetoothHeadset: Proxy object disconnected
08-29 10:24:09.389   872   872 D BluetoothHeadset: Proxy object disconnected
08-29 10:24:09.389   872   872 D BluetoothHeadset: Proxy object disconnected
,08-29 10:24:09.390  4194  4194 D A2dpService: Received stop request...Stopping profile...
08-29 10:24:09.391  4194  4370 D A2dpStateMachine: Exit Disconnected: -1
08-29 10:24:09.392  4091  4091 D DockEventReceiver: finishStartingService: stopping service
,08-29 10:24:09.393   872   872 D BluetoothA2dp: Proxy object disconnected
08-29 10:24:09.393  4091  4091 D HeadsetProfile: Bluetooth service disconnected
,08-29 10:24:09.394  4194  4194 D HidService: Received stop request...Stopping profile...
08-29 10:24:09.394  4194  4194 D HidService: Stopping Bluetooth HidService
08-29 10:24:09.395  4091  4091 D BluetoothA2dp: Proxy object disconnected
,08-29 10:24:09.396  4194  4194 V BluetoothAdapterState: isTurningOff()=true
,08-29 10:24:09.395  4091  4091 D BluetoothInputDevice: Proxy object disconnected
,08-29 10:24:09.396  4194  4194 V BluetoothAdapterState: isTurningOn()=false
,08-29 10:24:09.396  4091  4091 D HidProfile: Bluetooth service disconnected
,08-29 10:24:09.396  4194  4194 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 10:24:09.396  4194  4194 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:24:09.398  1359  1359 D HeadsetProfile: Bluetooth service disconnected
08-29 10:24:09.400  1359  1359 D BluetoothA2dp: Proxy object disconnected
08-29 10:24:09.401  1359  1359 D BluetoothInputDevice: Proxy object disconnected
08-29 10:24:09.401  1527  1527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 10:24:09.402  1359  1359 D HidProfile: Bluetooth service disconnected
08-29 10:24:09.403  4194  4194 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 10:24:09.403  4194  4194 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 10:24:09.403  4194  4355 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-29 10:24:09.403  4194  4361 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 10:24:09.403  4194  4361 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 10:24:09.403  4194  4361 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 10:24:09.403  4194  4194 D HealthService: Received stop request...Stopping profile...
08-29 10:24:09.404  4194  4355 E bt_btif : btif_hf_upstreams_evt: Invalid index 65534
,08-29 10:24:09.408  4194  4194 D PanService: Received stop request...Stopping profile...
08-29 10:24:09.410  4194  4194 V BluetoothAdapterState: isTurningOff()=true
08-29 10:24:09.410  4194  4194 V BluetoothAdapterState: isTurningOn()=false
,08-29 10:24:09.410  4194  4194 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:24:09.410  4194  4194 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:24:09.410  4091  4091 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 10:24:09.410  4091  4091 D PanProfile: Bluetooth service disconnected
,08-29 10:24:09.410  1359  1359 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 10:24:09.411  1359  1359 D PanProfile: Bluetooth service disconnected
08-29 10:24:09.411  4194  4194 D BluetoothMapService: Received stop request...Stopping profile...
08-29 10:24:09.411  4194  4194 D BluetoothMapService: stop()
08-29 10:24:09.412  4194  4194 D BluetoothMapAppObserver: deinitObservers()
08-29 10:24:09.412  4194  4194 D BluetoothMapAppObserver: removeReceiver(),
08-29 10:24:09.414  1359  1359 D BluetoothMap: Proxy object disconnected
08-29 10:24:09.414  1359  1359 D MapProfile: Bluetooth service disconnected
08-29 10:24:09.416  4091  4091 D BluetoothMap: Proxy object disconnected
08-29 10:24:09.416  4091  4091 D MapProfile: Bluetooth service disconnected
08-29 10:24:09.416  4194  4355 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-29 10:24:09.416  4194  4361 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 10:24:09.417  4194  4361 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 10:24:09.418  4194  4194 V BluetoothAdapterState: isTurningOff()=true
08-29 10:24:09.418  4194  4194 V BluetoothAdapterState: isTurningOn()=false
08-29 10:24:09.418  4194  4194 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:24:09.418  4194  4194 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 10:24:09.419  4194  4361 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 10:24:09.419  4194  4361 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 10:24:09.419  4194  4361 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-29 10:24:09.419  4194  4361 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 10:24:09.420  4194  4194 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 10:24:09.420  4194  4194 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 10:24:09.420  4194  4355 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 10:24:09.422  1359  1359 D BluetoothPbap: Proxy object disconnected
08-29 10:24:09.423  1359  1359 D PbapServerProfile: Bluetooth service disconnected
08-29 10:24:09.424  4194  4194 V BluetoothAdapterState: isTurningOff()=true
08-29 10:24:09.424  4194  4194 V BluetoothAdapterState: isTurningOn()=false
,08-29 10:24:09.424  4194  4194 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 10:24:09.424  4194  4194 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 10:24:09.425  4194  4194 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 10:24:09.425  4194  4355 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 10:24:09.426  4194  4194 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-29 10:24:09.427  4194  4194 V BluetoothAdapterState: isTurningOff()=true
08-29 10:24:09.427  4194  4194 V BluetoothAdapterState: isTurningOn()=false
,08-29 10:24:09.427  4194  4194 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:24:09.427  4194  4194 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:24:09.428  4194  4194 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...,
08-29 10:24:09.428  4194  4194 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-29 10:24:09.430  4194  4194 D BluetoothMapService: MAP Service closeService in
08-29 10:24:09.430  4194  4194 V BluetoothAdapterState: isTurningOff()=true
,08-29 10:24:09.430  4194  4194 V BluetoothAdapterState: isTurningOn()=false
08-29 10:24:09.430  4194  4194 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:24:09.431  4194  4194 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 10:24:09.431  4194  4351 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-29 10:24:09.431  4194  4351 D BluetoothAdapterProperties: Setting state to 15
08-29 10:24:09.431  4194  4194 D BluetoothMapService: cleanup(),
08-29 10:24:09.431  4194  4351 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 10:24:09.431  4194  4194 D BluetoothMapService: MAP Service closeService in
08-29 10:24:09.432  4194  4351 I BluetoothAdapterState: Entering BleOnState
08-29 10:24:09.432  1359  1372 D BluetoothPbap: onBluetoothStateChange: up=false
,08-29 10:24:09.434  1909  1921 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 10:24:09.434  4091  4091 D BluetoothPbap: Proxy object disconnected
08-29 10:24:09.434   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 10:24:09.434  4091  4091 D PbapServerProfile: Bluetooth service disconnected
08-29 10:24:09.437  1359  2049 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 10:24:09.437  4091  4104 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-29 10:24:09.438   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 10:24:09.438  1359  2171 D BluetoothPan: onBluetoothStateChange on: false
,08-29 10:24:09.439  4091  4102 D BluetoothMap: onBluetoothStateChange: up=false
,08-29 10:24:09.440  4091  4102 D BluetoothPbap: onBluetoothStateChange: up=false
,08-29 10:24:09.440  4091  4104 D BluetoothPan: onBluetoothStateChange on: false
,08-29 10:24:09.441  4091  4102 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 10:24:09.441   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 10:24:09.442  1359  1378 D BluetoothMap: onBluetoothStateChange: up=false
,08-29 10:24:09.442  1359  1372 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 10:24:09.443  4091  4104 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 10:24:09.444  1359  2049 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 10:24:09.444   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 10:24:09.445  4194  4351 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 10:24:09.445  4194  4351 D BluetoothAdapterProperties: Setting state to 16
,08-29 10:24:09.445  4194  4351 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-29 10:24:09.446  4194  4351 D BluetoothAdapterProperties: onBleDisable
,08-29 10:24:09.448  4194  4352 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-29 10:24:09.449  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:09.449  4194  4361 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 10:24:09.449  4194  4361 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 10:24:09.449  4091  4091 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 10:24:09.450  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:09.450  4194  4355 D BluetoothAdapterProperties: Scan Mode:20
08-29 10:24:09.451  4194  4351 I BluetoothAdapterState: Entering PendingCommandState
08-29 10:24:09.451  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:09.453  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:09.453  1527  1527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 10:24:09.458  4091  4091 D DockEventReceiver: finishStartingService: stopping service
,08-29 10:24:09.649  4194  4355 I bt_hci  : shut_down
,08-29 10:24:09.664  4194  4359 D bt_hwcfg: hw_epilog_process
,08-29 10:24:09.665  4194  4359 I bt_vendor: low_power_mode_cb
,08-29 10:24:09.688  4194  4359 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-29 10:24:09.689  4194  4359 I bt_vendor: epilog_cb
,08-29 10:24:09.689  4194  4359 I bt_hci  : epilog_finished_callback
,08-29 10:24:09.696  4194  4355 I bt_hci_h4: hal_close
,08-29 10:24:09.698  4194  4355 I bt_userial_vendor: device fd = 51 close
,08-29 10:24:09.816  4194  4352 D bt_stack_manager: event_shut_down_stack finished.
08-29 10:24:09.817  4194  4351 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 10:24:09.823  4194  4351 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-29 10:24:09.823  4194  4194 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 10:24:09.825  4194  4194 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 10:24:09.826  4194  4194 D BtGatt.GattService: stop()
08-29 10:24:09.827  4194  4194 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 10:24:09.833  4194  4194 V BluetoothAdapterState: isTurningOff()=false
08-29 10:24:09.833  4194  4194 V BluetoothAdapterState: isTurningOn()=false
08-29 10:24:09.833  4194  4194 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:24:09.834  4194  4194 V BluetoothAdapterState: isBleTurningOff()=true
08-29 10:24:09.835  4194  4351 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-29 10:24:09.835  4194  4351 D BluetoothAdapterProperties: Setting state to 10
,08-29 10:24:09.836  4194  4351 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-29 10:24:09.837  4194  4351 I BluetoothAdapterState: Entering OffState
08-29 10:24:09.838   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-29 10:24:09.851  4194  4194 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-29 10:24:09.851  4194  4194 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 10:24:09.851  4194  4194 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-29 10:24:09.852  4194  4352 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-29 10:24:09.857  4194  4352 D bt_stack_manager: event_clean_up_stack finished.
,08-29 10:24:09.859  4194  4194 I art     : System.exit called, status: 0
,08-29 10:24:09.859  4194  4194 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 10:24:09.921   872  1694 I ActivityManager: Process com.android.bluetooth (pid 4194) has died
,08-29 10:24:12.236  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 10:24:12.255  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 10:24:12.262  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 10:24:12.345  4023  4073 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 10:24:12.345  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:24:12.346  1527  2112 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-29 10:24:12.347  1527  2112 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-29 10:24:12.348  1527  2112 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 10:24:12.348  1527  2112 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 10:24:12.406  3710  3710 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-29 10:24:12.407  3710  3710 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-29 10:24:12.411  3710  3710 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-29 10:24:15.048   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-29 10:24:15.059  1850  1850 I Keyboard.Facilitator: onFinishInput()
,08-29 10:24:15.079   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 10:24:15.079   872   892 I Adreno  : Build Date                       : 10/20/15
08-29 10:24:15.079   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 10:24:15.079   872   892 I Adreno  : Local Branch                     : M14
08-29 10:24:15.079   872   892 I Adreno  : Remote Branch                    : 
08-29 10:24:15.079   872   892 I Adreno  : Remote Branch                    : 
08-29 10:24:15.079   872   892 I Adreno  : Reconstruct Branch               : 
,08-29 10:24:15.124   283   368 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (939 us)
,08-29 10:24:15.353  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 10:24:15.353  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@83399a2 added. We now have 6 listener(s)
08-29 10:24:15.353  4023  4073 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 10:24:15.355  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:24:15.356  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c13f633 added. We now have 7 listener(s)
08-29 10:24:15.356  4023  4073 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 10:24:15.357  4023  4073 I System.out: IsBluetoothEnabled
,08-29 10:24:15.368  4023  4073 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:24:15.404   872   889 I ActivityManager: Start proc 4400:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-29 10:24:15.571  4400  4400 D AdapterServiceConfig: Adding HeadsetService
,08-29 10:24:15.572  4400  4400 D AdapterServiceConfig: Adding A2dpService,
,08-29 10:24:15.572  4400  4400 D AdapterServiceConfig: Adding HidService
,08-29 10:24:15.572  4400  4400 D AdapterServiceConfig: Adding HealthService
08-29 10:24:15.572  4400  4400 D AdapterServiceConfig: Adding PanService
08-29 10:24:15.572  4400  4400 D AdapterServiceConfig: Adding GattService
08-29 10:24:15.573  4400  4400 D AdapterServiceConfig: Adding BluetoothMapService
,08-29 10:24:15.588   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c32bb4e:true
08-29 10:24:15.589  4400  4400 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 10:24:15.592  4400  4400 I bt_bluedroid: init
,08-29 10:24:15.593  4400  4412 I BluetoothAdapterState: Entering OffState
,08-29 10:24:15.599  4400  4413 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-29 10:24:15.599  4400  4413 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 10:24:15.600  4400  4413 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-29 10:24:15.600  4400  4413 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-29 10:24:15.603  4400  4400 I bt_bluedroid: get_profile_interface socket
,08-29 10:24:15.607  4400  4416 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 10:24:15.608  4400  4400 I bt_bluedroid: get_profile_interface sdp
08-29 10:24:15.610  4400  4416 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 10:24:15.614  4400  4411 I bt_bluedroid: config_hci_snoop_log
,08-29 10:24:15.617   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 10:24:15.629  4400  4412 D BluetoothAdapterState: Current state: OFF, message: 0
,08-29 10:24:15.630  4400  4412 D BluetoothAdapterProperties: Setting state to 14
,08-29 10:24:15.630  4400  4412 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 10:24:15.634  4400  4412 D BluetoothBondStateMachine: make
,08-29 10:24:15.643  4400  4417 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 10:24:15.649  4400  4412 I BluetoothAdapterState: Entering PendingCommandState
,08-29 10:24:15.651  4400  4400 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 10:24:15.663  4400  4400 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b0902c
,08-29 10:24:15.664  4400  4400 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 10:24:15.666  4400  4400 D BtGatt.GattService: Received start request. Starting profile...
,08-29 10:24:15.666  4400  4400 D BtGatt.GattService: start()
,08-29 10:24:15.667  4400  4400 I bt_bluedroid: get_profile_interface gatt
,08-29 10:24:15.669  4400  4400 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b0902c
,08-29 10:24:15.670  4400  4400 D BtGatt.AdvertiseManager: advertise manager created,
,08-29 10:24:15.685  4400  4400 V BluetoothAdapterState: isTurningOff()=false
,08-29 10:24:15.686  4400  4400 V BluetoothAdapterState: isTurningOn()=false
08-29 10:24:15.686  4400  4400 V BluetoothAdapterState: isBleTurningOn()=true
,08-29 10:24:15.686  4400  4400 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 10:24:15.687  4400  4412 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-29 10:24:15.688  4400  4412 I bt_bluedroid: enable
08-29 10:24:15.689  4400  4413 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-29 10:24:15.689  4400  4413 I bt_hci  : start_up
,08-29 10:24:15.705  4400  4413 I bt_vendor: alloc value 0xb39d7189
,08-29 10:24:15.705  4400  4413 I bt_vendor: init
08-29 10:24:15.705  4400  4413 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 10:24:15.706  4400  4413 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 10:24:15.771  4023  4023 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 10:24:15.771  4023  4023 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-29 10:24:15.804  4023  4023 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@5ac8318 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@7f58df0, 16908290=android.view.AbsSavedState$1@7f58df0}, android:focusedViewId=100}]}]
,08-29 10:24:15.804  4023  4023 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-29 10:24:15.804   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-29 10:24:15.804  4023  4023 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 10:24:15.804  4023  4023 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-29 10:24:15.808   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-29 10:24:15.812   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-29 10:24:15.813   283   283 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
,08-29 10:24:15.813   283   283 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
08-29 10:24:15.813  4400  4413 D bt_hci  : start_up starting async portion,
08-29 10:24:15.813  4400  4420 I bt_hci  : event_finish_startup
,08-29 10:24:15.813  4400  4420 I bt_hci_h4: hal_open
,08-29 10:24:15.813  4400  4420 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 10:24:15.822  4400  4420 I bt_userial_vendor: device fd = 51 open
,08-29 10:24:15.856  4400  4420 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 10:24:15.861   872   881 I art     : Background partial concurrent mark sweep GC freed 36796(2MB) AllocSpace objects, 13(388KB) LOS objects, 33% free, 28MB/43MB, paused 1.103ms total 101.851ms
,08-29 10:24:15.889  4400  4420 D bt_hwcfg: Chipset BCM4354A2
,08-29 10:24:15.889  4400  4420 D bt_hwcfg: Target name = [BCM4354A2]
08-29 10:24:15.889  4400  4420 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-29 10:24:16.046   283   341 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-29 10:24:16.051   283   283 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-29 10:24:16.051   872  1327 D SurfaceControl: Excessive delay in setPowerMode(): 239ms
,08-29 10:24:16.056   872   892 I DreamManagerService: Entering dreamland.
,08-29 10:24:16.057   872   892 I PowerManagerService: Dozing...
,08-29 10:24:16.059   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-29 10:24:16.104   374  1471 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-29 10:24:16.105   374  1471 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-29 10:24:16.113   872  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 10:24:16.118   872  1304 E native  : do suspend false
,08-29 10:24:16.121  1894  4423 D NfcService: Discovery configuration equal, not updating.
,08-29 10:24:16.142   872  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 10:24:16.146   872  1304 E native  : do suspend true
,08-29 10:24:16.247   374  1277 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-29 10:24:16.247   374  1277 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-29 10:24:16.668  4400  4420 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 10:24:16.670  4400  4420 D bt_hwcfg: Settlement delay -- 100 ms
08-29 10:24:16.670  4400  4420 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 10:24:16.788  4400  4420 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 10:24:16.790  4400  4420 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-29 10:24:16.818  4400  4420 I bt_hwcfg: vendor lib fwcfg completed
,08-29 10:24:16.818  4400  4420 I bt_vendor: firmware callback
08-29 10:24:16.818  4400  4420 I bt_hci  : firmware_config_callback
,08-29 10:24:16.831  4400  4427 I bt_btu  : btu_task pending for preload complete event
,08-29 10:24:16.831  4400  4427 I bt_btu_task: Bluetooth chip preload is complete
,08-29 10:24:16.832  4400  4427 I bt_btu  : btu_task received preload complete event
,08-29 10:24:16.842  4400  4427 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 10:24:16.843  4400  4427 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-29 10:24:16.843  4400  4427 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 10:24:16.843  4400  4427 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 10:24:16.843  4400  4427 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-29 10:24:16.844  4400  4427 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 10:24:16.844  4400  4427 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 10:24:16.844  4400  4427 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 10:24:16.844  4400  4427 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 10:24:16.845  4400  4427 I         : BTE_InitTraceLevels -- TRC_PAN
,08-29 10:24:16.845  4400  4427 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 10:24:16.845  4400  4427 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 10:24:16.845  4400  4427 I         : BTE_InitTraceLevels -- TRC_SMP
,08-29 10:24:16.845  4400  4427 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 10:24:16.846  4400  4427 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 10:24:16.993  4400  4427 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3954d9d
,08-29 10:24:16.993  4400  4427 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3954d9d 
,08-29 10:24:17.007  4400  4416 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 10:24:17.009  4400  4416 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 10:24:17.010  4400  4416 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 10:24:17.015  4400  4416 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 10:24:17.021  4400  4416 D BluetoothAdapterProperties: Scan Mode:20
,08-29 10:24:17.022  4400  4416 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 10:24:17.024  4400  4416 D bt_hci  : do_postload posting postload work item
,08-29 10:24:17.024  4400  4420 I bt_hci  : event_postload
,08-29 10:24:17.024  4400  4420 I bt_vendor: sco_config_cb
,08-29 10:24:17.025  4400  4420 I bt_hci  : sco_config_callback postload finished.
,08-29 10:24:17.026  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:17.027  4400  4416 D bt_bte_conf: Device ID record 1 : primary
,08-29 10:24:17.027  4400  4416 D bt_bte_conf:   vendorId            = 000f
,08-29 10:24:17.027  4400  4416 D bt_bte_conf:   vendorIdSource      = 0001
,08-29 10:24:17.027  4400  4416 D bt_bte_conf:   product             = 1200
,08-29 10:24:17.027  4400  4416 D bt_bte_conf:   version             = 1436
,08-29 10:24:17.027  4400  4416 D bt_bte_conf:   clientExecutableURL = 
08-29 10:24:17.027  4400  4416 D bt_bte_conf:   serviceDescription  = 
,08-29 10:24:17.027  4400  4416 D bt_bte_conf:   documentationURL    = 
08-29 10:24:17.027  4400  4416 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-29 10:24:17.028  4400  4413 D bt_stack_manager: event_start_up_stack finished
,08-29 10:24:17.028  4400  4412 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-29 10:24:17.028  4400  4412 D BluetoothAdapterProperties: Setting state to 15
08-29 10:24:17.029  4400  4412 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-29 10:24:17.029  4400  4412 I BluetoothAdapterState: Entering BleOnState
,08-29 10:24:17.031  4400  4420 I bt_vendor: low_power_mode_cb
08-29 10:24:17.032  4400  4412 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-29 10:24:17.032  4400  4412 D BluetoothAdapterProperties: Setting state to 11
08-29 10:24:17.032  4400  4412 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-29 10:24:17.040  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:17.044  4400  4400 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b0902c
08-29 10:24:17.045  4400  4400 D HeadsetService: Received start request. Starting profile...
08-29 10:24:17.048  4400  4400 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 10:24:17.049  4400  4400 D HeadsetStateMachine: make
08-29 10:24:17.051  4400  4412 I BluetoothAdapterState: Entering PendingCommandState
08-29 10:24:17.058  4400  4400 D HeadsetStateMachine: max_hf_connections = 1
08-29 10:24:17.058  4400  4400 I bt_bluedroid: get_profile_interface handsfree
08-29 10:24:17.059  4400  4416 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-29 10:24:17.059  4400  4416 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-29 10:24:17.066  1527  1527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 10:24:17.067  4400  4400 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b0902c
,08-29 10:24:17.067  4400  4400 D A2dpService: Received start request. Starting profile...
08-29 10:24:17.068  4400  4400 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 10:24:17.068  4400  4400 I bt_bluedroid: get_profile_interface avrcp
,08-29 10:24:17.074  4400  4400 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-29 10:24:17.074  4400  4400 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 10:24:17.074  4400  4400 D A2dpStateMachine: make
,08-29 10:24:17.075  4400  4400 I bt_bluedroid: get_profile_interface a2dp
,08-29 10:24:17.076  4400  4416 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-29 10:24:17.078  4400  4436 D A2dpStateMachine: Enter Disconnected: -2
,08-29 10:24:17.078  4400  4400 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 10:24:17.079  4400  4400 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b0902c
,08-29 10:24:17.080  4400  4400 D HidService: Received start request. Starting profile...
08-29 10:24:17.080  4400  4400 I bt_bluedroid: get_profile_interface hidhost
08-29 10:24:17.080  4400  4416 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39363e5
08-29 10:24:17.080  4400  4416 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-29 10:24:17.080  4400  4400 D HidService: setHidService(): set to: null
08-29 10:24:17.081  4400  4400 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 10:24:17.082  4400  4400 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b0902c
,08-29 10:24:17.082  4400  4400 D HealthService: Received start request. Starting profile...
,08-29 10:24:17.084  4400  4400 I bt_bluedroid: get_profile_interface health
,08-29 10:24:17.085  4400  4400 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-29 10:24:17.086  4400  4400 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b0902c
,08-29 10:24:17.086  4400  4400 D PanService: Received start request. Starting profile...
08-29 10:24:17.086  4400  4400 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 10:24:17.086  4400  4400 I bt_bluedroid: get_profile_interface pan
,08-29 10:24:17.087  4400  4416 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 10:24:17.090  4400  4400 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b0902c
,08-29 10:24:17.090  4400  4400 D BluetoothMapService: Received start request. Starting profile...
08-29 10:24:17.090  4400  4400 D BluetoothMapService: start()
,08-29 10:24:17.092  4400  4400 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-29 10:24:17.093  4400  4400 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-29 10:24:17.093  4400  4400 D BluetoothMapAppObserver: createReceiver()
,08-29 10:24:17.094  4400  4400 D BluetoothMapAppObserver: initObservers()
08-29 10:24:17.094  4400  4400 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-29 10:24:17.102  4400  4400 V BluetoothAdapterState: isTurningOff()=false
,08-29 10:24:17.102  4400  4400 V BluetoothAdapterState: isTurningOn()=true
,08-29 10:24:17.102  4400  4400 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 10:24:17.102  4400  4400 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:24:17.103  4400  4434 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-29 10:24:17.106  4400  4400 V BluetoothAdapterState: isTurningOff()=false
08-29 10:24:17.106  4400  4400 V BluetoothAdapterState: isTurningOn()=true
08-29 10:24:17.106  4400  4400 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:24:17.107  4400  4400 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 10:24:17.107  4400  4400 V BluetoothAdapterState: isTurningOff()=false
08-29 10:24:17.107  4400  4400 V BluetoothAdapterState: isTurningOn()=true
08-29 10:24:17.107  4400  4400 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:24:17.107  4400  4400 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 10:24:17.107  4400  4400 V BluetoothAdapterState: isTurningOff()=false
,08-29 10:24:17.107  4400  4400 V BluetoothAdapterState: isTurningOn()=true
08-29 10:24:17.107  4400  4400 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:24:17.107  4400  4400 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:24:17.108  4400  4400 V BluetoothAdapterState: isTurningOff()=false
08-29 10:24:17.108  4400  4400 V BluetoothAdapterState: isTurningOn()=true
08-29 10:24:17.108  4400  4400 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:24:17.108  4400  4400 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:24:17.108  4400  4400 V BluetoothAdapterState: isTurningOff()=false
,08-29 10:24:17.108  4400  4400 V BluetoothAdapterState: isTurningOn()=true
08-29 10:24:17.108  4400  4400 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:24:17.108  4400  4400 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:24:17.108  4400  4412 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-29 10:24:17.108  4400  4412 D BluetoothAdapterProperties: ScanMode =  20
,08-29 10:24:17.109  4400  4412 D BluetoothAdapterProperties: State =  11
08-29 10:24:17.109  4400  4412 D BluetoothAdapterProperties: Setting state to 12
08-29 10:24:17.109  4400  4412 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-29 10:24:17.110  4400  4412 I BluetoothAdapterState: Entering OnState
08-29 10:24:17.110  1359  1372 D BluetoothPbap: onBluetoothStateChange: up=true
,08-29 10:24:17.113  4400  4416 D BluetoothAdapterProperties: Scan Mode:21
08-29 10:24:17.113  4400  4416 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 10:24:17.114  1909  1920 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 10:24:17.115   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 10:24:17.115  1359  2171 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 10:24:17.116  4091  4102 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 10:24:17.117   872   872 D BluetoothA2dp: Proxy object connected
08-29 10:24:17.118  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:24:17.118  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:17.118  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:24:17.118  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:24:17.118  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:24:17.118  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:17.118  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:17.118  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 10:24:17.120  4400  4400 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 10:24:17.120  4023  4023 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:24:17.121   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 10:24:17.121  4400  4400 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-29 10:24:17.122  1359  1378 D BluetoothPan: onBluetoothStateChange on: true
,08-29 10:24:17.124  4400  4400 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 10:24:17.124  4091  4104 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 10:24:17.127  4400  4400 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 10:24:17.127  4091  4102 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 10:24:17.129  4091  4104 D BluetoothPan: onBluetoothStateChange on: true
08-29 10:24:17.129  4400  4400 D ObexServerSockets: Succeed to create listening sockets 
,08-29 10:24:17.129  4400  4400 D ObexServerSockets0: startAccept()
08-29 10:24:17.129  4400  4400 D ObexServerSockets0: prepareForNewConnect()
08-29 10:24:17.130  4091  4102 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 10:24:17.132  4400  4400 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-29 10:24:17.133  4400  4400 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-29 10:24:17.133   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 10:24:17.133  1359  2049 D BluetoothMap: onBluetoothStateChange: up=true
08-29 10:24:17.134  4091  4091 D BluetoothA2dp: Proxy object connected
,08-29 10:24:17.135  1359  1359 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 10:24:17.135  1359  1359 D PanProfile: Bluetooth service connected
08-29 10:24:17.135  1359  2171 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 10:24:17.136  4400  4441 D ObexServerSockets0: Accepting socket connection...
,08-29 10:24:17.136  4400  4443 D ObexServerSockets0: Accepting socket connection...
,08-29 10:24:17.137  4091  4091 D BluetoothInputDevice: Proxy object connected
08-29 10:24:17.137  4091  4091 D HidProfile: Bluetooth service connected
08-29 10:24:17.138  1359  1359 D BluetoothInputDevice: Proxy object connected
,08-29 10:24:17.138  1359  1359 D HidProfile: Bluetooth service connected
08-29 10:24:17.138  4091  4442 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 10:24:17.139  1359  1372 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 10:24:17.139  1359  1359 D BluetoothMap: Proxy object connected
08-29 10:24:17.139  1359  1359 D MapProfile: Bluetooth service connected
08-29 10:24:17.139  1359  1359 D BluetoothMap: getConnectedDevices()
08-29 10:24:17.140  4091  4091 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 10:24:17.140  4091  4091 D PanProfile: Bluetooth service connected
08-29 10:24:17.140  4091  4091 D BluetoothMap: Proxy object connected
08-29 10:24:17.140  4091  4091 D MapProfile: Bluetooth service connected
08-29 10:24:17.140  4091  4091 D BluetoothMap: getConnectedDevices()
,08-29 10:24:17.141   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 10:24:17.141  1359  1359 D BluetoothA2dp: Proxy object connected
08-29 10:24:17.142   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,08-29 10:24:17.145  4400  4400 D BluetoothMapService: onReceive
08-29 10:24:17.145  4400  4400 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 10:24:17.145  4400  4400 D BluetoothMapService: STATE_ON
08-29 10:24:17.146  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:24:17.153  4091  4091 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 10:24:17.158  4091  4091 D DockEventReceiver: finishStartingService: stopping service
,08-29 10:24:17.160  1527  1527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 10:24:17.167  4091  4091 D BluetoothPbap: Proxy object connected
08-29 10:24:17.167  4091  4091 D PbapServerProfile: Bluetooth service connected
,08-29 10:24:17.169  1359  1359 D BluetoothPbap: Proxy object connected
08-29 10:24:17.169  1359  1359 D PbapServerProfile: Bluetooth service connected
,08-29 10:24:17.174  4400  4400 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 10:24:17.174  4400  4400 D ObexServerSockets0: prepareForNewConnect()
,08-29 10:24:17.178  4400  4449 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 10:24:17.199  4400  4453 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 10:24:17.200  4400  4453 I BtOppRfcommListener: Accept thread started.
,08-29 10:24:17.216  1909  2170 D BluetoothHeadset: Proxy object connected
,08-29 10:24:17.217  4091  4104 D BluetoothHeadset: Proxy object connected
,08-29 10:24:17.217  4091  4091 D HeadsetProfile: Bluetooth service connected
08-29 10:24:17.218  1359  2171 D BluetoothHeadset: Proxy object connected
08-29 10:24:17.218  1359  1359 D HeadsetProfile: Bluetooth service connected
08-29 10:24:17.219   872   872 D BluetoothHeadset: Proxy object connected
08-29 10:24:17.219   872   872 D BluetoothHeadset: Proxy object connected
08-29 10:24:17.219   872   872 D BluetoothHeadset: Proxy object connected
,08-29 10:24:17.222   872   889 D BluetoothHeadset: Proxy object connected
,08-29 10:24:17.233   872   889 D BluetoothHeadset: Proxy object connected
,08-29 10:24:17.240  4091  4442 D BluetoothHeadset: Proxy object connected
,08-29 10:24:17.241  4091  4091 D HeadsetProfile: Bluetooth service connected
08-29 10:24:17.241   872   889 D BluetoothHeadset: Proxy object connected
,08-29 10:24:17.395  4023  4073 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:24:17.395  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:17.395  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:24:17.395  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:24:17.395  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:24:17.395  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:17.395  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:17.395  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 10:24:17.405  4023  4073 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 10:24:17.409  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 10:24:17.410  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c6cbf69 added. We now have 8 listener(s)
,08-29 10:24:17.410  4023  4073 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 10:24:17.416   872  2164 D WifiService: setWifiEnabled: false pid=4023, uid=10000
08-29 10:24:17.417   872  2164 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 10:24:17.431  4023  4073 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:24:17.432   872   883 D WifiService: setWifiEnabled: true pid=4023, uid=10000
08-29 10:24:17.432   872   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 10:24:17.449   872  1304 D WifiConfigStore: Loading config and enabling all networks 
,08-29 10:24:17.466  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:24:17.466  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:17.466  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:24:17.466  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:24:17.466  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:24:17.466  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:17.466  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:17.466  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 10:24:17.468  4023  4023 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 10:24:17.487   872  1304 D WifiConfigStore: loaded 0 passpoint configs
,08-29 10:24:17.488   872  1304 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-29 10:24:17.489   872  1304 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-29 10:24:17.490   872  1304 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-29 10:24:17.490   872  1304 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-29 10:24:17.491   872  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-29 10:24:17.491   872  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 10:24:17.503   370   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-29 10:24:17.503   872  1304 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.04 rxSuccessRate=0.05 delta 1000 -> 1000
,08-29 10:24:17.505   872  1304 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-29 10:24:17.505   370   870 D CommandListener: Setting iface cfg
,08-29 10:24:17.506   872  1303 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '163 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 163 Failed to set address (No such device)'
08-29 10:24:17.506   872  1303 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 10:24:17.519   872  1304 E native  : do suspend true
,08-29 10:24:17.525   872  1303 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 10:24:17.535   872  1303 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-29 10:24:17.542   872  1304 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-29 10:24:17.543   872  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 10:24:17.573   872  1304 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-29 10:24:17.628   872  1304 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-29 10:24:17.631  1485  1485 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 10:24:18.062  1485  1485 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 10:24:18.106  1485  1485 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 10:24:18.107  1485  1485 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-29 10:24:18.109   872  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 10:24:18.119   872  1304 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 10:24:18.120   872  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 10:24:18.120   872  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-29 10:24:18.141   872  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 10:24:18.156   370   870 D CommandListener: Setting iface cfg
,08-29 10:24:18.157   872  1304 D WifiStateMachine: Start Dhcp Watchdog 3
,08-29 10:24:18.173   872  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 10:24:18.202   872  4461 D DhcpClient: Receive thread started
,08-29 10:24:18.292   872  1304 E native  : do suspend false
,08-29 10:24:18.315   872  1962 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 10:24:18.332   872  4461 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-29 10:24:18.334   872  1962 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-29 10:24:18.338   872  1962 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-29 10:24:18.352   872  4461 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 10:24:18.354   872  1962 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-29 10:24:18.360   370   870 D CommandListener: Setting iface cfg
,08-29 10:24:18.373   872  1962 D DhcpClient: Scheduling renewal in 86399s
,08-29 10:24:18.373   872  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-29 10:24:18.376   872  1304 E native  : do suspend true
,08-29 10:24:18.392   872  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-29 10:24:18.396   872  1304 D WifiConfigStore: No blacklist allowed without epno enabled
,08-29 10:24:18.397   872  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-29 10:24:18.399   872  1306 D ConnectivityService: Adding iface wlan0 to network 102
,08-29 10:24:18.409   872  1304 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 10:24:18.455  4023  4073 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:24:18.455  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:18.455  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:24:18.455  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:24:18.455  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:24:18.455  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:18.455  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:18.455  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 10:24:18.457  4023  4073 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 10:24:18.461  4023  4073 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-29 10:24:18.462  4023  4073 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-29 10:24:18.465  4023  4073 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@5ac8318 Bundle[{}]
,08-29 10:24:18.465  4023  4073 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 10:24:18.466  4023  4073 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-29 10:24:18.468  4023  4073 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-29 10:24:18.469  4023  4073 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-29 10:24:18.471  4023  4073 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-29 10:24:18.471  4023  4073 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 10:24:18.477  4023  4073 I System.out: Running OutgoingSocketThread
,08-29 10:24:18.480  4023  4464 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 472)
,08-29 10:24:18.482  4023  4464 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 43550
,08-29 10:24:18.484   872  1306 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-29 10:24:18.484   872  1306 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-29 10:24:18.482  4023  4464 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...,
,08-29 10:24:18.485   872  1306 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-29 10:24:18.487   872  1306 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-29 10:24:18.488   872  1306 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-29 10:24:18.502   872  1306 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-29 10:24:18.507   872  1306 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-29 10:24:18.508   872  1306 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-29 10:24:18.508   872  1306 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-29 10:24:18.508   872  1306 D ConnectivityService:    accepting network in place of null
,08-29 10:24:18.508   872  1304 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-29 10:24:18.509   872  1306 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 10:24:18.510   872  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 10:24:18.523   872  4459 D NetlinkSocketObserver: NeighborEvent{elapsedMs=153579, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 10:24:18.559   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 10:24:18.596   872  4458 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.210.14,2a00:1450:4001:817::200e
,08-29 10:24:18.604   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 10:24:18.614   872  1306 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-29 10:24:18.614   872  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 10:24:18.615   872  1306 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-29 10:24:18.619   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-29 10:24:18.634  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:24:18.634  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:18.634  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:24:18.634  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:24:18.634  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:24:18.634  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:24:18.634  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:24:18.634  4023  4023 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:24:18.637  4023  4023 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 10:24:18.643  1749  1749 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 10:24:18.651  1749  1749 D SystemUpdateService: onCreate
,08-29 10:24:18.656  1749  1749 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 10:24:18.668  1749  4471 I SystemUpdateService: active receiver: enabled
,08-29 10:24:18.676   872  4458 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 08:24:18 GMT], X-Android-Received-Millis=[1472459058676], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472459058645]}
,08-29 10:24:18.678   872  1306 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 10:24:18.678   872  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,08-29 10:24:18.678   872  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-29 10:24:18.680   872  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-29 10:24:18.687  1749  1749 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 10:24:18.684  1749  4471 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 10:24:18.694  1749  1749 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-29 10:24:18.695  1749  4471 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-29 10:24:18.695  1749  4471 I SystemUpdateService: now status is 0 (complete)
08-29 10:24:18.695  1749  4471 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 10:24:18.695  1749  4471 I SystemUpdateService: file has been verified
08-29 10:24:18.695  1749  4471 I SystemUpdateService: OTA package size = 12249756
,08-29 10:24:18.698  1749  1749 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 10:24:18.688  1749  2476 I iu.UploadsManager: num queued entries: 0
,08-29 10:24:18.703  1749  4474 I MDM     : [186] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-29 10:24:18.703  1749  4474 W BaseAppContext: Using Auth Proxy for data requests.
08-29 10:24:18.703  1749  2476 I iu.UploadsManager: num updated entries: 0
,08-29 10:24:18.704  1749  4474 V GoogleAuthProtoRequest: [186] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 10:24:18.708  4208  4208 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 10:24:18.713  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 10:24:18.710  1749  2476 I iu.SyncManager: NEXT; no task
,08-29 10:24:18.717  4208  4208 D SprintDMHelper: simOperator: 
08-29 10:24:18.718  4208  4208 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-29 10:24:18.718  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 10:24:18.718  1749  4471 I SystemUpdateService: showing system update notification
,08-29 10:24:18.763  1749  1749 D SystemUpdateService: onDestroy
,08-29 10:24:18.773  1527  1539 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-29 10:24:18.774  1527  1539 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-29 10:24:18.775  1527  1539 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 10:24:18.775  1527  1539 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 10:24:18.809  1749  4474 E MDM     : [186] SitrepService.a: Error sending sitrep.
,08-29 10:24:18.887  4142  4477 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-29 10:24:19.485  4023  4073 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 473)
,08-29 10:24:19.487  4023  4073 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 473)
,08-29 10:24:19.497  4023  4073 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 478)
,08-29 10:24:19.499  4023  4073 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-29 10:24:19.500  4023  4073 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 479)
,08-29 10:24:19.508  4023  4073 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 10:24:19.508  4023  4073 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d5adee added. We now have 2 listener(s)
,08-29 10:24:19.512  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 10:24:19.512  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 10:24:19.512  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:24:19.512  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 10:24:19.512  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0dc28f added. We now have 9 listener(s)
08-29 10:24:19.512  4023  4073 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 10:24:19.513  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
08-29 10:24:19.516  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:24:19.522  4023  4073 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:24:19.522  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:19.522  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:24:19.522  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:24:19.522  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:24:19.522  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:24:19.522  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:24:19.522  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:24:19.524  4023  4073 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 10:24:19.524  4023  4073 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 10:24:19.524  4023  4073 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 10:24:19.524  4023  4073 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@708e925 added. We now have 3 listener(s)
08-29 10:24:19.526  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 10:24:19.526  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 10:24:19.526  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:24:19.527  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:24:19.527  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d72bafa added. We now have 10 listener(s)
,08-29 10:24:19.527  4023  4073 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:24:19.527  4023  4073 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:24:19.527  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 10:24:19.527  4023  4073 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:24:19.527  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 10:24:19.527  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:19.527  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:24:19.528  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 10:24:19.528  4023  4073 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d5adee removed from the list
08-29 10:24:19.528  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:19.528  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0dc28f removed from the list
08-29 10:24:19.529  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:24:19.531  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:24:19.531  4023  4073 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:24:19.532  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:19.532  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:24:19.533  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:19.534  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:19.534  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 10:24:19.535  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:19.535  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0dc28f not in the list
08-29 10:24:19.535  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:19.535  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:24:19.537  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:19.537  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:19.537  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:24:19.537  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d72bafa removed from the list
08-29 10:24:19.538  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:19.538  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:24:19.538  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:19.538  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 10:24:19.539  4023  4073 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@708e925 removed from the list
08-29 10:24:19.540  4023  4073 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 10:24:19.541  4023  4073 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@62df8ab added. We now have 2 listener(s)
,08-29 10:24:19.546  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 10:24:19.547  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 10:24:19.547  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:24:19.547  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 10:24:19.548  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2992b08 added. We now have 9 listener(s)
08-29 10:24:19.548  4023  4073 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:24:19.549  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 10:24:19.558  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:24:19.564  4023  4073 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:24:19.564  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:19.564  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:24:19.564  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:24:19.564  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:24:19.564  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:24:19.564  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:24:19.564  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:24:19.566  4023  4073 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 10:24:19.566  4023  4073 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 10:24:19.569  4023  4073 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 10:24:19.569  4023  4073 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a18cc6 added. We now have 3 listener(s)
,08-29 10:24:19.571  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:24:19.572  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 10:24:19.572  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 10:24:19.573  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 10:24:19.573  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 10:24:19.574  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:19.574  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd17487 added. We now have 10 listener(s)
08-29 10:24:19.574  4023  4073 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:24:19.574  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 10:24:19.575  4023  4073 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 10:24:19.575  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-29 10:24:19.575  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:24:19.575  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 10:24:19.578  4023  4073 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 10:24:19.578  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 10:24:19.582  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 10:24:19.583  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 10:24:19.583  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 10:24:19.586  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 10:24:19.587  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 10:24:19.587  4023  4073 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 10:24:19.588  4023  4073 D BluetoothAdapter: STATE_ON
,08-29 10:24:19.591  4400  4410 D BtGatt.GattService: registerClient() - UUID=62d1c123-9d07-45b0-a1f9-44222e6c95ab
,08-29 10:24:19.591  4400  4416 D BtGatt.GattService: onClientRegistered() - UUID=62d1c123-9d07-45b0-a1f9-44222e6c95ab, clientIf=5
,08-29 10:24:19.592  4023  4064 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 10:24:19.594  4400  4433 D BtGatt.GattService: start scan with filters
,08-29 10:24:19.599  4400  4419 D BtGatt.ScanManager: handling starting scan
,08-29 10:24:19.599  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 10:24:19.599  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 10:24:19.599  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 10:24:19.599  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 10:24:19.600  4400  4419 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b0902c
,08-29 10:24:19.604  4023  4073 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 10:24:19.604  4023  4073 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 10:24:19.604  4023  4023 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 10:24:19.606  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 10:24:19.607  4400  4416 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 10:24:19.607  4400  4416 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:24:19.608  4400  4419 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 10:24:19.611  4023  4073 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-29 10:24:19.611  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 10:24:19.611  4023  4073 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 10:24:19.611  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:19.611  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 10:24:19.611  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-29 10:24:19.612  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 10:24:19.612  4023  4073 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 10:24:19.612  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 10:24:19.612  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 10:24:19.612  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 10:24:19.613  4023  4073 D BluetoothAdapter: STATE_ON
08-29 10:24:19.614   872  1306 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-29 10:24:19.615  4400  4410 D BtGatt.GattService: stopScan() - queue size =1
,08-29 10:24:19.616  4400  4433 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 10:24:19.617  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 10:24:19.617  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 10:24:19.617  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 10:24:19.618  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-29 10:24:19.618  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 10:24:19.619  4400  4416 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 10:24:19.619  4400  4416 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:24:19.620  4400  4419 D BtGatt.ScanManager: Starting BLE batch scan
08-29 10:24:19.620  4400  4419 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 10:24:19.620  4023  4073 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 10:24:19.621  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 10:24:19.621  4023  4073 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-29 10:24:19.621  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 10:24:19.623  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:24:19.625  4023  4023 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 10:24:19.625  4023  4023 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 10:24:19.625  4023  4023 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 10:24:19.629  4023  4073 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 10:24:19.630  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 10:24:19.630  4023  4073 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 10:24:19.630  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 10:24:19.630  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:24:19.631  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:24:19.631  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 10:24:19.631  4023  4073 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@62df8ab removed from the list
,08-29 10:24:19.631  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:24:19.631  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2992b08 removed from the list
,08-29 10:24:19.631  4023  4073 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 10:24:19.632  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:24:19.632  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:24:19.633  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:19.634  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 10:24:19.635  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 10:24:19.635  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:24:19.635  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2992b08 not in the list
,08-29 10:24:19.635  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:24:19.636  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:19.636  4400  4416 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 10:24:19.636  4400  4416 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:24:19.638  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 10:24:19.638  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:19.638  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:24:19.638  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd17487 removed from the list
08-29 10:24:19.638  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
,08-29 10:24:19.638  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:19.639  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:24:19.639  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 10:24:19.639  4023  4073 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a18cc6 removed from the list
,08-29 10:24:19.641  4023  4073 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 10:24:19.641  4023  4073 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@546d223 added. We now have 2 listener(s)
,08-29 10:24:19.645  4400  4416 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 10:24:19.645  4400  4416 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:24:19.646  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 10:24:19.646  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
,08-29 10:24:19.646  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:24:19.647  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 10:24:19.647  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d405320 added. We now have 9 listener(s)
08-29 10:24:19.647  4023  4073 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 10:24:19.648  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 10:24:19.653  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:24:19.655  4400  4416 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 10:24:19.656  4400  4416 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-29 10:24:19.656  4400  4419 D BtGatt.ScanManager: stopping BLe Batch
,08-29 10:24:19.658  4023  4073 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:24:19.658  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:19.658  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:24:19.658  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:24:19.658  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:24:19.658  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:24:19.658  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:24:19.658  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:24:19.660  4023  4073 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 10:24:19.660  4023  4073 D io.jxcore.node.ConnectivityMonitor: start: OK,
08-29 10:24:19.661  4023  4073 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 10:24:19.661  4023  4073 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7f6e9e added. We now have 3 listener(s)
,08-29 10:24:19.663  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:19.664  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 10:24:19.664  4400  4416 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-29 10:24:19.664  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 10:24:19.664  4400  4416 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:24:19.664  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:24:19.664  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 10:24:19.664  4400  4419 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 10:24:19.664  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92a6d7f added. We now have 10 listener(s),
,08-29 10:24:19.664  4023  4073 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:24:19.665  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 10:24:19.666  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:19.667  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 10:24:19.667  4023  4073 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-29 10:24:19.667  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-29 10:24:19.667  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:24:19.667  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 10:24:19.671  4023  4073 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 10:24:19.671  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 10:24:19.672  4400  4416 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-29 10:24:19.672  4400  4416 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:24:19.675  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 10:24:19.676  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 10:24:19.676  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 10:24:19.679  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 10:24:19.679  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 10:24:19.679  4023  4073 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 10:24:19.680  4023  4073 D BluetoothAdapter: STATE_ON
,08-29 10:24:19.682  4400  4433 D BtGatt.GattService: registerClient() - UUID=be1299f1-9cbd-48d3-9a91-d4655cdcef19
,08-29 10:24:19.682  4400  4416 D BtGatt.GattService: onClientRegistered() - UUID=be1299f1-9cbd-48d3-9a91-d4655cdcef19, clientIf=5
08-29 10:24:19.682  4023  4064 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 10:24:19.683  4400  4445 D BtGatt.GattService: start scan with filters
,08-29 10:24:19.685  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 10:24:19.685  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 10:24:19.685  4400  4419 D BtGatt.ScanManager: handling starting scan
08-29 10:24:19.685  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 10:24:19.685  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 10:24:19.688  4023  4073 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 10:24:19.688  4023  4073 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 10:24:19.688  4023  4023 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 10:24:19.690  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 10:24:19.693  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 10:24:19.693  4023  4073 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-29 10:24:19.693  4023  4073 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:24:19.693  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:24:19.693  4023  4073 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 10:24:19.693  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:19.694  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:19.694  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 10:24:19.694  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 10:24:19.694  4023  4073 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@546d223 removed from the list
08-29 10:24:19.694  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:19.694  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d405320 removed from the list
,08-29 10:24:19.694  4023  4073 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 10:24:19.694  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:24:19.695  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:24:19.695  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-29 10:24:19.695  4400  4416 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 10:24:19.695  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:24:19.695  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:24:19.695  4400  4416 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:24:19.695  4400  4419 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 10:24:19.696  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:19.696  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:19.696  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:19.696  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d405320 not in the list
,08-29 10:24:19.697  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 10:24:19.697  4023  4073 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 10:24:19.697  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 10:24:19.697  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 10:24:19.697  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 10:24:19.697  4023  4073 D BluetoothAdapter: STATE_ON
,08-29 10:24:19.698  4400  4445 D BtGatt.GattService: stopScan() - queue size =1
08-29 10:24:19.699  4400  4411 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 10:24:19.700  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 10:24:19.700  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 10:24:19.700  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 10:24:19.700  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 10:24:19.700  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 10:24:19.702  4023  4073 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 10:24:19.702  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 10:24:19.702  4023  4073 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 10:24:19.702  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 10:24:19.703  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:19.704  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:19.704  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:19.704  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:24:19.704  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92a6d7f removed from the list
08-29 10:24:19.704  4023  4023 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:24:19.704  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:19.704  4023  4023 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:24:19.704  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:24:19.704  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:24:19.704  4023  4023 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 10:24:19.704  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 10:24:19.705  4023  4073 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7f6e9e removed from the list
08-29 10:24:19.705  4023  4073 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 10:24:19.705  4023  4073 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@182629b added. We now have 2 listener(s)
08-29 10:24:19.707  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 10:24:19.707  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 10:24:19.707  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:24:19.708  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:24:19.708  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d716638 added. We now have 9 listener(s)
08-29 10:24:19.708  4023  4073 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:24:19.708  4400  4416 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 10:24:19.708  4400  4416 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:24:19.709  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 10:24:19.709  4400  4419 D BtGatt.ScanManager: Starting BLE batch scan
08-29 10:24:19.709  4400  4419 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 10:24:19.712  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:24:19.717  4023  4073 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:24:19.717  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:19.717  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:24:19.717  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:24:19.717  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:24:19.717  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:24:19.717  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:24:19.717  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:24:19.719  4023  4073 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 10:24:19.720  4023  4073 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 10:24:19.720  4023  4073 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 10:24:19.720  4023  4073 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4cb376 added. We now have 3 listener(s)
08-29 10:24:19.723  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:24:19.724  4400  4416 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 10:24:19.724  4400  4416 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:24:19.725  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 10:24:19.725  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 10:24:19.725  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:24:19.725  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:19.725  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 10:24:19.725  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@89a8d77 added. We now have 10 listener(s)
08-29 10:24:19.725  4023  4073 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:24:19.726  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 10:24:19.726  4023  4073 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 10:24:19.726  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 10:24:19.726  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:24:19.726  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 10:24:19.730  4023  4073 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 10:24:19.730  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 10:24:19.733  4400  4416 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 10:24:19.733  4400  4416 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:24:19.735  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 10:24:19.736  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 10:24:19.736  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 10:24:19.740  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 10:24:19.740  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 10:24:19.740  4023  4073 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 10:24:19.742  4023  4073 D BluetoothAdapter: STATE_ON
,08-29 10:24:19.743  4400  4416 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-29 10:24:19.743  4400  4416 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:24:19.743  4400  4419 D BtGatt.ScanManager: stopping BLe Batch
,08-29 10:24:19.745  4400  4444 D BtGatt.GattService: registerClient() - UUID=2606a743-73cf-4801-a651-4bb6adcfbe1f
,08-29 10:24:19.745  4400  4416 D BtGatt.GattService: onClientRegistered() - UUID=2606a743-73cf-4801-a651-4bb6adcfbe1f, clientIf=5
,08-29 10:24:19.746  4023  4035 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 10:24:19.747  4400  4433 D BtGatt.GattService: start scan with filters
,08-29 10:24:19.750  4400  4416 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-29 10:24:19.750  4400  4416 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:24:19.750  4400  4419 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 10:24:19.751  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 10:24:19.751  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 10:24:19.752  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 10:24:19.752  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 10:24:19.756  4023  4073 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 10:24:19.757  4023  4023 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 10:24:19.757  4023  4073 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 10:24:19.757  4400  4416 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-29 10:24:19.757  4400  4416 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:24:19.759  4400  4419 D BtGatt.ScanManager: handling starting scan
,08-29 10:24:19.760  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
,08-29 10:24:19.767  4400  4416 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 10:24:19.767  4400  4416 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:24:19.767  4400  4419 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 10:24:19.767  4023  4073 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 10:24:19.768  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:24:19.768  4023  4073 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:24:19.768  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:19.768  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:24:19.768  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 10:24:19.768  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 10:24:19.768  4023  4073 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@182629b removed from the list
,08-29 10:24:19.769  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:24:19.769  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d716638 removed from the list
,08-29 10:24:19.770  4023  4073 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 10:24:19.770  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:24:19.772  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:24:19.772  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-29 10:24:19.772  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:19.772  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:24:19.773  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 10:24:19.773  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 10:24:19.773  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:24:19.773  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d716638 not in the list,
,08-29 10:24:19.774  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 10:24:19.774  4023  4073 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 10:24:19.774  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 10:24:19.774  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 10:24:19.774  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 10:24:19.775  4023  4073 D BluetoothAdapter: STATE_ON
,08-29 10:24:19.775  4400  4433 D BtGatt.GattService: stopScan() - queue size =1
,08-29 10:24:19.775  4400  4416 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 10:24:19.775  4400  4416 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:24:19.776  4400  4419 D BtGatt.ScanManager: Starting BLE batch scan
08-29 10:24:19.776  4400  4419 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 10:24:19.776  4400  4444 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 10:24:19.776  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 10:24:19.776  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-29 10:24:19.777  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 10:24:19.777  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-29 10:24:19.777  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 10:24:19.778  4023  4073 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 10:24:19.778  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 10:24:19.778  4023  4073 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 10:24:19.778  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 10:24:19.779  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:19.780  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:19.780  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 10:24:19.780  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:19.780  4023  4023 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:24:19.780  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@89a8d77 removed from the list
,08-29 10:24:19.780  4023  4023 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:24:19.781  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 10:24:19.781  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:24:19.781  4023  4023 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 10:24:19.781  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:19.781  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 10:24:19.781  4023  4073 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4cb376 removed from the list
08-29 10:24:19.782  4023  4073 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 10:24:19.782  4023  4073 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a08a13 added. We now have 2 listener(s)
,08-29 10:24:19.784  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 10:24:19.784  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 10:24:19.784  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 10:24:19.784  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:24:19.784  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71ec450 added. We now have 9 listener(s)
08-29 10:24:19.784  4023  4073 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 10:24:19.785  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 10:24:19.788  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:24:19.791  4400  4416 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 10:24:19.792  4400  4416 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:24:19.793  4023  4073 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:24:19.793  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:19.793  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:24:19.793  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:24:19.793  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:24:19.793  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:24:19.793  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
,08-29 10:24:19.793  4023  4073 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:24:19.795  4023  4073 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 10:24:19.795  4023  4073 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 10:24:19.795  4023  4073 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 10:24:19.795  4023  4073 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c32bb4e added. We now have 3 listener(s)
,08-29 10:24:19.797  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:24:19.798  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 10:24:19.798  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 10:24:19.798  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 10:24:19.799  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
,08-29 10:24:19.799  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ffb46f added. We now have 10 listener(s)
08-29 10:24:19.799  4023  4073 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 10:24:19.799  4023  4073 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:24:19.799  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:24:19.799  4023  4073 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 10:24:19.799  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:19.799  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:19.799  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:24:19.800  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 10:24:19.800  4400  4416 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 10:24:19.800  4400  4416 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:24:19.800  4023  4073 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a08a13 removed from the list
08-29 10:24:19.800  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:19.800  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71ec450 removed from the list
08-29 10:24:19.800  4023  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:24:19.801  4023  4073 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:24:19.801  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:19.801  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:19.801  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:19.803  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 10:24:19.803  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:19.803  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:19.803  4023  4073 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71ec450 not in the list
08-29 10:24:19.803  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:19.803  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:19.804  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 10:24:19.804  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:19.804  4023  4073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:19.805  4023  4073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ffb46f removed from the list
08-29 10:24:19.805  4023  4073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:19.805  4023  4073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:19.805  4023  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:24:19.805  4023  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 10:24:19.805  4023  4073 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c32bb4e removed from the list
08-29 10:24:19.806  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-29 10:24:19.806  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 10:24:19.806  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-29 10:24:19.806  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 10:24:19.806  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-29 10:24:19.806  4023  4073 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 10:24:19.808  4400  4416 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 10:24:19.808  4400  4416 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:24:19.808  4400  4419 D BtGatt.ScanManager: stopping BLe Batch
,08-29 10:24:19.814  4400  4416 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 10:24:19.814  4400  4416 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:24:19.814  4400  4419 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 10:24:19.817  4023  4483 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 486, name: My test thread name)
,08-29 10:24:19.817  4023  4483 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 486, thread name: My test thread name)
08-29 10:24:19.817  4023  4483 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 486, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-29 10:24:19.819  4023  4484 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 488, name: My test thread name)
08-29 10:24:19.819  4023  4484 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 488, thread name: My test thread name)
08-29 10:24:19.819  4023  4484 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 488, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-29 10:24:19.820  4400  4416 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 10:24:19.820  4400  4416 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:24:19.822  4023  4073 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-29 10:24:19.822  4023  4073 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,08-29 10:24:19.822  4023  4073 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-29 10:24:19.822  4023  4073 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,08-29 10:24:19.823  4023  4073 D com.test.thalitest.ThaliTestRunner: Total duration: 22897 ms
,08-29 10:24:19.826  4023  4073 I jxcore-log: *Native tests were executed*
08-29 10:24:19.826  4023  4073 I jxcore-log: 
,08-29 10:24:19.826  4023  4073 I jxcore-log: Total number of executed tests:  80
08-29 10:24:19.826  4023  4073 I jxcore-log: 
,08-29 10:24:19.826  4023  4073 I jxcore-log: Number of passed tests:  80
08-29 10:24:19.826  4023  4073 I jxcore-log: 
,08-29 10:24:19.826  4023  4073 I jxcore-log: Number of failed tests:  0
08-29 10:24:19.826  4023  4073 I jxcore-log: 
08-29 10:24:19.827  4023  4073 I jxcore-log: Number of ignored tests:  0
08-29 10:24:19.827  4023  4073 I jxcore-log: 
08-29 10:24:19.827  4023  4073 I jxcore-log: Total duration:  22897
08-29 10:24:19.827  4023  4073 I jxcore-log: 
,08-29 10:24:19.827  4023  4073 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-29 10:24:19.827  4023  4073 I jxcore-log: 
,08-29 10:24:19.831  4023  4073 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:24:19.831  4023  4073 I jxcore-log: 
08-29 10:24:19.834  4023  4073 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:24:19.834  4023  4073 I jxcore-log: 
08-29 10:24:19.835  4023  4073 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:24:19.835  4023  4073 I jxcore-log: 
08-29 10:24:19.836  4023  4073 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:24:19.836  4023  4073 I jxcore-log: 
08-29 10:24:19.837  4023  4073 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:24:19.837  4023  4073 I jxcore-log: 
08-29 10:24:19.838  4023  4073 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:24:19.838  4023  4073 I jxcore-log: 
08-29 10:24:19.841  4023  4073 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:24:19.841  4023  4073 I jxcore-log: 
08-29 10:24:19.842  4023  4023 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-29 10:24:19.843  4023  4073 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 10:24:19.843  4023  4073 I jxcore-log: 
,08-29 10:24:19.843  4023  4073 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 10:24:19.843  4023  4073 I jxcore-log: 
,08-29 10:24:19.844  4023  4073 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 10:24:19.844  4023  4073 I jxcore-log: 
08-29 10:24:19.845  4023  4073 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 10:24:19.845  4023  4073 I jxcore-log: 
,08-29 10:24:19.846  4023  4073 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 10:24:19.846  4023  4073 I jxcore-log: 
,08-29 10:24:19.847  4023  4073 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 10:24:19.847  4023  4073 I jxcore-log: 
08-29 10:24:19.847  4023  4073 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:24:19.847  4023  4073 I jxcore-log: 
,08-29 10:24:19.848  4023  4073 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:24:19.848  4023  4073 I jxcore-log: 
08-29 10:24:19.848  4023  4073 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 10:24:19.848  4023  4073 I jxcore-log: 
08-29 10:24:19.849  4023  4073 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 10:24:19.849  4023  4073 I jxcore-log: 
08-29 10:24:19.851  4023  4073 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"},
08-29 10:24:19.851  4023  4073 I jxcore-log: 
08-29 10:24:19.851  4023  4073 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 10:24:19.851  4023  4073 I jxcore-log: 
08-29 10:24:19.852  4023  4073 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 10:24:19.852  4023  4073 I jxcore-log: 
08-29 10:24:19.852  4023  4073 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 10:24:19.852  4023  4073 I jxcore-log: 
,08-29 10:24:19.853  4023  4073 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 10:24:19.853  4023  4073 I jxcore-log: 
08-29 10:24:19.853  4023  4073 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 10:24:19.853  4023  4073 I jxcore-log: 
,08-29 10:24:19.854  4023  4073 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 10:24:19.854  4023  4073 I jxcore-log: 
,08-29 10:24:19.854  4023  4073 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 10:24:19.854  4023  4073 I jxcore-log: 
08-29 10:24:19.855  4023  4073 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:24:19.855  4023  4073 I jxcore-log: 
08-29 10:24:19.855  4023  4073 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
08-29 10:24:19.855  4023  4073 I jxcore-log: 
08-29 10:24:19.856  4023  4073 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:24:19.856  4023  4073 I jxcore-log: 
,08-29 10:24:19.856  4023  4073 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:24:19.856  4023  4073 I jxcore-log: 
,08-29 10:24:19.857  4023  4073 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:24:19.857  4023  4073 I jxcore-log: 
08-29 10:24:19.857  4023  4073 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:24:19.857  4023  4073 I jxcore-log: 
,08-29 10:24:20.126  4023  4023 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 10:24:20.128  4023  4073 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 10:24:20.128  4023  4073 I jxcore-log: 
,08-29 10:24:20.205  4023  4023 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 10:24:20.208  4023  4073 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 10:24:20.208  4023  4073 I jxcore-log: 
,08-29 10:24:20.281  4023  4023 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 10:24:20.284  4023  4073 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 10:24:20.284  4023  4073 I jxcore-log: 
,08-29 10:24:20.528  4485  4485 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-29 10:24:20.534  4485  4485 D AndroidRuntime: CheckJNI is OFF
,08-29 10:24:20.577  4485  4485 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-29 10:24:20.625  4485  4485 I Radio-JNI: register_android_hardware_Radio DONE
,08-29 10:24:20.648  4485  4485 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-29 10:24:20.662   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-29 10:24:20.663   872   885 I ActivityManager: Killing 4023:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-29 10:24:20.769   872  1694 D GraphicsStats: Buffer count: 2
,08-29 10:24:20.769   872  1694 I WindowState: WIN DEATH: Window{d330ffd u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-29 10:24:20.772   872  1305 D WifiService: Client connection lost with reason: 4
,08-29 10:24:20.787   872   895 W PackageSettings: Skipping PackageSetting{8f7ad49 com.example.hello/10273} due to missing metadata
,08-29 10:24:20.834   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-29 10:24:20.834   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-29 10:24:20.834   872   885 E ActivityManager: Failure starting process com.test.thalitest,
08-29 10:24:20.834   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-29 10:24:20.834   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-29 10:24:20.834   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-29 10:24:20.834   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-29 10:24:20.834   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-29 10:24:20.834   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-29 10:24:20.834   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-29 10:24:20.834   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-29 10:24:20.834   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-29 10:24:20.834   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-29 10:24:20.834   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-29 10:24:20.834   872   885 E ActivityManager: 	,at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-29 10:24:20.834   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-29 10:24:20.834   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-29 10:24:20.834   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-29 10:24:20.834   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:24:20.834   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-29 10:24:20.834   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 10:24:20.834   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-29 10:24:20.835   872   885 I ActivityManager:   Force finishing activity ActivityRecord{48ae93a u0 com.test.thalitest/.MainActivity t2}
,08-29 10:24:20.837   872   895 I art     : Starting a blocking GC Explicit
,08-29 10:24:20.845   872  2043 W ActivityManager: Spurious death for ProcessRecord{f6d3993 0:com.test.thalitest/u0a0}, curProc for 4023: null
,08-29 10:24:20.901   872   895 I art     : Explicit concurrent mark sweep GC freed 55955(3MB) AllocSpace objects, 10(284KB) LOS objects, 33% free, 29MB/43MB, paused 843us total 63.389ms
08-29 10:24:20.901   872   881 I art     : WaitForGcToComplete blocked for 39.440ms for cause HeapTrim
,08-29 10:24:20.952   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-29 10:24:20.954  4485  4485 I art     : System.exit called, status: 0
08-29 10:24:20.954  4485  4485 I AndroidRuntime: VM exiting with result code 0.
,08-29 10:24:20.957   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-29 10:24:20.976   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-29 10:24:20.982   872  1296 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-29 10:24:20.984  3861  3861 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-29 10:24:20.986  4400  4400 D BluetoothMapAppObserver: onReceive
08-29 10:24:20.986  4400  4400 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-29 10:24:20.988  1850  1850 I Keyboard.Facilitator: resetDictionaries() : en_US
08-29 10:24:20.988  2134  2317 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-29 10:24:20.998  1850  4498 I Keyboard.Facilitator.DecoderInitializer: run()
,08-29 10:24:21.004  1850  4498 I Decoder : createOrResetDecoder
,08-29 10:24:21.022   872  1929 I ActivityManager: Start proc 4500:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-29 10:24:21.042  1909  1909 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-29 10:24:21.047   872  1302 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,08-29 10:24:21.052  1527  1527 I ConfigService: onCreate
,08-29 10:24:21.056  1527  4512 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-29 10:24:21.056  1527  4512 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 10:24:21.056  1527  4512 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 10:24:21.056  1527  4512 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 10:24:21.056  1527  4512 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 10:24:21.056  1527  4512 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 10:24:21.056  1527  4512 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 10:24:21.056  1527  4512 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 10:24:21.056  1527  4512 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 10:24:21.056  1527  4512 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 10:24:21.056  1527  4512 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 10:24:21.056  1527  4512 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 10:24:21.056  1527  4512 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 10:24:21.056  1527  4512 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 10:24:21.056  1527  4512 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 10:24:21.056  1527  4512 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-29 10:24:21.056  1527  4512 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-29 10:24:21.056  1527  4512 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-29 10:24:21.056  1527  4512 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):,
08-29 10:24:21.056  1527  4512 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 10:24:21.056  1527  4512 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 10:24:21.056  1527  4512 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 10:24:21.056  1527  4512 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 10:24:21.056  1527  4512 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 10:24:21.056  1527  4512 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 10:24:21.056  1527  4512 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 10:24:21.056  1527  4512 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 10:24:21.056  1527  4512 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 10:24:21.056  1527  4512 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 10:24:21.056  1527  4512 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 10:24:21.056  1527  4512 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 10:24:21.056  1527  4512 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 10:24:21.056  1527  4512 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 10:24:21.056  1527  4512 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-29 10:24:21.056  1527  4512 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-29 10:24:21.056  1527  4512 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-29 10:24:21.057  1527  4512 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-29 10:24:21.075  1850  4498 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-29 10:24:21.079   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-29 10:24:21.093  4500  4500 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-29 10:24:21.102   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-29 10:24:21.102   872   884 E PackageManager: Failed to write settings, restoring backup
08-29 10:24:21.102   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-29 10:24:21.102   872   884 E PackageManager: ,	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-29 10:24:21.102   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-29 10:24:21.102   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-29 10:24:21.102   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-29 10:24:21.102   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:24:21.102   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-29 10:24:21.102   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 10:24:21.106   872   883 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 4023 uid 10000
,08-29 10:24:21.107   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-29 10:24:21.107   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-29 10:24:21.107   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 10:24:21.107   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 10:24:21.107   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 10:24:21.107   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 10:24:21.107   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 10:24:21.107   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 10:24:21.107   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-29 10:24:21.107   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-29 10:24:21.107   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-29 10:24:21.107   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 10:24:21.107   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 10:24:21.107   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-29 10:24:21.107   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 10:24:21.107   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-29 10:24:21.107   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 10:24:21.107   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 10:24:21.107   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 10:24:21.107   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438),
08-29 10:24:21.107   872   885 E DropBoxManagerService: 	... 13 more
08-29 10:24:21.107  1922  1993 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-29 10:24:21.107  1850  1850 I Keyboard.Facilitator: onFinishInput()
,08-29 10:24:21.114  1850  4498 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-29 10:24:21.116  1850  4498 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-29 10:24:21.116  1850  4498 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-29 10:24:21.119  1850  4498 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-29 10:24:21.119  1850  4498 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-29 10:24:21.119   872  2161 I ActivityManager: Start proc 4514:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-29 10:24:21.120  1922  1993 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-29 10:24:21.120  1922  1993 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1922
08-29 10:24:21.120  1922  1993 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 10:24:21.120  1922  1993 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 10:24:21.120  1922  1993 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 10:24:21.120  1922  1993 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 10:24:21.120  1922  1993 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 10:24:21.120  1922  1993 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 10:24:21.120  1922  1993 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-29 10:24:21.120  1922  1993 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-29 10:24:21.120  1922  1993 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 10:24:21.120  1922  1993 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 10:24:21.120  1922  1993 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 10:24:21.120  1922  1993 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 10:24:21.120  1850  4498 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-29 10:24:21.121  1850  4498 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-29 10:24:21.122   872  2043 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-29 10:24:21.123   872  4520 E DropBoxManagerService: Can't write: system_app_crash
08-29 10:24:21.123   872  4520 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
08-29 10:24:21.123   872  4520 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 10:24:21.123   872  4520 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 10:24:21.123   872  4520 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 10:24:21.123   872  4520 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 10:24:21.123   872  4520 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 10:24:21.123   872  4520 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 10:24:21.123   872  4520 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 10:24:21.123   872  4520 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 10:24:21.123   872  4520 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 10:24:21.123   872  4520 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 10:24:21.123   872  4520 E DropBoxManagerService: 	... 5 more
,08-29 10:24:21.126  1922  1993 I Process : Sending signal. PID: 1922 SIG: 9
08-29 10:24:21.133  1850  4498 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-29 10:24:21.133  1850  4498 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-29 10:24:21.133  1850  4498 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-29 10:24:21.133  1850  4498 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-29 10:24:21.133  1850  4498 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,08-29 10:24:21.133  1850  4498 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-29 10:24:21.164  4500  4500 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-29 10:24:21.181   872  1929 I ActivityManager: Start proc 4531:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-29 10:24:21.184   872  2744 D GraphicsStats: Buffer count: 1
,08-29 10:24:21.184   872  2043 I WindowState: WIN DEATH: Window{d80c73a u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-29 10:24:21.189   872  2744 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1922) has died
,08-29 10:24:21.190   872  2744 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-29 10:24:21.191   872  2744 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-29 10:24:21.181  4500  4530 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-29 10:24:21.212   872   885 I ActivityManager: Start proc 4544:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-29 10:24:21.246  4531  4531 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-29 10:24:21.248  4500  4530 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-29 10:24:21.248  4500  4530 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 10:24:21.248  4500  4530 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 10:24:21.248  4500  4530 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 10:24:21.248  4500  4530 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 10:24:21.248  4500  4530 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 10:24:21.248  4500  4530 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 10:24:21.248  4500  4530 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 10:24:21.248  4500  4530 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 10:24:21.248  4500  4530 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 10:24:21.248  4500  4530 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 10:24:21.248  4500  4530 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 10:24:21.248  4500  4530 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 10:24:21.248  4500  4530 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 10:24:21.248  4500  4530 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 10:24:21.248  4500  4530 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-29 10:24:21.248  4500  4530 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-29 10:24:21.248  4500  4530 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 10:24:21.248  4500  4530 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 10:24:21.248  4500  4530 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-29 10:24:21.248  4500  4530 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-29 10:24:21.248  4500  4530 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 10:24:21.248  4500  4530 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:24:21.248  4500  4530 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 10:24:21.248  4500  4530 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 10:24:21.249  4500  4530 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-29 10:24:21.249  4500  4530 E AndroidRuntime: Process: android.process.acore, PID: 4500
08-29 10:24:21.249  4500  4530 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 10:24:21.249  4500  4530 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 10:24:21.249  4500  4530 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 10:24:21.249  4500  4530 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 10:24:21.249  4500  4530 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 10:24:21.249  4500  4530 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 10:24:21.249  4500  4530 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 10:24:21.249  4500  4530 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 10:24:21.249  4500  4530 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 10:24:21.249  4500  4530 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 10:24:21.249  4500  4530 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 10:24:21.249  4500  4530 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 10:24:21.249  4500  4530 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 10:24:21.249  4500  4530 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 10:24:21.249  4500  4530 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-29 10:24:21.249  4500  4530 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-29 10:24:21.249  4500  4530 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 10:24:21.249  4500  4530 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 10:24:21.249  4500  4530 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-29 10:24:21.249  4500  4530 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-29 10:24:21.249  4500  4530 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 10:24:21.249  4500  4530 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:24:21.249  4500  4530 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 10:24:21.249  4500  4530 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 10:24:21.255   872  4557 E DropBoxManagerService: Can't write: system_app_crash
08-29 10:24:21.255   872  4557 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-29 10:24:21.255   872  4557 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 10:24:21.255   872  4557 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 10:24:21.255   872  4557 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 10:24:21.255   872  4557 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 10:24:21.255   872  4557 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 10:24:21.255   872  4557 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 10:24:21.255   872  4557 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 10:24:21.255   872  4557 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 10:24:21.255   872  4557 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 10:24:21.255   872  4557 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 10:24:21.255   872  4557 E DropBoxManagerService: 	... 5 more
,08-29 10:24:21.257  4500  4530 I Process : Sending signal. PID: 4500 SIG: 9
,08-29 10:24:21.258   281   281 E lowmemorykiller: Error writing /proc/4500/oom_score_adj; errno=22
,08-29 10:24:21.266  4544  4544 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-29 10:24:21.266  4544  4544 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 10:24:21.266  4544  4544 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 10:24:21.266  4544  4544 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 10:24:21.266  4544  4544 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 10:24:21.266  4544  4544 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 10:24:21.266  4544  4544 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 10:24:21.266  4544  4544 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 10:24:21.266  4544  4544 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 10:24:21.266  4544  4544 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 10:24:21.266  4544  4544 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 10:24:21.266  4544  4544 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 10:24:21.266  4544  4544 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 10:24:21.266  4544  4544 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 10:24:21.266  4544  4544 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 10:24:21.266  4544  4544 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-29 10:24:21.266  4544  4544 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-29 10:24:21.266  4544  4544 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 10:24:21.266  4544  4544 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 10:24:21.266  4544  4544 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 10:24:21.266  4544  4544 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 10:24:21.266  4544  4544 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 10:24:21.266  4544  4544 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 10:24:21.266  4544  4544 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 10:24:21.266  4544  4544 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:24:21.266  4544  4544 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 10:24:21.266  4544  4544 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 10:24:21.266  4544  4544 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:24:21.266  4544  4544 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 10:24:21.266  4544  4544 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 10:24:21.266  4544  4544 D AndroidRuntime: Shutting down VM
,08-29 10:24:21.269  1527  1527 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-29 10:24:21.270  1527  1527 D AndroidRuntime: Shutting down VM
,08-29 10:24:21.271  1527  1527 E AndroidRuntime: FATAL EXCEPTION: main
08-29 10:24:21.271  1527  1527 E AndroidRuntime: Process: com.google.process.gapps, PID: 1527
08-29 10:24:21.271  1527  1527 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 10:24:21.271  1527  1527 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-29 10:24:21.271  1527  1527 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-29 10:24:21.271  1527  1527 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-29 10:24:21.271  1527  1527 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:24:21.271  1527  1527 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 10:24:21.271  1527  1527 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 10:24:21.271  1527  1527 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:24:21.271  1527  1527 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 10:24:21.271  1527  1527 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 10:24:21.271  1527  1527 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 10:24:21.271  1527  1527 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 10:24:21.271  1527  1527 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 10:24:21.271  1527  1527 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 10:24:21.271  1527  1527 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 10:24:21.271  1527  1527 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 10:24:21.271  1527  1527 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-29 10:24:21.271  1527  1527 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-29 10:24:21.271  1527  1527 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-29 10:24:21.271  1527  1527 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-29 10:24:21.271  1527  1527 E AndroidRuntime: 	... 8 more
,08-29 10:24:21.271  4544  4544 E AndroidRuntime: FATAL EXCEPTION: main
08-29 10:24:21.271  4544  4544 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4544
08-29 10:24:21.271  4544  4544 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 10:24:21.271  4544  4544 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-29 10:24:21.271  4544  4544 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 10:24:21.271  4544  4544 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 10:24:21.271  4544  4544 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 10:24:21.271  4544  4544 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 10:24:21.271  4544  4544 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:24:21.271  4544  4544 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 10:24:21.271  4544  4544 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 10:24:21.271  4544  4544 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:24:21.271  4544  4544 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 10:24:21.271  4544  4544 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 10:24:21.271  4544  4544 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 10:24:21.271  4544  4544 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 10:24:21.271  4544  4544 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 10:24:21.271  4544  4544 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 10:24:21.271  4544  4544 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 10:24:21.271  4544  4544 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 10:24:21.271  4544  4544 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 10:24:21.271  4544  4544 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 10:24:21.271  4544  4544 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 10:24:21.271  4544  4544 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 10:24:21.271  4544  4544 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 10:24:21.271  4544  4544 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 10:24:21.271  4544  4544 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 10:24:21.271  4544  4544 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 10:24:21.271  4544  4544 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-29 10:24:21.271  4544  4544 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-29 10:24:21.271  4544  4544 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 10:24:21.271  4544  4544 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-29 10:24:21.271  4544  4544 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 10:24:21.271  4544  4544 E AndroidRuntime: 	... 10 more
08-29 10:24:21.275   872  4560 E DropBoxManagerService: Can't write: system_app_crash
08-29 10:24:21.275   872  4560 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-29 10:24:21.275   872  4560 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 10:24:21.275   872  4560 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 10:24:21.275   872  4560 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 10:24:21.275   872  4560 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 10:24:21.275   872  4560 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 10:24:21.275   872  4560 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 10:24:21.275   872  4560 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 10:24:21.275   872  4560 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 10:24:21.275   872  4560 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 10:24:21.275   872  4560 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 10:24:21.275   872  4560 E DropBoxManagerService: 	... 5 more
,08-29 10:24:21.280   872  1929 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-29 10:24:21.281  1527  1527 I Process : Sending signal. PID: 1527 SIG: 9
,08-29 10:24:21.284  4544  4544 I Process : Sending signal. PID: 4544 SIG: 9
,08-29 10:24:21.291   872  4561 E DropBoxManagerService: Can't write: system_app_crash
08-29 10:24:21.291   872  4561 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-29 10:24:21.291   872  4561 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 10:24:21.291   872  4561 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 10:24:21.291   872  4561 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 10:24:21.291   872  4561 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 10:24:21.291   872  4561 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 10:24:21.291   872  4561 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 10:24:21.291   872  4561 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 10:24:21.291   872  4561 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 10:24:21.291   872  4561 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 10:24:21.291   872  4561 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 10:24:21.291   872  4561 E DropBoxManagerService: 	... 5 more
08-29 10:24:21.295   281   281 E lowmemorykiller: Error writing /proc/4500/oom_score_adj; errno=22
08-29 10:24:21.299   281   281 E lowmemorykiller: Error writing /proc/4500/oom_score_adj; errno=22
,08-29 10:24:21.306   872   882 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4544) has died
,08-29 10:24:21.307   872   882 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-29 10:24:21.318   872  1304 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,08-29 10:24:21.320   872  1305 D WifiService: Client connection lost with reason: 4
,08-29 10:24:21.322   872   885 I ActivityManager: Start proc 4564:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-29 10:24:21.322   872   883 I ActivityManager: Process com.google.process.gapps (pid 1527) has died
,08-29 10:24:21.323   872   883 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 1000ms
08-29 10:24:21.323   872   883 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
,08-29 10:24:21.323   872   883 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 21000ms
,08-29 10:24:21.323   872   883 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 31000ms
08-29 10:24:21.325  1749  1749 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@89ae413
,08-29 10:24:21.338  1749  1749 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-29 10:24:21.345   872   882 I ActivityManager: Process android.process.acore (pid 4500) has died
,08-29 10:24:21.345   872   882 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 40978ms
,08-29 10:24:21.361   872  1379 I ActivityManager: Start proc 4579:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,08-29 10:24:21.369  1749  1749 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-29 10:24:21.370  1749  1749 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-29 10:24:21.379  1749  1749 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-29 10:24:21.380  1749  1749 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-29 10:24:21.387  1749  4592 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-29 10:24:21.396  4564  4564 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-29 10:24:21.396  4564  4564 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 10:24:21.396  4564  4564 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 10:24:21.396  4564  4564 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 10:24:21.396  4564  4564 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 10:24:21.396  4564  4564 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 10:24:21.396  4564  4564 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 10:24:21.396  4564  4564 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 10:24:21.396  4564  4564 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 10:24:21.396  4564  4564 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 10:24:21.396  4564  4564 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 10:24:21.396  4564  4564 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 10:24:21.396  4564  4564 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 10:24:21.396  4564  4564 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 10:24:21.396  4564  4564 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 10:24:21.396  4564  4564 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-29 10:24:21.396  4564  4564 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-29 10:24:21.396  4564  4564 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 10:24:21.396  4564  4564 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 10:24:21.396  4564  4564 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 10:24:21.396  4564  4564 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 10:24:21.396  4564  4564 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 10:24:21.396  4564  4564 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 10:24:21.396  4564  4564 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 10:24:21.396  4564  4564 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:24:21.396  4564  4564 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 10:24:21.396  4564  4564 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 10:24:21.396  4564  4564 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:24:21.396  4564  4564 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 10:24:21.396  4564  4564 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 10:24:21.397  4564  4564 D AndroidRuntime: Shutting down VM
08-29 10:24:21.398  4579  4579 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-29 10:24:21.406  4564  4564 E AndroidRuntime: FATAL EXCEPTION: main
08-29 10:24:21.406  4564  4564 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4564
08-29 10:24:21.406  4564  4564 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 10:24:21.406  4564  4564 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-29 10:24:21.406  4564  4564 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 10:24:21.406  4564  4564 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 10:24:21.406  4564  4564 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 10:24:21.406  4564  4564 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 10:24:21.406  4564  4564 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:24:21.406  4564  4564 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 10:24:21.406  4564  4564 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 10:24:21.406  4564  4564 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:24:21.406  4564  4564 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 10:24:21.406  4564  4564 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 10:24:21.406  4564  4564 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 10:24:21.406  4564  4564 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 10:24:21.406  4564  4564 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 10:24:21.406  4564  4564 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 10:24:21.406  4564  4564 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 10:24:21.406  4564  4564 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 10:24:21.406  4564  4564 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 10:24:21.406  4564  4564 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 10:24:21.406  4564  4564 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 10:24:21.406  4564  4564 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 10:24:21.406  4564  4564 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 10:24:21.406  4564  4564 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 10:24:21.406  4564  4564 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 10:24:21.406  4564  4564 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
,08-29 10:24:21.406  4564  4564 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-29 10:24:21.406  4564  4564 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-29 10:24:21.406  4564  4564 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 10:24:21.406  4564  4564 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 10:24:21.406  4564  4564 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 10:24:21.406  4564  4564 E AndroidRuntime: 	... 10 more
08-29 10:24:21.407  1749  4592 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
08-29 10:24:21.407  1749  4592 E AndroidRuntime: Process: com.google.android.gms, PID: 1749
08-29 10:24:21.407  1749  4592 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 10:24:21.407  1749  4592 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-29 10:24:21.407  1749  4592 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-29 10:24:21.407  1749  4592 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-29 10:24:21.407  1749  4592 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-29 10:24:21.407  1749  4592 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-29 10:24:21.407  1749  4592 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
08-29 10:24:21.407  1749  4592 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
08-29 10:24:21.407  1749  4592 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
08-29 10:24:21.407  1749  4592 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
08-29 10:24:21.407  1749  4592 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 10:24:21.407  1749  4592 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 10:24:21.407  1749  4592 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
08-29 10:24:21.407  1749  4592 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
08-29 10:24:21.407  1749  4592 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
08-29 10:24:21.407  1749  4592 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
08-29 10:24:21.407  1749  4592 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 10:24:21.407  1749  4592 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 10:24:21.407  1749  4592 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)

```
