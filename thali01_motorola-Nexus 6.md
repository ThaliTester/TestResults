#### Test 82883341775ffd1_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
,08-28 22:39:40.192  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-28 22:39:40.202  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-28 22:39:40.207  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-28 22:39:40.231  1527  1539 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-28 22:39:40.231  1527  1539 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-28 22:39:40.231  1527  1539 I GLSUser : [GLSUser] Extracting token using key: Auth
08-28 22:39:40.231  1527  1539 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-28 22:39:40.245  3506  3506 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-28 22:39:40.246  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-28 22:39:40.246  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-28 22:39:40.804  3769  3769 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-28 22:39:40.809  3769  3769 D AndroidRuntime: CheckJNI is OFF
08-28 22:39:40.853  3769  3769 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-28 22:39:40.903  3769  3769 I Radio-JNI: register_android_hardware_Radio DONE
08-28 22:39:40.925  3769  3769 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-28 22:39:40.931   875  1930 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-28 22:39:40.976  2044  3725 W SearchService: Abort, client detached.
08-28 22:39:40.980  2044  2044 I HotwordDetector: Closing mic
08-28 22:39:40.981  2044  2329 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@6ad6b76
08-28 22:39:40.982  2044  2339 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-28 22:39:40.992  3769  3769 D AndroidRuntime: Shutting down VM
08-28 22:39:41.033   875  1972 I ActivityManager: Start proc 3778:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-28 22:39:41.048   377  2348 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-28 22:39:41.050   377  2348 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-28 22:39:41.059   377  1288 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-28 22:39:41.061  2044  2332 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-28 22:39:41.061  2044  2338 I MicroRecognitionRnrImpl: Detection finished
08-28 22:39:41.126  3778  3778 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-28 22:39:41.157  3778  3778 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-28 22:39:41.170  3778  3778 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 9997-1)
08-28 22:39:41.170  3778  3778 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-28 22:39:41.191  3778  3778 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {20980d8}
08-28 22:39:41.191  3778  3778 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-28 22:39:41.192  3778  3778 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-28 22:39:41.199  3778  3778 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-28 22:39:41.200  3778  3778 E SysUtils: ApplicationContext is null in ApplicationStatus
08-28 22:39:41.222  3778  3778 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-28 22:39:41.232  3778  3778 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-28 22:39:41.232  3778  3778 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-28 22:39:41.232  3778  3778 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-28 22:39:41.232  3778  3778 I Adreno  : Build Date                       : 10/20/15
08-28 22:39:41.232  3778  3778 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-28 22:39:41.232  3778  3778 I Adreno  : Local Branch                     : M14
08-28 22:39:41.232  3778  3778 I Adreno  : Remote Branch                    : 
08-28 22:39:41.232  3778  3778 I Adreno  : Remote Branch                    : 
08-28 22:39:41.232  3778  3778 I Adreno  : Reconstruct Branch               : 
,08-28 22:39:41.295   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c3b8324:true
,08-28 22:39:41.333  3778  3778 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-28 22:39:41.345  3778  3778 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-28 22:39:41.402  3778  3816 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-28 22:39:41.410  3778  3803 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-28 22:39:41.448  3778  3816 I OpenGLRenderer: Initialized EGL, version 1.4
,08-28 22:39:41.471  1874  1874 I Keyboard.Facilitator: onFinishInput()
,08-28 22:39:41.513   875   893 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +520ms
,08-28 22:39:41.540  3778  3778 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3778
,08-28 22:39:41.624  3778  3778 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-28 22:39:41.812  3778  3820 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1699083984
,08-28 22:39:41.818  3778  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-28 22:39:41.818  3778  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-28 22:39:41.818  3778  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-28 22:39:41.818  3778  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-28 22:39:41.818  3778  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-28 22:39:41.818  3778  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57e9f4f added. We now have 1 listener(s)
,08-28 22:39:41.822  3778  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-28 22:39:41.822  3778  3820 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-28 22:39:41.823  3778  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-28 22:39:41.823  3778  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-28 22:39:41.826  3778  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-28 22:39:41.826  3778  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-28 22:39:41.826  3778  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-28 22:39:41.826  3778  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-28 22:39:41.826  3778  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-28 22:39:41.826  3778  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-28 22:39:41.826  3778  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-28 22:39:41.826  3778  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-28 22:39:41.826  3778  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-28 22:39:41.826  3778  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-28 22:39:41.826  3778  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-28 22:39:41.826  3778  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-28 22:39:41.826  3778  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-28 22:39:41.826  3778  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-28 22:39:41.826  3778  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bceba added. We now have 1 listener(s)
08-28 22:39:41.827  3778  3820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-28 22:39:41.833   875  1319 D WifiService: New client listening to asynchronous messages
,08-28 22:39:41.834  3778  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-28 22:39:41.834  3778  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-28 22:39:41.834  3778  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-28 22:39:41.834  3778  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-28 22:39:41.835  3778  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-28 22:39:41.841  3778  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-28 22:39:41.841  3778  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-28 22:39:41.851  3778  3820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-28 22:39:41.852  3778  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-28 22:39:41.852  3778  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:39:41.852  3778  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:39:41.852  3778  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 22:39:41.852  3778  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 22:39:41.852  3778  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-28 22:39:41.852  3778  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-28 22:39:41.852  3778  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-28 22:39:41.852  3778  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-28 22:39:41.852  3778  3820 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-28 22:39:41.852  3778  3820 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-28 22:39:41.854  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 22:39:41.855  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 22:39:41.878  3778  3778 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-28 22:39:41.904   875  1722 I ActivityManager: Killing 2976:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-28 22:39:41.930   875  1722 I ActivityManager: Killing 3191:com.google.android.gm/u0a78 (adj 15): empty #18
,08-28 22:39:42.708  3778  3828 W jxcore-log: Initializing JXcore engine
,08-28 22:39:42.708  3778  3828 W jxcore-log: JXcore engine is ready
,08-28 22:39:42.748  3828  3828 W Thread-321: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8981 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-28 22:39:42.748  3828  3828 W Thread-321: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9614]" dev="sockfs" ino=9614 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-28 22:39:42.748  3828  3828 W Thread-321: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-28 22:39:42.748  3828  3828 W Thread-321: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[26229]" dev="sockfs" ino=26229 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-28 22:39:42.769  3778  3828 W jxcore-log: Starting JXcore engine
,08-28 22:39:42.854  3778  3828 W jxcore-log: Platform android
08-28 22:39:42.854  3778  3828 W jxcore-log: 
,08-28 22:39:42.854  3778  3828 W jxcore-log: Process ARCH arm
08-28 22:39:42.854  3778  3828 W jxcore-log: 
,08-28 22:39:43.075  3778  3828 I jxcore-log: JXcore Cordova bridge is ready!
08-28 22:39:43.075  3778  3828 I jxcore-log: 
,08-28 22:39:43.077  3778  3828 W jxcore-log: JXcore engine is started
,08-28 22:39:43.087  3778  3820 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-28 22:39:43.092  3778  3778 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-28 22:39:43.118   875  1318 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-28 22:39:48.516  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 22:39:48.518  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 22:39:48.539  1527  2295 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-28 22:39:48.539  1527  2295 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-28 22:39:48.539  1527  2295 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-28 22:39:48.540  1527  2295 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 22:39:48.554  2992  3836 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-28 22:39:48.554  2992  3836 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-28 22:39:48.554  2992  3836 E HttpOperation: 	at jdm.a(PG:82)
08-28 22:39:48.554  2992  3836 E HttpOperation: 	at jcs.o(PG:406)
08-28 22:39:48.554  2992  3836 E HttpOperation: 	at jcn.a(PG:1379)
08-28 22:39:48.554  2992  3836 E HttpOperation: 	at jcs.i(PG:143)
08-28 22:39:48.554  2992  3836 E HttpOperation: 	at blb.a(PG:3937)
08-28 22:39:48.554  2992  3836 E HttpOperation: 	at czp.a(PG:18188)
08-28 22:39:48.554  2992  3836 E HttpOperation: 	at czp.a(PG:9081)
08-28 22:39:48.554  2992  3836 E HttpOperation: 	at czq.run(PG:1686)
08-28 22:39:48.554  2992  3836 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-28 22:39:48.554  2992  3836 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-28 22:39:48.554  2992  3836 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-28 22:39:48.554  2992  3836 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-28 22:39:48.554  2992  3836 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-28 22:39:48.554  2992  3836 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-28 22:39:48.554  2992  3836 E HttpOperation: 	at jdj.a(PG:4091)
08-28 22:39:48.554  2992  3836 E HttpOperation: 	at jdj.a(PG:1125)
08-28 22:39:48.554  2992  3836 E HttpOperation: 	at jdm.a(PG:77)
08-28 22:39:48.554  2992  3836 E HttpOperation: 	... 12 more
08-28 22:39:48.554  2992  3836 E HttpOperation: Caused by: faj: BadAuthentication
08-28 22:39:48.554  2992  3836 E HttpOperation: 	at fal.a(PG:38)
08-28 22:39:48.554  2992  3836 E HttpOperation: 	at jdj.a(PG:4089)
08-28 22:39:48.554  2992  3836 E HttpOperation: 	... 14 more
,08-28 22:39:48.597  1527  2296 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-28 22:39:48.598  1527  2296 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-28 22:39:48.599  1527  2296 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-28 22:39:48.600  1527  2296 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 22:39:48.618  2992  3836 E HttpOperation: [getmobileexperiments] Unexpected exception
08-28 22:39:48.618  2992  3836 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-28 22:39:48.618  2992  3836 E HttpOperation: 	at jdm.a(PG:82)
08-28 22:39:48.618  2992  3836 E HttpOperation: 	at jcs.o(PG:406)
08-28 22:39:48.618  2992  3836 E HttpOperation: 	at jcn.a(PG:1379)
08-28 22:39:48.618  2992  3836 E HttpOperation: 	at jcs.i(PG:143)
08-28 22:39:48.618  2992  3836 E HttpOperation: 	at hec.a(PG:42)
08-28 22:39:48.618  2992  3836 E HttpOperation: 	at hee.a(PG:102)
08-28 22:39:48.618  2992  3836 E HttpOperation: 	at czr.a(PG:65)
08-28 22:39:48.618  2992  3836 E HttpOperation: 	at kka.a(PG:108)
08-28 22:39:48.618  2992  3836 E HttpOperation: 	at czp.a(PG:19176)
08-28 22:39:48.618  2992  3836 E HttpOperation: 	at czp.a(PG:9081)
08-28 22:39:48.618  2992  3836 E HttpOperation: 	at czq.run(PG:1686)
08-28 22:39:48.618  2992  3836 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-28 22:39:48.618  2992  3836 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-28 22:39:48.618  2992  3836 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-28 22:39:48.618  2992  3836 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-28 22:39:48.618  2992  3836 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-28 22:39:48.618  2992  3836 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-28 22:39:48.618  2992  3836 E HttpOperation: 	at jdj.a(PG:4091)
08-28 22:39:48.618  2992  3836 E HttpOperation: 	at jdj.a(PG:1125)
08-28 22:39:48.618  2992  3836 E HttpOperation: 	at jdm.a(PG:77)
08-28 22:39:48.618  2992  3836 E HttpOperation: 	... 15 more
08-28 22:39:48.618  2992  3836 E HttpOperation: Caused by: faj: BadAuthentication
08-28 22:39:48.618  2992  3836 E HttpOperation: 	at fal.a(PG:38)
08-28 22:39:48.618  2992  3836 E HttpOperation: 	at jdj.a(PG:4089)
08-28 22:39:48.618  2992  3836 E HttpOperation: 	... 17 more
,08-28 22:39:48.619  2992  3836 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-28 22:39:48.619  2992  3836 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-28 22:39:48.619  2992  3836 E ExperimentLoader: 	at jdm.a(PG:82)
08-28 22:39:48.619  2992  3836 E ExperimentLoader: 	at jcs.o(PG:406)
08-28 22:39:48.619  2992  3836 E ExperimentLoader: 	at jcn.a(PG:1379)
08-28 22:39:48.619  2992  3836 E ExperimentLoader: 	at jcs.i(PG:143)
08-28 22:39:48.619  2992  3836 E ExperimentLoader: 	at hec.a(PG:42)
08-28 22:39:48.619  2992  3836 E ExperimentLoader: 	at hee.a(PG:102)
08-28 22:39:48.619  2992  3836 E ExperimentLoader: 	at czr.a(PG:65)
08-28 22:39:48.619  2992  3836 E ExperimentLoader: 	at kka.a(PG:108)
08-28 22:39:48.619  2992  3836 E ExperimentLoader: 	at czp.a(PG:19176)
08-28 22:39:48.619  2992  3836 E ExperimentLoader: 	at czp.a(PG:9081)
08-28 22:39:48.619  2992  3836 E ExperimentLoader: 	at czq.run(PG:1686)
08-28 22:39:48.619  2992  3836 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-28 22:39:48.619  2992  3836 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-28 22:39:48.619  2992  3836 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-28 22:39:48.619  2992  3836 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-28 22:39:48.619  2992  3836 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-28 22:39:48.619  2992  3836 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-28 22:39:48.619  2992  3836 E ExperimentLoader: 	at jdj.a(PG:4091)
08-28 22:39:48.619  2992  3836 E ExperimentLoader: 	at jdj.a(PG:1125)
08-28 22:39:48.619  2992  3836 E ExperimentLoader: 	at jdm.a(PG:77)
08-28 22:39:48.619  2992  3836 E ExperimentLoader: 	... 15 more
08-28 22:39:48.619  2992  3836 E ExperimentLoader: Caused by: faj: BadAuthentication
08-28 22:39:48.619  2992  3836 E ExperimentLoader: 	at fal.a(PG:38)
08-28 22:39:48.619  2992  3836 E ExperimentLoader: 	at jdj.a(PG:4089)
08-28 22:39:48.619  2992  3836 E ExperimentLoader: 	... 17 more
,08-28 22:39:48.736   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 127092, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-28 22:39:48.824   875  1320 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-28 22:39:51.856   875  1320 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-28 22:39:53.036  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-28 22:39:53.036  3778  3828 I jxcore-log: 
,08-28 22:39:53.039  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-28 22:39:53.039  3778  3828 I jxcore-log: 
,08-28 22:39:53.049  3778  3828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-28 22:39:53.049  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:39:53.049  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:39:53.049  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 22:39:53.049  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 22:39:53.049  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-28 22:39:53.049  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-28 22:39:53.049  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-28 22:39:53.052  3778  3828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-28 22:39:53.055  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-28 22:39:53.055  3778  3828 I jxcore-log: 
,08-28 22:39:53.057  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-28 22:39:53.057  3778  3828 I jxcore-log: 
,08-28 22:39:53.553  3778  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-28 22:39:53.553  3778  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@978d305 added. We now have 2 listener(s)
,08-28 22:39:53.554  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-28 22:39:53.554  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-28 22:39:53.554  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-28 22:39:53.554  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-28 22:39:53.554  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39b8f5a added. We now have 2 listener(s)
08-28 22:39:53.554  3778  3828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-28 22:39:53.555  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-28 22:39:53.558  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-28 22:39:53.565  3778  3828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-28 22:39:53.565  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:39:53.565  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:39:53.565  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 22:39:53.565  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 22:39:53.565  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-28 22:39:53.565  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-28 22:39:53.565  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-28 22:39:53.568  3778  3828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-28 22:39:53.568  3778  3828 D io.jxcore.node.ConnectivityMonitor: start: OK
08-28 22:39:53.568  3778  3828 D ExecuteNativeTests: Running unit tests
,08-28 22:39:53.575  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 22:39:53.581  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 22:39:53.628  3778  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-28 22:39:53.628  3778  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fcfd998 added. We now have 3 listener(s)
,08-28 22:39:53.629  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-28 22:39:53.629  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-28 22:39:53.629  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-28 22:39:53.629  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-28 22:39:53.629  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 added. We now have 3 listener(s)
08-28 22:39:53.629  3778  3828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-28 22:39:53.630  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-28 22:39:53.632  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-28 22:39:53.640  3778  3828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-28 22:39:53.640  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:39:53.640  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:39:53.640  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 22:39:53.640  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 22:39:53.640  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-28 22:39:53.640  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-28 22:39:53.640  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-28 22:39:53.641  3778  3828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-28 22:39:53.641  3778  3828 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-28 22:39:53.643  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-28 22:39:53.643  3778  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-28 22:39:53.643  3778  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
08-28 22:39:53.643  3778  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-28 22:39:53.644  3778  3828 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-28 22:39:53.644  3778  3828 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-28 22:39:53.644  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-28 22:39:53.645  3778  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-28 22:39:53.645  3778  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-28 22:39:53.645  3778  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-28 22:39:53.645  3778  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-28 22:39:53.645  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-28 22:39:53.646  3778  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-28 22:39:53.646  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 22:39:53.646  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:39:53.646  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-28 22:39:53.646  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-28 22:39:53.646  3778  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fcfd998 removed from the list
08-28 22:39:53.646  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:39:53.646  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 removed from the list
08-28 22:39:53.647  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 22:39:53.648  3778  3828 D io.jxcore.node.ConnectivityMonitor: stop
08-28 22:39:53.648  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:39:53.648  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:39:53.648  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:39:53.652  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 22:39:53.652  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-28 22:39:53.652  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:39:53.652  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
08-28 22:39:53.654  3778  3828 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-28 22:39:53.654  3778  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killin,g connections
08-28 22:39:53.654  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-28 22:39:53.654  3778  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-28 22:39:53.655  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 22:39:53.655  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:39:53.655  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:39:53.655  3778  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fcfd998 not in the list
08-28 22:39:53.655  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:39:53.655  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
08-28 22:39:53.665  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 22:39:53.665  3778  3828 D io.jxcore.node.ConnectivityMonitor: stop
08-28 22:39:53.665  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:39:53.665  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:39:53.665  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:39:53.665  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:39:53.667  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 22:39:53.667  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-28 22:39:53.667  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:39:53.667  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
08-28 22:39:53.672  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-28 22:39:53.672  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-28 22:39:53.672  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-28 22:39:53.672  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-28 22:39:53.672  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-28 22:39:53.672  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-28 22:39:53.672  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-28 22:39:53.672  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-28 22:39:53.672  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-28 22:39:53.672  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-28 22:39:53.672  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-28 22:39:53.672  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-28 22:39:53.672  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-28 22:39:53.672  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-28 22:39:53.673  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-28 22:39:53.673  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-28 22:39:53.673  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-28 22:39:53.673  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-28 22:39:53.673  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-28 22:39:53.673  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-28 22:39:53.673  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-28 22:39:53.673  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-28 22:39:53.673  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-28 22:39:53.673  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-28 22:39:53.673  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-28 22:39:53.673  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-28 22:39:53.673  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-28 22:39:53.673  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-28 22:39:53.673  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-28 22:39:53.673  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-28 22:39:53.673  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-28 22:39:53.673  3778  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-28 22:39:53.673  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-28 22:39:53.674  3778  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-28 22:39:53.674  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 22:39:53.674  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:39:53.674  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:39:53.674  3778  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fcfd998 not in the list
08-28 22:39:53.674  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:39:53.674  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
08-28 22:39:53.674  3778  3828 D io.jxcore.node.ConnectivityMonitor: stop
08-28 22:39:53.674  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:39:53.674  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:39:53.674  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:39:53.674  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:39:53.675  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 22:39:53.675  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-28 22:39:53.675  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:39:53.675  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
08-28 22:39:53.676  3778  3828 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-28 22:39:53.677  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-28 22:39:53.680  3778  3828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-28 22:39:53.680  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:39:53.680  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:39:53.680  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 22:39:53.680  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 22:39:53.680  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-28 22:39:53.680  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-28 22:39:53.680  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-28 22:39:53.682  3778  3828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-28 22:39:53.682  3778  3828 D io.jxcore.node.ConnectivityMonitor: start: OK
08-28 22:39:53.682  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-28 22:39:53.682  3778  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-28 22:39:53.682  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-28 22:39:53.682  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-28 22:39:53.683  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-28 22:39:53.684  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 22:39:53.685  3778  3828 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-28 22:39:53.685  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-28 22:39:53.687  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 22:39:53.690  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-28 22:39:53.692  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-28 22:39:53.692  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-28 22:39:53.694  3778  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-28 22:39:53.696  3778  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-28 22:39:53.696  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-28 22:39:53.696  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-28 22:39:53.697  3778  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-28 22:39:53.697  3778  3828 D BluetoothAdapter: STATE_ON
,08-28 22:39:53.701  2682  2693 D BtGatt.GattService: registerClient() - UUID=38df3a7c-9a13-47fa-9431-3ec8655fd673
08-28 22:39:53.701  2682  2704 D BtGatt.GattService: onClientRegistered() - UUID=38df3a7c-9a13-47fa-9431-3ec8655fd673, clientIf=5
08-28 22:39:53.702  3778  3789 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-28 22:39:53.703  2682  2696 D BtGatt.GattService: start scan with filters
08-28 22:39:53.706  2682  2709 D BtGatt.ScanManager: handling starting scan
08-28 22:39:53.706  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-28 22:39:53.707  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-28 22:39:53.707  2682  2709 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c6d6a2
08-28 22:39:53.707  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-28 22:39:53.707  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-28 22:39:53.709  3778  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-28 22:39:53.709  3778  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-28 22:39:53.709  3778  3778 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-28 22:39:53.710  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-28 22:39:53.712  3778  3828 I io.jxcore.node.ConnectionHelper: start: OK
08-28 22:39:53.714  2682  2704 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-28 22:39:53.714  2682  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-28 22:39:53.715  2682  2709 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-28 22:39:53.723  2682  2704 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-28 22:39:53.723  2682  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-28 22:39:53.724  2682  2709 D BtGatt.ScanManager: Starting BLE batch scan
08-28 22:39:53.724  2682  2709 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-28 22:39:53.741  2682  2704 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-28 22:39:53.741  2682  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 22:39:53.751  2682  2704 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-28 22:39:53.751  2682  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 22:39:54.211  3778  3778 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-28 22:39:54.212  3778  3778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-28 22:39:54.212  3778  3778 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-28 22:39:54.899   875  1320 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-28 22:39:55.257  2682  2682 D BtGatt.ScanManager: awakened up at time 134088
,08-28 22:39:55.261  2682  2709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-28 22:39:55.318  2682  2704 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-28 22:39:55.318  2682  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 22:39:55.319  2682  2704 D BtGatt.GattService: current time is 134150532226
,08-28 22:39:55.320  2682  2704 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -87, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -81, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -90, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -81, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -83, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -86, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-28 22:39:55.323  2682  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-28 22:39:55.326  2682  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-28 22:39:55.326  2682  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
08-28 22:39:55.326  2682  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-28 22:39:55.326  2682  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-28 22:39:55.327  2682  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-28 22:39:56.821  2682  2682 D BtGatt.ScanManager: awakened up at time 135652
,08-28 22:39:56.827  2682  2709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-28 22:39:56.858  2682  2704 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,08-28 22:39:56.858  2682  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 22:39:56.859  2682  2704 D BtGatt.GattService: current time is 135690629097,
,08-28 22:39:56.860  2682  2704 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -94, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -81, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -85, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -83, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-28 22:39:56.861  2682  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-28 22:39:56.862  2682  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-28 22:39:56.863  2682  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,08-28 22:39:56.864  2682  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-28 22:39:57.931   875  1320 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-28 22:39:58.361  2682  2682 D BtGatt.ScanManager: awakened up at time 137193
,08-28 22:39:58.368  2682  2709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-28 22:39:58.396  2682  2704 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,08-28 22:39:58.396  2682  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 22:39:58.396  2682  2704 D BtGatt.GattService: current time is 137228267428
,08-28 22:39:58.397  2682  2704 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -83, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -92, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-28 22:39:58.398  2682  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,08-28 22:39:58.399  2682  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-28 22:39:58.722  3778  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-28 22:39:58.722  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-28 22:39:58.723  3778  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-28 22:39:58.723  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:39:58.723  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-28 22:39:58.724  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-28 22:39:58.724  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-28 22:39:58.724  3778  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-28 22:39:58.724  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-28 22:39:58.726  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-28 22:39:58.727  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-28 22:39:58.729  3778  3828 D BluetoothAdapter: STATE_ON
,08-28 22:39:58.731  2682  2693 D BtGatt.GattService: stopScan() - queue size =1
,08-28 22:39:58.733  2682  2696 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-28 22:39:58.734  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-28 22:39:58.735  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-28 22:39:58.738  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-28 22:39:58.739  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-28 22:39:58.739  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-28 22:39:58.743  3778  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-28 22:39:58.744  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-28 22:39:58.745  3778  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-28 22:39:58.746  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-28 22:39:58.748  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-28 22:39:58.751  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-28 22:39:58.751  3778  3778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-28 22:39:58.751  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:39:58.752  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-28 22:39:58.752  3778  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fcfd998 not in the list
08-28 22:39:58.752  3778  3778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-28 22:39:58.753  3778  3778 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-28 22:39:58.753  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-28 22:39:58.753  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
08-28 22:39:58.753  3778  3828 D io.jxcore.node.ConnectivityMonitor: stop
08-28 22:39:58.753  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:39:58.756  2682  2704 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-28 22:39:58.756  2682  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 22:39:58.757  2682  2709 D BtGatt.ScanManager: stopping BLe Batch
,08-28 22:39:58.765   875  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=137596, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-28 22:39:58.772  2682  2704 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-28 22:39:58.772  2682  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 22:39:58.773  2682  2709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-28 22:39:58.785  2682  2704 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-28 22:39:58.785  2682  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 22:39:59.254  3778  3778 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-28 22:40:00.511  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 22:40:00.522  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 22:40:00.524  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,08-28 22:40:00.576  1527  2295 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-28 22:40:00.576  1527  2295 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-28 22:40:00.576  1527  2295 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-28 22:40:00.577  1527  2295 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 22:40:00.612  3506  3506 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-28 22:40:00.612  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-28 22:40:00.613  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-28 22:40:00.965   875  1320 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-28 22:40:03.756  3778  3828 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-28 22:40:03.763  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-28 22:40:03.773  3778  3828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-28 22:40:03.773  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:40:03.773  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:40:03.773  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 22:40:03.773  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 22:40:03.773  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-28 22:40:03.773  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-28 22:40:03.773  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-28 22:40:03.775  3778  3828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-28 22:40:03.775  3778  3828 D io.jxcore.node.ConnectivityMonitor: start: OK
08-28 22:40:03.777  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-28 22:40:03.777  3778  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-28 22:40:03.777  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-28 22:40:03.777  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-28 22:40:03.777  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-28 22:40:03.780  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 22:40:03.782  3778  3828 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-28 22:40:03.783  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-28 22:40:03.787  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-28 22:40:03.787  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 22:40:03.788  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-28 22:40:03.788  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-28 22:40:03.793  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-28 22:40:03.793  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-28 22:40:03.794  3778  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-28 22:40:03.794  3778  3828 D BluetoothAdapter: STATE_ON
,08-28 22:40:03.799  2682  2693 D BtGatt.GattService: registerClient() - UUID=945bb60b-fe50-41cd-8cd8-edc00fc816ea
08-28 22:40:03.800  2682  2704 D BtGatt.GattService: onClientRegistered() - UUID=945bb60b-fe50-41cd-8cd8-edc00fc816ea, clientIf=5
,08-28 22:40:03.800  3778  3790 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-28 22:40:03.800  2682  2849 D BtGatt.GattService: start scan with filters
,08-28 22:40:03.805  2682  2709 D BtGatt.ScanManager: handling starting scan
,08-28 22:40:03.805  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-28 22:40:03.805  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-28 22:40:03.806  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-28 22:40:03.806  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-28 22:40:03.810  3778  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-28 22:40:03.810  3778  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-28 22:40:03.810  3778  3778 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-28 22:40:03.812  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-28 22:40:03.815  2682  2704 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-28 22:40:03.815  2682  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-28 22:40:03.816  2682  2709 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-28 22:40:03.816  3778  3828 I io.jxcore.node.ConnectionHelper: start: OK
,08-28 22:40:03.829  3778  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-28 22:40:03.829  3778  3828 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-28 22:40:03.830  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-28 22:40:03.830  3778  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-28 22:40:03.830  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:03.830  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-28 22:40:03.830  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-28 22:40:03.830  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-28 22:40:03.830  3778  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-28 22:40:03.830  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-28 22:40:03.831  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-28 22:40:03.831  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-28 22:40:03.831  3778  3828 D BluetoothAdapter: STATE_ON
,08-28 22:40:03.832  2682  2693 D BtGatt.GattService: stopScan() - queue size =1
08-28 22:40:03.833  2682  2704 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-28 22:40:03.833  2682  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-28 22:40:03.834  2682  2709 D BtGatt.ScanManager: Starting BLE batch scan
08-28 22:40:03.834  2682  2709 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-28 22:40:03.834  2682  2696 D BtGatt.GattService: unregisterClient() - clientIf=5
08-28 22:40:03.835  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-28 22:40:03.835  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-28 22:40:03.835  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-28 22:40:03.835  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-28 22:40:03.836  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-28 22:40:03.837  3778  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-28 22:40:03.837  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-28 22:40:03.837  3778  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-28 22:40:03.838  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-28 22:40:03.839  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-28 22:40:03.841  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 22:40:03.841  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:03.841  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-28 22:40:03.841  3778  3778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-28 22:40:03.841  3778  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fcfd998 not in the list
08-28 22:40:03.841  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:40:03.841  3778  3778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-28 22:40:03.842  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
08-28 22:40:03.842  3778  3778 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-28 22:40:03.842  3778  3828 D io.jxcore.node.ConnectivityMonitor: stop
08-28 22:40:03.842  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:03.842  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:03.842  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:03.843  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 22:40:03.843  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-28 22:40:03.843  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:40:03.843  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
08-28 22:40:03.844  3778  3828 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-28 22:40:03.846  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-28 22:40:03.851  3778  3828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-28 22:40:03.851  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:40:03.851  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:40:03.851  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 22:40:03.851  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 22:40:03.851  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-28 22:40:03.851  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-28 22:40:03.851  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-28 22:40:03.854  2682  2704 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-28 22:40:03.854  2682  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-28 22:40:03.856  3778  3828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-28 22:40:03.856  3778  3828 D io.jxcore.node.ConnectivityMonitor: start: OK
08-28 22:40:03.857  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-28 22:40:03.857  3778  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-28 22:40:03.857  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-28 22:40:03.857  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-28 22:40:03.857  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-28 22:40:03.859  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 22:40:03.861  2682  2704 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-28 22:40:03.861  2682  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-28 22:40:03.865  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 22:40:03.864  3778  3828 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-28 22:40:03.866  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-28 22:40:03.869  2682  2704 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-28 22:40:03.869  2682  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-28 22:40:03.869  2682  2709 D BtGatt.ScanManager: stopping BLe Batch
,08-28 22:40:03.878  2682  2704 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-28 22:40:03.878  2682  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-28 22:40:03.878  2682  2709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-28 22:40:03.878  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-28 22:40:03.881  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-28 22:40:03.881  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-28 22:40:03.887  2682  2704 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-28 22:40:03.887  2682  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 22:40:03.889  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-28 22:40:03.889  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-28 22:40:03.889  3778  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-28 22:40:03.889  3778  3828 D BluetoothAdapter: STATE_ON
,08-28 22:40:03.891  2682  2849 D BtGatt.GattService: registerClient() - UUID=30b9c233-0796-45ba-ba16-df657ff3d39c
08-28 22:40:03.891  2682  2704 D BtGatt.GattService: onClientRegistered() - UUID=30b9c233-0796-45ba-ba16-df657ff3d39c, clientIf=5
08-28 22:40:03.891  3778  3789 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-28 22:40:03.892  2682  2696 D BtGatt.GattService: start scan with filters
,08-28 22:40:03.894  2682  2709 D BtGatt.ScanManager: handling starting scan
,08-28 22:40:03.894  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-28 22:40:03.894  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-28 22:40:03.894  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-28 22:40:03.894  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-28 22:40:03.896  3778  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-28 22:40:03.896  3778  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-28 22:40:03.896  3778  3778 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-28 22:40:03.897  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-28 22:40:03.899  2682  2704 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-28 22:40:03.899  2682  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 22:40:03.899  3778  3828 I io.jxcore.node.ConnectionHelper: start: OK
08-28 22:40:03.899  2682  2709 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-28 22:40:03.904  2682  2704 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-28 22:40:03.904  2682  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-28 22:40:03.904  2682  2709 D BtGatt.ScanManager: Starting BLE batch scan
08-28 22:40:03.904  2682  2709 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-28 22:40:03.913  2682  2704 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-28 22:40:03.913  2682  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 22:40:03.918  2682  2704 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-28 22:40:03.918  2682  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 22:40:04.397  3778  3778 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-28 22:40:04.398  3778  3778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-28 22:40:04.398  3778  3778 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-28 22:40:05.426  2682  2682 D BtGatt.ScanManager: awakened up at time 144257
,08-28 22:40:05.428  2682  2709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-28 22:40:05.465  2682  2704 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-28 22:40:05.465  2682  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 22:40:05.465  2682  2704 D BtGatt.GattService: current time is 144296990997
,08-28 22:40:05.465  2682  2704 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -82, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -65, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -86, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -82, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -90, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-28 22:40:05.466  2682  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-28 22:40:05.466  2682  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-28 22:40:05.466  2682  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-28 22:40:05.467  2682  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-28 22:40:05.467  2682  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-28 22:40:06.972  2682  2682 D BtGatt.ScanManager: awakened up at time 145803
08-28 22:40:06.974  2682  2709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-28 22:40:07.005  2682  2704 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
08-28 22:40:07.005  2682  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 22:40:07.004   875  1320 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-28 22:40:07.020  2682  2704 D BtGatt.GattService: current time is 145851349329
,08-28 22:40:07.020  2682  2704 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -87, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -84, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -95, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -66, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0]
08-28 22:40:07.021  2682  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-28 22:40:07.022  2682  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-28 22:40:07.022  2682  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-28 22:40:07.023  2682  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,08-28 22:40:08.508  2682  2682 D BtGatt.ScanManager: awakened up at time 147339
,08-28 22:40:08.511  2682  2709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-28 22:40:08.554  2682  2704 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
08-28 22:40:08.554  2682  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-28 22:40:08.555  2682  2704 D BtGatt.GattService: current time is 147386355367
,08-28 22:40:08.556  2682  2704 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -83, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -84, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -92, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -81, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-28 22:40:08.556  2682  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-28 22:40:08.557  2682  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-28 22:40:08.558  2682  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-28 22:40:08.559  2682  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-28 22:40:08.900  3778  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-28 22:40:08.900  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-28 22:40:08.900  3778  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-28 22:40:08.901  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:08.901  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-28 22:40:08.901  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-28 22:40:08.903  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-28 22:40:08.903  3778  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-28 22:40:08.903  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-28 22:40:08.904  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-28 22:40:08.904  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-28 22:40:08.909  3778  3828 D BluetoothAdapter: STATE_ON
,08-28 22:40:08.911  2682  2849 D BtGatt.GattService: stopScan() - queue size =1
,08-28 22:40:08.918  2682  2693 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-28 22:40:08.919  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-28 22:40:08.920  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-28 22:40:08.920  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-28 22:40:08.921  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-28 22:40:08.921  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-28 22:40:08.925  3778  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-28 22:40:08.927  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-28 22:40:08.927  3778  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-28 22:40:08.927  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-28 22:40:08.930  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-28 22:40:08.934  3778  3778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-28 22:40:08.935  3778  3778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-28 22:40:08.935  3778  3778 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-28 22:40:08.940  2682  2704 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-28 22:40:08.940  2682  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-28 22:40:08.941  2682  2709 D BtGatt.ScanManager: stopping BLe Batch
,08-28 22:40:08.953  2682  2704 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-28 22:40:08.953  2682  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-28 22:40:08.953  2682  2709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-28 22:40:08.962  2682  2704 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-28 22:40:08.962  2682  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 22:40:09.437  3778  3778 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-28 22:40:09.437  3778  3778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-28 22:40:09.437  3778  3778 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-28 22:40:10.044   875  1320 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-28 22:40:11.187   875   895 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-28 22:40:11.194  1874  1874 I Keyboard.Facilitator: onFinishInput()
,08-28 22:40:11.209   875   895 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-28 22:40:11.209   875   895 I Adreno  : Build Date                       : 10/20/15
08-28 22:40:11.209   875   895 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-28 22:40:11.209   875   895 I Adreno  : Local Branch                     : M14
08-28 22:40:11.209   875   895 I Adreno  : Remote Branch                    : 
08-28 22:40:11.209   875   895 I Adreno  : Remote Branch                    : 
08-28 22:40:11.209   875   895 I Adreno  : Reconstruct Branch               : 
,08-28 22:40:11.247   283   365 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (188 us)
,08-28 22:40:11.860  3778  3778 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-28 22:40:11.860  3778  3778 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-28 22:40:11.911   875   895 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-28 22:40:11.912  3778  3778 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@4dfbaee Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@86cc56b, 16908290=android.view.AbsSavedState$1@86cc56b}, android:focusedViewId=100}]}]
08-28 22:40:11.912  3778  3778 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-28 22:40:11.913  3778  3778 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-28 22:40:11.913  3778  3778 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-28 22:40:11.920   875   895 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-28 22:40:11.925   875   893 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-28 22:40:11.926   283   283 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
08-28 22:40:11.927   283   283 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-28 22:40:12.225   283   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-28 22:40:12.228   283   283 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-28 22:40:12.234   875  1342 D SurfaceControl: Excessive delay in setPowerMode(): 309ms
,08-28 22:40:12.238   875   895 I DreamManagerService: Entering dreamland.
,08-28 22:40:12.240   875   895 I PowerManagerService: Dozing...
,08-28 22:40:12.241   875   890 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-28 22:40:12.324   377   377 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-28 22:40:12.325   377   377 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-28 22:40:12.340   875  1318 D WifiConfigStore: Retrieve network priorities after PNO.
,08-28 22:40:12.357   875  1320 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-28 22:40:12.365  1929  3848 D NfcService: Discovery configuration equal, not updating.
,08-28 22:40:12.370   875  1318 E native  : do suspend false
,08-28 22:40:12.391   875  1318 D WifiConfigStore: No blacklist allowed without epno enabled
,08-28 22:40:12.409   875  1318 D WifiConfigStore: Retrieve network priorities after PNO.
,08-28 22:40:12.412   875  1318 E native  : do suspend true
,08-28 22:40:12.451   377  1289 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-28 22:40:12.451   377  1289 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-28 22:40:12.847   875  1318 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,08-28 22:40:13.937  3778  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-28 22:40:13.937  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-28 22:40:13.938  3778  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-28 22:40:13.938  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 22:40:13.939  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-28 22:40:13.939  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-28 22:40:13.940  3778  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fcfd998 not in the list
08-28 22:40:13.940  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-28 22:40:13.940  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
08-28 22:40:13.941  3778  3828 D io.jxcore.node.ConnectivityMonitor: stop
,08-28 22:40:13.941  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:13.943  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:13.943  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 22:40:13.946  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-28 22:40:13.947  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-28 22:40:13.947  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:40:13.947  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
,08-28 22:40:13.950  3778  3828 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-28 22:40:13.952  3778  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-28 22:40:13.952  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-28 22:40:13.952  3778  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-28 22:40:13.953  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-28 22:40:13.954  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:13.954  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 22:40:13.955  3778  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fcfd998 not in the list
,08-28 22:40:13.955  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:40:13.955  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
08-28 22:40:13.956  3778  3828 D io.jxcore.node.ConnectivityMonitor: stop
,08-28 22:40:13.956  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:13.956  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:13.956  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-28 22:40:13.957  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:13.958  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-28 22:40:13.958  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-28 22:40:13.958  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:40:13.958  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
,08-28 22:40:13.960  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-28 22:40:13.960  3778  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-28 22:40:13.960  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-28 22:40:13.960  3778  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-28 22:40:13.960  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 22:40:13.960  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:13.960  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:13.960  3778  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fcfd998 not in the list
08-28 22:40:13.961  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:40:13.961  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
08-28 22:40:13.961  3778  3828 D io.jxcore.node.ConnectivityMonitor: stop
08-28 22:40:13.961  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:13.961  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:13.961  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:13.961  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:13.962  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 22:40:13.962  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-28 22:40:13.962  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:40:13.962  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
08-28 22:40:13.963  3778  3828 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-28 22:40:13.963  3778  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-28 22:40:13.963  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-28 22:40:13.963  3778  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-28 22:40:13.964  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 22:40:13.964  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:13.964  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:13.964  3778  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fcfd998 not in the list
08-28 22:40:13.964  3778  38,28 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:40:13.964  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
08-28 22:40:13.964  3778  3828 D io.jxcore.node.ConnectivityMonitor: stop
08-28 22:40:13.964  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:13.964  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:13.964  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:13.964  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:13.966  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 22:40:13.966  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-28 22:40:13.966  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:40:13.966  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
08-28 22:40:13.967  3778  3828 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-28 22:40:13.967  3778  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-28 22:40:13.967  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-28 22:40:13.967  3778  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-28 22:40:13.968  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 22:40:13.968  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:13.968  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:13.968  3778  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fcfd998 not in the list
08-28 22:40:13.968  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:40:13.968  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
08-28 22:40:13.968  3778  3828 D io.jxcore.node.ConnectivityMonitor: stop
08-28 22:40:13.968  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:13.968  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:13.968  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:13.969  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:13.970  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 22:40:13.970  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-28 22:40:13.970  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:40:13.970  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
08-28 22:40:13.971  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-28 22:40:13.971  3778  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-28 22:40:13.971  3778  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-28 22:40:13.971  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-28 22:40:13.971  3778  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-28 22:40:13.971  3778  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-28 22:40:13.971  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-28 22:40:13.971  3778  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-28 22:40:13.971  3778  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-28 22:40:13.972  3778  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-28 22:40:13.972  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-28 22:40:13.972  3778  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-28 22:40:13.972  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 22:40:13.972  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:13.972  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:13.972  3778  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fcfd998 not in the list
08-28 22:40:13.972  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:40:13.973  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
08-28 22:40:13.973  3778  3828 D io.jxcore.node.ConnectivityMonitor: stop
08-28 22:40:13.973  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:13.973  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:13.973  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:13.973  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:13.974  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 22:40:13.975  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-28 22:40:13.975  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:40:13.975  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
08-28 22:40:13.976  3778  3828 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-28 22:40:13.976  3778  3828 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-28 22:40:13.976  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-28 22:40:13.980  3778  3828 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-28 22:40:13.980  3778  3828 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,08-28 22:40:13.980  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-28 22:40:13.980  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-28 22:40:13.980  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-28 22:40:13.980  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310],
08-28 22:40:13.980  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-28 22:40:13.980  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-28 22:40:13.982  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-28 22:40:13.982  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710],
,08-28 22:40:13.982  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-28 22:40:13.982  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-28 22:40:13.982  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-28 22:40:13.982  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-28 22:40:13.982  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-28 22:40:13.982  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310],
,08-28 22:40:13.982  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-28 22:40:13.983  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-28 22:40:13.983  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-28 22:40:13.983  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-28 22:40:13.983  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-28 22:40:13.983  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-28 22:40:13.983  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-28 22:40:13.983  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-28 22:40:13.983  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-28 22:40:13.983  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-28 22:40:13.983  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-28 22:40:13.983  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-28 22:40:13.984  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-28 22:40:13.984  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-28 22:40:13.984  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-28 22:40:13.984  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-28 22:40:13.984  3778  3828 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-28 22:40:13.984  3778  3828 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-28 22:40:13.985  3778  3828 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-28 22:40:13.985  3778  3828 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-28 22:40:13.985  3778  3828 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-28 22:40:13.985  3778  3828 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-28 22:40:13.985  3778  3828 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-28 22:40:13.985  3778  3828 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-28 22:40:13.985  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-28 22:40:13.988  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-28 22:40:13.989  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-28 22:40:13.989  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-28 22:40:13.990  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-28 22:40:13.990  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,08-28 22:40:13.990  3778  3828 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-28 22:40:13.990  3778  3828 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-28 22:40:13.991  3778  3828 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-28 22:40:13.991  3778  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-28 22:40:13.992  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-28 22:40:13.992  3778  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-28 22:40:13.992  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 22:40:13.992  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:13.992  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:13.992  3778  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 385)
08-28 22:40:13.992  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-28 22:40:13.993  3778  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fcfd998 not in the list
08-28 22:40:13.994  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:40:13.994  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
08-28 22:40:13.994  3778  3828 D io.jxcore.node.ConnectivityMonitor: stop
,08-28 22:40:13.994  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:13.994  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:13.994  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-28 22:40:13.994  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:13.996  3778  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 385
08-28 22:40:13.997  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 22:40:13.997  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-28 22:40:13.997  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-28 22:40:13.997  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
08-28 22:40:13.998  3778  3828 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported,
08-28 22:40:13.999  3778  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-28 22:40:13.999  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-28 22:40:13.999  3778  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-28 22:40:13.999  3778  3852 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-28 22:40:13.999  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-28 22:40:13.999  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:13.999  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:14.000  3778  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fcfd998 not in the list
08-28 22:40:14.000  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:40:14.000  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
,08-28 22:40:14.000  3778  3828 D io.jxcore.node.ConnectivityMonitor: stop
08-28 22:40:14.000  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:14.000  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 22:40:14.000  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:14.000  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:14.002  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 22:40:14.002  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-28 22:40:14.002  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-28 22:40:14.003  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
08-28 22:40:14.006  3778  3828 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-28 22:40:14.006  3778  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-28 22:40:14.006  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-28 22:40:14.006  3778  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-28 22:40:14.007  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 22:40:14.007  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:14.007  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:14.007  3778  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fcfd998 not in the list
08-28 22:40:14.007  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:40:14.007  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
08-28 22:40:14.007  3778  3828 D io.jxcore.node.ConnectivityMonitor: stop
08-28 22:40:14.007  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:14.007  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:14.007  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:14.007  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:14.009  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 22:40:14.009  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-28 22:40:14.009  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:40:14.009  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
,08-28 22:40:14.010  3778  3828 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-28 22:40:14.010  3778  3828 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-28 22:40:14.010  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-28 22:40:14.010  3778  3828 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-28 22:40:14.010  3778  3828 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-28 22:40:14.010  3778  3828 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55,
08-28 22:40:14.010  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-28 22:40:14.011  3778  3828 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55,
08-28 22:40:14.011  3778  3828 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-28 22:40:14.011  3778  3828 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,08-28 22:40:14.011  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-28 22:40:14.011  3778  3828 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,08-28 22:40:14.011  3778  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-28 22:40:14.011  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-28 22:40:14.011  3778  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-28 22:40:14.014  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 22:40:14.014  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-28 22:40:14.014  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:14.014  3778  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fcfd998 not in the list,
08-28 22:40:14.014  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:40:14.014  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
,08-28 22:40:14.014  3778  3828 D io.jxcore.node.ConnectivityMonitor: stop
08-28 22:40:14.014  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-28 22:40:14.014  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:14.014  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-28 22:40:14.015  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:14.016  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-28 22:40:14.016  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-28 22:40:14.016  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-28 22:40:14.016  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
08-28 22:40:14.016  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-28 22:40:14.016  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:14.017  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:14.017  3778  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fcfd998 not in the list,
08-28 22:40:14.017  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:40:14.017  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
,08-28 22:40:14.017  3778  3828 D io.jxcore.node.ConnectivityMonitor: stop
08-28 22:40:14.017  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-28 22:40:14.017  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 22:40:16.926  1990  2645 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-28 22:40:19.018  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-28 22:40:19.019  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
08-28 22:40:19.019  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-28 22:40:19.019  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:19.020  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:19.020  3778  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fcfd998 not in the list
,08-28 22:40:19.020  3778  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-28 22:40:19.021  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-28 22:40:19.021  3778  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-28 22:40:19.021  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-28 22:40:19.022  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:19.022  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:19.022  3778  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fcfd998 not in the list
,08-28 22:40:19.023  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:40:19.023  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
08-28 22:40:19.023  3778  3828 D io.jxcore.node.ConnectivityMonitor: stop
08-28 22:40:19.024  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-28 22:40:19.024  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:19.024  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-28 22:40:19.024  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 22:40:19.028  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 22:40:19.028  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-28 22:40:19.029  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:40:19.029  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
08-28 22:40:19.034  3778  3828 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-28 22:40:19.035  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-28 22:40:19.037  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-28 22:40:19.040  3778  3828 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-28 22:40:19.040  3778  3828 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-28 22:40:19.040  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-28 22:40:19.040  3778  3778 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-28 22:40:19.040  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-28 22:40:19.041  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-28 22:40:19.041  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-28 22:40:19.041  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-28 22:40:19.041  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-28 22:40:19.041  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 22:40:19.041  3778  3828 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-28 22:40:19.041  3778  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fcfd998 not in the list
08-28 22:40:19.041  3778  3778 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-28 22:40:19.041  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:40:19.041  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-28 22:40:19.042  3778  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-28 22:40:19.042  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-28 22:40:19.042  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:19.042  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:19.042  3778  3855 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-28 22:40:19.043  3778  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-28 22:40:19.043  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
08-28 22:40:19.043  3778  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-28 22:40:19.043  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-28 22:40:19.044  3778  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-28 22:40:19.044  3778  3778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-28 22:40:19.044  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 22:40:19.044  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:19.044  3778  3778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-28 22:40:19.044  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 22:40:19.044  3778  3778 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-28 22:40:19.044  3778  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fcfd998 not in the list
08-28 22:40:19.044  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:40:19.044  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
08-28 22:40:19.044  3778  3828 D io.jxcore.node.ConnectivityMonitor: stop
08-28 22:40:19.044  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:19.044  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 22:40:19.045  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:19.045  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:19.045  3778  3855 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-28 22:40:19.045  3778  3855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-28 22:40:19.045  3778  3855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true,
08-28 22:40:19.046  3778  3778 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-28 22:40:19.047  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 22:40:19.047  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-28 22:40:19.047  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:40:19.047  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
08-28 22:40:19.049  3778  3828 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-28 22:40:19.049  3778  3828 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-28 22:40:19.049  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-28 22:40:19.050  3778  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-28 22:40:19.050  3778  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-28 22:40:19.050  3778  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-28 22:40:19.050  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-28 22:40:19.050  3778  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-28 22:40:19.050  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 22:40:19.050  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:19.050  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:19.050  3778  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fcfd998 not in the list
08-28 22:40:19.050  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-28 22:40:19.051  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
08-28 22:40:19.051  3778  3828 D io.jxcore.node.ConnectivityMonitor: stop
08-28 22:40:19.051  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:19.051  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:19.051  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-28 22:40:19.051  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:19.053  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 22:40:19.053  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-28 22:40:19.053  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:40:19.053  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
,08-28 22:40:19.056  3778  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-28 22:40:19.056  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-28 22:40:19.056  3778  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-28 22:40:19.057  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-28 22:40:19.057  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:19.057  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:19.057  3778  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fcfd998 not in the list
08-28 22:40:19.057  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:40:19.057  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
08-28 22:40:19.057  3778  3828 D io.jxcore.node.ConnectivityMonitor: stop
08-28 22:40:19.057  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-28 22:40:19.057  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:19.058  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:19.058  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:19.059  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 22:40:19.059  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-28 22:40:19.059  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:40:19.059  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
,08-28 22:40:19.060  3778  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-28 22:40:19.060  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-28 22:40:19.060  3778  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-28 22:40:19.060  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 22:40:19.060  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:19.060  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:19.061  3778  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fcfd998 not in the list
,08-28 22:40:19.061  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:40:19.061  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
08-28 22:40:19.061  3778  3828 D io.jxcore.node.ConnectivityMonitor: stop
,08-28 22:40:19.061  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:19.061  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:19.061  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:19.061  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 22:40:19.064  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-28 22:40:19.064  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-28 22:40:19.064  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:40:19.064  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c25f1 not in the list
08-28 22:40:19.065  3778  3828 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-28 22:40:19.066  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-28 22:40:19.066  3778  3828 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-28 22:40:19.066  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-28 22:40:19.066  3778  3828 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-28 22:40:19.066  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-28 22:40:19.069  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-28 22:40:19.069  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-28 22:40:19.070  3778  3828 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-28 22:40:19.070  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-28 22:40:19.070  3778  3828 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,08-28 22:40:19.070  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-28 22:40:19.070  3778  3828 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-28 22:40:19.070  3778  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-28 22:40:19.071  3778  3828 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-28 22:40:19.071  3778  3828 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-28 22:40:19.071  3778  3828 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-28 22:40:19.071  3778  3828 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-28 22:40:19.072  3778  3828 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-28 22:40:19.072  3778  3828 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-28 22:40:19.073  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-28 22:40:19.073  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@638d8c8 added. We now have 3 listener(s)
,08-28 22:40:19.073  3778  3828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-28 22:40:19.074  3778  3828 D BluetoothAdapter: enable(): BT is already enabled..!
08-28 22:40:19.075   875  1723 D WifiService: setWifiEnabled: true pid=3778, uid=10000
08-28 22:40:19.075   875  1723 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-28 22:40:19.136  2682  2817 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,08-28 22:40:19.137  2682  2839 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
08-28 22:40:19.138  3778  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 385)
,08-28 22:40:19.383  3729  3857 I BooksSync: Starting books sync for 61035162, extras: ade
,08-28 22:40:19.428  3729  3858 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-28 22:40:19.461  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 22:40:19.468  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 22:40:19.542  1527  1538 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-28 22:40:19.543  1527  1538 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-28 22:40:19.543  1527  1538 I GLSUser : [GLSUser] Extracting token using key: Auth
08-28 22:40:19.544  1527  1538 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-28 22:40:19.544  3778  3778 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-28 22:40:19.618  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 22:40:19.625  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 22:40:19.696  1527  2295 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-28 22:40:19.697  1527  2295 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-28 22:40:19.698  1527  2295 I GLSUser : [GLSUser] Extracting token using key: Auth
08-28 22:40:19.698  1527  2295 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 22:40:19.751  3729  3858 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-28 22:40:19.755  3729  3857 E BooksSync: Soft error
08-28 22:40:19.755  3729  3857 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-28 22:40:19.755  3729  3857 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-28 22:40:19.757  3729  3857 E BooksSync: Sync error
08-28 22:40:19.757  3729  3857 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-28 22:40:19.757  3729  3857 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-28 22:40:19.757  3729  3857 I BooksSync: Finished books sync
,08-28 22:40:19.775   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 158143, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-28 22:40:20.778  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 22:40:20.960  1527  3860 I VacuumService: Vacuum at: now=1472416820960 tag=VacuumService
,08-28 22:40:20.962  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 22:40:20.973  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 22:40:20.976  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 22:40:21.031  1527  1539 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-28 22:40:21.031  1527  1539 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-28 22:40:21.031  1527  1539 I GLSUser : [GLSUser] Extracting token using key: Auth
08-28 22:40:21.031  1527  1539 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 22:40:21.046  3506  3506 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-28 22:40:21.046  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-28 22:40:21.047  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-28 22:40:21.080  1527  3861 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-28 22:40:21.083  1527  3861 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-28 22:40:21.122  1527  3861 W Uploader:  no longer exists, so no auth token.
,08-28 22:40:22.133  1527  3861 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-28 22:40:22.133  1527  3861 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-28 22:40:22.133  1527  3861 I GLSUser : [GLSUser] Extracting token using key: Auth
08-28 22:40:22.133  1527  3861 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 22:40:22.150  1527  3861 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-28 22:40:22.150  1527  3861 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-28 22:40:22.150  1527  3861 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-28 22:40:22.150  1527  3861 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-28 22:40:22.150  1527  3861 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-28 22:40:22.150  1527  3861 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-28 22:40:22.150  1527  3861 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-28 22:40:22.150  1527  3861 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-28 22:40:22.150  1527  3861 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-28 22:40:22.150  1527  3861 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-28 22:40:22.150  1527  3861 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-28 22:40:22.150  1527  3861 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-28 22:40:22.150  1527  3861 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-28 22:40:22.614  1527  3861 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-28 22:40:22.614  1527  3861 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-28 22:40:22.614  1527  3861 I GLSUser : [GLSUser] Extracting token using key: Auth
08-28 22:40:22.614  1527  3861 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 22:40:22.632  1527  3861 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-28 22:40:22.632  1527  3861 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-28 22:40:22.632  1527  3861 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-28 22:40:22.632  1527  3861 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-28 22:40:22.632  1527  3861 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-28 22:40:22.632  1527  3861 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-28 22:40:22.632  1527  3861 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-28 22:40:22.632  1527  3861 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-28 22:40:22.632  1527  3861 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-28 22:40:22.632  1527  3861 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-28 22:40:22.632  1527  3861 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-28 22:40:22.632  1527  3861 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-28 22:40:22.632  1527  3861 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-28 22:40:23.086  1527  3861 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-28 22:40:23.087  1527  3861 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-28 22:40:23.087  1527  3861 I GLSUser : [GLSUser] Extracting token using key: Auth
08-28 22:40:23.087  1527  3861 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 22:40:23.108  1527  3861 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-28 22:40:23.108  1527  3861 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-28 22:40:23.108  1527  3861 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-28 22:40:23.108  1527  3861 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-28 22:40:23.108  1527  3861 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-28 22:40:23.108  1527  3861 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-28 22:40:23.108  1527  3861 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-28 22:40:23.108  1527  3861 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-28 22:40:23.108  1527  3861 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-28 22:40:23.108  1527  3861 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-28 22:40:23.108  1527  3861 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-28 22:40:23.108  1527  3861 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-28 22:40:23.108  1527  3861 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-28 22:40:23.129   875  1318 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,08-28 22:40:23.278  1527  3861 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-28 22:40:23.278  1527  3861 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-28 22:40:23.279  1527  3861 I GLSUser : [GLSUser] Extracting token using key: Auth
08-28 22:40:23.279  1527  3861 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 22:40:23.299  1527  3861 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-28 22:40:23.299  1527  3861 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-28 22:40:23.299  1527  3861 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-28 22:40:23.299  1527  3861 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-28 22:40:23.299  1527  3861 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-28 22:40:23.299  1527  3861 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-28 22:40:23.299  1527  3861 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-28 22:40:23.299  1527  3861 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-28 22:40:23.299  1527  3861 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-28 22:40:23.299  1527  3861 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-28 22:40:23.299  1527  3861 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-28 22:40:23.299  1527  3861 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-28 22:40:23.299  1527  3861 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-28 22:40:24.082  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-28 22:40:24.083  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@af16d61 added. We now have 4 listener(s)
08-28 22:40:24.083  3778  3828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-28 22:40:24.100  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-28 22:40:24.100  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@af16d61 removed from the list
,08-28 22:40:24.100  3778  3828 D io.jxcore.node.ConnectivityMonitor: stop
08-28 22:40:24.101  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:24.101  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 22:40:24.104  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-28 22:40:24.105  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2255086 added. We now have 4 listener(s)
08-28 22:40:24.105  3778  3828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-28 22:40:24.109  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-28 22:40:24.110  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2255086 removed from the list
08-28 22:40:24.110  3778  3828 D io.jxcore.node.ConnectivityMonitor: stop
08-28 22:40:24.110  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-28 22:40:24.111  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:24.113  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-28 22:40:24.113  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6104d47 added. We now have 4 listener(s)
08-28 22:40:24.114  3778  3828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-28 22:40:24.121   875  1723 D WifiService: setWifiEnabled: false pid=3778, uid=10000
,08-28 22:40:24.121   875  1723 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-28 22:40:24.140  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-28 22:40:24.140  2682  2699 D BluetoothAdapterState: Current state: ON, message: 23
08-28 22:40:24.140  2682  2699 D BluetoothAdapterProperties: Setting state to 13
08-28 22:40:24.140  2682  2699 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-28 22:40:24.141  2682  2699 D BluetoothAdapterProperties: onBluetoothDisable()
,08-28 22:40:24.144  2682  2699 I BluetoothAdapterState: Entering PendingCommandState
08-28 22:40:24.148  2682  2682 D BluetoothMapService: onReceive
,08-28 22:40:24.149  2682  2682 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-28 22:40:24.149  2682  2682 D BluetoothMapService: STATE_TURNING_OFF
08-28 22:40:24.150  2682  2682 D BluetoothMapService: MAP Service closeService in
08-28 22:40:24.150  2682  2682 D BluetoothMapMasInstance0: MAP Service shutdown
,08-28 22:40:24.150  2682  2682 D ObexServerSockets0: shutdown(block = true)
08-28 22:40:24.151  2682  2876 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-28 22:40:24.153  2682  2682 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-28 22:40:24.154  2682  2877 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-28 22:40:24.156  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 22:40:24.156  3778  3828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-28 22:40:24.156  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:40:24.156  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:40:24.156  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 22:40:24.156  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 22:40:24.156  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-28 22:40:24.156  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-28 22:40:24.156  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-28 22:40:24.157  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-28 22:40:24.160  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 22:40:24.160  3778  3828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-28 22:40:24.161  3778  3828 D io.jxcore.node.ConnectivityMonitor: start: OK
08-28 22:40:24.161   875  1318 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-28 22:40:24.161   875  1318 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-28 22:40:24.162   875  1318 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-28 22:40:24.162   875  1318 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-28 22:40:24.164  2682  2839 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-28 22:40:24.164  2682  2682 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-28 22:40:24.165  2682  2682 I BtOppRfcommListener: stopping Accept Thread
08-28 22:40:24.165  2682  3421 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-28 22:40:24.165  2682  3421 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-28 22:40:24.166  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 22:40:24.169  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 22:40:24.173  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-28 22:40:24.173  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 22:40:24.173  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:40:24.173  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:40:24.173  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 22:40:24.173  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 22:40:24.173  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-28 22:40:24.173  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-28 22:40:24.173  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-28 22:40:24.175  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 22:40:24.175  3778  3778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-28 22:40:24.176   875  1318 E native  : do suspend true
,08-28 22:40:24.178  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-28 22:40:24.178  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 22:40:24.178  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:40:24.178  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:40:24.178  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 22:40:24.178  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 22:40:24.178  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-28 22:40:24.178  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-28 22:40:24.178  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-28 22:40:24.179  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 22:40:24.179  3778  3778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-28 22:40:24.182  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 22:40:24.187   373   873 D CommandListener: Clearing all IP addresses on wlan0
,08-28 22:40:24.187   875  1887 D DhcpClient: Clearing IP address
08-28 22:40:24.190   373   873 D CommandListener: Setting iface cfg
,08-28 22:40:24.192   875  1888 D DhcpClient: Receive thread stopped
,08-28 22:40:24.193   875   888 I ActivityManager: Start proc 3875:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-28 22:40:24.194  2682  2704 D BluetoothAdapterProperties: Scan Mode:20
,08-28 22:40:24.194  2682  2699 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-28 22:40:24.197  2682  2682 D HeadsetService: Received stop request...Stopping profile...
,08-28 22:40:24.198   875   875 D BluetoothHeadset: Proxy object disconnected
08-28 22:40:24.199  2682  2682 V BluetoothAdapterState: isTurningOff()=true
08-28 22:40:24.199  1374  1398 D BluetoothHeadset: Proxy object disconnected
,08-28 22:40:24.199  2682  2682 V BluetoothAdapterState: isTurningOn()=false
,08-28 22:40:24.199  2682  2682 V BluetoothAdapterState: isBleTurningOn()=false
,08-28 22:40:24.199  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 22:40:24.199  2682  2682 V BluetoothAdapterState: isBleTurningOff()=false
08-28 22:40:24.199  1374  1374 D HeadsetProfile: Bluetooth service disconnected
08-28 22:40:24.199  1943  1956 D BluetoothHeadset: Proxy object disconnected
,08-28 22:40:24.199  2682  2682 D A2dpService: Received stop request...Stopping profile...
08-28 22:40:24.200   875   875 D BluetoothHeadset: Proxy object disconnected
08-28 22:40:24.200   875   875 D BluetoothHeadset: Proxy object disconnected
08-28 22:40:24.200  2682  2854 D A2dpStateMachine: Exit Disconnected: -1
08-28 22:40:24.201   875   875 D BluetoothA2dp: Proxy object disconnected
,08-28 22:40:24.201  1374  1374 D BluetoothA2dp: Proxy object disconnected
08-28 22:40:24.202  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 22:40:24.203   875  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-28 22:40:24.203   875  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-28 22:40:24.203   875  1318 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-28 22:40:24.204   875  1318 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-28 22:40:24.204   875  1318 E native  : do suspend true
,08-28 22:40:24.206  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-28 22:40:24.206  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 22:40:24.206  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:40:24.206  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:40:24.206  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 22:40:24.206  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 22:40:24.206  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 22:40:24.206  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-28 22:40:24.206  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-28 22:40:24.207  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 22:40:24.207  3778  3778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-28 22:40:24.209   396   396 E Parcel  : Reading a NULL string not supported here.
08-28 22:40:24.194  1527  2458 V NativeCrypto: Read error: ssl=0x9af67c00: I/O error during system call, Connection timed out
08-28 22:40:24.212   875  1320 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-28 22:40:24.212  2682  2682 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-28 22:40:24.212  2682  2704 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-28 22:40:24.212  2682  2817 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-28 22:40:24.212  2682  2682 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-28 22:40:24.212  2682  2817 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-28 22:40:24.212  2682  2817 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-28 22:40:24.213  2682  2704 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-28 22:40:24.213  2682  2682 D HidService: Received stop request...Stopping profile...
08-28 22:40:24.214  2682  2682 D HidService: Stopping Bluetooth HidService
08-28 22:40:24.214  2682  2682 V BluetoothAdapterState: isTurningOff()=true
08-28 22:40:24.215  2682  2682 V BluetoothAdapterState: isTurningOn()=false
08-28 22:40:24.215  2682  2682 V BluetoothAdapterState: isBleTurningOn()=false
,08-28 22:40:24.215  2682  2682 V BluetoothAdapterState: isBleTurningOff()=false
,08-28 22:40:24.216  2682  2817 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-28 22:40:24.216  2682  2817 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-28 22:40:24.217  2682  2817 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-28 22:40:24.217  2682  2817 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-28 22:40:24.217  1527  2458 V NativeCrypto: SSL shutdown failed: ssl=0x9af67c00: I/O error during system call, Broken pipe
08-28 22:40:24.217  2682  2817 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-28 22:40:24.217  2682  2817 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-28 22:40:24.217  2682  2704 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-28 22:40:24.222  2682  2682 D HealthService: Received stop request...Stopping profile...
08-28 22:40:24.225  2682  2682 D PanService: Received stop request...Stopping profile...
08-28 22:40:24.228  2682  2682 D BluetoothMapService: Received stop request...Stopping profile...
08-28 22:40:24.228  2682  2682 D BluetoothMapService: stop()
08-28 22:40:24.231  1374  1374 D BluetoothInputDevice: Proxy object disconnected
08-28 22:40:24.231  1374  1374 D HidProfile: Bluetooth service disconnected
08-28 22:40:24.232  2682  2682 D BluetoothMapAppObserver: deinitObservers()
08-28 22:40:24.233  2682  2682 D BluetoothMapAppObserver: removeReceiver()
08-28 22:40:24.233  1374  1374 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-28 22:40:24.233  1374  1374 D PanProfile: Bluetooth service disconnected
,08-28 22:40:24.234  1374  1374 D BluetoothMap: Proxy object disconnected
08-28 22:40:24.234  1374  1374 D MapProfile: Bluetooth service disconnected
08-28 22:40:24.234  2682  2682 V BluetoothAdapterState: isTurningOff()=true
08-28 22:40:24.234  2682  2682 V BluetoothAdapterState: isTurningOn()=false
08-28 22:40:24.234  2682  2682 V BluetoothAdapterState: isBleTurningOn()=false
08-28 22:40:24.234  2682  2682 V BluetoothAdapterState: isBleTurningOff()=false
08-28 22:40:24.234  2682  2682 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-28 22:40:24.234  2682  2682 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-28 22:40:24.234  2682  2704 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-28 22:40:24.234  2682  2682 V BluetoothAdapterState: isTurningOff()=true
,08-28 22:40:24.235  2682  2682 V BluetoothAdapterState: isTurningOn()=false
08-28 22:40:24.235  2682  2682 V BluetoothAdapterState: isBleTurningOn()=false
08-28 22:40:24.235  2682  2682 V BluetoothAdapterState: isBleTurningOff()=false
08-28 22:40:24.235  2682  2682 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-28 22:40:24.235  2682  2704 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-28 22:40:24.235  2682  2682 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-28 22:40:24.236  2682  2682 V BluetoothAdapterState: isTurningOff()=true
08-28 22:40:24.237  2682  2682 V BluetoothAdapterState: isTurningOn()=false
08-28 22:40:24.237  2682  2682 V BluetoothAdapterState: isBleTurningOn()=false
08-28 22:40:24.237  2682  2682 V BluetoothAdapterState: isBleTurningOff()=false
08-28 22:40:24.238  2682  2682 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-28 22:40:24.238  2682  2682 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-28 22:40:24.239  2682  2682 D BluetoothMapService: MAP Service closeService in
08-28 22:40:24.239  2682  2682 V BluetoothAdapterState: isTurningOff()=true
08-28 22:40:24.239  2682  2682 V BluetoothAdapterState: isTurningOn()=false
08-28 22:40:24.242  2682  2682 V BluetoothAdapterState: isBleTurningOn()=false
08-28 22:40:24.242  2682  2682 V BluetoothAdapterState: isBleTurningOff()=false
08-28 22:40:24.243  2682  2699 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-28 22:40:24.243  2682  2699 D BluetoothAdapterProperties: Setting state to 15
08-28 22:40:24.243  2682  2699 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-28 22:40:24.243  1374  2079 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-28 22:40:24.244  1374  1396 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-28 22:40:24.244  1943  2224 D BluetoothHeadset: onBluetoothStateChange: up=false
08-28 22:40:24.244  2682  2699 I BluetoothAdapterState: Entering BleOnState
08-28 22:40:24.244   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-28 22:40:24.244  1374  1398 D BluetoothMap: onBluetoothStateChange: up=false
08-28 22:40:24.245   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-28 22:40:24.245  1374  2079 D BluetoothA2dp: onBluetoothStateChange: up=false
08-28 22:40:24.245   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-28 22:40:24.245  1374  1396 D BluetoothPan: onBluetoothStateChange on: false
08-28 22:40:24.246  1374  1398 D BluetoothPbap: onBluetoothStateChange: up=false
08-28 22:40:24.247   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-28 22:40:24.247  2682  2699 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-28 22:40:24.247  2682  2699 D BluetoothAdapterProperties: Setting state to 16
08-28 22:40:24.247  2682  2699 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-28 22:40:24.248  2682  2699 D BluetoothAdapterProperties: onBleDisable
08-28 22:40:24.248  2682  2699 I BluetoothAdapterState: Entering PendingCommandState
08-28 22:40:24.248  2682  2701 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-28 22:40:24.248  2682  2704 D BluetoothAdapterProperties: Scan Mode:20
08-28 22:40:24.249  2682  2817 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-28 22:40:24.249  2682  2817 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-28 22:40:24.250  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-28 22:40:24.250  2682  2682 D BluetoothMapService: cleanup()
08-28 22:40:24.250  2682  2682 D BluetoothMapService: MAP Service closeService in
08-28 22:40:24.250  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 22:40:24.250  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:40:24.250  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:40:24.250  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 22:40:24.250  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 22:40:24.250  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 22:40:24.250  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 22:40:24.250  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-28 22:40:24.251  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 22:40:24.251  3778  3778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-28 22:40:24.252  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 22:40:24.253  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 22:40:24.253  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:40:24.253  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:40:24.253  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 22:40:24.253  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 22:40:24.253  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 22:40:24.253  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 22:40:24.253  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-28 22:40:24.253  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 22:40:24.253  3778  3778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-28 22:40:24.255  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 22:40:24.255  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 22:40:24.255  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:40:24.255  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:40:24.255  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 22:40:24.255  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 22:40:24.255  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 22:40:24.255  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 22:40:24.255  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-28 22:40:24.257  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 22:40:24.258  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 22:40:24.259  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 22:40:24.260   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-28 22:40:24.273  3875  3875 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-28 22:40:24.281  3875  3875 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-28 22:40:24.282   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-28 22:40:24.282   373   873 D CommandListener: Clearing all IP addresses on wlan0
,08-28 22:40:24.283   875  1320 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-28 22:40:24.283   875  1320 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-28 22:40:24.285   875  1318 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-28 22:40:24.288   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-28 22:40:24.291  1527  1527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-28 22:40:24.291  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 22:40:24.293  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 22:40:24.294  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 22:40:24.293  3371  3371 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@18e16dc and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-28 22:40:24.300   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@62555b8:true
,08-28 22:40:24.308   875  2221 I ActivityManager: Start proc 3894:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-28 22:40:24.309   875  1318 D WifiConfigStore: Retrieve network priorities after PNO.
,08-28 22:40:24.313  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-28 22:40:24.313  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 22:40:24.313  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:40:24.313  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:40:24.313  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-28 22:40:24.313  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 22:40:24.313  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 22:40:24.313  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 22:40:24.313  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-28 22:40:24.313  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 22:40:24.313  3778  3778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-28 22:40:24.313   875  1318 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-28 22:40:24.315  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 22:40:24.315  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 22:40:24.315  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:40:24.315  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:40:24.315  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-28 22:40:24.315  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 22:40:24.315  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 22:40:24.315  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 22:40:24.315  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-28 22:40:24.316  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-28 22:40:24.316  3778  3778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-28 22:40:24.318  1990  2318 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-28 22:40:24.318  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 22:40:24.318  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 22:40:24.318  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:40:24.318  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:40:24.318  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-28 22:40:24.318  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 22:40:24.318  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 22:40:24.318  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 22:40:24.318  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-28 22:40:24.319  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 22:40:24.319  3778  3778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-28 22:40:24.339  3875  3875 D LocalBluetoothProfileManager: Adding local MAP profile
,08-28 22:40:24.341  3875  3875 D BluetoothMap: Create BluetoothMap proxy object
,08-28 22:40:24.344  3875  3875 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-28 22:40:24.347   373   873 E Netd    : netlink response contains error (No such file or directory)
,08-28 22:40:24.348   875  1320 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-28 22:40:24.349  3894  3894 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-28 22:40:24.357  3875  3875 D DockEventReceiver: finishStartingService: stopping service
,08-28 22:40:24.364   875  1964 I ActivityManager: Killing 3371:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-28 22:40:24.456  2682  2704 I bt_hci  : shut_down
,08-28 22:40:24.456  2682  2711 D bt_hwcfg: hw_epilog_process
,08-28 22:40:24.458  2682  2711 I bt_vendor: low_power_mode_cb
,08-28 22:40:24.486  2682  2711 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-28 22:40:24.486  2682  2711 I bt_vendor: epilog_cb
,08-28 22:40:24.486  2682  2711 I bt_hci  : epilog_finished_callback
,08-28 22:40:24.495  2682  2704 I bt_hci_h4: hal_close
,08-28 22:40:24.497  2682  2704 I bt_userial_vendor: device fd = 51 close
,08-28 22:40:24.620  2682  2701 D bt_stack_manager: event_shut_down_stack finished.
,08-28 22:40:24.621  2682  2699 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-28 22:40:24.622  2682  2699 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-28 22:40:24.623  2682  2682 D BtGatt.DebugUtils: handleDebugAction() action=null
08-28 22:40:24.623  2682  2682 D BtGatt.GattService: Received stop request...Stopping profile...
08-28 22:40:24.623  2682  2682 D BtGatt.GattService: stop()
08-28 22:40:24.623  2682  2682 D BtGatt.AdvertiseManager: advertise clients cleared
08-28 22:40:24.625  2682  2682 V BluetoothAdapterState: isTurningOff()=false
08-28 22:40:24.625  2682  2682 V BluetoothAdapterState: isTurningOn()=false
,08-28 22:40:24.625  2682  2682 V BluetoothAdapterState: isBleTurningOn()=false
08-28 22:40:24.625  2682  2682 V BluetoothAdapterState: isBleTurningOff()=true
08-28 22:40:24.625  2682  2699 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-28 22:40:24.625  2682  2699 D BluetoothAdapterProperties: Setting state to 10
,08-28 22:40:24.625  2682  2699 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-28 22:40:24.626  2682  2699 I BluetoothAdapterState: Entering OffState
,08-28 22:40:24.628   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-28 22:40:24.647  2682  2682 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-28 22:40:24.648  2682  2682 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-28 22:40:24.648  2682  2682 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-28 22:40:24.649  2682  2701 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-28 22:40:24.651  2682  2701 D bt_stack_manager: event_clean_up_stack finished.
,08-28 22:40:24.663  2682  2682 I art     : System.exit called, status: 0
,08-28 22:40:24.663  2682  2682 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-28 22:40:24.683  3894  3894 D StrictMode: StrictMode policy violation; ~duration=176 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at java.io.File.exists(File.java:361)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-28 22:40:24.683  3894  3894 D StrictMode: StrictMode policy violation; ~duration=174 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-28 22:40:24.683  3894  3894 D StrictMode: StrictMode policy violation; ~duration=172 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-28 22:40:24.683  3894  3894 D StrictMode: StrictMode policy violation; ~duration=166 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.r.e.b(PG:170)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
,08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
,08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-28 22:40:24.683  3894  3894 D StrictMode: 	,at java.lang.reflect.Method.invoke(Native Method)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-28 22:40:24.683  3894  3894 D StrictMode: StrictMode policy violation; ~duration=162 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
,08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.r.k.d(PG:583)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.r.e.b(PG:170)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-28 22:40:24.683  3894  3894 D StrictMode: 	,at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-28 22:40:24.683  3894  3894 D StrictMode: StrictMode policy violation; ~duration=141 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-28 22:40:24.683  3894  3894 D StrictMode: ,	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at java.io.File.exists(File.java:361)
,08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-28 22:40:24.683  3894  3894 D StrictMode: 	,at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-28 22:40:24.683  3894  3894 D StrictMode: StrictMode policy violation; ~duration=140 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at java.io.File.exists(File.java:361)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-28 22:40:24.683  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-28 22:40:24.684  3894  3894 D StrictMode: StrictMode policy violation; ~duration=140 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=6,5567 violation=2
08-28 22:40:24.684  3894  3894 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-28 22:40:24.684  3894  3894 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-28 22:40:24.684  3894  3894 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-28 22:40:24.684  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-28 22:40:24.684  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-28 22:40:24.684  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-28 22:40:24.684  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-28 22:40:24.684  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-28 22:40:24.684  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-28 22:40:24.684  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-28 22:40:24.684  3894  3894 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-28 22:40:24.684  3894  3894 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-28 22:40:24.684  3894  3894 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-28 22:40:24.684  3894  3894 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-28 22:40:24.684  3894  3894 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-28 22:40:24.684  3894  3894 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-28 22:40:24.684  3894  3894 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-28 22:40:24.684  3894  3894 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-28 22:40:24.684  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-28 22:40:24.684  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-28 22:40:24.705  3875  3875 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-28 22:40:24.708   875  1930 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 76)
08-28 22:40:24.708   875  1930 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1904)
08-28 22:40:24.709   875  1930 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapReceiver}
08-28 22:40:24.709   875  1930 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
08-28 22:40:24.709   875  1930 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-28 22:40:24.709   875  1930 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
08-28 22:40:24.709   875  1930 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
08-28 22:40:24.709   875  1930 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
08-28 22:40:24.709   875  1930 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
08-28 22:40:24.709   875  1930 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17118)
08-28 22:40:24.709   875  1930 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
08-28 22:40:24.709   875  1930 W BroadcastQueue: 	at com.android.server.am.Activ,ityManagerService.onTransact(ActivityManagerService.java:2483)
08-28 22:40:24.709   875  1930 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
08-28 22:40:24.741   875  1930 I ActivityManager: Start proc 3928:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
08-28 22:40:24.743  3875  3875 D DockEventReceiver: finishStartingService: stopping service
08-28 22:40:24.743   875  1972 W ActivityManager: Spurious death for ProcessRecord{20d0038 3928:com.android.bluetooth/1002}, curProc for 2682: null
08-28 22:40:24.747   875   885 I ActivityManager: Killing 3550:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-28 22:40:24.871  3928  3928 D AdapterServiceConfig: Adding HeadsetService
,08-28 22:40:24.871  3928  3928 D AdapterServiceConfig: Adding A2dpService
08-28 22:40:24.871  3928  3928 D AdapterServiceConfig: Adding HidService
08-28 22:40:24.872  3928  3928 D AdapterServiceConfig: Adding HealthService
08-28 22:40:24.872  3928  3928 D AdapterServiceConfig: Adding PanService
08-28 22:40:24.872  3928  3928 D AdapterServiceConfig: Adding GattService
,08-28 22:40:24.872  3928  3928 D AdapterServiceConfig: Adding BluetoothMapService
,08-28 22:40:24.876  1527  1527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-28 22:40:24.892  1725  1725 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-28 22:40:24.895  1725  1725 D SystemUpdateService: onCreate
,08-28 22:40:24.898  1725  1725 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-28 22:40:24.902  1725  3942 I SystemUpdateService: active receiver: enabled
,08-28 22:40:24.906  1725  3942 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-28 22:40:24.907  1725  1725 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-28 22:40:24.912  1725  2422 I iu.UploadsManager: num queued entries: 0
,08-28 22:40:24.912  1725  2422 I iu.UploadsManager: num updated entries: 0
,08-28 22:40:24.912  1725  3942 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-28 22:40:24.912  1725  3942 I SystemUpdateService: now status is 0 (complete)
08-28 22:40:24.913  1725  3942 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-28 22:40:24.913  1725  3942 I SystemUpdateService: file has been verified
,08-28 22:40:24.913  1725  3942 I SystemUpdateService: OTA package size = 12249756
08-28 22:40:24.915  1725  1725 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-28 22:40:24.917  1725  1725 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-28 22:40:24.918  1725  2422 I iu.SyncManager: NEXT; no task
08-28 22:40:24.919  1725  3942 I SystemUpdateService: showing system update notification
,08-28 22:40:24.925  3894  3920 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-28 22:40:24.939   875  2221 I ActivityManager: Start proc 3944:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-28 22:40:24.941  1725  1725 D SystemUpdateService: onDestroy
,08-28 22:40:24.948   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@39015c4:true
,08-28 22:40:24.969  3944  3944 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-28 22:40:24.971  3944  3944 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-28 22:40:24.976  3944  3944 D SprintDMHelper: simOperator: 
08-28 22:40:24.976  3944  3944 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-28 22:40:24.989   875  1964 I ActivityManager: Start proc 3956:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
08-28 22:40:24.990   875  1964 I ActivityManager: Killing 3444:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-28 22:40:25.133  2463  3970 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-28 22:40:25.146   875  1381 I ActivityManager: Start proc 3971:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-28 22:40:25.151   875   886 I ActivityManager: Killing 3490:android.process.acore/u0a5 (adj 15): empty #17
,08-28 22:40:25.243  3971  3971 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-28 22:40:25.303  3971  3971 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-28 22:40:25.303  3971  3971 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-28 22:40:25.303  3971  3971 I GAv4    :   adb logcat -s GAv4
,08-28 22:40:25.320  3971  3971 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-28 22:40:25.327  3971  3971 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-28 22:40:25.360  3971  3988 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-28 22:40:25.470  3971  3971 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-28 22:40:25.510  3971  3971 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-28 22:40:25.521  3971  3971 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 4346-4352)
08-28 22:40:25.521  3971  3971 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-28 22:40:25.531  3971  3971 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {172ef0c}
08-28 22:40:25.531  3971  3971 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-28 22:40:25.531  3971  3971 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-28 22:40:25.539  3971  3971 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-28 22:40:25.541  3971  3971 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-28 22:40:25.557  3971  3971 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-28 22:40:25.573  3971  3971 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-28 22:40:25.573  3971  3971 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-28 22:40:25.573  3971  3971 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-28 22:40:25.573  3971  3971 I Adreno  : Build Date                       : 10/20/15
08-28 22:40:25.573  3971  3971 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-28 22:40:25.573  3971  3971 I Adreno  : Local Branch                     : M14
08-28 22:40:25.573  3971  3971 I Adreno  : Remote Branch                    : 
08-28 22:40:25.573  3971  3971 I Adreno  : Remote Branch                    : 
08-28 22:40:25.573  3971  3971 I Adreno  : Reconstruct Branch               : 
,08-28 22:40:25.637  3971  3971 I NSApplication: Starting up...
,08-28 22:40:25.649  3971  4017 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-28 22:40:25.668   875  2221 I ActivityManager: Start proc 4022:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
08-28 22:40:25.670   875  2221 I ActivityManager: Killing 3625:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-28 22:40:25.747  4022  4022 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-28 22:40:25.960   875  1541 I ActivityManager: Killing 3642:com.android.musicfx/u0a18 (adj 15): empty #17
,08-28 22:40:26.028   875  1972 I ActivityManager: Start proc 4036:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-28 22:40:26.080  4036  4036 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-28 22:40:26.126  4036  4036 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-28 22:40:26.142   875  1930 I ActivityManager: Killing 2148:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-28 22:40:29.163   875  1964 D WifiService: setWifiEnabled: true pid=3778, uid=10000
,08-28 22:40:29.164   875  1964 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-28 22:40:29.176   875  1318 D WifiConfigStore: Loading config and enabling all networks 
08-28 22:40:29.186  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 22:40:29.186  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 22:40:29.186  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:40:29.186  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:40:29.186  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 22:40:29.186  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 22:40:29.186  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 22:40:29.186  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 22:40:29.186  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-28 22:40:29.186  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 22:40:29.187  3778  3778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-28 22:40:29.189  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 22:40:29.189  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 22:40:29.189  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:40:29.189  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:40:29.189  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 22:40:29.189  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 22:40:29.189  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 22:40:29.189  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 22:40:29.189  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-28 22:40:29.190  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 22:40:29.190  3778  3778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-28 22:40:29.193  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-28 22:40:29.193  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 22:40:29.193  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:40:29.193  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:40:29.193  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 22:40:29.193  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 22:40:29.193  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 22:40:29.193  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 22:40:29.193  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-28 22:40:29.193  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 22:40:29.193  3778  3778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-28 22:40:29.215   875  1318 D WifiConfigStore: loaded 0 passpoint configs
08-28 22:40:29.216   875  1318 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-28 22:40:29.217   875  1318 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-28 22:40:29.217   875  1318 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-28 22:40:29.218   875  1318 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-28 22:40:29.218   875  1318 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-28 22:40:29.218   875  1318 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-28 22:40:29.237   373   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-28 22:40:29.237   875  1318 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-28 22:40:29.239   373   873 D CommandListener: Setting iface cfg
,08-28 22:40:29.249   875  1317 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '129 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 129 Failed to set address (No such device)'
,08-28 22:40:29.250   875  1317 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-28 22:40:29.251   875  1318 E native  : do suspend true
,08-28 22:40:29.268   875  1317 D WifiNative-HAL: p2pGetDeviceAddress
,08-28 22:40:29.270   875  1317 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-28 22:40:29.276   875  1318 D WifiConfigStore: Retrieve network priorities after PNO.
,08-28 22:40:29.959   875   885 I ActivityManager: Killing 3664:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-28 22:40:30.672   875  1318 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-28 22:40:30.768   875  1318 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.88 rxSuccessRate=7.00 delta 1000 -> 994
,08-28 22:40:30.770   875  1318 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-28 22:40:30.770   875  1318 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-28 22:40:30.788   875  1318 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-28 22:40:30.867   875  1318 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-28 22:40:30.870  1469  1469 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-28 22:40:31.305  1469  1469 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-28 22:40:31.355  1469  1469 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-28 22:40:31.356  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-28 22:40:31.358   875  1318 D WifiConfigStore: Retrieve network priorities after PNO.
,08-28 22:40:31.371   875  1318 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-28 22:40:31.371   875  1318 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-28 22:40:31.371   875  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-28 22:40:31.389   875  1318 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-28 22:40:31.399   373   873 D CommandListener: Setting iface cfg
08-28 22:40:31.400   875  1318 D WifiStateMachine: Start Dhcp Watchdog 2
,08-28 22:40:31.407   875  1318 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-28 22:40:31.427   875  4071 D DhcpClient: Receive thread started
,08-28 22:40:31.512   875  1318 E native  : do suspend false
,08-28 22:40:31.536   875  1887 D DhcpClient: Broadcasting DHCPDISCOVER
,08-28 22:40:31.549   875  4071 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172652, domain null
,08-28 22:40:31.551   875  1887 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172652 seconds
,08-28 22:40:31.554   875  1887 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-28 22:40:31.569   875  4071 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-28 22:40:31.570   875  1887 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-28 22:40:31.574   373   873 D CommandListener: Setting iface cfg
,08-28 22:40:31.586   875  1887 D DhcpClient: Scheduling renewal in 86399s
,08-28 22:40:31.586   875  1318 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-28 22:40:31.591   875  1318 E native  : do suspend true
,08-28 22:40:31.613   875  1318 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-28 22:40:31.617   875  1318 D WifiConfigStore: No blacklist allowed without epno enabled
,08-28 22:40:31.619   875  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-28 22:40:31.623   875  1320 D ConnectivityService: Adding iface wlan0 to network 101
08-28 22:40:31.623   875  1318 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-28 22:40:31.684   875  1320 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-28 22:40:31.685   875  1320 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-28 22:40:31.686   875  1320 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-28 22:40:31.688   875  1320 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-28 22:40:31.691   875  1320 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-28 22:40:31.709   875  1320 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-28 22:40:31.715   875  1320 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-28 22:40:31.716   875  1320 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-28 22:40:31.716   875  1320 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-28 22:40:31.716   875  1320 D ConnectivityService:    accepting network in place of null
08-28 22:40:31.716   875  1318 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-28 22:40:31.717   875  1320 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-28 22:40:31.718   875  1318 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-28 22:40:31.729   875  4070 D NetlinkSocketObserver: NeighborEvent{elapsedMs=170560, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-28 22:40:31.768   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-28 22:40:31.804   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-28 22:40:31.812   875  1320 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-28 22:40:31.812   875  1320 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-28 22:40:31.813   875  4069 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.174,2a00:1450:4001:816::200e
,08-28 22:40:31.822   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-28 22:40:31.832   875  1320 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-28 22:40:31.833  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 22:40:31.833  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 22:40:31.833  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:40:31.833  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:40:31.833  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 22:40:31.833  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 22:40:31.833  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-28 22:40:31.833  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-28 22:40:31.833  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-28 22:40:31.833  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 22:40:31.833  3778  3778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-28 22:40:31.836  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 22:40:31.836  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 22:40:31.836  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:40:31.836  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:40:31.836  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 22:40:31.836  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 22:40:31.836  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-28 22:40:31.836  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-28 22:40:31.836  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-28 22:40:31.836  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 22:40:31.836  3778  3778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-28 22:40:31.839  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 22:40:31.839  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 22:40:31.839  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:40:31.839  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:40:31.839  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 22:40:31.839  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 22:40:31.839  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-28 22:40:31.839  37,78  3778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-28 22:40:31.839  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-28 22:40:31.839  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 22:40:31.839  3778  3778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-28 22:40:31.851  1725  1725 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-28 22:40:31.857  1725  1725 D SystemUpdateService: onCreate
08-28 22:40:31.861  1725  1725 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-28 22:40:31.879  1725  4081 I SystemUpdateService: active receiver: enabled
,08-28 22:40:31.889  1725  1725 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-28 22:40:31.893  1725  4081 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-28 22:40:31.894  1725  2422 I iu.UploadsManager: num queued entries: 0,
08-28 22:40:31.894  1725  2422 I iu.UploadsManager: num updated entries: 0
,08-28 22:40:31.895  1725  2422 I iu.SyncManager: NEXT; no task
08-28 22:40:31.896  1725  4081 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-28 22:40:31.896  1725  4081 I SystemUpdateService: now status is 0 (complete)
08-28 22:40:31.896  1725  4081 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-28 22:40:31.896  1725  4081 I SystemUpdateService: file has been verified
08-28 22:40:31.896  1725  4081 I SystemUpdateService: OTA package size = 12249756
,08-28 22:40:31.897   875  4069 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sun, 28 Aug 2016 20:40:31 GMT], X-Android-Received-Millis=[1472416831896], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472416831861]}
,08-28 22:40:31.904   875  1320 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-28 22:40:31.905   875  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-28 22:40:31.905   875  1320 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-28 22:40:31.916   875  1320 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-28 22:40:31.917  1725  1725 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-28 22:40:31.918  1725  1725 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-28 22:40:31.920  3944  3944 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-28 22:40:31.923  1725  4084 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-28 22:40:31.923  1725  4084 W BaseAppContext: Using Auth Proxy for data requests.
,08-28 22:40:31.925  1725  4084 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
,08-28 22:40:31.927  3944  3944 D SprintDMHelper: simOperator: 
08-28 22:40:31.927  3944  3944 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-28 22:40:31.937  1725  4081 I SystemUpdateService: showing system update notification
,08-28 22:40:31.946  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 22:40:31.951  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 22:40:32.011  1725  1725 D SystemUpdateService: onDestroy
,08-28 22:40:32.028  1527  1538 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-28 22:40:32.028  1527  1538 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-28 22:40:32.029  1527  1538 I GLSUser : [GLSUser] Extracting token using key: Auth
08-28 22:40:32.029  1527  1538 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 22:40:32.051  3021  4079 V KeepSync: Connecting to GoogleApiClient
,08-28 22:40:32.052   875   885 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-28 22:40:32.075  1725  4084 E MDM     : [178] SitrepService.a: Error sending sitrep.
,08-28 22:40:32.097  1527  2295 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-28 22:40:32.097  1527  2295 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-28 22:40:32.097  1527  2295 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-28 22:40:32.097  1527  2295 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 22:40:32.103  2463  4087 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-28 22:40:32.114  1725  4093 V BaseAuthAsyncOperation: access token request failed
,08-28 22:40:32.115  3021  4079 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-28 22:40:32.155  1527  2297 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-28 22:40:32.155  1527  2297 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-28 22:40:32.155  1527  2297 I GLSUser : [GLSUser] Extracting token using key: Auth
08-28 22:40:32.156  1527  2297 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 22:40:32.169  3021  4079 E KeepSync: IOException
08-28 22:40:32.169  3021  4079 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-28 22:40:32.169  3021  4079 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-28 22:40:32.169  3021  4079 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-28 22:40:32.169  3021  4079 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-28 22:40:32.169  3021  4079 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-28 22:40:32.169  3021  4079 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-28 22:40:32.169  3021  4079 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-28 22:40:32.169  3021  4079 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-28 22:40:32.169  3021  4079 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-28 22:40:32.169  3021  4079 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-28 22:40:32.169  3021  4079 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-28 22:40:32.169  3021  4079 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-28 22:40:32.169  3021  4079 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-28 22:40:32.169  3021  4079 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-28 22:40:32.169  3021  4079 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-28 22:40:32.169  3021  4079 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-28 22:40:32.169  3021  4079 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-28 22:40:32.169  3021  4079 E KeepSync: 	... 10 more
08-28 22:40:32.169  3021  4079 W KeepSync: Sync result 2
,08-28 22:40:32.180   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 160278, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-28 22:40:32.221  1725  1725 I GCM     : Message from null null
,08-28 22:40:32.221  1725  1725 E GCM     : Dropping message from null
,08-28 22:40:32.812   875  1320 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-28 22:40:34.171   875  1722 D WifiService: setWifiEnabled: false pid=3778, uid=10000
,08-28 22:40:34.171   875  1722 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-28 22:40:34.209  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-28 22:40:34.218   875  1318 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-28 22:40:34.219   875  1318 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-28 22:40:34.219   875  1318 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-28 22:40:34.220   875  1318 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-28 22:40:34.241   875  1318 E native  : do suspend true
,08-28 22:40:34.260   875  1887 D DhcpClient: Clearing IP address
,08-28 22:40:34.261   373   873 D CommandListener: Clearing all IP addresses on wlan0
08-28 22:40:34.267   373   873 D CommandListener: Setting iface cfg
,08-28 22:40:34.281   875  4071 D DhcpClient: Receive thread stopped
,08-28 22:40:34.286   875  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-28 22:40:34.287   875  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-28 22:40:34.287  1527  4092 V NativeCrypto: Read error: ssl=0x9a942a00: I/O error during system call, Connection timed out
08-28 22:40:34.291  1527  4092 V NativeCrypto: SSL shutdown failed: ssl=0x9a942a00: I/O error during system call, Broken pipe
,08-28 22:40:34.293   396   396 E Parcel  : Reading a NULL string not supported here.
08-28 22:40:34.297   875  1318 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-28 22:40:34.298   875  1318 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-28 22:40:34.298   875  1318 E native  : do suspend true
,08-28 22:40:34.301   875  1320 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-28 22:40:34.357   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-28 22:40:34.388   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-28 22:40:34.389   875  1320 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-28 22:40:34.389   875  1320 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-28 22:40:34.389   373   873 D CommandListener: Clearing all IP addresses on wlan0
,08-28 22:40:34.393   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-28 22:40:34.410  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-28 22:40:34.410  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 22:40:34.410  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:40:34.410  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:40:34.410  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 22:40:34.410  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 22:40:34.410  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 22:40:34.410  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 22:40:34.410  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-28 22:40:34.410  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-28 22:40:34.410  3778  3778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-28 22:40:34.413  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 22:40:34.413  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 22:40:34.413  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:40:34.413  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:40:34.413  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 22:40:34.413  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 22:40:34.413  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 22:40:34.413  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 22:40:34.413  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-28 22:40:34.413  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 22:40:34.414  3778  3778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-28 22:40:34.415  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 22:40:34.415  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 22:40:34.415  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:40:34.415  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:40:34.415  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 22:40:34.415  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 22:40:34.415  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 22:40:34.415  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 22:40:34.415  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-28 22:40:34.415  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 22:40:34.415  3778  3778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-28 22:40:34.414   875  1318 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-28 22:40:34.429  1725  1725 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-28 22:40:34.433  1725  1725 D SystemUpdateService: onCreate
,08-28 22:40:34.436   875  1318 D WifiConfigStore: Retrieve network priorities after PNO.
,08-28 22:40:34.439  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-28 22:40:34.439  1990  2318 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-28 22:40:34.439  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 22:40:34.439  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:40:34.439  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:40:34.439  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-28 22:40:34.439  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 22:40:34.439  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 22:40:34.439  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 22:40:34.439  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-28 22:40:34.439  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 22:40:34.439  3778  3778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-28 22:40:34.440  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-28 22:40:34.440  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 22:40:34.440  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:40:34.440  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:40:34.440  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-28 22:40:34.440  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 22:40:34.440  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 22:40:34.440  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 22:40:34.440  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-28 22:40:34.440  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 22:40:34.440  3778  3778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-28 22:40:34.442  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 22:40:34.442  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 22:40:34.442  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:40:34.442  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:40:34.442  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-28 22:40:34.442  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 22:40:34.442  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 22:40:34.442  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 22:40:34.442  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-28 22:40:34.442  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 22:40:34.442  3778  3778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-28 22:40:34.443  1725  1725 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-28 22:40:34.443   875  1318 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-28 22:40:34.453  1725  1725 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-28 22:40:34.459  1725  2422 I iu.UploadsManager: num queued entries: 0
08-28 22:40:34.459  1725  2422 I iu.UploadsManager: num updated entries: 0
08-28 22:40:34.460  1725  2422 I iu.SyncManager: NEXT; no task
,08-28 22:40:34.464  1725  1725 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-28 22:40:34.465  1725  1725 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-28 22:40:34.468  3944  3944 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-28 22:40:34.473  3944  3944 D SprintDMHelper: simOperator: 
,08-28 22:40:34.473  3944  3944 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-28 22:40:34.485   373   873 E Netd    : netlink response contains error (No such file or directory)
,08-28 22:40:34.486   875  1320 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-28 22:40:34.473  1725  4103 I SystemUpdateService: active receiver: enabled
,08-28 22:40:34.515  2463  4107 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-28 22:40:34.528  1725  4103 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-28 22:40:34.529  1725  4103 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-28 22:40:34.529  1725  4103 I SystemUpdateService: now status is 0 (complete)
,08-28 22:40:34.529  1725  4103 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-28 22:40:34.529  1725  4103 I SystemUpdateService: file has been verified
08-28 22:40:34.530  1725  4103 I SystemUpdateService: OTA package size = 12249756
,08-28 22:40:34.533  1725  4103 I SystemUpdateService: showing system update notification
,08-28 22:40:34.542  1725  1725 D SystemUpdateService: onDestroy
,08-28 22:40:39.224   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cfc845f:true
,08-28 22:40:39.225  3928  3928 D BluetoothAdapterState: make() - Creating AdapterState
,08-28 22:40:39.228  3928  3928 I bt_bluedroid: init
,08-28 22:40:39.230  3928  4112 I BluetoothAdapterState: Entering OffState
,08-28 22:40:39.234  3928  4113 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-28 22:40:39.234  3928  4113 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-28 22:40:39.235  3928  4113 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-28 22:40:39.235  3928  4113 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-28 22:40:39.237  3928  3928 I bt_bluedroid: get_profile_interface socket
,08-28 22:40:39.239  3928  3928 I bt_bluedroid: get_profile_interface sdp
,08-28 22:40:39.243  3928  4116 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-28 22:40:39.244  3928  3938 I bt_bluedroid: config_hci_snoop_log
08-28 22:40:39.246  3928  4116 D BluetoothAdapterProperties: Name is: Nexus 6
,08-28 22:40:39.248   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-28 22:40:39.258  3928  4112 D BluetoothAdapterState: Current state: OFF, message: 0
,08-28 22:40:39.259  3928  4112 D BluetoothAdapterProperties: Setting state to 14
08-28 22:40:39.259  3928  4112 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-28 22:40:39.265  3928  4112 D BluetoothBondStateMachine: make
,08-28 22:40:39.269  3928  4117 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-28 22:40:39.280  3928  3928 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-28 22:40:39.282  3928  4112 I BluetoothAdapterState: Entering PendingCommandState
,08-28 22:40:39.285  3928  3928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c6d6a2
08-28 22:40:39.286  3928  3928 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-28 22:40:39.287  3928  3928 D BtGatt.GattService: Received start request. Starting profile...
08-28 22:40:39.287  3928  3928 D BtGatt.GattService: start()
08-28 22:40:39.287  3928  3928 I bt_bluedroid: get_profile_interface gatt
,08-28 22:40:39.290  3928  3928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c6d6a2
08-28 22:40:39.290  3928  3928 D BtGatt.AdvertiseManager: advertise manager created
,08-28 22:40:39.305  3928  3928 V BluetoothAdapterState: isTurningOff()=false
,08-28 22:40:39.306  3928  3928 V BluetoothAdapterState: isTurningOn()=false
08-28 22:40:39.306  3928  3928 V BluetoothAdapterState: isBleTurningOn()=true
08-28 22:40:39.306  3928  3928 V BluetoothAdapterState: isBleTurningOff()=false
,08-28 22:40:39.309  3928  4112 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-28 22:40:39.310  3928  4112 I bt_bluedroid: enable
08-28 22:40:39.310  3928  4113 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-28 22:40:39.311  3928  4113 I bt_hci  : start_up
,08-28 22:40:39.333  3928  4113 I bt_vendor: alloc value 0xb3979189
08-28 22:40:39.333  3928  4113 I bt_vendor: init
,08-28 22:40:39.333  3928  4113 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-28 22:40:39.334  3928  4113 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-28 22:40:39.443  3928  4113 D bt_hci  : start_up starting async portion
,08-28 22:40:39.444  3928  4120 I bt_hci  : event_finish_startup
08-28 22:40:39.444  3928  4120 I bt_hci_h4: hal_open
08-28 22:40:39.444  3928  4120 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-28 22:40:39.453  3928  4120 I bt_userial_vendor: device fd = 51 open
,08-28 22:40:39.486  3928  4120 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-28 22:40:39.518  3928  4120 D bt_hwcfg: Chipset BCM4354A2
,08-28 22:40:39.518  3928  4120 D bt_hwcfg: Target name = [BCM4354A2]
08-28 22:40:39.519  3928  4120 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-28 22:40:39.721   875  1320 D ConnectivityService: handlePromptUnvalidated 101
,08-28 22:40:40.330  3928  4120 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-28 22:40:40.332  3928  4120 D bt_hwcfg: Settlement delay -- 100 ms
08-28 22:40:40.332  3928  4120 I bt_hwcfg: Setting fw settlement delay to 100 
,08-28 22:40:40.450  3928  4120 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-28 22:40:40.452  3928  4120 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-28 22:40:40.478  3928  4120 I bt_hwcfg: vendor lib fwcfg completed
,08-28 22:40:40.479  3928  4120 I bt_vendor: firmware callback
08-28 22:40:40.479  3928  4120 I bt_hci  : firmware_config_callback
,08-28 22:40:40.492  3928  4122 I bt_btu  : btu_task pending for preload complete event
08-28 22:40:40.492  3928  4122 I bt_btu_task: Bluetooth chip preload is complete
,08-28 22:40:40.493  3928  4122 I bt_btu  : btu_task received preload complete event
,08-28 22:40:40.503  3928  4122 I         : BTE_InitTraceLevels -- TRC_HCI
,08-28 22:40:40.504  3928  4122 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-28 22:40:40.504  3928  4122 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-28 22:40:40.504  3928  4122 I         : BTE_InitTraceLevels -- TRC_AVDT
08-28 22:40:40.504  3928  4122 I         : BTE_InitTraceLevels -- TRC_AVRC
08-28 22:40:40.505  3928  4122 I         : BTE_InitTraceLevels -- TRC_A2D
,08-28 22:40:40.505  3928  4122 I         : BTE_InitTraceLevels -- TRC_BNEP
08-28 22:40:40.505  3928  4122 I         : BTE_InitTraceLevels -- TRC_BTM
08-28 22:40:40.506  3928  4122 I         : BTE_InitTraceLevels -- TRC_GAP
,08-28 22:40:40.506  3928  4122 I         : BTE_InitTraceLevels -- TRC_PAN
08-28 22:40:40.506  3928  4122 I         : BTE_InitTraceLevels -- TRC_SDP
08-28 22:40:40.506  3928  4122 I         : BTE_InitTraceLevels -- TRC_GATT
08-28 22:40:40.507  3928  4122 I         : BTE_InitTraceLevels -- TRC_SMP
08-28 22:40:40.507  3928  4122 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-28 22:40:40.507  3928  4122 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-28 22:40:40.654  3928  4122 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38f6d9d
,08-28 22:40:40.654  3928  4122 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38f6d9d 
,08-28 22:40:40.666  3928  4116 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-28 22:40:40.667  3928  4116 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-28 22:40:40.668  3928  4116 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-28 22:40:40.671  3928  4116 D BluetoothAdapterProperties: Name is: Nexus 6
,08-28 22:40:40.674  3928  4116 D BluetoothAdapterProperties: Scan Mode:20
,08-28 22:40:40.675  3928  4116 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-28 22:40:40.675  3928  4116 D bt_hci  : do_postload posting postload work item
,08-28 22:40:40.676  3928  4120 I bt_hci  : event_postload
,08-28 22:40:40.676  3928  4120 I bt_vendor: sco_config_cb
08-28 22:40:40.676  3928  4120 I bt_hci  : sco_config_callback postload finished.
,08-28 22:40:40.681  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 22:40:40.682  3928  4116 D bt_bte_conf: Device ID record 1 : primary
08-28 22:40:40.683  3928  4116 D bt_bte_conf:   vendorId            = 000f
08-28 22:40:40.683  3928  4116 D bt_bte_conf:   vendorIdSource      = 0001
,08-28 22:40:40.683  3928  4116 D bt_bte_conf:   product             = 1200
,08-28 22:40:40.683  3928  4116 D bt_bte_conf:   version             = 1436
08-28 22:40:40.683  3928  4116 D bt_bte_conf:   clientExecutableURL = 
08-28 22:40:40.684  3928  4116 D bt_bte_conf:   serviceDescription  = 
08-28 22:40:40.684  3928  4116 D bt_bte_conf:   documentationURL    = 
08-28 22:40:40.684  3928  4116 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-28 22:40:40.685  3928  4113 D bt_stack_manager: event_start_up_stack finished
08-28 22:40:40.686  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 22:40:40.686  3928  4112 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-28 22:40:40.687  3928  4112 D BluetoothAdapterProperties: Setting state to 15
,08-28 22:40:40.687  3928  4112 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-28 22:40:40.689  3928  4112 I BluetoothAdapterState: Entering BleOnState
,08-28 22:40:40.693  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 22:40:40.695  3928  4120 I bt_vendor: low_power_mode_cb
,08-28 22:40:40.697  3928  4112 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-28 22:40:40.697  3928  4112 D BluetoothAdapterProperties: Setting state to 11
08-28 22:40:40.698  3928  4112 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-28 22:40:40.702  3928  3928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c6d6a2
08-28 22:40:40.703  3928  3928 D HeadsetService: Received start request. Starting profile...
,08-28 22:40:40.706  3928  3928 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-28 22:40:40.707  3928  3928 D HeadsetStateMachine: make
,08-28 22:40:40.719  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 22:40:40.724  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 22:40:40.726  3928  3928 D HeadsetStateMachine: max_hf_connections = 1
08-28 22:40:40.726  3928  3928 I bt_bluedroid: get_profile_interface handsfree
08-28 22:40:40.727  3928  4116 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-28 22:40:40.727  3928  4116 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
08-28 22:40:40.728  3928  4112 I BluetoothAdapterState: Entering PendingCommandState
,08-28 22:40:40.733  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 22:40:40.736  3928  3928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c6d6a2
,08-28 22:40:40.737  3928  3928 D A2dpService: Received start request. Starting profile...
,08-28 22:40:40.737  3928  3928 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-28 22:40:40.738  3928  3928 I bt_bluedroid: get_profile_interface avrcp
,08-28 22:40:40.747  3928  3928 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-28 22:40:40.748  3928  3928 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-28 22:40:40.748  3928  3928 D A2dpStateMachine: make
08-28 22:40:40.750  3928  3928 I bt_bluedroid: get_profile_interface a2dp
,08-28 22:40:40.751  3928  4116 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-28 22:40:40.752  3928  4131 D A2dpStateMachine: Enter Disconnected: -2
08-28 22:40:40.753  3928  3928 I BluetoothHidServiceJni: classInitNative: succeeds
08-28 22:40:40.754  3928  3928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c6d6a2
,08-28 22:40:40.756  3928  3928 D HidService: Received start request. Starting profile...
08-28 22:40:40.756  3875  3875 D BluetoothInputDevice: Proxy object connected
,08-28 22:40:40.756  3928  3928 I bt_bluedroid: get_profile_interface hidhost
,08-28 22:40:40.756  3928  3928 D HidService: setHidService(): set to: null
,08-28 22:40:40.756  3928  4116 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38d83e5
08-28 22:40:40.757  3928  3928 I BluetoothHealthServiceJni: classInitNative: succeeds
08-28 22:40:40.757  3928  4116 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-28 22:40:40.757  3928  3928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c6d6a2
08-28 22:40:40.758  3928  3928 D HealthService: Received start request. Starting profile...
08-28 22:40:40.760  3928  3928 I bt_bluedroid: get_profile_interface health
08-28 22:40:40.761  3928  3928 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-28 22:40:40.762  3928  3928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c6d6a2
08-28 22:40:40.764  3928  3928 D PanService: Received start request. Starting profile...
,08-28 22:40:40.764  3928  3928 D BluetoothPanServiceJni: initializeNative(L110): pan
08-28 22:40:40.764  3928  3928 I bt_bluedroid: get_profile_interface pan
08-28 22:40:40.765  3928  4116 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-28 22:40:40.768  3928  3928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c6d6a2
08-28 22:40:40.769  3928  3928 D BluetoothMapService: Received start request. Starting profile...
08-28 22:40:40.769  3928  3928 D BluetoothMapService: start()
,08-28 22:40:40.769  3875  3875 D HidProfile: Bluetooth service connected
,08-28 22:40:40.776  3928  3928 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-28 22:40:40.779  3928  3928 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-28 22:40:40.779  3928  3928 D BluetoothMapAppObserver: createReceiver()
,08-28 22:40:40.782  3928  3928 D BluetoothMapAppObserver: initObservers()
,08-28 22:40:40.782  3928  3928 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-28 22:40:40.788  3875  3875 D BluetoothPan: BluetoothPAN Proxy object connected
08-28 22:40:40.789  3875  3875 D PanProfile: Bluetooth service connected
,08-28 22:40:40.789  3875  3875 D BluetoothMap: Proxy object connected
08-28 22:40:40.790  3875  3875 D MapProfile: Bluetooth service connected
08-28 22:40:40.790  3875  3875 D BluetoothMap: getConnectedDevices()
08-28 22:40:40.791  3875  3875 D BluetoothMap: Bluetooth is Not enabled
,08-28 22:40:40.798  3928  3928 V BluetoothAdapterState: isTurningOff()=false
,08-28 22:40:40.798  3928  3928 V BluetoothAdapterState: isTurningOn()=true
08-28 22:40:40.798  3928  3928 V BluetoothAdapterState: isBleTurningOn()=false
08-28 22:40:40.798  3928  3928 V BluetoothAdapterState: isBleTurningOff()=false
,08-28 22:40:40.800  1527  1527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-28 22:40:40.801  3928  3928 V BluetoothAdapterState: isTurningOff()=false
08-28 22:40:40.801  3928  3928 V BluetoothAdapterState: isTurningOn()=true
08-28 22:40:40.801  3928  4129 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-28 22:40:40.801  3928  3928 V BluetoothAdapterState: isBleTurningOn()=false
08-28 22:40:40.801  3928  3928 V BluetoothAdapterState: isBleTurningOff()=false
08-28 22:40:40.802  3928  3928 V BluetoothAdapterState: isTurningOff()=false
08-28 22:40:40.802  3928  3928 V BluetoothAdapterState: isTurningOn()=true
08-28 22:40:40.802  3928  3928 V BluetoothAdapterState: isBleTurningOn()=false
08-28 22:40:40.802  3928  3928 V BluetoothAdapterState: isBleTurningOff()=false
08-28 22:40:40.802  3928  3928 V BluetoothAdapterState: isTurningOff()=false
,08-28 22:40:40.802  3928  3928 V BluetoothAdapterState: isTurningOn()=true
08-28 22:40:40.802  3928  3928 V BluetoothAdapterState: isBleTurningOn()=false
08-28 22:40:40.802  3928  3928 V BluetoothAdapterState: isBleTurningOff()=false
,08-28 22:40:40.803  3928  3928 V BluetoothAdapterState: isTurningOff()=false
,08-28 22:40:40.803  3928  3928 V BluetoothAdapterState: isTurningOn()=true
08-28 22:40:40.803  3928  3928 V BluetoothAdapterState: isBleTurningOn()=false
08-28 22:40:40.803  3928  3928 V BluetoothAdapterState: isBleTurningOff()=false
08-28 22:40:40.803  3928  3928 V BluetoothAdapterState: isTurningOff()=false
08-28 22:40:40.803  3928  3928 V BluetoothAdapterState: isTurningOn()=true
08-28 22:40:40.803  3928  3928 V BluetoothAdapterState: isBleTurningOn()=false
,08-28 22:40:40.803  3928  3928 V BluetoothAdapterState: isBleTurningOff()=false
08-28 22:40:40.803  3928  4112 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-28 22:40:40.804  3928  4112 D BluetoothAdapterProperties: ScanMode =  20
08-28 22:40:40.804  3928  4112 D BluetoothAdapterProperties: State =  11
08-28 22:40:40.804  3928  4112 D BluetoothAdapterProperties: Setting state to 12
08-28 22:40:40.804  3928  4112 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-28 22:40:40.805  1374  1396 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-28 22:40:40.806  3928  4116 D BluetoothAdapterProperties: Scan Mode:21
,08-28 22:40:40.806  3928  4116 D BluetoothAdapterProperties: Discoverable Timeout:120
08-28 22:40:40.806  1374  1398 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-28 22:40:40.806  3928  4112 I BluetoothAdapterState: Entering OnState
,08-28 22:40:40.810  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 22:40:40.810  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:40:40.810  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:40:40.810  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-28 22:40:40.810  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 22:40:40.810  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 22:40:40.810  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 22:40:40.810  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-28 22:40:40.813  3778  3778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-28 22:40:40.814  1374  1374 D BluetoothInputDevice: Proxy object connected
08-28 22:40:40.814  1374  1374 D HidProfile: Bluetooth service connected
08-28 22:40:40.816  1943  2078 D BluetoothHeadset: onBluetoothStateChange: up=true
08-28 22:40:40.816   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-28 22:40:40.817  3875  3888 D BluetoothMap: onBluetoothStateChange: up=true
,08-28 22:40:40.817  3875  3886 D BluetoothPan: onBluetoothStateChange on: true
08-28 22:40:40.817  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 22:40:40.817  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:40:40.817  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:40:40.817  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-28 22:40:40.817  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 22:40:40.817  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 22:40:40.817  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 22:40:40.817  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-28 22:40:40.818  1374  1396 D BluetoothMap: onBluetoothStateChange: up=true
,08-28 22:40:40.820   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-28 22:40:40.820  1374  1374 D BluetoothMap: Proxy object connected
08-28 22:40:40.820  1374  1374 D MapProfile: Bluetooth service connected
08-28 22:40:40.820  1374  1374 D BluetoothMap: getConnectedDevices()
08-28 22:40:40.820  3875  3888 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-28 22:40:40.821  1374  1398 D BluetoothA2dp: onBluetoothStateChange: up=true
08-28 22:40:40.821  3778  3778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-28 22:40:40.824  3928  3928 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-28 22:40:40.826  3928  3928 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-28 22:40:40.826  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 22:40:40.826  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:40:40.826  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:40:40.826  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-28 22:40:40.826  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 22:40:40.826  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 22:40:40.826  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 22:40:40.826  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-28 22:40:40.827  3875  3886 D BluetoothPbap: onBluetoothStateChange: up=true
,08-28 22:40:40.829  3778  3778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-28 22:40:40.830  3928  3928 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-28 22:40:40.830   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-28 22:40:40.831  1374  1396 D BluetoothPan: onBluetoothStateChange on: true
,08-28 22:40:40.832  1374  1374 D BluetoothPan: BluetoothPAN Proxy object connected
,08-28 22:40:40.832  1374  1374 D PanProfile: Bluetooth service connected
08-28 22:40:40.832  1374  1398 D BluetoothPbap: onBluetoothStateChange: up=true
,08-28 22:40:40.834   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-28 22:40:40.835   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
,08-28 22:40:40.837  3928  3928 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-28 22:40:40.838  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 22:40:40.839  3928  3928 D ObexServerSockets: Succeed to create listening sockets 
08-28 22:40:40.839  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 22:40:40.839  3928  3928 D ObexServerSockets0: startAccept()
08-28 22:40:40.839  3928  3928 D ObexServerSockets0: prepareForNewConnect()
,08-28 22:40:40.840  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 22:40:40.842  3928  3928 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-28 22:40:40.842  3928  3928 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-28 22:40:40.843   875   875 D BluetoothA2dp: Proxy object connected
,08-28 22:40:40.844  3928  4136 D ObexServerSockets0: Accepting socket connection...
08-28 22:40:40.844  3928  3928 D BluetoothMapService: onReceive
08-28 22:40:40.844  3928  3928 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-28 22:40:40.844  3928  3928 D BluetoothMapService: STATE_ON
08-28 22:40:40.845  3928  4137 D ObexServerSockets0: Accepting socket connection...
,08-28 22:40:40.846  3875  3875 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-28 22:40:40.850  3875  3875 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-28 22:40:40.857  3875  3875 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-28 22:40:40.860  3875  3875 D BluetoothA2dp: Proxy object connected
,08-28 22:40:40.861  1374  1374 D BluetoothA2dp: Proxy object connected
,08-28 22:40:40.864  1527  1527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-28 22:40:40.869  3875  3875 D DockEventReceiver: finishStartingService: stopping service
,08-28 22:40:40.872  1374  1374 D BluetoothPbap: Proxy object connected
,08-28 22:40:40.872  1374  1374 D PbapServerProfile: Bluetooth service connected
08-28 22:40:40.872  3875  3875 D BluetoothPbap: Proxy object connected
08-28 22:40:40.872  3928  3928 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-28 22:40:40.873  3875  3875 D PbapServerProfile: Bluetooth service connected
08-28 22:40:40.873  3928  3928 D ObexServerSockets0: prepareForNewConnect()
,08-28 22:40:40.881  3928  4142 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-28 22:40:40.898  3928  4146 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-28 22:40:40.899  3928  4146 I BtOppRfcommListener: Accept thread started.
,08-28 22:40:40.908   875   875 D BluetoothHeadset: Proxy object connected
,08-28 22:40:40.909  1374  1396 D BluetoothHeadset: Proxy object connected
08-28 22:40:40.909  1374  1374 D HeadsetProfile: Bluetooth service connected
08-28 22:40:40.910  1943  1956 D BluetoothHeadset: Proxy object connected
,08-28 22:40:40.910   875   875 D BluetoothHeadset: Proxy object connected
,08-28 22:40:40.910   875   875 D BluetoothHeadset: Proxy object connected
,08-28 22:40:40.917  1943  2224 D BluetoothHeadset: Proxy object connected
08-28 22:40:40.917   875   892 D BluetoothHeadset: Proxy object connected
,08-28 22:40:40.920   875   892 D BluetoothHeadset: Proxy object connected
,08-28 22:40:40.931   875   892 D BluetoothHeadset: Proxy object connected
,08-28 22:40:40.954  3875  3888 D BluetoothHeadset: Proxy object connected
,08-28 22:40:40.955  3875  3875 D HeadsetProfile: Bluetooth service connected
,08-28 22:40:44.192  3928  4112 D BluetoothAdapterState: Current state: ON, message: 23
08-28 22:40:44.193  3928  4112 D BluetoothAdapterProperties: Setting state to 13
,08-28 22:40:44.193  3928  4112 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-28 22:40:44.195  3928  4112 D BluetoothAdapterProperties: onBluetoothDisable()
,08-28 22:40:44.203  3928  3928 D BluetoothMapService: onReceive
,08-28 22:40:44.203  3928  3928 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-28 22:40:44.204  3928  3928 D BluetoothMapService: STATE_TURNING_OFF
08-28 22:40:44.204  3928  3928 D BluetoothMapService: MAP Service closeService in
,08-28 22:40:44.205  3928  3928 D BluetoothMapMasInstance0: MAP Service shutdown
,08-28 22:40:44.207  3928  3928 D ObexServerSockets0: shutdown(block = true)
08-28 22:40:44.209  3928  4136 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-28 22:40:44.209  3928  4112 I BluetoothAdapterState: Entering PendingCommandState
08-28 22:40:44.213  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 22:40:44.213  3928  3928 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-28 22:40:44.213  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 22:40:44.213  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:40:44.213  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:40:44.213  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-28 22:40:44.213  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 22:40:44.213  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 22:40:44.213  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 22:40:44.213  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-28 22:40:44.214  3928  4137 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-28 22:40:44.216  3928  3928 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-28 22:40:44.216  3928  4124 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-28 22:40:44.217  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 22:40:44.217  3778  3778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-28 22:40:44.217  3928  3928 I BtOppRfcommListener: stopping Accept Thread
08-28 22:40:44.218  3928  4146 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-28 22:40:44.220  3928  4146 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-28 22:40:44.223  3928  4116 D BluetoothAdapterProperties: Scan Mode:20
08-28 22:40:44.223  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 22:40:44.223  3928  4112 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-28 22:40:44.223  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 22:40:44.223  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:40:44.223  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:40:44.223  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-28 22:40:44.223  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 22:40:44.223  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 22:40:44.223  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 22:40:44.223  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-28 22:40:44.225  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-28 22:40:44.225  3778  3778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-28 22:40:44.229  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 22:40:44.229  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 22:40:44.229  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:40:44.229  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:40:44.229  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-28 22:40:44.229  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 22:40:44.229  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 22:40:44.229  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 22:40:44.229  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-28 22:40:44.229  3875  3875 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-28 22:40:44.229  3928  3928 D HeadsetService: Received stop request...Stopping profile...
08-28 22:40:44.230  3778  3778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 22:40:44.230  3778  3778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-28 22:40:44.232  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 22:40:44.233  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 22:40:44.234  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 22:40:44.235   875   875 D BluetoothHeadset: Proxy object disconnected
,08-28 22:40:44.235  1374  1396 D BluetoothHeadset: Proxy object disconnected
08-28 22:40:44.235  1374  1374 D HeadsetProfile: Bluetooth service disconnected
08-28 22:40:44.236  3875  3888 D BluetoothHeadset: Proxy object disconnected
08-28 22:40:44.236  3928  3928 D A2dpService: Received stop request...Stopping profile...
,08-28 22:40:44.236  3928  4131 D A2dpStateMachine: Exit Disconnected: -1
08-28 22:40:44.236  1943  2078 D BluetoothHeadset: Proxy object disconnected
08-28 22:40:44.236   875   875 D BluetoothHeadset: Proxy object disconnected
08-28 22:40:44.236   875   875 D BluetoothHeadset: Proxy object disconnected
08-28 22:40:44.238   875   875 D BluetoothA2dp: Proxy object disconnected
,08-28 22:40:44.239  1374  1374 D BluetoothA2dp: Proxy object disconnected
08-28 22:40:44.239  3928  3928 D HidService: Received stop request...Stopping profile...
08-28 22:40:44.240  3928  3928 D HidService: Stopping Bluetooth HidService
08-28 22:40:44.240  1374  1374 D BluetoothInputDevice: Proxy object disconnected
,08-28 22:40:44.240  1374  1374 D HidProfile: Bluetooth service disconnected
08-28 22:40:44.241  3928  3928 D HealthService: Received stop request...Stopping profile...
,08-28 22:40:44.242  3928  3928 D PanService: Received stop request...Stopping profile...
,08-28 22:40:44.243  3875  3875 D DockEventReceiver: finishStartingService: stopping service
,08-28 22:40:44.244  1374  1374 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-28 22:40:44.244  1374  1374 D PanProfile: Bluetooth service disconnected
08-28 22:40:44.244  3875  3875 D HeadsetProfile: Bluetooth service disconnected
,08-28 22:40:44.244  3928  3928 D BluetoothMapService: Received stop request...Stopping profile...
08-28 22:40:44.244  3928  3928 D BluetoothMapService: stop()
08-28 22:40:44.244  3875  3875 D BluetoothA2dp: Proxy object disconnected
08-28 22:40:44.245  3875  3875 D BluetoothInputDevice: Proxy object disconnected
,08-28 22:40:44.245  3928  3928 D BluetoothMapAppObserver: deinitObservers()
08-28 22:40:44.245  3875  3875 D HidProfile: Bluetooth service disconnected
08-28 22:40:44.245  3928  3928 D BluetoothMapAppObserver: removeReceiver()
,08-28 22:40:44.247  3875  3875 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-28 22:40:44.247  3875  3875 D PanProfile: Bluetooth service disconnected
08-28 22:40:44.248  1374  1374 D BluetoothMap: Proxy object disconnected
,08-28 22:40:44.248  3875  3875 D BluetoothMap: Proxy object disconnected
08-28 22:40:44.248  3928  3928 V BluetoothAdapterState: isTurningOff()=true
08-28 22:40:44.249  3875  3875 D MapProfile: Bluetooth service disconnected
,08-28 22:40:44.249  3928  3928 V BluetoothAdapterState: isTurningOn()=false
08-28 22:40:44.249  3928  3928 V BluetoothAdapterState: isBleTurningOn()=false
08-28 22:40:44.249  3928  3928 V BluetoothAdapterState: isBleTurningOff()=false
08-28 22:40:44.248  1374  1374 D MapProfile: Bluetooth service disconnected
08-28 22:40:44.250  3928  3928 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-28 22:40:44.250  3928  3928 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-28 22:40:44.250  3928  4116 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-28 22:40:44.251  3928  4122 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-28 22:40:44.251  3928  4122 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-28 22:40:44.251  3928  4122 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-28 22:40:44.251  3928  4116 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-28 22:40:44.252  3928  3928 V BluetoothAdapterState: isTurningOff()=true
,08-28 22:40:44.252  3928  3928 V BluetoothAdapterState: isTurningOn()=false
,08-28 22:40:44.252  3928  3928 V BluetoothAdapterState: isBleTurningOn()=false
08-28 22:40:44.252  3928  3928 V BluetoothAdapterState: isBleTurningOff()=false
08-28 22:40:44.256  3928  4122 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-28 22:40:44.256  3928  3928 V BluetoothAdapterState: isTurningOff()=true
08-28 22:40:44.256  3928  4122 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-28 22:40:44.256  3928  3928 V BluetoothAdapterState: isTurningOn()=false
08-28 22:40:44.256  3928  3928 V BluetoothAdapterState: isBleTurningOn()=false
,08-28 22:40:44.256  3928  4122 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-28 22:40:44.256  3928  4122 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-28 22:40:44.256  3928  3928 V BluetoothAdapterState: isBleTurningOff()=false
08-28 22:40:44.256  3928  4122 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-28 22:40:44.256  3928  4122 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-28 22:40:44.256  1527  1527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-28 22:40:44.257  3928  4116 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-28 22:40:44.257  3928  3928 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-28 22:40:44.257  3928  3928 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-28 22:40:44.257  3928  4116 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-28 22:40:44.257  3928  3928 V BluetoothAdapterState: isTurningOff()=true
08-28 22:40:44.257  3928  3928 V BluetoothAdapterState: isTurningOn()=false
08-28 22:40:44.257  3928  3928 V BluetoothAdapterState: isBleTurningOn()=false
,08-28 22:40:44.259  3928  3928 V BluetoothAdapterState: isBleTurningOff()=false
08-28 22:40:44.259  3928  3928 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-28 22:40:44.259  3928  4116 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-28 22:40:44.259  3928  3928 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-28 22:40:44.260  3928  3928 V BluetoothAdapterState: isTurningOff()=true
08-28 22:40:44.260  3928  3928 V BluetoothAdapterState: isTurningOn()=false
08-28 22:40:44.260  3928  3928 V BluetoothAdapterState: isBleTurningOn()=false
08-28 22:40:44.260  3928  3928 V BluetoothAdapterState: isBleTurningOff()=false
08-28 22:40:44.260  3928  3928 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-28 22:40:44.260  3928  3928 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-28 22:40:44.261  3928  3928 D BluetoothMapService: MAP Service closeService in
08-28 22:40:44.261  3928  3928 V BluetoothAdapterState: isTurningOff()=true
08-28 22:40:44.261  3928  3928 V BluetoothAdapterState: isTurningOn()=false
08-28 22:40:44.261  3928  3928 V BluetoothAdapterState: isBleTurningOn()=false
08-28 22:40:44.261  3928  3928 V BluetoothAdapterState: isBleTurningOff()=false
08-28 22:40:44.262  3928  4112 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-28 22:40:44.262  3928  4112 D BluetoothAdapterProperties: Setting state to 15
08-28 22:40:44.262  3928  4112 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-28 22:40:44.262  3928  4112 I BluetoothAdapterState: Entering BleOnState
08-28 22:40:44.263  1374  1396 D BluetoothHeadset: onBluetoothStateChange: up=false
08-28 22:40:44.262  3928  3928 D BluetoothMapService: cleanup()
08-28 22:40:44.263  3928  3928 D BluetoothMapService: MAP Service closeService in
08-28 22:40:44.263  1374  1398 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-28 22:40:44.264  1943  1956 D BluetoothHeadset: onBluetoothStateChange: up=false
08-28 22:40:44.264   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-28 22:40:44.264  3875  3886 D BluetoothMap: onBluetoothStateChange: up=false
08-28 22:40:44.265  3875  3888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-28 22:40:44.265  3875  3886 D BluetoothPan: onBluetoothStateChange on: false
08-28 22:40:44.266  1374  1374 D BluetoothPbap: Proxy object disconnected
,08-28 22:40:44.266  1374  1374 D PbapServerProfile: Bluetooth service disconnected
,08-28 22:40:44.269  3875  3888 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-28 22:40:44.269  1374  1398 D BluetoothMap: onBluetoothStateChange: up=false
,08-28 22:40:44.270   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-28 22:40:44.270  3875  3886 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-28 22:40:44.270  1374  2079 D BluetoothA2dp: onBluetoothStateChange: up=false
08-28 22:40:44.271  3875  3888 D BluetoothPbap: onBluetoothStateChange: up=false
,08-28 22:40:44.279   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-28 22:40:44.280  1374  1396 D BluetoothPan: onBluetoothStateChange on: false
,08-28 22:40:44.280  1374  1398 D BluetoothPbap: onBluetoothStateChange: up=false
08-28 22:40:44.281   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
08-28 22:40:44.281  3928  4112 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-28 22:40:44.281  3928  4112 D BluetoothAdapterProperties: Setting state to 16
,08-28 22:40:44.281  3928  4112 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-28 22:40:44.284  3928  4112 D BluetoothAdapterProperties: onBleDisable
,08-28 22:40:44.284  3928  4112 I BluetoothAdapterState: Entering PendingCommandState
08-28 22:40:44.284  3928  4113 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-28 22:40:44.285  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 22:40:44.286  3928  4122 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-28 22:40:44.286  3928  4122 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-28 22:40:44.286  3928  4116 D BluetoothAdapterProperties: Scan Mode:20
08-28 22:40:44.286  3875  3875 D BluetoothPbap: Proxy object disconnected
08-28 22:40:44.287  3875  3875 D PbapServerProfile: Bluetooth service disconnected
08-28 22:40:44.287  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 22:40:44.288  3875  3875 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-28 22:40:44.288  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 22:40:44.290  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 22:40:44.291  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 22:40:44.292  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 22:40:44.311  1527  1527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-28 22:40:44.316  3875  3875 D DockEventReceiver: finishStartingService: stopping service
,08-28 22:40:44.489  3928  4116 I bt_hci  : shut_down
,08-28 22:40:44.489  3928  4120 D bt_hwcfg: hw_epilog_process
08-28 22:40:44.491  3928  4120 I bt_vendor: low_power_mode_cb
,08-28 22:40:44.521  3928  4120 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-28 22:40:44.521  3928  4120 I bt_vendor: epilog_cb
08-28 22:40:44.522  3928  4120 I bt_hci  : epilog_finished_callback
,08-28 22:40:44.530  3928  4116 I bt_hci_h4: hal_close
,08-28 22:40:44.532  3928  4116 I bt_userial_vendor: device fd = 51 close
,08-28 22:40:44.656  3928  4113 D bt_stack_manager: event_shut_down_stack finished.
,08-28 22:40:44.657  3928  4112 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-28 22:40:44.664  3928  4112 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-28 22:40:44.664  3928  3928 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-28 22:40:44.666  3928  3928 D BtGatt.GattService: Received stop request...Stopping profile...
,08-28 22:40:44.667  3928  3928 D BtGatt.GattService: stop()
08-28 22:40:44.668  3928  3928 D BtGatt.AdvertiseManager: advertise clients cleared
,08-28 22:40:44.675  3928  3928 V BluetoothAdapterState: isTurningOff()=false
,08-28 22:40:44.675  3928  3928 V BluetoothAdapterState: isTurningOn()=false
08-28 22:40:44.676  3928  3928 V BluetoothAdapterState: isBleTurningOn()=false
08-28 22:40:44.676  3928  3928 V BluetoothAdapterState: isBleTurningOff()=true
,08-28 22:40:44.678  3928  4112 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-28 22:40:44.678  3928  4112 D BluetoothAdapterProperties: Setting state to 10
,08-28 22:40:44.679  3928  4112 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-28 22:40:44.682  3928  4112 I BluetoothAdapterState: Entering OffState
08-28 22:40:44.683   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-28 22:40:44.713  3928  3928 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-28 22:40:44.713  3928  3928 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-28 22:40:44.714  3928  4113 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-28 22:40:44.722  3928  4113 D bt_stack_manager: event_clean_up_stack finished.
,08-28 22:40:44.723  3928  3928 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-28 22:40:44.729  3928  3928 I art     : System.exit called, status: 0
,08-28 22:40:44.729  3928  3928 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-28 22:40:44.799   875  1541 I ActivityManager: Process com.android.bluetooth (pid 3928) has died
,08-28 22:40:46.216  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 22:40:46.238  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 22:40:46.242  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 22:40:46.300  1527  1538 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-28 22:40:46.301  1527  1538 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-28 22:40:46.301  1527  1538 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-28 22:40:46.301  1527  1538 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 22:40:46.369  3506  3506 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-28 22:40:46.372  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-28 22:40:46.374  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-28 22:40:49.190  3778  3828 D io.jxcore.node.ConnectivityMonitor: stop
08-28 22:40:49.190  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 22:40:49.195  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-28 22:40:49.196  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6104d47 removed from the list
08-28 22:40:49.196  3778  3828 D io.jxcore.node.ConnectivityMonitor: stop
08-28 22:40:49.196  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:49.197  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 22:40:49.202  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-28 22:40:49.202  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3f67e9d added. We now have 4 listener(s)
08-28 22:40:49.203  3778  3828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-28 22:40:49.205  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-28 22:40:49.205  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3f67e9d removed from the list
08-28 22:40:49.206  3778  3828 D io.jxcore.node.ConnectivityMonitor: stop
08-28 22:40:49.206  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:49.207  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 22:40:49.209  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-28 22:40:49.210  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4f5ef12 added. We now have 4 listener(s)
08-28 22:40:49.210  3778  3828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-28 22:40:54.223  3778  3828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 22:40:54.270   875   892 I ActivityManager: Start proc 4158:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-28 22:40:54.425  4158  4158 D AdapterServiceConfig: Adding HeadsetService
08-28 22:40:54.425  4158  4158 D AdapterServiceConfig: Adding A2dpService
,08-28 22:40:54.425  4158  4158 D AdapterServiceConfig: Adding HidService
08-28 22:40:54.426  4158  4158 D AdapterServiceConfig: Adding HealthService
08-28 22:40:54.426  4158  4158 D AdapterServiceConfig: Adding PanService
,08-28 22:40:54.426  4158  4158 D AdapterServiceConfig: Adding GattService
08-28 22:40:54.426  4158  4158 D AdapterServiceConfig: Adding BluetoothMapService
,08-28 22:40:54.439   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ef451ed:true
,08-28 22:40:54.440  4158  4158 D BluetoothAdapterState: make() - Creating AdapterState
,08-28 22:40:54.448  4158  4158 I bt_bluedroid: init
08-28 22:40:54.448  4158  4170 I BluetoothAdapterState: Entering OffState
,08-28 22:40:54.456  4158  4171 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-28 22:40:54.456  4158  4171 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-28 22:40:54.456  4158  4171 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-28 22:40:54.457  4158  4171 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-28 22:40:54.459  4158  4158 I bt_bluedroid: get_profile_interface socket
,08-28 22:40:54.465  4158  4158 I bt_bluedroid: get_profile_interface sdp
,08-28 22:40:54.467  4158  4174 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-28 22:40:54.470  4158  4174 D BluetoothAdapterProperties: Name is: Nexus 6
,08-28 22:40:54.472  4158  4169 I bt_bluedroid: config_hci_snoop_log
,08-28 22:40:54.475   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-28 22:40:54.488  4158  4170 D BluetoothAdapterState: Current state: OFF, message: 0
08-28 22:40:54.488  4158  4170 D BluetoothAdapterProperties: Setting state to 14
08-28 22:40:54.488  4158  4170 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-28 22:40:54.490  4158  4170 D BluetoothBondStateMachine: make
,08-28 22:40:54.494  4158  4175 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-28 22:40:54.500  4158  4170 I BluetoothAdapterState: Entering PendingCommandState
,08-28 22:40:54.502  4158  4158 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-28 22:40:54.510  4158  4158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c6d6a2
,08-28 22:40:54.512  4158  4158 D BtGatt.DebugUtils: handleDebugAction() action=null
08-28 22:40:54.513  4158  4158 D BtGatt.GattService: Received start request. Starting profile...
,08-28 22:40:54.513  4158  4158 D BtGatt.GattService: start()
08-28 22:40:54.514  4158  4158 I bt_bluedroid: get_profile_interface gatt
,08-28 22:40:54.516  4158  4158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c6d6a2
08-28 22:40:54.516  4158  4158 D BtGatt.AdvertiseManager: advertise manager created
,08-28 22:40:54.528  4158  4158 V BluetoothAdapterState: isTurningOff()=false
,08-28 22:40:54.528  4158  4158 V BluetoothAdapterState: isTurningOn()=false
08-28 22:40:54.528  4158  4158 V BluetoothAdapterState: isBleTurningOn()=true
08-28 22:40:54.528  4158  4158 V BluetoothAdapterState: isBleTurningOff()=false
08-28 22:40:54.529  4158  4170 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-28 22:40:54.529  4158  4170 I bt_bluedroid: enable
08-28 22:40:54.530  4158  4171 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-28 22:40:54.531  4158  4171 I bt_hci  : start_up
,08-28 22:40:54.546  4158  4171 I bt_vendor: alloc value 0xb39e4189
,08-28 22:40:54.546  4158  4171 I bt_vendor: init
08-28 22:40:54.546  4158  4171 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-28 22:40:54.546  4158  4171 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-28 22:40:54.655  4158  4171 D bt_hci  : start_up starting async portion
,08-28 22:40:54.655  4158  4178 I bt_hci  : event_finish_startup
08-28 22:40:54.656  4158  4178 I bt_hci_h4: hal_open
08-28 22:40:54.656  4158  4178 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-28 22:40:54.668  4158  4178 I bt_userial_vendor: device fd = 51 open
,08-28 22:40:54.697  4158  4178 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-28 22:40:54.729  4158  4178 D bt_hwcfg: Chipset BCM4354A2
08-28 22:40:54.729  4158  4178 D bt_hwcfg: Target name = [BCM4354A2]
,08-28 22:40:54.730  4158  4178 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-28 22:40:55.626  4158  4178 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-28 22:40:55.628  4158  4178 D bt_hwcfg: Settlement delay -- 100 ms
08-28 22:40:55.628  4158  4178 I bt_hwcfg: Setting fw settlement delay to 100 
,08-28 22:40:55.746  4158  4178 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-28 22:40:55.748  4158  4178 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-28 22:40:55.776  4158  4178 I bt_hwcfg: vendor lib fwcfg completed
,08-28 22:40:55.776  4158  4178 I bt_vendor: firmware callback
08-28 22:40:55.776  4158  4178 I bt_hci  : firmware_config_callback
,08-28 22:40:55.789  4158  4180 I bt_btu  : btu_task pending for preload complete event
,08-28 22:40:55.789  4158  4180 I bt_btu_task: Bluetooth chip preload is complete
08-28 22:40:55.789  4158  4180 I bt_btu  : btu_task received preload complete event
,08-28 22:40:55.802  4158  4180 I         : BTE_InitTraceLevels -- TRC_HCI
,08-28 22:40:55.802  4158  4180 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-28 22:40:55.802  4158  4180 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-28 22:40:55.802  4158  4180 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-28 22:40:55.803  4158  4180 I         : BTE_InitTraceLevels -- TRC_AVRC
08-28 22:40:55.803  4158  4180 I         : BTE_InitTraceLevels -- TRC_A2D
,08-28 22:40:55.803  4158  4180 I         : BTE_InitTraceLevels -- TRC_BNEP
08-28 22:40:55.803  4158  4180 I         : BTE_InitTraceLevels -- TRC_BTM
08-28 22:40:55.804  4158  4180 I         : BTE_InitTraceLevels -- TRC_GAP
08-28 22:40:55.805  4158  4180 I         : BTE_InitTraceLevels -- TRC_PAN
,08-28 22:40:55.806  4158  4180 I         : BTE_InitTraceLevels -- TRC_SDP
,08-28 22:40:55.806  4158  4180 I         : BTE_InitTraceLevels -- TRC_GATT
08-28 22:40:55.806  4158  4180 I         : BTE_InitTraceLevels -- TRC_SMP
08-28 22:40:55.807  4158  4180 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-28 22:40:55.807  4158  4180 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-28 22:40:55.946  4158  4180 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3961d9d
,08-28 22:40:55.946  4158  4180 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3961d9d 
,08-28 22:40:55.967  4158  4174 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-28 22:40:55.968  4158  4174 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-28 22:40:55.969  4158  4174 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-28 22:40:55.973  4158  4174 D BluetoothAdapterProperties: Name is: Nexus 6
,08-28 22:40:55.980  4158  4174 D BluetoothAdapterProperties: Scan Mode:20
,08-28 22:40:55.981  4158  4174 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-28 22:40:55.982  4158  4174 D bt_hci  : do_postload posting postload work item
,08-28 22:40:55.983  4158  4178 I bt_hci  : event_postload
08-28 22:40:55.983  4158  4178 I bt_vendor: sco_config_cb
08-28 22:40:55.983  4158  4178 I bt_hci  : sco_config_callback postload finished.
,08-28 22:40:55.985  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 22:40:55.986  4158  4174 D bt_bte_conf: Device ID record 1 : primary
,08-28 22:40:55.986  4158  4174 D bt_bte_conf:   vendorId            = 000f
,08-28 22:40:55.986  4158  4174 D bt_bte_conf:   vendorIdSource      = 0001
,08-28 22:40:55.986  4158  4174 D bt_bte_conf:   product             = 1200
,08-28 22:40:55.986  4158  4174 D bt_bte_conf:   version             = 1436
08-28 22:40:55.987  4158  4174 D bt_bte_conf:   clientExecutableURL = 
,08-28 22:40:55.987  4158  4174 D bt_bte_conf:   serviceDescription  = 
08-28 22:40:55.987  4158  4174 D bt_bte_conf:   documentationURL    = 
08-28 22:40:55.987  4158  4174 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-28 22:40:55.987  4158  4171 D bt_stack_manager: event_start_up_stack finished
08-28 22:40:55.987  4158  4170 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-28 22:40:55.987  4158  4170 D BluetoothAdapterProperties: Setting state to 15
08-28 22:40:55.988  4158  4170 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-28 22:40:55.989  4158  4170 I BluetoothAdapterState: Entering BleOnState
08-28 22:40:55.992  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 22:40:55.994  4158  4170 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-28 22:40:55.994  4158  4170 D BluetoothAdapterProperties: Setting state to 11
08-28 22:40:55.994  4158  4170 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-28 22:40:55.996  4158  4178 I bt_vendor: low_power_mode_cb
08-28 22:40:56.002  4158  4158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c6d6a2
08-28 22:40:56.003  4158  4158 D HeadsetService: Received start request. Starting profile...
08-28 22:40:56.008  4158  4158 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-28 22:40:56.008  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 22:40:56.008  4158  4158 D HeadsetStateMachine: make
08-28 22:40:56.011  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 22:40:56.019  4158  4158 D HeadsetStateMachine: max_hf_connections = 1
08-28 22:40:56.020  4158  4158 I bt_bluedroid: get_profile_interface handsfree
,08-28 22:40:56.020  4158  4174 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-28 22:40:56.020  4158  4174 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
08-28 22:40:56.022  4158  4170 I BluetoothAdapterState: Entering PendingCommandState
,08-28 22:40:56.026  4158  4158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c6d6a2
,08-28 22:40:56.026  4158  4158 D A2dpService: Received start request. Starting profile...
08-28 22:40:56.027  4158  4158 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-28 22:40:56.027  4158  4158 I bt_bluedroid: get_profile_interface avrcp
,08-28 22:40:56.032  4158  4158 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-28 22:40:56.032  4158  4158 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-28 22:40:56.033  4158  4158 D A2dpStateMachine: make
08-28 22:40:56.034  4158  4158 I bt_bluedroid: get_profile_interface a2dp
,08-28 22:40:56.034  4158  4174 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-28 22:40:56.035  4158  4189 D A2dpStateMachine: Enter Disconnected: -2
,08-28 22:40:56.036  4158  4158 I BluetoothHidServiceJni: classInitNative: succeeds
08-28 22:40:56.037  4158  4158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c6d6a2
,08-28 22:40:56.038  4158  4158 D HidService: Received start request. Starting profile...
08-28 22:40:56.038  4158  4158 I bt_bluedroid: get_profile_interface hidhost
,08-28 22:40:56.038  4158  4158 D HidService: setHidService(): set to: null
08-28 22:40:56.038  4158  4174 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39433e5
08-28 22:40:56.038  4158  4174 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-28 22:40:56.038  4158  4158 I BluetoothHealthServiceJni: classInitNative: succeeds
08-28 22:40:56.039  4158  4158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c6d6a2
,08-28 22:40:56.040  4158  4158 D HealthService: Received start request. Starting profile...
,08-28 22:40:56.041  4158  4158 I bt_bluedroid: get_profile_interface health
08-28 22:40:56.041  4158  4158 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-28 22:40:56.042  4158  4158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c6d6a2
08-28 22:40:56.043  4158  4158 D PanService: Received start request. Starting profile...
08-28 22:40:56.043  4158  4158 D BluetoothPanServiceJni: initializeNative(L110): pan
08-28 22:40:56.043  4158  4158 I bt_bluedroid: get_profile_interface pan
08-28 22:40:56.043  4158  4174 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-28 22:40:56.048  4158  4158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c6d6a2
,08-28 22:40:56.048  1527  1527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-28 22:40:56.049  4158  4158 D BluetoothMapService: Received start request. Starting profile...
08-28 22:40:56.049  4158  4158 D BluetoothMapService: start()
08-28 22:40:56.051  4158  4158 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-28 22:40:56.052  4158  4158 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-28 22:40:56.052  4158  4158 D BluetoothMapAppObserver: createReceiver()
08-28 22:40:56.053  4158  4158 D BluetoothMapAppObserver: initObservers()
08-28 22:40:56.053  4158  4158 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-28 22:40:56.058  4158  4158 V BluetoothAdapterState: isTurningOff()=false
08-28 22:40:56.058  4158  4158 V BluetoothAdapterState: isTurningOn()=true
,08-28 22:40:56.058  4158  4158 V BluetoothAdapterState: isBleTurningOn()=false
08-28 22:40:56.058  4158  4158 V BluetoothAdapterState: isBleTurningOff()=false
,08-28 22:40:56.060  4158  4158 V BluetoothAdapterState: isTurningOff()=false
08-28 22:40:56.060  4158  4158 V BluetoothAdapterState: isTurningOn()=true
08-28 22:40:56.060  4158  4158 V BluetoothAdapterState: isBleTurningOn()=false
08-28 22:40:56.060  4158  4158 V BluetoothAdapterState: isBleTurningOff()=false
08-28 22:40:56.060  4158  4187 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-28 22:40:56.060  4158  4158 V BluetoothAdapterState: isTurningOff()=false
08-28 22:40:56.060  4158  4158 V BluetoothAdapterState: isTurningOn()=true
08-28 22:40:56.061  4158  4158 V BluetoothAdapterState: isBleTurningOn()=false
,08-28 22:40:56.061  4158  4158 V BluetoothAdapterState: isBleTurningOff()=false
08-28 22:40:56.061  4158  4158 V BluetoothAdapterState: isTurningOff()=false
08-28 22:40:56.061  4158  4158 V BluetoothAdapterState: isTurningOn()=true
,08-28 22:40:56.061  4158  4158 V BluetoothAdapterState: isBleTurningOn()=false
08-28 22:40:56.061  4158  4158 V BluetoothAdapterState: isBleTurningOff()=false
08-28 22:40:56.061  4158  4158 V BluetoothAdapterState: isTurningOff()=false
,08-28 22:40:56.061  4158  4158 V BluetoothAdapterState: isTurningOn()=true
08-28 22:40:56.061  4158  4158 V BluetoothAdapterState: isBleTurningOn()=false
08-28 22:40:56.061  4158  4158 V BluetoothAdapterState: isBleTurningOff()=false
08-28 22:40:56.062  4158  4158 V BluetoothAdapterState: isTurningOff()=false
,08-28 22:40:56.062  4158  4158 V BluetoothAdapterState: isTurningOn()=true
,08-28 22:40:56.062  4158  4158 V BluetoothAdapterState: isBleTurningOn()=false
08-28 22:40:56.062  4158  4158 V BluetoothAdapterState: isBleTurningOff()=false
08-28 22:40:56.063  4158  4170 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-28 22:40:56.063  4158  4170 D BluetoothAdapterProperties: ScanMode =  20
08-28 22:40:56.063  4158  4170 D BluetoothAdapterProperties: State =  11
08-28 22:40:56.063  4158  4170 D BluetoothAdapterProperties: Setting state to 12
08-28 22:40:56.063  4158  4170 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-28 22:40:56.064  4158  4170 I BluetoothAdapterState: Entering OnState
08-28 22:40:56.064  1374  2079 D BluetoothHeadset: onBluetoothStateChange: up=true
08-28 22:40:56.064  1374  1396 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-28 22:40:56.068  1943  2078 D BluetoothHeadset: onBluetoothStateChange: up=true
08-28 22:40:56.068  4158  4174 D BluetoothAdapterProperties: Scan Mode:21
08-28 22:40:56.068  4158  4174 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-28 22:40:56.069  1374  1374 D BluetoothInputDevice: Proxy object connected
08-28 22:40:56.069  1374  1374 D HidProfile: Bluetooth service connected
08-28 22:40:56.069   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-28 22:40:56.069  3875  3888 D BluetoothMap: onBluetoothStateChange: up=true
08-28 22:40:56.071  3875  4150 D BluetoothHeadset: onBluetoothStateChange: up=true
08-28 22:40:56.072  3875  3886 D BluetoothPan: onBluetoothStateChange on: true
08-28 22:40:56.073  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 22:40:56.073  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:40:56.073  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:40:56.073  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-28 22:40:56.073  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 22:40:56.073  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 22:40:56.073  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 22:40:56.073  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-28 22:40:56.075  3778  3778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-28 22:40:56.075  3875  3888 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-28 22:40:56.077  1374  2079 D BluetoothMap: onBluetoothStateChange: up=true
,08-28 22:40:56.077  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 22:40:56.077  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:40:56.077  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:40:56.077  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-28 22:40:56.077  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 22:40:56.077  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 22:40:56.077  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 22:40:56.077  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-28 22:40:56.079  1374  1374 D BluetoothMap: Proxy object connected
,08-28 22:40:56.079   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-28 22:40:56.079  1374  1374 D MapProfile: Bluetooth service connected
08-28 22:40:56.079  1374  1374 D BluetoothMap: getConnectedDevices()
08-28 22:40:56.079  4158  4158 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-28 22:40:56.079  3875  3886 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-28 22:40:56.079  3778  3778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-28 22:40:56.079  4158  4158 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-28 22:40:56.081  1374  1398 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-28 22:40:56.081  3875  3875 D BluetoothMap: Proxy object connected
,08-28 22:40:56.081  3875  3875 D MapProfile: Bluetooth service connected
08-28 22:40:56.081  3875  3875 D BluetoothMap: getConnectedDevices(),
,08-28 22:40:56.081  4158  4158 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-28 22:40:56.082  1374  1374 D BluetoothA2dp: Proxy object connected
08-28 22:40:56.083  3875  4150 D BluetoothPbap: onBluetoothStateChange: up=true
08-28 22:40:56.083  3875  3875 D BluetoothPan: BluetoothPAN Proxy object connected
,08-28 22:40:56.083  3875  3875 D PanProfile: Bluetooth service connected
08-28 22:40:56.084  3875  3875 D BluetoothA2dp: Proxy object connected
08-28 22:40:56.084  4158  4158 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-28 22:40:56.085  4158  4158 D ObexServerSockets: Succeed to create listening sockets 
08-28 22:40:56.085  4158  4158 D ObexServerSockets0: startAccept()
,08-28 22:40:56.085  4158  4158 D ObexServerSockets0: prepareForNewConnect()
08-28 22:40:56.085   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-28 22:40:56.085  1374  2079 D BluetoothPan: onBluetoothStateChange on: true
08-28 22:40:56.086  3875  3875 D BluetoothInputDevice: Proxy object connected
08-28 22:40:56.086  3875  3875 D HidProfile: Bluetooth service connected
08-28 22:40:56.087  1374  1374 D BluetoothPan: BluetoothPAN Proxy object connected
,08-28 22:40:56.087  1374  1374 D PanProfile: Bluetooth service connected
08-28 22:40:56.088  4158  4158 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-28 22:40:56.088  1374  1398 D BluetoothPbap: onBluetoothStateChange: up=true
08-28 22:40:56.088  4158  4158 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-28 22:40:56.088  4158  4195 D ObexServerSockets0: Accepting socket connection...
08-28 22:40:56.089  4158  4196 D ObexServerSockets0: Accepting socket connection...
08-28 22:40:56.089   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
08-28 22:40:56.090   875   875 D BluetoothA2dp: Proxy object connected
08-28 22:40:56.092  4158  4158 D BluetoothMapService: onReceive
08-28 22:40:56.092  4158  4158 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-28 22:40:56.092  4158  4158 D BluetoothMapService: STATE_ON
08-28 22:40:56.093  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 22:40:56.094  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 22:40:56.094   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
08-28 22:40:56.099  3875  3875 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-28 22:40:56.107  1527  1527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-28 22:40:56.109  3875  3875 D DockEventReceiver: finishStartingService: stopping service
,08-28 22:40:56.111  3875  3875 D BluetoothPbap: Proxy object connected
08-28 22:40:56.112  3875  3875 D PbapServerProfile: Bluetooth service connected
,08-28 22:40:56.112  4158  4158 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-28 22:40:56.112  4158  4158 D ObexServerSockets0: prepareForNewConnect()
08-28 22:40:56.113  4158  4199 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-28 22:40:56.120  1374  1374 D BluetoothPbap: Proxy object connected
,08-28 22:40:56.120  1374  1374 D PbapServerProfile: Bluetooth service connected
,08-28 22:40:56.133  4158  4205 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-28 22:40:56.134  4158  4205 I BtOppRfcommListener: Accept thread started.
,08-28 22:40:56.167   875   875 D BluetoothHeadset: Proxy object connected
,08-28 22:40:56.172  1943  1956 D BluetoothHeadset: Proxy object connected
08-28 22:40:56.172  1374  1396 D BluetoothHeadset: Proxy object connected
,08-28 22:40:56.172  1374  1374 D HeadsetProfile: Bluetooth service connected
08-28 22:40:56.172   875   892 D BluetoothHeadset: Proxy object connected
,08-28 22:40:56.173  3875  3886 D BluetoothHeadset: Proxy object connected
08-28 22:40:56.173  3875  3886 D BluetoothHeadset: Proxy object connected
08-28 22:40:56.173  1943  2224 D BluetoothHeadset: Proxy object connected
08-28 22:40:56.173  3875  3875 D HeadsetProfile: Bluetooth service connected
08-28 22:40:56.173   875   875 D BluetoothHeadset: Proxy object connected
08-28 22:40:56.173   875   875 D BluetoothHeadset: Proxy object connected
,08-28 22:40:56.178  3875  3875 D HeadsetProfile: Bluetooth service connected
,08-28 22:40:56.179   875   892 D BluetoothHeadset: Proxy object connected
,08-28 22:40:56.186   875   892 D BluetoothHeadset: Proxy object connected
,08-28 22:40:59.244  3778  3828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 22:40:59.244  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:40:59.244  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:40:59.244  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-28 22:40:59.244  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 22:40:59.244  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 22:40:59.244  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 22:40:59.244  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-28 22:40:59.251  3778  3828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-28 22:40:59.252  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,08-28 22:40:59.252  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4f5ef12 removed from the list
,08-28 22:40:59.253  3778  3828 D io.jxcore.node.ConnectivityMonitor: stop
,08-28 22:40:59.253  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:40:59.253  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:40:59.256  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-28 22:40:59.256  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@57a76e3 added. We now have 4 listener(s)
08-28 22:40:59.257  3778  3828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-28 22:40:59.261   875  1930 D WifiService: setWifiEnabled: false pid=3778, uid=10000
08-28 22:40:59.261   875  1930 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-28 22:41:04.274  3778  3828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 22:41:04.276   875   885 D WifiService: setWifiEnabled: true pid=3778, uid=10000
08-28 22:41:04.276   875   885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-28 22:41:04.288   875  1318 D WifiConfigStore: Loading config and enabling all networks 
,08-28 22:41:04.303  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 22:41:04.303  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:41:04.303  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:41:04.303  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 22:41:04.303  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 22:41:04.303  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 22:41:04.303  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 22:41:04.303  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-28 22:41:04.310  3778  3778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-28 22:41:04.319  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 22:41:04.319  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:41:04.319  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:41:04.319  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 22:41:04.319  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 22:41:04.319  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 22:41:04.319  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 22:41:04.319  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-28 22:41:04.325  3778  3778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-28 22:41:04.333   875  1318 D WifiConfigStore: loaded 0 passpoint configs
,08-28 22:41:04.334   875  1318 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-28 22:41:04.334   875  1318 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-28 22:41:04.335   875  1318 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-28 22:41:04.336   875  1318 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-28 22:41:04.336   875  1318 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-28 22:41:04.336   875  1318 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-28 22:41:04.353   373   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-28 22:41:04.355   875  1318 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-28 22:41:04.355   373   873 D CommandListener: Setting iface cfg
,08-28 22:41:04.356   875  1317 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '154 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 154 Failed to set address (No such device)'
08-28 22:41:04.356   875  1317 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-28 22:41:04.411   875  1317 D WifiNative-HAL: p2pGetDeviceAddress
,08-28 22:41:04.413   875  1317 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
08-28 22:41:04.415   875  1318 E native  : do suspend true
,08-28 22:41:04.469   875  1318 D WifiConfigStore: Retrieve network priorities after PNO.
,08-28 22:41:05.836   875  1318 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-28 22:41:05.980   875  1318 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.62 rxSuccessRate=8.44 delta 1000 -> 994
,08-28 22:41:05.981   875  1318 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-28 22:41:05.982   875  1318 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-28 22:41:06.003   875  1318 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-28 22:41:06.052   875  1318 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-28 22:41:06.054  1469  1469 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-28 22:41:06.489  1469  1469 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-28 22:41:06.543  1469  1469 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-28 22:41:06.544  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-28 22:41:06.551   875  1318 D WifiConfigStore: Retrieve network priorities after PNO.
,08-28 22:41:06.560   875  1318 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-28 22:41:06.560   875  1318 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-28 22:41:06.560   875  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-28 22:41:06.582   875  1318 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-28 22:41:06.600   373   873 D CommandListener: Setting iface cfg
,08-28 22:41:06.602   875  1318 D WifiStateMachine: Start Dhcp Watchdog 3
,08-28 22:41:06.612   875  1318 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-28 22:41:06.664   875  4216 D DhcpClient: Receive thread started
,08-28 22:41:06.766   875  1318 E native  : do suspend false
,08-28 22:41:06.794   875  1887 D DhcpClient: Broadcasting DHCPDISCOVER
,08-28 22:41:06.810   875  4216 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,08-28 22:41:06.811   875  1887 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,08-28 22:41:06.817   875  1887 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-28 22:41:06.836   875  4216 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-28 22:41:06.838   875  1887 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-28 22:41:06.843   373   873 D CommandListener: Setting iface cfg
,08-28 22:41:06.854   875  1318 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-28 22:41:06.857   875  1887 D DhcpClient: Scheduling renewal in 86399s
,08-28 22:41:06.858   875  1318 E native  : do suspend true
,08-28 22:41:06.888   875  1318 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-28 22:41:06.893   875  1318 D WifiConfigStore: No blacklist allowed without epno enabled
,08-28 22:41:06.895   875  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-28 22:41:06.897   875  1320 D ConnectivityService: Adding iface wlan0 to network 102
,08-28 22:41:06.910   875  1318 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-28 22:41:06.956   875  1320 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-28 22:41:06.956   875  1320 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-28 22:41:06.959   875  1320 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-28 22:41:06.961   875  1320 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-28 22:41:06.963   875  1320 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-28 22:41:06.979   875  1320 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-28 22:41:06.984   875  1320 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-28 22:41:06.984   875  1320 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-28 22:41:06.985   875  1318 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-28 22:41:06.986   875  1318 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-28 22:41:06.986   875  1320 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-28 22:41:06.986   875  1320 D ConnectivityService:    accepting network in place of null
08-28 22:41:06.987   875  1320 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-28 22:41:07.026   875  4215 D NetlinkSocketObserver: NeighborEvent{elapsedMs=205856, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-28 22:41:07.050   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-28 22:41:07.084   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-28 22:41:07.095   875  1320 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-28 22:41:07.096   875  1320 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-28 22:41:07.104   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-28 22:41:07.104   875  1320 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-28 22:41:07.125  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 22:41:07.125  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:41:07.125  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:41:07.125  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 22:41:07.125  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 22:41:07.125  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-28 22:41:07.125  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-28 22:41:07.125  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-28 22:41:07.130  3778  3778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-28 22:41:07.135  1725  1725 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-28 22:41:07.137  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 22:41:07.137  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:41:07.137  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:41:07.137  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 22:41:07.137  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 22:41:07.137  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-28 22:41:07.137  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-28 22:41:07.137  3778  3778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-28 22:41:07.140  1725  1725 D SystemUpdateService: onCreate
,08-28 22:41:07.141  3778  3778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-28 22:41:07.146  1725  1725 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-28 22:41:07.148   875  4214 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.46,2a00:1450:4001:817::200e
,08-28 22:41:07.165  1725  4225 I SystemUpdateService: active receiver: enabled
,08-28 22:41:07.170  1725  1725 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-28 22:41:07.172  1725  2422 I iu.UploadsManager: num queued entries: 0
,08-28 22:41:07.172  1725  2422 I iu.UploadsManager: num updated entries: 0
,08-28 22:41:07.173  1725  2422 I iu.SyncManager: NEXT; no task
,08-28 22:41:07.199  1725  1725 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-28 22:41:07.201  1725  1725 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-28 22:41:07.203  3944  3944 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-28 22:41:07.214  3944  3944 D SprintDMHelper: simOperator: 
,08-28 22:41:07.214  3944  3944 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-28 22:41:07.225  1725  4228 I MDM     : [185] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-28 22:41:07.225  1725  4228 W BaseAppContext: Using Auth Proxy for data requests.,
08-28 22:41:07.226  1725  4225 I SystemUpdateService: Already downloaded, skipping offpeak checks.
08-28 22:41:07.231   875  4214 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sun, 28 Aug 2016 20:41:07 GMT], X-Android-Received-Millis=[1472416867231], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472416867200]}
08-28 22:41:07.232   875  1320 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-28 22:41:07.232   875  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-28 22:41:07.232   875  1320 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-28 22:41:07.233   875  1320 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-28 22:41:07.259  1725  4228 V GoogleAuthProtoRequest: [185] a.<init>: mAccountName set to: thalitester@gmail.com
,08-28 22:41:07.264  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 22:41:07.266  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 22:41:07.294  1725  4225 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-28 22:41:07.294  1725  4225 I SystemUpdateService: now status is 0 (complete)
,08-28 22:41:07.294  1725  4225 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-28 22:41:07.294  1725  4225 I SystemUpdateService: file has been verified
,08-28 22:41:07.295  1725  4225 I SystemUpdateService: OTA package size = 12249756
,08-28 22:41:07.315  1725  4225 I SystemUpdateService: showing system update notification
,08-28 22:41:07.329  1527  2295 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-28 22:41:07.329  1527  2295 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-28 22:41:07.329  1527  2295 I GLSUser : [GLSUser] Extracting token using key: Auth
08-28 22:41:07.329  1527  2295 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 22:41:07.338  1725  1725 D SystemUpdateService: onDestroy
,08-28 22:41:07.362  1725  4228 E MDM     : [185] SitrepService.a: Error sending sitrep.
,08-28 22:41:07.368  3021  4230 V KeepSync: Connecting to GoogleApiClient
,08-28 22:41:07.368   875  2223 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-28 22:41:07.409  2463  4231 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-28 22:41:07.422  1527  2296 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-28 22:41:07.422  1527  2296 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-28 22:41:07.422  1527  2296 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-28 22:41:07.422  1527  2296 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 22:41:07.435  1725  4237 V BaseAuthAsyncOperation: access token request failed
,08-28 22:41:07.437  3021  4230 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-28 22:41:07.447  1527  4236 I GCM     : Ack for not saved message 116
,08-28 22:41:07.493  1527  1538 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-28 22:41:07.493  1527  1538 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-28 22:41:07.493  1527  1538 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-28 22:41:07.494  1527  1538 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 22:41:07.508  3021  4230 E KeepSync: IOException
08-28 22:41:07.508  3021  4230 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-28 22:41:07.508  3021  4230 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-28 22:41:07.508  3021  4230 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-28 22:41:07.508  3021  4230 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-28 22:41:07.508  3021  4230 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-28 22:41:07.508  3021  4230 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-28 22:41:07.508  3021  4230 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-28 22:41:07.508  3021  4230 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-28 22:41:07.508  3021  4230 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-28 22:41:07.508  3021  4230 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-28 22:41:07.508  3021  4230 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-28 22:41:07.508  3021  4230 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-28 22:41:07.508  3021  4230 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-28 22:41:07.508  3021  4230 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-28 22:41:07.508  3021  4230 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-28 22:41:07.508  3021  4230 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-28 22:41:07.508  3021  4230 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-28 22:41:07.508  3021  4230 E KeepSync: 	... 10 more
,08-28 22:41:07.508  3021  4230 W KeepSync: Sync result 2
,08-28 22:41:07.518   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 202035, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-28 22:41:08.093   875  1320 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-28 22:41:09.301  3778  3828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 22:41:09.301  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:41:09.301  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:41:09.301  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 22:41:09.301  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 22:41:09.301  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-28 22:41:09.301  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-28 22:41:09.301  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-28 22:41:09.308  3778  3828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-28 22:41:09.309  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-28 22:41:09.310  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@57a76e3 removed from the list
,08-28 22:41:09.310  3778  3828 D io.jxcore.node.ConnectivityMonitor: stop
08-28 22:41:09.311  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-28 22:41:09.311  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 22:41:09.326  3778  4239 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,08-28 22:41:09.326  3778  4239 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-28 22:41:11.235  1874  1976 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-28 22:41:11.236  1874  1976 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-28 22:41:11.280  1527  1527 I ConfigService: onCreate
,08-28 22:41:12.333  3778  4241 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,08-28 22:41:12.335  3778  4239 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-28 22:41:12.336  3778  4241 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-28 22:41:12.336  3778  4239 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-28 22:41:12.337  3778  4239 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-28 22:41:12.337  3778  4241 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-28 22:41:12.340  3778  4239 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-28 22:41:12.340  3778  4241 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-28 22:41:12.340  3778  4239 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-28 22:41:12.343  3778  4243 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 416, name: OutgoingSocketThread/Sender)
,08-28 22:41:12.344  3778  4241 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-28 22:41:12.346  3778  4244 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 417, name: IncomingSocketThread/Sender)
08-28 22:41:12.347  3778  4245 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 418, name: OutgoingSocketThread/Receiver)
,08-28 22:41:12.347  3778  4245 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 418, thread name: OutgoingSocketThread/Receiver)
08-28 22:41:12.347  3778  4245 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-28 22:41:12.347  3778  4245 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 418, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-28 22:41:12.348  3778  4246 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 419, name: IncomingSocketThread/Receiver)
08-28 22:41:12.349  3778  4246 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 419, thread name: IncomingSocketThread/Receiver)
08-28 22:41:12.349  3778  4246 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-28 22:41:12.349  3778  4246 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 419, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-28 22:41:14.992   875  1320 D ConnectivityService: handlePromptUnvalidated 102
,08-28 22:41:15.332  3778  3828 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-28 22:41:15.334  3778  3828 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-28 22:41:15.344  3778  3828 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@4dfbaee Bundle[{}]
,08-28 22:41:15.345  3778  3828 I io.jxcore.node.LifeCycleMonitor: start: OK
08-28 22:41:15.345  3778  3828 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-28 22:41:15.346  3778  3828 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-28 22:41:15.346  3778  3828 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-28 22:41:15.347  3778  3828 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-28 22:41:15.348  3778  3828 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-28 22:41:15.353  3778  3828 I System.out: Running OutgoingSocketThread
,08-28 22:41:15.357  3778  4249 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-28 22:41:15.357  3778  4249 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-28 22:41:16.347  1527  1527 I ConfigService: onDestroy
,08-28 22:41:18.368  3778  4249 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,08-28 22:41:18.368  3778  4249 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-28 22:41:18.369  3778  4249 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-28 22:41:18.370  3778  4251 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-28 22:41:18.370  3778  4249 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-28 22:41:18.370  3778  4251 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-28 22:41:18.371  3778  4251 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-28 22:41:18.373  3778  4249 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-28 22:41:18.377  3778  4251 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-28 22:41:18.377  3778  4253 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 428, name: OutgoingSocketThread/Sender)
08-28 22:41:18.380  3778  4254 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 429, name: OutgoingSocketThread/Receiver)
08-28 22:41:18.380  3778  4255 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 430, name: IncomingSocketThread/Sender)
,08-28 22:41:18.381  3778  4254 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 429, thread name: OutgoingSocketThread/Receiver)
,08-28 22:41:18.381  3778  4254 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-28 22:41:18.381  3778  4254 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 429, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-28 22:41:18.382  3778  4256 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 431, name: IncomingSocketThread/Receiver)
,08-28 22:41:18.382  3778  4251 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-28 22:41:18.383  3778  4256 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 431, thread name: IncomingSocketThread/Receiver)
08-28 22:41:18.383  3778  4256 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-28 22:41:18.383  3778  4256 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 431, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-28 22:41:21.369  3778  3828 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 440)
,08-28 22:41:21.371  3778  3828 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-28 22:41:21.372  3778  3828 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 441)
,08-28 22:41:21.381  3778  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-28 22:41:21.381  3778  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@beff8e0 added. We now have 3 listener(s)
,08-28 22:41:21.388  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-28 22:41:21.389  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-28 22:41:21.389  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-28 22:41:21.389  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-28 22:41:21.390  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@416799 added. We now have 4 listener(s)
08-28 22:41:21.390  3778  3828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-28 22:41:21.391  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-28 22:41:21.398  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-28 22:41:21.409  3778  3828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-28 22:41:21.409  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:41:21.409  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:41:21.409  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 22:41:21.409  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 22:41:21.409  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-28 22:41:21.409  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-28 22:41:21.409  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-28 22:41:21.415  3778  3828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-28 22:41:21.416  3778  3828 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-28 22:41:21.417  3778  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-28 22:41:21.418  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-28 22:41:21.418  3778  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-28 22:41:21.418  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-28 22:41:21.419  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:41:21.419  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-28 22:41:21.419  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-28 22:41:21.420  3778  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@beff8e0 removed from the list
08-28 22:41:21.420  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-28 22:41:21.420  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@416799 removed from the list
08-28 22:41:21.424  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 22:41:21.432  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 22:41:21.432  3778  3828 D io.jxcore.node.ConnectivityMonitor: stop
08-28 22:41:21.432  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 22:41:21.434  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:41:21.434  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:41:21.438  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-28 22:41:21.438  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-28 22:41:21.438  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:41:21.439  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@416799 not in the list
08-28 22:41:21.439  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:41:21.439  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 22:41:21.443  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-28 22:41:21.443  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 22:41:21.443  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:41:21.443  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@416799 not in the list
,08-28 22:41:21.443  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 22:41:21.444  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:41:21.444  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 22:41:21.444  3778  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@beff8e0 not in the list
08-28 22:41:21.446  3778  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-28 22:41:21.446  3778  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d39e3f added. We now have 3 listener(s)
,08-28 22:41:21.451  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-28 22:41:21.451  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-28 22:41:21.452  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-28 22:41:21.452  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-28 22:41:21.452  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30bc30c added. We now have 4 listener(s)
08-28 22:41:21.452  3778  3828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-28 22:41:21.454  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-28 22:41:21.460  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-28 22:41:21.474  3778  3828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-28 22:41:21.474  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:41:21.474  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:41:21.474  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 22:41:21.474  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 22:41:21.474  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-28 22:41:21.474  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-28 22:41:21.474  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-28 22:41:21.481  3778  3828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-28 22:41:21.482  3778  3828 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-28 22:41:21.483  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-28 22:41:21.483  3778  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-28 22:41:21.483  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-28 22:41:21.484  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-28 22:41:21.484  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-28 22:41:21.491  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 22:41:21.494  3778  3828 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-28 22:41:21.494  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-28 22:41:21.498  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 22:41:21.508  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-28 22:41:21.510  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-28 22:41:21.511  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-28 22:41:21.523  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-28 22:41:21.523  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-28 22:41:21.523  3778  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-28 22:41:21.526  3778  3828 D BluetoothAdapter: STATE_ON
,08-28 22:41:21.535  4158  4197 D BtGatt.GattService: registerClient() - UUID=1cda7b5e-8f4a-4c5a-a35b-035dc8fdad84
,08-28 22:41:21.538  4158  4174 D BtGatt.GattService: onClientRegistered() - UUID=1cda7b5e-8f4a-4c5a-a35b-035dc8fdad84, clientIf=5
,08-28 22:41:21.540  3778  3789 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-28 22:41:21.544  4158  4168 D BtGatt.GattService: start scan with filters
,08-28 22:41:21.559  4158  4177 D BtGatt.ScanManager: handling starting scan
,08-28 22:41:21.560  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-28 22:41:21.560  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-28 22:41:21.561  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-28 22:41:21.562  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-28 22:41:21.566  4158  4177 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c6d6a2
,08-28 22:41:21.575  3778  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-28 22:41:21.576  3778  3778 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-28 22:41:21.577  3778  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-28 22:41:21.584  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-28 22:41:21.585  4158  4174 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-28 22:41:21.586  4158  4174 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-28 22:41:21.587  4158  4177 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-28 22:41:21.594  3778  3828 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-28 22:41:21.594  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-28 22:41:21.594  3778  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-28 22:41:21.594  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:41:21.594  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-28 22:41:21.594  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-28 22:41:21.594  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-28 22:41:21.594  3778  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-28 22:41:21.594  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-28 22:41:21.595  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-28 22:41:21.595  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-28 22:41:21.597  3778  3828 D BluetoothAdapter: STATE_ON
08-28 22:41:21.598  4158  4197 D BtGatt.GattService: stopScan() - queue size =1
,08-28 22:41:21.600  4158  4168 D BtGatt.GattService: unregisterClient() - clientIf=5
08-28 22:41:21.600  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-28 22:41:21.600  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-28 22:41:21.600  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-28 22:41:21.600  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-28 22:41:21.601  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-28 22:41:21.609  3778  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-28 22:41:21.609  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-28 22:41:21.609  3778  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-28 22:41:21.609  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-28 22:41:21.616  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-28 22:41:21.617  3778  3778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-28 22:41:21.617  3778  3778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-28 22:41:21.617  3778  3778 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-28 22:41:21.620  4158  4174 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-28 22:41:21.620  4158  4174 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-28 22:41:21.621  4158  4177 D BtGatt.ScanManager: Starting BLE batch scan
,08-28 22:41:21.621  4158  4177 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-28 22:41:21.633  4158  4174 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-28 22:41:21.633  4158  4174 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 22:41:21.641  4158  4174 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-28 22:41:21.641  4158  4174 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 22:41:21.654  4158  4174 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-28 22:41:21.654  4158  4174 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-28 22:41:21.655  4158  4177 D BtGatt.ScanManager: stopping BLe Batch
,08-28 22:41:21.663  4158  4174 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-28 22:41:21.663  4158  4174 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-28 22:41:21.664  4158  4177 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-28 22:41:21.671  4158  4174 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-28 22:41:21.672  4158  4174 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 22:41:22.118  3778  3778 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-28 22:41:22.119  3778  3778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-28 22:41:22.119  3778  3778 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-28 22:41:24.618  3778  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-28 22:41:24.619  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-28 22:41:24.619  3778  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-28 22:41:24.620  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 22:41:24.620  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:41:24.621  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-28 22:41:24.621  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-28 22:41:24.621  3778  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d39e3f removed from the list
,08-28 22:41:24.622  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:41:24.622  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30bc30c removed from the list
08-28 22:41:24.622  3778  3828 D io.jxcore.node.ConnectivityMonitor: stop
,08-28 22:41:24.622  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:41:24.624  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-28 22:41:24.624  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:41:24.628  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 22:41:24.629  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-28 22:41:24.629  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:41:24.629  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30bc30c not in the list
08-28 22:41:24.630  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-28 22:41:24.630  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 22:41:24.634  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-28 22:41:24.634  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 22:41:24.634  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:41:24.635  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30bc30c not in the list
,08-28 22:41:24.635  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 22:41:24.635  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:41:24.636  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:41:24.636  3778  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d39e3f not in the list
08-28 22:41:24.637  3778  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-28 22:41:24.637  3778  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4df70d1 added. We now have 3 listener(s)
08-28 22:41:24.639  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-28 22:41:24.639  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-28 22:41:24.639  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-28 22:41:24.639  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-28 22:41:24.640  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a28e736 added. We now have 4 listener(s)
08-28 22:41:24.640  3778  3828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-28 22:41:24.640  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-28 22:41:24.643  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-28 22:41:24.650  3778  3828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-28 22:41:24.650  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:41:24.650  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:41:24.650  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 22:41:24.650  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 22:41:24.650  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-28 22:41:24.650  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-28 22:41:24.650  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-28 22:41:24.653  3778  3828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-28 22:41:24.654  3778  3828 D io.jxcore.node.ConnectivityMonitor: start: OK
08-28 22:41:24.654  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-28 22:41:24.656  3778  3828 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,08-28 22:41:24.656  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 22:41:24.656  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-28 22:41:24.659  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-28 22:41:24.659  3778  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,08-28 22:41:24.659  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 22:41:24.659  3778  3828 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-28 22:41:24.659  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-28 22:41:24.660  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-28 22:41:24.661  3778  3828 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-28 22:41:24.662  3778  3828 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-28 22:41:24.662  3778  3778 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-28 22:41:24.662  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-28 22:41:24.663  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-28 22:41:24.663  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-28 22:41:24.664  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-28 22:41:24.665  3778  4257 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-28 22:41:24.668  3778  4257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-28 22:41:24.674  3778  3828 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-28 22:41:24.674  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-28 22:41:24.682  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-28 22:41:24.683  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-28 22:41:24.683  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-28 22:41:24.686  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-28 22:41:24.687  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-28 22:41:24.687  3778  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
08-28 22:41:24.688  3778  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-28 22:41:24.689  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-28 22:41:24.689  3778  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-28 22:41:24.690  3778  3828 D BluetoothAdapter: STATE_ON
,08-28 22:41:24.693  4158  4194 D BtGatt.GattService: registerClient() - UUID=31905e98-d9b7-4b59-b6c1-268db344f352
,08-28 22:41:24.694  4158  4174 D BtGatt.GattService: onClientRegistered() - UUID=31905e98-d9b7-4b59-b6c1-268db344f352, clientIf=5
,08-28 22:41:24.695  3778  3789 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-28 22:41:24.698  4158  4176 D BtGatt.AdvertiseManager: message : 0
,08-28 22:41:24.703  4158  4176 D BtGatt.AdvertiseManager: starting multi advertising
,08-28 22:41:24.721  4158  4174 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-28 22:41:24.733  4158  4174 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-28 22:41:24.735  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-28 22:41:24.736  3778  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-28 22:41:24.739  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-28 22:41:24.741  3778  3778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-28 22:41:24.742  3778  3778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-28 22:41:24.742  3778  3778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-28 22:41:24.742  3778  3778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,08-28 22:41:24.742  3778  3778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-28 22:41:24.742  3778  3778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-28 22:41:24.747  3778  3778 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
08-28 22:41:24.748  3778  3778 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-28 22:41:24.751  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-28 22:41:24.751  3778  3828 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-28 22:41:25.249  3778  3778 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-28 22:41:27.753  3778  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-28 22:41:27.754  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,08-28 22:41:27.754  3778  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-28 22:41:27.754  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-28 22:41:27.754  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-28 22:41:27.755  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-28 22:41:27.756  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-28 22:41:27.756  3778  3828 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-28 22:41:27.756  3778  4257 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-28 22:41:27.756  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-28 22:41:27.757  3778  4257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-28 22:41:27.757  3778  3778 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-28 22:41:27.757  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-28 22:41:27.757  3778  4257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-28 22:41:27.757  3778  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-28 22:41:27.757  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-28 22:41:27.758  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-28 22:41:27.761  3778  3828 D BluetoothAdapter: STATE_ON
08-28 22:41:27.761  3778  3828 D BluetoothLeScanner: could not find callback wrapper
08-28 22:41:27.761  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-28 22:41:27.762  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,08-28 22:41:27.764  4158  4176 D BtGatt.AdvertiseManager: message : 1
08-28 22:41:27.766  4158  4176 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-28 22:41:27.776  4158  4174 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-28 22:41:27.776  4158  4174 D BtGatt.GattService: Client app is not null!
,08-28 22:41:27.778  4158  4185 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-28 22:41:27.779  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-28 22:41:27.779  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED,
08-28 22:41:27.780  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,08-28 22:41:27.780  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,08-28 22:41:27.781  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-28 22:41:27.783  3778  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-28 22:41:27.783  3778  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-28 22:41:27.784  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-28 22:41:27.785  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-28 22:41:27.788  3778  3778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-28 22:41:27.788  3778  3778 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-28 22:41:27.788  3778  3778 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-28 22:41:27.788  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-28 22:41:27.789  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-28 22:41:27.789  3778  3778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-28 22:41:27.789  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-28 22:41:27.790  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-28 22:41:27.790  3778  3778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-28 22:41:27.790  3778  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4df70d1 removed from the list
,08-28 22:41:27.791  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:41:27.791  3778  3778 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-28 22:41:27.791  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a28e736 removed from the list
08-28 22:41:27.792  3778  3828 D io.jxcore.node.ConnectivityMonitor: stop
08-28 22:41:27.792  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:41:27.793  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:41:27.793  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 22:41:27.795  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 22:41:27.795  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-28 22:41:27.795  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:41:27.795  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a28e736 not in the list
08-28 22:41:27.795  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:41:27.795  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 22:41:27.796  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-28 22:41:27.796  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 22:41:27.796  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:41:27.796  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a28e736 not in the list
08-28 22:41:27.796  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 22:41:27.796  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-28 22:41:27.796  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:41:27.796  3778  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4df70d1 not in the list
08-28 22:41:27.797  3778  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-28 22:41:27.797  3778  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@566ded3 added. We now have 3 listener(s)
,08-28 22:41:27.799  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-28 22:41:27.799  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-28 22:41:27.799  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-28 22:41:27.800  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-28 22:41:27.800  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee35a10 added. We now have 4 listener(s)
08-28 22:41:27.800  3778  3828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-28 22:41:27.800  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-28 22:41:27.803  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-28 22:41:27.808  3778  3828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-28 22:41:27.808  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:41:27.808  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:41:27.808  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 22:41:27.808  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 22:41:27.808  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-28 22:41:27.808  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-28 22:41:27.808  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-28 22:41:27.811  3778  3828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-28 22:41:27.812  3778  3828 D io.jxcore.node.ConnectivityMonitor: start: OK
08-28 22:41:27.812  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-28 22:41:27.813  3778  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-28 22:41:27.813  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-28 22:41:27.813  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-28 22:41:27.813  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-28 22:41:27.814  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 22:41:27.817  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 22:41:27.819  3778  3828 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-28 22:41:27.820  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-28 22:41:27.828  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-28 22:41:27.829  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-28 22:41:27.829  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-28 22:41:27.834  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-28 22:41:27.834  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-28 22:41:27.834  3778  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-28 22:41:27.835  3778  3828 D BluetoothAdapter: STATE_ON
,08-28 22:41:27.837  4158  4169 D BtGatt.GattService: registerClient() - UUID=def9dca0-07ba-46ba-a839-fab30c922863
,08-28 22:41:27.837  4158  4174 D BtGatt.GattService: onClientRegistered() - UUID=def9dca0-07ba-46ba-a839-fab30c922863, clientIf=5
08-28 22:41:27.838  3778  3790 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-28 22:41:27.838  4158  4185 D BtGatt.GattService: start scan with filters
,08-28 22:41:27.842  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-28 22:41:27.842  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-28 22:41:27.842  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-28 22:41:27.842  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-28 22:41:27.842  4158  4177 D BtGatt.ScanManager: handling starting scan
,08-28 22:41:27.847  3778  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-28 22:41:27.848  3778  3778 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-28 22:41:27.850  3778  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-28 22:41:27.851  4158  4174 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-28 22:41:27.851  4158  4174 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-28 22:41:27.851  4158  4177 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-28 22:41:27.853  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-28 22:41:27.861  4158  4174 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-28 22:41:27.862  4158  4174 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-28 22:41:27.862  4158  4177 D BtGatt.ScanManager: Starting BLE batch scan
08-28 22:41:27.862  4158  4177 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-28 22:41:27.879  4158  4174 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-28 22:41:27.879  4158  4174 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 22:41:27.888  4158  4174 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-28 22:41:27.888  4158  4174 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 22:41:28.293  3778  3778 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-28 22:41:28.349  3778  3778 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-28 22:41:28.349  3778  3778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-28 22:41:28.350  3778  3778 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-28 22:41:29.395  4158  4158 D BtGatt.ScanManager: awakened up at time 228226
,08-28 22:41:29.399  4158  4177 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-28 22:41:29.448  4158  4174 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=8
,08-28 22:41:29.448  4158  4174 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-28 22:41:29.448  4158  4174 D BtGatt.GattService: current time is 228280210003
08-28 22:41:29.449  4158  4174 D BtGatt.GattService: Batch record : [87, -21, 113, 81, -103, 119, 1, -128, -59, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96, 0, 81, 34, 97, 112, -14, -5, 1, -128, -87, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -82, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -81, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -82, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -88, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -89, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 87, -21, 113, 81, -103, 119, 1, -128, -59, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96, 0]
,08-28 22:41:29.451  4158  4174 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96]
08-28 22:41:29.451  4158  4174 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-28 22:41:29.452  4158  4174 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-28 22:41:29.452  4158  4174 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-28 22:41:29.452  4158  4174 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-28 22:41:29.452  4158  4174 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-28 22:41:29.453  4158  4174 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-28 22:41:29.453  4158  4174 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96]
08-28 22:41:29.457  3778  3778 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:34:8A:A0 1], added - the peer count is 1
,08-28 22:41:29.458  3778  3778 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> 7C:F9:0E:34:8A:A0 1] updated - the peer count is 1
08-28 22:41:29.458  3778  3778 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:34:8A:A0 1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: '', device address: ''
,08-28 22:41:30.864  3778  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-28 22:41:30.865  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-28 22:41:30.865  3778  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything,
,08-28 22:41:30.865  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-28 22:41:30.866  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-28 22:41:30.866  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-28 22:41:30.866  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-28 22:41:30.866  3778  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-28 22:41:30.867  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-28 22:41:30.867  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-28 22:41:30.867  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-28 22:41:30.870  3778  3828 D BluetoothAdapter: STATE_ON
08-28 22:41:30.872  4158  4168 D BtGatt.GattService: stopScan() - queue size =1
08-28 22:41:30.874  4158  4169 D BtGatt.GattService: unregisterClient() - clientIf=5
08-28 22:41:30.876  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-28 22:41:30.876  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-28 22:41:30.876  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-28 22:41:30.877  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-28 22:41:30.877  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-28 22:41:30.880  3778  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-28 22:41:30.882  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-28 22:41:30.882  3778  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-28 22:41:30.883  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-28 22:41:30.884  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-28 22:41:30.885  3778  3828 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
08-28 22:41:30.885  4158  4158 D BtGatt.ScanManager: awakened up at time 229717
08-28 22:41:30.888  3778  3778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-28 22:41:30.888  3778  3778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-28 22:41:30.889  3778  3778 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-28 22:41:30.889  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 22:41:30.889  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-28 22:41:30.889  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-28 22:41:30.889  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-28 22:41:30.889  3778  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@566ded3 removed from the list
08-28 22:41:30.890  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:41:30.890  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee35a10 removed from the list
08-28 22:41:30.890  3778  3828 D io.jxcore.node.ConnectivityMonitor: stop
,08-28 22:41:30.890  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:41:30.891  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:41:30.891  4158  4174 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-28 22:41:30.891  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:41:30.891  4158  4174 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 22:41:30.892  4158  4177 D BtGatt.ScanManager: stopping BLe Batch
08-28 22:41:30.892  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 22:41:30.893  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-28 22:41:30.893  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-28 22:41:30.893  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee35a10 not in the list
08-28 22:41:30.893  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-28 22:41:30.893  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:41:30.895  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-28 22:41:30.896  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 22:41:30.896  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:41:30.896  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee35a10 not in the list
,08-28 22:41:30.896  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 22:41:30.897  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:41:30.897  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:41:30.897  3778  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@566ded3 not in the list
08-28 22:41:30.899  3778  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-28 22:41:30.899  3778  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a1554b added. We now have 3 listener(s)
,08-28 22:41:30.905  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-28 22:41:30.906  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-28 22:41:30.906  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-28 22:41:30.906  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-28 22:41:30.907  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b05b28 added. We now have 4 listener(s)
08-28 22:41:30.907  3778  3828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-28 22:41:30.908  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-28 22:41:30.909  4158  4174 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-28 22:41:30.909  4158  4174 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-28 22:41:30.910  4158  4177 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-28 22:41:30.915  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-28 22:41:30.923  3778  3828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-28 22:41:30.923  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 22:41:30.923  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 22:41:30.923  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 22:41:30.923  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 22:41:30.923  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-28 22:41:30.923  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-28 22:41:30.923  3778  3828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-28 22:41:30.926  4158  4174 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,08-28 22:41:30.926  3778  3828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-28 22:41:30.926  4158  4174 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 22:41:30.926  4158  4174 D BtGatt.GattService: current time is 229758156544
08-28 22:41:30.926  4158  4174 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -88, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-28 22:41:30.927  3778  3828 D io.jxcore.node.ConnectivityMonitor: start: OK
08-28 22:41:30.927  4158  4174 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-28 22:41:30.928  3778  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-28 22:41:30.929  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-28 22:41:30.929  3778  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-28 22:41:30.929  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 22:41:30.930  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 22:41:30.930  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:41:30.930  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-28 22:41:30.930  3778  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-28 22:41:30.930  3778  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a1554b removed from the list
08-28 22:41:30.930  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:41:30.931  3778  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b05b28 removed from the list
,08-28 22:41:30.932  3778  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 22:41:30.933  3778  3828 D io.jxcore.node.ConnectivityMonitor: stop
08-28 22:41:30.933  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 22:41:30.933  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:41:30.934  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 22:41:30.935  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-28 22:41:30.935  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-28 22:41:30.935  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-28 22:41:30.936  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b05b28 not in the list
08-28 22:41:30.936  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:41:30.936  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 22:41:30.937  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-28 22:41:30.937  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 22:41:30.937  3778  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 22:41:30.938  3778  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b05b28 not in the list
08-28 22:41:30.938  3778  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-28 22:41:30.938  3778  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 22:41:30.938  3778  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 22:41:30.938  3778  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a1554b not in the list
08-28 22:41:30.939  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-28 22:41:30.940  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-28 22:41:30.940  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-28 22:41:30.940  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-28 22:41:30.940  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only,
08-28 22:41:30.940  3778  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-28 22:41:31.389  3778  3778 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-28 22:41:32.957  3778  4258 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 450, name: My test thread name)
,08-28 22:41:34.954  3778  3828 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 450
,08-28 22:41:34.955  3778  3828 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 450, name: My test thread name)
,08-28 22:41:34.961  3778  4259 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 451, name: My test thread name)
,08-28 22:41:34.962  3778  4259 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 451, thread name: My test thread name)
,08-28 22:41:34.962  3778  4259 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 451, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-28 22:41:34.966  3778  3828 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-28 22:41:34.974  3778  4260 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 455, name: My test thread name)
,08-28 22:41:34.975  3778  4260 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 455, thread name: My test thread name): Test exception.
,08-28 22:41:34.975  3778  4260 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 455, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-28 22:41:34.981  3778  3828 I jxcore-log: Total number of executed tests:  82
08-28 22:41:34.981  3778  3828 I jxcore-log: 
,08-28 22:41:34.982  3778  3828 I jxcore-log: Number of passed tests:  82
08-28 22:41:34.982  3778  3828 I jxcore-log: 
,08-28 22:41:34.982  3778  3828 I jxcore-log: Number of failed tests:  0
08-28 22:41:34.982  3778  3828 I jxcore-log: 
08-28 22:41:34.983  3778  3828 I jxcore-log: Number of ignored tests:  0
08-28 22:41:34.983  3778  3828 I jxcore-log: 
08-28 22:41:34.984  3778  3828 I jxcore-log: Total duration:  101351
08-28 22:41:34.984  3778  3828 I jxcore-log: 
,08-28 22:41:34.986  3778  3828 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-28 22:41:34.986  3778  3828 I jxcore-log: 
,08-28 22:41:34.994  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-28 22:41:34.994  3778  3828 I jxcore-log: 
,08-28 22:41:35.002  3778  3778 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-28 22:41:35.003  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-28 22:41:35.003  3778  3828 I jxcore-log: 
08-28 22:41:35.006  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-28 22:41:35.006  3778  3828 I jxcore-log: 
,08-28 22:41:35.009  3778  4258 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 450, name: My test thread name), during the lifetime of the thread the total number of bytes read was 132 and the total number of bytes written 132
,08-28 22:41:35.009  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-28 22:41:35.009  3778  3828 I jxcore-log: 
,08-28 22:41:35.013  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-28 22:41:35.013  3778  3828 I jxcore-log: 
,08-28 22:41:35.014  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-28 22:41:35.014  3778  3828 I jxcore-log: 
,08-28 22:41:35.017  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-28 22:41:35.017  3778  3828 I jxcore-log: 
,08-28 22:41:35.019  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-28 22:41:35.019  3778  3828 I jxcore-log: 
,08-28 22:41:35.020  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-28 22:41:35.020  3778  3828 I jxcore-log: 
,08-28 22:41:35.020  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-28 22:41:35.020  3778  3828 I jxcore-log: 
,08-28 22:41:35.021  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-28 22:41:35.021  3778  3828 I jxcore-log: 
,08-28 22:41:35.022  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-28 22:41:35.022  3778  3828 I jxcore-log: 
08-28 22:41:35.023  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,08-28 22:41:35.023  3778  3828 I jxcore-log: 
08-28 22:41:35.024  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-28 22:41:35.024  3778  3828 I jxcore-log: 
,08-28 22:41:35.024  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-28 22:41:35.024  3778  3828 I jxcore-log: 
,08-28 22:41:35.026  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-28 22:41:35.026  3778  3828 I jxcore-log: 
,08-28 22:41:35.026  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-28 22:41:35.026  3778  3828 I jxcore-log: 
,08-28 22:41:35.027  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-28 22:41:35.027  3778  3828 I jxcore-log: 
,08-28 22:41:35.028  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-28 22:41:35.028  3778  3828 I jxcore-log: 
,08-28 22:41:35.029  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-28 22:41:35.029  3778  3828 I jxcore-log: 
,08-28 22:41:35.030  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-28 22:41:35.030  3778  3828 I jxcore-log: 
,08-28 22:41:35.031  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-28 22:41:35.031  3778  3828 I jxcore-log: 
,08-28 22:41:35.031  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-28 22:41:35.031  3778  3828 I jxcore-log: 
,08-28 22:41:35.032  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-28 22:41:35.032  3778  3828 I jxcore-log: 
,08-28 22:41:35.033  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-28 22:41:35.033  3778  3828 I jxcore-log: 
,08-28 22:41:35.033  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
08-28 22:41:35.033  3778  3828 I jxcore-log: 
,08-28 22:41:35.034  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-28 22:41:35.034  3778  3828 I jxcore-log: 
,08-28 22:41:35.035  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-28 22:41:35.035  3778  3828 I jxcore-log: 
,08-28 22:41:35.036  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-28 22:41:35.036  3778  3828 I jxcore-log: 
,08-28 22:41:35.037  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-28 22:41:35.037  3778  3828 I jxcore-log: 
,08-28 22:41:35.037  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
08-28 22:41:35.037  3778  3828 I jxcore-log: 
,08-28 22:41:35.038  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-28 22:41:35.038  3778  3828 I jxcore-log: 
,08-28 22:41:35.039  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-28 22:41:35.039  3778  3828 I jxcore-log: 
08-28 22:41:35.040  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-28 22:41:35.040  3778  3828 I jxcore-log: 
,08-28 22:41:35.040  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-28 22:41:35.040  3778  3828 I jxcore-log: 
,08-28 22:41:35.041  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-28 22:41:35.041  3778  3828 I jxcore-log: 
,08-28 22:41:35.042  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-28 22:41:35.042  3778  3828 I jxcore-log: 
,08-28 22:41:35.042  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-28 22:41:35.042  3778  3828 I jxcore-log: ,
08-28 22:41:35.043  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-28 22:41:35.043  3778  3828 I jxcore-log: 
08-28 22:41:35.044  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-28 22:41:35.044  3778  3828 I jxcore-log: 
08-28 22:41:35.045  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-28 22:41:35.045  3778  3828 I jxcore-log: 
,08-28 22:41:35.045  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-28 22:41:35.045  3778  3828 I jxcore-log: 
08-28 22:41:35.046  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-28 22:41:35.046  3778  3828 I jxcore-log: 
08-28 22:41:35.047  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-28 22:41:35.047  3778  3828 I jxcore-log: 
08-28 22:41:35.048  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-28 22:41:35.048  3778  3828 I jxcore-log: 
08-28 22:41:35.049  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-28 22:41:35.049  3778  3828 I jxcore-log: 
08-28 22:41:35.049  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-28 22:41:35.049  3778  3828 I jxcore-log: 
,08-28 22:41:35.050  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-28 22:41:35.050  3778  3828 I jxcore-log: 
08-28 22:41:35.051  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-28 22:41:35.051  3778  3828 I jxcore-log: 
,08-28 22:41:35.053  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-28 22:41:35.053  3778  3828 I jxcore-log: 
08-28 22:41:35.054  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-28 22:41:35.054  3778  3828 I jxcore-log: 
08-28 22:41:35.054  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-28 22:41:35.054  3778  3828 I jxcore-log: 
08-28 22:41:35.055  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-28 22:41:35.055  3778  3828 I jxcore-log: 
,08-28 22:41:35.055  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-28 22:41:35.055  3778  3828 I jxcore-log: 
08-28 22:41:35.056  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
08-28 22:41:35.056  3778  3828 I jxcore-log: 
08-28 22:41:35.057  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-28 22:41:35.057  3778  3828 I jxcore-log: 
,08-28 22:41:35.058  3778  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-28 22:41:35.058  3778  3828 I jxcore-log: 
,08-28 22:41:35.580  4261  4261 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-28 22:41:35.585  4261  4261 D AndroidRuntime: CheckJNI is OFF
,08-28 22:41:35.628  4261  4261 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-28 22:41:35.676  4261  4261 I Radio-JNI: register_android_hardware_Radio DONE
,08-28 22:41:35.699  4261  4261 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-28 22:41:35.710   875   888 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-28 22:41:35.711   875   888 I ActivityManager: Killing 3778:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-28 22:41:35.811   875   898 W PackageSettings: Skipping PackageSetting{7083a27 com.example.hello/10273} due to missing metadata
,08-28 22:41:35.842   875   886 I WindowState: WIN DEATH: Window{117fd54 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-28 22:41:35.844   875  1319 D WifiService: Client connection lost with reason: 4
,08-28 22:41:35.846   875  2222 D GraphicsStats: Buffer count: 2
,08-28 22:41:35.857   875   898 I art     : Starting a blocking GC Explicit
,08-28 22:41:35.897   875   888 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-28 22:41:35.897   875   888 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-28 22:41:35.898   875   888 E ActivityManager: Failure starting process com.test.thalitest
08-28 22:41:35.898   875   888 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-28 22:41:35.898   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-28 22:41:35.898   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-28 22:41:35.898   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-28 22:41:35.898   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-28 22:41:35.898   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-28 22:41:35.898   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-28 22:41:35.898   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-28 22:41:35.898   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-28 22:41:35.898   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-28 22:41:35.898   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-28 22:41:35.898   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-28 22:41:35.898   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-28 22:41:35.898   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-28 22:41:35.898   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-28 22:41:35.898   875   888 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-28 22:41:35.898   875   888 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-28 22:41:35.898   875   888 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-28 22:41:35.898   875   888 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-28 22:41:35.899   875   888 I ActivityManager:   Force finishing activity ActivityRecord{beb5d65 u0 com.test.thalitest/.MainActivity t2}
,08-28 22:41:35.912   875  2223 W ActivityManager: Spurious death for ProcessRecord{a26f0d9 0:com.test.thalitest/u0a0}, curProc for 3778: null
,08-28 22:41:35.949   875   898 I art     : Explicit concurrent mark sweep GC freed 29015(1808KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 29MB/43MB, paused 1.174ms total 91.550ms
,08-28 22:41:35.986   875   898 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-28 22:41:35.990  4261  4261 I art     : System.exit called, status: 0
,08-28 22:41:35.990  4261  4261 I AndroidRuntime: VM exiting with result code 0.
08-28 22:41:35.991   875   898 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-28 22:41:36.016   875   888 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-28 22:41:36.020  1874  1874 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-28 22:41:36.022   875  1306 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-28 22:41:36.025  4158  4158 D BluetoothMapAppObserver: onReceive
,08-28 22:41:36.025  4158  4158 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-28 22:41:36.033  3611  3611 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-28 22:41:36.035  1990  2274 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-28 22:41:36.038  1874  4272 I Keyboard.Facilitator.DecoderInitializer: run()
,08-28 22:41:36.042  1874  4272 I Decoder : createOrResetDecoder
,08-28 22:41:36.069  1943  1943 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-28 22:41:36.072   875   886 I ActivityManager: Start proc 4275:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-28 22:41:36.103  1527  1527 I ConfigService: onCreate
,08-28 22:41:36.111  1527  4287 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-28 22:41:36.111  1527  4287 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-28 22:41:36.111  1527  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-28 22:41:36.111  1527  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-28 22:41:36.111  1527  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-28 22:41:36.111  1527  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-28 22:41:36.111  1527  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-28 22:41:36.111  1527  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-28 22:41:36.111  1527  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-28 22:41:36.111  1527  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-28 22:41:36.111  1527  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-28 22:41:36.111  1527  4287 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-28 22:41:36.111  1527  4287 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-28 22:41:36.111  1527  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-28 22:41:36.111  1527  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-28 22:41:36.111  1527  4287 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-28 22:41:36.111  1527  4287 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-28 22:41:36.111  1527  4287 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-28 22:41:36.111  1527  4287 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-28 22:41:36.111  1527  4287 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-28 22:41:36.111  1527  4287 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-28 22:41:36.111  1527  4287 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-28 22:41:36.111  1527  4287 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-28 22:41:36.111  1527  4287 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-28 22:41:36.111  1527  4287 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-28 22:41:36.111  1527  4287 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-28 22:41:36.111  1527  4287 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-28 22:41:36.111  1527  4287 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-28 22:41:36.111  1527  4287 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-28 22:41:36.111  1527  4287 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-28 22:41:36.111  1527  4287 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-28 22:41:36.111  1527  4287 E SQLiteOpenHelper:, 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-28 22:41:36.111  1527  4287 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-28 22:41:36.111  1527  4287 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-28 22:41:36.111  1527  4287 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-28 22:41:36.111  1527  4287 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-28 22:41:36.114   875   875 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-28 22:41:36.120   875  2221 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3778 uid 10000
08-28 22:41:36.122  1874  1874 I Keyboard.Facilitator: onFinishInput()
08-28 22:41:36.124  4275  4275 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
08-28 22:41:36.125  1527  4287 W SQLiteOpenHelper: Opened config.db in read-only mode
08-28 22:41:36.147  1874  4272 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-28 22:41:36.166   875   887 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-28 22:41:36.166  1958  2027 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-28 22:41:36.172   875   887 E PackageManager: Failed to write settings, restoring backup
08-28 22:41:36.172   875   887 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-28 22:41:36.172   875   887 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-28 22:41:36.172   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-28 22:41:36.172   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-28 22:41:36.172   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-28 22:41:36.172   875   887 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-28 22:41:36.172   875   887 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-28 22:41:36.172   875   887 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-28 22:41:36.176   875   888 E DropBoxManagerService: Can't write: system_server_wtf
08-28 22:41:36.176   875   888 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-28 22:41:36.176   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-28 22:41:36.176   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-28 22:41:36.176   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-28 22:41:36.176   875   888 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-28 22:41:36.176   875   888 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-28 22:41:36.176   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-28 22:41:36.176   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-28 22:41:36.176   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-28 22:41:36.176   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-28 22:41:36.176   875   888 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-28 22:41:36.176   875   888 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-28 22:41:36.176   875   888 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-28 22:41:36.176   875   888 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-28 22:41:36.176   875   888 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-28 22:41:36.176   875   888 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-28 22:41:36.176   875   888 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-28 22:41:36.176   875   888 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-28 22:41:36.176   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-28 22:41:36.176   875   888 E DropBoxManagerService: 	... 13 more
,08-28 22:41:36.180   875  1953 I ActivityManager: Start proc 4291:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-28 22:41:36.181  1958  2027 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-28 22:41:36.181  1958  2027 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1958
08-28 22:41:36.181  1958  2027 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-28 22:41:36.181  1958  2027 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-28 22:41:36.181  1958  2027 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-28 22:41:36.181  1958  2027 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-28 22:41:36.181  1958  2027 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-28 22:41:36.181  1958  2027 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-28 22:41:36.181  1958  2027 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-28 22:41:36.181  1958  2027 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-28 22:41:36.181  1958  2027 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-28 22:41:36.181  1958  2027 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-28 22:41:36.181  1958  2027 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-28 22:41:36.181  1958  2027 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-28 22:41:36.183   875  4297 E DropBoxManagerService: Can't write: system_app_crash
08-28 22:41:36.183   875  4297 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-28 22:41:36.183   875  4297 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-28 22:41:36.183   875  4297 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-28 22:41:36.183   875  4297 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-28 22:41:36.183   875  4297 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-28 22:41:36.183   875  4297 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-28 22:41:36.183   875  4297 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-28 22:41:36.183   875  4297 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-28 22:41:36.183   875  4297 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-28 22:41:36.183   875  4297 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-28 22:41:36.183   875  4297 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-28 22:41:36.183   875  4297 E DropBoxManagerService: 	... 5 more
,08-28 22:41:36.183   875  1930 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-28 22:41:36.188  1958  2027 I Process : Sending signal. PID: 1958 SIG: 9
,08-28 22:41:36.201  4275  4275 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-28 22:41:36.227   875  1541 I ActivityManager: Start proc 4306:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-28 22:41:36.236  1874  4272 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-28 22:41:36.238  1874  4272 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-28 22:41:36.238  1874  4272 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-28 22:41:36.240  1874  4272 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-28 22:41:36.240  1874  4272 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-28 22:41:36.240  1874  4272 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-28 22:41:36.241  1874  4272 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-28 22:41:36.241  1874  4272 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-28 22:41:36.241  1874  4272 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-28 22:41:36.241  1874  4272 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-28 22:41:36.244  1874  4272 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-28 22:41:36.244  1874  4272 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,08-28 22:41:36.247  1874  4272 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-28 22:41:36.257  4306  4306 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-28 22:41:36.260  4275  4308 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-28 22:41:36.297  1527  1527 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-28 22:41:36.299  1527  1527 D AndroidRuntime: Shutting down VM
,08-28 22:41:36.300  1527  1527 E AndroidRuntime: FATAL EXCEPTION: main
08-28 22:41:36.300  1527  1527 E AndroidRuntime: Process: com.google.process.gapps, PID: 1527
08-28 22:41:36.300  1527  1527 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-28 22:41:36.300  1527  1527 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-28 22:41:36.300  1527  1527 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-28 22:41:36.300  1527  1527 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-28 22:41:36.300  1527  1527 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-28 22:41:36.300  1527  1527 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-28 22:41:36.300  1527  1527 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-28 22:41:36.300  1527  1527 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-28 22:41:36.300  1527  1527 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-28 22:41:36.300  1527  1527 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-28 22:41:36.300  1527  1527 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-28 22:41:36.300  1527  1527 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-28 22:41:36.300  1527  1527 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-28 22:41:36.300  1527  1527 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-28 22:41:36.300  1527  1527 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-28 22:41:36.300  1527  1527 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-28 22:41:36.300  1527  1527 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-28 22:41:36.300  1527  1527 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-28 22:41:36.300  1527  1527 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-28 22:41:36.300  1527  1527 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-28 22:41:36.300  1527  1527 E AndroidRuntime: 	... 8 more
,08-28 22:41:36.308   875  4324 E DropBoxManagerService: Can't write: system_app_crash
08-28 22:41:36.308   875  4324 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-28 22:41:36.308   875  4324 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-28 22:41:36.308   875  4324 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-28 22:41:36.308   875  4324 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-28 22:41:36.308   875  4324 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-28 22:41:36.308   875  4324 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-28 22:41:36.308   875  4324 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-28 22:41:36.308   875  4324 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-28 22:41:36.308   875  4324 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-28 22:41:36.308   875  4324 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-28 22:41:36.308   875  4324 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-28 22:41:36.308   875  4324 E DropBoxManagerService: 	... 5 more
,08-28 22:41:36.315  1527  1527 I Process : Sending signal. PID: 1527 SIG: 9
,08-28 22:41:36.355  1725  4325 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 352)
,08-28 22:41:36.356  1725  4325 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@4a1c2c2
08-28 22:41:36.356   875  1381 I ActivityManager: Process com.google.process.gapps (pid 1527) early provider death
,08-28 22:41:36.358  4275  4289 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-28 22:41:36.358  4275  4289 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-28 22:41:36.358  4275  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-28 22:41:36.358  4275  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-28 22:41:36.358  4275  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-28 22:41:36.358  4275  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-28 22:41:36.358  4275  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-28 22:41:36.358  4275  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-28 22:41:36.358  4275  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-28 22:41:36.358  4275  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-28 22:41:36.358  4275  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-28 22:41:36.358  4275  4289 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-28 22:41:36.358  4275  4289 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-28 22:41:36.358  4275  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-28 22:41:36.358  4275  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-28 22:41:36.358  4275  4289 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-28 22:41:36.358  4275  4289 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-28 22:41:36.358  4275  4289 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-28 22:41:36.358  4275  4289 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-28 22:41:36.358  4275  4289 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-28 22:41:36.358  4275  4289 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-28 22:41:36.358  4275  4289 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-28 22:41:36.359  4275  4289 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-28 22:41:36.359  4275  4289 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-28 22:41:36.359  4275  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-28 22:41:36.359  4275  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-28 22:41:36.359  4275  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-28 22:41:36.359  4275  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-28 22:41:36.359  4275  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-28 22:41:36.359  4275  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-28 22:41:36.359  4275  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-28 22:41:36.359  4275  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-28 22:41:36.359  4275  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-28 22:41:36.359  4275  4289 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-28 22:41:36.359  4275  4289 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-28 22:41:36.359  4275  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-28 22:41:36.359  4275  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-28 22:41:36.359  4275  4289 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-28 22:41:36.359  4275  4289 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-28 22:41:36.359  4275  4289 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-28 22:41:36.359  4275  4289 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-28 22:41:36.359  4275  4289 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-28 22:41:36.359  4275  4289 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-28 22:41:36.359  4275  4289 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-28 22:41:36.367   875  1953 D GraphicsStats: Buffer count: 1
,08-28 22:41:36.368   875  2221 I WindowState: WIN DEATH: Window{daf4720 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-28 22:41:36.376   875  1319 D WifiService: Client connection lost with reason: 4
,08-28 22:41:36.392   875  1381 I ActivityManager: Process com.google.process.gapps (pid 1527) has died
,08-28 22:41:36.393   875  1381 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
,08-28 22:41:36.393   875  1381 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 11000ms
08-28 22:41:36.394   875  1381 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 21000ms
,08-28 22:41:36.396   875   886 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1958) has died
,08-28 22:41:36.396   875   886 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 30998ms
,08-28 22:41:36.402   875   886 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-28 22:41:36.405   875  2222 W ActivityManager: Spurious death for ProcessRecord{a4916ee 0:com.google.process.gapps/u0a11}, curProc for 1527: null
,08-28 22:41:36.410  1725  1725 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-28 22:41:36.420   875   888 I ActivityManager: Start proc 4327:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-28 22:41:36.438  4275  4289 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
08-28 22:41:36.440   875  1972 I ActivityManager: Start proc 4339:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
,08-28 22:41:36.453  4275  4308 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-28 22:41:36.453  4275  4308 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-28 22:41:36.453  4275  4308 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-28 22:41:36.453  4275  4308 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-28 22:41:36.453  4275  4308 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-28 22:41:36.453  4275  4308 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-28 22:41:36.453  4275  4308 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-28 22:41:36.453  4275  4308 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-28 22:41:36.453  4275  4308 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-28 22:41:36.453  4275  4308 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-28 22:41:36.453  4275  4308 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-28 22:41:36.453  4275  4308 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-28 22:41:36.453  4275  4308 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-28 22:41:36.453  4275  4308 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-28 22:41:36.453  4275  4308 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-28 22:41:36.453  4275  4308 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-28 22:41:36.453  4275  4308 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-28 22:41:36.453  4275  4308 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-28 22:41:36.453  4275  4308 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-28 22:41:36.453  4275  4308 E SQLiteDatabase: 	,at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-28 22:41:36.453  4275  4308 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-28 22:41:36.453  4275  4308 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-28 22:41:36.453  4275  4308 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-28 22:41:36.453  4275  4308 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-28 22:41:36.453  4275  4308 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-28 22:41:36.454  4275  4308 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-28 22:41:36.454  4275  4308 E AndroidRuntime: Process: android.process.acore, PID: 4275
08-28 22:41:36.454  4275  4308 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-28 22:41:36.454  4275  4308 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-28 22:41:36.454  4275  4308 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-28 22:41:36.454  4275  4308 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-28 22:41:36.454  4275  4308 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-28 22:41:36.454  4275  4308 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-28 22:41:36.454  4275  4308 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-28 22:41:36.454  4275  4308 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-28 22:41:36.454  4275  4308 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-28 22:41:36.454  4275  4308 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-28 22:41:36.454  4275  4308 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-28 22:41:36.454  4275  4308 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-28 22:41:36.454  4275  4308 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-28 22:41:36.454  4275  4308 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-28 22:41:36.454  4275  4308 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-28 22:41:36.454  4275  4308 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-28 22:41:36.454  4275  4308 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-28 22:41:36.454  4275  4308 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-28 22:41:36.454  4275  4308 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-28 22:41:36.454  4275  4308 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-28 22:41:36.454  4275  4308 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-28 22:41:36.454  4275  4308 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-28 22:41:36.454  4275  4308 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-28 22:41:36.454  4275  4308 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-28 22:41:36.458   875  4351 E DropBoxManagerService: Can't write: system_app_crash
08-28 22:41:36.458   875  4351 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-28 22:41:36.458   875  4351 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-28 22:41:36.458   875  4351 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-28 22:41:36.458   875  4351 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-28 22:41:36.458   875  4351 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-28 22:41:36.458   875  4351 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-28 22:41:36.458   875  4351 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-28 22:41:36.458   875  4351 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-28 22:41:36.458   875  4351 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-28 22:41:36.458   875  4351 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-28 22:41:36.458   875  4351 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-28 22:41:36.458   875  4351 E DropBoxManagerService: 	... 5 more
,08-28 22:41:36.459  4275  4308 I Process : Sending signal. PID: 4275 SIG: 9
,08-28 22:41:36.472  1725  1725 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-28 22:41:36.472  1725  1725 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-28 22:41:36.478  4327  4327 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-28 22:41:36.478  4327  4327 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-28 22:41:36.478  4327  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-28 22:41:36.478  4327  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-28 22:41:36.478  4327  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-28 22:41:36.478  4327  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-28 22:41:36.478  4327  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-28 22:41:36.478  4327  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-28 22:41:36.478  4327  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-28 22:41:36.478  4327  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-28 22:41:36.478  4327  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-28 22:41:36.478  4327  4327 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-28 22:41:36.478  4327  4327 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-28 22:41:36.478  4327  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-28 22:41:36.478  4327  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-28 22:41:36.478  4327  4327 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-28 22:41:36.478  4327  4327 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-28 22:41:36.478  4327  4327 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-28 22:41:36.478  4327  4327 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-28 22:41:36.478  4327  4327 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-28 22:41:36.478  4327  4327 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-28 22:41:36.478  4327  4327 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-28 22:41:36.478  4327  4327 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-28 22:41:36.478  4327  4327 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-28 22:41:36.478  4327  4327 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-28 22:41:36.478  4327  4327 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-28 22:41:36.478  4327  4327 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-28 22:41:36.478  4327  4327 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-28 22:41:36.478  4327  4327 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-28 22:41:36.478  4327  4327 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-28 22:41:36.478  4327  4327 D AndroidRuntime: Shutting down VM
,08-28 22:41:36.480  1725  1725 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-28 22:41:36.481  1725  1725 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-28 22:41:36.485  4327  4327 E AndroidRuntime: FATAL EXCEPTION: main
08-28 22:41:36.485  4327  4327 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4327
08-28 22:41:36.485  4327  4327 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-28 22:41:36.485  4327  4327 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-28 22:41:36.485  4327  4327 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-28 22:41:36.485  4327  4327 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-28 22:41:36.485  4327  4327 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-28 22:41:36.485  4327  4327 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-28 22:41:36.485  4327  4327 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-28 22:41:36.485  4327  4327 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-28 22:41:36.485  4327  4327 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-28 22:41:36.485  4327  4327 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-28 22:41:36.485  4327  4327 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-28 22:41:36.485  4327  4327 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-28 22:41:36.485  4327  4327 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-28 22:41:36.485  4327  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-28 22:41:36.485  4327  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-28 22:41:36.485  4327  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-28 22:41:36.485  4327  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-28 22:41:36.485  4327  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-28 22:41:36.485  4327  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-28 22:41:36.485  4327  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-28 22:41:36.485  4327  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-28 22:41:36.485  4327  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-28 22:41:36.485  4327  4327 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-28 22:41:36.485  4327  4327 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-28 22:41:36.485  4327  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-28 22:41:36.485  4327  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-28 22:41:36.485  4327  4327 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482),
08-28 22:41:36.485  4327  4327 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-28 22:41:36.485  4327  4327 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-28 22:41:36.485  4327  4327 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-28 22:41:36.485  4327  4327 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-28 22:41:36.485  4327  4327 E AndroidRuntime: 	... 10 more
08-28 22:41:36.487   875  2222 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-28 22:41:36.487  4327  4327 I Process : Sending signal. PID: 4327 SIG: 9
08-28 22:41:36.488   875  4356 E DropBoxManagerService: Can't write: system_app_crash
08-28 22:41:36.488   875  4356 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-28 22:41:36.488   875  4356 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-28 22:41:36.488   875  4356 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-28 22:41:36.488   875  4356 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-28 22:41:36.488   875  4356 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-28 22:41:36.488   875  4356 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-28 22:41:36.488   875  4356 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-28 22:41:36.488   875  4356 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-28 22:41:36.488   875  4356 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-28 22:41:36.488   875  4356 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-28 22:41:36.488   875  4356 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-28 22:41:36.488   875  4356 E DropBoxManagerService: 	... 5 more
,08-28 22:41:36.489  4339  4339 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
08-28 22:41:36.490  1725  4355 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-28 22:41:36.495  4339  4339 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-28 22:41:36.497  4339  4339 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-28 22:41:36.497  4339  4339 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-28 22:41:36.497  4339  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-28 22:41:36.497  4339  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-28 22:41:36.497  4339  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-28 22:41:36.497  4339  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-28 22:41:36.497  4339  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-28 22:41:36.497  4339  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-28 22:41:36.497  4339  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-28 22:41:36.497  4339  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-28 22:41:36.497  4339  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-28 22:41:36.497  4339  4339 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-28 22:41:36.497  4339  4339 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-28 22:41:36.497  4339  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-28 22:41:36.497  4339  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-28 22:41:36.497  4339  4339 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-28 22:41:36.497  4339  4339 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-28 22:41:36.497  4339  4339 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-28 22:41:36.497  4339  4339 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-28 22:41:36.497  4339  4339 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-28 22:41:36.497  4339  4339 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-28 22:41:36.497  4339  4339 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-28 22:41:36.497  4339  4339 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-28 22:41:36.497  4339  4339 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-28 22:41:36.497  4339  4339 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-28 22:41:36.497  4339  4339 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-28 22:41:36.497  4339  4339 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-28 22:41:36.497  4339  4339 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-28 22:41:36.497  4339  4339 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-28 22:41:36.497  4339  4339 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-28 22:41:36.497  4339  4339 D AndroidRuntime: Shutting down VM

```
