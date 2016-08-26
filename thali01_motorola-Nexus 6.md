#### Test 79763830eafb657_thali01_motorola-Nexus 6 Logs


```
--------- beginning of system
08-26 12:02:41.734   874  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,--------- beginning of main
08-26 12:02:43.275  3753  3753 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-26 12:02:43.280  3753  3753 D AndroidRuntime: CheckJNI is OFF
08-26 12:02:43.324  3753  3753 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-26 12:02:43.376  3753  3753 I Radio-JNI: register_android_hardware_Radio DONE
08-26 12:02:43.399  3753  3753 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-26 12:02:43.405   874  1995 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-26 12:02:43.448  2031  2418 W SearchService: Abort, client detached.
08-26 12:02:43.452  2031  2031 I HotwordDetector: Closing mic
08-26 12:02:43.453  2031  2309 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@2a6501d
08-26 12:02:43.453  2031  2333 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-26 12:02:43.457  3753  3753 D AndroidRuntime: Shutting down VM
08-26 12:02:43.518   378  2338 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-26 12:02:43.519   378  2338 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-26 12:02:43.526   378  1279 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-26 12:02:43.528   874   884 I ActivityManager: Start proc 3763:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-26 12:02:43.531  2031  2326 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-26 12:02:43.531  2031  2332 I MicroRecognitionRnrImpl: Detection finished
08-26 12:02:43.615  3763  3763 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-26 12:02:43.626  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-26 12:02:43.630  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-26 12:02:43.631  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-26 12:02:43.645  3763  3763 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-26 12:02:43.647  1500  2037 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-26 12:02:43.647  1500  2037 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-26 12:02:43.647  1500  2037 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 12:02:43.647  1500  2037 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-26 12:02:43.651  3763  3763 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9628-9631)
08-26 12:02:43.651  3763  3763 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 12:02:43.658  3507  3507 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-26 12:02:43.658  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-26 12:02:43.658  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-26 12:02:43.666  3763  3763 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1e09030}
08-26 12:02:43.666  3763  3763 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 12:02:43.667  3763  3763 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-26 12:02:43.676  3763  3763 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-26 12:02:43.677  3763  3763 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-26 12:02:43.687  3763  3763 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-26 12:02:43.696  3763  3763 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-26 12:02:43.696  3763  3763 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 12:02:43.696  3763  3763 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-26 12:02:43.696  3763  3763 I Adreno  : Build Date                       : 10/20/15
08-26 12:02:43.696  3763  3763 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 12:02:43.696  3763  3763 I Adreno  : Local Branch                     : M14
08-26 12:02:43.696  3763  3763 I Adreno  : Remote Branch                    : 
08-26 12:02:43.696  3763  3763 I Adreno  : Remote Branch                    : 
08-26 12:02:43.696  3763  3763 I Adreno  : Reconstruct Branch               : 
,08-26 12:02:43.728   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ec88cef:true
,08-26 12:02:43.765  3763  3763 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-26 12:02:43.777  3763  3763 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-26 12:02:43.817  3763  3802 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-26 12:02:43.825  3763  3788 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-26 12:02:43.842  3763  3802 I OpenGLRenderer: Initialized EGL, version 1.4
,08-26 12:02:43.860  1872  1872 I Keyboard.Facilitator: onFinishInput()
,08-26 12:02:43.904   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +409ms
,08-26 12:02:43.973  3763  3763 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3763
,08-26 12:02:44.072  3763  3763 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-26 12:02:44.221  3763  3805 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1700792016
,08-26 12:02:44.237  3763  3805 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-26 12:02:44.237  3763  3805 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 12:02:44.237  3763  3805 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 12:02:44.237  3763  3805 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 12:02:44.237  3763  3805 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-26 12:02:44.237  3763  3805 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c6ff87 added. We now have 1 listener(s)
,08-26 12:02:44.241  3763  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-26 12:02:44.243  3763  3805 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 12:02:44.244  3763  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 12:02:44.244  3763  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 12:02:44.251  3763  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-26 12:02:44.251  3763  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 12:02:44.251  3763  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 12:02:44.251  3763  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-26 12:02:44.251  3763  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 12:02:44.251  3763  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 12:02:44.251  3763  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 12:02:44.251  3763  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 12:02:44.251  3763  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 12:02:44.251  3763  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 12:02:44.251  3763  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 12:02:44.251  3763  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 12:02:44.251  3763  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-26 12:02:44.251  3763  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-26 12:02:44.251  3763  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f48f652 added. We now have 1 listener(s)
08-26 12:02:44.251  3763  3805 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 12:02:44.256   874  1309 D WifiService: New client listening to asynchronous messages
08-26 12:02:44.258  3763  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 12:02:44.258  3763  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-26 12:02:44.258  3763  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-26 12:02:44.258  3763  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-26 12:02:44.258  3763  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-26 12:02:44.262  3763  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 12:02:44.262  3763  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-26 12:02:44.268  3763  3805 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-26 12:02:44.268  3763  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 12:02:44.268  3763  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:02:44.268  3763  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:02:44.268  3763  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:02:44.268  3763  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:02:44.268  3763  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:02:44.268  3763  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:02:44.268  3763  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 12:02:44.268  3763  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-26 12:02:44.268  3763  3805 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 12:02:44.270  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:02:44.272  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:02:44.273  3763  3805 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-26 12:02:44.296  3763  3763 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-26 12:02:44.315   874  1392 I ActivityManager: Killing 2991:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-26 12:02:44.352   874  1392 I ActivityManager: Killing 3110:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,08-26 12:02:44.751   874  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-26 12:02:45.155  3763  3811 W jxcore-log: Initializing JXcore engine
,08-26 12:02:45.155  3763  3811 W jxcore-log: JXcore engine is ready
,08-26 12:02:45.190  3811  3811 W Thread-322: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8796 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-26 12:02:45.193  3811  3811 W Thread-322: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11642]" dev="sockfs" ino=11642 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-26 12:02:45.193  3811  3811 W Thread-322: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-26 12:02:45.193  3811  3811 W Thread-322: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[22517]" dev="sockfs" ino=22517 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-26 12:02:45.210  3763  3811 W jxcore-log: Starting JXcore engine
,08-26 12:02:45.296  3763  3811 W jxcore-log: Platform android
08-26 12:02:45.296  3763  3811 W jxcore-log: 
,08-26 12:02:45.296  3763  3811 W jxcore-log: Process ARCH arm
08-26 12:02:45.296  3763  3811 W jxcore-log: 
,08-26 12:02:45.542  3763  3811 I jxcore-log: JXcore Cordova bridge is ready!
08-26 12:02:45.542  3763  3811 I jxcore-log: 
,08-26 12:02:45.542  3763  3811 W jxcore-log: JXcore engine is started
,08-26 12:02:45.555  3763  3805 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-26 12:02:45.563  3763  3763 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-26 12:02:48.117   874  1308 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-26 12:02:51.508  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 12:02:51.509  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 12:02:51.551  1500  1511 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-26 12:02:51.551  1500  1511 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-26 12:02:51.551  1500  1511 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 12:02:51.551  1500  1511 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 12:02:51.581  3010  3821 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-26 12:02:51.581  3010  3821 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-26 12:02:51.581  3010  3821 E HttpOperation: 	at jdm.a(PG:82)
08-26 12:02:51.581  3010  3821 E HttpOperation: 	at jcs.o(PG:406)
08-26 12:02:51.581  3010  3821 E HttpOperation: 	at jcn.a(PG:1379)
08-26 12:02:51.581  3010  3821 E HttpOperation: 	at jcs.i(PG:143)
08-26 12:02:51.581  3010  3821 E HttpOperation: 	at blb.a(PG:3937)
08-26 12:02:51.581  3010  3821 E HttpOperation: 	at czp.a(PG:18188)
08-26 12:02:51.581  3010  3821 E HttpOperation: 	at czp.a(PG:9081)
08-26 12:02:51.581  3010  3821 E HttpOperation: 	at czq.run(PG:1686)
08-26 12:02:51.581  3010  3821 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 12:02:51.581  3010  3821 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 12:02:51.581  3010  3821 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 12:02:51.581  3010  3821 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 12:02:51.581  3010  3821 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-26 12:02:51.581  3010  3821 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-26 12:02:51.581  3010  3821 E HttpOperation: 	at jdj.a(PG:4091)
08-26 12:02:51.581  3010  3821 E HttpOperation: 	at jdj.a(PG:1125)
08-26 12:02:51.581  3010  3821 E HttpOperation: 	at jdm.a(PG:77)
08-26 12:02:51.581  3010  3821 E HttpOperation: 	... 12 more
08-26 12:02:51.581  3010  3821 E HttpOperation: Caused by: faj: BadAuthentication
08-26 12:02:51.581  3010  3821 E HttpOperation: 	at fal.a(PG:38)
08-26 12:02:51.581  3010  3821 E HttpOperation: 	at jdj.a(PG:4089)
08-26 12:02:51.581  3010  3821 E HttpOperation: 	... 14 more
,08-26 12:02:51.637  1500  2283 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-26 12:02:51.638  1500  2283 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-26 12:02:51.638  1500  2283 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 12:02:51.638  1500  2283 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 12:02:51.663  3010  3821 E HttpOperation: [getmobileexperiments] Unexpected exception
08-26 12:02:51.663  3010  3821 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-26 12:02:51.663  3010  3821 E HttpOperation: 	at jdm.a(PG:82)
08-26 12:02:51.663  3010  3821 E HttpOperation: 	at jcs.o(PG:406)
08-26 12:02:51.663  3010  3821 E HttpOperation: 	at jcn.a(PG:1379)
08-26 12:02:51.663  3010  3821 E HttpOperation: 	at jcs.i(PG:143)
08-26 12:02:51.663  3010  3821 E HttpOperation: 	at hec.a(PG:42)
08-26 12:02:51.663  3010  3821 E HttpOperation: 	at hee.a(PG:102)
08-26 12:02:51.663  3010  3821 E HttpOperation: 	at czr.a(PG:65)
08-26 12:02:51.663  3010  3821 E HttpOperation: 	at kka.a(PG:108)
08-26 12:02:51.663  3010  3821 E HttpOperation: 	at czp.a(PG:19176)
08-26 12:02:51.663  3010  3821 E HttpOperation: 	at czp.a(PG:9081)
08-26 12:02:51.663  3010  3821 E HttpOperation: 	at czq.run(PG:1686)
08-26 12:02:51.663  3010  3821 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 12:02:51.663  3010  3821 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 12:02:51.663  3010  3821 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 12:02:51.663  3010  3821 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 12:02:51.663  3010  3821 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-26 12:02:51.663  3010  3821 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-26 12:02:51.663  3010  3821 E HttpOperation: 	at jdj.a(PG:4091)
08-26 12:02:51.663  3010  3821 E HttpOperation: 	at jdj.a(PG:1125)
08-26 12:02:51.663  3010  3821 E HttpOperation: 	at jdm.a(PG:77)
08-26 12:02:51.663  3010  3821 E HttpOperation: 	... 15 more
08-26 12:02:51.663  3010  3821 E HttpOperation: Caused by: faj: BadAuthentication
08-26 12:02:51.663  3010  3821 E HttpOperation: 	at fal.a(PG:38)
08-26 12:02:51.663  3010  3821 E HttpOperation: 	at jdj.a(PG:4089)
08-26 12:02:51.663  3010  3821 E HttpOperation: 	... 17 more
,08-26 12:02:51.663  3010  3821 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-26 12:02:51.663  3010  3821 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-26 12:02:51.663  3010  3821 E ExperimentLoader: 	at jdm.a(PG:82)
08-26 12:02:51.663  3010  3821 E ExperimentLoader: 	at jcs.o(PG:406)
08-26 12:02:51.663  3010  3821 E ExperimentLoader: 	at jcn.a(PG:1379)
08-26 12:02:51.663  3010  3821 E ExperimentLoader: 	at jcs.i(PG:143)
08-26 12:02:51.663  3010  3821 E ExperimentLoader: 	at hec.a(PG:42)
08-26 12:02:51.663  3010  3821 E ExperimentLoader: 	at hee.a(PG:102)
08-26 12:02:51.663  3010  3821 E ExperimentLoader: 	at czr.a(PG:65)
08-26 12:02:51.663  3010  3821 E ExperimentLoader: 	at kka.a(PG:108)
08-26 12:02:51.663  3010  3821 E ExperimentLoader: 	at czp.a(PG:19176)
08-26 12:02:51.663  3010  3821 E ExperimentLoader: 	at czp.a(PG:9081)
08-26 12:02:51.663  3010  3821 E ExperimentLoader: 	at czq.run(PG:1686)
08-26 12:02:51.663  3010  3821 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 12:02:51.663  3010  3821 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 12:02:51.663  3010  3821 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 12:02:51.663  3010  3821 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 12:02:51.663  3010  3821 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-26 12:02:51.663  3010  3821 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-26 12:02:51.663  3010  3821 E ExperimentLoader: 	at jdj.a(PG:4091)
08-26 12:02:51.663  3010  3821 E ExperimentLoader: 	at jdj.a(PG:1125)
08-26 12:02:51.663  3010  3821 E ExperimentLoader: 	at jdm.a(PG:77)
08-26 12:02:51.663  3010  3821 E ExperimentLoader: 	... 15 more
08-26 12:02:51.663  3010  3821 E ExperimentLoader: Caused by: faj: BadAuthentication
08-26 12:02:51.663  3010  3821 E ExperimentLoader: 	at fal.a(PG:38)
08-26 12:02:51.663  3010  3821 E ExperimentLoader: 	at jdj.a(PG:4089)
08-26 12:02:51.663  3010  3821 E ExperimentLoader: 	... 17 more
,08-26 12:02:51.800   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 127313, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-26 12:02:55.277  3763  3811 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-26 12:02:55.277  3763  3811 I jxcore-log: 
08-26 12:02:55.279  3763  3811 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-26 12:02:55.279  3763  3811 I jxcore-log: 
,08-26 12:02:55.292  3763  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 12:02:55.292  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:02:55.292  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:02:55.292  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:02:55.292  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:02:55.292  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:02:55.292  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:02:55.292  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 12:02:55.299  3763  3811 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 12:02:55.301  3763  3811 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-26 12:02:55.301  3763  3811 I jxcore-log: 
,08-26 12:02:55.303  3763  3811 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-26 12:02:55.303  3763  3811 I jxcore-log: 
,08-26 12:02:55.801  3763  3811 D executeNativeTests: Running unit tests
,08-26 12:02:55.859  3763  3811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 12:02:55.859  3763  3811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2fe084 added. We now have 2 listener(s)
,08-26 12:02:55.860  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 12:02:55.860  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 12:02:55.860  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 12:02:55.860  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 12:02:55.861  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d added. We now have 2 listener(s)
08-26 12:02:55.861  3763  3811 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 12:02:55.861  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 12:02:55.873  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 12:02:55.886  3763  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 12:02:55.886  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:02:55.886  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:02:55.886  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:02:55.886  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:02:55.886  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:02:55.886  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:02:55.886  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 12:02:55.891  3763  3811 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 12:02:55.892  3763  3811 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 12:02:55.897  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:02:55.899  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-26 12:02:55.902  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:02:55.903  3763  3811 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 12:02:55.903  3763  3811 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-26 12:02:55.907  3763  3811 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-26 12:02:55.907  3763  3811 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 12:02:55.908  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 12:02:55.908  3763  3811 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 12:02:55.908  3763  3811 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-26 12:02:55.909  3763  3811 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 12:02:55.910  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:02:55.910  3763  3811 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:02:55.911  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:02:55.911  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 12:02:55.912  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 12:02:55.912  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 12:02:55.912  3763  3811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2fe084 removed from the list
08-26 12:02:55.913  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:02:55.913  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d removed from the list
08-26 12:02:55.913  3763  3811 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 12:02:55.913  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:55.915  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:55.915  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 12:02:55.917  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:02:55.918  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 12:02:55.918  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:02:55.918  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list
,08-26 12:02:55.921  3763  3811 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-26 12:02:55.922  3763  3811 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:02:55.922  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:02:55.922  3763  3811 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:02:55.922  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:02:55.922  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:55.922  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:55.922  3763  3811 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2fe084 not in the list
08-26 12:02:55.922  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:02:55.922  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list
08-26 12:02:55.923  3763  3811 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 12:02:55.923  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:55.923  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:55.923  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:55.923  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:55.924  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:02:55.924  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:02:55.924  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:02:55.924  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list
,08-26 12:02:55.930  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 12:02:55.930  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-26 12:02:55.930  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 12:02:55.930  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 12:02:55.930  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 12:02:55.930  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 12:02:55.930  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 12:02:55.930  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 12:02:55.930  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 12:02:55.930  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 12:02:55.931  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 12:02:55.931  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-26 12:02:55.931  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 12:02:55.931  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 12:02:55.931  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 12:02:55.931  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 12:02:55.931  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 12:02:55.931  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 12:02:55.931  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 12:02:55.932  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 12:02:55.932  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 12:02:55.932  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-26 12:02:55.932  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 12:02:55.932  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 12:02:55.932  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 12:02:55.932  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 12:02:55.932  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 12:02:55.932  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 12:02:55.932  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 12:02:55.933  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-26 12:02:55.933  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 12:02:55.933  3763  3811 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:02:55.933  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:02:55.933  3763  3811 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:02:55.933  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:02:55.933  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:55.933  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:55.933  3763  3811 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2fe084 not in the list
,08-26 12:02:55.934  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:02:55.934  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list
08-26 12:02:55.934  3763  3811 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:02:55.934  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:55.934  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:55.934  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:55.934  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 12:02:55.935  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 12:02:55.936  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:02:55.936  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:02:55.936  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list
08-26 12:02:55.936  3763  3811 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-26 12:02:55.938  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 12:02:55.943  3763  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 12:02:55.943  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:02:55.943  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:02:55.943  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:02:55.943  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:02:55.943  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:02:55.943  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:02:55.943  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 12:02:55.947  3763  3811 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 12:02:55.947  3763  3811 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 12:02:55.948  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 12:02:55.948  3763  3811 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 12:02:55.948  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 12:02:55.948  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 12:02:55.948  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 12:02:55.951  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:02:55.953  3763  3811 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-26 12:02:55.953  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 12:02:55.955  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:02:55.961  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 12:02:55.964  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-26 12:02:55.965  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 12:02:55.972  3763  3811 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-26 12:02:55.979  3763  3811 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-26 12:02:55.979  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 12:02:55.980  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-26 12:02:55.982  3763  3811 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 12:02:55.984  3763  3811 D BluetoothAdapter: STATE_ON
,08-26 12:02:55.993  2666  2816 D BtGatt.GattService: registerClient() - UUID=ef6cb8ba-f964-48cb-ab1e-e62243e0fc8e
,08-26 12:02:55.995  2666  2699 D BtGatt.GattService: onClientRegistered() - UUID=ef6cb8ba-f964-48cb-ab1e-e62243e0fc8e, clientIf=5
,08-26 12:02:55.996  3763  3803 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-26 12:02:55.997  2666  2677 D BtGatt.GattService: start scan with filters
,08-26 12:02:56.005  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 12:02:56.005  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 12:02:56.005  2666  2702 D BtGatt.ScanManager: handling starting scan
08-26 12:02:56.006  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 12:02:56.006  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 12:02:56.009  2666  2702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcbab3a
,08-26 12:02:56.017  3763  3811 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 12:02:56.017  3763  3811 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 12:02:56.018  3763  3763 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 12:02:56.019  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 12:02:56.021  2666  2699 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 12:02:56.021  2666  2699 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 12:02:56.023  2666  2702 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 12:02:56.024  3763  3811 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 12:02:56.032  3763  3811 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:02:56.032  3763  3811 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 12:02:56.032  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 12:02:56.032  3763  3811 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-26 12:02:56.032  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.033  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-26 12:02:56.033  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-26 12:02:56.033  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 12:02:56.033  3763  3811 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 12:02:56.034  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 12:02:56.038  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-26 12:02:56.039  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 12:02:56.041  3763  3811 D BluetoothAdapter: STATE_ON
,08-26 12:02:56.041  2666  2699 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 12:02:56.041  2666  2699 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:02:56.043  2666  2702 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 12:02:56.043  2666  2816 D BtGatt.GattService: stopScan() - queue size =1
,08-26 12:02:56.043  2666  2702 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 12:02:56.045  2666  2677 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-26 12:02:56.046  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 12:02:56.047  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 12:02:56.047  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 12:02:56.047  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 12:02:56.048  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 12:02:56.051  3763  3811 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 12:02:56.051  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 12:02:56.051  3763  3811 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-26 12:02:56.052  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 12:02:56.053  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 12:02:56.055  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 12:02:56.056  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 12:02:56.056  3763  3763 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 12:02:56.056  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 12:02:56.057  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.057  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 12:02:56.057  3763  3811 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2fe084 not in the list
,08-26 12:02:56.057  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:02:56.057  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list
08-26 12:02:56.057  3763  3811 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:02:56.057  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 12:02:56.059  3763  3811 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-26 12:02:56.064  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 12:02:56.068  2666  2699 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 12:02:56.068  2666  2699 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 12:02:56.075  3763  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 12:02:56.075  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:02:56.075  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:02:56.075  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:02:56.075  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:02:56.075  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:02:56.075  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:02:56.075  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 12:02:56.077  3763  3811 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 12:02:56.078  3763  3811 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 12:02:56.078  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 12:02:56.078  3763  3811 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 12:02:56.078  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 12:02:56.078  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 12:02:56.078  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 12:02:56.081  2666  2699 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 12:02:56.081  2666  2699 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:02:56.082  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:02:56.083  3763  3811 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 12:02:56.083  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 12:02:56.086  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:02:56.088  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 12:02:56.088  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 12:02:56.089  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 12:02:56.093  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 12:02:56.093  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 12:02:56.093  3763  3811 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 12:02:56.095  3763  3811 D BluetoothAdapter: STATE_ON
,08-26 12:02:56.096  2666  2699 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-26 12:02:56.096  2666  2699 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:02:56.096  2666  2702 D BtGatt.ScanManager: stopping BLe Batch
08-26 12:02:56.099  2666  2679 D BtGatt.GattService: registerClient() - UUID=1633a3a8-7b64-413b-85ed-05b8d16c1b2e
08-26 12:02:56.099  2666  2699 D BtGatt.GattService: onClientRegistered() - UUID=1633a3a8-7b64-413b-85ed-05b8d16c1b2e, clientIf=5
08-26 12:02:56.100  3763  3774 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-26 12:02:56.100  2666  2816 D BtGatt.GattService: start scan with filters
08-26 12:02:56.105  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 12:02:56.105  2666  2699 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 12:02:56.105  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 12:02:56.105  2666  2699 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 12:02:56.105  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 12:02:56.105  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 12:02:56.105  2666  2702 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-26 12:02:56.111  3763  3811 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 12:02:56.111  3763  3811 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 12:02:56.111  3763  3763 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 12:02:56.114  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 12:02:56.119  3763  3811 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 12:02:56.132  3763  3811 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 12:02:56.132  3763  3811 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 12:02:56.132  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 12:02:56.133  3763  3811 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-26 12:02:56.133  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.133  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 12:02:56.133  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-26 12:02:56.133  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 12:02:56.133  3763  3811 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 12:02:56.133  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 12:02:56.133  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-26 12:02:56.134  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 12:02:56.135  2666  2699 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
08-26 12:02:56.135  2666  2699 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:02:56.135  3763  3811 D BluetoothAdapter: STATE_ON
08-26 12:02:56.135  2666  2699 D BtGatt.GattService: current time is 132115557806
08-26 12:02:56.135  2666  2699 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -84, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-26 12:02:56.136  2666  2677 D BtGatt.GattService: stopScan() - queue size =0
08-26 12:02:56.137  2666  2816 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 12:02:56.137  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 12:02:56.137  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-26 12:02:56.137  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 12:02:56.137  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 12:02:56.137  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 12:02:56.138  2666  2699 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-26 12:02:56.140  3763  3811 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 12:02:56.140  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 12:02:56.140  3763  3811 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 12:02:56.140  2666  2702 D BtGatt.ScanManager: handling starting scan
08-26 12:02:56.140  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 12:02:56.141  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 12:02:56.146  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 12:02:56.146  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 12:02:56.146  3763  3763 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 12:02:56.147  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 12:02:56.147  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.147  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 12:02:56.147  3763  3811 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2fe084 not in the list
,08-26 12:02:56.147  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:02:56.148  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list
08-26 12:02:56.148  2666  2699 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-26 12:02:56.148  2666  2699 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:02:56.149  3763  3811 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 12:02:56.149  2666  2702 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-26 12:02:56.149  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.151  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.151  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 12:02:56.154  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:02:56.154  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 12:02:56.154  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 12:02:56.154  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list
08-26 12:02:56.155  2666  2699 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 12:02:56.155  2666  2699 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 12:02:56.155  3763  3811 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 12:02:56.156  2666  2702 D BtGatt.ScanManager: Starting BLE batch scan
08-26 12:02:56.156  2666  2702 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-26 12:02:56.159  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 12:02:56.171  3763  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 12:02:56.171  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:02:56.171  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:02:56.171  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:02:56.171  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:02:56.171  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:02:56.171  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:02:56.171  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 12:02:56.174  3763  3811 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 12:02:56.175  3763  3811 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 12:02:56.175  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 12:02:56.175  2666  2699 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 12:02:56.175  3763  3811 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-26 12:02:56.175  2666  2699 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 12:02:56.175  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 12:02:56.175  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 12:02:56.175  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 12:02:56.179  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:02:56.180  3763  3811 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 12:02:56.180  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 12:02:56.185  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:02:56.186  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 12:02:56.186  2666  2699 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 12:02:56.186  2666  2699 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 12:02:56.187  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 12:02:56.187  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 12:02:56.197  2666  2699 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 12:02:56.197  2666  2699 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:02:56.198  2666  2702 D BtGatt.ScanManager: stopping BLe Batch
,08-26 12:02:56.198  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 12:02:56.198  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-26 12:02:56.198  3763  3811 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 12:02:56.200  3763  3811 D BluetoothAdapter: STATE_ON
,08-26 12:02:56.208  2666  2699 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-26 12:02:56.208  2666  2699 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:02:56.208  2666  2702 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 12:02:56.209  2666  2677 D BtGatt.GattService: registerClient() - UUID=10388b31-f624-4d67-a63f-40473f02a531
,08-26 12:02:56.210  2666  2699 D BtGatt.GattService: onClientRegistered() - UUID=10388b31-f624-4d67-a63f-40473f02a531, clientIf=5
,08-26 12:02:56.211  3763  3803 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-26 12:02:56.213  2666  2679 D BtGatt.GattService: start scan with filters
,08-26 12:02:56.219  2666  2699 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-26 12:02:56.219  2666  2699 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 12:02:56.223  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 12:02:56.223  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 12:02:56.223  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-26 12:02:56.223  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 12:02:56.224  2666  2702 D BtGatt.ScanManager: handling starting scan
,08-26 12:02:56.229  3763  3811 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 12:02:56.229  3763  3811 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 12:02:56.229  3763  3763 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 12:02:56.231  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 12:02:56.234  2666  2699 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 12:02:56.234  2666  2699 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:02:56.234  2666  2702 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 12:02:56.237  3763  3811 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 12:02:56.238  3763  3811 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:02:56.238  3763  3811 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 12:02:56.239  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 12:02:56.240  3763  3811 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-26 12:02:56.240  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.240  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 12:02:56.240  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 12:02:56.241  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 12:02:56.241  3763  3811 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-26 12:02:56.241  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 12:02:56.241  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 12:02:56.242  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 12:02:56.243  3763  3811 D BluetoothAdapter: STATE_ON
,08-26 12:02:56.244  2666  2699 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-26 12:02:56.244  2666  2699 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 12:02:56.244  2666  2677 D BtGatt.GattService: stopScan() - queue size =1
,08-26 12:02:56.245  2666  2702 D BtGatt.ScanManager: Starting BLE batch scan
08-26 12:02:56.245  2666  2702 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-26 12:02:56.245  2666  2816 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 12:02:56.246  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 12:02:56.246  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 12:02:56.246  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 12:02:56.246  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-26 12:02:56.246  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 12:02:56.248  3763  3811 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 12:02:56.248  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 12:02:56.249  3763  3811 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 12:02:56.249  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 12:02:56.249  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 12:02:56.252  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 12:02:56.252  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 12:02:56.252  3763  3811 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:02:56.253  3763  3811 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 12:02:56.253  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:02:56.253  3763  3811 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 12:02:56.253  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:02:56.253  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 12:02:56.253  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 12:02:56.252  3763  3763 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 12:02:56.254  3763  3811 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2fe084 not in the list
08-26 12:02:56.254  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:02:56.254  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list
,08-26 12:02:56.254  3763  3811 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:02:56.254  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 12:02:56.255  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.255  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.256  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:02:56.256  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:02:56.257  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 12:02:56.257  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list
08-26 12:02:56.258  3763  3811 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-26 12:02:56.259  3763  3811 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:02:56.259  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 12:02:56.259  3763  3811 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:02:56.259  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 12:02:56.259  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.259  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.259  3763  3811 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2fe084 not in the list
,08-26 12:02:56.260  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:02:56.260  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list
08-26 12:02:56.260  2666  2699 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-26 12:02:56.260  3763  3811 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:02:56.260  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 12:02:56.260  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 12:02:56.260  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 12:02:56.260  2666  2699 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 12:02:56.260  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.261  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 12:02:56.261  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:02:56.262  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 12:02:56.262  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list,
08-26 12:02:56.263  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming],
08-26 12:02:56.263  3763  3811 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:02:56.263  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-26 12:02:56.263  3763  3811 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:02:56.263  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:02:56.263  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 12:02:56.263  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.264  3763  3811 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2fe084 not in the list
08-26 12:02:56.264  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 12:02:56.264  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list
08-26 12:02:56.264  3763  3811 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 12:02:56.264  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.264  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.264  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 12:02:56.264  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.265  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:02:56.265  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:02:56.265  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 12:02:56.265  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list
08-26 12:02:56.266  3763  3811 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-26 12:02:56.266  3763  3811 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:02:56.266  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:02:56.266  3763  3811 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 12:02:56.266  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:02:56.267  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 12:02:56.267  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.267  3763  3811 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2fe084 not in the list
08-26 12:02:56.267  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 12:02:56.267  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list
08-26 12:02:56.267  3763  3811 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:02:56.267  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-26 12:02:56.267  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.267  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 12:02:56.267  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.268  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:02:56.268  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 12:02:56.268  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:02:56.268  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list
,08-26 12:02:56.269  2666  2699 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 12:02:56.269  2666  2699 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:02:56.269  3763  3811 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-26 12:02:56.269  3763  3811 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:02:56.269  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:02:56.269  3763  3811 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:02:56.270  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 12:02:56.270  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.270  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.270  3763  3811 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2fe084 not in the list
,08-26 12:02:56.270  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 12:02:56.270  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list
,08-26 12:02:56.270  3763  3811 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 12:02:56.270  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.270  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 12:02:56.270  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 12:02:56.270  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.272  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:02:56.272  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 12:02:56.272  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:02:56.272  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list
08-26 12:02:56.273  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 12:02:56.273  3763  3811 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 12:02:56.273  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 12:02:56.273  3763  3811 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 12:02:56.273  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 12:02:56.273  3763  3811 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 12:02:56.273  3763  3811 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:02:56.274  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:02:56.274  3763  3811 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:02:56.274  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:02:56.274  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.274  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.274  3763  3811 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2fe084 not in the list
08-26 12:02:56.274  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:02:56.274  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list
08-26 12:02:56.274  3763  3811 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:02:56.274  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.274  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.275  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.275  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.276  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:02:56.276  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:02:56.276  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:02:56.277  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list
08-26 12:02:56.278  3763  3811 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 12:02:56.278  3763  3811 E io.jxcore.node.Conne,ctionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 12:02:56.278  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 12:02:56.283  3763  3811 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 12:02:56.283  3763  3811 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-26 12:02:56.284  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 12:02:56.284  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 12:02:56.284  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 12:02:56.284  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 12:02:56.284  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 12:02:56.284  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 12:02:56.284  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 12:02:56.284  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 12:02:56.284  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 12:02:56.284  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 12:02:56.285  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 12:02:56.285  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 12:02:56.285  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 12:02:56.287  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 12:02:56.287  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 12:02:56.287  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 12:02:56.288  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 12:02:56.288  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 12:02:56.288  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 12:02:56.288  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 12:02:56.288  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 12:02:56.288  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 12:02:56.288  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 12:02:56.288  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 12:02:56.288  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 12:02:56.288  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 12:02:56.288  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 12:02:56.289  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 12:02:56.289  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 12:02:56.289  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 12:02:56.289  3763  3811 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-26 12:02:56.289  3763  3811 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 12:02:56.289  3763  3811 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-26 12:02:56.290  3763  3811 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 12:02:56.290  3763  3811 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 12:02:56.290  3763  3811 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-26 12:02:56.290  3763  3811 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 12:02:56.290  3763  3811 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 12:02:56.290  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-26 12:02:56.292  2666  2699 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 12:02:56.292  2666  2699 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:02:56.293  2666  2702 D BtGatt.ScanManager: stopping BLe Batch
08-26 12:02:56.295  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-26 12:02:56.296  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-26 12:02:56.296  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-26 12:02:56.296  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-26 12:02:56.296  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-26 12:02:56.296  3763  3811 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-26 12:02:56.297  3763  3811 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 12:02:56.297  3763  3811 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-26 12:02:56.297  3763  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 386)
08-26 12:02:56.298  3763  3811 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:02:56.298  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:02:56.298  3763  3811 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:02:56.298  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:02:56.298  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.298  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.298  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-26 12:02:56.299  3763  3811 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2fe084 not in the list
08-26 12:02:56.299  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:02:56.299  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list
08-26 12:02:56.299  3763  3811 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:02:56.299  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.299  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.299  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.300  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.301  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:02:56.301  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:02:56.301  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:02:56.301  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list
08-26 12:02:56.301  3763  3827 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 12:02:56.302  3763  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 386
08-26 12:02:56.302  3763  3811 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-26 12:02:56.302  3763  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 386)
08-26 12:02:56.302  3763  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 386)
08-26 12:02:56.303  3763  3811 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:02:56.303  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:02:56.303  3763  3811 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:02:56.303  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:02:56.303  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.303  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.303  3763  3811 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2fe084 not in the list
08-26 12:02:56.303  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:02:56.303  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list
08-26 12:02:56.303  3763  3811 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:02:56.304  3763  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 386)
08-26 12:02:56.304  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.304  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.304  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.304  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.305  2666  2699 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 12:02:56.305  2666  2699 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:02:56.305  2666  2702 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-26 12:02:56.305  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:02:56.306  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:02:56.306  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:02:56.306  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list
08-26 12:02:56.306  3763  3811 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-26 12:02:56.307  3763  3811 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:02:56.307  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:02:56.307  3763  3811 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:02:56.307  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:02:56.307  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.307  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.307  3763  3811 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2fe084 not in the list
08-26 12:02:56.307  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:02:56.307  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list
08-26 12:02:56.307  3763  3811 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:02:56.307  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.307  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.307  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.307  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.309  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:02:56.309  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:02:56.309  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:02:56.309  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list
08-26 12:02:56.309  3763  3811 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-26 12:02:56.309  3763  3811 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-26 12:02:56.310  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 12:02:56.310  3763  3811 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-26 12:02:56.310  3763  3811 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 12:02:56.310  3763  3811 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-26 12:02:56.310  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 12:02:56.310  3763  3811 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-26 12:02:56.310  3763  3811 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 12:02:56.310  3763  3811 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 12:02:56.311  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 12:02:56.311  3763  3811 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-26 12:02:56.311  3763  3811 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:02:56.311  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:02:56.311  3763  3811 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:02:56.311  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:02:56.311  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.311  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.311  3763  3811 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2fe084 not in the list
08-26 12:02:56.311  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:02:56.311  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list
08-26 12:02:56.311  3763  3811 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:02:56.311  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.312  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.312  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.312  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.312  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:02:56.312  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:02:56.313  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:02:56.313  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list
08-26 12:02:56.313  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:02:56.313  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.313  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.313  3763  3811 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2fe084 not in the list
08-26 12:02:56.313  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:02:56.313  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list
08-26 12:02:56.314  3763  3811 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:02:56.314  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.314  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.314  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:02:56.314  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list
08-26 12:02:56.314  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:02:56.314  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.314  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.314  3763  3811 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2fe084 not in the list
08-26 12:02:56.314  3763  3811 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:02:56.314  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:02:56.314  3763  3811 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:02:56.314  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:02:56.315  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.315  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.315  3763  3811 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2fe084 not in the list
08-26 12:02:56.315  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:02:56.315  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list
08-26 12:02:56.315  3763  3811 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:02:56.315  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.315  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.315  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.315  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.318  2666  2699 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 12:02:56.318  2666  2699 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:02:56.321  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:02:56.321  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:02:56.321  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:02:56.321  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list
08-26 12:02:56.323  3763  3811 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-26 12:02:56.323  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 12:02:56.324  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-26 12:02:56.324  3763  3811 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-26 12:02:56.325  3763  3811 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-26 12:02:56.325  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-26 12:02:56.325  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 12:02:56.325  3763  3763 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-26 12:02:56.325  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:02:56.325  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-26 12:02:56.325  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-26 12:02:56.325  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-26 12:02:56.325  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.326  3763  3811 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-26 12:02:56.326  3763  3763 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-26 12:02:56.326  3763  3811 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2fe084 not in the list
08-26 12:02:56.326  3763  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-26 12:02:56.326  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:02:56.326  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 12:02:56.326  3763  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-26 12:02:56.326  3763  3811 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 12:02:56.326  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 12:02:56.326  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.326  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.327  3763  3811 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 12:02:56.327  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 12:02:56.327  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list
08-26 12:02:56.328  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 12:02:56.328  3763  3811 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:02:56.328  3763  3763 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-26 12:02:56.328  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:02:56.328  3763  3763 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 12:02:56.328  3763  3811 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:02:56.328  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:02:56.328  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.328  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.328  3763  3811 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2fe084 not in the list
08-26 12:02:56.328  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:02:56.328  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list
08-26 12:02:56.328  3763  3811 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:02:56.328  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.328  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.328  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.328  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.330  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:02:56.330  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:02:56.330  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:02:56.330  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list
08-26 12:02:56.331  3763  3811 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-26 12:02:56.331  3763  3811 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 12:02:56.331  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 12:02:56.333  3763  3811 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 12:02:56.336  3763  3811 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:02:56.336  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:02:56.336  3763  3811 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:02:56.337  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:02:56.337  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.337  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.337  3763  3811 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2fe084 not in the list
08-26 12:02:56.337  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:02:56.337  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list
08-26 12:02:56.337  3763  3811 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:02:56.337  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.337  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.337  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.337  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.338  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:02:56.338  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:02:56.338  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:02:56.338  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list
08-26 12:02:56.341  3763  3811 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:02:56.341  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:02:56.341  3763  3811 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:02:56.341  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:02:56.341  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.342  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.342  3763  3811 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2fe084 not in the list
08-26 12:02:56.342  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:02:56.342  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list
08-26 12:02:56.342  3763  3811 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:02:56.342  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.342  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.342  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.342  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.343  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:02:56.343  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:02:56.343  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:02:56.343  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list
08-26 12:02:56.344  3763  3811 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:02:56.344  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:02:56.344  3763  3811 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:02:56.344  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:02:56.344  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.344  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.344  3763  3811 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2fe084 not in the list
08-26 12:02:56.344  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:02:56.344  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list
08-26 12:02:56.344  3763  3811 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:02:56.345  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.345  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.345  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:02:56.345  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:02:56.345  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:02:56.346  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:02:56.346  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:02:56.346  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3006d not in the list
,08-26 12:02:56.347  3763  3811 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-26 12:02:56.347  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 12:02:56.347  3763  3811 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-26 12:02:56.347  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 12:02:56.347  3763  3811 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-26 12:02:56.347  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 12:02:56.349  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 12:02:56.349  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-26 12:02:56.349  3763  3811 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-26 12:02:56.349  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 12:02:56.350  3763  3811 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-26 12:02:56.350  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 12:02:56.350  3763  3811 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-26 12:02:56.350  3763  3811 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-26 12:02:56.350  3763  3811 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-26 12:02:56.350  3763  3811 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-26 12:02:56.351  3763  3811 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-26 12:02:56.351  3763  3811 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-26 12:02:56.351  3763  3811 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-26 12:02:56.351  3763  3811 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-26 12:02:56.352  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 12:02:56.352  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a8a2387 added. We now have 2 listener(s)
08-26 12:02:56.352  3763  3811 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 12:02:56.354  3763  3811 D BluetoothAdapter: enable(): BT is already enabled..!
08-26 12:02:56.354   874  1992 D WifiService: setWifiEnabled: true pid=3763, uid=10000
08-26 12:02:56.354   874  1992 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 12:02:56.355  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 12:02:56.355  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@50e72b4 added. We now have 3 listener(s)
08-26 12:02:56.355  3763  3811 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 12:02:56.359  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 12:02:56.359  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@951dedd added. We now have 4 listener(s)
08-26 12:02:56.359  3763  3811 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 12:02:56.361  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 12:02:56.361  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5b16a52 added. We now have 5 listener(s)
08-26 12:02:56.361  3763  3811 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 12:02:56.362   874  1995 D WifiService: setWifiEnabled: false pid=3763, uid=10000
08-26 12:02:56.362   874  1995 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 12:02:56.370  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 12:02:56.370  2666  2695 D BluetoothAdapterState: Current state: ON, message: 23
,08-26 12:02:56.371  2666  2695 D BluetoothAdapterProperties: Setting state to 13
,08-26 12:02:56.371  2666  2695 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-26 12:02:56.371  2666  2695 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 12:02:56.372  2666  2695 I BluetoothAdapterState: Entering PendingCommandState
,08-26 12:02:56.373  2666  2699 D BluetoothAdapterProperties: Scan Mode:20
08-26 12:02:56.373  2666  2695 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-26 12:02:56.374  2666  2666 D BluetoothMapService: onReceive
08-26 12:02:56.374  2666  2666 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:02:56.374  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 12:02:56.374  3763  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 12:02:56.374  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:02:56.374  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:02:56.374  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:02:56.374  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:02:56.374  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:02:56.374  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:02:56.374  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 12:02:56.374  2666  2666 D BluetoothMapService: STATE_TURNING_OFF
08-26 12:02:56.375  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:02:56.375  2666  2666 D BluetoothMapService: MAP Service closeService in
08-26 12:02:56.375  2666  2666 D BluetoothMapMasInstance0: MAP Service shutdown
08-26 12:02:56.375  3763  3811 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 12:02:56.375  3763  3811 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 12:02:56.375  2666  2666 D ObexServerSockets0: shutdown(block = true)
,08-26 12:02:56.375  2666  2666 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-26 12:02:56.376  2666  2666 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 12:02:56.376  2666  2824 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-26 12:02:56.376  2666  2814 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-26 12:02:56.376  2666  2825 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-26 12:02:56.377  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:02:56.377  2666  2666 I BtOppRfcommListener: stopping Accept Thread
,08-26 12:02:56.378  2666  3416 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 12:02:56.378  2666  3416 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-26 12:02:56.379  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:02:56.382  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:02:56.382  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:02:56.382  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:02:56.382  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:02:56.382  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:02:56.382  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:02:56.382  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:02:56.382  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:02:56.382  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 12:02:56.382  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:02:56.382  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 12:02:56.384  1453  1453 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 12:02:56.384  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:02:56.386  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:02:56.387   874  1308 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-26 12:02:56.387   874  1308 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-26 12:02:56.387   874  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 12:02:56.387   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 12:02:56.389  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:02:56.392   874  2254 D DhcpClient: Clearing IP address
,08-26 12:02:56.393   374   872 D CommandListener: Clearing all IP addresses on wlan0
,08-26 12:02:56.395   374   872 D CommandListener: Setting iface cfg
,08-26 12:02:56.397  1500  3489 V NativeCrypto: Read error: ssl=0x9a7bb200: I/O error during system call, Connection timed out
08-26 12:02:56.397   874   887 I ActivityManager: Start proc 3832:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-26 12:02:56.399  2666  2666 D HeadsetService: Received stop request...Stopping profile...
08-26 12:02:56.400  1500  3489 V NativeCrypto: SSL shutdown failed: ssl=0x9a7bb200: I/O error during system call, Broken pipe
08-26 12:02:56.401   874   874 D BluetoothHeadset: Proxy object disconnected
08-26 12:02:56.401   874   874 D BluetoothHeadset: Proxy object disconnected
08-26 12:02:56.401   874   874 D BluetoothHeadset: Proxy object disconnected
,08-26 12:02:56.402  1946  1958 D BluetoothHeadset: Proxy object disconnected
08-26 12:02:56.402  1351  2072 D BluetoothHeadset: Proxy object disconnected
08-26 12:02:56.403   874  1308 D WifiStateMachine: Start Disconnecting Watchdog 1
08-26 12:02:56.403  1351  1351 D HeadsetProfile: Bluetooth service disconnected
08-26 12:02:56.403   874  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 12:02:56.404   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-26 12:02:56.404   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-26 12:02:56.404  2666  2666 D A2dpService: Received stop request...Stopping profile...
08-26 12:02:56.404  2666  2819 D A2dpStateMachine: Exit Disconnected: -1
08-26 12:02:56.408   374   872 D CommandListener: Clearing all IP addresses on wlan0
,08-26 12:02:56.408   397   397 E Parcel  : Reading a NULL string not supported here.
08-26 12:02:56.411   874  1310 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-26 12:02:56.413   874   874 D BluetoothA2dp: Proxy object disconnected
08-26 12:02:56.413  1351  1351 D BluetoothA2dp: Proxy object disconnected
,08-26 12:02:56.413  2666  2666 V BluetoothAdapterState: isTurningOff()=true
08-26 12:02:56.413  2666  2666 V BluetoothAdapterState: isTurningOn()=false
08-26 12:02:56.414  2666  2666 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:02:56.414  2666  2666 V BluetoothAdapterState: isBleTurningOff()=false
08-26 12:02:56.416  2666  2666 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 12:02:56.416  2666  2699 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-26 12:02:56.416  2666  2784 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 12:02:56.416  2666  2666 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 12:02:56.416  2666  2784 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 12:02:56.416  2666  2784 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 12:02:56.416  2666  2699 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-26 12:02:56.417  2666  2666 D HidService: Received stop request...Stopping profile...
08-26 12:02:56.417  2666  2666 D HidService: Stopping Bluetooth HidService
,08-26 12:02:56.418  1351  1351 D BluetoothInputDevice: Proxy object disconnected
08-26 12:02:56.418  1351  1351 D HidProfile: Bluetooth service disconnected
08-26 12:02:56.420   874  2257 D DhcpClient: Receive thread stopped
08-26 12:02:56.421   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
08-26 12:02:56.422  2666  2666 D HealthService: Received stop request...Stopping profile...
08-26 12:02:56.422  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:02:56.422  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:02:56.422  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:02:56.422  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:02:56.422  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 12:02:56.422  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:02:56.422  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:02:56.422  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:02:56.422  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 12:02:56.423  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 12:02:56.423  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 12:02:56.423   874  1308 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 12:02:56.425  1884  2279 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 12:02:56.425  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 12:02:56.425  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:02:56.425  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:02:56.425  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:02:56.425  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 12:02:56.425  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:02:56.425  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:02:56.425  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:02:56.425  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 12:02:56.426  2666  2666 D PanService: Received stop request...Stopping profile...
08-26 12:02:56.427  1351  1351 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 12:02:56.427  1351  1351 D PanProfile: Bluetooth service disconnected
08-26 12:02:56.427  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:02:56.427  2666  2666 V BluetoothAdapterState: isTurningOff()=true
08-26 12:02:56.427  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 12:02:56.427  2666  2666 V BluetoothAdapterState: isTurningOn()=false
08-26 12:02:56.427  2666  2666 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:02:56.427  2666  2666 V BluetoothAdapterState: isBleTurningOff()=false
08-26 12:02:56.428  2666  2666 D BluetoothMapService: Received stop request...Stopping profile...
08-26 12:02:56.428  2666  2666 D BluetoothMapService: stop()
08-26 12:02:56.429  2666  2666 D BluetoothMapAppObserver: deinitObservers()
,08-26 12:02:56.429  2666  2666 D BluetoothMapAppObserver: removeReceiver()
,08-26 12:02:56.430  1351  1351 D BluetoothMap: Proxy object disconnected
08-26 12:02:56.430  1351  1351 D MapProfile: Bluetooth service disconnected
08-26 12:02:56.432  2666  2784 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 12:02:56.432  2666  2699 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-26 12:02:56.433  2666  2784 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 12:02:56.433  2666  2784 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-26 12:02:56.433  2666  2784 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 12:02:56.433  2666  2784 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 12:02:56.433  2666  2784 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-26 12:02:56.434  2666  2666 V BluetoothAdapterState: isTurningOff()=true
08-26 12:02:56.434  2666  2666 V BluetoothAdapterState: isTurningOn()=false
08-26 12:02:56.435  2666  2666 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:02:56.435  2666  2666 V BluetoothAdapterState: isBleTurningOff()=false
08-26 12:02:56.440  2666  2666 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 12:02:56.440  2666  2699 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-26 12:02:56.440  2666  2666 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-26 12:02:56.440  2666  2666 V BluetoothAdapterState: isTurningOff()=true
08-26 12:02:56.440  2666  2666 V BluetoothAdapterState: isTurningOn()=false
08-26 12:02:56.441  2666  2666 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:02:56.441  2666  2666 V BluetoothAdapterState: isBleTurningOff()=false
08-26 12:02:56.441  2666  2666 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 12:02:56.442  2666  2699 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-26 12:02:56.442  2666  2666 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 12:02:56.442  2666  2666 V BluetoothAdapterState: isTurningOff()=true
08-26 12:02:56.442  2666  2666 V BluetoothAdapterState: isTurningOn()=false
,08-26 12:02:56.442  2666  2666 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:02:56.442  2666  2666 V BluetoothAdapterState: isBleTurningOff()=false
08-26 12:02:56.443  2666  2666 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 12:02:56.443  2666  2666 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 12:02:56.443  2666  2666 D BluetoothMapService: MAP Service closeService in
08-26 12:02:56.443  2666  2666 V BluetoothAdapterState: isTurningOff()=true
,08-26 12:02:56.444  2666  2666 V BluetoothAdapterState: isTurningOn()=false
08-26 12:02:56.447  2666  2666 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:02:56.447  2666  2666 V BluetoothAdapterState: isBleTurningOff()=false
08-26 12:02:56.447  2666  2666 D BluetoothMapService: cleanup()
08-26 12:02:56.447  2666  2695 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-26 12:02:56.447  2666  2666 D BluetoothMapService: MAP Service closeService in
08-26 12:02:56.447  2666  2695 D BluetoothAdapterProperties: Setting state to 15
08-26 12:02:56.447  2666  2695 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-26 12:02:56.448  2666  2695 I BluetoothAdapterState: Entering BleOnState
08-26 12:02:56.452   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 12:02:56.452  1351  1365 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 12:02:56.452  1351  2072 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 12:02:56.453  1351  1368 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-26 12:02:56.454   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 12:02:56.454  1946  1957 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 12:02:56.454   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 12:02:56.454   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 12:02:56.454  1351  1365 D BluetoothMap: onBluetoothStateChange: up=false
08-26 12:02:56.454  1351  2072 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 12:02:56.455  1351  1368 D BluetoothPan: onBluetoothStateChange on: false
08-26 12:02:56.455  2666  2695 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-26 12:02:56.455  2666  2695 D BluetoothAdapterProperties: Setting state to 16
08-26 12:02:56.455  2666  2695 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-26 12:02:56.456  2666  2695 D BluetoothAdapterProperties: onBleDisable
08-26 12:02:56.456  2666  2695 I BluetoothAdapterState: Entering PendingCommandState
08-26 12:02:56.456  2666  2696 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-26 12:02:56.457  2666  2784 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-26 12:02:56.457  2666  2784 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 12:02:56.458  2666  2699 D BluetoothAdapterProperties: Scan Mode:20
08-26 12:02:56.460  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:02:56.461  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:02:56.462  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:02:56.464  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:02:56.469  3832  3832 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-26 12:02:56.473   374   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 12:02:56.493   374   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 12:02:56.493   874  1310 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-26 12:02:56.494   874  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 12:02:56.496   874   891 D Tethering: MasterInitialState.processMessage what=3
08-26 12:02:56.498  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:02:56.499  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:02:56.501  3408  3408 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@b001eb4 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-26 12:02:56.504  3832  3832 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 12:02:56.509  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 12:02:56.509   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@732eb4a:true
,08-26 12:02:56.521   874  1995 I ActivityManager: Start proc 3854:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-26 12:02:56.529  3832  3832 D LocalBluetoothProfileManager: Adding local MAP profile
,08-26 12:02:56.532  3832  3832 D BluetoothMap: Create BluetoothMap proxy object
,08-26 12:02:56.537  3832  3832 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-26 12:02:56.549  3832  3832 D DockEventReceiver: finishStartingService: stopping service
,08-26 12:02:56.550   374   872 E Netd    : netlink response contains error (No such file or directory)
,08-26 12:02:56.555  3854  3854 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-26 12:02:56.557   874   885 I ActivityManager: Killing 3211:com.google.android.gm/u0a78 (adj 15): empty #17
,08-26 12:02:56.670  2666  2699 I bt_hci  : shut_down
,08-26 12:02:56.693  2666  2703 I bt_vendor: low_power_mode_cb
,08-26 12:02:56.699  2666  2703 D bt_hwcfg: hw_epilog_process
,08-26 12:02:56.710  2666  2703 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-26 12:02:56.711  2666  2703 I bt_vendor: epilog_cb
,08-26 12:02:56.711  2666  2703 I bt_hci  : epilog_finished_callback
,08-26 12:02:56.718  2666  2699 I bt_hci_h4: hal_close
,08-26 12:02:56.718  2666  2699 I bt_userial_vendor: device fd = 51 close
,08-26 12:02:56.753  3854  3854 D StrictMode: StrictMode policy violation; ~duration=118 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 12:02:56.753  3854  3854 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 12:02:56.753  3854  3854 D StrictMode: 	,at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 12:02:56.753  3854  3854 D StrictMode: StrictMode policy violation; ~duration=117 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 12:02:56.753  3854  3854 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at android.app.Instr,umentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 12:02:56.753  3854  3854 D StrictMode: StrictMode policy violation; ~duration=117 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 12:02:56.753  3854  3854 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 12:02:56.753  3854  3854 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 12:02:56.754  3854  3854 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardP,olicy.onReadFromDisk(StrictMode.java:1263)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.r.e.b(PG:170)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 12:02:56.754  3854  3854 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.r.k.d(PG:583)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.r.e.b(PG:170)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 12:02:56.754  3854  3854 D StrictMode: StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 12:02:56.754  3854  3854 D StrictMode: StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 12:02:56.754  3854  3854 D StrictMode: StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 12:02:56.754  3854  3854 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 12:02:56.794   874  1390 I ActivityManager: Start proc 3886:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
08-26 12:02:56.795   874  1390 I ActivityManager: Killing 3408:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-26 12:02:56.829  3763  3763 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 12:02:56.862  2666  2696 D bt_stack_manager: event_shut_down_stack finished.
,08-26 12:02:56.862  3886  3886 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
08-26 12:02:56.862  2666  2695 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-26 12:02:56.865  2666  2695 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-26 12:02:56.865  2666  2666 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 12:02:56.865  2666  2666 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 12:02:56.866  2666  2666 D BtGatt.GattService: stop()
08-26 12:02:56.866  2666  2666 D BtGatt.AdvertiseManager: advertise clients cleared
08-26 12:02:56.868  2666  2666 V BluetoothAdapterState: isTurningOff()=false
08-26 12:02:56.868  2666  2666 V BluetoothAdapterState: isTurningOn()=false
,08-26 12:02:56.868  2666  2666 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:02:56.868  2666  2666 V BluetoothAdapterState: isBleTurningOff()=true
08-26 12:02:56.869  2666  2695 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-26 12:02:56.869  2666  2695 D BluetoothAdapterProperties: Setting state to 10
08-26 12:02:56.869  2666  2695 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-26 12:02:56.870  2666  2695 I BluetoothAdapterState: Entering OffState
,08-26 12:02:56.873   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-26 12:02:56.883  2666  2666 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-26 12:02:56.883  2666  2666 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-26 12:02:56.883  2666  2666 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-26 12:02:56.884  2666  2696 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-26 12:02:56.885  2666  2696 D bt_stack_manager: event_clean_up_stack finished.
08-26 12:02:56.886  2666  2666 I art     : System.exit called, status: 0
08-26 12:02:56.886  2666  2666 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 12:02:56.957   874  1997 I ActivityManager: Process com.android.bluetooth (pid 2666) has died
,08-26 12:02:56.987  3886  3886 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-26 12:02:57.009  3832  3832 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 12:02:57.026   874  1964 I ActivityManager: Start proc 3914:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
08-26 12:02:57.030  3832  3832 D DockEventReceiver: finishStartingService: stopping service
,08-26 12:02:57.034  3854  3878 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-26 12:02:57.063   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@481d6aa:true
,08-26 12:02:57.109  3914  3914 D AdapterServiceConfig: Adding HeadsetService
08-26 12:02:57.109  3914  3914 D AdapterServiceConfig: Adding A2dpService
08-26 12:02:57.109  3914  3914 D AdapterServiceConfig: Adding HidService
,08-26 12:02:57.109  3914  3914 D AdapterServiceConfig: Adding HealthService
08-26 12:02:57.109  3914  3914 D AdapterServiceConfig: Adding PanService
08-26 12:02:57.110  3914  3914 D AdapterServiceConfig: Adding GattService
08-26 12:02:57.110  3914  3914 D AdapterServiceConfig: Adding BluetoothMapService
,08-26 12:02:57.113   874   884 I ActivityManager: Killing 2786:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-26 12:02:57.142  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 12:02:57.161  1712  1712 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 12:02:57.167  1712  1712 D SystemUpdateService: onCreate,
,08-26 12:02:57.175  1712  1712 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 12:02:57.189  1712  3926 I SystemUpdateService: active receiver: enabled
,08-26 12:02:57.204  1712  3926 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 12:02:57.205  1712  1712 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-26 12:02:57.207  1712  2542 I iu.UploadsManager: num queued entries: 0
08-26 12:02:57.207  1712  3926 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-26 12:02:57.207  1712  3926 I SystemUpdateService: now status is 0 (complete)
08-26 12:02:57.207  1712  2542 I iu.UploadsManager: num updated entries: 0
08-26 12:02:57.207  1712  3926 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-26 12:02:57.207  1712  3926 I SystemUpdateService: file has been verified
,08-26 12:02:57.207  1712  3926 I SystemUpdateService: OTA package size = 12249756
08-26 12:02:57.208  1712  2542 I iu.SyncManager: NEXT; no task
,08-26 12:02:57.213  1712  3926 I SystemUpdateService: showing system update notification
,08-26 12:02:57.237  1712  1712 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 12:02:57.239  1712  1712 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-26 12:02:57.239  1712  1712 D SystemUpdateService: onDestroy
,08-26 12:02:57.258   874  1978 I ActivityManager: Start proc 3928:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-26 12:02:57.296  3928  3928 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-26 12:02:57.301  3928  3928 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 12:02:57.309  3928  3928 D SprintDMHelper: simOperator: 
08-26 12:02:57.309  3928  3928 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 12:02:57.352   874  1992 I ActivityManager: Start proc 3940:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-26 12:02:57.355   874  1992 I ActivityManager: Killing 1695:android.process.acore/u0a5 (adj 15): empty #17
,08-26 12:02:57.562  2258  3954 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-26 12:02:57.604   874   884 I ActivityManager: Start proc 3955:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-26 12:02:57.614   874  1964 I ActivityManager: Killing 3619:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-26 12:02:57.691  3955  3955 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-26 12:02:57.769  3955  3955 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-26 12:02:57.769  3955  3955 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-26 12:02:57.769  3955  3955 I GAv4    :   adb logcat -s GAv4
,08-26 12:02:57.793  3955  3955 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-26 12:02:57.800  3955  3955 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-26 12:02:57.826  3955  3973 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-26 12:02:57.916  3955  3955 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-26 12:02:57.952  3955  3955 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-26 12:02:57.959  3955  3955 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3936-3939)
08-26 12:02:57.959  3955  3955 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-26 12:02:57.968  3955  3955 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {5429ce4}
,08-26 12:02:57.968  3955  3955 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 12:02:57.968  3955  3955 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-26 12:02:57.974  3955  3955 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-26 12:02:57.975  3955  3955 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-26 12:02:57.991  3955  3955 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-26 12:02:58.004  3955  3955 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 12:02:58.004  3955  3955 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-26 12:02:58.004  3955  3955 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-26 12:02:58.004  3955  3955 I Adreno  : Build Date                       : 10/20/15
08-26 12:02:58.004  3955  3955 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 12:02:58.004  3955  3955 I Adreno  : Local Branch                     : M14
08-26 12:02:58.004  3955  3955 I Adreno  : Remote Branch                    : 
08-26 12:02:58.004  3955  3955 I Adreno  : Remote Branch                    : 
08-26 12:02:58.004  3955  3955 I Adreno  : Reconstruct Branch               : 
,08-26 12:02:58.061  3955  3955 I NSApplication: Starting up...
,08-26 12:02:58.063  3955  4001 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-26 12:02:58.107   874   884 I ActivityManager: Start proc 4006:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-26 12:02:58.109   874   884 I ActivityManager: Killing 3635:com.android.musicfx/u0a18 (adj 15): empty #17
,08-26 12:02:58.245  4006  4006 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-26 12:02:58.452   874  1711 I ActivityManager: Killing 3440:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-26 12:02:59.378   874  1990 D WifiService: setWifiEnabled: true pid=3763, uid=10000
,08-26 12:02:59.378   874  1990 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 12:02:59.391   874  1308 D WifiConfigStore: Loading config and enabling all networks 
,08-26 12:02:59.400  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:02:59.401  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:02:59.401  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:02:59.401  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:02:59.401  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:02:59.401  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:02:59.401  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:02:59.401  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:02:59.401  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 12:02:59.401  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:02:59.401  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 12:02:59.404  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:02:59.405  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:02:59.405  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:02:59.405  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:02:59.405  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:02:59.405  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:02:59.405  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:02:59.405  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:02:59.405  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 12:02:59.405  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:02:59.405  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 12:02:59.440   874  1308 D WifiConfigStore: loaded 0 passpoint configs
,08-26 12:02:59.441   874  1308 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-26 12:02:59.442   874  1308 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-26 12:02:59.442   874  1308 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-26 12:02:59.443   874  1308 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-26 12:02:59.443   874  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-26 12:02:59.443   874  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-26 12:02:59.455   374   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-26 12:02:59.456   874  1308 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.00 rxSuccessRate=19.75 delta 1000 -> 994
,08-26 12:02:59.458   374   872 D CommandListener: Setting iface cfg
,08-26 12:02:59.461   874  1307 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '129 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 129 Failed to set address (No such device)'
,08-26 12:02:59.461   874  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-26 12:02:59.467   874  1308 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-26 12:02:59.468   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 12:02:59.472   874  1307 D WifiNative-HAL: p2pGetDeviceAddress
,08-26 12:02:59.480   874  1308 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-26 12:02:59.480   874  1307 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-26 12:02:59.557   874  1308 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-26 12:02:59.561  1453  1453 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-26 12:02:59.988  1453  1453 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-26 12:03:00.026  1453  1453 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-26 12:03:00.027  1453  1453 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-26 12:03:00.033   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 12:03:00.045   874  1308 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 12:03:00.045   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 12:03:00.046   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-26 12:03:00.059   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 12:03:00.069   374   872 D CommandListener: Setting iface cfg
,08-26 12:03:00.069   874  1308 D WifiStateMachine: Start Dhcp Watchdog 2
,08-26 12:03:00.082   874  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-26 12:03:00.083   874  1310 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-26 12:03:00.085   874  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-26 12:03:00.112   874  4029 D DhcpClient: Receive thread started
,08-26 12:03:00.195   874  1308 E native  : do suspend false
,08-26 12:03:00.214   874  2254 D DhcpClient: Broadcasting DHCPDISCOVER
,08-26 12:03:00.231   874  4029 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172688, domain null
,08-26 12:03:00.232   874  2254 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172688 seconds
,08-26 12:03:00.236   874  2254 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-26 12:03:00.249   874  4029 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-26 12:03:00.252   874  2254 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-26 12:03:00.257   374   872 D CommandListener: Setting iface cfg
,08-26 12:03:00.268   874  2254 D DhcpClient: Scheduling renewal in 86399s
,08-26 12:03:00.274   874  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-26 12:03:00.291   874  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-26 12:03:00.294   874  1308 D WifiConfigStore: No blacklist allowed without epno enabled
,08-26 12:03:00.295   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-26 12:03:00.298   874  1310 D ConnectivityService: Adding iface wlan0 to network 101
,08-26 12:03:00.305   874  1308 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 12:03:00.355   874  1310 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-26 12:03:00.355   874  1310 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-26 12:03:00.356   874  1310 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-26 12:03:00.358   874  1310 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-26 12:03:00.359   874  1310 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-26 12:03:00.365   874  1310 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-26 12:03:00.372   874  1310 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-26 12:03:00.372   874  1310 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-26 12:03:00.372   874  1310 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-26 12:03:00.372   874  1310 D ConnectivityService:    accepting network in place of null
,08-26 12:03:00.374   874  1310 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 12:03:00.377   874  1308 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-26 12:03:00.378   874  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-26 12:03:00.389   874  4028 D NetlinkSocketObserver: NeighborEvent{elapsedMs=136368, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-26 12:03:00.405   374   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 12:03:00.436   374   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 12:03:00.440   874  1310 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-26 12:03:00.440   874  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 12:03:00.441   874  1310 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-26 12:03:00.442   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-26 12:03:00.460  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 12:03:00.460  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:03:00.460  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:03:00.460  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:03:00.460  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:03:00.460  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:03:00.460  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:03:00.460  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:03:00.460  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 12:03:00.461  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:03:00.461  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 12:03:00.464  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:03:00.465  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:03:00.465  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:03:00.465  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:03:00.465  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:03:00.465  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:03:00.465  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:03:00.465  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:03:00.465  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 12:03:00.465  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 12:03:00.465  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 12:03:00.471  1712  1712 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 12:03:00.473  1712  1712 D SystemUpdateService: onCreate
,08-26 12:03:00.476  1712  1712 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 12:03:00.478  1712  4040 I SystemUpdateService: active receiver: enabled
,08-26 12:03:00.482   874  4027 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.110,2a00:1450:4001:817::200e
,08-26 12:03:00.485  1712  4040 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 12:03:00.488  1712  4040 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-26 12:03:00.488  1712  4040 I SystemUpdateService: now status is 0 (complete)
08-26 12:03:00.488  1712  4040 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-26 12:03:00.488  1712  4040 I SystemUpdateService: file has been verified
08-26 12:03:00.488  1712  4040 I SystemUpdateService: OTA package size = 12249756
,08-26 12:03:00.492  1712  4040 I SystemUpdateService: showing system update notification
,08-26 12:03:00.498  1712  1712 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-26 12:03:00.499  1712  4043 I MDM     : [176] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-26 12:03:00.500  1712  4043 W BaseAppContext: Using Auth Proxy for data requests.
08-26 12:03:00.501  1712  2542 I iu.UploadsManager: num queued entries: 0
08-26 12:03:00.502  1712  2542 I iu.UploadsManager: num updated entries: 0
08-26 12:03:00.502  1712  4043 V GoogleAuthProtoRequest: [176] a.<init>: mAccountName set to: thalitester@gmail.com
,08-26 12:03:00.503  1712  1712 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-26 12:03:00.503  1712  2542 I iu.SyncManager: NEXT; no task
,08-26 12:03:00.505  1712  1712 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-26 12:03:00.508  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 12:03:00.508  3928  3928 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 12:03:00.511  1712  1712 D SystemUpdateService: onDestroy
08-26 12:03:00.511  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 12:03:00.513  3928  3928 D SprintDMHelper: simOperator: 
,08-26 12:03:00.513  3928  3928 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 12:03:00.545  1500  2998 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-26 12:03:00.545  1500  2998 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-26 12:03:00.545  1500  2998 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 12:03:00.545  1500  2998 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 12:03:00.550   874  4027 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 10:03:00 GMT], X-Android-Received-Millis=[1472205780549], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472205780518]}
08-26 12:03:00.553   874  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-26 12:03:00.553   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-26 12:03:00.553   874  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-26 12:03:00.555   874  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-26 12:03:00.564  1712  4043 E MDM     : [176] SitrepService.a: Error sending sitrep.
,08-26 12:03:00.697  2258  4045 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-26 12:03:01.441   874  1310 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-26 12:03:02.104   874  1978 I ActivityManager: Killing 3659:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-26 12:03:02.386   874  1390 D WifiService: setWifiEnabled: false pid=3763, uid=10000
08-26 12:03:02.386   874  1390 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 12:03:02.405  1453  1453 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-26 12:03:02.411   874  1308 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-26 12:03:02.411   874  1308 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-26 12:03:02.411   874  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-26 12:03:02.411   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 12:03:02.430   874  2254 D DhcpClient: Clearing IP address
,08-26 12:03:02.430   374   872 D CommandListener: Clearing all IP addresses on wlan0
,08-26 12:03:02.434   374   872 D CommandListener: Setting iface cfg
,08-26 12:03:02.442  1500  4050 V NativeCrypto: Read error: ssl=0x9aa8dc00: I/O error during system call, Connection timed out
,08-26 12:03:02.444  1500  4050 V NativeCrypto: SSL shutdown failed: ssl=0x9aa8dc00: I/O error during system call, Broken pipe
,08-26 12:03:02.448   874   885 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
08-26 12:03:02.449   874  4027 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,08-26 12:03:02.450   874  4027 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.110,2a00:1450:4001:817::200e
,08-26 12:03:02.454   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-26 12:03:02.454   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-26 12:03:02.461   397   397 E Parcel  : Reading a NULL string not supported here.
08-26 12:03:02.462   874  1308 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-26 12:03:02.467   874  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 12:03:02.468   874  4029 D DhcpClient: Receive thread stopped
,08-26 12:03:02.470   374   872 D CommandListener: Clearing all IP addresses on wlan0
08-26 12:03:02.475   874  4027 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:817::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
08-26 12:03:02.477   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 12:03:02.481  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 12:03:02.481  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:03:02.481  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:03:02.481  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:03:02.481  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 12:03:02.481  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:03:02.481  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:03:02.481  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:03:02.481  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 12:03:02.481  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:03:02.481  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 12:03:02.482  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:03:02.482  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:03:02.482  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:03:02.482  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:03:02.482  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 12:03:02.482  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:03:02.482  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:03:02.482  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:03:02.482  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 12:03:02.482   874  1308 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 12:03:02.482  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:03:02.482  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 12:03:02.485   874  1310 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-26 12:03:02.488  1884  2279 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 12:03:02.519   374   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 12:03:02.553   374   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 12:03:02.553   874  1310 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-26 12:03:02.554   874  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 12:03:02.556   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-26 12:03:02.559  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 12:03:02.559  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:03:02.559  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:03:02.559  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:03:02.559  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 12:03:02.559  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:03:02.559  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:03:02.559  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:03:02.559  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 12:03:02.560  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 12:03:02.560  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:03:02.560  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:03:02.560  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:03:02.560  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 12:03:02.560  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:03:02.560  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:03:02.560  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:03:02.560  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 12:03:02.565  1712  1712 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-26 12:03:02.568  1712  1712 D SystemUpdateService: onCreate
,08-26 12:03:02.570  1712  1712 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 12:03:02.579  1712  1712 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-26 12:03:02.583  1712  2542 I iu.UploadsManager: num queued entries: 0
08-26 12:03:02.583  1712  2542 I iu.UploadsManager: num updated entries: 0
08-26 12:03:02.584  1712  2542 I iu.SyncManager: NEXT; no task
,08-26 12:03:02.585  1712  4060 I SystemUpdateService: active receiver: enabled
,08-26 12:03:02.588  1712  1712 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 12:03:02.589  1712  1712 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-26 12:03:02.591  3928  3928 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 12:03:02.596  3928  3928 D SprintDMHelper: simOperator: 
,08-26 12:03:02.596  3928  3928 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 12:03:02.629  2258  4063 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-26 12:03:02.640  1712  4060 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 12:03:02.642  1712  4060 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-26 12:03:02.642  1712  4060 I SystemUpdateService: now status is 0 (complete)
08-26 12:03:02.642  1712  4060 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-26 12:03:02.642  1712  4060 I SystemUpdateService: file has been verified
08-26 12:03:02.642  1712  4060 I SystemUpdateService: OTA package size = 12249756
,08-26 12:03:02.646  1712  4060 I SystemUpdateService: showing system update notification
,08-26 12:03:02.656  1712  1712 D SystemUpdateService: onDestroy
,08-26 12:03:02.664   374   872 E Netd    : netlink response contains error (No such file or directory)
,08-26 12:03:02.664   874  1310 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-26 12:03:02.665   874  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-26 12:03:05.437  3914  3914 D BluetoothAdapterState: make() - Creating AdapterState
08-26 12:03:05.437   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@334fc35:true
,08-26 12:03:05.444  3914  3914 I bt_bluedroid: init
,08-26 12:03:05.445  3914  4068 I BluetoothAdapterState: Entering OffState
,08-26 12:03:05.449  3914  4069 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-26 12:03:05.450  3914  4069 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 12:03:05.450  3914  4069 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 12:03:05.451  3914  4069 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-26 12:03:05.452  3914  3914 I bt_bluedroid: get_profile_interface socket
,08-26 12:03:05.454  3914  3914 I bt_bluedroid: get_profile_interface sdp
,08-26 12:03:05.459  3914  3925 I bt_bluedroid: config_hci_snoop_log
,08-26 12:03:05.461   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-26 12:03:05.462  3914  4072 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 12:03:05.467  3914  4072 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 12:03:05.471  3914  4068 D BluetoothAdapterState: Current state: OFF, message: 0
,08-26 12:03:05.471  3914  4068 D BluetoothAdapterProperties: Setting state to 14
,08-26 12:03:05.473  3914  4068 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-26 12:03:05.477  3914  4068 D BluetoothBondStateMachine: make
,08-26 12:03:05.481  3914  4073 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 12:03:05.486  3914  4068 I BluetoothAdapterState: Entering PendingCommandState
,08-26 12:03:05.487  3914  3914 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
08-26 12:03:05.491  3914  3914 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcbab3a
08-26 12:03:05.492  3914  3914 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 12:03:05.493  3914  3914 D BtGatt.GattService: Received start request. Starting profile...
08-26 12:03:05.493  3914  3914 D BtGatt.GattService: start()
08-26 12:03:05.494  3914  3914 I bt_bluedroid: get_profile_interface gatt
,08-26 12:03:05.496  3914  3914 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcbab3a
,08-26 12:03:05.496  3914  3914 D BtGatt.AdvertiseManager: advertise manager created
,08-26 12:03:05.506  3914  3914 V BluetoothAdapterState: isTurningOff()=false
,08-26 12:03:05.506  3914  3914 V BluetoothAdapterState: isTurningOn()=false
08-26 12:03:05.507  3914  3914 V BluetoothAdapterState: isBleTurningOn()=true
,08-26 12:03:05.507  3914  3914 V BluetoothAdapterState: isBleTurningOff()=false
08-26 12:03:05.507  3914  4068 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-26 12:03:05.508  3914  4068 I bt_bluedroid: enable
,08-26 12:03:05.508  3914  4069 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-26 12:03:05.509  3914  4069 I bt_hci  : start_up
,08-26 12:03:05.520  3914  4069 I bt_vendor: alloc value 0xb3939189
08-26 12:03:05.520  3914  4069 I bt_vendor: init
,08-26 12:03:05.520  3914  4069 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-26 12:03:05.520  3914  4069 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-26 12:03:05.628  3914  4069 D bt_hci  : start_up starting async portion
,08-26 12:03:05.629  3914  4076 I bt_hci  : event_finish_startup
08-26 12:03:05.629  3914  4076 I bt_hci_h4: hal_open
08-26 12:03:05.629  3914  4076 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-26 12:03:05.634  3914  4076 I bt_userial_vendor: device fd = 51 open
,08-26 12:03:05.671  3914  4076 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 12:03:05.702  3914  4076 D bt_hwcfg: Chipset BCM4354A2
,08-26 12:03:05.703  3914  4076 D bt_hwcfg: Target name = [BCM4354A2]
08-26 12:03:05.703  3914  4076 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-26 12:03:06.367  3914  4076 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-26 12:03:06.368  3914  4076 D bt_hwcfg: Settlement delay -- 100 ms
,08-26 12:03:06.369  3914  4076 I bt_hwcfg: Setting fw settlement delay to 100 
,08-26 12:03:06.486  3914  4076 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 12:03:06.488  3914  4076 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-26 12:03:06.516  3914  4076 I bt_hwcfg: vendor lib fwcfg completed
,08-26 12:03:06.517  3914  4076 I bt_vendor: firmware callback
08-26 12:03:06.517  3914  4076 I bt_hci  : firmware_config_callback
,08-26 12:03:06.529  3914  4078 I bt_btu  : btu_task pending for preload complete event
,08-26 12:03:06.529  3914  4078 I bt_btu_task: Bluetooth chip preload is complete
08-26 12:03:06.530  3914  4078 I bt_btu  : btu_task received preload complete event
,08-26 12:03:06.541  3914  4078 I         : BTE_InitTraceLevels -- TRC_HCI
08-26 12:03:06.541  3914  4078 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-26 12:03:06.542  3914  4078 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 12:03:06.542  3914  4078 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 12:03:06.542  3914  4078 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 12:03:06.542  3914  4078 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 12:03:06.543  3914  4078 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 12:03:06.543  3914  4078 I         : BTE_InitTraceLevels -- TRC_BTM
,08-26 12:03:06.544  3914  4078 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 12:03:06.544  3914  4078 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 12:03:06.544  3914  4078 I         : BTE_InitTraceLevels -- TRC_SDP
,08-26 12:03:06.545  3914  4078 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 12:03:06.545  3914  4078 I         : BTE_InitTraceLevels -- TRC_SMP
,08-26 12:03:06.545  3914  4078 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 12:03:06.545  3914  4078 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 12:03:06.682  3914  4078 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38b6d9d
,08-26 12:03:06.682  3914  4078 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38b6d9d 
,08-26 12:03:06.695  3914  4072 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-26 12:03:06.699  3914  4072 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-26 12:03:06.699  3914  4072 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 12:03:06.704  3914  4072 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 12:03:06.707  3914  4072 D BluetoothAdapterProperties: Scan Mode:20
,08-26 12:03:06.707  3914  4072 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 12:03:06.707  3914  4072 D bt_hci  : do_postload posting postload work item
,08-26 12:03:06.708  3914  4076 I bt_hci  : event_postload
08-26 12:03:06.708  3914  4076 I bt_vendor: sco_config_cb
08-26 12:03:06.708  3914  4076 I bt_hci  : sco_config_callback postload finished.
,08-26 12:03:06.713  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:03:06.714  3914  4076 I bt_vendor: low_power_mode_cb
08-26 12:03:06.714  3914  4072 D bt_bte_conf: Device ID record 1 : primary
08-26 12:03:06.714  3914  4072 D bt_bte_conf:   vendorId            = 000f
,08-26 12:03:06.715  3914  4072 D bt_bte_conf:   vendorIdSource      = 0001
08-26 12:03:06.715  3914  4072 D bt_bte_conf:   product             = 1200
08-26 12:03:06.715  3914  4072 D bt_bte_conf:   version             = 1436
08-26 12:03:06.715  3914  4072 D bt_bte_conf:   clientExecutableURL = 
08-26 12:03:06.715  3914  4072 D bt_bte_conf:   serviceDescription  = 
08-26 12:03:06.716  3914  4072 D bt_bte_conf:   documentationURL    = 
,08-26 12:03:06.716  3914  4072 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-26 12:03:06.716  3914  4069 D bt_stack_manager: event_start_up_stack finished
,08-26 12:03:06.719  3914  4068 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-26 12:03:06.719  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:03:06.720  3914  4068 D BluetoothAdapterProperties: Setting state to 15
08-26 12:03:06.720  3914  4068 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-26 12:03:06.721  3914  4068 I BluetoothAdapterState: Entering BleOnState
,08-26 12:03:06.727  3914  4068 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-26 12:03:06.727  3914  4068 D BluetoothAdapterProperties: Setting state to 11
,08-26 12:03:06.728  3914  4068 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-26 12:03:06.734  3914  3914 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcbab3a
,08-26 12:03:06.735  3914  3914 D HeadsetService: Received start request. Starting profile...
08-26 12:03:06.740  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:03:06.742  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:03:06.746  3914  3914 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-26 12:03:06.747  3914  3914 D HeadsetStateMachine: make
,08-26 12:03:06.754  3914  4068 I BluetoothAdapterState: Entering PendingCommandState
,08-26 12:03:06.756  3914  3914 D HeadsetStateMachine: max_hf_connections = 1
,08-26 12:03:06.756  3914  3914 I bt_bluedroid: get_profile_interface handsfree
,08-26 12:03:06.756  3914  4072 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-26 12:03:06.756  3914  4072 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-26 12:03:06.761  3914  3914 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcbab3a
,08-26 12:03:06.762  3914  3914 D A2dpService: Received start request. Starting profile...
,08-26 12:03:06.763  3914  3914 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-26 12:03:06.764  3914  3914 I bt_bluedroid: get_profile_interface avrcp
,08-26 12:03:06.771  3914  3914 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-26 12:03:06.771  3914  3914 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 12:03:06.772  3914  3914 D A2dpStateMachine: make
,08-26 12:03:06.773  3914  3914 I bt_bluedroid: get_profile_interface a2dp
,08-26 12:03:06.773  3914  4072 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-26 12:03:06.774  3914  4087 D A2dpStateMachine: Enter Disconnected: -2
,08-26 12:03:06.775  3914  3914 I BluetoothHidServiceJni: classInitNative: succeeds
08-26 12:03:06.776  3914  3914 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcbab3a
08-26 12:03:06.777  3914  3914 D HidService: Received start request. Starting profile...
08-26 12:03:06.777  3832  3832 D BluetoothInputDevice: Proxy object connected
08-26 12:03:06.777  3914  3914 I bt_bluedroid: get_profile_interface hidhost
,08-26 12:03:06.777  3914  3914 D HidService: setHidService(): set to: null
,08-26 12:03:06.777  3914  4072 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38983e5
08-26 12:03:06.778  3914  4072 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-26 12:03:06.778  3914  3914 I BluetoothHealthServiceJni: classInitNative: succeeds
08-26 12:03:06.778  3832  3832 D HidProfile: Bluetooth service connected
,08-26 12:03:06.779  3914  3914 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcbab3a
08-26 12:03:06.780  3914  3914 D HealthService: Received start request. Starting profile...
08-26 12:03:06.781  3914  3914 I bt_bluedroid: get_profile_interface health
08-26 12:03:06.782  3914  3914 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-26 12:03:06.782  3914  3914 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcbab3a
08-26 12:03:06.784  3914  3914 D PanService: Received start request. Starting profile...
08-26 12:03:06.784  3832  3832 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 12:03:06.784  3914  3914 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-26 12:03:06.784  3914  3914 I bt_bluedroid: get_profile_interface pan
08-26 12:03:06.785  3914  4072 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-26 12:03:06.785  3832  3832 D PanProfile: Bluetooth service connected
08-26 12:03:06.788  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 12:03:06.791  3914  3914 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcbab3a
,08-26 12:03:06.792  3832  3832 D BluetoothMap: Proxy object connected
,08-26 12:03:06.792  3914  3914 D BluetoothMapService: Received start request. Starting profile...
08-26 12:03:06.792  3914  3914 D BluetoothMapService: start()
08-26 12:03:06.792  3832  3832 D MapProfile: Bluetooth service connected
08-26 12:03:06.793  3832  3832 D BluetoothMap: getConnectedDevices()
08-26 12:03:06.793  3832  3832 D BluetoothMap: Bluetooth is Not enabled
08-26 12:03:06.794  3914  3914 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-26 12:03:06.795  3914  3914 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-26 12:03:06.795  3914  3914 D BluetoothMapAppObserver: createReceiver()
,08-26 12:03:06.796  3914  3914 D BluetoothMapAppObserver: initObservers()
,08-26 12:03:06.796  3914  3914 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-26 12:03:06.802  3914  3914 V BluetoothAdapterState: isTurningOff()=false
,08-26 12:03:06.802  3914  3914 V BluetoothAdapterState: isTurningOn()=true
08-26 12:03:06.802  3914  3914 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:03:06.802  3914  3914 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 12:03:06.805  3914  4085 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-26 12:03:06.805  3914  3914 V BluetoothAdapterState: isTurningOff()=false
08-26 12:03:06.805  3914  3914 V BluetoothAdapterState: isTurningOn()=true
,08-26 12:03:06.805  3914  3914 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 12:03:06.805  3914  3914 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 12:03:06.805  3914  3914 V BluetoothAdapterState: isTurningOff()=false
,08-26 12:03:06.805  3914  3914 V BluetoothAdapterState: isTurningOn()=true
,08-26 12:03:06.805  3914  3914 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:03:06.805  3914  3914 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 12:03:06.806  3914  3914 V BluetoothAdapterState: isTurningOff()=false
,08-26 12:03:06.806  3914  3914 V BluetoothAdapterState: isTurningOn()=true
08-26 12:03:06.806  3914  3914 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:03:06.806  3914  3914 V BluetoothAdapterState: isBleTurningOff()=false
08-26 12:03:06.806  3914  3914 V BluetoothAdapterState: isTurningOff()=false
08-26 12:03:06.806  3914  3914 V BluetoothAdapterState: isTurningOn()=true
,08-26 12:03:06.806  3914  3914 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:03:06.806  3914  3914 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 12:03:06.808  3914  3914 V BluetoothAdapterState: isTurningOff()=false
08-26 12:03:06.808  3914  3914 V BluetoothAdapterState: isTurningOn()=true
08-26 12:03:06.808  3914  3914 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:03:06.808  3914  3914 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 12:03:06.808  3914  4068 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-26 12:03:06.808  3914  4068 D BluetoothAdapterProperties: ScanMode =  20
,08-26 12:03:06.809  3914  4068 D BluetoothAdapterProperties: State =  11
,08-26 12:03:06.812  3914  4072 D BluetoothAdapterProperties: Scan Mode:21
,08-26 12:03:06.812  3914  4068 D BluetoothAdapterProperties: Setting state to 12
,08-26 12:03:06.812  3914  4068 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-26 12:03:06.812  3914  4072 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 12:03:06.812  3914  4068 I BluetoothAdapterState: Entering OnState
08-26 12:03:06.812  3832  3848 D BluetoothPbap: onBluetoothStateChange: up=true
,08-26 12:03:06.814   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 12:03:06.814  1351  2072 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 12:03:06.815  3832  3847 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 12:03:06.815   874   874 D BluetoothA2dp: Proxy object connected
08-26 12:03:06.815  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:03:06.815  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:03:06.815  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:03:06.815  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 12:03:06.815  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:03:06.815  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:03:06.815  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:03:06.815  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 12:03:06.815  1351  1365 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 12:03:06.817  1351  1368 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 12:03:06.817  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 12:03:06.818  1351  1351 D BluetoothInputDevice: Proxy object connected
08-26 12:03:06.818  1351  1351 D HidProfile: Bluetooth service connected
08-26 12:03:06.818   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 12:03:06.818  1946  2339 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 12:03:06.819  3832  3848 D BluetoothMap: onBluetoothStateChange: up=true
08-26 12:03:06.820  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:03:06.820  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:03:06.820  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:03:06.820  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 12:03:06.820  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:03:06.820  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:03:06.820  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:03:06.820  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 12:03:06.820  3832  3847 D BluetoothPan: onBluetoothStateChange on: true
08-26 12:03:06.820   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 12:03:06.820   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 12:03:06.821  1351  1365 D BluetoothMap: onBluetoothStateChange: up=true
08-26 12:03:06.822  1351  1351 D BluetoothMap: Proxy object connected
08-26 12:03:06.822  1351  1368 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 12:03:06.822  1351  1351 D MapProfile: Bluetooth service connected
08-26 12:03:06.822  1351  1351 D BluetoothMap: getConnectedDevices()
08-26 12:03:06.823  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 12:03:06.824  1351  2072 D BluetoothPan: onBluetoothStateChange on: true
08-26 12:03:06.824  3914  3914 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-26 12:03:06.825  3914  3914 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-26 12:03:06.827   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
08-26 12:03:06.827  1351  1351 D BluetoothA2dp: Proxy object connected
08-26 12:03:06.827  3914  3914 W BluetoothAdapter: getBl,uetoothService() called with no BluetoothManagerCallback
08-26 12:03:06.829  1351  1351 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 12:03:06.829  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:03:06.829  1351  1351 D PanProfile: Bluetooth service connected
08-26 12:03:06.830  3832  3832 D LocalBluetoothProfileManager: Adding local A2DP profile
08-26 12:03:06.831  3914  3914 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 12:03:06.832  3914  3914 D ObexServerSockets: Succeed to create listening sockets 
08-26 12:03:06.832  3914  3914 D ObexServerSockets0: startAccept()
08-26 12:03:06.832  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:03:06.832  3914  3914 D ObexServerSockets0: prepareForNewConnect()
08-26 12:03:06.833  3832  3832 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-26 12:03:06.834  3914  3914 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-26 12:03:06.834  3914  3914 D BluetoothSdpJni: SDP Create record success - handle: 0
08-26 12:03:06.835  3914  4095 D ObexServerSockets0: Accepting socket connection...
08-26 12:03:06.835  3914  3914 D BluetoothMapService: onReceive
08-26 12:03:06.835  3914  3914 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:03:06.835  3914  4096 D ObexServerSockets0: Accepting socket connection...
08-26 12:03:06.835  3914  3914 D BluetoothMapService: STATE_ON
,08-26 12:03:06.842  3832  3832 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 12:03:06.844  3832  3832 D BluetoothA2dp: Proxy object connected
,08-26 12:03:06.848  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 12:03:06.852  3832  3832 D DockEventReceiver: finishStartingService: stopping service
,08-26 12:03:06.859  3832  3832 D BluetoothPbap: Proxy object connected
08-26 12:03:06.859  1351  1351 D BluetoothPbap: Proxy object connected
08-26 12:03:06.860  1351  1351 D PbapServerProfile: Bluetooth service connected
08-26 12:03:06.860  3832  3832 D PbapServerProfile: Bluetooth service connected
,08-26 12:03:06.865  3914  3914 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-26 12:03:06.865  3914  3914 D ObexServerSockets0: prepareForNewConnect()
,08-26 12:03:06.870  3914  4100 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 12:03:06.878  3914  4104 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 12:03:06.879  3914  4104 I BtOppRfcommListener: Accept thread started.
,08-26 12:03:06.916   874   874 D BluetoothHeadset: Proxy object connected
08-26 12:03:06.916   874   874 D BluetoothHeadset: Proxy object connected
08-26 12:03:06.916   874   874 D BluetoothHeadset: Proxy object connected
,08-26 12:03:06.917  1946  1957 D BluetoothHeadset: Proxy object connected
08-26 12:03:06.917  1351  1365 D BluetoothHeadset: Proxy object connected
,08-26 12:03:06.917  1351  1351 D HeadsetProfile: Bluetooth service connected
,08-26 12:03:06.919   874   891 D BluetoothHeadset: Proxy object connected
08-26 12:03:06.919  1946  2142 D BluetoothHeadset: Proxy object connected
,08-26 12:03:06.920   874   891 D BluetoothHeadset: Proxy object connected
08-26 12:03:06.921   874   891 D BluetoothHeadset: Proxy object connected
,08-26 12:03:06.935  3832  3848 D BluetoothHeadset: Proxy object connected
,08-26 12:03:06.938  3832  3832 D HeadsetProfile: Bluetooth service connected
,08-26 12:03:08.378   874  1310 D ConnectivityService: handlePromptUnvalidated 101
,08-26 12:03:08.403  3914  4068 D BluetoothAdapterState: Current state: ON, message: 23
,08-26 12:03:08.403  3914  4068 D BluetoothAdapterProperties: Setting state to 13
08-26 12:03:08.404  3914  4068 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-26 12:03:08.406  3914  4068 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 12:03:08.409  3914  4068 I BluetoothAdapterState: Entering PendingCommandState
08-26 12:03:08.417  3914  3914 D BluetoothMapService: onReceive
,08-26 12:03:08.417  3914  3914 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:03:08.418  3914  3914 D BluetoothMapService: STATE_TURNING_OFF
08-26 12:03:08.418  3914  3914 D BluetoothMapService: MAP Service closeService in
,08-26 12:03:08.418  3914  3914 D BluetoothMapMasInstance0: MAP Service shutdown
08-26 12:03:08.418  3914  3914 D ObexServerSockets0: shutdown(block = true)
08-26 12:03:08.419  3914  3914 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 12:03:08.420  3914  3914 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 12:03:08.420  3914  4096 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-26 12:03:08.420  3914  4081 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-26 12:03:08.420  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:03:08.421  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:03:08.421  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:03:08.421  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:03:08.421  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 12:03:08.421  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:03:08.421  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:03:08.421  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:03:08.421  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 12:03:08.421  3914  4095 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-26 12:03:08.421  3914  4072 D BluetoothAdapterProperties: Scan Mode:20
08-26 12:03:08.422  3914  4068 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-26 12:03:08.422  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:03:08.422  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 12:03:08.423  3832  3832 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-26 12:03:08.423  3914  3914 I BtOppRfcommListener: stopping Accept Thread
,08-26 12:03:08.424  3914  4104 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 12:03:08.424  3914  4104 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 12:03:08.431  3914  3914 D HeadsetService: Received stop request...Stopping profile...
,08-26 12:03:08.434   874   874 D BluetoothHeadset: Proxy object disconnected
,08-26 12:03:08.434   874   874 D BluetoothHeadset: Proxy object disconnected
08-26 12:03:08.434   874   874 D BluetoothHeadset: Proxy object disconnected
,08-26 12:03:08.435  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:03:08.436  1946  1958 D BluetoothHeadset: Proxy object disconnected
08-26 12:03:08.435  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:03:08.435  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:03:08.435  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:03:08.435  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 12:03:08.435  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:03:08.435  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:03:08.435  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:03:08.435  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 12:03:08.436  3832  3847 D BluetoothHeadset: Proxy object disconnected
08-26 12:03:08.436  3914  3914 D A2dpService: Received stop request...Stopping profile...
08-26 12:03:08.437  3914  4087 D A2dpStateMachine: Exit Disconnected: -1
08-26 12:03:08.437  1351  2072 D BluetoothHeadset: Proxy object disconnected
,08-26 12:03:08.438  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:03:08.438  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 12:03:08.440  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:03:08.442   874   874 D BluetoothA2dp: Proxy object disconnected
08-26 12:03:08.442  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:03:08.443  1351  1351 D HeadsetProfile: Bluetooth service disconnected
08-26 12:03:08.443  1351  1351 D BluetoothA2dp: Proxy object disconnected
08-26 12:03:08.444  3914  3914 D HidService: Received stop request...Stopping profile...
,08-26 12:03:08.444  3914  3914 D HidService: Stopping Bluetooth HidService
,08-26 12:03:08.445  1351  1351 D BluetoothInputDevice: Proxy object disconnected
08-26 12:03:08.445  1351  1351 D HidProfile: Bluetooth service disconnected
08-26 12:03:08.446  3914  3914 V BluetoothAdapterState: isTurningOff()=true
08-26 12:03:08.446  3914  3914 V BluetoothAdapterState: isTurningOn()=false
08-26 12:03:08.446  3914  3914 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 12:03:08.446  3914  3914 V BluetoothAdapterState: isBleTurningOff()=false
08-26 12:03:08.447  3832  3832 D DockEventReceiver: finishStartingService: stopping service
,08-26 12:03:08.447  3914  3914 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 12:03:08.447  3914  4072 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-26 12:03:08.447  3914  3914 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-26 12:03:08.448  3914  4078 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 12:03:08.448  3914  4078 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 12:03:08.448  3832  3832 D HeadsetProfile: Bluetooth service disconnected
08-26 12:03:08.448  3832  3832 D BluetoothA2dp: Proxy object disconnected
08-26 12:03:08.448  3832  3832 D BluetoothInputDevice: Proxy object disconnected
08-26 12:03:08.449  3832  3832 D HidProfile: Bluetooth service disconnected
,08-26 12:03:08.449  3914  4078 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 12:03:08.450  3914  4072 E bt_btif : btif_hf_upstreams_evt: Invalid index 65534
08-26 12:03:08.452  3914  3914 D HealthService: Received stop request...Stopping profile...
,08-26 12:03:08.453  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 12:03:08.453  3914  3914 D PanService: Received stop request...Stopping profile...
08-26 12:03:08.455  3832  3832 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 12:03:08.455  3832  3832 D PanProfile: Bluetooth service disconnected
08-26 12:03:08.455  1351  1351 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 12:03:08.456  1351  1351 D PanProfile: Bluetooth service disconnected
08-26 12:03:08.456  3914  3914 D BluetoothMapService: Received stop request...Stopping profile...
08-26 12:03:08.456  3914  3914 D BluetoothMapService: stop()
,08-26 12:03:08.456  3914  3914 D BluetoothMapAppObserver: deinitObservers()
08-26 12:03:08.457  3914  3914 D BluetoothMapAppObserver: removeReceiver()
,08-26 12:03:08.458  3832  3832 D BluetoothMap: Proxy object disconnected
,08-26 12:03:08.458  3832  3832 D MapProfile: Bluetooth service disconnected
08-26 12:03:08.458  1351  1351 D BluetoothMap: Proxy object disconnected
08-26 12:03:08.458  3914  3914 V BluetoothAdapterState: isTurningOff()=true
08-26 12:03:08.458  3914  3914 V BluetoothAdapterState: isTurningOn()=false
08-26 12:03:08.458  3914  3914 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:03:08.458  1351  1351 D MapProfile: Bluetooth service disconnected
08-26 12:03:08.458  3914  3914 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 12:03:08.459  3914  4072 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-26 12:03:08.459  3914  4078 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 12:03:08.459  3914  4078 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 12:03:08.459  3914  3914 V BluetoothAdapterState: isTurningOff()=true
08-26 12:03:08.459  3914  3914 V BluetoothAdapterState: isTurningOn()=false
,08-26 12:03:08.460  3914  3914 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:03:08.460  3914  3914 V BluetoothAdapterState: isBleTurningOff()=false
08-26 12:03:08.460  3914  4078 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 12:03:08.460  3914  4078 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 12:03:08.460  3914  4078 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 12:03:08.460  3914  3914 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-26 12:03:08.460  3914  4078 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 12:03:08.460  3914  4072 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-26 12:03:08.461  3914  3914 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-26 12:03:08.463  3914  3914 V BluetoothAdapterState: isTurningOff()=true
,08-26 12:03:08.463  3914  3914 V BluetoothAdapterState: isTurningOn()=false
08-26 12:03:08.463  3914  3914 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:03:08.463  1351  1351 D BluetoothPbap: Proxy object disconnected
08-26 12:03:08.463  3914  3914 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 12:03:08.463  1351  1351 D PbapServerProfile: Bluetooth service disconnected
,08-26 12:03:08.463  3914  3914 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 12:03:08.463  3832  3832 D BluetoothPbap: Proxy object disconnected
08-26 12:03:08.464  3914  4072 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-26 12:03:08.464  3832  3832 D PbapServerProfile: Bluetooth service disconnected
08-26 12:03:08.464  3914  3914 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 12:03:08.464  3914  3914 V BluetoothAdapterState: isTurningOff()=true
,08-26 12:03:08.464  3914  3914 V BluetoothAdapterState: isTurningOn()=false
08-26 12:03:08.464  3914  3914 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:03:08.464  3914  3914 V BluetoothAdapterState: isBleTurningOff()=false
08-26 12:03:08.467  3914  3914 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 12:03:08.467  3914  3914 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 12:03:08.467  3914  3914 D BluetoothMapService: MAP Service closeService in
08-26 12:03:08.467  3914  3914 V BluetoothAdapterState: isTurningOff()=true
08-26 12:03:08.468  3914  3914 V BluetoothAdapterState: isTurningOn()=false
,08-26 12:03:08.468  3914  3914 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:03:08.468  3914  3914 V BluetoothAdapterState: isBleTurningOff()=false
08-26 12:03:08.468  3914  3914 D BluetoothMapService: cleanup()
08-26 12:03:08.468  3914  3914 D BluetoothMapService: MAP Service closeService in
08-26 12:03:08.469  3914  4068 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-26 12:03:08.469  3914  4068 D BluetoothAdapterProperties: Setting state to 15
08-26 12:03:08.469  3914  4068 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-26 12:03:08.470  3914  4068 I BluetoothAdapterState: Entering BleOnState
08-26 12:03:08.470  3832  3848 D BluetoothPbap: onBluetoothStateChange: up=false
,08-26 12:03:08.474   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 12:03:08.474  3832  3847 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 12:03:08.475  1351  1365 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 12:03:08.475  3832  3848 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-26 12:03:08.475  1351  1368 D BluetoothPbap: onBluetoothStateChange: up=false
,08-26 12:03:08.476  1351  2072 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 12:03:08.477   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 12:03:08.477  1946  2339 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 12:03:08.477  3832  3847 D BluetoothMap: onBluetoothStateChange: up=false
,08-26 12:03:08.478  3832  3848 D BluetoothPan: onBluetoothStateChange on: false
,08-26 12:03:08.478   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 12:03:08.479  3832  3847 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 12:03:08.479   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 12:03:08.479  1351  1365 D BluetoothMap: onBluetoothStateChange: up=false
08-26 12:03:08.480  1351  1368 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 12:03:08.480  1351  2072 D BluetoothPan: onBluetoothStateChange on: false
,08-26 12:03:08.481  3914  4068 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-26 12:03:08.481  3914  4068 D BluetoothAdapterProperties: Setting state to 16
08-26 12:03:08.481  3914  4068 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-26 12:03:08.482  3914  4068 D BluetoothAdapterProperties: onBleDisable
08-26 12:03:08.482  3914  4068 I BluetoothAdapterState: Entering PendingCommandState
08-26 12:03:08.482  3914  4069 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-26 12:03:08.483  3914  4078 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-26 12:03:08.483  3914  4078 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 12:03:08.486  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:03:08.486  3914  4072 D BluetoothAdapterProperties: Scan Mode:20
,08-26 12:03:08.488  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:03:08.489  3832  3832 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 12:03:08.489  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:03:08.490  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:03:08.494  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 12:03:08.496  3832  3832 D DockEventReceiver: finishStartingService: stopping service
,08-26 12:03:08.684  3914  4072 I bt_hci  : shut_down
,08-26 12:03:08.684  3914  4076 D bt_hwcfg: hw_epilog_process
,08-26 12:03:08.698  3914  4076 I bt_vendor: low_power_mode_cb
,08-26 12:03:08.722  3914  4076 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-26 12:03:08.722  3914  4076 I bt_vendor: epilog_cb
08-26 12:03:08.722  3914  4076 I bt_hci  : epilog_finished_callback
,08-26 12:03:08.729  3914  4072 I bt_hci_h4: hal_close
,08-26 12:03:08.730  3914  4072 I bt_userial_vendor: device fd = 51 close
,08-26 12:03:08.843  3914  4069 D bt_stack_manager: event_shut_down_stack finished.
,08-26 12:03:08.845  3914  4068 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-26 12:03:08.850  3914  4068 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-26 12:03:08.851  3914  3914 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 12:03:08.852  3914  3914 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 12:03:08.853  3914  3914 D BtGatt.GattService: stop()
08-26 12:03:08.853  3914  3914 D BtGatt.AdvertiseManager: advertise clients cleared
,08-26 12:03:08.858  3914  3914 V BluetoothAdapterState: isTurningOff()=false
,08-26 12:03:08.858  3914  3914 V BluetoothAdapterState: isTurningOn()=false
,08-26 12:03:08.858  3914  3914 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:03:08.859  3914  3914 V BluetoothAdapterState: isBleTurningOff()=true
,08-26 12:03:08.860  3914  4068 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-26 12:03:08.861  3914  4068 D BluetoothAdapterProperties: Setting state to 10
08-26 12:03:08.861  3914  4068 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-26 12:03:08.863  3914  4068 I BluetoothAdapterState: Entering OffState
08-26 12:03:08.864   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-26 12:03:08.894  3914  3914 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-26 12:03:08.894  3914  3914 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-26 12:03:08.896  3914  4069 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-26 12:03:08.897  3914  3914 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-26 12:03:08.907  3914  4069 D bt_stack_manager: event_clean_up_stack finished.
,08-26 12:03:08.914  3914  3914 I art     : System.exit called, status: 0
08-26 12:03:08.914  3914  3914 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 12:03:08.986   874  1392 I ActivityManager: Process com.android.bluetooth (pid 3914) has died
,08-26 12:03:10.246  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 12:03:10.264  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 12:03:10.272  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 12:03:10.328  1500  2037 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-26 12:03:10.329  1500  2037 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-26 12:03:10.329  1500  2037 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 12:03:10.329  1500  2037 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 12:03:10.357  3507  3507 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-26 12:03:10.358  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-26 12:03:10.358  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-26 12:03:11.400  3763  3811 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 12:03:11.400  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 12:03:14.036   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-26 12:03:14.045  1872  1872 I Keyboard.Facilitator: onFinishInput()
,08-26 12:03:14.049   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-26 12:03:14.049   874   894 I Adreno  : Build Date                       : 10/20/15
08-26 12:03:14.049   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 12:03:14.049   874   894 I Adreno  : Local Branch                     : M14
08-26 12:03:14.049   874   894 I Adreno  : Remote Branch                    : 
08-26 12:03:14.049   874   894 I Adreno  : Remote Branch                    : 
08-26 12:03:14.049   874   894 I Adreno  : Reconstruct Branch               : 
,08-26 12:03:14.079   281   301 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (675 us)
,08-26 12:03:14.408  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 12:03:14.412  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f7a0620 added. We now have 6 listener(s)
08-26 12:03:14.412  3763  3811 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 12:03:14.420  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 12:03:14.421  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1928bd9 added. We now have 7 listener(s)
08-26 12:03:14.421  3763  3811 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 12:03:14.422  3763  3811 I System.out: IsBluetoothEnabled
,08-26 12:03:14.434  3763  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:03:14.485   874   891 I ActivityManager: Start proc 4116:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-26 12:03:14.600  4116  4116 D AdapterServiceConfig: Adding HeadsetService
,08-26 12:03:14.601  4116  4116 D AdapterServiceConfig: Adding A2dpService
08-26 12:03:14.601  4116  4116 D AdapterServiceConfig: Adding HidService
08-26 12:03:14.601  4116  4116 D AdapterServiceConfig: Adding HealthService
,08-26 12:03:14.601  4116  4116 D AdapterServiceConfig: Adding PanService
08-26 12:03:14.602  4116  4116 D AdapterServiceConfig: Adding GattService
08-26 12:03:14.602  4116  4116 D AdapterServiceConfig: Adding BluetoothMapService
,08-26 12:03:14.616   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a6bfdcf:true
,08-26 12:03:14.621  4116  4116 D BluetoothAdapterState: make() - Creating AdapterState
,08-26 12:03:14.624  4116  4116 I bt_bluedroid: init
,08-26 12:03:14.625  4116  4128 I BluetoothAdapterState: Entering OffState
08-26 12:03:14.627  4116  4129 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-26 12:03:14.628  4116  4129 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 12:03:14.628  4116  4129 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-26 12:03:14.628  4116  4129 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-26 12:03:14.630  4116  4116 I bt_bluedroid: get_profile_interface socket
,08-26 12:03:14.633  4116  4132 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 12:03:14.634  4116  4132 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 12:03:14.636  4116  4116 I bt_bluedroid: get_profile_interface sdp
,08-26 12:03:14.642  4116  4127 I bt_bluedroid: config_hci_snoop_log
08-26 12:03:14.646   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-26 12:03:14.653  4116  4128 D BluetoothAdapterState: Current state: OFF, message: 0
,08-26 12:03:14.653  4116  4128 D BluetoothAdapterProperties: Setting state to 14
,08-26 12:03:14.653  4116  4128 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-26 12:03:14.655  4116  4128 D BluetoothBondStateMachine: make
,08-26 12:03:14.660  4116  4128 I BluetoothAdapterState: Entering PendingCommandState
,08-26 12:03:14.661  4116  4133 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 12:03:14.664  4116  4116 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-26 12:03:14.672  4116  4116 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcbab3a
,08-26 12:03:14.675  4116  4116 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 12:03:14.678  4116  4116 D BtGatt.GattService: Received start request. Starting profile...
,08-26 12:03:14.679  4116  4116 D BtGatt.GattService: start()
,08-26 12:03:14.679  4116  4116 I bt_bluedroid: get_profile_interface gatt
,08-26 12:03:14.681  4116  4116 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcbab3a
08-26 12:03:14.682  4116  4116 D BtGatt.AdvertiseManager: advertise manager created
,08-26 12:03:14.692  4116  4116 V BluetoothAdapterState: isTurningOff()=false
,08-26 12:03:14.693  4116  4116 V BluetoothAdapterState: isTurningOn()=false
,08-26 12:03:14.693  4116  4116 V BluetoothAdapterState: isBleTurningOn()=true
,08-26 12:03:14.693  4116  4116 V BluetoothAdapterState: isBleTurningOff()=false
08-26 12:03:14.693  4116  4128 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-26 12:03:14.694  4116  4128 I bt_bluedroid: enable
08-26 12:03:14.694  4116  4129 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-26 12:03:14.695  4116  4129 I bt_hci  : start_up
,08-26 12:03:14.724  3763  3763 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 12:03:14.725  3763  3763 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-26 12:03:14.779   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-26 12:03:14.786  4116  4129 I bt_vendor: alloc value 0xb399b189
,08-26 12:03:14.787  4116  4129 I bt_vendor: init
,08-26 12:03:14.782  3763  3763 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c394106 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@4d7d99e, 16908290=android.view.AbsSavedState$1@4d7d99e}, android:focusedViewId=100}]}]
,08-26 12:03:14.787  4116  4129 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-26 12:03:14.787  4116  4129 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-26 12:03:14.787  3763  3763 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-26 12:03:14.788  3763  3763 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-26 12:03:14.789  3763  3763 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-26 12:03:14.796   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-26 12:03:14.802   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
08-26 12:03:14.802   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
08-26 12:03:14.802   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-26 12:03:14.893  4116  4129 D bt_hci  : start_up starting async portion
,08-26 12:03:14.894  4116  4136 I bt_hci  : event_finish_startup
,08-26 12:03:14.895  4116  4136 I bt_hci_h4: hal_open
08-26 12:03:14.895  4116  4136 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-26 12:03:14.905  4116  4136 I bt_userial_vendor: device fd = 51 open
,08-26 12:03:14.938  4116  4136 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 12:03:14.969  4116  4136 D bt_hwcfg: Chipset BCM4354A2
,08-26 12:03:14.970  4116  4136 D bt_hwcfg: Target name = [BCM4354A2]
08-26 12:03:14.971  4116  4136 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-26 12:03:15.050   281   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-26 12:03:15.064   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-26 12:03:15.065   874  1334 D SurfaceControl: Excessive delay in setPowerMode(): 263ms
,08-26 12:03:15.069   874   894 I DreamManagerService: Entering dreamland.
08-26 12:03:15.069   874   894 I PowerManagerService: Dozing...
08-26 12:03:15.071   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-26 12:03:15.115   378  2061 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-26 12:03:15.116   378  2061 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-26 12:03:15.128   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 12:03:15.132   874  1308 E native  : do suspend false
,08-26 12:03:15.140  1934  4139 D NfcService: Discovery configuration equal, not updating.
,08-26 12:03:15.167   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 12:03:15.171   874  1308 E native  : do suspend true
,08-26 12:03:15.258   378  1316 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-26 12:03:15.259   378  1316 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-26 12:03:15.784  4116  4136 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-26 12:03:15.786  4116  4136 D bt_hwcfg: Settlement delay -- 100 ms
,08-26 12:03:15.787  4116  4136 I bt_hwcfg: Setting fw settlement delay to 100 
,08-26 12:03:15.905  4116  4136 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 12:03:15.907  4116  4136 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-26 12:03:15.934  4116  4136 I bt_hwcfg: vendor lib fwcfg completed
,08-26 12:03:15.934  4116  4136 I bt_vendor: firmware callback
08-26 12:03:15.935  4116  4136 I bt_hci  : firmware_config_callback
,08-26 12:03:15.947  4116  4143 I bt_btu  : btu_task pending for preload complete event
08-26 12:03:15.947  4116  4143 I bt_btu_task: Bluetooth chip preload is complete
08-26 12:03:15.947  4116  4143 I bt_btu  : btu_task received preload complete event
,08-26 12:03:15.956  4116  4143 I         : BTE_InitTraceLevels -- TRC_HCI
,08-26 12:03:15.956  4116  4143 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 12:03:15.956  4116  4143 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 12:03:15.956  4116  4143 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-26 12:03:15.956  4116  4143 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 12:03:15.956  4116  4143 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 12:03:15.956  4116  4143 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 12:03:15.956  4116  4143 I         : BTE_InitTraceLevels -- TRC_BTM
08-26 12:03:15.956  4116  4143 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 12:03:15.956  4116  4143 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 12:03:15.956  4116  4143 I         : BTE_InitTraceLevels -- TRC_SDP
,08-26 12:03:15.956  4116  4143 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 12:03:15.956  4116  4143 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 12:03:15.956  4116  4143 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 12:03:15.957  4116  4143 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 12:03:16.098  4116  4143 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3918d9d
08-26 12:03:16.098  4116  4143 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3918d9d 
,08-26 12:03:16.108  4116  4132 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-26 12:03:16.110  4116  4132 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-26 12:03:16.111  4116  4132 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 12:03:16.113  4116  4132 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 12:03:16.116  4116  4132 D BluetoothAdapterProperties: Scan Mode:20
,08-26 12:03:16.118  4116  4132 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 12:03:16.119  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:03:16.119  4116  4132 D bt_hci  : do_postload posting postload work item
,08-26 12:03:16.119  4116  4136 I bt_hci  : event_postload
,08-26 12:03:16.119  4116  4136 I bt_vendor: sco_config_cb
,08-26 12:03:16.119  4116  4136 I bt_hci  : sco_config_callback postload finished.
,08-26 12:03:16.124  4116  4132 D bt_bte_conf: Device ID record 1 : primary
,08-26 12:03:16.124  4116  4132 D bt_bte_conf:   vendorId            = 000f
,08-26 12:03:16.124  4116  4132 D bt_bte_conf:   vendorIdSource      = 0001
,08-26 12:03:16.124  4116  4132 D bt_bte_conf:   product             = 1200
,08-26 12:03:16.125  4116  4132 D bt_bte_conf:   version             = 1436
08-26 12:03:16.125  4116  4136 I bt_vendor: low_power_mode_cb
,08-26 12:03:16.125  4116  4132 D bt_bte_conf:   clientExecutableURL = 
08-26 12:03:16.125  4116  4132 D bt_bte_conf:   serviceDescription  = 
,08-26 12:03:16.125  4116  4132 D bt_bte_conf:   documentationURL    = 
,08-26 12:03:16.126  4116  4132 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-26 12:03:16.126  4116  4129 D bt_stack_manager: event_start_up_stack finished
,08-26 12:03:16.128  4116  4128 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-26 12:03:16.129  4116  4128 D BluetoothAdapterProperties: Setting state to 15
,08-26 12:03:16.129  4116  4128 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-26 12:03:16.130  4116  4128 I BluetoothAdapterState: Entering BleOnState
08-26 12:03:16.133  4116  4128 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-26 12:03:16.134  4116  4128 D BluetoothAdapterProperties: Setting state to 11
,08-26 12:03:16.134  4116  4128 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-26 12:03:16.143  4116  4116 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcbab3a
,08-26 12:03:16.145  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:03:16.145  4116  4116 D HeadsetService: Received start request. Starting profile...
08-26 12:03:16.148  4116  4116 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 12:03:16.148  4116  4116 D HeadsetStateMachine: make
08-26 12:03:16.155  4116  4128 I BluetoothAdapterState: Entering PendingCommandState
,08-26 12:03:16.159  4116  4116 D HeadsetStateMachine: max_hf_connections = 1
,08-26 12:03:16.159  4116  4116 I bt_bluedroid: get_profile_interface handsfree
08-26 12:03:16.159  4116  4132 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-26 12:03:16.159  4116  4132 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-26 12:03:16.162  4116  4116 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcbab3a
,08-26 12:03:16.162  4116  4116 D A2dpService: Received start request. Starting profile...
08-26 12:03:16.163  4116  4116 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-26 12:03:16.163  4116  4116 I bt_bluedroid: get_profile_interface avrcp
,08-26 12:03:16.170  4116  4116 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 12:03:16.170  4116  4116 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 12:03:16.171  4116  4116 D A2dpStateMachine: make
,08-26 12:03:16.172  4116  4116 I bt_bluedroid: get_profile_interface a2dp
08-26 12:03:16.172  4116  4132 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-26 12:03:16.174  4116  4152 D A2dpStateMachine: Enter Disconnected: -2
,08-26 12:03:16.176  4116  4116 I BluetoothHidServiceJni: classInitNative: succeeds
,08-26 12:03:16.177  4116  4116 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcbab3a
,08-26 12:03:16.177  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 12:03:16.177  4116  4116 D HidService: Received start request. Starting profile...
,08-26 12:03:16.178  4116  4116 I bt_bluedroid: get_profile_interface hidhost
08-26 12:03:16.179  4116  4116 D HidService: setHidService(): set to: null
08-26 12:03:16.179  4116  4132 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38fa3e5
,08-26 12:03:16.179  4116  4132 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-26 12:03:16.179  4116  4116 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-26 12:03:16.180  4116  4116 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcbab3a
08-26 12:03:16.181  4116  4116 D HealthService: Received start request. Starting profile...
,08-26 12:03:16.182  4116  4116 I bt_bluedroid: get_profile_interface health
,08-26 12:03:16.182  4116  4116 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-26 12:03:16.183  4116  4116 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcbab3a
,08-26 12:03:16.184  4116  4116 D PanService: Received start request. Starting profile...
,08-26 12:03:16.184  4116  4116 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-26 12:03:16.184  4116  4116 I bt_bluedroid: get_profile_interface pan
08-26 12:03:16.185  4116  4132 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-26 12:03:16.187  4116  4116 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcbab3a
,08-26 12:03:16.188  4116  4116 D BluetoothMapService: Received start request. Starting profile...
08-26 12:03:16.188  4116  4116 D BluetoothMapService: start()
,08-26 12:03:16.190  4116  4116 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-26 12:03:16.191  4116  4116 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-26 12:03:16.191  4116  4116 D BluetoothMapAppObserver: createReceiver()
08-26 12:03:16.192  4116  4116 D BluetoothMapAppObserver: initObservers()
,08-26 12:03:16.192  4116  4116 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-26 12:03:16.199  4116  4116 V BluetoothAdapterState: isTurningOff()=false
,08-26 12:03:16.200  4116  4116 V BluetoothAdapterState: isTurningOn()=true
08-26 12:03:16.200  4116  4116 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:03:16.200  4116  4116 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 12:03:16.201  4116  4116 V BluetoothAdapterState: isTurningOff()=false
,08-26 12:03:16.201  4116  4116 V BluetoothAdapterState: isTurningOn()=true
,08-26 12:03:16.201  4116  4116 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 12:03:16.201  4116  4116 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 12:03:16.202  4116  4150 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 12:03:16.202  4116  4116 V BluetoothAdapterState: isTurningOff()=false
,08-26 12:03:16.202  4116  4116 V BluetoothAdapterState: isTurningOn()=true
08-26 12:03:16.202  4116  4116 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:03:16.202  4116  4116 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 12:03:16.202  4116  4116 V BluetoothAdapterState: isTurningOff()=false
08-26 12:03:16.202  4116  4116 V BluetoothAdapterState: isTurningOn()=true
,08-26 12:03:16.202  4116  4116 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 12:03:16.202  4116  4116 V BluetoothAdapterState: isBleTurningOff()=false
08-26 12:03:16.202  4116  4116 V BluetoothAdapterState: isTurningOff()=false
08-26 12:03:16.202  4116  4116 V BluetoothAdapterState: isTurningOn()=true
08-26 12:03:16.202  4116  4116 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:03:16.202  4116  4116 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 12:03:16.203  4116  4116 V BluetoothAdapterState: isTurningOff()=false
08-26 12:03:16.203  4116  4116 V BluetoothAdapterState: isTurningOn()=true
08-26 12:03:16.203  4116  4116 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:03:16.203  4116  4116 V BluetoothAdapterState: isBleTurningOff()=false
08-26 12:03:16.203  4116  4128 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-26 12:03:16.203  4116  4128 D BluetoothAdapterProperties: ScanMode =  20
08-26 12:03:16.203  4116  4128 D BluetoothAdapterProperties: State =  11
,08-26 12:03:16.204  4116  4132 D BluetoothAdapterProperties: Scan Mode:21
08-26 12:03:16.205  4116  4132 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 12:03:16.205  4116  4128 D BluetoothAdapterProperties: Setting state to 12
08-26 12:03:16.205  4116  4128 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 12:03:16.205  4116  4128 I BluetoothAdapterState: Entering OnState
08-26 12:03:16.206  3832  3847 D BluetoothPbap: onBluetoothStateChange: up=true
,08-26 12:03:16.208  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:03:16.208  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:03:16.208  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:03:16.208  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 12:03:16.208  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:03:16.208  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:03:16.208  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:03:16.208  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 12:03:16.209   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 12:03:16.209  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 12:03:16.210  3832  3848 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 12:03:16.211   874   874 D BluetoothA2dp: Proxy object connected
08-26 12:03:16.212  3832  3832 D BluetoothA2dp: Proxy object connected
08-26 12:03:16.212  1351  1365 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 12:03:16.213  3832  3847 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-26 12:03:16.215  1351  2072 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 12:03:16.217  1351  1368 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 12:03:16.218  4116  4116 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-26 12:03:16.218  4116  4116 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-26 12:03:16.219  1351  1351 D BluetoothInputDevice: Proxy object connected
,08-26 12:03:16.219  1351  1351 D HidProfile: Bluetooth service connected
08-26 12:03:16.219  4116  4116 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 12:03:16.219   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 12:03:16.220  1946  1958 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 12:03:16.221  3832  4157 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 12:03:16.221  4116  4116 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 12:03:16.222  4116  4116 D ObexServerSockets: Succeed to create listening sockets 
08-26 12:03:16.222  4116  4116 D ObexServerSockets0: startAccept()
08-26 12:03:16.223  4116  4116 D ObexServerSockets0: prepareForNewConnect()
08-26 12:03:16.223  3832  3847 D BluetoothPan: onBluetoothStateChange on: true
,08-26 12:03:16.224  4116  4116 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-26 12:03:16.224  4116  4116 D BluetoothSdpJni: SDP Create record success - handle: 0
08-26 12:03:16.225   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 12:03:16.225  3832  3848 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 12:03:16.226   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 12:03:16.226  1351  1368 D BluetoothMap: onBluetoothStateChange: up=true
08-26 12:03:16.227  4116  4159 D ObexServerSockets0: Accepting socket connection...
,08-26 12:03:16.228  4116  4158 D ObexServerSockets0: Accepting socket connection...
,08-26 12:03:16.228  1351  1351 D BluetoothMap: Proxy object connected
08-26 12:03:16.228  1351  1351 D MapProfile: Bluetooth service connected
08-26 12:03:16.228  1351  1351 D BluetoothMap: getConnectedDevices()
,08-26 12:03:16.229  1351  1365 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 12:03:16.229  3832  3832 D BluetoothInputDevice: Proxy object connected
,08-26 12:03:16.231  1351  1351 D BluetoothA2dp: Proxy object connected
08-26 12:03:16.231  1351  1368 D BluetoothPan: onBluetoothStateChange on: true
,08-26 12:03:16.233  1351  1351 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 12:03:16.233  1351  1351 D PanProfile: Bluetooth service connected
,08-26 12:03:16.230  3832  3832 D HidProfile: Bluetooth service connected
08-26 12:03:16.234   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
,08-26 12:03:16.236  4116  4116 D BluetoothMapService: onReceive
08-26 12:03:16.236  4116  4116 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:03:16.236  4116  4116 D BluetoothMapService: STATE_ON
08-26 12:03:16.237  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:03:16.238  3832  3832 D BluetoothMap: Proxy object connected
,08-26 12:03:16.239  3832  3832 D MapProfile: Bluetooth service connected
08-26 12:03:16.239  3832  3832 D BluetoothMap: getConnectedDevices()
08-26 12:03:16.240  3832  3832 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 12:03:16.240  3832  3832 D PanProfile: Bluetooth service connected
,08-26 12:03:16.245  3832  3832 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 12:03:16.252  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 12:03:16.253  3832  3832 D DockEventReceiver: finishStartingService: stopping service
08-26 12:03:16.257  3832  3832 D BluetoothPbap: Proxy object connected
08-26 12:03:16.257  3832  3832 D PbapServerProfile: Bluetooth service connected
,08-26 12:03:16.258  4116  4116 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-26 12:03:16.258  4116  4116 D ObexServerSockets0: prepareForNewConnect()
,08-26 12:03:16.258  4116  4163 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 12:03:16.261  1351  1351 D BluetoothPbap: Proxy object connected
,08-26 12:03:16.262  1351  1351 D PbapServerProfile: Bluetooth service connected
,08-26 12:03:16.281  4116  4169 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 12:03:16.282  4116  4169 I BtOppRfcommListener: Accept thread started.
,08-26 12:03:16.315   874   874 D BluetoothHeadset: Proxy object connected
,08-26 12:03:16.315   874   874 D BluetoothHeadset: Proxy object connected
08-26 12:03:16.315   874   874 D BluetoothHeadset: Proxy object connected
08-26 12:03:16.316  1946  2339 D BluetoothHeadset: Proxy object connected
,08-26 12:03:16.317  3832  4157 D BluetoothHeadset: Proxy object connected
08-26 12:03:16.317  3832  3832 D HeadsetProfile: Bluetooth service connected
,08-26 12:03:16.317  1351  1365 D BluetoothHeadset: Proxy object connected
08-26 12:03:16.318  1351  1351 D HeadsetProfile: Bluetooth service connected
,08-26 12:03:16.320   874   891 D BluetoothHeadset: Proxy object connected
08-26 12:03:16.320  1946  1957 D BluetoothHeadset: Proxy object connected
,08-26 12:03:16.326   874   891 D BluetoothHeadset: Proxy object connected
08-26 12:03:16.326  3832  3847 D BluetoothHeadset: Proxy object connected
,08-26 12:03:16.326   874   891 D BluetoothHeadset: Proxy object connected
08-26 12:03:16.326  3832  3832 D HeadsetProfile: Bluetooth service connected
,08-26 12:03:16.462  3763  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:03:16.462  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:03:16.462  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:03:16.462  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 12:03:16.462  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:03:16.462  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:03:16.462  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:03:16.462  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 12:03:16.470  3763  3811 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 12:03:16.473  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 12:03:16.474  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@269fc7f added. We now have 8 listener(s)
,08-26 12:03:16.474  3763  3811 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 12:03:16.480   874  1995 D WifiService: setWifiEnabled: false pid=3763, uid=10000
,08-26 12:03:16.481   874  1995 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 12:03:16.495  3763  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:03:16.496   874  1997 D WifiService: setWifiEnabled: true pid=3763, uid=10000
,08-26 12:03:16.497   874  1997 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 12:03:16.509   874  1308 D WifiConfigStore: Loading config and enabling all networks 
,08-26 12:03:16.532  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:03:16.532  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:03:16.532  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:03:16.532  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:03:16.532  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:03:16.532  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:03:16.532  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:03:16.532  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 12:03:16.536  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 12:03:16.544   874  1308 D WifiConfigStore: loaded 0 passpoint configs
,08-26 12:03:16.545   874  1308 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-26 12:03:16.545   874  1308 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-26 12:03:16.546   874  1308 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-26 12:03:16.547   874  1308 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-26 12:03:16.547   874  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-26 12:03:16.547   874  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-26 12:03:16.560   374   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-26 12:03:16.561   874  1308 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.05 rxSuccessRate=0.09 delta 1000 -> 1000
,08-26 12:03:16.561   374   872 D CommandListener: Setting iface cfg
08-26 12:03:16.562   874  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-26 12:03:16.562   874  1307 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '154 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 154 Failed to set address (No such device)'
08-26 12:03:16.563   874  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-26 12:03:16.576   874  1308 E native  : do suspend true
,08-26 12:03:16.590   874  1308 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-26 12:03:16.590   874  1307 D WifiNative-HAL: p2pGetDeviceAddress
08-26 12:03:16.590   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 12:03:16.590   874  1307 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-26 12:03:16.599   874  1308 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-26 12:03:16.675   874  1308 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-26 12:03:16.678  1453  1453 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-26 12:03:17.107  1453  1453 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-26 12:03:17.144  1453  1453 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-26 12:03:17.145  1453  1453 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-26 12:03:17.151   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 12:03:17.163   874  1308 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 12:03:17.164   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-26 12:03:17.164   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 12:03:17.193   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 12:03:17.218   374   872 D CommandListener: Setting iface cfg
,08-26 12:03:17.219   874  1308 D WifiStateMachine: Start Dhcp Watchdog 3
,08-26 12:03:17.235   874  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-26 12:03:17.245   874  4176 D DhcpClient: Receive thread started
,08-26 12:03:17.334   874  1308 E native  : do suspend false
,08-26 12:03:17.354   874  2254 D DhcpClient: Broadcasting DHCPDISCOVER
,08-26 12:03:17.368   874  4176 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-26 12:03:17.369   874  2254 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-26 12:03:17.372   874  2254 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-26 12:03:17.385   874  4176 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-26 12:03:17.386   874  2254 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-26 12:03:17.391   374   872 D CommandListener: Setting iface cfg
,08-26 12:03:17.402   874  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-26 12:03:17.402   874  2254 D DhcpClient: Scheduling renewal in 86399s
,08-26 12:03:17.408   874  1308 E native  : do suspend true
,08-26 12:03:17.433   874  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-26 12:03:17.434   874  1308 D WifiConfigStore: No blacklist allowed without epno enabled
,08-26 12:03:17.434   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-26 12:03:17.437   874  1310 D ConnectivityService: Adding iface wlan0 to network 102
08-26 12:03:17.441   874  1308 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 12:03:17.479   874  1310 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-26 12:03:17.480   874  1310 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-26 12:03:17.482   874  1310 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-26 12:03:17.484   874  1310 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-26 12:03:17.486   874  1310 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-26 12:03:17.504   874  1310 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-26 12:03:17.514  3763  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:03:17.514  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:03:17.514  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:03:17.514  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:03:17.514  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:03:17.514  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:03:17.514  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:03:17.514  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 12:03:17.517   874  1310 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-26 12:03:17.517   874  1310 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-26 12:03:17.518   874  1308 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-26 12:03:17.518  3763  3811 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 12:03:17.518   874  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 12:03:17.518   874  1310 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-26 12:03:17.519   874  1310 D ConnectivityService:    accepting network in place of null
08-26 12:03:17.521   874  1310 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 12:03:17.523  3763  3811 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-26 12:03:17.523  3763  3811 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-26 12:03:17.527  3763  3811 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c394106 Bundle[{}]
,08-26 12:03:17.527  3763  3811 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-26 12:03:17.528  3763  3811 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-26 12:03:17.529  3763  3811 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-26 12:03:17.530  3763  3811 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-26 12:03:17.531  3763  3811 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-26 12:03:17.532  3763  3811 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 12:03:17.537  3763  3811 I System.out: Running OutgoingSocketThread
,08-26 12:03:17.540  3763  4182 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 417)
,08-26 12:03:17.542  3763  4182 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 44815
,08-26 12:03:17.543   874  4175 D NetlinkSocketObserver: NeighborEvent{elapsedMs=153522, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
08-26 12:03:17.543  3763  4182 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-26 12:03:17.554   374   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 12:03:17.613   374   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 12:03:17.618   874  1310 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-26 12:03:17.618   874  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 12:03:17.619   874  4174 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.206,2a00:1450:4001:805::200e
,08-26 12:03:17.625   874  1310 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-26 12:03:17.627   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-26 12:03:17.641  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:03:17.641  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:03:17.641  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:03:17.641  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:03:17.641  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:03:17.641  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:03:17.641  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:03:17.641  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 12:03:17.643  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 12:03:17.655  1712  1712 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 12:03:17.660  1712  1712 D SystemUpdateService: onCreate
,08-26 12:03:17.664  1712  1712 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 12:03:17.683  1712  4187 I SystemUpdateService: active receiver: enabled
,08-26 12:03:17.686  1712  1712 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-26 12:03:17.689  1712  2542 I iu.UploadsManager: num queued entries: 0
,08-26 12:03:17.689  1712  2542 I iu.UploadsManager: num updated entries: 0
,08-26 12:03:17.696  1712  1712 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 12:03:17.698  1712  4187 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 12:03:17.700   874  4174 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 10:03:17 GMT], X-Android-Received-Millis=[1472205797699], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472205797667]}
,08-26 12:03:17.700  1712  1712 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-26 12:03:17.701   874  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-26 12:03:17.701   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-26 12:03:17.702   874  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-26 12:03:17.703   874  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-26 12:03:17.704  3928  3928 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 12:03:17.711  3928  3928 D SprintDMHelper: simOperator: 
08-26 12:03:17.711  3928  3928 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 12:03:17.721  1712  4190 I MDM     : [181] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-26 12:03:17.722  1712  4190 W BaseAppContext: Using Auth Proxy for data requests.
,08-26 12:03:17.724  1712  4190 V GoogleAuthProtoRequest: [181] a.<init>: mAccountName set to: thalitester@gmail.com
,08-26 12:03:17.730  1712  4187 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-26 12:03:17.731  1712  4187 I SystemUpdateService: now status is 0 (complete)
,08-26 12:03:17.728  1712  2542 I iu.SyncManager: NEXT; no task
,08-26 12:03:17.731  1712  4187 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-26 12:03:17.734  1712  4187 I SystemUpdateService: file has been verified
08-26 12:03:17.734  1712  4187 I SystemUpdateService: OTA package size = 12249756
,08-26 12:03:17.737  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 12:03:17.741  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 12:03:17.754  1712  4187 I SystemUpdateService: showing system update notification
,08-26 12:03:17.783  1712  1712 D SystemUpdateService: onDestroy
,08-26 12:03:17.797  1500  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-26 12:03:17.797  1500  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-26 12:03:17.798  1500  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 12:03:17.798  1500  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 12:03:17.824  1712  4190 E MDM     : [181] SitrepService.a: Error sending sitrep.
,08-26 12:03:17.839  2258  4193 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-26 12:03:18.541  3763  3811 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 418)
,08-26 12:03:18.541  3763  3811 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 418)
,08-26 12:03:18.554  3763  3811 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 423)
,08-26 12:03:18.558  3763  3811 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-26 12:03:18.558  3763  3811 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 424)
,08-26 12:03:18.562  3763  3811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 12:03:18.562  3763  3811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b49644c added. We now have 2 listener(s)
,08-26 12:03:18.565  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 12:03:18.566  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 12:03:18.566  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 12:03:18.566  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 12:03:18.566  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9970c95 added. We now have 9 listener(s)
08-26 12:03:18.566  3763  3811 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 12:03:18.567  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 12:03:18.573  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 12:03:18.582  3763  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 12:03:18.582  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:03:18.582  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:03:18.582  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:03:18.582  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:03:18.582  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:03:18.582  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:03:18.582  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 12:03:18.586  3763  3811 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 12:03:18.586  3763  3811 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 12:03:18.587  3763  3811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 12:03:18.587  3763  3811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abe19b added. We now have 3 listener(s)
,08-26 12:03:18.589  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 12:03:18.589  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 12:03:18.590  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 12:03:18.590  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 12:03:18.590  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce7938 added. We now have 10 listener(s)
08-26 12:03:18.590  3763  3811 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 12:03:18.590  3763  3811 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 12:03:18.590  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 12:03:18.590  3763  3811 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 12:03:18.590  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 12:03:18.591  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 12:03:18.591  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 12:03:18.591  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 12:03:18.591  3763  3811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b49644c removed from the list
08-26 12:03:18.591  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 12:03:18.592  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9970c95 removed from the list
,08-26 12:03:18.592  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:03:18.592  3763  3811 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:03:18.592  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 12:03:18.593  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:03:18.593  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 12:03:18.594  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 12:03:18.594  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:03:18.595  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 12:03:18.595  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9970c95 not in the list
08-26 12:03:18.595  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:03:18.595  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:03:18.597  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:03:18.597  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:03:18.597  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:03:18.597  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce7938 removed from the list
08-26 12:03:18.597  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:03:18.597  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 12:03:18.597  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:03:18.597  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 12:03:18.597  3763  3811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abe19b removed from the list
08-26 12:03:18.599  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:03:18.599  3763  3811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 12:03:18.599  3763  3811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a28dd11 added. We now have 2 listener(s)
08-26 12:03:18.602  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 12:03:18.602  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 12:03:18.603  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 12:03:18.603  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 12:03:18.603  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e77e76 added. We now have 9 listener(s)
08-26 12:03:18.603  3763  3811 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 12:03:18.604  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 12:03:18.607  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 12:03:18.614  3763  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 12:03:18.614  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:03:18.614  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:03:18.614  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:03:18.614  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:03:18.614  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:03:18.614  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:03:18.614  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 12:03:18.617  3763  3811 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 12:03:18.618  3763  3811 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 12:03:18.618   874  1310 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
08-26 12:03:18.620  3763  3811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 12:03:18.620  3763  3811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@98df0e4 added. We now have 3 listener(s)
08-26 12:03:18.622  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:03:18.626  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:03:18.626  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 12:03:18.626  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 12:03:18.626  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 12:03:18.627  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 12:03:18.627  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52d394d added. We now have 10 listener(s)
08-26 12:03:18.627  3763  3811 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 12:03:18.628  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 12:03:18.628  3763  3811 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-26 12:03:18.628  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 12:03:18.629  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 12:03:18.629  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 12:03:18.636  3763  3811 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-26 12:03:18.636  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 12:03:18.645  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 12:03:18.646  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-26 12:03:18.647  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 12:03:18.652  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 12:03:18.652  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 12:03:18.652  3763  3811 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 12:03:18.653  3763  3811 D BluetoothAdapter: STATE_ON
,08-26 12:03:18.659  4116  4161 D BtGatt.GattService: registerClient() - UUID=5563708a-75e0-448c-aa24-a08ae4e986df
,08-26 12:03:18.661  4116  4132 D BtGatt.GattService: onClientRegistered() - UUID=5563708a-75e0-448c-aa24-a08ae4e986df, clientIf=5
,08-26 12:03:18.663  3763  3775 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-26 12:03:18.666  4116  4126 D BtGatt.GattService: start scan with filters
,08-26 12:03:18.675  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 12:03:18.675  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-26 12:03:18.675  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 12:03:18.675  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 12:03:18.675  4116  4135 D BtGatt.ScanManager: handling starting scan
,08-26 12:03:18.680  4116  4135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcbab3a
,08-26 12:03:18.685  3763  3811 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 12:03:18.685  3763  3811 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 12:03:18.685  3763  3763 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 12:03:18.689  4116  4132 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 12:03:18.689  4116  4132 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 12:03:18.692  4116  4135 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 12:03:18.693  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 12:03:18.699  3763  3811 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 12:03:18.700  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 12:03:18.700  3763  3811 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 12:03:18.700  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 12:03:18.700  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 12:03:18.700  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-26 12:03:18.700  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 12:03:18.700  3763  3811 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 12:03:18.700  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 12:03:18.701  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-26 12:03:18.701  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 12:03:18.702  3763  3811 D BluetoothAdapter: STATE_ON
08-26 12:03:18.704  4116  4161 D BtGatt.GattService: stopScan() - queue size =1
,08-26 12:03:18.705  4116  4126 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-26 12:03:18.710  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 12:03:18.711  4116  4132 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 12:03:18.711  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-26 12:03:18.711  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 12:03:18.711  4116  4132 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 12:03:18.712  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-26 12:03:18.712  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 12:03:18.712  4116  4135 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 12:03:18.713  4116  4135 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 12:03:18.714  3763  3811 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 12:03:18.714  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 12:03:18.715  3763  3811 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 12:03:18.715  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 12:03:18.716  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 12:03:18.719  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 12:03:18.719  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 12:03:18.719  3763  3763 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 12:03:18.723  3763  3811 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 12:03:18.723  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:03:18.723  3763  3811 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 12:03:18.724  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:03:18.724  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 12:03:18.724  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 12:03:18.724  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 12:03:18.724  3763  3811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a28dd11 removed from the list
08-26 12:03:18.724  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:03:18.725  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e77e76 removed from the list
,08-26 12:03:18.725  3763  3811 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:03:18.725  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:03:18.726  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 12:03:18.726  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 12:03:18.729  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 12:03:18.729  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:03:18.729  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 12:03:18.730  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e77e76 not in the list
08-26 12:03:18.730  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:03:18.730  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:03:18.734  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:03:18.734  4116  4132 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 12:03:18.734  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:03:18.734  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:03:18.734  4116  4132 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 12:03:18.735  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52d394d removed from the list
08-26 12:03:18.735  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:03:18.735  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:03:18.736  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:03:18.736  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 12:03:18.736  3763  3811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@98df0e4 removed from the list
08-26 12:03:18.738  3763  3811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 12:03:18.738  3763  3811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ba11d49 added. We now have 2 listener(s)
,08-26 12:03:18.741  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 12:03:18.741  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 12:03:18.741  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 12:03:18.741  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 12:03:18.741  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9fbe64e added. We now have 9 listener(s)
08-26 12:03:18.741  3763  3811 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 12:03:18.742  4116  4132 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 12:03:18.742  4116  4132 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:03:18.742  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 12:03:18.752  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 12:03:18.755  4116  4132 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-26 12:03:18.755  4116  4132 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:03:18.755  4116  4135 D BtGatt.ScanManager: stopping BLe Batch
,08-26 12:03:18.760  3763  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 12:03:18.760  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:03:18.760  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:03:18.760  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:03:18.760  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:03:18.760  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:03:18.760  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:03:18.760  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 12:03:18.762  4116  4132 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 12:03:18.762  4116  4132 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:03:18.762  4116  4135 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 12:03:18.763  3763  3811 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 12:03:18.763  3763  3811 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 12:03:18.764  3763  3811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 12:03:18.764  3763  3811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e14787c added. We now have 3 listener(s)
,08-26 12:03:18.766  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 12:03:18.766  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 12:03:18.766  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 12:03:18.766  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:03:18.766  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 12:03:18.766  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7554505 added. We now have 10 listener(s)
08-26 12:03:18.766  3763  3811 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 12:03:18.767  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 12:03:18.768  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 12:03:18.768  3763  3811 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 12:03:18.768  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 12:03:18.768  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 12:03:18.768  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 12:03:18.769  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:03:18.769  4116  4132 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 12:03:18.769  4116  4132 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:03:18.772  3763  3811 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 12:03:18.772  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 12:03:18.776  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 12:03:18.776  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 12:03:18.776  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 12:03:18.779  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 12:03:18.779  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 12:03:18.779  3763  3811 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 12:03:18.780  3763  3811 D BluetoothAdapter: STATE_ON
,08-26 12:03:18.782  4116  4160 D BtGatt.GattService: registerClient() - UUID=ca35a88c-e0d7-4f8e-82e8-9532625668e4
,08-26 12:03:18.782  4116  4132 D BtGatt.GattService: onClientRegistered() - UUID=ca35a88c-e0d7-4f8e-82e8-9532625668e4, clientIf=5
08-26 12:03:18.783  3763  3803 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 12:03:18.783  4116  4161 D BtGatt.GattService: start scan with filters
,08-26 12:03:18.785  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 12:03:18.785  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 12:03:18.785  4116  4135 D BtGatt.ScanManager: handling starting scan
08-26 12:03:18.785  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 12:03:18.786  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 12:03:18.788  3763  3811 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 12:03:18.788  3763  3763 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 12:03:18.789  3763  3811 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 12:03:18.790  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 12:03:18.792  4116  4132 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 12:03:18.792  4116  4132 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:03:18.792  4116  4135 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-26 12:03:18.793  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 12:03:18.793  3763  3811 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-26 12:03:18.794  3763  3811 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:03:18.794  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:03:18.794  3763  3811 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:03:18.794  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:03:18.794  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:03:18.794  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-26 12:03:18.794  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 12:03:18.795  3763  3811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ba11d49 removed from the list
08-26 12:03:18.795  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:03:18.795  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9fbe64e removed from the list
08-26 12:03:18.795  3763  3811 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:03:18.795  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 12:03:18.796  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-26 12:03:18.796  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-26 12:03:18.796  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:03:18.796  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 12:03:18.797  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:03:18.797  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 12:03:18.797  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:03:18.797  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9fbe64e not in the list
08-26 12:03:18.797  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 12:03:18.797  3763  3811 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 12:03:18.797  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 12:03:18.798  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 12:03:18.798  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 12:03:18.798  4116  4132 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 12:03:18.798  3763  3811 D BluetoothAdapter: STATE_ON
08-26 12:03:18.798  4116  4132 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:03:18.798  4116  4135 D BtGatt.ScanManager: Starting BLE batch scan
08-26 12:03:18.799  4116  4135 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 12:03:18.799  4116  4149 D BtGatt.GattService: stopScan() - queue size =1
,08-26 12:03:18.799  4116  4126 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 12:03:18.800  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 12:03:18.800  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 12:03:18.800  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 12:03:18.800  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-26 12:03:18.800  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 12:03:18.801  3763  3811 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 12:03:18.802  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 12:03:18.802  3763  3811 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 12:03:18.802  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 12:03:18.802  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 12:03:18.803  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 12:03:18.803  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 12:03:18.804  3763  3763 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 12:03:18.804  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:03:18.804  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:03:18.804  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:03:18.804  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7554505 removed from the list
,08-26 12:03:18.804  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:03:18.804  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:03:18.804  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:03:18.804  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 12:03:18.804  3763  3811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e14787c removed from the list
08-26 12:03:18.805  3763  3811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 12:03:18.805  3763  3811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46a2c81 added. We now have 2 listener(s)
,08-26 12:03:18.807  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 12:03:18.807  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 12:03:18.807  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 12:03:18.807  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 12:03:18.808  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78a7126 added. We now have 9 listener(s)
08-26 12:03:18.808  3763  3811 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 12:03:18.809  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 12:03:18.810  4116  4132 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 12:03:18.810  4116  4132 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 12:03:18.813  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 12:03:18.816  4116  4132 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-26 12:03:18.816  4116  4132 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:03:18.817  3763  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 12:03:18.817  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:03:18.817  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:03:18.817  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:03:18.817  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:03:18.817  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:03:18.817  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:03:18.817  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 12:03:18.819  3763  3811 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 12:03:18.819  3763  3811 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 12:03:18.820  3763  3811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 12:03:18.820  3763  3811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9c15b14 added. We now have 3 listener(s)
08-26 12:03:18.821  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:03:18.823  4116  4132 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 12:03:18.823  4116  4132 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:03:18.823  4116  4135 D BtGatt.ScanManager: stopping BLe Batch
,08-26 12:03:18.824  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:03:18.825  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 12:03:18.825  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 12:03:18.825  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 12:03:18.825  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 12:03:18.825  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68c0fbd added. We now have 10 listener(s)
08-26 12:03:18.826  3763  3811 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-26 12:03:18.826  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 12:03:18.826  3763  3811 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 12:03:18.826  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-26 12:03:18.826  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 12:03:18.826  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 12:03:18.828  3763  3811 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 12:03:18.828  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 12:03:18.829  4116  4132 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 12:03:18.829  4116  4132 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:03:18.829  4116  4135 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-26 12:03:18.831  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 12:03:18.832  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 12:03:18.832  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 12:03:18.834  4116  4132 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-26 12:03:18.834  4116  4132 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:03:18.834  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 12:03:18.834  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 12:03:18.834  3763  3811 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 12:03:18.835  3763  3811 D BluetoothAdapter: STATE_ON
,08-26 12:03:18.836  4116  4161 D BtGatt.GattService: registerClient() - UUID=0b7dac79-5749-4e18-bbae-f19f73f3ed9f
08-26 12:03:18.836  4116  4132 D BtGatt.GattService: onClientRegistered() - UUID=0b7dac79-5749-4e18-bbae-f19f73f3ed9f, clientIf=5
,08-26 12:03:18.836  3763  3837 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 12:03:18.837  4116  4149 D BtGatt.GattService: start scan with filters
,08-26 12:03:18.838  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 12:03:18.838  4116  4135 D BtGatt.ScanManager: handling starting scan
08-26 12:03:18.838  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 12:03:18.838  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 12:03:18.839  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 12:03:18.840  3763  3811 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 12:03:18.841  3763  3763 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 12:03:18.841  3763  3811 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 12:03:18.842  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 12:03:18.844  4116  4132 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 12:03:18.844  4116  4132 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:03:18.844  4116  4135 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 12:03:18.845  3763  3811 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 12:03:18.845  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 12:03:18.845  3763  3811 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 12:03:18.845  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 12:03:18.845  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 12:03:18.846  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-26 12:03:18.846  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 12:03:18.846  3763  3811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46a2c81 removed from the list
08-26 12:03:18.846  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 12:03:18.846  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78a7126 removed from the list
,08-26 12:03:18.846  3763  3811 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 12:03:18.846  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
,08-26 12:03:18.846  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-26 12:03:18.846  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-26 12:03:18.846  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 12:03:18.846  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 12:03:18.847  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 12:03:18.847  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 12:03:18.847  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:03:18.847  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78a7126 not in the list
,08-26 12:03:18.847  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 12:03:18.847  3763  3811 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 12:03:18.848  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 12:03:18.848  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-26 12:03:18.848  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 12:03:18.848  3763  3811 D BluetoothAdapter: STATE_ON
,08-26 12:03:18.848  4116  4132 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-26 12:03:18.848  4116  4132 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-26 12:03:18.848  4116  4135 D BtGatt.ScanManager: Starting BLE batch scan
08-26 12:03:18.849  4116  4135 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-26 12:03:18.849  4116  4161 D BtGatt.GattService: stopScan() - queue size =1
,08-26 12:03:18.849  4116  4149 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-26 12:03:18.849  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 12:03:18.849  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 12:03:18.849  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
08-26 12:03:18.849  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 12:03:18.849  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 12:03:18.850  3763  3811 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 12:03:18.850  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 12:03:18.850  3763  3811 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 12:03:18.851  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 12:03:18.851  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 12:03:18.852  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 12:03:18.852  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 12:03:18.852  3763  3763 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 12:03:18.852  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:03:18.852  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 12:03:18.852  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:03:18.852  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68c0fbd removed from the list
,08-26 12:03:18.852  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:03:18.852  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 12:03:18.853  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:03:18.853  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 12:03:18.853  3763  3811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9c15b14 removed from the list
08-26 12:03:18.853  3763  3811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-26 12:03:18.853  3763  3811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5eeeab9 added. We now have 2 listener(s)
,08-26 12:03:18.855  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 12:03:18.855  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 12:03:18.855  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 12:03:18.855  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 12:03:18.855  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6547efe added. We now have 9 listener(s)
08-26 12:03:18.855  3763  3811 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 12:03:18.856  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 12:03:18.857  4116  4132 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-26 12:03:18.857  4116  4132 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:03:18.859  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 12:03:18.861  4116  4132 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-26 12:03:18.861  4116  4132 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 12:03:18.862  3763  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 12:03:18.862  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:03:18.862  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:03:18.862  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:03:18.862  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:03:18.862  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:03:18.862  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:03:18.862  3763  3811 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 12:03:18.864  3763  3811 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 12:03:18.864  3763  3811 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 12:03:18.865  3763  3811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 12:03:18.865  3763  3811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9a4f8ac added. We now have 3 listener(s)
08-26 12:03:18.866  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:03:18.868  4116  4132 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-26 12:03:18.868  4116  4132 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:03:18.868  4116  4135 D BtGatt.ScanManager: stopping BLe Batch
,08-26 12:03:18.868  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 12:03:18.868  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:03:18.869  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 12:03:18.869  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 12:03:18.869  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 12:03:18.869  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a7975 added. We now have 10 listener(s)
,08-26 12:03:18.869  3763  3811 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 12:03:18.869  3763  3811 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 12:03:18.869  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:03:18.869  3763  3811 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 12:03:18.869  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:03:18.869  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 12:03:18.869  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 12:03:18.869  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 12:03:18.869  3763  3811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5eeeab9 removed from the list
08-26 12:03:18.869  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:03:18.869  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6547efe removed from the list
,08-26 12:03:18.870  3763  3811 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:03:18.870  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:03:18.870  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 12:03:18.870  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:03:18.871  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:03:18.871  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 12:03:18.871  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:03:18.871  3763  3811 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6547efe not in the list
08-26 12:03:18.871  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:03:18.871  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:03:18.872  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 12:03:18.872  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:03:18.872  3763  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-26 12:03:18.872  3763  3811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a7975 removed from the list
,08-26 12:03:18.872  3763  3811 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 12:03:18.872  3763  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:03:18.872  3763  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 12:03:18.872  3763  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 12:03:18.872  3763  3811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9a4f8ac removed from the list
,08-26 12:03:18.873  4116  4132 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 12:03:18.873  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-26 12:03:18.873  4116  4132 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:03:18.873  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-26 12:03:18.873  4116  4135 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 12:03:18.873  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-26 12:03:18.873  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 12:03:18.873  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-26 12:03:18.873  3763  3811 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 12:03:18.878  4116  4132 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 12:03:18.878  4116  4132 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:03:18.880  3763  4199 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 431, name: My test thread name)
08-26 12:03:18.880  3763  4199 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 431, thread name: My test thread name)
08-26 12:03:18.880  3763  4199 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 431, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-26 12:03:18.882  3763  4200 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 433, name: My test thread name)
,08-26 12:03:18.882  3763  4200 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 433, thread name: My test thread name)
08-26 12:03:18.882  3763  4200 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 433, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-26 12:03:18.883  3763  3811 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-26 12:03:18.883  3763  3811 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-26 12:03:18.883  3763  3811 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-26 12:03:18.883  3763  3811 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-26 12:03:18.883  3763  3811 D com.test.thalitest.ThaliTestRunner: Total duration: 23026 ms
,08-26 12:03:18.885  3763  3811 I jxcore-log: *Native tests were executed*
08-26 12:03:18.885  3763  3811 I jxcore-log: 
08-26 12:03:18.885  3763  3811 I jxcore-log: Total number of executed tests:  80
08-26 12:03:18.885  3763  3811 I jxcore-log: 
08-26 12:03:18.885  3763  3811 I jxcore-log: Number of passed tests:  80
08-26 12:03:18.885  3763  3811 I jxcore-log: 
,08-26 12:03:18.886  3763  3811 I jxcore-log: Number of failed tests:  0
08-26 12:03:18.886  3763  3811 I jxcore-log: 
08-26 12:03:18.886  3763  3811 I jxcore-log: Number of ignored tests:  0
08-26 12:03:18.886  3763  3811 I jxcore-log: 
08-26 12:03:18.886  3763  3811 I jxcore-log: Total duration:  23026
08-26 12:03:18.886  3763  3811 I jxcore-log: 
,08-26 12:03:18.886  3763  3811 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-26 12:03:18.886  3763  3811 I jxcore-log: 
08-26 12:03:18.890  3763  3811 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:03:18.890  3763  3811 I jxcore-log: 
08-26 12:03:18.893  3763  3811 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:03:18.893  3763  3811 I jxcore-log: 
,08-26 12:03:18.894  3763  3763 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-26 12:03:18.894  3763  3811 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:03:18.894  3763  3811 I jxcore-log: 
08-26 12:03:18.895  3763  3811 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:03:18.895  3763  3811 I jxcore-log: 
08-26 12:03:18.896  3763  3811 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:03:18.896  3763  3811 I jxcore-log: 
08-26 12:03:18.897  3763  3811 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:03:18.897  3763  3811 I jxcore-log: 
08-26 12:03:18.899  3763  3811 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:03:18.899  3763  3811 I jxcore-log: 
08-26 12:03:18.900  3763  3811 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 12:03:18.900  3763  3811 I jxcore-log: 
08-26 12:03:18.901  3763  3811 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 12:03:18.901  3763  3811 I jxcore-log: 
08-26 12:03:18.902  3763  3811 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 12:03:18.902  3763  3811 I jxcore-log: 
08-26 12:03:18.903  3763  3811 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 12:03:18.903  3763  3811 I jxcore-log: 
08-26 12:03:18.904  3763  3811 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 12:03:18.904  3763  3811 I jxcore-log: 
08-26 12:03:18.905  3763  3811 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:03:18.905  3763  3811 I jxcore-log: 
08-26 12:03:18.906  3763  3811 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:03:18.906  3763  3811 I jxcore-log: 
08-26 12:03:18.907  3763  3811 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 12:03:18.907  3763  3811 I jxcore-log: 
08-26 12:03:18.907  3763  3811 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 12:03:18.907  3763  3811 I jxcore-log: 
08-26 12:03:18.908  3763  3811 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 12:03:18.908  3763  3811 I jxcore-log: 
08-26 12:03:18.909  3763  3811 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 12:03:18.909  3763  3811 I jxcore-log: 
08-26 12:03:18.910  3763  3811 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 12:03:18.910  3763  3811 I jxcore-log: 
08-26 12:03:18.910  3763  3811 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 12:03:18.910  3763  3811 I jxcore-log: 
08-26 12:03:18.911  3763  3811 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 12:03:18.911  3763  3811 I jxcore-log: 
08-26 12:03:18.912  3763  3811 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 12:03:18.912  3763  3811 I jxcore-log: 
08-26 12:03:18.913  3763  3811 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 12:03:18.913  3763  3811 I jxcore-log: 
08-26 12:03:18.913  3763  3811 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 12:03:18.913  3763  3811 I jxcore-log: 
08-26 12:03:18.914  3763  3811 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:03:18.914  3763  3811 I jxcore-log: 
08-26 12:03:18.915  3763  3811 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:03:18.915  3763  3811 I jxcore-log: 
08-26 12:03:18.916  3763  3811 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:03:18.916  3763  3811 I jxcore-log: 
08-26 12:03:18.917  3763  3811 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:03:18.917  3763  3811 I jxcore-log: 
08-26 12:03:18.918  3763  3811 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:03:18.918  3763  3811 I jxcore-log: 
08-26 12:03:18.919  3763  3811 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:03:18.919  3763  3811 I jxcore-log: 
,08-26 12:03:19.220  3763  3763 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 12:03:19.223  3763  3811 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 12:03:19.223  3763  3811 I jxcore-log: 
,08-26 12:03:19.304  3763  3763 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 12:03:19.307  3763  3811 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 12:03:19.307  3763  3811 I jxcore-log: 
,08-26 12:03:19.353  3763  3763 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 12:03:19.356  3763  3811 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 12:03:19.356  3763  3811 I jxcore-log: 
,08-26 12:03:19.559  4201  4201 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-26 12:03:19.564  4201  4201 D AndroidRuntime: CheckJNI is OFF
,08-26 12:03:19.608  4201  4201 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-26 12:03:19.656  4201  4201 I Radio-JNI: register_android_hardware_Radio DONE
,08-26 12:03:19.679  4201  4201 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-26 12:03:19.691   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-26 12:03:19.692   874   887 I ActivityManager: Killing 3763:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-26 12:03:19.787   874   897 W PackageSettings: Skipping PackageSetting{bb3c55f com.example.hello/10273} due to missing metadata
,08-26 12:03:19.805   874  1964 I WindowState: WIN DEATH: Window{adc8fdf u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-26 12:03:19.806   874   885 D GraphicsStats: Buffer count: 2
08-26 12:03:19.808   874  1309 D WifiService: Client connection lost with reason: 4
,08-26 12:03:19.840   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-26 12:03:19.840   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-26 12:03:19.841   874   887 E ActivityManager: Failure starting process com.test.thalitest
08-26 12:03:19.841   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-26 12:03:19.841   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-26 12:03:19.841   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-26 12:03:19.841   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-26 12:03:19.841   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-26 12:03:19.841   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-26 12:03:19.841   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-26 12:03:19.841   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-26 12:03:19.841   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-26 12:03:19.841   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-26 12:03:19.841   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-26 12:03:19.841   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-26 12:03:19.841   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-26 12:03:19.841   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-26 12:03:19.841   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-26 12:03:19.841   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:03:19.841   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:03:19.841   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 12:03:19.841   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-26 12:03:19.842   874   887 I ActivityManager:   Force finishing activity ActivityRecord{5e99c22 u0 com.test.thalitest/.MainActivity t2}
,08-26 12:03:19.845   874   897 I art     : Starting a blocking GC Explicit
,08-26 12:03:19.852   874  1992 W ActivityManager: Spurious death for ProcessRecord{b249db0 0:com.test.thalitest/u0a0}, curProc for 3763: null
,08-26 12:03:19.911   874   897 I art     : Explicit concurrent mark sweep GC freed 56637(3MB) AllocSpace objects, 10(296KB) LOS objects, 33% free, 29MB/43MB, paused 1.070ms total 65.725ms
,08-26 12:03:19.972   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-26 12:03:19.977  4201  4201 I art     : System.exit called, status: 0
,08-26 12:03:19.977  4201  4201 I AndroidRuntime: VM exiting with result code 0.
,08-26 12:03:19.992   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-26 12:03:20.015   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-26 12:03:20.021  4116  4116 D BluetoothMapAppObserver: onReceive
,08-26 12:03:20.021  4116  4116 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-26 12:03:20.022  1872  1872 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-26 12:03:20.023  1884  2221 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-26 12:03:20.030  3605  3605 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-26 12:03:20.030   874  1300 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-26 12:03:20.038  1872  4214 I Keyboard.Facilitator.DecoderInitializer: run()
,08-26 12:03:20.048  1872  4214 I Decoder : createOrResetDecoder
,08-26 12:03:20.057   874  1978 I ActivityManager: Start proc 4216:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-26 12:03:20.080  1946  1946 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-26 12:03:20.088   874  1306 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,08-26 12:03:20.096  1500  1500 I ConfigService: onCreate
,08-26 12:03:20.106  1500  4229 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-26 12:03:20.106  1500  4229 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 12:03:20.106  1500  4229 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 12:03:20.106  1500  4229 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 12:03:20.106  1500  4229 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 12:03:20.106  1500  4229 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 12:03:20.106  1500  4229 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 12:03:20.106  1500  4229 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 12:03:20.106  1500  4229 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 12:03:20.106  1500  4229 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 12:03:20.106  1500  4229 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 12:03:20.106  1500  4229 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 12:03:20.106  1500  4229 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 12:03:20.106  1500  4229 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 12:03:20.106  1500  4229 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 12:03:20.106  1500  4229 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-26 12:03:20.106  1500  4229 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-26 12:03:20.106  1500  4229 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-26 12:03:20.107  1500  4229 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-26 12:03:20.107  1500  4229 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 12:03:20.107  1500  4229 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 12:03:20.107  1500  4229 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 12:03:20.107  1500  4229 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 12:03:20.107  1500  4229 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 12:03:20.107  1500  4229 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 12:03:20.107  1500  4229 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 12:03:20.107  1500  4229 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 12:03:20.107  1500  4229 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 12:03:20.107  1500  4229 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 12:03:20.107  1500  4229 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 12:03:20.107  1500  4229 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 12:03:20.107  1500  4229 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 12:03:20.107  1500  4229 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 12:03:20.107  1500  4229 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-26 12:03:20.107  1500  4229 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-26 12:03:20.107  1500  4229 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,08-26 12:03:20.108  1500  4229 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-26 12:03:20.123   874  1392 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3763 uid 10000
08-26 12:03:20.124  1872  1872 I Keyboard.Facilitator: onFinishInput()
,08-26 12:03:20.125  1872  4214 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-26 12:03:20.152  4216  4216 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-26 12:03:20.155   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-26 12:03:20.168  1959  2070 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-26 12:03:20.168   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-26 12:03:20.169   874   886 E PackageManager: Failed to write settings, restoring backup
08-26 12:03:20.169   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-26 12:03:20.169   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-26 12:03:20.169   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-26 12:03:20.169   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-26 12:03:20.169   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-26 12:03:20.169   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:03:20.169   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:03:20.169   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 12:03:20.173   874   887 E DropBoxManagerService: Can't write: system_server_wtf
08-26 12:03:20.173   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-26 12:03:20.173   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 12:03:20.173   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 12:03:20.173   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 12:03:20.173   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 12:03:20.173   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 12:03:20.173   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 12:03:20.173   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-26 12:03:20.173   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-26 12:03:20.173   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-26 12:03:20.173   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 12:03:20.173   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 12:03:20.173   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:03:20.173   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 12:03:20.173   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-26 12:03:20.173   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 12:03:20.173   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 12:03:20.173   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 12:03:20.173   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 12:03:20.173   874   887 E DropBoxManagerService: 	... 13 more
,08-26 12:03:20.175  1872  4214 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-26 12:03:20.177  1872  4214 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-26 12:03:20.177  1872  4214 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-26 12:03:20.179  1872  4214 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-26 12:03:20.179  1872  4214 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-26 12:03:20.180  1872  4214 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-26 12:03:20.180  1872  4214 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-26 12:03:20.181   874  1990 I ActivityManager: Start proc 4231:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-26 12:03:20.182  1959  2070 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-26 12:03:20.182  1959  2070 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1959
08-26 12:03:20.182  1959  2070 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 12:03:20.182  1959  2070 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-26 12:03:20.182  1959  2070 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-26 12:03:20.182  1959  2070 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-26 12:03:20.182  1959  2070 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-26 12:03:20.182  1959  2070 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-26 12:03:20.182  1959  2070 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-26 12:03:20.182  1959  2070 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-26 12:03:20.182  1959  2070 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 12:03:20.182  1959  2070 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 12:03:20.182  1959  2070 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:03:20.182  1959  2070 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 12:03:20.184   874  1711 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-26 12:03:20.184   874  4236 E DropBoxManagerService: Can't write: system_app_crash
08-26 12:03:20.184   874  4236 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-26 12:03:20.184   874  4236 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 12:03:20.184   874  4236 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 12:03:20.184   874  4236 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 12:03:20.184   874  4236 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 12:03:20.184   874  4236 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 12:03:20.184   874  4236 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 12:03:20.184   874  4236 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 12:03:20.184   874  4236 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 12:03:20.184   874  4236 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 12:03:20.184   874  4236 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 12:03:20.184   874  4236 E DropBoxManagerService: 	... 5 more
,08-26 12:03:20.189  1959  2070 I Process : Sending signal. PID: 1959 SIG: 9
,08-26 12:03:20.192  1872  4214 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-26 12:03:20.192  1872  4214 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-26 12:03:20.192  1872  4214 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-26 12:03:20.194  1872  4214 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-26 12:03:20.195  1872  4214 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,08-26 12:03:20.195  1872  4214 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-26 12:03:20.234  4216  4216 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-26 12:03:20.244  4216  4249 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-26 12:03:20.252   874   884 I ActivityManager: Start proc 4250:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-26 12:03:20.255   874  1991 D GraphicsStats: Buffer count: 1
,08-26 12:03:20.255   874  1392 I WindowState: WIN DEATH: Window{5aef0bb u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-26 12:03:20.269  4216  4247 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-26 12:03:20.269  4216  4247 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 12:03:20.269  4216  4247 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 12:03:20.269  4216  4247 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 12:03:20.269  4216  4247 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 12:03:20.269  4216  4247 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 12:03:20.269  4216  4247 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 12:03:20.269  4216  4247 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 12:03:20.269  4216  4247 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 12:03:20.269  4216  4247 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 12:03:20.269  4216  4247 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 12:03:20.269  4216  4247 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 12:03:20.269  4216  4247 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 12:03:20.269  4216  4247 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 12:03:20.269  4216  4247 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 12:03:20.269  4216  4247 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-26 12:03:20.269  4216  4247 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-26 12:03:20.269  4216  4247 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-26 12:03:20.269  4216  4247 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-26 12:03:20.269  4216  4247 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:03:20.269  4216  4247 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:03:20.269  4216  4247 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 12:03:20.271   874  1991 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1959) has died
,08-26 12:03:20.272   874  1991 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-26 12:03:20.273   874  1991 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-26 12:03:20.281  4216  4247 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-26 12:03:20.281  4216  4247 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 12:03:20.281  4216  4247 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 12:03:20.281  4216  4247 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 12:03:20.281  4216  4247 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 12:03:20.281  4216  4247 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 12:03:20.281  4216  4247 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 12:03:20.281  4216  4247 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 12:03:20.281  4216  4247 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 12:03:20.281  4216  4247 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 12:03:20.281  4216  4247 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 12:03:20.281  4216  4247 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 12:03:20.281  4216  4247 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 12:03:20.281  4216  4247 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 12:03:20.281  4216  4247 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 12:03:20.281  4216  4247 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-26 12:03:20.281  4216  4247 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-26 12:03:20.281  4216  4247 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-26 12:03:20.281  4216  4247 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-26 12:03:20.281  4216  4247 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:03:20.281  4216  4247 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:03:20.281  4216  4247 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 12:03:20.288   874   885 I ActivityManager: Start proc 4263:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-26 12:03:20.325  4250  4250 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-26 12:03:20.337  1884  2513 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-26 12:03:20.340  1500  1500 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-26 12:03:20.341  1500  1500 D AndroidRuntime: Shutting down VM
08-26 12:03:20.342  1500  1500 E AndroidRuntime: FATAL EXCEPTION: main
08-26 12:03:20.342  1500  1500 E AndroidRuntime: Process: com.google.process.gapps, PID: 1500
08-26 12:03:20.342  1500  1500 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 12:03:20.342  1500  1500 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-26 12:03:20.342  1500  1500 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-26 12:03:20.342  1500  1500 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-26 12:03:20.342  1500  1500 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:03:20.342  1500  1500 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:03:20.342  1500  1500 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 12:03:20.342  1500  1500 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 12:03:20.342  1500  1500 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 12:03:20.342  1500  1500 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 12:03:20.342  1500  1500 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 12:03:20.342  1500  1500 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-26 12:03:20.342  1500  1500 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-26 12:03:20.342  1500  1500 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-26 12:03:20.342  1500  1500 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-26 12:03:20.342  1500  1500 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-26 12:03:20.342  1500  1500 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-26 12:03:20.342  1500  1500 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-26 12:03:20.342  1500  1500 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-26 12:03:20.342  1500  1500 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-26 12:03:20.342  1500  1500 E AndroidRuntime: 	... 8 more
08-26 12:03:20.345  4263  4263 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-26 12:03:20.345  4263  4263 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 12:03:20.345  4263  4263 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 12:03:20.345  4263  4263 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 12:03:20.345  4263  4263 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 12:03:20.345  4263  4263 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 12:03:20.345  4263  4263 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 12:03:20.345  4263  4263 E SQLiteDatabase: 	at android.database.sqlite.SQLit,eConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 12:03:20.345  4263  4263 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 12:03:20.345  4263  4263 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 12:03:20.345  4263  4263 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 12:03:20.345  4263  4263 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 12:03:20.345  4263  4263 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 12:03:20.345  4263  4263 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 12:03:20.345  4263  4263 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 12:03:20.345  4263  4263 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-26 12:03:20.345  4263  4263 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-26 12:03:20.345  4263  4263 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-26 12:03:20.345  4263  4263 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-26 12:03:20.345  4263  4263 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-26 12:03:20.345  4263  4263 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-26 12:03:20.345  4263  4263 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-26 12:03:20.345  4263  4263 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 12:03:20.345  4263  4263 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 12:03:20.345  4263  4263 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:03:20.345  4263  4263 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:03:20.345  4263  4263 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 12:03:20.345  4263  4263 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 12:03:20.345  4263  4263 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 12:03:20.345  4263  4263 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 12:03:20.345  4263  4263 D AndroidRuntime: Shutting down VM
08-26 12:03:20.346   874  4278 E DropBoxManagerService: Can't write: system_app_crash
08-26 12:03:20.346   874  4278 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-26 12:03:20.346   874  4278 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 12:03:20.346   874  4278 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 12:03:20.346   874  4278 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 12:03:20.346   874  4278 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 12:03:20.346   874  4278 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 12:03:20.346   874  4278 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 12:03:20.346   874  4278 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 12:03:20.346   874  4278 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 12:03:20.346   87,4  4278 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 12:03:20.346   874  4278 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 12:03:20.346   874  4278 E DropBoxManagerService: 	... 5 more
08-26 12:03:20.346  1500  1500 I Process : Sending signal. PID: 1500 SIG: 9
08-26 12:03:20.351  4263  4263 E AndroidRuntime: FATAL EXCEPTION: main
08-26 12:03:20.351  4263  4263 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4263
08-26 12:03:20.351  4263  4263 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 12:03:20.351  4263  4263 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-26 12:03:20.351  4263  4263 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-26 12:03:20.351  4263  4263 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-26 12:03:20.351  4263  4263 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 12:03:20.351  4263  4263 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 12:03:20.351  4263  4263 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:03:20.351  4263  4263 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:03:20.351  4263  4263 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 12:03:20.351  4263  4263 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 12:03:20.351  4263  4263 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 12:03:20.351  4263  4263 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 12:03:20.351  4263  4263 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 12:03:20.351  4263  4263 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 12:03:20.351  4263  4263 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 12:03:20.351  4263  4263 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 12:03:20.351  4263  4263 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 12:03:20.351  4263  4263 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 12:03:20.351  4263  4263 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 12:03:20.351  4263  4263 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 12:03:20.351  4263  4263 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 12:03:20.351  4263  4263 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 12:03:20.351  4263  4263 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 12:03:20.351  4263  4263 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 12:03:20.351  4263  4263 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 12:03:20.351  4263  4263 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 12:03:20.351  4263  4263 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-26 12:03:20.351  4263  4263 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-26 12:03:20.351  4263  4263 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-26 12:03:20.351  4263  4263 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-26 12:03:20.351  4263  4263 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-26 12:03:20.351  4263  4263 E AndroidRuntime: 	... 10 more
08-26 12:03:20.352   874  1390 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-26 12:03:20.353  4263  4263 I Process : Sending signal. PID: 4263 SIG: 9
08-26 12:03:20.354   874  4279 E DropBoxManagerService: Can't write: system_app_crash
08-26 12:03:20.354   874  4279 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-26 12:03:20.354   874  4279 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 12:03:20.354   874  4279 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 12:03:20.354   874  4279 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 12:03:20.354   874  4279 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 12:03:20.354   874  4279 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 12:03:20.354   874  4279 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 12:03:20.354   874  4279 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 12:03:20.354   874  4279 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 12:03:20.354   874  4279 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 12:03:20.354   874  4279 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 12:03:20.354   874  4279 E DropBoxManagerService: 	... 5 more
08-26 12:03:20.357   874  1308 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
08-26 12:03:20.380   874  1995 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4263) has died
08-26 12:03:20.382   874  1995 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-26 12:03:20.389   874  1309 D WifiService: Client connection lost with reason: 4
08-26 12:03:20.391  1712  4280 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@a6dd820
08-26 12:03:20.394  4216  4247 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
08-26 12:03:20.399  4216  4249 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-26 12:03:20.399  4216  4249 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 12:03:20.399  4216  4249 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 12:03:20.399  4216  4249 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 12:03:20.399  4216  4249 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 12:03:20.399  4216  4249 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 12:03:20.399  4216  4249 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 12:03:20.399  4216  4249 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 12:03:20.399  4216  4249 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 12:03:20.399  4216  4249 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 12:03:20.399  4216  4249 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 12:03:20.399  4216  4249 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 12:03:20.399  4216  4249 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 12:03:20.399  4216  4249 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 12:03:20.399  4216  4249 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 12:03:20.399  4216  4249 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-26 12:03:20.399  4216  4249 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-26 12:03:20.399  4216  4249 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-26 12:03:20.399  4216  4249 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-26 12:03:20.399  4216  4249 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-26 12:03:20.399  4216  4249 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-26 12:03:20.399  4216  4249 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-26 12:03:20.399  4216  4249 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:03:20.399  4216  4249 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:03:20.399  4216  4249 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 12:03:20.399  4216  4249 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-26 12:03:20.399  4216  4249 E AndroidRuntime: Process: android.process.acore, PID: 4216
08-26 12:03:20.399  4216  4249 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 12:03:20.399  4216  4249 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 12:03:20.399  4216  4249 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 12:03:20.399  4216  4249 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 12:03:20.399  4216  4249 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 12:03:20.399  4216  4249 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 12:03:20.399  4216  4249 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 12:03:20.399  4216  4249 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 12:03:20.399  4216  4249 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 12:03:20.399  4216  4249 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 12:03:20.399  4216  4249 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 12:03:20.399  4216  4249 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 12:03:20.399  4216  4249 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 12:03:20.399  4216  4249 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 12:03:20.399  4216  4249 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-26 12:03:20.399  4216  4249 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-26 12:03:20.399  4216  4249 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-26 12:03:20.399  4216  4249 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-26 12:03:20.399  4216  4249 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-26 12:03:20.399  4216  4249 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-26 12:03:20.399  4216  4249 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-26 12:03:20.399  4216  4249 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:03:20.399  4216  4249 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:03:20.399  4216  4249 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 12:03:20.401  4216  4247 I Process : Sending signal. PID: 4216 SIG: 9
08-26 12:03:20.405   874   887 I ActivityManager: Start proc 4283:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-26 12:03:20.405   874   884 I ActivityManager: Process com.google.process.gapps (pid 1500) has died
08-26 12:03:20.405   874   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
08-26 12:03:20.406   874   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
08-26 12:03:20.406   874   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 20999ms
08-26 12:03:20.406   874   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 30999ms
08-26 12:03:20.411   874  4288 E DropBoxManagerService: Can't write: system_app_crash
08-26 12:03:20.411   874  4288 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-26 12:03:20.411   874  4288 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 12:03:20.411   874  4288 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 12:03:20.411   874  4288 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 12:03:20.411   874  4288 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 12:03:20.411   874  4288 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 12:03:20.411   874  4288 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 12:03:20.411   874  4288 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 12:03:20.411   874  4288 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 12:03:20.411   874  4288 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 12:03:20.411   874  4288 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 12:03:20.411   874  4288 E DropBoxManagerService: 	... 5 more
,08-26 12:03:20.423   874  1995 I ActivityManager: Start proc 4296:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
08-26 12:03:20.430  1712  1712 W RocketImpressions: ClearcutLogger connection suspended: 1
08-26 12:03:20.452  4283  4283 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-26 12:03:20.452  4283  4283 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 12:03:20.452  4283  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 12:03:20.452  4283  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 12:03:20.452  4283  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 12:03:20.452  4283  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 12:03:20.452  4283  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 12:03:20.452  4283  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 12:03:20.452  4283  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 12:03:20.452  4283  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 12:03:20.452  4283  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 12:03:20.452  4283  4283 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 12:03:20.452  4283  4283 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 12:03:20.452  4283  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 12:03:20.452  4283  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 12:03:20.452  4283  4283 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-26 12:03:20.452  4283  4283 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-26 12:03:20.452  4283  4283 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-26 12:03:20.452  4283  4283 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-26 12:03:20.452  4283  4283 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-26 12:03:20.452  4283  4283 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-26 12:03:20.452  4283  4283 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-26 12:03:20.452  4283  4283 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 12:03:20.452  4283  4283 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 12:03:20.452  4283  4283 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:03:20.452  4283  4283 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:03:20.452  4283  4283 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 12:03:20.452  4283  4283 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 12:03:20.452  4283  4283 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 12:03:20.452  4283  4283 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 12:03:20.454  4283  4283 D AndroidRuntime: Shutting down VM
,08-26 12:03:20.461  1712  1712 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-26 12:03:20.461  1712  1712 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-26 12:03:20.462  4283  4283 E AndroidRuntime: FATAL EXCEPTION: main
08-26 12:03:20.462  4283  4283 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4283
08-26 12:03:20.462  4283  4283 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 12:03:20.462  4283  4283 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-26 12:03:20.462  4283  4283 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-26 12:03:20.462  4283  4283 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-26 12:03:20.462  4283  4283 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 12:03:20.462  4283  4283 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 12:03:20.462  4283  4283 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:03:20.462  4283  4283 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:03:20.462  4283  4283 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 12:03:20.462  4283  4283 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 12:03:20.462  4283  4283 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 12:03:20.462  4283  4283 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 12:03:20.462  4283  4283 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 12:03:20.462  4283  4283 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 12:03:20.462  4283  4283 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 12:03:20.462  4283  4283 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 12:03:20.462  4283  4283 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 12:03:20.462  4283  4283 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 12:03:20.462  4283  4283 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 12:03:20.462  4283  4283 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 12:03:20.462  4283  4283 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 12:03:20.462  4283  4283 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 12:03:20.462  4283  4283 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 12:03:20.462  4283  4283 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 12:03:20.462  4283  4283 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 12:03:20.462  4283  4283 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 12:03:20.462  4283  4283 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-26 12:03:20.462  4283  4283 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-26 12:03:20.462  4283  4283 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:174,8)
08-26 12:03:20.462  4283  4283 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-26 12:03:20.462  4283  4283 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-26 12:03:20.462  4283  4283 E AndroidRuntime: 	... 10 more
08-26 12:03:20.464  4296  4296 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
08-26 12:03:20.466   874  1991 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-26 12:03:20.467  4283  4283 I Process : Sending signal. PID: 4283 SIG: 9
08-26 12:03:20.468   874  4310 E DropBoxManagerService: Can't write: system_app_crash
08-26 12:03:20.468   874  4310 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-26 12:03:20.468   874  4310 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 12:03:20.468   874  4310 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 12:03:20.468   874  4310 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 12:03:20.468   874  4310 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 12:03:20.468   874  4310 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 12:03:20.468   874  4310 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 12:03:20.468   874  4310 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 12:03:20.468   874  4310 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 12:03:20.468   874  4310 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 12:03:20.468   874  4310 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 12:03:20.468   874  4310 E DropBoxManagerService: 	... 5 more
08-26 12:03:20.469  1712  1712 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-26 12:03:20.469  1712  1712 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-26 12:03:20.469  4296  4296 I GservicesProvider: Gservices pushing to system: true; secure/global: true
08-26 12:03:20.471  4296  4296 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-26 12:03:20.471  4296  4296 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 12:03:20.471  4296  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 12:03:20.471  4296  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 12:03:20.471  4296  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 12:03:20.471  4296  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 12:03:20.471  4296  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 12:03:20.471  4296  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 12:03:20.471  4296  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 12:03:20.471  4296  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 12:03:20.471  4296  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 12:03:20.471  4296  4296 E SQLiteDatabase: 	at android.app.ContextI,mpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 12:03:20.471  4296  4296 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 12:03:20.471  4296  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 12:03:20.471  4296  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 12:03:20.471  4296  4296 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-26 12:03:20.471  4296  4296 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-26 12:03:20.471  4296  4296 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-26 12:03:20.471  4296  4296 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-26 12:03:20.471  4296  4296 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-26 12:03:20.471  4296  4296 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-26 12:03:20.471  4296  4296 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-26 12:03:20.471  4296  4296 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 12:03:20.471  4296  4296 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 12:03:20.471  4296  4296 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:03:20.471  4296  4296 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:03:20.471  4296  4296 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 12:03:20.471  4296  4296 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 12:03:20.471  4296  4296 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 12:03:20.471  4296  4296 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 12:03:20.472  4296  4296 D AndroidRuntime: Shutting down VM
08-26 12:03:20.472  4296  4296 E AndroidRuntime: FATAL EXCEPTION: main
08-26 12:03:20.472  4296  4296 E AndroidRuntime: Process: com.google.process.gapps, PID: 4296
08-26 12:03:20.472  4296  4296 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 12:03:20.472  4296  4296 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-26 12:03:20.472  4296  4296 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-26 12:03:20.472  4296  4296 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-26 12:03:20.472  4296  4296 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 12:03:20.472  4296  4296 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 12:03:20.472  4296  4296 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:03:20.472  4296  4296 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:03:20.472  4296  4296 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 12:03:20.472  4296  4296 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 12:03:20.472  4296  4296 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 12:03:20.472  4296  4296 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 12:03:20.472  4296  4296 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 12:03:20.472  4296  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 12:03:20.472  4296  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 12:03:20.472  4296  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 12:03:20.472  4296  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 12:03:20.472  4296  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 12:03:20.472  4296  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 12:03:20.472  4296  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 12:03:20.472  4296  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 12:03:20.472  4296  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 12:03:20.472  4296  4296 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 12:03:20.472  4296  4296 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 12:03:20.472  4296  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 12:03:20.472  4296  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 12:03:20.472  4296  4296 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-26 12:03:20.472  4296  4296 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-26 12:03:20.472  4296  4296 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-26 12:03:20.472  4296  4296 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-26 12:03:20.472  4296  4296 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-26 12:03:20.472  4296  4296 E AndroidRuntime: 	... 10 more
08-26 12:03:20.473   279   279 E lowmemorykiller: Error writing /proc/4216/oom_score_adj; errno=22
08-26 12:03:20.475  4296  4296 I Process : Sending signal. PID: 4296 SIG: 9
08-26 12:03:20.476   874  4312 E DropBoxManagerService: Can't write: system_app_crash
08-26 12:03:20.476   874  4312 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-26 12:03:20.476   874  4312 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 12:03:20.476   874  4312 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 12:03:20.476   874  4312 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 12:03:20.476   874  4312 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 12:03:20.476   874  4312 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 12:03:20.476   874  4312 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 12:03:20.476   874  4312 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 12:03:20.476   874  4312 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 12:03:20.476   874  4312 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 12:03:20.476   874  4312 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 12:03:20.476   874  4312 E DropBoxManagerService: 	... 5 more
08-26 12:03:20.477   281   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
