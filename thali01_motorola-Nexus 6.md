#### Test 797638308bd3e25_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-26 12:45:29.809  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 12:45:29.820  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-26 12:45:29.824  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-26 12:45:29.859  1523  2431 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-26 12:45:29.860  1523  2431 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-26 12:45:29.860  1523  2431 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 12:45:29.860  1523  2431 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-26 12:45:29.889  3509  3509 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-26 12:45:29.891  3509  3509 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-26 12:45:29.893  3509  3509 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-26 12:45:30.521  3778  3778 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-26 12:45:30.527  3778  3778 D AndroidRuntime: CheckJNI is OFF
08-26 12:45:30.570  3778  3778 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-26 12:45:30.620  3778  3778 I Radio-JNI: register_android_hardware_Radio DONE
08-26 12:45:30.644  3778  3778 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-26 12:45:30.648   872   882 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-26 12:45:30.669  3778  3778 D AndroidRuntime: Shutting down VM
08-26 12:45:30.678  2051  2062 W SearchService: Abort, client detached.
08-26 12:45:30.690  2051  2338 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@db960b6
08-26 12:45:30.690  2051  2353 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-26 12:45:30.690  2051  2051 I HotwordDetector: Closing mic
08-26 12:45:30.709   872  1875 I ActivityManager: Start proc 3787:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-26 12:45:30.737   373  2355 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-26 12:45:30.738   373  2355 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-26 12:45:30.743   373  1285 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-26 12:45:30.746  2051  2345 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-26 12:45:30.746  2051  2352 I MicroRecognitionRnrImpl: Detection finished
08-26 12:45:30.793  3787  3787 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-26 12:45:30.820  3787  3787 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-26 12:45:30.840  3787  3787 I LibraryLoader: Time to load native libraries: 7 ms (timestamps 111-118)
08-26 12:45:30.840  3787  3787 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 12:45:30.862  3787  3787 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {70a29eb}
08-26 12:45:30.863  3787  3787 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 12:45:30.863  3787  3787 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-26 12:45:30.873  3787  3787 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-26 12:45:30.878  3787  3787 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-26 12:45:30.922  3787  3787 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-26 12:45:30.938  3787  3787 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-26 12:45:30.938  3787  3787 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-26 12:45:30.938  3787  3787 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-26 12:45:30.938  3787  3787 I Adreno  : Build Date                       : 10/20/15
08-26 12:45:30.938  3787  3787 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 12:45:30.938  3787  3787 I Adreno  : Local Branch                     : M14
08-26 12:45:30.938  3787  3787 I Adreno  : Remote Branch                    : 
08-26 12:45:30.938  3787  3787 I Adreno  : Remote Branch                    : 
08-26 12:45:30.938  3787  3787 I Adreno  : Reconstruct Branch               : 
,08-26 12:45:31.014   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@641ee39:true
,08-26 12:45:31.093  3787  3787 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-26 12:45:31.113  3787  3787 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-26 12:45:31.188  3787  3826 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-26 12:45:31.196  3787  3813 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-26 12:45:31.240  3787  3826 I OpenGLRenderer: Initialized EGL, version 1.4
,08-26 12:45:31.308   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +622ms
,08-26 12:45:31.317  1901  1901 I Keyboard.Facilitator: onFinishInput()
,08-26 12:45:31.394  3787  3787 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3787
,08-26 12:45:31.488  3787  3787 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-26 12:45:31.546   872  2796 I ActivityManager: Killing 3223:com.google.android.gm/u0a78 (adj 15): empty #17
,08-26 12:45:31.594   872  2796 I ActivityManager: Killing 3115:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,08-26 12:45:31.698  3787  3828 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1698694864
,08-26 12:45:31.706  3787  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-26 12:45:31.706  3787  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 12:45:31.706  3787  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 12:45:31.706  3787  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 12:45:31.706  3787  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-26 12:45:31.707  3787  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c39de7f added. We now have 1 listener(s)
08-26 12:45:31.710  3787  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-26 12:45:31.712  3787  3828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 12:45:31.713  3787  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 12:45:31.713  3787  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 12:45:31.716  3787  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-26 12:45:31.716  3787  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 12:45:31.716  3787  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 12:45:31.716  3787  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-26 12:45:31.716  3787  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 12:45:31.716  3787  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 12:45:31.716  3787  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 12:45:31.716  3787  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 12:45:31.716  3787  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 12:45:31.716  3787  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 12:45:31.716  3787  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 12:45:31.716  3787  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 12:45:31.716  3787  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-26 12:45:31.716  3787  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-26 12:45:31.716  3787  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f56bbaa added. We now have 1 listener(s)
08-26 12:45:31.716  3787  3828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 12:45:31.727   872  1314 D WifiService: New client listening to asynchronous messages
08-26 12:45:31.728  3787  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 12:45:31.728  3787  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-26 12:45:31.728  3787  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-26 12:45:31.728  3787  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-26 12:45:31.728  3787  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-26 12:45:31.731  3787  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 12:45:31.731  3787  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-26 12:45:31.738  3787  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-26 12:45:31.739  3787  3828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 12:45:31.739  3787  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:31.739  3787  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:45:31.739  3787  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:45:31.739  3787  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:45:31.739  3787  3828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:45:31.739  3787  3828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:45:31.739  3787  3828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 12:45:31.739  3787  3828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-26 12:45:31.739  3787  3828 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 12:45:31.739  3787  3828 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-26 12:45:31.882  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:45:31.886  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:45:31.888  3787  3787 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-26 12:45:32.388  3787  3837 W jxcore-log: Initializing JXcore engine
,08-26 12:45:32.388  3787  3837 W jxcore-log: JXcore engine is ready
,08-26 12:45:32.424  3837  3837 W Thread-321: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8943 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-26 12:45:32.424  3837  3837 W Thread-321: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11522]" dev="sockfs" ino=11522 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-26 12:45:32.424  3837  3837 W Thread-321: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-26 12:45:32.424  3837  3837 W Thread-321: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24487]" dev="sockfs" ino=24487 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,08-26 12:45:32.439  3787  3837 W jxcore-log: Starting JXcore engine
,08-26 12:45:32.517  3787  3837 W jxcore-log: Platform android
08-26 12:45:32.517  3787  3837 W jxcore-log: 
,08-26 12:45:32.517  3787  3837 W jxcore-log: Process ARCH arm
08-26 12:45:32.517  3787  3837 W jxcore-log: 
,08-26 12:45:32.701  3787  3837 I jxcore-log: JXcore Cordova bridge is ready!
08-26 12:45:32.701  3787  3837 I jxcore-log: 
,08-26 12:45:32.702  3787  3837 W jxcore-log: JXcore engine is started
,08-26 12:45:32.712  3787  3828 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-26 12:45:32.718  3787  3787 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-26 12:45:33.209   872  1313 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-26 12:45:39.476  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 12:45:39.480  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 12:45:39.535  1523  2131 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-26 12:45:39.535  1523  2131 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-26 12:45:39.535  1523  2131 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-26 12:45:39.535  1523  2131 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 12:45:39.572  3550  3845 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-26 12:45:39.572  3550  3845 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-26 12:45:39.572  3550  3845 E HttpOperation: 	at jdm.a(PG:82)
08-26 12:45:39.572  3550  3845 E HttpOperation: 	at jcs.o(PG:406)
08-26 12:45:39.572  3550  3845 E HttpOperation: 	at jcn.a(PG:1379)
08-26 12:45:39.572  3550  3845 E HttpOperation: 	at jcs.i(PG:143)
08-26 12:45:39.572  3550  3845 E HttpOperation: 	at blb.a(PG:3937)
08-26 12:45:39.572  3550  3845 E HttpOperation: 	at czp.a(PG:18188)
08-26 12:45:39.572  3550  3845 E HttpOperation: 	at czp.a(PG:9081)
08-26 12:45:39.572  3550  3845 E HttpOperation: 	at czq.run(PG:1686)
08-26 12:45:39.572  3550  3845 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 12:45:39.572  3550  3845 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 12:45:39.572  3550  3845 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 12:45:39.572  3550  3845 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 12:45:39.572  3550  3845 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-26 12:45:39.572  3550  3845 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-26 12:45:39.572  3550  3845 E HttpOperation: 	at jdj.a(PG:4091)
08-26 12:45:39.572  3550  3845 E HttpOperation: 	at jdj.a(PG:1125)
08-26 12:45:39.572  3550  3845 E HttpOperation: 	at jdm.a(PG:77)
08-26 12:45:39.572  3550  3845 E HttpOperation: 	... 12 more
08-26 12:45:39.572  3550  3845 E HttpOperation: Caused by: faj: BadAuthentication
08-26 12:45:39.572  3550  3845 E HttpOperation: 	at fal.a(PG:38)
08-26 12:45:39.572  3550  3845 E HttpOperation: 	at jdj.a(PG:4089)
08-26 12:45:39.572  3550  3845 E HttpOperation: 	... 14 more
,08-26 12:45:39.666  1523  2431 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-26 12:45:39.666  1523  2431 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-26 12:45:39.667  1523  2431 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 12:45:39.667  1523  2431 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 12:45:39.706  3550  3845 E HttpOperation: [getmobileexperiments] Unexpected exception
08-26 12:45:39.706  3550  3845 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-26 12:45:39.706  3550  3845 E HttpOperation: 	at jdm.a(PG:82)
08-26 12:45:39.706  3550  3845 E HttpOperation: 	at jcs.o(PG:406)
08-26 12:45:39.706  3550  3845 E HttpOperation: 	at jcn.a(PG:1379)
08-26 12:45:39.706  3550  3845 E HttpOperation: 	at jcs.i(PG:143)
08-26 12:45:39.706  3550  3845 E HttpOperation: 	at hec.a(PG:42)
08-26 12:45:39.706  3550  3845 E HttpOperation: 	at hee.a(PG:102)
08-26 12:45:39.706  3550  3845 E HttpOperation: 	at czr.a(PG:65)
08-26 12:45:39.706  3550  3845 E HttpOperation: 	at kka.a(PG:108)
08-26 12:45:39.706  3550  3845 E HttpOperation: 	at czp.a(PG:19176)
08-26 12:45:39.706  3550  3845 E HttpOperation: 	at czp.a(PG:9081)
08-26 12:45:39.706  3550  3845 E HttpOperation: 	at czq.run(PG:1686)
08-26 12:45:39.706  3550  3845 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 12:45:39.706  3550  3845 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 12:45:39.706  3550  3845 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 12:45:39.706  3550  3845 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 12:45:39.706  3550  3845 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-26 12:45:39.706  3550  3845 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-26 12:45:39.706  3550  3845 E HttpOperation: 	at jdj.a(PG:4091)
08-26 12:45:39.706  3550  3845 E HttpOperation: 	at jdj.a(PG:1125)
08-26 12:45:39.706  3550  3845 E HttpOperation: 	at jdm.a(PG:77)
08-26 12:45:39.706  3550  3845 E HttpOperation: 	... 15 more
08-26 12:45:39.706  3550  3845 E HttpOperation: Caused by: faj: BadAuthentication
08-26 12:45:39.706  3550  3845 E HttpOperation: 	at fal.a(PG:38)
08-26 12:45:39.706  3550  3845 E HttpOperation: 	at jdj.a(PG:4089)
08-26 12:45:39.706  3550  3845 E HttpOperation: 	... 17 more
,08-26 12:45:39.707  3550  3845 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-26 12:45:39.707  3550  3845 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-26 12:45:39.707  3550  3845 E ExperimentLoader: 	at jdm.a(PG:82)
08-26 12:45:39.707  3550  3845 E ExperimentLoader: 	at jcs.o(PG:406)
08-26 12:45:39.707  3550  3845 E ExperimentLoader: 	at jcn.a(PG:1379)
08-26 12:45:39.707  3550  3845 E ExperimentLoader: 	at jcs.i(PG:143)
08-26 12:45:39.707  3550  3845 E ExperimentLoader: 	at hec.a(PG:42)
08-26 12:45:39.707  3550  3845 E ExperimentLoader: 	at hee.a(PG:102)
08-26 12:45:39.707  3550  3845 E ExperimentLoader: 	at czr.a(PG:65)
08-26 12:45:39.707  3550  3845 E ExperimentLoader: 	at kka.a(PG:108)
08-26 12:45:39.707  3550  3845 E ExperimentLoader: 	at czp.a(PG:19176)
08-26 12:45:39.707  3550  3845 E ExperimentLoader: 	at czp.a(PG:9081)
08-26 12:45:39.707  3550  3845 E ExperimentLoader: 	at czq.run(PG:1686)
08-26 12:45:39.707  3550  3845 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 12:45:39.707  3550  3845 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 12:45:39.707  3550  3845 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 12:45:39.707  3550  3845 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 12:45:39.707  3550  3845 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-26 12:45:39.707  3550  3845 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-26 12:45:39.707  3550  3845 E ExperimentLoader: 	at jdj.a(PG:4091)
08-26 12:45:39.707  3550  3845 E ExperimentLoader: 	at jdj.a(PG:1125)
08-26 12:45:39.707  3550  3845 E ExperimentLoader: 	at jdm.a(PG:77)
08-26 12:45:39.707  3550  3845 E ExperimentLoader: 	... 15 more
08-26 12:45:39.707  3550  3845 E ExperimentLoader: Caused by: faj: BadAuthentication
08-26 12:45:39.707  3550  3845 E ExperimentLoader: 	at fal.a(PG:38)
08-26 12:45:39.707  3550  3845 E ExperimentLoader: 	at jdj.a(PG:4089)
08-26 12:45:39.707  3550  3845 E ExperimentLoader: 	... 17 more
,08-26 12:45:39.865   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 128487, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-26 12:45:42.612  3787  3837 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-26 12:45:42.612  3787  3837 I jxcore-log: 
,08-26 12:45:42.615  3787  3837 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-26 12:45:42.615  3787  3837 I jxcore-log: 
,08-26 12:45:42.626  3787  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 12:45:42.626  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:42.626  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:45:42.626  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:45:42.626  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:45:42.626  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:45:42.626  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:45:42.626  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 12:45:42.632  3787  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 12:45:42.634  3787  3837 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-26 12:45:42.634  3787  3837 I jxcore-log: 
,08-26 12:45:42.636  3787  3837 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-26 12:45:42.636  3787  3837 I jxcore-log: 
,08-26 12:45:43.132  3787  3837 D executeNativeTests: Running unit tests
,08-26 12:45:43.190  3787  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 12:45:43.190  3787  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@921978f added. We now have 2 listener(s)
,08-26 12:45:43.191  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 12:45:43.191  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 12:45:43.191  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 12:45:43.192  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 12:45:43.192  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c added. We now have 2 listener(s)
08-26 12:45:43.192  3787  3837 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 12:45:43.192  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 12:45:43.197  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 12:45:43.216  3787  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 12:45:43.216  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:43.216  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:45:43.216  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:45:43.216  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:45:43.216  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:45:43.216  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:45:43.216  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 12:45:43.220  3787  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 12:45:43.220  3787  3837 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 12:45:43.223  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-26 12:45:43.225  3787  3837 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 12:45:43.225  3787  3837 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 12:45:43.227  3787  3837 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-26 12:45:43.227  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:43.227  3787  3837 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 12:45:43.227  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 12:45:43.228  3787  3837 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 12:45:43.228  3787  3837 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-26 12:45:43.228  3787  3837 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:45:43.229  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:45:43.229  3787  3837 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:45:43.229  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:43.229  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.229  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 12:45:43.229  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 12:45:43.229  3787  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@921978f removed from the list
,08-26 12:45:43.229  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:43.229  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c removed from the list
,08-26 12:45:43.237  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:45:43.238  3787  3837 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 12:45:43.238  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 12:45:43.239  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.239  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.240  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 12:45:43.240  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:45:43.240  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:43.240  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
08-26 12:45:43.242  3787  3837 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-26 12:45:43.243  3787  3837 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 12:45:43.243  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:45:43.243  3787  3837 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:45:43.243  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:43.243  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.244  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 12:45:43.244  3787  3837 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@921978f not in the list
08-26 12:45:43.244  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:43.244  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
08-26 12:45:43.244  3787  3837 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:43.244  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.244  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.244  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.244  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 12:45:43.246  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:45:43.246  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:45:43.246  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:43.246  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
,08-26 12:45:43.252  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 12:45:43.252  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 12:45:43.252  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 12:45:43.252  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-26 12:45:43.252  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 12:45:43.252  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 12:45:43.252  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 12:45:43.253  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-26 12:45:43.253  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 12:45:43.253  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-26 12:45:43.253  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 12:45:43.253  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 12:45:43.253  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 12:45:43.253  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 12:45:43.253  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 12:45:43.253  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-26 12:45:43.253  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 12:45:43.253  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 12:45:43.253  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-26 12:45:43.253  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 12:45:43.253  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 12:45:43.253  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 12:45:43.254  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 12:45:43.254  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 12:45:43.254  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 12:45:43.254  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 12:45:43.254  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-26 12:45:43.254  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 12:45:43.254  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 12:45:43.254  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 12:45:43.254  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 12:45:43.254  3787  3837 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:45:43.254  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:45:43.254  3787  3837 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:45:43.254  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 12:45:43.254  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.255  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.255  3787  3837 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@921978f not in the list
08-26 12:45:43.255  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:43.255  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
08-26 12:45:43.255  3787  3837 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:43.255  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.255  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.255  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.255  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.257  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:45:43.257  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 12:45:43.257  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:43.257  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
08-26 12:45:43.258  3787  3837 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 12:45:43.261  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 12:45:43.268  3787  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 12:45:43.268  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:43.268  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:45:43.268  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:45:43.268  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:45:43.268  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:45:43.268  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:45:43.268  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 12:45:43.271  3787  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 12:45:43.271  3787  3837 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 12:45:43.272  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 12:45:43.272  3787  3837 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 12:45:43.272  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-26 12:45:43.272  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 12:45:43.272  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 12:45:43.275  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:45:43.280  3787  3837 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-26 12:45:43.280  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 12:45:43.280  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:45:43.287  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 12:45:43.289  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-26 12:45:43.289  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 12:45:43.293  3787  3837 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-26 12:45:43.296  3787  3837 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-26 12:45:43.297  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 12:45:43.297  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 12:45:43.298  3787  3837 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 12:45:43.298  3787  3837 D BluetoothAdapter: STATE_ON
,08-26 12:45:43.304  2684  2695 D BtGatt.GattService: registerClient() - UUID=74c78c5c-82ab-42fd-8f88-6e7ac1f44be1
,08-26 12:45:43.306  2684  2704 D BtGatt.GattService: onClientRegistered() - UUID=74c78c5c-82ab-42fd-8f88-6e7ac1f44be1, clientIf=5
,08-26 12:45:43.306  3787  3799 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-26 12:45:43.307  2684  2696 D BtGatt.GattService: start scan with filters
,08-26 12:45:43.312  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 12:45:43.312  2684  2710 D BtGatt.ScanManager: handling starting scan
,08-26 12:45:43.313  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 12:45:43.313  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 12:45:43.313  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 12:45:43.315  2684  2710 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@634bf1d
08-26 12:45:43.316  3787  3837 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 12:45:43.317  3787  3837 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 12:45:43.318  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 12:45:43.318  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 12:45:43.322  3787  3837 I io.jxcore.node.ConnectionHelper: start: OK
08-26 12:45:43.323  2684  2704 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-26 12:45:43.323  2684  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 12:45:43.324  2684  2710 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-26 12:45:43.325  3787  3837 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:45:43.325  3787  3837 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 12:45:43.325  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 12:45:43.325  3787  3837 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 12:45:43.325  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 12:45:43.325  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 12:45:43.325  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 12:45:43.325  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 12:45:43.325  3787  3837 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 12:45:43.325  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 12:45:43.326  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 12:45:43.326  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 12:45:43.327  3787  3837 D BluetoothAdapter: STATE_ON
08-26 12:45:43.327  2684  2816 D BtGatt.GattService: stopScan() - queue size =1
,08-26 12:45:43.329  2684  2696 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-26 12:45:43.329  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 12:45:43.329  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
08-26 12:45:43.329  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-26 12:45:43.329  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-26 12:45:43.329  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 12:45:43.330  3787  3837 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 12:45:43.331  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 12:45:43.331  3787  3837 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 12:45:43.331  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 12:45:43.332  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 12:45:43.332  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 12:45:43.332  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 12:45:43.332  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 12:45:43.333  2684  2704 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-26 12:45:43.333  2684  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 12:45:43.333  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:43.333  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 12:45:43.333  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 12:45:43.333  3787  3837 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@921978f not in the list
,08-26 12:45:43.333  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 12:45:43.333  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
08-26 12:45:43.333  3787  3837 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 12:45:43.333  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.333  2684  2710 D BtGatt.ScanManager: Starting BLE batch scan
08-26 12:45:43.333  2684  2710 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 12:45:43.334  3787  3837 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-26 12:45:43.336  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 12:45:43.342  3787  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 12:45:43.342  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:43.342  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:45:43.342  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:45:43.342  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:45:43.342  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:45:43.342  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:45:43.342  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 12:45:43.343  3787  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 12:45:43.344  3787  3837 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 12:45:43.345  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
08-26 12:45:43.345  3787  3837 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 12:45:43.345  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 12:45:43.345  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 12:45:43.345  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 12:45:43.345  2684  2704 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 12:45:43.345  2684  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:45:43.349  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:43.351  3787  3837 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 12:45:43.351  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 12:45:43.353  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:45:43.355  2684  2704 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-26 12:45:43.355  2684  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:45:43.355  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 12:45:43.356  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 12:45:43.356  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 12:45:43.359  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 12:45:43.359  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 12:45:43.359  3787  3837 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 12:45:43.361  3787  3837 D BluetoothAdapter: STATE_ON
,08-26 12:45:43.369  2684  2704 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-26 12:45:43.369  2684  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:45:43.369  2684  2710 D BtGatt.ScanManager: stopping BLe Batch
,08-26 12:45:43.376  2684  2816 D BtGatt.GattService: registerClient() - UUID=bb8f821e-9711-4605-8eb3-5ede9f3e8b60
,08-26 12:45:43.376  2684  2704 D BtGatt.GattService: onClientRegistered() - UUID=bb8f821e-9711-4605-8eb3-5ede9f3e8b60, clientIf=5
08-26 12:45:43.377  3787  3798 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5,
08-26 12:45:43.378  2684  2696 D BtGatt.GattService: start scan with filters
,08-26 12:45:43.380  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 12:45:43.381  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 12:45:43.381  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 12:45:43.381  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 12:45:43.386  3787  3837 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 12:45:43.386  3787  3837 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 12:45:43.386  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 12:45:43.387  2684  2704 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 12:45:43.387  2684  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:45:43.387  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 12:45:43.387  2684  2710 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 12:45:43.389  3787  3837 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 12:45:43.392  3787  3837 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:45:43.392  3787  3837 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 12:45:43.392  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 12:45:43.392  3787  3837 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 12:45:43.392  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.392  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 12:45:43.392  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 12:45:43.392  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 12:45:43.392  3787  3837 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 12:45:43.392  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 12:45:43.393  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 12:45:43.393  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 12:45:43.393  3787  3837 D BluetoothAdapter: STATE_ON
08-26 12:45:43.395  2684  2816 D BtGatt.GattService: stopScan() - queue size =0
,08-26 12:45:43.395  2684  2695 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 12:45:43.396  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 12:45:43.396  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 12:45:43.396  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-26 12:45:43.396  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 12:45:43.396  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 12:45:43.396  3787  3837 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 12:45:43.397  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 12:45:43.397  3787  3837 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 12:45:43.397  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 12:45:43.397  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 12:45:43.398  2684  2704 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 12:45:43.398  2684  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 12:45:43.399  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 12:45:43.399  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 12:45:43.399  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 12:45:43.399  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:43.399  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.399  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 12:45:43.399  3787  3837 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@921978f not in the list
08-26 12:45:43.399  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:43.399  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
08-26 12:45:43.400  3787  3837 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:43.400  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.400  2684  2710 D BtGatt.ScanManager: handling starting scan
08-26 12:45:43.400  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.400  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.401  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 12:45:43.401  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:45:43.401  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:43.401  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
08-26 12:45:43.401  3787  3837 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 12:45:43.403  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 12:45:43.406  2684  2704 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-26 12:45:43.406  2684  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:45:43.406  2684  2710 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 12:45:43.409  3787  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 12:45:43.409  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:43.409  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:45:43.409  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:45:43.409  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:45:43.409  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:45:43.409  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:45:43.409  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 12:45:43.411  3787  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 12:45:43.411  3787  3837 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 12:45:43.411  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 12:45:43.411  3787  3837 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-26 12:45:43.411  2684  2704 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 12:45:43.411  2684  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:45:43.411  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 12:45:43.411  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 12:45:43.412  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 12:45:43.412  2684  2710 D BtGatt.ScanManager: Starting BLE batch scan
08-26 12:45:43.412  2684  2710 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 12:45:43.415  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:45:43.417  3787  3837 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-26 12:45:43.417  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 12:45:43.418  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:45:43.422  2684  2704 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-26 12:45:43.422  2684  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:45:43.422  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 12:45:43.423  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 12:45:43.423  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 12:45:43.427  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 12:45:43.427  2684  2704 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 12:45:43.427  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 12:45:43.427  2684  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:45:43.427  3787  3837 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 12:45:43.428  3787  3837 D BluetoothAdapter: STATE_ON
,08-26 12:45:43.430  2684  2816 D BtGatt.GattService: registerClient() - UUID=bd926a30-a2c8-4205-bcf9-ccdc6c4a7bc6
,08-26 12:45:43.430  2684  2704 D BtGatt.GattService: onClientRegistered() - UUID=bd926a30-a2c8-4205-bcf9-ccdc6c4a7bc6, clientIf=5
,08-26 12:45:43.431  3787  3799 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 12:45:43.431  2684  2696 D BtGatt.GattService: start scan with filters
,08-26 12:45:43.433  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 12:45:43.433  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 12:45:43.433  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 12:45:43.433  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 12:45:43.434  2684  2704 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-26 12:45:43.434  2684  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:45:43.434  2684  2710 D BtGatt.ScanManager: stopping BLe Batch
,08-26 12:45:43.435  3787  3837 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 12:45:43.435  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 12:45:43.435  3787  3837 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 12:45:43.436  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 12:45:43.438  3787  3837 I io.jxcore.node.ConnectionHelper: start: OK
08-26 12:45:43.438  3787  3837 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:45:43.438  3787  3837 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 12:45:43.438  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 12:45:43.438  3787  3837 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-26 12:45:43.438  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.438  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 12:45:43.438  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 12:45:43.438  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 12:45:43.438  3787  3837 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 12:45:43.438  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 12:45:43.438  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 12:45:43.438  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 12:45:43.439  3787  3837 D BluetoothAdapter: STATE_ON
08-26 12:45:43.439  2684  2695 D BtGatt.GattService: stopScan() - queue size =0
08-26 12:45:43.440  2684  2704 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 12:45:43.440  2684  2816 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 12:45:43.440  2684  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:45:43.440  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 12:45:43.440  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-26 12:45:43.440  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 12:45:43.440  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 12:45:43.440  2684  2710 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-26 12:45:43.440  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 12:45:43.441  3787  3837 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 12:45:43.441  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 12:45:43.441  3787  3837 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 12:45:43.441  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 12:45:43.442  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 12:45:43.442  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 12:45:43.442  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 12:45:43.442  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 12:45:43.443  3787  3837 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:45:43.443  3787  3837 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 12:45:43.443  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 12:45:43.443  3787  3837 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:45:43.443  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:43.443  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.443  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 12:45:43.443  3787  3837 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@921978f not in the list
,08-26 12:45:43.443  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:43.443  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
08-26 12:45:43.443  3787  3837 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:43.443  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.444  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.444  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 12:45:43.444  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:45:43.445  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 12:45:43.445  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:43.445  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
08-26 12:45:43.445  3787  3837 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-26 12:45:43.445  2684  2704 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 12:45:43.445  3787  3837 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:45:43.445  2684  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 12:45:43.445  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:45:43.446  3787  3837 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:45:43.446  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:43.446  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.446  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.446  3787  3837 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@921978f not in the list
08-26 12:45:43.446  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:43.446  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
,08-26 12:45:43.446  3787  3837 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:43.446  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.446  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.446  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.446  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.447  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:45:43.447  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 12:45:43.447  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:43.447  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
08-26 12:45:43.447  2684  2710 D BtGatt.ScanManager: handling starting scan
08-26 12:45:43.448  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 12:45:43.448  3787  3837 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:45:43.448  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 12:45:43.448  3787  3837 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:45:43.448  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:43.448  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.448  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.448  3787  3837 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@921978f not in the list
08-26 12:45:43.448  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 12:45:43.448  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
08-26 12:45:43.448  3787  3837 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:43.448  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.448  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.449  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.449  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 12:45:43.449  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:45:43.449  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:45:43.449  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:43.449  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
08-26 12:45:43.450  3787  3837 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-26 12:45:43.450  3787  3837 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 12:45:43.450  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:45:43.450  3787  3837 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:45:43.450  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:43.450  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.450  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.450  3787  3837 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@921978f not in the list
08-26 12:45:43.450  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:43.450  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
,08-26 12:45:43.450  3787  3837 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:43.450  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.450  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.451  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.451  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.451  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:45:43.451  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:45:43.451  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:43.451  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
,08-26 12:45:43.452  3787  3837 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-26 12:45:43.452  3787  3837 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:45:43.452  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:45:43.452  3787  3837 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:45:43.452  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 12:45:43.452  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.452  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.452  3787  3837 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@921978f not in the list
08-26 12:45:43.452  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:43.452  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
,08-26 12:45:43.452  3787  3837 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:43.452  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.452  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.452  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.453  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.453  2684  2704 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-26 12:45:43.453  2684  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:45:43.453  2684  2710 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-26 12:45:43.453  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 12:45:43.453  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:45:43.454  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:43.454  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
08-26 12:45:43.454  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-26 12:45:43.455  3787  3837 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 12:45:43.455  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 12:45:43.456  3787  3837 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 12:45:43.456  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 12:45:43.457  3787  3837 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 12:45:43.457  3787  3837 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:45:43.457  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:45:43.457  3787  3837 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:45:43.457  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 12:45:43.457  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.457  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.458  3787  3837 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@921978f not in the list
08-26 12:45:43.458  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:43.458  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
08-26 12:45:43.458  3787  3837 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:43.458  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.458  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.459  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.459  2684  2704 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-26 12:45:43.459  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.459  2684  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:45:43.460  2684  2710 D BtGatt.ScanManager: Starting BLE batch scan
08-26 12:45:43.460  2684  2710 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 12:45:43.461  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:45:43.461  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:45:43.461  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 12:45:43.461  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
08-26 12:45:43.462  3787  3837 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 12:45:43.462  3787  3837 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 12:45:43.463  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-26 12:45:43.468  3787  3837 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-26 12:45:43.468  3787  3837 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-26 12:45:43.468  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-26 12:45:43.468  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 12:45:43.468  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-26 12:45:43.468  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 12:45:43.469  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-26 12:45:43.469  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 12:45:43.469  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-26 12:45:43.469  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 12:45:43.469  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-26 12:45:43.469  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 12:45:43.469  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 12:45:43.469  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 12:45:43.469  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 12:45:43.469  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 12:45:43.469  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-26 12:45:43.469  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 12:45:43.470  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 12:45:43.470  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-26 12:45:43.470  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 12:45:43.470  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-26 12:45:43.470  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 12:45:43.470  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 12:45:43.470  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-26 12:45:43.470  2684  2704 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 12:45:43.471  2684  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:45:43.470  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 12:45:43.471  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-26 12:45:43.471  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 12:45:43.471  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-26 12:45:43.471  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 12:45:43.471  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-26 12:45:43.471  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-26 12:45:43.471  3787  3837 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,08-26 12:45:43.472  3787  3837 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-26 12:45:43.472  3787  3837 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-26 12:45:43.472  3787  3837 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 12:45:43.472  3787  3837 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 12:45:43.472  3787  3837 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-26 12:45:43.472  3787  3837 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 12:45:43.472  3787  3837 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 12:45:43.472  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-26 12:45:43.476  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-26 12:45:43.476  2684  2704 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 12:45:43.476  2684  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:45:43.477  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-26 12:45:43.477  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-26 12:45:43.477  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-26 12:45:43.477  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-26 12:45:43.477  3787  3837 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,08-26 12:45:43.478  3787  3837 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 12:45:43.478  3787  3837 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-26 12:45:43.478  3787  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 385)
08-26 12:45:43.479  3787  3837 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:45:43.479  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:45:43.479  3787  3837 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:45:43.479  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:43.479  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.479  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 12:45:43.479  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-26 12:45:43.479  3787  3850 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 12:45:43.480  3787  3837 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@921978f not in the list
,08-26 12:45:43.480  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:43.480  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
08-26 12:45:43.480  3787  3837 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:43.480  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 12:45:43.480  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.480  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.480  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.481  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:45:43.481  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:45:43.482  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:43.482  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
,08-26 12:45:43.482  3787  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 385
08-26 12:45:43.482  3787  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 385)
08-26 12:45:43.482  2684  2704 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 12:45:43.482  2684  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:45:43.482  3787  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 385)
08-26 12:45:43.482  2684  2813 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
08-26 12:45:43.483  2684  2710 D BtGatt.ScanManager: stopping BLe Batch
08-26 12:45:43.483  3787  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 385)
08-26 12:45:43.483  3787  3837 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-26 12:45:43.483  3787  3837 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:45:43.483  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:45:43.484  3787  3837 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:45:43.484  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:43.484  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.484  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 12:45:43.484  3787  3837 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@921978f not in the list
08-26 12:45:43.484  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:43.484  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
08-26 12:45:43.484  3787  3837 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:43.484  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 12:45:43.484  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.484  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.484  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.485  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:45:43.485  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:45:43.485  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:43.485  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
08-26 12:45:43.486  3787  3837 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-26 12:45:43.486  3787  3837 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:45:43.486  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:45:43.486  3787  3837 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:45:43.486  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:43.486  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.486  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.486  3787  3837 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@921978f not in the list
08-26 12:45:43.486  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:43.486  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
08-26 12:45:43.486  3787  3837 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:43.486  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.486  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.486  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.487  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.487  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:45:43.487  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:45:43.487  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:43.487  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
08-26 12:45:43.488  3787  3837 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-26 12:45:43.488  3787  3837 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer, with ID randomString
08-26 12:45:43.488  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 12:45:43.488  3787  3837 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-26 12:45:43.488  3787  3837 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 12:45:43.488  3787  3837 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-26 12:45:43.488  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 12:45:43.488  3787  3837 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-26 12:45:43.488  3787  3837 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 12:45:43.488  3787  3837 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 12:45:43.488  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 12:45:43.488  3787  3837 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-26 12:45:43.488  3787  3837 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:45:43.489  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:45:43.489  3787  3837 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:45:43.489  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:43.489  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.489  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.489  3787  3837 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@921978f not in the list
08-26 12:45:43.489  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:43.489  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
08-26 12:45:43.489  3787  3837 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:43.489  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.489  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.489  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.489  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.490  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:45:43.490  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:45:43.490  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:43.490  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
08-26 12:45:43.490  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:43.490  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.490  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.491  3787  3837 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@921978f not in the list
08-26 12:45:43.491  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:43.491  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
08-26 12:45:43.491  3787  3837 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:43.491  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.491  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.491  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:43.491  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
08-26 12:45:43.491  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:43.491  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.491  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.491  3787  3837 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@921978f not in the list
08-26 12:45:43.491  3787  3837 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:45:43.491  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:45:43.491  3787  3837 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:45:43.492  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:43.492  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.492  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.492  3787  3837 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@921978f not in the list
08-26 12:45:43.492  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:43.492  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
08-26 12:45:43.492  3787  3837 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:43.492  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.492  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.492  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.492  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.493  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:45:43.493  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:45:43.493  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:43.493  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
08-26 12:45:43.493  2684  2704 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 12:45:43.493  2684  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:45:43.493  2684  2710 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-26 12:45:43.494  3787  3837 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-26 12:45:43.494  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 12:45:43.495  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-26 12:45:43.495  3787  3837 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-26 12:45:43.495  3787  3837 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-26 12:45:43.496  3787  3787 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-26 12:45:43.496  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-26 12:45:43.496  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 12:45:43.498  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:43.498  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-26 12:45:43.498  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-26 12:45:43.498  2684  2704 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 12:45:43.499  2684  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:45:43.498  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-26 12:45:43.499  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.499  3787  3837 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-26 12:45:43.500  3787  3787 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-26 12:45:43.500  3787  3837 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@921978f not in the list
08-26 12:45:43.500  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:43.500  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 12:45:43.500  3787  3852 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 12:45:43.500  3787  3837 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 12:45:43.500  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 12:45:43.500  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.500  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.502  3787  3852 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-26 12:45:43.502  3787  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-26 12:45:43.502  3787  3837 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 12:45:43.502  3787  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-26 12:45:43.502  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 12:45:43.502  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
08-26 12:45:43.502  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 12:45:43.502  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 12:45:43.502  3787  3837 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:45:43.502  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:45:43.502  3787  3787 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-26 12:45:43.502  3787  3837 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:45:43.503  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:43.503  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.503  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.503  3787  3837 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@921978f not in the list
08-26 12:45:43.503  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:43.503  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
08-26 12:45:43.503  3787  3837 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:43.503  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.503  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.504  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.504  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.505  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:45:43.505  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:45:43.505  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:43.506  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
08-26 12:45:43.507  3787  3837 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-26 12:45:43.508  3787  3837 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 12:45:43.508  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 12:45:43.508  3787  3837 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 12:45:43.508  3787  3837 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:45:43.508  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:45:43.509  3787  3837 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:45:43.509  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:43.509  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.509  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.509  3787  3837 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@921978f not in the list
08-26 12:45:43.509  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:43.509  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
08-26 12:45:43.509  3787  3837 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:43.509  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.509  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.509  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.509  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.510  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:45:43.510  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:45:43.510  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:43.511  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
08-26 12:45:43.517  3787  3837 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:45:43.517  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:45:43.517  3787  3837 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:45:43.517  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:43.517  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.517  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.517  3787  3837 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@921978f not in the list
08-26 12:45:43.517  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:43.517  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
08-26 12:45:43.517  3787  3837 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:43.517  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.517  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.518  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.518  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.519  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:45:43.519  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:45:43.519  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:43.519  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
08-26 12:45:43.519  3787  3837 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:45:43.519  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:45:43.519  3787  3837 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:45:43.520  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:43.520  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.520  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.520  3787  3837 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@921978f not in the list
08-26 12:45:43.520  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:43.520  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
08-26 12:45:43.520  3787  3837 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:43.520  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.520  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.520  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:43.520  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:43.521  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:45:43.521  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:45:43.521  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:43.521  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7154a1c not in the list
08-26 12:45:43.522  3787  3837 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-26 12:45:43.522  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 12:45:43.522  3787  3837 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-26 12:45:43.522  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 12:45:43.522  3787  3837 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-26 12:45:43.522  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 12:45:43.524  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 12:45:43.524  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-26 12:45:43.524  3787  3837 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-26 12:45:43.524  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 12:45:43.524  3787  3837 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-26 12:45:43.524  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 12:45:43.524  3787  3837 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-26 12:45:43.525  3787  3837 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-26 12:45:43.525  3787  3837 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-26 12:45:43.525  3787  3837 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-26 12:45:43.525  3787  3837 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-26 12:45:43.525  3787  3837 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-26 12:45:43.525  3787  3837 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-26 12:45:43.526  3787  3837 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-26 12:45:43.526  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 12:45:43.526  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6edb79e added. We now have 2 listener(s)
08-26 12:45:43.526  3787  3837 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 12:45:43.528  3787  3837 D BluetoothAdapter: enable(): BT is already enabled..!
08-26 12:45:43.529   872   883 D WifiService: setWifiEnabled: true pid=3787, uid=10000
08-26 12:45:43.529   872   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 12:45:43.530  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 12:45:43.530  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@35d827f added. We now have 3 listener(s)
,08-26 12:45:43.530  3787  3837 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 12:45:43.536  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 12:45:43.536  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9cd724c added. We now have 4 listener(s)
08-26 12:45:43.536  3787  3837 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 12:45:43.537  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 12:45:43.537  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8150295 added. We now have 5 listener(s)
08-26 12:45:43.537  3787  3837 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 12:45:43.542   872  2984 D WifiService: setWifiEnabled: false pid=3787, uid=10000
08-26 12:45:43.542   872  2984 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 12:45:43.551  2684  2699 D BluetoothAdapterState: Current state: ON, message: 23
08-26 12:45:43.551  2684  2699 D BluetoothAdapterProperties: Setting state to 13
08-26 12:45:43.551  2684  2699 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 12:45:43.552  2684  2699 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 12:45:43.552  2684  2699 I BluetoothAdapterState: Entering PendingCommandState
08-26 12:45:43.556  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 12:45:43.561  2684  2684 D BluetoothMapService: onReceive
,08-26 12:45:43.561  2684  2684 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:45:43.562  2684  2684 D BluetoothMapService: STATE_TURNING_OFF
08-26 12:45:43.562  2684  2684 D BluetoothMapService: MAP Service closeService in
,08-26 12:45:43.562  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-26 12:45:43.562  2684  2684 D BluetoothMapMasInstance0: MAP Service shutdown
,08-26 12:45:43.562  2684  2684 D ObexServerSockets0: shutdown(block = true)
,08-26 12:45:43.562  2684  2684 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 12:45:43.563  2684  2684 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 12:45:43.563  2684  2824 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-26 12:45:43.563  2684  2813 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-26 12:45:43.564  2684  2704 D BluetoothAdapterProperties: Scan Mode:20
08-26 12:45:43.564  2684  2699 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-26 12:45:43.564  2684  2825 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-26 12:45:43.565  2684  2684 I BtOppRfcommListener: stopping Accept Thread
08-26 12:45:43.565  2684  3433 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 12:45:43.565  2684  3433 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 12:45:43.568   872  1313 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-26 12:45:43.568   872  1313 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-26 12:45:43.568   872  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-26 12:45:43.568   872  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 12:45:43.571  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 12:45:43.571  3787  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 12:45:43.571  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:43.571  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:45:43.571  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:45:43.571  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:45:43.571  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:45:43.571  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:45:43.571  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 12:45:43.571   872   885 I ActivityManager: Start proc 3855:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-26 12:45:43.572  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 12:45:43.572  3787  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 12:45:43.572  3787  3837 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 12:45:43.574  2684  2684 D HeadsetService: Received stop request...Stopping profile...
,08-26 12:45:43.575  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:43.576   872   872 D BluetoothHeadset: Proxy object disconnected
08-26 12:45:43.576   872   872 D BluetoothHeadset: Proxy object disconnected
08-26 12:45:43.579  1372  2069 D BluetoothHeadset: Proxy object disconnected
08-26 12:45:43.578  2684  2684 D A2dpService: Received stop request...Stopping profile...
08-26 12:45:43.579  2684  2819 D A2dpStateMachine: Exit Disconnected: -1
08-26 12:45:43.579  1972  1991 D BluetoothHeadset: Proxy object disconnected
08-26 12:45:43.580   872   872 D BluetoothHeadset: Proxy object disconnected
08-26 12:45:43.581  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:43.583   369   870 D CommandListener: Clearing all IP addresses on wlan0
08-26 12:45:43.583   872  1898 D DhcpClient: Clearing IP address
08-26 12:45:43.584   872   872 D BluetoothA2dp: Proxy object disconnected
08-26 12:45:43.585  1372  1372 D HeadsetProfile: Bluetooth service disconnected
,08-26 12:45:43.585  2684  2684 V BluetoothAdapterState: isTurningOff()=true
08-26 12:45:43.585  2684  2684 V BluetoothAdapterState: isTurningOn()=false
08-26 12:45:43.585  2684  2684 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:45:43.586  2684  2684 V BluetoothAdapterState: isBleTurningOff()=false
08-26 12:45:43.586  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:43.586  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:45:43.586  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:43.586  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:45:43.586  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:45:43.586  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:45:43.586  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:45:43.586  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:45:43.586  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 12:45:43.586  2684  2684 D HidService: Received stop request...Stopping profile...
08-26 12:45:43.586  2684  2684 D HidService: Stopping Bluetooth HidService
08-26 12:45:43.586  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:43.586   369   870 D CommandListener: Setting iface cfg
08-26 12:45:43.586  3787  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 12:45:43.589  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:43.589  2684  2684 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 12:45:43.590  2684  2704 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-26 12:45:43.590  2684  2684 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 12:45:43.590  2684  2797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 12:45:43.590  2684  2797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 12:45:43.590  2684  2797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 12:45:43.590  2684  2704 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-26 12:45:43.590  2684  2684 D HealthService: Received stop request...Stopping profile...
08-26 12:45:43.591  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:43.592  1523  2197 V NativeCrypto: Read error: ssl=0xaedbdc00: I/O error during system call, Connection timed out
08-26 12:45:43.593  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:43.593  2684  2684 D PanService: Received stop request...Stopping profile...
08-26 12:45:43.594  1523  2197 V NativeCrypto: SSL shutdown failed: ssl=0xaedbdc00: I/O error during system call, Broken pipe
,08-26 12:45:43.595  1372  1372 D BluetoothA2dp: Proxy object disconnected
08-26 12:45:43.595  1372  1372 D BluetoothInputDevice: Proxy object disconnected
08-26 12:45:43.595  1372  1372 D HidProfile: Bluetooth service disconnected
08-26 12:45:43.595  1372  1372 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 12:45:43.595  1372  1372 D PanProfile: Bluetooth service disconnected
08-26 12:45:43.595   872  1913 D DhcpClient: Receive thread stopped
08-26 12:45:43.596   872  1419 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-26 12:45:43.597   872  1892 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-26 12:45:43.597   872  1313 D WifiStateMachine: Start Disconnecting Watchdog 1
08-26 12:45:43.597   872  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-26 12:45:43.598   872  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-26 12:45:43.598   872  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-26 12:45:43.603   398   398 E Parcel  : Reading a NULL string not supported here.
08-26 12:45:43.605   369   870 D CommandListener: Clearing all IP addresses on wlan0
08-26 12:45:43.605  2684  2684 D BluetoothMapService: Received stop request...Stopping profile...
08-26 12:45:43.606  2684  2684 D BluetoothMapService: stop()
08-26 12:45:43.608  2684  2684 D BluetoothMapAppObserver: deinitObservers()
08-26 12:45:43.608  2684  2684 D BluetoothMapAppObserver: removeReceiver()
08-26 12:45:43.610   872  1892 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-26 12:45:43.610   872  1313 D WifiConfigStore: Retrieve network priorities after PNO.
08-26 12:45:43.611   872  1315 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-26 12:45:43.612  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:43.612  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:45:43.612  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:43.612  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:45:43.612  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 12:45:43.612  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:45:43.612  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:45:43.612  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:45:43.612  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 12:45:43.612  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:43.612  3787  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 12:45:43.612   872  1313 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 12:45:43.613  2684  2684 V BluetoothAdapterState: isTurningOff()=true
08-26 12:45:43.613  2684  2684 V BluetoothAdapterState: isTurningOn()=false
08-26 12:45:43.613  2684  2684 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:45:43.614  2684  2684 V BluetoothAdapterState: isBleTurningOff()=false
08-26 12:45:43.614  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:43.614  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:45:43.614  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:43.614  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:45:43.614  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 12:45:43.614  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:45:43.614  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:45:43.614  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:45:43.614  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 12:45:43.614  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:43.614  3787  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 12:45:43.615  2684  2704 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-26 12:45:43.615  2684  2797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-26 12:45:43.615  2684  2797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 12:45:43.615  2684  2797 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 12:45:43.615  2684  2797 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 12:45:43.615  2684  2797 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 12:45:43.615  2684  2797 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 12:45:43.615  2684  2684 V BluetoothAdapterState: isTurningOff()=true
08-26 12:45:43.615  2684  2684 V BluetoothAdapterState: isTurningOn()=false
08-26 12:45:43.615  2684  2684 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:45:43.615  2684  2684 V BluetoothAdapterState: isBleTurningOff()=false
08-26 12:45:43.616  2684  2684 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 12:45:43.616  2684  2684 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 12:45:43.616  2684  2704 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-26 12:45:43.618  2684  2684 V BluetoothAdapterState: isTurningOff()=true
08-26 12:45:43.618  2684  2684 V BluetoothAdapterState: isTurningOn()=false
08-26 12:45:43.618  2684  2684 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:45:43.618  2684  2684 V BluetoothAdapterState: isBleTurningOff()=false
08-26 12:45:43.619  2684  2684 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-26 12:45:43.619  2684  2704 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-26 12:45:43.619  2684  2684 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 12:45:43.619  2684  2684 V BluetoothAdapterState: isTurningOff()=true
08-26 12:45:43.620  2684  2684 V BluetoothAdapterState: isTurningOn()=false
08-26 12:45:43.620  2684  2684 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:45:43.620  2684  2684 V BluetoothAdapterState: isBleTurningOff()=false
08-26 12:45:43.623  2684  2684 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 12:45:43.623  2684  2684 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 12:45:43.628  2684  2684 D BluetoothMapService: MAP Service closeService in
,08-26 12:45:43.628  2684  2684 V BluetoothAdapterState: isTurningOff()=true
08-26 12:45:43.628  2684  2684 V BluetoothAdapterState: isTurningOn()=false
08-26 12:45:43.628  1372  1372 D BluetoothMap: Proxy object disconnected
08-26 12:45:43.629  1372  1372 D MapProfile: Bluetooth service disconnected
08-26 12:45:43.628  2684  2684 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:45:43.629  2684  2684 V BluetoothAdapterState: isBleTurningOff()=false
08-26 12:45:43.629  2684  2699 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-26 12:45:43.629  2684  2699 D BluetoothAdapterProperties: Setting state to 15
08-26 12:45:43.629  2684  2699 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-26 12:45:43.630  1972  1999 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 12:45:43.630  1372  1384 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 12:45:43.630  2684  2699 I BluetoothAdapterState: Entering BleOnState
08-26 12:45:43.630   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 12:45:43.631  1372  2069 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 12:45:43.633  1372  1384 D BluetoothMap: onBluetoothStateChange: up=false
08-26 12:45:43.633  1372  1383 D BluetoothPan: onBluetoothStateChange on: false
08-26 12:45:43.633   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 12:45:43.634  1372  2069 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 12:45:43.634   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 12:45:43.634  1372  1384 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 12:45:43.634   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 12:45:43.635  2684  2699 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-26 12:45:43.635  2684  2699 D BluetoothAdapterProperties: Setting state to 16
08-26 12:45:43.635  2684  2699 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-26 12:45:43.637  2684  2699 D BluetoothAdapterProperties: onBleDisable
08-26 12:45:43.637  2684  2699 I BluetoothAdapterState: Entering PendingCommandState
08-26 12:45:43.637  2684  2700 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-26 12:45:43.638  2684  2797 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-26 12:45:43.638  2684  2797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 12:45:43.638  2684  2704 D BluetoothAdapterProperties: Scan Mode:20
08-26 12:45:43.639  2684  2684 D BluetoothMapService: cleanup()
08-26 12:45:43.639  2684  2684 D BluetoothMapService: MAP Service closeService in
08-26 12:45:43.642  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:43.642  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:45:43.642  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:43.642  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:45:43.642  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 12:45:43.642  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:45:43.642  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:45:43.642  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:45:43.642  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 12:45:43.654  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:43.654  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:45:43.654  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:43.654  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:45:43.654  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 12:45:43.654  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:45:43.654  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:45:43.654  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:45:43.654  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 12:45:43.655  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:43.656  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:43.657   369   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 12:45:43.661   872   881 I art     : Background partial concurrent mark sweep GC freed 46545(2MB) AllocSpace objects, 12(264KB) LOS objects, 33% free, 29MB/44MB, paused 1.059ms total 103.854ms
08-26 12:45:43.661  2152  2316 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:43.675   369   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 12:45:43.676   872  1315 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-26 12:45:43.676   872  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 12:45:43.677   872   889 D Tethering: MasterInitialState.processMessage what=3
08-26 12:45:43.680  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:43.681  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:43.682  3419  3419 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@c39de7f and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-26 12:45:43.686  3855  3855 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-26 12:45:43.696  3855  3855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 12:45:43.701  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 12:45:43.702   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@225c88f:true
,08-26 12:45:43.715   872  1858 I ActivityManager: Start proc 3878:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-26 12:45:43.722   369   870 E Netd    : netlink response contains error (No such file or directory)
,08-26 12:45:43.723   872  1315 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-26 12:45:43.728  3855  3855 D LocalBluetoothProfileManager: Adding local MAP profile
,08-26 12:45:43.730  3855  3855 D BluetoothMap: Create BluetoothMap proxy object
,08-26 12:45:43.738  3855  3855 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-26 12:45:43.748  3878  3878 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-26 12:45:43.755  3855  3855 D DockEventReceiver: finishStartingService: stopping service
,08-26 12:45:43.757   872  1859 I ActivityManager: Killing 2979:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-26 12:45:43.840  2684  2704 I bt_hci  : shut_down
,08-26 12:45:43.850  2684  2711 I bt_vendor: low_power_mode_cb
,08-26 12:45:43.855  2684  2711 D bt_hwcfg: hw_epilog_process
,08-26 12:45:43.870  2684  2711 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-26 12:45:43.871  2684  2711 I bt_vendor: epilog_cb
08-26 12:45:43.871  2684  2711 I bt_hci  : epilog_finished_callback
,08-26 12:45:43.876  2684  2704 I bt_hci_h4: hal_close
,08-26 12:45:43.877  2684  2704 I bt_userial_vendor: device fd = 51 close
,08-26 12:45:43.945  3878  3878 D StrictMode: StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 12:45:43.945  3878  3878 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 12:45:43.945  3878  3878 D StrictMode: StrictMode policy violation; ~duration=88 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 12:45:43.945  3878  3878 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 12:45:43.945  3878  3878 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 12:45:43.954  3878  3878 D StrictMode: StrictMode policy violation; ~duration=88 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 12:45:43.954  3878  3878 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 12:45:43.954  3878  3878 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 12:45:43.954  3878  3878 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-26 12:45:43.954  387,8  3878 D StrictMode: 	at com.google.r.e.b(PG:170)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
,08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 12:45:43.954  3878  3878 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 12:45:43.954  3878  3878 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
,08-26 12:45:43.954  3878  3878 D StrictMode: 	,at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-26 12:45:43.954  3878  3878 D StrictMode: ,	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.google.r.k.d(PG:1187)
,08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.google.r.k.d(PG:583)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.google.r.e.b(PG:170)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 12:45:43.954  3878  3878 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 12:45:43.956  3878  3878 D StrictMode: StrictMode policy violation; ~duration=53 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 12:45:43.956  3878  3878 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2,265)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 12:45:43.956  3878  3878 D StrictMode: StrictMode policy violation; ~duration=53 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 12:45:43.956  3878  3878 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67),
08-26 12:45:43.956  3878  3878 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 12:45:43.956  3878  3878 D StrictMode: StrictMode policy violation; ~duration=52 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 12:45:43.956  3878  3878 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at java.lang.r,eflect.Method.invoke(Native Method)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 12:45:43.956  3878  3878 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 12:45:43.990   872   883 I ActivityManager: Start proc 3907:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-26 12:45:43.996   872   883 I ActivityManager: Killing 3419:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-26 12:45:44.003  3787  3787 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 12:45:44.108  2684  2700 D bt_stack_manager: event_shut_down_stack finished.
,08-26 12:45:44.109  2684  2699 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-26 12:45:44.114  3907  3907 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
08-26 12:45:44.114  2684  2699 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-26 12:45:44.114  2684  2684 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 12:45:44.115  2684  2684 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 12:45:44.116  2684  2684 D BtGatt.GattService: stop()
08-26 12:45:44.116  2684  2684 D BtGatt.AdvertiseManager: advertise clients cleared
,08-26 12:45:44.120  2684  2684 V BluetoothAdapterState: isTurningOff()=false
08-26 12:45:44.120  2684  2684 V BluetoothAdapterState: isTurningOn()=false
08-26 12:45:44.120  2684  2684 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:45:44.121  2684  2684 V BluetoothAdapterState: isBleTurningOff()=true
,08-26 12:45:44.121  2684  2699 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-26 12:45:44.122  2684  2699 D BluetoothAdapterProperties: Setting state to 10
,08-26 12:45:44.122  2684  2699 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-26 12:45:44.123  2684  2699 I BluetoothAdapterState: Entering OffState
,08-26 12:45:44.125   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-26 12:45:44.163  2684  2684 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-26 12:45:44.163  2684  2684 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-26 12:45:44.164  2684  2700 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-26 12:45:44.165  2684  2684 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-26 12:45:44.166  2684  2700 D bt_stack_manager: event_clean_up_stack finished.
,08-26 12:45:44.167  2684  2684 I art     : System.exit called, status: 0
,08-26 12:45:44.167  2684  2684 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 12:45:44.219  3878  3898 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-26 12:45:44.233   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f125438:true
,08-26 12:45:44.239   872   882 I ActivityManager: Process com.android.bluetooth (pid 2684) has died
,08-26 12:45:44.352  3907  3907 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-26 12:45:44.396  3855  3855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 12:45:44.436   872  2984 I ActivityManager: Start proc 3936:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-26 12:45:44.446  3855  3855 D DockEventReceiver: finishStartingService: stopping service
,08-26 12:45:44.511  3936  3936 D AdapterServiceConfig: Adding HeadsetService
,08-26 12:45:44.511  3936  3936 D AdapterServiceConfig: Adding A2dpService
08-26 12:45:44.511  3936  3936 D AdapterServiceConfig: Adding HidService
,08-26 12:45:44.511  3936  3936 D AdapterServiceConfig: Adding HealthService
,08-26 12:45:44.511  3936  3936 D AdapterServiceConfig: Adding PanService
08-26 12:45:44.511  3936  3936 D AdapterServiceConfig: Adding GattService
,08-26 12:45:44.511  3936  3936 D AdapterServiceConfig: Adding BluetoothMapService
,08-26 12:45:44.514   872  3139 I ActivityManager: Killing 3467:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-26 12:45:44.552  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 12:45:44.574  1742  1742 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 12:45:44.580  1742  1742 D SystemUpdateService: onCreate
,08-26 12:45:44.585  1742  1742 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 12:45:44.600  1742  3948 I SystemUpdateService: active receiver: enabled
,08-26 12:45:44.612  1742  1742 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-26 12:45:44.614  1742  2364 I iu.UploadsManager: num queued entries: 0
,08-26 12:45:44.614  1742  2364 I iu.UploadsManager: num updated entries: 0
08-26 12:45:44.614  1742  3948 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 12:45:44.615  1742  2364 I iu.SyncManager: NEXT; no task
,08-26 12:45:44.625  1742  1742 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 12:45:44.627  1742  1742 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-26 12:45:44.625  1742  3948 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-26 12:45:44.627  1742  3948 I SystemUpdateService: now status is 0 (complete)
,08-26 12:45:44.627  1742  3948 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-26 12:45:44.627  1742  3948 I SystemUpdateService: file has been verified
,08-26 12:45:44.627  1742  3948 I SystemUpdateService: OTA package size = 12249756
,08-26 12:45:44.632  1742  3948 I SystemUpdateService: showing system update notification
,08-26 12:45:44.654   872  1875 I ActivityManager: Start proc 3950:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-26 12:45:44.664  1742  1742 D SystemUpdateService: onDestroy
,08-26 12:45:44.699  3950  3950 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-26 12:45:44.703  3950  3950 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 12:45:44.719  3950  3950 D SprintDMHelper: simOperator: 
,08-26 12:45:44.719  3950  3950 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 12:45:44.749   872  3139 I ActivityManager: Start proc 3962:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-26 12:45:44.752   872  3139 I ActivityManager: Killing 1683:android.process.acore/u0a5 (adj 15): empty #17
,08-26 12:45:44.934   872  2012 I ActivityManager: Start proc 3977:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-26 12:45:44.940  3062  3976 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-26 12:45:44.950   872   883 I ActivityManager: Killing 3641:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-26 12:45:45.034  3977  3977 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-26 12:45:45.109  3977  3977 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-26 12:45:45.109  3977  3977 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-26 12:45:45.109  3977  3977 I GAv4    :   adb logcat -s GAv4
,08-26 12:45:45.134  3977  3977 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-26 12:45:45.141  3977  3977 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-26 12:45:45.166  3977  3994 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-26 12:45:45.261  3977  3977 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-26 12:45:45.296  3977  3977 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-26 12:45:45.306  3977  3977 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 4578-4584)
,08-26 12:45:45.306  3977  3977 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-26 12:45:45.314  3977  3977 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {54d656f}
,08-26 12:45:45.314  3977  3977 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-26 12:45:45.314  3977  3977 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-26 12:45:45.321  3977  3977 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-26 12:45:45.323  3977  3977 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-26 12:45:45.344  3977  3977 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-26 12:45:45.356  3977  3977 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-26 12:45:45.356  3977  3977 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-26 12:45:45.357  3977  3977 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-26 12:45:45.357  3977  3977 I Adreno  : Build Date                       : 10/20/15
08-26 12:45:45.357  3977  3977 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 12:45:45.357  3977  3977 I Adreno  : Local Branch                     : M14
08-26 12:45:45.357  3977  3977 I Adreno  : Remote Branch                    : 
08-26 12:45:45.357  3977  3977 I Adreno  : Remote Branch                    : 
08-26 12:45:45.357  3977  3977 I Adreno  : Reconstruct Branch               : 
,08-26 12:45:45.411  3977  3977 I NSApplication: Starting up...
,08-26 12:45:45.419  3977  4023 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-26 12:45:45.452   872   883 I ActivityManager: Start proc 4028:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-26 12:45:45.454   872   883 I ActivityManager: Killing 3657:com.android.musicfx/u0a18 (adj 15): empty #17
,08-26 12:45:45.520  4028  4028 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-26 12:45:45.696   872   883 I ActivityManager: Killing 2239:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-26 12:45:46.575   872  2796 D WifiService: setWifiEnabled: true pid=3787, uid=10000
08-26 12:45:46.575   872  2796 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 12:45:46.591   872  1313 D WifiConfigStore: Loading config and enabling all networks 
,08-26 12:45:46.599  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 12:45:46.600  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:45:46.600  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:46.600  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:45:46.600  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:45:46.600  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:45:46.600  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:45:46.600  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:45:46.600  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 12:45:46.600  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:46.600  3787  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 12:45:46.603  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:46.604  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:45:46.604  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:46.604  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:45:46.604  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:45:46.604  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:45:46.604  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:45:46.604  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:45:46.604  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 12:45:46.604  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 12:45:46.604  3787  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 12:45:46.629   872  1313 D WifiConfigStore: loaded 0 passpoint configs
,08-26 12:45:46.630   872  1313 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-26 12:45:46.631   872  1313 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-26 12:45:46.632   872  1313 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-26 12:45:46.632   872  1313 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-26 12:45:46.632   872  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-26 12:45:46.632   872  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-26 12:45:46.645   369   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-26 12:45:46.646   872  1313 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.12 rxSuccessRate=15.75 delta 1000 -> 994
,08-26 12:45:46.647   369   870 D CommandListener: Setting iface cfg
,08-26 12:45:46.649   872  1312 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '129 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 129 Failed to set address (No such device)'
,08-26 12:45:46.649   872  1312 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-26 12:45:46.655   872  1313 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-26 12:45:46.655   872  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 12:45:46.663   872  1313 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-26 12:45:46.714   872  1313 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-26 12:45:46.715   872  1312 D WifiNative-HAL: p2pGetDeviceAddress
,08-26 12:45:46.716   872  1312 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-26 12:45:46.720  1468  1468 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-26 12:45:47.223  1468  1468 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-26 12:45:47.264  1468  1468 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-26 12:45:47.267  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-26 12:45:47.276   872  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 12:45:47.289   872  1313 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 12:45:47.290   872  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 12:45:47.290   872  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-26 12:45:47.313   872  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 12:45:47.333   369   870 D CommandListener: Setting iface cfg
,08-26 12:45:47.338   872  1313 D WifiStateMachine: Start Dhcp Watchdog 2
,08-26 12:45:47.356   872  1315 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-26 12:45:47.363   872  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-26 12:45:47.383   872  4051 D DhcpClient: Receive thread started
,08-26 12:45:47.465   872  1313 E native  : do suspend false
,08-26 12:45:47.484   872  1898 D DhcpClient: Broadcasting DHCPDISCOVER
,08-26 12:45:47.499   872  4051 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172686, domain null
,08-26 12:45:47.500   872  1898 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172686 seconds
,08-26 12:45:47.504   872  1898 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-26 12:45:47.516   872  4051 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-26 12:45:47.517   872  1898 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-26 12:45:47.523   369   870 D CommandListener: Setting iface cfg
,08-26 12:45:47.535   872  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-26 12:45:47.536   872  1898 D DhcpClient: Scheduling renewal in 86399s
,08-26 12:45:47.555   872  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-26 12:45:47.558   872  1313 D WifiConfigStore: No blacklist allowed without epno enabled
,08-26 12:45:47.558   872  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-26 12:45:47.559   872  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-26 12:45:47.561   872  1315 D ConnectivityService: Adding iface wlan0 to network 101
08-26 12:45:47.573   872  1313 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 12:45:47.618   872  1315 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-26 12:45:47.618   872  1315 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-26 12:45:47.619   872  1315 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-26 12:45:47.620   872  1315 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-26 12:45:47.621   872  1315 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-26 12:45:47.629   872  1315 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-26 12:45:47.635   872  1315 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-26 12:45:47.635   872  1315 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-26 12:45:47.635   872  1313 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-26 12:45:47.635   872  1315 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-26 12:45:47.636   872  1315 D ConnectivityService:    accepting network in place of null
08-26 12:45:47.636   872  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 12:45:47.638   872  1315 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 12:45:47.649   872  4050 D NetlinkSocketObserver: NeighborEvent{elapsedMs=136927, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-26 12:45:47.665   369   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 12:45:47.694   369   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 12:45:47.697   872  1315 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-26 12:45:47.698   872  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 12:45:47.699   872  1315 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-26 12:45:47.708   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-26 12:45:47.730  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 12:45:47.730  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:45:47.730  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:47.730  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:45:47.730  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:45:47.730  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:45:47.730  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:45:47.730  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:45:47.730  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 12:45:47.730  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:47.730  3787  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 12:45:47.730   872  4049 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.18.14,2a00:1450:4001:81c::200e
08-26 12:45:47.732  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:47.732  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:45:47.732  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:47.732  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:45:47.732  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:45:47.732  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:45:47.732  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:45:47.732  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:45:47.732  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 12:45:47.732  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:47.732  3787  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 12:45:47.741  1742  1742 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 12:45:47.744  1742  1742 D SystemUpdateService: onCreate
,08-26 12:45:47.747  1742  1742 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 12:45:47.750  1742  4062 I SystemUpdateService: active receiver: enabled
,08-26 12:45:47.753  1742  4062 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 12:45:47.755  1742  4062 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-26 12:45:47.756  1742  4062 I SystemUpdateService: now status is 0 (complete)
08-26 12:45:47.756  1742  4062 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-26 12:45:47.756  1742  4062 I SystemUpdateService: file has been verified
08-26 12:45:47.756  1742  4062 I SystemUpdateService: OTA package size = 12249756
,08-26 12:45:47.760  1742  4062 I SystemUpdateService: showing system update notification
,08-26 12:45:47.764  1742  1742 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-26 12:45:47.766  1742  2364 I iu.UploadsManager: num queued entries: 0
,08-26 12:45:47.767  1742  2364 I iu.UploadsManager: num updated entries: 0
,08-26 12:45:47.768  1742  2364 I iu.SyncManager: NEXT; no task
,08-26 12:45:47.769  1742  1742 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 12:45:47.770  1742  4065 I MDM     : [175] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-26 12:45:47.770  1742  4065 W BaseAppContext: Using Auth Proxy for data requests.
,08-26 12:45:47.770  1742  1742 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-26 12:45:47.771  1742  4065 V GoogleAuthProtoRequest: [175] a.<init>: mAccountName set to: thalitester@gmail.com
,08-26 12:45:47.773  3950  3950 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 12:45:47.774  1742  1742 D SystemUpdateService: onDestroy
,08-26 12:45:47.779  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 12:45:47.780  3950  3950 D SprintDMHelper: simOperator: 
,08-26 12:45:47.780  3950  3950 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-26 12:45:47.781  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 12:45:47.802   872  4049 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 10:45:47 GMT], X-Android-Received-Millis=[1472208347802], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472208347777]}
,08-26 12:45:47.803   872  1315 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-26 12:45:47.803   872  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,08-26 12:45:47.803   872  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-26 12:45:47.804   872  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-26 12:45:47.814  1523  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-26 12:45:47.814  1523  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-26 12:45:47.814  1523  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-26 12:45:47.814  1523  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 12:45:47.832  1742  4065 E MDM     : [175] SitrepService.a: Error sending sitrep.
,08-26 12:45:47.898  3062  4067 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-26 12:45:48.699   872  1315 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-26 12:45:49.419   872  1875 I ActivityManager: Killing 3679:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-26 12:45:49.581   872  2019 D WifiService: setWifiEnabled: false pid=3787, uid=10000
,08-26 12:45:49.582   872  2019 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 12:45:49.618  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-26 12:45:49.623   872  1313 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-26 12:45:49.623   872  1313 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-26 12:45:49.623   872  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 12:45:49.623   872  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 12:45:49.638   872  1898 D DhcpClient: Clearing IP address
,08-26 12:45:49.639   369   870 D CommandListener: Setting iface cfg
,08-26 12:45:49.644   369   870 D CommandListener: Clearing all IP addresses on wlan0
,08-26 12:45:49.647   872  4051 D DhcpClient: Receive thread stopped
,08-26 12:45:49.654  1523  4073 V NativeCrypto: Read error: ssl=0x9abffa00: I/O error during system call, Connection timed out
,08-26 12:45:49.658  1523  4073 V NativeCrypto: SSL shutdown failed: ssl=0x9abffa00: I/O error during system call, Broken pipe
,08-26 12:45:49.666   872   882 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,08-26 12:45:49.667   872  4049 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,08-26 12:45:49.672   872  4049 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.18.14,2a00:1450:4001:81c::200e
,08-26 12:45:49.673   872  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-26 12:45:49.673   872  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-26 12:45:49.677   398   398 E Parcel  : Reading a NULL string not supported here.
,08-26 12:45:49.685   872  4049 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:81c::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,08-26 12:45:49.689   872  1313 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-26 12:45:49.690   872  1315 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-26 12:45:49.690   872  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-26 12:45:49.727   369   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 12:45:49.765   369   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 12:45:49.765   369   870 D CommandListener: Clearing all IP addresses on wlan0
,08-26 12:45:49.766   872  1315 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-26 12:45:49.766   872  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 12:45:49.769   872   889 D Tethering: MasterInitialState.processMessage what=3
08-26 12:45:49.775  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:49.775  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:45:49.775  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:49.775  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:45:49.775  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:45:49.775  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:45:49.775  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:45:49.775  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:45:49.775  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 12:45:49.775  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:49.776  3787  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 12:45:49.778  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:49.778  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:45:49.778  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:49.778  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:45:49.778  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:45:49.778  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:45:49.778  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:45:49.778  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:45:49.778  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 12:45:49.779  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 12:45:49.779  3787  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 12:45:49.784   872  1313 D WifiConfigStore: Retrieve network priorities after PNO.
08-26 12:45:49.789  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:49.789  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:45:49.789  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:49.789  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:45:49.789  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 12:45:49.789  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:45:49.789  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:45:49.789  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:45:49.789  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 12:45:49.789  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:49.789  3787  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 12:45:49.790  1742  1742 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-26 12:45:49.792  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:49.792  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:45:49.792  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:49.792  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:45:49.792  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 12:45:49.792  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:45:49.792  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:45:49.792  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:45:49.792  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 12:45:49.792  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:49.793  3787  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 12:45:49.793   872  1313 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-26 12:45:49.795  2152  2316 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 12:45:49.814  1742  1742 D SystemUpdateService: onCreate
,08-26 12:45:49.818  1742  1742 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 12:45:49.823  1742  4085 I SystemUpdateService: active receiver: enabled
,08-26 12:45:49.829  1742  1742 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-26 12:45:49.833  1742  2364 I iu.UploadsManager: num queued entries: 0
,08-26 12:45:49.834  1742  4085 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 12:45:49.841  1742  4085 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-26 12:45:49.841  1742  4085 I SystemUpdateService: now status is 0 (complete)
,08-26 12:45:49.844  1742  1742 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 12:45:49.841  1742  4085 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-26 12:45:49.845  1742  1742 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-26 12:45:49.848  3950  3950 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 12:45:49.845  1742  4085 I SystemUpdateService: file has been verified
,08-26 12:45:49.851  1742  4085 I SystemUpdateService: OTA package size = 12249756
,08-26 12:45:49.855  3950  3950 D SprintDMHelper: simOperator: 
,08-26 12:45:49.855  3950  3950 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 12:45:49.858   369   870 E Netd    : netlink response contains error (No such file or directory)
,08-26 12:45:49.860   872  1315 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-26 12:45:49.860   872  1315 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-26 12:45:49.871  1742  2364 I iu.UploadsManager: num updated entries: 0
,08-26 12:45:49.872  1742  2364 I iu.SyncManager: NEXT; no task
,08-26 12:45:49.883  1742  4085 I SystemUpdateService: showing system update notification
,08-26 12:45:49.898  3062  4089 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-26 12:45:49.911  1742  1742 D SystemUpdateService: onDestroy
,08-26 12:45:52.639   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6af616e:true
,08-26 12:45:52.639  3936  3936 D BluetoothAdapterState: make() - Creating AdapterState
,08-26 12:45:52.644  3936  3936 I bt_bluedroid: init
,08-26 12:45:52.645  3936  4092 I BluetoothAdapterState: Entering OffState
,08-26 12:45:52.647  3936  4093 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-26 12:45:52.647  3936  4093 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-26 12:45:52.647  3936  4093 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 12:45:52.647  3936  4093 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-26 12:45:52.648  3936  3936 I bt_bluedroid: get_profile_interface socket
,08-26 12:45:52.650  3936  3936 I bt_bluedroid: get_profile_interface sdp
08-26 12:45:52.650  3936  4096 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 12:45:52.653  3936  4096 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 12:45:52.656  3936  3946 I bt_bluedroid: config_hci_snoop_log
,08-26 12:45:52.657   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-26 12:45:52.665  3936  4092 D BluetoothAdapterState: Current state: OFF, message: 0
,08-26 12:45:52.666  3936  4092 D BluetoothAdapterProperties: Setting state to 14
,08-26 12:45:52.666  3936  4092 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-26 12:45:52.670  3936  4092 D BluetoothBondStateMachine: make
,08-26 12:45:52.673  3936  4097 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 12:45:52.680  3936  3936 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
08-26 12:45:52.678  3936  4092 I BluetoothAdapterState: Entering PendingCommandState
,08-26 12:45:52.682  3936  3936 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@634bf1d
,08-26 12:45:52.683  3936  3936 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 12:45:52.684  3936  3936 D BtGatt.GattService: Received start request. Starting profile...
,08-26 12:45:52.684  3936  3936 D BtGatt.GattService: start()
08-26 12:45:52.684  3936  3936 I bt_bluedroid: get_profile_interface gatt
08-26 12:45:52.685  3936  3936 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@634bf1d
,08-26 12:45:52.685  3936  3936 D BtGatt.AdvertiseManager: advertise manager created
,08-26 12:45:52.689  3936  3936 V BluetoothAdapterState: isTurningOff()=false
,08-26 12:45:52.690  3936  3936 V BluetoothAdapterState: isTurningOn()=false
08-26 12:45:52.690  3936  3936 V BluetoothAdapterState: isBleTurningOn()=true
08-26 12:45:52.690  3936  3936 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 12:45:52.690  3936  4092 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-26 12:45:52.691  3936  4092 I bt_bluedroid: enable
08-26 12:45:52.692  3936  4093 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-26 12:45:52.692  3936  4093 I bt_hci  : start_up
,08-26 12:45:52.698  3936  4093 I bt_vendor: alloc value 0xb3939189
,08-26 12:45:52.698  3936  4093 I bt_vendor: init
08-26 12:45:52.698  3936  4093 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-26 12:45:52.698  3936  4093 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-26 12:45:52.806  3936  4093 D bt_hci  : start_up starting async portion
,08-26 12:45:52.808  3936  4100 I bt_hci  : event_finish_startup
,08-26 12:45:52.809  3936  4100 I bt_hci_h4: hal_open
08-26 12:45:52.809  3936  4100 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-26 12:45:52.818  3936  4100 I bt_userial_vendor: device fd = 51 open
,08-26 12:45:52.849  3936  4100 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 12:45:52.882  3936  4100 D bt_hwcfg: Chipset BCM4354A2
,08-26 12:45:52.882  3936  4100 D bt_hwcfg: Target name = [BCM4354A2]
08-26 12:45:52.883  3936  4100 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-26 12:45:53.569  3936  4100 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-26 12:45:53.571  3936  4100 D bt_hwcfg: Settlement delay -- 100 ms
,08-26 12:45:53.572  3936  4100 I bt_hwcfg: Setting fw settlement delay to 100 
,08-26 12:45:53.689  3936  4100 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 12:45:53.691  3936  4100 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-26 12:45:53.718  3936  4100 I bt_hwcfg: vendor lib fwcfg completed
,08-26 12:45:53.719  3936  4100 I bt_vendor: firmware callback
,08-26 12:45:53.720  3936  4100 I bt_hci  : firmware_config_callback
,08-26 12:45:53.734  3936  4102 I bt_btu  : btu_task pending for preload complete event
08-26 12:45:53.734  3936  4102 I bt_btu_task: Bluetooth chip preload is complete
,08-26 12:45:53.734  3936  4102 I bt_btu  : btu_task received preload complete event
,08-26 12:45:53.744  3936  4102 I         : BTE_InitTraceLevels -- TRC_HCI
,08-26 12:45:53.745  3936  4102 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 12:45:53.745  3936  4102 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 12:45:53.745  3936  4102 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 12:45:53.746  3936  4102 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-26 12:45:53.746  3936  4102 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 12:45:53.746  3936  4102 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 12:45:53.746  3936  4102 I         : BTE_InitTraceLevels -- TRC_BTM
08-26 12:45:53.746  3936  4102 I         : BTE_InitTraceLevels -- TRC_GAP
,08-26 12:45:53.747  3936  4102 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 12:45:53.747  3936  4102 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 12:45:53.747  3936  4102 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 12:45:53.747  3936  4102 I         : BTE_InitTraceLevels -- TRC_SMP
,08-26 12:45:53.748  3936  4102 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 12:45:53.748  3936  4102 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 12:45:53.885  3936  4102 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38b6d9d
,08-26 12:45:53.885  3936  4102 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38b6d9d 
,08-26 12:45:53.910  3936  4096 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-26 12:45:53.911  3936  4096 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-26 12:45:53.912  3936  4096 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 12:45:53.914  3936  4096 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 12:45:53.917  3936  4096 D BluetoothAdapterProperties: Scan Mode:20
,08-26 12:45:53.917  3936  4096 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 12:45:53.917  3936  4096 D bt_hci  : do_postload posting postload work item
,08-26 12:45:53.917  3936  4100 I bt_hci  : event_postload
08-26 12:45:53.917  3936  4100 I bt_vendor: sco_config_cb
,08-26 12:45:53.917  3936  4100 I bt_hci  : sco_config_callback postload finished.
,08-26 12:45:53.918  3936  4096 D bt_bte_conf: Device ID record 1 : primary
08-26 12:45:53.918  3936  4096 D bt_bte_conf:   vendorId            = 000f
08-26 12:45:53.918  3936  4096 D bt_bte_conf:   vendorIdSource      = 0001
08-26 12:45:53.918  3936  4096 D bt_bte_conf:   product             = 1200
08-26 12:45:53.918  3936  4096 D bt_bte_conf:   version             = 1436
08-26 12:45:53.918  3936  4096 D bt_bte_conf:   clientExecutableURL = 
08-26 12:45:53.918  3936  4096 D bt_bte_conf:   serviceDescription  = 
,08-26 12:45:53.918  3936  4096 D bt_bte_conf:   documentationURL    = 
08-26 12:45:53.918  3936  4096 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-26 12:45:53.919  3936  4093 D bt_stack_manager: event_start_up_stack finished
08-26 12:45:53.919  3936  4092 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-26 12:45:53.919  3936  4092 D BluetoothAdapterProperties: Setting state to 15
08-26 12:45:53.920  3936  4092 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-26 12:45:53.922  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:53.925  3936  4092 I BluetoothAdapterState: Entering BleOnState
08-26 12:45:53.927  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:53.928  3936  4092 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-26 12:45:53.928  3936  4100 I bt_vendor: low_power_mode_cb
08-26 12:45:53.928  3936  4092 D BluetoothAdapterProperties: Setting state to 11
,08-26 12:45:53.928  3936  4092 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-26 12:45:53.935  3936  3936 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@634bf1d
,08-26 12:45:53.936  3936  3936 D HeadsetService: Received start request. Starting profile...
,08-26 12:45:53.942  3936  3936 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-26 12:45:53.942  3936  3936 D HeadsetStateMachine: make
,08-26 12:45:53.947  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:45:53.954  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:45:53.956  3936  3936 D HeadsetStateMachine: max_hf_connections = 1
08-26 12:45:53.957  3936  3936 I bt_bluedroid: get_profile_interface handsfree
,08-26 12:45:53.958  3936  4096 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-26 12:45:53.958  3936  4096 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-26 12:45:53.968  3936  3936 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@634bf1d
,08-26 12:45:53.969  3936  4092 I BluetoothAdapterState: Entering PendingCommandState
08-26 12:45:53.969  3936  3936 D A2dpService: Received start request. Starting profile...
08-26 12:45:53.969  3936  3936 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-26 12:45:53.970  3936  3936 I bt_bluedroid: get_profile_interface avrcp
,08-26 12:45:53.979  3936  3936 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 12:45:53.979  3936  3936 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 12:45:53.979  3936  3936 D A2dpStateMachine: make,
,08-26 12:45:53.980  3936  3936 I bt_bluedroid: get_profile_interface a2dp
08-26 12:45:53.980  3936  4096 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-26 12:45:53.985  3936  4112 D A2dpStateMachine: Enter Disconnected: -2
,08-26 12:45:53.985  3936  3936 I BluetoothHidServiceJni: classInitNative: succeeds
,08-26 12:45:53.986  3936  3936 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@634bf1d
,08-26 12:45:53.986  3855  3855 D BluetoothInputDevice: Proxy object connected
,08-26 12:45:53.987  3936  3936 D HidService: Received start request. Starting profile...
08-26 12:45:53.987  3936  3936 I bt_bluedroid: get_profile_interface hidhost
08-26 12:45:53.987  3936  3936 D HidService: setHidService(): set to: null
08-26 12:45:53.987  3936  4096 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38983e5
08-26 12:45:53.987  3936  4096 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-26 12:45:53.989  3936  3936 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-26 12:45:53.989  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 12:45:53.990  3855  3855 D HidProfile: Bluetooth service connected
08-26 12:45:53.990  3936  3936 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@634bf1d
08-26 12:45:53.991  3936  3936 D HealthService: Received start request. Starting profile...
,08-26 12:45:53.992  3936  3936 I bt_bluedroid: get_profile_interface health
,08-26 12:45:53.992  3936  3936 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-26 12:45:53.993  3936  3936 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@634bf1d
,08-26 12:45:53.994  3936  3936 D PanService: Received start request. Starting profile...
08-26 12:45:53.994  3936  3936 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 12:45:53.994  3936  3936 I bt_bluedroid: get_profile_interface pan
08-26 12:45:53.994  3855  3855 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 12:45:53.995  3936  4096 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-26 12:45:53.996  3855  3855 D PanProfile: Bluetooth service connected
,08-26 12:45:54.001  3936  3936 V BluetoothAdapterState: isTurningOff()=false
,08-26 12:45:54.001  3936  3936 V BluetoothAdapterState: isTurningOn()=true
08-26 12:45:54.001  3936  3936 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:45:54.001  3936  3936 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 12:45:54.004  3936  3936 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@634bf1d
,08-26 12:45:54.005  3855  3855 D BluetoothMap: Proxy object connected
,08-26 12:45:54.005  3936  3936 D BluetoothMapService: Received start request. Starting profile...
08-26 12:45:54.006  3936  3936 D BluetoothMapService: start()
08-26 12:45:54.006  3855  3855 D MapProfile: Bluetooth service connected
08-26 12:45:54.006  3855  3855 D BluetoothMap: getConnectedDevices()
08-26 12:45:54.006  3855  3855 D BluetoothMap: Bluetooth is Not enabled
08-26 12:45:54.009  3936  3936 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-26 12:45:54.009  3936  3936 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-26 12:45:54.009  3936  3936 D BluetoothMapAppObserver: createReceiver()
,08-26 12:45:54.010  3936  3936 D BluetoothMapAppObserver: initObservers()
08-26 12:45:54.010  3936  3936 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-26 12:45:54.014  3936  3936 V BluetoothAdapterState: isTurningOff()=false
,08-26 12:45:54.014  3936  3936 V BluetoothAdapterState: isTurningOn()=true
08-26 12:45:54.014  3936  3936 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:45:54.014  3936  3936 V BluetoothAdapterState: isBleTurningOff()=false
08-26 12:45:54.014  3936  4109 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 12:45:54.015  3936  3936 V BluetoothAdapterState: isTurningOff()=false
08-26 12:45:54.015  3936  3936 V BluetoothAdapterState: isTurningOn()=true
08-26 12:45:54.015  3936  3936 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:45:54.015  3936  3936 V BluetoothAdapterState: isBleTurningOff()=false
08-26 12:45:54.015  3936  3936 V BluetoothAdapterState: isTurningOff()=false
08-26 12:45:54.015  3936  3936 V BluetoothAdapterState: isTurningOn()=true
08-26 12:45:54.015  3936  3936 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:45:54.015  3936  3936 V BluetoothAdapterState: isBleTurningOff()=false
08-26 12:45:54.015  3936  3936 V BluetoothAdapterState: isTurningOff()=false
08-26 12:45:54.015  3936  3936 V BluetoothAdapterState: isTurningOn()=true
08-26 12:45:54.015  3936  3936 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:45:54.015  3936  3936 V BluetoothAdapterState: isBleTurningOff()=false
08-26 12:45:54.015  3936  3936 V BluetoothAdapterState: isTurningOff()=false
,08-26 12:45:54.016  3936  3936 V BluetoothAdapterState: isTurningOn()=true
08-26 12:45:54.016  3936  3936 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:45:54.016  3936  3936 V BluetoothAdapterState: isBleTurningOff()=false
08-26 12:45:54.016  3936  4092 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-26 12:45:54.016  3936  4092 D BluetoothAdapterProperties: ScanMode =  20
08-26 12:45:54.016  3936  4092 D BluetoothAdapterProperties: State =  11
,08-26 12:45:54.018  3936  4096 D BluetoothAdapterProperties: Scan Mode:21
,08-26 12:45:54.018  3936  4092 D BluetoothAdapterProperties: Setting state to 12
,08-26 12:45:54.018  3936  4092 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-26 12:45:54.018  3936  4096 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 12:45:54.018  3936  4092 I BluetoothAdapterState: Entering OnState
08-26 12:45:54.018  1972  2188 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 12:45:54.019  1372  1384 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 12:45:54.020   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 12:45:54.021  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:45:54.021  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:54.021  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:45:54.021  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 12:45:54.021  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:45:54.021  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:45:54.021  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:45:54.021  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 12:45:54.021  3855  3869 D BluetoothPan: onBluetoothStateChange on: true
08-26 12:45:54.021  1372  2069 D BluetoothPbap: onBluetoothStateChange: up=true
,08-26 12:45:54.023  3787  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 12:45:54.023  1372  1383 D BluetoothMap: onBluetoothStateChange: up=true
08-26 12:45:54.024  1372  1372 D BluetoothA2dp: Proxy object connected
08-26 12:45:54.025  1372  2069 D BluetoothPan: onBluetoothStateChange on: true
08-26 12:45:54.026  1372  1372 D BluetoothMap: Proxy object connected
08-26 12:45:54.026  1372  1372 D MapProfile: Bluetooth service connected
08-26 12:45:54.026  1372  1372 D BluetoothMap: getConnectedDevices()
08-26 12:45:54.026  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:45:54.026  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:54.026  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:45:54.026  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 12:45:54.026  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:45:54.026  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:45:54.026  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:45:54.026  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 12:45:54.027  3855  3871 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 12:45:54.027  1372  1372 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 12:45:54.027  1372  1372 D PanProfile: Bluetooth service connected
08-26 12:45:54.028  3787  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 12:45:54.028  3855  3869 D BluetoothMap: onBluetoothStateChange: up=true
08-26 12:45:54.028   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 12:45:54.029  1372  1383 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 12:45:54.030  1372  1372 D BluetoothInputDevice: Proxy object connected
,08-26 12:45:54.030  1372  1372 D HidProfile: Bluetooth service connected
08-26 12:45:54.030   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 12:45:54.030  1372  2069 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 12:45:54.031  3855  3871 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 12:45:54.031   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 12:45:54.032   872   872 D BluetoothA2dp: Proxy object connected
08-26 12:45:54.032  3936  3936 D BluetoothMapService: onReceive
08-26 12:45:54.032  3936  3936 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:45:54.032  3936  3936 D BluetoothMapService: STATE_ON
,08-26 12:45:54.033  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:54.034  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:54.034  3936  3936 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-26 12:45:54.035  3936  3936 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-26 12:45:54.035   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
08-26 12:45:54.036  3936  3936 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 12:45:54.037  3936  3936 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 12:45:54.038  3936  3936 D ObexServerSockets: Succeed to create listening sockets 
,08-26 12:45:54.038  3936  3936 D ObexServerSockets0: startAccept()
08-26 12:45:54.038  3936  3936 D ObexServerSockets0: prepareForNewConnect()
08-26 12:45:54.039  3936  3936 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-26 12:45:54.039  3936  3936 D BluetoothSdpJni: SDP Create record success - handle: 0
08-26 12:45:54.040  3936  4119 D ObexServerSockets0: Accepting socket connection...
08-26 12:45:54.041  3936  4120 D ObexServerSockets0: Accepting socket connection...
,08-26 12:45:54.043  3855  3855 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-26 12:45:54.047  3855  3855 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-26 12:45:54.052  3855  3855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 12:45:54.053  3936  3936 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-26 12:45:54.053  3936  3936 D ObexServerSockets0: prepareForNewConnect()
,08-26 12:45:54.054  3855  3855 D BluetoothA2dp: Proxy object connected
08-26 12:45:54.056  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 12:45:54.062  1372  1372 D BluetoothPbap: Proxy object connected
,08-26 12:45:54.062  1372  1372 D PbapServerProfile: Bluetooth service connected
,08-26 12:45:54.064  3855  3855 D DockEventReceiver: finishStartingService: stopping service
,08-26 12:45:54.065  3855  3855 D BluetoothPbap: Proxy object connected
,08-26 12:45:54.065  3855  3855 D PbapServerProfile: Bluetooth service connected
,08-26 12:45:54.069  3936  4124 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 12:45:54.088  3936  4128 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 12:45:54.089  3936  4128 I BtOppRfcommListener: Accept thread started.
,08-26 12:45:54.120   872   872 D BluetoothHeadset: Proxy object connected
,08-26 12:45:54.120   872   872 D BluetoothHeadset: Proxy object connected
,08-26 12:45:54.120  1372  1384 D BluetoothHeadset: Proxy object connected
08-26 12:45:54.120  1372  1372 D HeadsetProfile: Bluetooth service connected
08-26 12:45:54.120   872   889 D BluetoothHeadset: Proxy object connected
,08-26 12:45:54.121  1972  2102 D BluetoothHeadset: Proxy object connected
08-26 12:45:54.121   872   872 D BluetoothHeadset: Proxy object connected
,08-26 12:45:54.129   872   889 D BluetoothHeadset: Proxy object connected
,08-26 12:45:54.130   872   889 D BluetoothHeadset: Proxy object connected
,08-26 12:45:54.131  1372  2069 D BluetoothHeadset: Proxy object connected
,08-26 12:45:54.131  1372  1372 D HeadsetProfile: Bluetooth service connected
,08-26 12:45:54.150  3855  3871 D BluetoothHeadset: Proxy object connected
,08-26 12:45:54.150  3855  3855 D HeadsetProfile: Bluetooth service connected
,08-26 12:45:55.599  3936  4092 D BluetoothAdapterState: Current state: ON, message: 23
,08-26 12:45:55.599  3936  4092 D BluetoothAdapterProperties: Setting state to 13
08-26 12:45:55.599  3936  4092 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 12:45:55.601  3936  4092 D BluetoothAdapterProperties: onBluetoothDisable()
,08-26 12:45:55.608  3936  4092 I BluetoothAdapterState: Entering PendingCommandState
,08-26 12:45:55.614  3936  3936 D BluetoothMapService: onReceive
08-26 12:45:55.614  3936  3936 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:45:55.615  3936  3936 D BluetoothMapService: STATE_TURNING_OFF
08-26 12:45:55.616  3936  3936 D BluetoothMapService: MAP Service closeService in
,08-26 12:45:55.616  3936  3936 D BluetoothMapMasInstance0: MAP Service shutdown
08-26 12:45:55.616  3936  3936 D ObexServerSockets0: shutdown(block = true)
08-26 12:45:55.617  3936  4119 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-26 12:45:55.621  3936  3936 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 12:45:55.622  3936  4120 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-26 12:45:55.622  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 12:45:55.622  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:45:55.622  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:55.622  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:45:55.622  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 12:45:55.622  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:45:55.622  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:45:55.622  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:45:55.622  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 12:45:55.623  3936  4104 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-26 12:45:55.624  3936  3936 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 12:45:55.627  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:55.627  3787  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 12:45:55.627  3936  4096 D BluetoothAdapterProperties: Scan Mode:20
08-26 12:45:55.628  3936  3936 I BtOppRfcommListener: stopping Accept Thread
08-26 12:45:55.628  3936  4092 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-26 12:45:55.629  3936  4128 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 12:45:55.630  3936  4128 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-26 12:45:55.632  3936  3936 D HeadsetService: Received stop request...Stopping profile...
08-26 12:45:55.633  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:55.633  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:45:55.633  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:55.633  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:45:55.633  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 12:45:55.633  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:45:55.633  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:45:55.633  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:45:55.633  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 12:45:55.633  3855  3855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-26 12:45:55.633   872   872 D BluetoothHeadset: Proxy object disconnected
,08-26 12:45:55.634  3936  3936 D A2dpService: Received stop request...Stopping profile...
08-26 12:45:55.635  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:55.635  3787  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 12:45:55.635  3936  4112 D A2dpStateMachine: Exit Disconnected: -1
08-26 12:45:55.636  3855  3869 D BluetoothHeadset: Proxy object disconnected
,08-26 12:45:55.636   872   872 D BluetoothHeadset: Proxy object disconnected
,08-26 12:45:55.637  1372  2069 D BluetoothHeadset: Proxy object disconnected
08-26 12:45:55.637  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:45:55.637  1972  1991 D BluetoothHeadset: Proxy object disconnected
08-26 12:45:55.637   872   872 D BluetoothHeadset: Proxy object disconnected
08-26 12:45:55.638  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:55.640   872   872 D BluetoothA2dp: Proxy object disconnected
08-26 12:45:55.641   872  1315 D ConnectivityService: handlePromptUnvalidated 101
,08-26 12:45:55.642  1372  1372 D HeadsetProfile: Bluetooth service disconnected
08-26 12:45:55.642  1372  1372 D BluetoothA2dp: Proxy object disconnected
08-26 12:45:55.646  3936  3936 D HidService: Received stop request...Stopping profile...
,08-26 12:45:55.646  3936  3936 D HidService: Stopping Bluetooth HidService
08-26 12:45:55.647  3855  3855 D HeadsetProfile: Bluetooth service disconnected
08-26 12:45:55.647  1372  1372 D BluetoothInputDevice: Proxy object disconnected
08-26 12:45:55.647  1372  1372 D HidProfile: Bluetooth service disconnected
08-26 12:45:55.647  3936  3936 V BluetoothAdapterState: isTurningOff()=true
,08-26 12:45:55.647  3936  3936 V BluetoothAdapterState: isTurningOn()=false
08-26 12:45:55.648  3936  3936 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 12:45:55.648  3936  3936 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 12:45:55.649  3936  3936 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 12:45:55.649  3936  3936 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 12:45:55.649  3936  4096 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-26 12:45:55.650  3936  3936 V BluetoothAdapterState: isTurningOff()=true
08-26 12:45:55.650  3936  3936 V BluetoothAdapterState: isTurningOn()=false
08-26 12:45:55.650  3936  3936 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 12:45:55.650  3936  3936 V BluetoothAdapterState: isBleTurningOff()=false
08-26 12:45:55.649  3936  4102 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 12:45:55.650  3936  4102 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 12:45:55.650  3936  4102 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 12:45:55.650  3936  4096 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
08-26 12:45:55.650  3936  3936 D HealthService: Received stop request...Stopping profile...
,08-26 12:45:55.653  3936  4102 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 12:45:55.653  3936  4102 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 12:45:55.654  3936  4102 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 12:45:55.654  3936  4102 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 12:45:55.654  3936  4102 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 12:45:55.654  3936  4102 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 12:45:55.654  3936  4096 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-26 12:45:55.658  3936  3936 D PanService: Received stop request...Stopping profile...
,08-26 12:45:55.659  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 12:45:55.659  1372  1372 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-26 12:45:55.659  1372  1372 D PanProfile: Bluetooth service disconnected
08-26 12:45:55.660  3936  3936 V BluetoothAdapterState: isTurningOff()=true
08-26 12:45:55.660  3936  3936 V BluetoothAdapterState: isTurningOn()=false
,08-26 12:45:55.660  3936  3936 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 12:45:55.660  3936  3936 V BluetoothAdapterState: isBleTurningOff()=false
08-26 12:45:55.661  3855  3855 D DockEventReceiver: finishStartingService: stopping service
08-26 12:45:55.661  3936  3936 D BluetoothMapService: Received stop request...Stopping profile...
08-26 12:45:55.661  3936  3936 D BluetoothMapService: stop()
,08-26 12:45:55.662  3936  3936 D BluetoothMapAppObserver: deinitObservers()
08-26 12:45:55.662  3936  3936 D BluetoothMapAppObserver: removeReceiver()
08-26 12:45:55.662  3855  3855 D BluetoothA2dp: Proxy object disconnected
,08-26 12:45:55.663  3855  3855 D BluetoothInputDevice: Proxy object disconnected
08-26 12:45:55.663  3936  3936 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-26 12:45:55.663  3936  3936 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 12:45:55.664  3936  4096 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-26 12:45:55.664  3855  3855 D HidProfile: Bluetooth service disconnected
08-26 12:45:55.664  3936  3936 V BluetoothAdapterState: isTurningOff()=true
08-26 12:45:55.664  3936  3936 V BluetoothAdapterState: isTurningOn()=false
08-26 12:45:55.664  3855  3855 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 12:45:55.664  3936  3936 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:45:55.664  3855  3855 D PanProfile: Bluetooth service disconnected
08-26 12:45:55.664  3936  3936 V BluetoothAdapterState: isBleTurningOff()=false
08-26 12:45:55.664  3936  3936 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 12:45:55.664  3936  4096 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-26 12:45:55.665  3936  3936 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 12:45:55.665  1372  1372 D BluetoothMap: Proxy object disconnected
08-26 12:45:55.665  1372  1372 D MapProfile: Bluetooth service disconnected
08-26 12:45:55.667  3855  3855 D BluetoothMap: Proxy object disconnected
08-26 12:45:55.667  3855  3855 D MapProfile: Bluetooth service disconnected
08-26 12:45:55.667  3855  3855 D BluetoothPbap: Proxy object disconnected
,08-26 12:45:55.667  3855  3855 D PbapServerProfile: Bluetooth service disconnected
08-26 12:45:55.667  3936  3936 V BluetoothAdapterState: isTurningOff()=true
08-26 12:45:55.667  1372  1372 D BluetoothPbap: Proxy object disconnected
08-26 12:45:55.667  3936  3936 V BluetoothAdapterState: isTurningOn()=false
08-26 12:45:55.667  1372  1372 D PbapServerProfile: Bluetooth service disconnected
08-26 12:45:55.667  3936  3936 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:45:55.667  3936  3936 V BluetoothAdapterState: isBleTurningOff()=false
08-26 12:45:55.668  3936  3936 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 12:45:55.668  3936  3936 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-26 12:45:55.670  3936  3936 D BluetoothMapService: MAP Service closeService in
08-26 12:45:55.670  3936  3936 V BluetoothAdapterState: isTurningOff()=true
08-26 12:45:55.670  3936  3936 V BluetoothAdapterState: isTurningOn()=false
08-26 12:45:55.670  3936  3936 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:45:55.670  3936  3936 V BluetoothAdapterState: isBleTurningOff()=false
08-26 12:45:55.670  3936  4092 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-26 12:45:55.670  3936  4092 D BluetoothAdapterProperties: Setting state to 15
,08-26 12:45:55.670  3936  4092 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-26 12:45:55.671  3936  4092 I BluetoothAdapterState: Entering BleOnState
08-26 12:45:55.671  3936  3936 D BluetoothMapService: cleanup()
08-26 12:45:55.671  3936  3936 D BluetoothMapService: MAP Service closeService in
08-26 12:45:55.675  1972  1999 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 12:45:55.675  1372  1383 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 12:45:55.675   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 12:45:55.676  3855  4131 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 12:45:55.676  3855  3869 D BluetoothPan: onBluetoothStateChange on: false
08-26 12:45:55.677  1372  2069 D BluetoothPbap: onBluetoothStateChange: up=false
,08-26 12:45:55.679  1372  1384 D BluetoothMap: onBluetoothStateChange: up=false
,08-26 12:45:55.679  1372  1383 D BluetoothPan: onBluetoothStateChange on: false
,08-26 12:45:55.680  3855  3871 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 12:45:55.680  3855  4131 D BluetoothMap: onBluetoothStateChange: up=false
,08-26 12:45:55.681  3855  3869 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 12:45:55.681   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 12:45:55.681  1372  2069 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-26 12:45:55.682   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 12:45:55.682  1372  1384 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 12:45:55.682  3855  3871 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 12:45:55.682   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 12:45:55.683  3936  4092 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-26 12:45:55.683  3936  4092 D BluetoothAdapterProperties: Setting state to 16
,08-26 12:45:55.683  3936  4092 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-26 12:45:55.683  3936  4092 D BluetoothAdapterProperties: onBleDisable
08-26 12:45:55.684  3936  4092 I BluetoothAdapterState: Entering PendingCommandState
08-26 12:45:55.684  3936  4093 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-26 12:45:55.685  3936  4102 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-26 12:45:55.685  3936  4102 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 12:45:55.686  3936  4096 D BluetoothAdapterProperties: Scan Mode:20
,08-26 12:45:55.686  3855  3855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 12:45:55.686  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:55.688  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:55.689  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:55.690  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 12:45:55.691  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:45:55.697  3855  3855 D DockEventReceiver: finishStartingService: stopping service
,08-26 12:45:55.886  3936  4096 I bt_hci  : shut_down
,08-26 12:45:55.887  3936  4100 D bt_hwcfg: hw_epilog_process
,08-26 12:45:55.899  3936  4100 I bt_vendor: low_power_mode_cb
,08-26 12:45:55.924  3936  4100 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-26 12:45:55.924  3936  4100 I bt_vendor: epilog_cb
08-26 12:45:55.924  3936  4100 I bt_hci  : epilog_finished_callback
,08-26 12:45:55.932  3936  4096 I bt_hci_h4: hal_close
,08-26 12:45:55.933  3936  4096 I bt_userial_vendor: device fd = 51 close
,08-26 12:45:56.047  3936  4093 D bt_stack_manager: event_shut_down_stack finished.
,08-26 12:45:56.049  3936  4092 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-26 12:45:56.054  3936  4092 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-26 12:45:56.055  3936  3936 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 12:45:56.059  3936  3936 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 12:45:56.059  3936  3936 D BtGatt.GattService: stop()
,08-26 12:45:56.060  3936  3936 D BtGatt.AdvertiseManager: advertise clients cleared
,08-26 12:45:56.064  3936  3936 V BluetoothAdapterState: isTurningOff()=false
,08-26 12:45:56.066  3936  3936 V BluetoothAdapterState: isTurningOn()=false
,08-26 12:45:56.066  3936  3936 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:45:56.067  3936  3936 V BluetoothAdapterState: isBleTurningOff()=true
,08-26 12:45:56.068  3936  4092 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-26 12:45:56.069  3936  4092 D BluetoothAdapterProperties: Setting state to 10
,08-26 12:45:56.070  3936  4092 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-26 12:45:56.071  3936  4092 I BluetoothAdapterState: Entering OffState
,08-26 12:45:56.075   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-26 12:45:56.105  3936  3936 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-26 12:45:56.105  3936  3936 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-26 12:45:56.108  3936  4093 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-26 12:45:56.115  3936  4093 D bt_stack_manager: event_clean_up_stack finished.
,08-26 12:45:56.108  3936  3936 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-26 12:45:56.123  3936  3936 I art     : System.exit called, status: 0
,08-26 12:45:56.124  3936  3936 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 12:45:56.175   872  2796 I ActivityManager: Process com.android.bluetooth (pid 3936) has died
,08-26 12:45:58.596  3787  3837 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:58.596  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 12:45:58.795  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 12:45:58.815  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 12:45:58.823  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 12:45:58.891  1523  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-26 12:45:58.891  1523  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-26 12:45:58.892  1523  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 12:45:58.892  1523  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 12:45:58.924  3509  3509 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-26 12:45:58.924  3509  3509 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-26 12:45:58.927  3509  3509 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-26 12:46:00.901   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-26 12:46:00.913  1901  1901 I Keyboard.Facilitator: onFinishInput()
,08-26 12:46:00.916   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-26 12:46:00.916   872   892 I Adreno  : Build Date                       : 10/20/15
08-26 12:46:00.916   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 12:46:00.916   872   892 I Adreno  : Local Branch                     : M14
08-26 12:46:00.916   872   892 I Adreno  : Remote Branch                    : 
08-26 12:46:00.916   872   892 I Adreno  : Remote Branch                    : 
08-26 12:46:00.916   872   892 I Adreno  : Reconstruct Branch               : 
,08-26 12:46:00.956   280   304 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (203 us)
,08-26 12:46:01.590  3787  3787 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 12:46:01.590  3787  3787 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-26 12:46:01.599  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 12:46:01.600  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@451c79b added. We now have 6 listener(s)
,08-26 12:46:01.600  3787  3837 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 12:46:01.601  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 12:46:01.601  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e856738 added. We now have 7 listener(s)
,08-26 12:46:01.601  3787  3837 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 12:46:01.601  3787  3837 I System.out: IsBluetoothEnabled
,08-26 12:46:01.623   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-26 12:46:01.630  3787  3787 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@b633019 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@1903311, 16908290=android.view.AbsSavedState$1@1903311}, android:focusedViewId=100}]}]
,08-26 12:46:01.631  3787  3787 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-26 12:46:01.631  3787  3787 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-26 12:46:01.631  3787  3787 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-26 12:46:01.636  3787  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:46:01.642   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-26 12:46:01.648   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
08-26 12:46:01.649   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-26 12:46:01.648   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-26 12:46:01.652   872   889 I ActivityManager: Start proc 4142:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-26 12:46:01.704  4142  4142 D AdapterServiceConfig: Adding HeadsetService
,08-26 12:46:01.704  4142  4142 D AdapterServiceConfig: Adding A2dpService
,08-26 12:46:01.704  4142  4142 D AdapterServiceConfig: Adding HidService
08-26 12:46:01.705  4142  4142 D AdapterServiceConfig: Adding HealthService
,08-26 12:46:01.705  4142  4142 D AdapterServiceConfig: Adding PanService
08-26 12:46:01.706  4142  4142 D AdapterServiceConfig: Adding GattService
,08-26 12:46:01.706  4142  4142 D AdapterServiceConfig: Adding BluetoothMapService
,08-26 12:46:01.722   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7dd2760:true
,08-26 12:46:01.722  4142  4142 D BluetoothAdapterState: make() - Creating AdapterState
,08-26 12:46:01.724  4142  4142 I bt_bluedroid: init
,08-26 12:46:01.724  4142  4154 I BluetoothAdapterState: Entering OffState
,08-26 12:46:01.726  4142  4155 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-26 12:46:01.726  4142  4155 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 12:46:01.726  4142  4155 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-26 12:46:01.726  4142  4155 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-26 12:46:01.726  4142  4142 I bt_bluedroid: get_profile_interface socket
08-26 12:46:01.727  4142  4142 I bt_bluedroid: get_profile_interface sdp
,08-26 12:46:01.729  4142  4153 I bt_bluedroid: config_hci_snoop_log
,08-26 12:46:01.729   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-26 12:46:01.730  4142  4158 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 12:46:01.731  4142  4158 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 12:46:01.738  4142  4154 D BluetoothAdapterState: Current state: OFF, message: 0
,08-26 12:46:01.739  4142  4154 D BluetoothAdapterProperties: Setting state to 14
08-26 12:46:01.739  4142  4154 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-26 12:46:01.739  4142  4154 D BluetoothBondStateMachine: make
,08-26 12:46:01.741  4142  4159 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 12:46:01.743  4142  4142 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
08-26 12:46:01.743  4142  4154 I BluetoothAdapterState: Entering PendingCommandState
,08-26 12:46:01.745  4142  4142 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@634bf1d
,08-26 12:46:01.745  4142  4142 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 12:46:01.746  4142  4142 D BtGatt.GattService: Received start request. Starting profile...
,08-26 12:46:01.746  4142  4142 D BtGatt.GattService: start()
08-26 12:46:01.746  4142  4142 I bt_bluedroid: get_profile_interface gatt
,08-26 12:46:01.746  4142  4142 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@634bf1d
08-26 12:46:01.746  4142  4142 D BtGatt.AdvertiseManager: advertise manager created
,08-26 12:46:01.749  4142  4142 V BluetoothAdapterState: isTurningOff()=false
,08-26 12:46:01.749  4142  4142 V BluetoothAdapterState: isTurningOn()=false
,08-26 12:46:01.749  4142  4142 V BluetoothAdapterState: isBleTurningOn()=true
08-26 12:46:01.749  4142  4142 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 12:46:01.750  4142  4154 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-26 12:46:01.750  4142  4154 I bt_bluedroid: enable
,08-26 12:46:01.751  4142  4155 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-26 12:46:01.751  4142  4155 I bt_hci  : start_up
,08-26 12:46:01.755  4142  4155 I bt_vendor: alloc value 0xb39b0189
08-26 12:46:01.755  4142  4155 I bt_vendor: init
,08-26 12:46:01.755  4142  4155 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-26 12:46:01.755  4142  4155 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-26 12:46:01.864  4142  4155 D bt_hci  : start_up starting async portion
,08-26 12:46:01.865  4142  4162 I bt_hci  : event_finish_startup
08-26 12:46:01.866  4142  4162 I bt_hci_h4: hal_open
08-26 12:46:01.868  4142  4162 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-26 12:46:01.876  4142  4162 I bt_userial_vendor: device fd = 51 open
,08-26 12:46:01.884   280   340 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-26 12:46:01.888   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-26 12:46:01.891   872  1341 D SurfaceControl: Excessive delay in setPowerMode(): 242ms
08-26 12:46:01.895   872   892 I DreamManagerService: Entering dreamland.
08-26 12:46:01.896   872   892 I PowerManagerService: Dozing...
,08-26 12:46:01.899   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-26 12:46:01.906  4142  4162 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 12:46:01.937  4142  4162 D bt_hwcfg: Chipset BCM4354A2
,08-26 12:46:01.937  4142  4162 D bt_hwcfg: Target name = [BCM4354A2]
,08-26 12:46:01.938  4142  4162 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-26 12:46:01.951   373  1322 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-26 12:46:01.951   373  1322 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-26 12:46:01.961   872  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 12:46:01.965   872  1313 E native  : do suspend false
,08-26 12:46:01.968  1962  4165 D NfcService: Discovery configuration equal, not updating.
,08-26 12:46:01.988   872  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 12:46:01.993   872  1313 E native  : do suspend true
,08-26 12:46:02.093   373  1286 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-26 12:46:02.093   373  1286 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-26 12:46:02.600  4142  4162 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-26 12:46:02.601  4142  4162 D bt_hwcfg: Settlement delay -- 100 ms
08-26 12:46:02.602  4142  4162 I bt_hwcfg: Setting fw settlement delay to 100 
,08-26 12:46:02.718  4142  4162 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 12:46:02.720  4142  4162 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-26 12:46:02.749  4142  4162 I bt_hwcfg: vendor lib fwcfg completed
08-26 12:46:02.749  4142  4162 I bt_vendor: firmware callback
08-26 12:46:02.750  4142  4162 I bt_hci  : firmware_config_callback
,08-26 12:46:02.761  4142  4169 I bt_btu  : btu_task pending for preload complete event
,08-26 12:46:02.761  4142  4169 I bt_btu_task: Bluetooth chip preload is complete
08-26 12:46:02.762  4142  4169 I bt_btu  : btu_task received preload complete event
,08-26 12:46:02.773  4142  4169 I         : BTE_InitTraceLevels -- TRC_HCI
,08-26 12:46:02.774  4142  4169 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-26 12:46:02.774  4142  4169 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 12:46:02.774  4142  4169 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 12:46:02.775  4142  4169 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-26 12:46:02.775  4142  4169 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 12:46:02.775  4142  4169 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-26 12:46:02.776  4142  4169 I         : BTE_InitTraceLevels -- TRC_BTM
08-26 12:46:02.777  4142  4169 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 12:46:02.777  4142  4169 I         : BTE_InitTraceLevels -- TRC_PAN
,08-26 12:46:02.778  4142  4169 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 12:46:02.778  4142  4169 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 12:46:02.779  4142  4169 I         : BTE_InitTraceLevels -- TRC_SMP
,08-26 12:46:02.780  4142  4169 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 12:46:02.780  4142  4169 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 12:46:02.919  4142  4169 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb392dd9d
,08-26 12:46:02.919  4142  4169 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb392dd9d 
,08-26 12:46:02.930  4142  4158 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
08-26 12:46:02.932  4142  4158 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-26 12:46:02.932  4142  4158 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 12:46:02.936  4142  4158 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 12:46:02.940  4142  4158 D BluetoothAdapterProperties: Scan Mode:20,
,08-26 12:46:02.941  4142  4158 D BluetoothAdapterProperties: Discoverable Timeout:120,
,08-26 12:46:02.941  4142  4158 D bt_hci  : do_postload posting postload work item,
,08-26 12:46:02.942  4142  4162 I bt_hci  : event_postload,
,08-26 12:46:02.942  4142  4162 I bt_vendor: sco_config_cb
,08-26 12:46:02.942  4142  4162 I bt_hci  : sco_config_callback postload finished.
08-26 12:46:02.946  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:46:02.947  4142  4158 D bt_bte_conf: Device ID record 1 : primary
08-26 12:46:02.947  4142  4158 D bt_bte_conf:   vendorId            = 000f
08-26 12:46:02.948  4142  4158 D bt_bte_conf:   vendorIdSource      = 0001
,08-26 12:46:02.948  4142  4158 D bt_bte_conf:   product             = 1200
,08-26 12:46:02.948  4142  4158 D bt_bte_conf:   version             = 1436,
08-26 12:46:02.948  4142  4162 I bt_vendor: low_power_mode_cb
08-26 12:46:02.948  4142  4158 D bt_bte_conf:   clientExecutableURL = ,
08-26 12:46:02.949  4142  4158 D bt_bte_conf:   serviceDescription  = 
08-26 12:46:02.949  4142  4158 D bt_bte_conf:   documentationURL    = ,
,08-26 12:46:02.949  4142  4158 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-26 12:46:02.950  4142  4155 D bt_stack_manager: event_start_up_stack finished
,08-26 12:46:02.950  4142  4154 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-26 12:46:02.951  4142  4154 D BluetoothAdapterProperties: Setting state to 15
08-26 12:46:02.951  4142  4154 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-26 12:46:02.953  4142  4154 I BluetoothAdapterState: Entering BleOnState
08-26 12:46:02.959  4142  4154 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-26 12:46:02.959  4142  4154 D BluetoothAdapterProperties: Setting state to 11
08-26 12:46:02.959  4142  4154 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-26 12:46:02.968  4142  4142 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@634bf1d
08-26 12:46:02.969  4142  4142 D HeadsetService: Received start request. Starting profile...
08-26 12:46:02.971  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:46:02.973  4142  4142 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 12:46:02.973  4142  4142 D HeadsetStateMachine: make
,08-26 12:46:02.986  4142  4142 D HeadsetStateMachine: max_hf_connections = 1
,08-26 12:46:02.986  4142  4142 I bt_bluedroid: get_profile_interface handsfree
08-26 12:46:02.987  4142  4158 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-26 12:46:02.987  4142  4158 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-26 12:46:02.990  4142  4154 I BluetoothAdapterState: Entering PendingCommandState
,08-26 12:46:02.992  4142  4142 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@634bf1d
,08-26 12:46:02.992  4142  4142 D A2dpService: Received start request. Starting profile...
,08-26 12:46:02.994  4142  4142 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-26 12:46:02.994  4142  4142 I bt_bluedroid: get_profile_interface avrcp
,08-26 12:46:03.002  4142  4142 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 12:46:03.002  4142  4142 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 12:46:03.002  4142  4142 D A2dpStateMachine: make
,08-26 12:46:03.003  4142  4142 I bt_bluedroid: get_profile_interface a2dp
,08-26 12:46:03.004  4142  4158 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-26 12:46:03.006  4142  4178 D A2dpStateMachine: Enter Disconnected: -2
,08-26 12:46:03.008  4142  4142 I BluetoothHidServiceJni: classInitNative: succeeds
,08-26 12:46:03.009  4142  4142 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@634bf1d
,08-26 12:46:03.010  4142  4142 D HidService: Received start request. Starting profile...
08-26 12:46:03.010  4142  4142 I bt_bluedroid: get_profile_interface hidhost
08-26 12:46:03.010  4142  4158 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb390f3e5
,08-26 12:46:03.010  4142  4158 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-26 12:46:03.010  4142  4142 D HidService: setHidService(): set to: null
,08-26 12:46:03.012  4142  4142 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-26 12:46:03.013  4142  4142 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@634bf1d
08-26 12:46:03.013  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 12:46:03.014  4142  4142 D HealthService: Received start request. Starting profile...
,08-26 12:46:03.015  4142  4142 I bt_bluedroid: get_profile_interface health
,08-26 12:46:03.017  4142  4142 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-26 12:46:03.017  4142  4142 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@634bf1d
08-26 12:46:03.018  4142  4142 D PanService: Received start request. Starting profile...
08-26 12:46:03.018  4142  4142 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-26 12:46:03.018  4142  4142 I bt_bluedroid: get_profile_interface pan
08-26 12:46:03.018  4142  4158 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-26 12:46:03.021  4142  4142 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@634bf1d
,08-26 12:46:03.022  4142  4142 D BluetoothMapService: Received start request. Starting profile...
08-26 12:46:03.022  4142  4142 D BluetoothMapService: start()
,08-26 12:46:03.024  4142  4142 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-26 12:46:03.025  4142  4142 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-26 12:46:03.025  4142  4142 D BluetoothMapAppObserver: createReceiver()
,08-26 12:46:03.026  4142  4142 D BluetoothMapAppObserver: initObservers()
08-26 12:46:03.026  4142  4142 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-26 12:46:03.032  4142  4142 V BluetoothAdapterState: isTurningOff()=false
,08-26 12:46:03.032  4142  4142 V BluetoothAdapterState: isTurningOn()=true
08-26 12:46:03.032  4142  4142 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:46:03.032  4142  4142 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 12:46:03.034  4142  4142 V BluetoothAdapterState: isTurningOff()=false
,08-26 12:46:03.034  4142  4142 V BluetoothAdapterState: isTurningOn()=true
08-26 12:46:03.034  4142  4176 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-26 12:46:03.035  4142  4142 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 12:46:03.035  4142  4142 V BluetoothAdapterState: isBleTurningOff()=false
08-26 12:46:03.035  4142  4142 V BluetoothAdapterState: isTurningOff()=false
,08-26 12:46:03.035  4142  4142 V BluetoothAdapterState: isTurningOn()=true
,08-26 12:46:03.035  4142  4142 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 12:46:03.035  4142  4142 V BluetoothAdapterState: isBleTurningOff()=false
08-26 12:46:03.035  4142  4142 V BluetoothAdapterState: isTurningOff()=false
08-26 12:46:03.036  4142  4142 V BluetoothAdapterState: isTurningOn()=true
,08-26 12:46:03.036  4142  4142 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:46:03.036  4142  4142 V BluetoothAdapterState: isBleTurningOff()=false
08-26 12:46:03.036  4142  4142 V BluetoothAdapterState: isTurningOff()=false
,08-26 12:46:03.036  4142  4142 V BluetoothAdapterState: isTurningOn()=true
,08-26 12:46:03.036  4142  4142 V BluetoothAdapterState: isBleTurningOn()=false
08-26 12:46:03.036  4142  4142 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 12:46:03.036  4142  4142 V BluetoothAdapterState: isTurningOff()=false
08-26 12:46:03.036  4142  4142 V BluetoothAdapterState: isTurningOn()=true
08-26 12:46:03.036  4142  4142 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 12:46:03.036  4142  4142 V BluetoothAdapterState: isBleTurningOff()=false
08-26 12:46:03.037  4142  4154 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-26 12:46:03.037  4142  4154 D BluetoothAdapterProperties: ScanMode =  20
08-26 12:46:03.037  4142  4154 D BluetoothAdapterProperties: State =  11
08-26 12:46:03.037  4142  4154 D BluetoothAdapterProperties: Setting state to 12
08-26 12:46:03.038  4142  4154 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 12:46:03.039  4142  4158 D BluetoothAdapterProperties: Scan Mode:21
,08-26 12:46:03.039  1972  1991 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 12:46:03.039  4142  4154 I BluetoothAdapterState: Entering OnState
,08-26 12:46:03.039  4142  4158 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 12:46:03.040  1372  2069 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 12:46:03.042   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 12:46:03.042  3855  3869 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 12:46:03.042  1372  1372 D BluetoothA2dp: Proxy object connected
,08-26 12:46:03.044  3855  4131 D BluetoothPan: onBluetoothStateChange on: true
,08-26 12:46:03.045  1372  1384 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 12:46:03.046  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:46:03.046  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:46:03.046  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:46:03.046  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 12:46:03.046  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:46:03.046  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:46:03.046  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:46:03.046  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 12:46:03.047  1372  2069 D BluetoothMap: onBluetoothStateChange: up=true
08-26 12:46:03.048  3787  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 12:46:03.049  3855  3855 D BluetoothA2dp: Proxy object connected
08-26 12:46:03.049  1372  1383 D BluetoothPan: onBluetoothStateChange on: true
,08-26 12:46:03.050  1372  1372 D BluetoothMap: Proxy object connected
08-26 12:46:03.050  1372  1372 D MapProfile: Bluetooth service connected
08-26 12:46:03.050  1372  1372 D BluetoothMap: getConnectedDevices()
08-26 12:46:03.051  3855  3855 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 12:46:03.051  3855  3855 D PanProfile: Bluetooth service connected
08-26 12:46:03.051  3855  3869 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 12:46:03.053  4142  4142 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-26 12:46:03.053  3855  4131 D BluetoothMap: onBluetoothStateChange: up=true
08-26 12:46:03.053  4142  4142 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-26 12:46:03.055  3855  3869 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 12:46:03.054  1372  1372 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 12:46:03.055  1372  1372 D PanProfile: Bluetooth service connected
08-26 12:46:03.055  4142  4142 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 12:46:03.055   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 12:46:03.055  1372  1384 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 12:46:03.057   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 12:46:03.057  4142  4142 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 12:46:03.057  1372  2069 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 12:46:03.058  3855  3871 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 12:46:03.058  4142  4142 D ObexServerSockets: Succeed to create listening sockets 
08-26 12:46:03.058  4142  4142 D ObexServerSockets0: startAccept()
08-26 12:46:03.058  4142  4142 D ObexServerSockets0: prepareForNewConnect()
08-26 12:46:03.060   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 12:46:03.060   872   872 D BluetoothA2dp: Proxy object connected
08-26 12:46:03.060  4142  4142 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-26 12:46:03.061  4142  4142 D BluetoothSdpJni: SDP Create record success - handle: 0
08-26 12:46:03.064  3855  3855 D BluetoothMap: Proxy object connected
,08-26 12:46:03.064  3855  3855 D MapProfile: Bluetooth service connected
08-26 12:46:03.064  3855  3855 D BluetoothMap: getConnectedDevices()
08-26 12:46:03.064   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
08-26 12:46:03.065  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:46:03.068  4142  4142 D BluetoothMapService: onReceive
08-26 12:46:03.068  4142  4142 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:46:03.068  4142  4142 D BluetoothMapService: STATE_ON
,08-26 12:46:03.068  1372  1372 D BluetoothInputDevice: Proxy object connected
08-26 12:46:03.068  1372  1372 D HidProfile: Bluetooth service connected
08-26 12:46:03.069  4142  4183 D ObexServerSockets0: Accepting socket connection...
08-26 12:46:03.071  3855  3855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-26 12:46:03.071  4142  4184 D ObexServerSockets0: Accepting socket connection...
08-26 12:46:03.075  3855  3855 D BluetoothInputDevice: Proxy object connected
08-26 12:46:03.075  3855  3855 D HidProfile: Bluetooth service connected
,08-26 12:46:03.080  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 12:46:03.081  3855  3855 D DockEventReceiver: finishStartingService: stopping service
,08-26 12:46:03.088  3855  3855 D BluetoothPbap: Proxy object connected
08-26 12:46:03.088  3855  3855 D PbapServerProfile: Bluetooth service connected
,08-26 12:46:03.093  1372  1372 D BluetoothPbap: Proxy object connected
,08-26 12:46:03.093  1372  1372 D PbapServerProfile: Bluetooth service connected
,08-26 12:46:03.095  4142  4142 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-26 12:46:03.095  4142  4142 D ObexServerSockets0: prepareForNewConnect()
,08-26 12:46:03.098  4142  4189 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 12:46:03.111  4142  4193 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 12:46:03.113  4142  4193 I BtOppRfcommListener: Accept thread started.
,08-26 12:46:03.141   872   872 D BluetoothHeadset: Proxy object connected
,08-26 12:46:03.141   872   889 D BluetoothHeadset: Proxy object connected
08-26 12:46:03.141  3855  4131 D BluetoothHeadset: Proxy object connected
,08-26 12:46:03.141  3855  3855 D HeadsetProfile: Bluetooth service connected
08-26 12:46:03.141   872   872 D BluetoothHeadset: Proxy object connected
08-26 12:46:03.142  1372  1383 D BluetoothHeadset: Proxy object connected
08-26 12:46:03.142  1372  1372 D HeadsetProfile: Bluetooth service connected
,08-26 12:46:03.143  1972  1999 D BluetoothHeadset: Proxy object connected
,08-26 12:46:03.144   872   872 D BluetoothHeadset: Proxy object connected
,08-26 12:46:03.155  3855  3869 D BluetoothHeadset: Proxy object connected
08-26 12:46:03.155   872   889 D BluetoothHeadset: Proxy object connected
08-26 12:46:03.155  3855  3855 D HeadsetProfile: Bluetooth service connected
,08-26 12:46:03.157   872   889 D BluetoothHeadset: Proxy object connected
,08-26 12:46:03.157  1372  2069 D BluetoothHeadset: Proxy object connected
08-26 12:46:03.158  1372  1372 D HeadsetProfile: Bluetooth service connected
,08-26 12:46:03.663  3787  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:46:03.663  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:46:03.663  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:46:03.663  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 12:46:03.663  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:46:03.663  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:46:03.663  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:46:03.663  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 12:46:03.672  3787  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 12:46:03.675  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 12:46:03.675  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a1b1c76 added. We now have 8 listener(s)
08-26 12:46:03.677  3787  3837 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 12:46:03.684   872  2012 D WifiService: setWifiEnabled: false pid=3787, uid=10000
,08-26 12:46:03.685   872  2012 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 12:46:03.697  3787  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:46:03.698   872  2984 D WifiService: setWifiEnabled: true pid=3787, uid=10000
08-26 12:46:03.698   872  2984 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 12:46:03.712   872  1313 D WifiConfigStore: Loading config and enabling all networks 
,08-26 12:46:03.730  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:46:03.730  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:46:03.730  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:46:03.730  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:46:03.730  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:46:03.730  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:46:03.730  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:46:03.730  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 12:46:03.736  3787  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 12:46:03.744   872  1313 D WifiConfigStore: loaded 0 passpoint configs
,08-26 12:46:03.745   872  1313 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-26 12:46:03.746   872  1313 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-26 12:46:03.747   872  1313 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-26 12:46:03.747   872  1313 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-26 12:46:03.747   872  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-26 12:46:03.747   872  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-26 12:46:03.761   369   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-26 12:46:03.762   872  1313 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.04 rxSuccessRate=0.07 delta 1000 -> 1000
,08-26 12:46:03.763   369   870 D CommandListener: Setting iface cfg
,08-26 12:46:03.763   872  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-26 12:46:03.765   872  1312 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '154 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 154 Failed to set address (No such device)'
,08-26 12:46:03.765   872  1312 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-26 12:46:03.774   872  1313 E native  : do suspend true
,08-26 12:46:03.783   872  1312 D WifiNative-HAL: p2pGetDeviceAddress
,08-26 12:46:03.788   872  1312 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-26 12:46:03.791   872  1313 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-26 12:46:03.791   872  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 12:46:03.817   872  1313 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-26 12:46:03.874   872  1313 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-26 12:46:03.876  1468  1468 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-26 12:46:04.488  1468  1468 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-26 12:46:04.530  1468  1468 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-26 12:46:04.533  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-26 12:46:04.539   872  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 12:46:04.552   872  1313 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 12:46:04.553   872  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 12:46:04.553   872  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-26 12:46:04.568   872  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 12:46:04.580   369   870 D CommandListener: Setting iface cfg
,08-26 12:46:04.581   872  1313 D WifiStateMachine: Start Dhcp Watchdog 3
,08-26 12:46:04.590   872  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-26 12:46:04.633   872  4201 D DhcpClient: Receive thread started
,08-26 12:46:04.719  3787  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:46:04.719  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:46:04.719  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:46:04.719  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:46:04.719  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:46:04.719  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:46:04.719  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:46:04.719  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 12:46:04.722   872  1313 E native  : do suspend false
,08-26 12:46:04.725  3787  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 12:46:04.733  3787  3837 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-26 12:46:04.735  3787  3837 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-26 12:46:04.742   872  1898 D DhcpClient: Broadcasting DHCPDISCOVER
,08-26 12:46:04.741  3787  3837 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@b633019 Bundle[{}]
,08-26 12:46:04.744  3787  3837 I io.jxcore.node.LifeCycleMonitor: start: OK
08-26 12:46:04.745  3787  3837 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-26 12:46:04.746  3787  3837 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-26 12:46:04.748  3787  3837 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-26 12:46:04.749  3787  3837 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-26 12:46:04.751  3787  3837 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 12:46:04.755  3787  3837 I System.out: Running OutgoingSocketThread
,08-26 12:46:04.756   872  4201 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-26 12:46:04.756   872  1898 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-26 12:46:04.757   872  1898 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-26 12:46:04.758  3787  4202 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 415)
08-26 12:46:04.759  3787  4202 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 49670
,08-26 12:46:04.759  3787  4202 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-26 12:46:04.780   872  4201 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-26 12:46:04.780   872  1898 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-26 12:46:04.782   369   870 D CommandListener: Setting iface cfg
,08-26 12:46:04.787   872  1898 D DhcpClient: Scheduling renewal in 86399s
,08-26 12:46:04.791   872  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-26 12:46:04.793   872  1313 E native  : do suspend true
,08-26 12:46:04.810   872  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-26 12:46:04.811   872  1313 D WifiConfigStore: No blacklist allowed without epno enabled
,08-26 12:46:04.812   872  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-26 12:46:04.815   872  1315 D ConnectivityService: Adding iface wlan0 to network 102
,08-26 12:46:04.822   872  1313 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 12:46:04.873   872  1315 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-26 12:46:04.874   872  1315 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-26 12:46:04.876   872  1315 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-26 12:46:04.880   872  1315 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-26 12:46:04.881   872  1315 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-26 12:46:04.894   872  1315 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-26 12:46:04.900   872  1315 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-26 12:46:04.901   872  1315 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-26 12:46:04.901   872  1313 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-26 12:46:04.902   872  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 12:46:04.902   872  1315 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-26 12:46:04.902   872  1315 D ConnectivityService:    accepting network in place of null
08-26 12:46:04.904   872  1315 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 12:46:04.929   872  4200 D NetlinkSocketObserver: NeighborEvent{elapsedMs=154207, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-26 12:46:04.938   369   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 12:46:04.986   369   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 12:46:04.992   872  1315 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-26 12:46:04.992   872  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 12:46:04.996   872  1315 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-26 12:46:04.999   872   889 D Tethering: MasterInitialState.processMessage what=3
08-26 12:46:05.006   872  4199 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.210.14,2a00:1450:4001:803::200e
08-26 12:46:05.020  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:46:05.020  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:46:05.020  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:46:05.020  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:46:05.020  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:46:05.020  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:46:05.020  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:46:05.020  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 12:46:05.023  3787  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 12:46:05.026  1742  1742 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 12:46:05.033  1742  1742 D SystemUpdateService: onCreate
,08-26 12:46:05.038  1742  1742 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 12:46:05.047  1742  4211 I SystemUpdateService: active receiver: enabled
,08-26 12:46:05.056  1742  4211 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 12:46:05.060  1742  1742 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-26 12:46:05.063  1742  2364 I iu.UploadsManager: num queued entries: 0
,08-26 12:46:05.059  1742  4211 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-26 12:46:05.064  1742  4211 I SystemUpdateService: now status is 0 (complete)
08-26 12:46:05.065  1742  4211 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-26 12:46:05.065  1742  4211 I SystemUpdateService: file has been verified
08-26 12:46:05.065  1742  4211 I SystemUpdateService: OTA package size = 12249756
,08-26 12:46:05.069  1742  1742 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 12:46:05.070  1742  1742 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-26 12:46:05.073  1742  4214 I MDM     : [180] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-26 12:46:05.073  1742  4214 W BaseAppContext: Using Auth Proxy for data requests.
,08-26 12:46:05.076  1742  4214 V GoogleAuthProtoRequest: [180] a.<init>: mAccountName set to: thalitester@gmail.com
,08-26 12:46:05.078  1742  2364 I iu.UploadsManager: num updated entries: 0
08-26 12:46:05.079  1742  2364 I iu.SyncManager: NEXT; no task
,08-26 12:46:05.082  1742  4211 I SystemUpdateService: showing system update notification
,08-26 12:46:05.084  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 12:46:05.085  3950  3950 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 12:46:05.086  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 12:46:05.090  3950  3950 D SprintDMHelper: simOperator: 
,08-26 12:46:05.091  3950  3950 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 12:46:05.098   872  4199 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 10:46:05 GMT], X-Android-Received-Millis=[1472208365097], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472208365061]}
,08-26 12:46:05.100   872  1315 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-26 12:46:05.100   872  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-26 12:46:05.100   872  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-26 12:46:05.103   872  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-26 12:46:05.121  1742  1742 D SystemUpdateService: onDestroy
,08-26 12:46:05.136  1523  2995 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-26 12:46:05.136  1523  2995 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-26 12:46:05.136  1523  2995 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 12:46:05.137  1523  2995 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 12:46:05.156  1742  4214 E MDM     : [180] SitrepService.a: Error sending sitrep.
,08-26 12:46:05.221  3062  4217 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-26 12:46:05.759  3787  3837 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 416)
,08-26 12:46:05.759  3787  3837 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 416)
,08-26 12:46:05.769  3787  3837 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 421)
,08-26 12:46:05.771  3787  3837 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-26 12:46:05.771  3787  3837 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 422)
,08-26 12:46:05.777  3787  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 12:46:05.777  3787  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97b4277 added. We now have 2 listener(s)
,08-26 12:46:05.779  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 12:46:05.779  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 12:46:05.779  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 12:46:05.779  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 12:46:05.779  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c5bee4 added. We now have 9 listener(s)
08-26 12:46:05.779  3787  3837 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 12:46:05.780  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 12:46:05.785  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 12:46:05.791  3787  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 12:46:05.791  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:46:05.791  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:46:05.791  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:46:05.791  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:46:05.791  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:46:05.791  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:46:05.791  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 12:46:05.793  3787  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 12:46:05.793  3787  3837 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 12:46:05.794  3787  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 12:46:05.794  3787  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4148a02 added. We now have 3 listener(s)
08-26 12:46:05.795  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 12:46:05.796  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 12:46:05.796  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 12:46:05.796  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 12:46:05.796  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e578f13 added. We now have 10 listener(s)
08-26 12:46:05.796  3787  3837 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 12:46:05.796  3787  3837 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:46:05.796  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:46:05.796  3787  3837 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 12:46:05.797  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:46:05.797  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:46:05.797  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 12:46:05.797  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 12:46:05.797  3787  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97b4277 removed from the list
08-26 12:46:05.797  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:46:05.797  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c5bee4 removed from the list
,08-26 12:46:05.799  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:46:05.808  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:46:05.808  3787  3837 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:46:05.809  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:46:05.809  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 12:46:05.809  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 12:46:05.813  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 12:46:05.813  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:46:05.813  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:46:05.814  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c5bee4 not in the list
08-26 12:46:05.814  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 12:46:05.815  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 12:46:05.817  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 12:46:05.817  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:46:05.817  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 12:46:05.818  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e578f13 removed from the list
08-26 12:46:05.819  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:46:05.819  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 12:46:05.819  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:46:05.819  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 12:46:05.819  3787  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4148a02 removed from the list
08-26 12:46:05.820  3787  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 12:46:05.820  3787  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@491e550 added. We now have 2 listener(s)
,08-26 12:46:05.823  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 12:46:05.823  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 12:46:05.823  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 12:46:05.823  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 12:46:05.823  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1dd3349 added. We now have 9 listener(s)
08-26 12:46:05.823  3787  3837 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 12:46:05.824  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 12:46:05.827  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 12:46:05.832  3787  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 12:46:05.832  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:46:05.832  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:46:05.832  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:46:05.832  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:46:05.832  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:46:05.832  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:46:05.832  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 12:46:05.834  3787  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 12:46:05.835  3787  3837 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 12:46:05.835  3787  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 12:46:05.835  3787  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ea2096f added. We now have 3 listener(s)
08-26 12:46:05.837  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:46:05.838  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 12:46:05.838  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 12:46:05.838  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 12:46:05.839  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 12:46:05.839  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b8067c added. We now have 10 listener(s)
08-26 12:46:05.839  3787  3837 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 12:46:05.839  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 12:46:05.839  3787  3837 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 12:46:05.839  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 12:46:05.839  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 12:46:05.840  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 12:46:05.840  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:46:05.843  3787  3837 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 12:46:05.843  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 12:46:05.848  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 12:46:05.848  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 12:46:05.849  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 12:46:05.852  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 12:46:05.853  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 12:46:05.853  3787  3837 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 12:46:05.853  3787  3837 D BluetoothAdapter: STATE_ON
,08-26 12:46:05.857  4142  4153 D BtGatt.GattService: registerClient() - UUID=a0ce3378-66c7-4322-9fd3-55cf38535a2d
,08-26 12:46:05.858  4142  4158 D BtGatt.GattService: onClientRegistered() - UUID=a0ce3378-66c7-4322-9fd3-55cf38535a2d, clientIf=5
,08-26 12:46:05.859  3787  3798 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 12:46:05.860  4142  4152 D BtGatt.GattService: start scan with filters
,08-26 12:46:05.866  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 12:46:05.866  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-26 12:46:05.866  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 12:46:05.866  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 12:46:05.866  4142  4161 D BtGatt.ScanManager: handling starting scan
,08-26 12:46:05.868  4142  4161 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@634bf1d
08-26 12:46:05.869  3787  3837 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 12:46:05.870  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 12:46:05.870  3787  3837 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 12:46:05.872  4142  4158 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 12:46:05.872  4142  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:46:05.873  4142  4161 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 12:46:05.874  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 12:46:05.878  3787  3837 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 12:46:05.878  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 12:46:05.878  3787  3837 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 12:46:05.878  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 12:46:05.878  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 12:46:05.878  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-26 12:46:05.878  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 12:46:05.879  3787  3837 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-26 12:46:05.879  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 12:46:05.879  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 12:46:05.879  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 12:46:05.880  3787  3837 D BluetoothAdapter: STATE_ON
,08-26 12:46:05.881  4142  4152 D BtGatt.GattService: stopScan() - queue size =1
08-26 12:46:05.883  4142  4185 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 12:46:05.884  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 12:46:05.884  4142  4158 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-26 12:46:05.884  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 12:46:05.884  4142  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:46:05.884  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-26 12:46:05.885  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 12:46:05.885  4142  4161 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 12:46:05.885  4142  4161 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 12:46:05.885  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 12:46:05.887  3787  3837 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 12:46:05.888  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 12:46:05.888  3787  3837 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-26 12:46:05.888  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 12:46:05.889  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 12:46:05.890  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 12:46:05.891  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 12:46:05.891  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 12:46:05.895  3787  3837 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:46:05.896  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 12:46:05.896  3787  3837 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:46:05.896  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:46:05.896  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:46:05.897  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 12:46:05.897  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 12:46:05.897  3787  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@491e550 removed from the list
08-26 12:46:05.897  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:46:05.897  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1dd3349 removed from the list
,08-26 12:46:05.897  3787  3837 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:46:05.897  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:46:05.898  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:46:05.898  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:46:05.900  4142  4158 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 12:46:05.901  4142  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 12:46:05.901  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 12:46:05.901  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 12:46:05.901  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 12:46:05.901  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1dd3349 not in the list
08-26 12:46:05.902  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 12:46:05.902  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:46:05.903  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:46:05.903  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 12:46:05.903  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:46:05.903  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b8067c removed from the list
08-26 12:46:05.903  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:46:05.903  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:46:05.903  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:46:05.903  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 12:46:05.904  3787  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ea2096f removed from the list
08-26 12:46:05.904  3787  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 12:46:05.904  3787  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd0e68 added. We now have 2 listener(s)
08-26 12:46:05.906  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 12:46:05.907  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 12:46:05.907  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 12:46:05.907  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 12:46:05.907  4142  4158 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 12:46:05.907  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7530281 added. We now have 9 listener(s)
08-26 12:46:05.907  4142  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:46:05.907  3787  3837 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 12:46:05.908  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 12:46:05.912  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 12:46:05.915  4142  4158 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 12:46:05.915  4142  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 12:46:05.915  4142  4161 D BtGatt.ScanManager: stopping BLe Batch
,08-26 12:46:05.918  3787  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 12:46:05.918  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:46:05.918  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:46:05.918  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:46:05.918  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:46:05.918  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:46:05.918  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:46:05.918  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 12:46:05.921  3787  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 12:46:05.922  3787  3837 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 12:46:05.923  4142  4158 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 12:46:05.923  4142  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:46:05.923  4142  4161 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-26 12:46:05.923  3787  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 12:46:05.924  3787  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0bb767 added. We now have 3 listener(s)
08-26 12:46:05.924  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:46:05.926  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 12:46:05.926  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 12:46:05.926  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 12:46:05.926  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 12:46:05.926  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:46:05.926  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@388a914 added. We now have 10 listener(s)
08-26 12:46:05.927  3787  3837 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 12:46:05.927  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 12:46:05.928  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 12:46:05.928  3787  3837 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 12:46:05.928  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 12:46:05.928  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 12:46:05.928  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 12:46:05.932  3787  3837 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 12:46:05.932  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 12:46:05.932  4142  4158 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 12:46:05.932  4142  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 12:46:05.935  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 12:46:05.936  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-26 12:46:05.936  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 12:46:05.939  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 12:46:05.939  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-26 12:46:05.939  3787  3837 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 12:46:05.940  3787  3837 D BluetoothAdapter: STATE_ON
,08-26 12:46:05.942  4142  4152 D BtGatt.GattService: registerClient() - UUID=c202e540-dcec-4785-ae06-94bee06b9e52
,08-26 12:46:05.943  4142  4158 D BtGatt.GattService: onClientRegistered() - UUID=c202e540-dcec-4785-ae06-94bee06b9e52, clientIf=5
08-26 12:46:05.943  3787  3799 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 12:46:05.943  4142  4185 D BtGatt.GattService: start scan with filters
,08-26 12:46:05.946  4142  4161 D BtGatt.ScanManager: handling starting scan
08-26 12:46:05.946  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 12:46:05.946  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 12:46:05.946  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 12:46:05.947  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 12:46:05.950  3787  3837 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 12:46:05.951  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 12:46:05.951  3787  3837 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 12:46:05.952  4142  4158 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-26 12:46:05.952  4142  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:46:05.952  4142  4161 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 12:46:05.954  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 12:46:05.958  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 12:46:05.958  3787  3837 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-26 12:46:05.958  4142  4158 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 12:46:05.958  4142  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:46:05.958  4142  4161 D BtGatt.ScanManager: Starting BLE batch scan
08-26 12:46:05.958  4142  4161 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 12:46:05.959  3787  3837 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:46:05.959  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:46:05.959  3787  3837 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 12:46:05.959  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:46:05.959  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:46:05.960  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 12:46:05.960  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 12:46:05.960  3787  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd0e68 removed from the list
08-26 12:46:05.960  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:46:05.960  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7530281 removed from the list
08-26 12:46:05.960  3787  3837 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:46:05.960  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 12:46:05.961  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-26 12:46:05.961  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-26 12:46:05.961  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:46:05.961  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 12:46:05.963  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:46:05.963  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:46:05.963  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:46:05.963  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7530281 not in the list
08-26 12:46:05.963  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 12:46:05.963  3787  3837 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-26 12:46:05.964  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 12:46:05.964  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 12:46:05.964  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 12:46:05.965  3787  3837 D BluetoothAdapter: STATE_ON
,08-26 12:46:05.966  4142  4175 D BtGatt.GattService: stopScan() - queue size =1
08-26 12:46:05.966  4142  4153 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 12:46:05.967  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 12:46:05.967  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 12:46:05.967  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 12:46:05.967  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 12:46:05.968  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 12:46:05.969  3787  3837 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 12:46:05.969  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 12:46:05.969  3787  3837 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 12:46:05.969  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 12:46:05.970  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:46:05.971  4142  4158 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 12:46:05.971  4142  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 12:46:05.972  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 12:46:05.972  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 12:46:05.972  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 12:46:05.972  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:46:05.972  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:46:05.972  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 12:46:05.973  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@388a914 removed from the list
08-26 12:46:05.973  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:46:05.973  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:46:05.973  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 12:46:05.973  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 12:46:05.973  3787  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0bb767 removed from the list
08-26 12:46:05.974  3787  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 12:46:05.974  3787  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cd14280 added. We now have 2 listener(s)
,08-26 12:46:05.976  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 12:46:05.977  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 12:46:05.977  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 12:46:05.977  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 12:46:05.977  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@65c80b9 added. We now have 9 listener(s)
,08-26 12:46:05.977  3787  3837 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 12:46:05.977  4142  4158 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 12:46:05.978  4142  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:46:05.978  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 12:46:05.980  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 12:46:05.984  3787  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 12:46:05.984  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:46:05.984  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:46:05.984  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:46:05.984  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:46:05.984  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:46:05.984  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:46:05.984  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 12:46:05.985  4142  4158 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 12:46:05.985  4142  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:46:05.985  4142  4161 D BtGatt.ScanManager: stopping BLe Batch
,08-26 12:46:05.988  3787  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 12:46:05.988  3787  3837 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 12:46:05.989  3787  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 12:46:05.989  3787  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4e2c5f added. We now have 3 listener(s)
,08-26 12:46:05.990  4142  4158 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 12:46:05.990  4142  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:46:05.991  4142  4161 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 12:46:05.991   872  1315 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-26 12:46:05.992  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:46:05.994  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:46:05.996  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 12:46:05.996  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 12:46:05.996  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 12:46:05.997  4142  4158 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 12:46:05.997  4142  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:46:05.997  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 12:46:05.998  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4806ac added. We now have 10 listener(s)
08-26 12:46:05.998  3787  3837 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 12:46:05.999  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 12:46:06.000  3787  3837 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-26 12:46:06.000  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 12:46:06.000  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 12:46:06.000  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 12:46:06.004  3787  3837 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-26 12:46:06.004  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 12:46:06.007  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 12:46:06.008  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 12:46:06.008  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 12:46:06.010  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 12:46:06.011  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 12:46:06.011  3787  3837 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 12:46:06.011  3787  3837 D BluetoothAdapter: STATE_ON
,08-26 12:46:06.013  4142  4175 D BtGatt.GattService: registerClient() - UUID=62473461-93c3-48b4-ad6f-168c533e304b
,08-26 12:46:06.013  4142  4158 D BtGatt.GattService: onClientRegistered() - UUID=62473461-93c3-48b4-ad6f-168c533e304b, clientIf=5
08-26 12:46:06.014  3787  3798 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 12:46:06.014  4142  4153 D BtGatt.GattService: start scan with filters
,08-26 12:46:06.016  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 12:46:06.016  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 12:46:06.016  4142  4161 D BtGatt.ScanManager: handling starting scan
08-26 12:46:06.016  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 12:46:06.016  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 12:46:06.018  3787  3837 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 12:46:06.019  3787  3837 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 12:46:06.019  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 12:46:06.020  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 12:46:06.023  4142  4158 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 12:46:06.023  4142  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 12:46:06.023  4142  4161 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 12:46:06.025  3787  3837 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:46:06.025  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 12:46:06.025  3787  3837 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:46:06.026  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:46:06.026  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:46:06.026  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 12:46:06.026  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 12:46:06.026  3787  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cd14280 removed from the list
08-26 12:46:06.026  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:46:06.026  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@65c80b9 removed from the list
08-26 12:46:06.026  3787  3837 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:46:06.026  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 12:46:06.027  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-26 12:46:06.027  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-26 12:46:06.027  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:46:06.027  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 12:46:06.028  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:46:06.028  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:46:06.028  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:46:06.028  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@65c80b9 not in the list
,08-26 12:46:06.028  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 12:46:06.028  3787  3837 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 12:46:06.028  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 12:46:06.028  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 12:46:06.028  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 12:46:06.029  3787  3837 D BluetoothAdapter: STATE_ON
,08-26 12:46:06.030  4142  4153 D BtGatt.GattService: stopScan() - queue size =1
08-26 12:46:06.030  4142  4152 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 12:46:06.030  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 12:46:06.030  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 12:46:06.031  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-26 12:46:06.031  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 12:46:06.031  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 12:46:06.032  3787  3837 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 12:46:06.032  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 12:46:06.032  3787  3837 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 12:46:06.032  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 12:46:06.032  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 12:46:06.033  4142  4158 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-26 12:46:06.033  4142  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:46:06.034  4142  4161 D BtGatt.ScanManager: Starting BLE batch scan
08-26 12:46:06.034  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:46:06.034  4142  4161 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 12:46:06.034  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:46:06.034  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:46:06.034  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 12:46:06.034  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4806ac removed from the list
08-26 12:46:06.034  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:46:06.034  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 12:46:06.034  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:46:06.034  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:46:06.034  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 12:46:06.034  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 12:46:06.034  3787  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4e2c5f removed from the list
08-26 12:46:06.035  3787  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 12:46:06.035  3787  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@584e198 added. We now have 2 listener(s)
,08-26 12:46:06.037  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 12:46:06.037  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 12:46:06.037  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 12:46:06.037  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 12:46:06.037  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e08df1 added. We now have 9 listener(s)
08-26 12:46:06.037  3787  3837 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 12:46:06.038  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 12:46:06.040  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 12:46:06.044  3787  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 12:46:06.044  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:46:06.044  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 12:46:06.044  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:46:06.044  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:46:06.044  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:46:06.044  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:46:06.044  3787  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 12:46:06.047  3787  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 12:46:06.047  3787  3837 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 12:46:06.048  3787  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 12:46:06.048  3787  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adb4857 added. We now have 3 listener(s)
08-26 12:46:06.050  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 12:46:06.050  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 12:46:06.050  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 12:46:06.050  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 12:46:06.050  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b27f44 added. We now have 10 listener(s)
08-26 12:46:06.050  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:46:06.050  3787  3837 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 12:46:06.051  3787  3837 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:46:06.051  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:46:06.051  3787  3837 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:46:06.051  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:46:06.051  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:46:06.051  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 12:46:06.051  4142  4158 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 12:46:06.051  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 12:46:06.051  3787  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@584e198 removed from the list
08-26 12:46:06.051  4142  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:46:06.051  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:46:06.052  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e08df1 removed from the list
,08-26 12:46:06.057  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:46:06.057  3787  3837 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:46:06.057  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:46:06.058  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:46:06.058  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 12:46:06.060  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 12:46:06.060  4142  4158 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 12:46:06.060  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:46:06.060  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:46:06.060  4142  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:46:06.060  3787  3837 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e08df1 not in the list
,08-26 12:46:06.060  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:46:06.060  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:46:06.062  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:46:06.062  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:46:06.062  3787  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:46:06.062  3787  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b27f44 removed from the list
08-26 12:46:06.062  3787  3837 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:46:06.063  3787  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:46:06.063  3787  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:46:06.063  3787  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 12:46:06.063  3787  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adb4857 removed from the list
,08-26 12:46:06.066  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-26 12:46:06.067  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-26 12:46:06.067  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-26 12:46:06.067  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 12:46:06.068  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-26 12:46:06.068  3787  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 12:46:06.069  4142  4158 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-26 12:46:06.069  4142  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 12:46:06.070  4142  4161 D BtGatt.ScanManager: stopping BLe Batch
,08-26 12:46:06.077  4142  4158 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-26 12:46:06.077  4142  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 12:46:06.077  4142  4161 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 12:46:06.081  3787  4223 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 429, name: My test thread name)
,08-26 12:46:06.081  3787  4223 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 429, thread name: My test thread name)
,08-26 12:46:06.082  3787  4223 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 429, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 12:46:06.083  4142  4158 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-26 12:46:06.083  4142  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 12:46:06.084  3787  4224 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 431, name: My test thread name)
08-26 12:46:06.085  3787  4224 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 431, thread name: My test thread name)
08-26 12:46:06.085  3787  4224 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 431, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-26 12:46:06.087  3787  3837 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-26 12:46:06.088  3787  3837 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-26 12:46:06.088  3787  3837 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-26 12:46:06.088  3787  3837 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,08-26 12:46:06.088  3787  3837 D com.test.thalitest.ThaliTestRunner: Total duration: 22899 ms
,08-26 12:46:06.091  3787  3837 I jxcore-log: *Native tests were executed*
08-26 12:46:06.091  3787  3837 I jxcore-log: 
,08-26 12:46:06.091  3787  3837 I jxcore-log: Total number of executed tests:  80
08-26 12:46:06.091  3787  3837 I jxcore-log: 
,08-26 12:46:06.092  3787  3837 I jxcore-log: Number of passed tests:  80
08-26 12:46:06.092  3787  3837 I jxcore-log: 
08-26 12:46:06.092  3787  3837 I jxcore-log: Number of failed tests:  0
08-26 12:46:06.092  3787  3837 I jxcore-log: 
08-26 12:46:06.093  3787  3837 I jxcore-log: Number of ignored tests:  0
08-26 12:46:06.093  3787  3837 I jxcore-log: 
08-26 12:46:06.093  3787  3837 I jxcore-log: Total duration:  22899
08-26 12:46:06.093  3787  3837 I jxcore-log: 
08-26 12:46:06.093  3787  3837 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-26 12:46:06.093  3787  3837 I jxcore-log: 
,08-26 12:46:06.097  3787  3837 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:46:06.097  3787  3837 I jxcore-log: 
08-26 12:46:06.100  3787  3787 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-26 12:46:06.100  3787  3837 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:46:06.100  3787  3837 I jxcore-log: 
08-26 12:46:06.101  3787  3837 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:46:06.101  3787  3837 I jxcore-log: 
08-26 12:46:06.103  3787  3837 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:46:06.103  3787  3837 I jxcore-log: 
08-26 12:46:06.104  3787  3837 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:46:06.104  3787  3837 I jxcore-log: 
08-26 12:46:06.105  3787  3837 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:46:06.105  3787  3837 I jxcore-log: 
08-26 12:46:06.108  3787  3837 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:46:06.108  3787  3837 I jxcore-log: 
08-26 12:46:06.110  3787  3837 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 12:46:06.110  3787  3837 I jxcore-log: 
08-26 12:46:06.110  3787  3837 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 12:46:06.110  3787  3837 I jxcore-log: 
08-26 12:46:06.111  3787  3837 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 12:46:06.111  3787  3837 I jxcore-log: 
08-26 12:46:06.112  3787  3837 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 12:46:06.112  3787  3837 I jxcore-log: 
,08-26 12:46:06.112  3787  3837 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 12:46:06.112  3787  3837 I jxcore-log: 
08-26 12:46:06.113  3787  3837 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:46:06.113  3787  3837 I jxcore-log: 
,08-26 12:46:06.113  3787  3837 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:46:06.113  3787  3837 I jxcore-log: 
08-26 12:46:06.114  3787  3837 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 12:46:06.114  3787  3837 I jxcore-log: 
,08-26 12:46:06.114  3787  3837 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 12:46:06.114  3787  3837 I jxcore-log: 
08-26 12:46:06.115  3787  3837 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 12:46:06.115  3787  3837 I jxcore-log: 
08-26 12:46:06.115  3787  3837 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 12:46:06.115  3787  3837 I jxcore-log: 
,08-26 12:46:06.115  3787  3837 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 12:46:06.115  3787  3837 I jxcore-log: 
08-26 12:46:06.116  3787  3837 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 12:46:06.116  3787  3837 I jxcore-log: 
,08-26 12:46:06.116  3787  3837 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 12:46:06.116  3787  3837 I jxcore-log: 
08-26 12:46:06.117  3787  3837 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 12:46:06.117  3787  3837 I jxcore-log: 
,08-26 12:46:06.117  3787  3837 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 12:46:06.117  3787  3837 I jxcore-log: 
08-26 12:46:06.118  3787  3837 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 12:46:06.118  3787  3837 I jxcore-log: 
,08-26 12:46:06.118  3787  3837 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 12:46:06.118  3787  3837 I jxcore-log: 
08-26 12:46:06.119  3787  3837 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 12:46:06.119  3787  3837 I jxcore-log: 
08-26 12:46:06.119  3787  3837 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:46:06.119  3787  3837 I jxcore-log: 
08-26 12:46:06.120  3787  3837 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:46:06.120  3787  3837 I jxcore-log: 
08-26 12:46:06.120  3787  3837 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:46:06.120  3787  3837 I jxcore-log: 
08-26 12:46:06.120  3787  3837 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:46:06.120  3787  3837 I jxcore-log: 
08-26 12:46:06.121  3787  3837 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:46:06.121  3787  3837 I jxcore-log: 
08-26 12:46:06.121  3787  3837 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:46:06.121  3787  3837 I jxcore-log: 
,08-26 12:46:06.391  3787  3787 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 12:46:06.393  3787  3837 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 12:46:06.393  3787  3837 I jxcore-log: 
,08-26 12:46:06.472  3787  3787 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 12:46:06.475  3787  3837 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 12:46:06.475  3787  3837 I jxcore-log: 
,08-26 12:46:06.535  3787  3787 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 12:46:06.537  3787  3837 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 12:46:06.537  3787  3837 I jxcore-log: 
,08-26 12:46:06.776  4226  4226 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-26 12:46:06.782  4226  4226 D AndroidRuntime: CheckJNI is OFF
,08-26 12:46:06.824  4226  4226 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-26 12:46:06.870  4226  4226 I Radio-JNI: register_android_hardware_Radio DONE
,08-26 12:46:06.893  4226  4226 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-26 12:46:06.908   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-26 12:46:06.909   872   885 I ActivityManager: Killing 3787:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-26 12:46:07.015   872  3139 I WindowState: WIN DEATH: Window{f9dd7a9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-26 12:46:07.016   872  1314 D WifiService: Client connection lost with reason: 4
08-26 12:46:07.016   872  2012 D GraphicsStats: Buffer count: 2
,08-26 12:46:07.021   872   896 W PackageSettings: Skipping PackageSetting{ceba8d6 com.example.hello/10273} due to missing metadata
,08-26 12:46:07.064   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-26 12:46:07.065   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-26 12:46:07.066   872   885 E ActivityManager: Failure starting process com.test.thalitest
08-26 12:46:07.066   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-26 12:46:07.066   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-26 12:46:07.066   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-26 12:46:07.066   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-26 12:46:07.066   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-26 12:46:07.066   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-26 12:46:07.066   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-26 12:46:07.066   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-26 12:46:07.066   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-26 12:46:07.066   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-26 12:46:07.066   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-26 12:46:07.066   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-26 12:46:07.066   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-26 12:46:07.066   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-26 12:46:07.066   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-26 12:46:07.066   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:46:07.066   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:46:07.066   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 12:46:07.066   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-26 12:46:07.067   872   885 I ActivityManager:   Force finishing activity ActivityRecord{44e6bf6 u0 com.test.thalitest/.MainActivity t2}
,08-26 12:46:07.067   872   896 I art     : Starting a blocking GC Explicit
,08-26 12:46:07.074   872   882 W ActivityManager: Spurious death for ProcessRecord{4e3669d 0:com.test.thalitest/u0a0}, curProc for 3787: null
,08-26 12:46:07.124   872   896 I art     : Explicit concurrent mark sweep GC freed 13692(957KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 856us total 56.131ms
,08-26 12:46:07.155   872   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-26 12:46:07.159  4226  4226 I art     : System.exit called, status: 0
08-26 12:46:07.159  4226  4226 I AndroidRuntime: VM exiting with result code 0.
,08-26 12:46:07.161   872   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-26 12:46:07.183   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-26 12:46:07.187  4142  4142 D BluetoothMapAppObserver: onReceive
,08-26 12:46:07.187  4142  4142 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-26 12:46:07.188  2152  2281 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-26 12:46:07.190  3627  3627 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) },
,08-26 12:46:07.196   872  1305 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-26 12:46:07.221  1901  1901 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-26 12:46:07.237   872  1858 I ActivityManager: Start proc 4240:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-26 12:46:07.246  1972  1972 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-26 12:46:07.248  1901  4250 I Keyboard.Facilitator.DecoderInitializer: run()
,08-26 12:46:07.255  1901  4250 I Decoder : createOrResetDecoder
,08-26 12:46:07.280  1523  1523 I ConfigService: onCreate
,08-26 12:46:07.283  1523  4253 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-26 12:46:07.283  1523  4253 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 12:46:07.283  1523  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 12:46:07.283  1523  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 12:46:07.283  1523  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 12:46:07.283  1523  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 12:46:07.283  1523  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 12:46:07.283  1523  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 12:46:07.283  1523  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 12:46:07.283  1523  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 12:46:07.283  1523  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 12:46:07.283  1523  4253 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 12:46:07.283  1523  4253 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 12:46:07.283  1523  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 12:46:07.283  1523  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 12:46:07.283  1523  4253 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-26 12:46:07.283  1523  4253 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-26 12:46:07.283  1523  4253 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-26 12:46:07.283  1523  4253 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-26 12:46:07.283  1523  4253 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 12:46:07.283  1523  4253 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 12:46:07.283  1523  4253 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 12:46:07.283  1523  4253 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 12:46:07.283  1523  4253 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 12:46:07.283  1523  4253 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 12:46:07.283  1523  4253 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 12:46:07.283  1523  4253 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 12:46:07.283  1523  4253 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 12:46:07.283  1523  4253 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 12:46:07.283  1523  4253 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 12:46:07.283  1523  4253 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 12:46:07.283  1523  4253 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 12:46:07.283  1523  4253 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 12:46:07.283  1523  4253 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-26 12:46:07.283  1523  4253 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-26 12:46:07.283  1523  4253 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,08-26 12:46:07.285  1523  4253 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-26 12:46:07.290  4240  4240 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm,
,08-26 12:46:07.302  2152  2651 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-26 12:46:07.306   872   882 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3787 uid 10000
,08-26 12:46:07.306  1901  1901 I Keyboard.Facilitator: onFinishInput()
08-26 12:46:07.306  1901  4250 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-26 12:46:07.312   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-26 12:46:07.350  4240  4240 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-26 12:46:07.353  1992  2068 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-26 12:46:07.356   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-26 12:46:07.357   872   884 E PackageManager: Failed to write settings, restoring backup
08-26 12:46:07.357   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-26 12:46:07.357   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-26 12:46:07.357   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-26 12:46:07.357   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-26 12:46:07.357   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-26 12:46:07.357   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:46:07.357   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:46:07.357   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 12:46:07.360   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-26 12:46:07.360   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-26 12:46:07.360   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 12:46:07.360   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 12:46:07.360   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 12:46:07.360   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 12:46:07.360   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 12:46:07.360   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 12:46:07.360   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-26 12:46:07.360   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-26 12:46:07.360   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-26 12:46:07.360   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 12:46:07.360   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 12:46:07.360   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
,08-26 12:46:07.360   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 12:46:07.360   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-26 12:46:07.360   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 12:46:07.360   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 12:46:07.360   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 12:46:07.360   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 12:46:07.360   872   885 E DropBoxManagerService: 	... 13 more
08-26 12:46:07.360  1901  4250 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-26 12:46:07.363  1901  4250 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-26 12:46:07.364  1901  4250 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-26 12:46:07.366   872   883 I ActivityManager: Start proc 4258:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-26 12:46:07.367  1992  2068 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-26 12:46:07.367  1992  2068 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1992
08-26 12:46:07.367  1992  2068 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 12:46:07.367  1992  2068 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-26 12:46:07.367  1992  2068 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-26 12:46:07.367  1992  2068 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-26 12:46:07.367  1992  2068 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-26 12:46:07.367  1992  2068 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-26 12:46:07.367  1992  2068 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-26 12:46:07.367  1992  2068 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-26 12:46:07.367  1992  2068 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 12:46:07.367  1992  2068 E AndroidRuntime: 	,at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 12:46:07.367  1992  2068 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:46:07.367  1992  2068 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 12:46:07.369   872  3139 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-26 12:46:07.372   872  4264 E DropBoxManagerService: Can't write: system_app_crash
08-26 12:46:07.372   872  4264 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-26 12:46:07.372   872  4264 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 12:46:07.372   872  4264 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 12:46:07.372   872  4264 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 12:46:07.372   872  4264 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 12:46:07.372   872  4264 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 12:46:07.372   872  4264 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 12:46:07.372   872  4264 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 12:46:07.372   872  4264 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 12:46:07.372   872  4264 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 12:46:07.372   872  4264 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 12:46:07.372   872  4264 E DropBoxManagerService: 	... 5 more
08-26 12:46:07.374  1992  2068 I Process : Sending signal. PID: 1992 SIG: 9
08-26 12:46:07.376  1901  4250 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-26 12:46:07.376  1901  4250 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-26 12:46:07.377  1901  4250 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-26 12:46:07.377  1901  4250 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-26 12:46:07.378  1901  4250 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-26 12:46:07.378  1901  4250 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-26 12:46:07.378  1901  4250 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-26 12:46:07.378  1901  4250 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-26 12:46:07.378  1901  4250 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-26 12:46:07.378  1901  4250 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-26 12:46:07.391   872  1875 I ActivityManager: Start proc 4273:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-26 12:46:07.396  4240  4272 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-26 12:46:07.429  4273  4273 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-26 12:46:07.460  1523  1523 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-26 12:46:07.462  1523  1523 D AndroidRuntime: Shutting down VM
,08-26 12:46:07.463  1523  1523 E AndroidRuntime: FATAL EXCEPTION: main
08-26 12:46:07.463  1523  1523 E AndroidRuntime: Process: com.google.process.gapps, PID: 1523
08-26 12:46:07.463  1523  1523 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 12:46:07.463  1523  1523 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-26 12:46:07.463  1523  1523 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-26 12:46:07.463  1523  1523 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-26 12:46:07.463  1523  1523 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:46:07.463  1523  1523 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:46:07.463  1523  1523 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 12:46:07.463  1523  1523 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 12:46:07.463  1523  1523 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 12:46:07.463  1523  1523 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 12:46:07.463  1523  1523 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 12:46:07.463  1523  1523 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-26 12:46:07.463  1523  1523 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-26 12:46:07.463  1523  1523 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-26 12:46:07.463  1523  1523 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-26 12:46:07.463  1523  1523 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-26 12:46:07.463  1523  1523 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-26 12:46:07.463  1523  1523 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-26 12:46:07.463  1523  1523 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-26 12:46:07.463  1523  1523 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-26 12:46:07.463  1523  1523 E AndroidRuntime: 	... 8 more
,08-26 12:46:07.466   872  4288 E DropBoxManagerService: Can't write: system_app_crash
08-26 12:46:07.466   872  4288 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-26 12:46:07.466   872  4288 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 12:46:07.466   872  4288 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 12:46:07.466   872  4288 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 12:46:07.466   872  4288 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 12:46:07.466   872  4288 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 12:46:07.466   872  4288 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 12:46:07.466   872  4288 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 12:46:07.466   872  4288 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 12:46:07.466   872  4288 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 12:46:07.466   872  4288 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 12:46:07.466   872  4288 E DropBoxManagerService: 	... 5 more
,08-26 12:46:07.467  1523  1523 I Process : Sending signal. PID: 1523 SIG: 9
,08-26 12:46:07.496   872  1385 D GraphicsStats: Buffer count: 1
08-26 12:46:07.496   872   882 I WindowState: WIN DEATH: Window{e5b2c8e u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-26 12:46:07.504   872  1314 D WifiService: Client connection lost with reason: 4
,08-26 12:46:07.506   872  1385 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1992) has died
,08-26 12:46:07.507   872  1385 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-26 12:46:07.508   872  1385 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-26 12:46:07.503  4240  4255 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-26 12:46:07.503  4240  4255 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 12:46:07.503  4240  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 12:46:07.503  4240  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 12:46:07.503  4240  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 12:46:07.503  4240  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 12:46:07.503  4240  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 12:46:07.503  4240  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 12:46:07.503  4240  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 12:46:07.503  4240  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 12:46:07.503  4240  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 12:46:07.503  4240  4255 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 12:46:07.503  4240  4255 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 12:46:07.503  4240  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 12:46:07.503  4240  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 12:46:07.503  4240  4255 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-26 12:46:07.503  4240  4255 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-26 12:46:07.503  4240  4255 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-26 12:46:07.503  4240  4255 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-26 12:46:07.503  4240  4255 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:46:07.503  4240  4255 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:46:07.503  4240  4255 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 12:46:07.510  4240  4255 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-26 12:46:07.510  4240  4255 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 12:46:07.510  4240  4255 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 12:46:07.510  4240  4255 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 12:46:07.510  4240  4255 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 12:46:07.510  4240  4255 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 12:46:07.510  4240  4255 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 12:46:07.510  4240  4255 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 12:46:07.510  4240  4255 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 12:46:07.510  4240  4255 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 12:46:07.510  4240  4255 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 12:46:07.510  4240  4255 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 12:46:07.510  4240  4255 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 12:46:07.510  4240  4255 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 12:46:07.510  4240  4255 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 12:46:07.510  4240  4255 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-26 12:46:07.510  4240  4255 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-26 12:46:07.510  4240  4255 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-26 12:46:07.510  4240  4255 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-26 12:46:07.510  4240  4255 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:46:07.510  4240  4255 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:46:07.510  4240  4255 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 12:46:07.517   872  1875 I ActivityManager: Process com.google.process.gapps (pid 1523) has died
08-26 12:46:07.517   872  1875 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
08-26 12:46:07.517   872  1875 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 10999ms
08-26 12:46:07.517   872  1875 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20999ms
,08-26 12:46:07.517   872  1875 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 30999ms
,08-26 12:46:07.531   872   885 I ActivityManager: Start proc 4292:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-26 12:46:07.545  1742  1742 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-26 12:46:07.553   872  2980 I ActivityManager: Start proc 4304:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
,08-26 12:46:07.576  4304  4304 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-26 12:46:07.586  4304  4304 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-26 12:46:07.587  4292  4292 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-26 12:46:07.587  4292  4292 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 12:46:07.587  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 12:46:07.587  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 12:46:07.587  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 12:46:07.587  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 12:46:07.587  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 12:46:07.587  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 12:46:07.587  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 12:46:07.587  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 12:46:07.587  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 12:46:07.587  4292  4292 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 12:46:07.587  4292  4292 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 12:46:07.587  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 12:46:07.587  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 12:46:07.587  4292  4292 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-26 12:46:07.587  4292  4292 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-26 12:46:07.587  4292  4292 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-26 12:46:07.587  4292  4292 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-26 12:46:07.587  4292  4292 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-26 12:46:07.587  4292  4292 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-26 12:46:07.587  4292  4292 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-26 12:46:07.587  4292  4292 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 12:46:07.587  4292  4292 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 12:46:07.587  4292  4292 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:46:07.587  4292  4292 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:46:07.587  4292  4292 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 12:46:07.587  4292  4292 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 12:46:07.587  4292  4292 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 12:46:07.587  4292  4292 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 12:46:07.588  4292  4292 D AndroidRuntime: Shutting down VM
08-26 12:46:07.588  4304  4304 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-26 12:46:07.588  4304  4304 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 12:46:07.588  4304  4304 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 12:46:07.588  4304  4304 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 12:46:07.588  4304  4304 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 12:46:07.588  4304  4304 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 12:46:07.588  4304  4304 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 12:46:07.588  4304  4304 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 12:46:07.588  4304  4304 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 12:46:07.588  4304  4304 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 12:46:07.588  4304  4304 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 12:46:07.588  4304  4304 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 12:46:07.588  4304  4304 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 12:46:07.588  4304  4304 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 12:46:07.588  4304  4304 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 12:46:07.588  4304  4304 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-26 12:46:07.588  4304  4304 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-26 12:46:07.588  4304  4304 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-26 12:46:07.588  4304  4304 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-26 12:46:07.588  4304  4304 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-26 12:46:07.588  4304  4304 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-26 12:46:07.588  4304  4304 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-26 12:46:07.588  4304  4304 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 12:46:07.588  4304  4304 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 12:46:07.588  4304  4304 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:46:07.588  4304  4304 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:46:07.588  4304  4304 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 12:46:07.588  4304  4304 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 12:46:07.588  4304  4304 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 12:46:07.588  4304  4304 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 12:46:07.588  4304  4304 D AndroidRuntime: Shutting down VM
,08-26 12:46:07.589  1742  1742 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-26 12:46:07.589  1742  1742 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-26 12:46:07.589  4304  4304 E AndroidRuntime: FATAL EXCEPTION: main
08-26 12:46:07.589  4304  4304 E AndroidRuntime: Process: com.google.process.gapps, PID: 4304
08-26 12:46:07.589  4304  4304 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 12:46:07.589  4304  4304 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-26 12:46:07.589  4304  4304 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-26 12:46:07.589  4304  4304 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-26 12:46:07.589  4304  4304 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 12:46:07.589  4304  4304 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 12:46:07.589  4304  4304 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:46:07.589  4304  4304 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:46:07.589  4304  4304 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 12:46:07.589  4304  4304 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 12:46:07.589  4304  4304 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 12:46:07.589  4304  4304 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 12:46:07.589  4304  4304 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 12:46:07.589  4304  4304 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 12:46:07.589  4304  4304 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 12:46:07.589  4304  4304 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 12:46:07.589  4304  4304 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 12:46:07.589  4304  4304 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 12:46:07.589  4304  4304 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 12:46:07.589  4304  4304 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 12:46:07.589  4304  4304 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 12:46:07.589  4304  4304 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 12:46:07.589  4304  4304 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 12:46:07.589  4304  4304 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 12:46:07.589  4304  4304 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 12:46:07.589  4304  4304 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 12:46:07.589  4304  4304 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-26 12:46:07.589  4304  4304 E AndroidRuntime: 	at com.google.android.gsf.gservices.Gservice,sProvider.onCreate(GservicesProvider.java:185)
08-26 12:46:07.589  4304  4304 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-26 12:46:07.589  4304  4304 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-26 12:46:07.589  4304  4304 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-26 12:46:07.589  4304  4304 E AndroidRuntime: 	... 10 more
,08-26 12:46:07.597  1742  1742 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-26 12:46:07.597  1742  1742 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-26 12:46:07.600   872  4318 E DropBoxManagerService: Can't write: system_app_crash
08-26 12:46:07.600   872  4318 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-26 12:46:07.600   872  4318 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 12:46:07.600   872  4318 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 12:46:07.600   872  4318 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 12:46:07.600   872  4318 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 12:46:07.600   872  4318 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 12:46:07.600   872  4318 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 12:46:07.600   872  4318 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 12:46:07.600   872  4318 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 12:46:07.600   872  4318 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 12:46:07.600   872  4318 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 12:46:07.600   872  4318 E DropBoxManagerService: 	... 5 more
,08-26 12:46:07.602  1742  4319 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-26 12:46:07.606  4292  4292 E AndroidRuntime: FATAL EXCEPTION: main
08-26 12:46:07.606  4292  4292 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4292
08-26 12:46:07.606  4292  4292 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 12:46:07.606  4292  4292 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-26 12:46:07.606  4292  4292 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-26 12:46:07.606  4292  4292 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-26 12:46:07.606  4292  4292 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 12:46:07.606  4292  4292 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 12:46:07.606  4292  4292 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:46:07.606  4292  4292 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:46:07.606  4292  4292 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 12:46:07.606  4292  4292 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 12:46:07.606  4292  4292 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 12:46:07.606  4292  4292 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 12:46:07.606  4292  4292 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 12:46:07.606  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 12:46:07.606  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 12:46:07.606  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 12:46:07.606  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 12:46:07.606  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 12:46:07.606  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 12:46:07.606  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 12:46:07.606  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 12:46:07.606  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 12:46:07.606  4292  4292 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 12:46:07.606  4292  4292 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 12:46:07.606  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 12:46:07.606  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 12:46:07.606  4292  4292 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-26 12:46:07.606  4292  4292 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-26 12:46:07.606  4292  4292 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-26 12:46:07.606  4292  4292 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-26 12:46:07.606  4292  4292 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-26 12:46:07.606  4292  4292 E AndroidRuntime: 	... 10 more
,08-26 12:46:07.608  4304  4304 I Process : Sending signal. PID: 4304 SIG: 9
,08-26 12:46:07.608   872  2984 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-26 12:46:07.610   872  4321 E DropBoxManagerService: Can't write: system_app_crash
08-26 12:46:07.610   872  4321 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-26 12:46:07.610   872  4321 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 12:46:07.610   872  4321 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 12:46:07.610   872  4321 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 12:46:07.610   872  4321 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 12:46:07.610   872  4321 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 12:46:07.610   872  4321 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 12:46:07.610   872  4321 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 12:46:07.610   872  4321 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 12:46:07.610   872  4321 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 12:46:07.610   872  4321 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 12:46:07.610   872  4321 E DropBoxManagerService: 	... 5 more
,08-26 12:46:07.611  4292  4292 I Process : Sending signal. PID: 4292 SIG: 9
,08-26 12:46:07.616  1742  4319 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
08-26 12:46:07.616  1742  4319 E AndroidRuntime: Process: com.google.android.gms, PID: 1742
08-26 12:46:07.616  1742  4319 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 12:46:07.616  1742  4319 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-26 12:46:07.616  1742  4319 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-26 12:46:07.616  1742  4319 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-26 12:46:07.616  1742  4319 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-26 12:46:07.616  1742  4319 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-26 12:46:07.616  1742  4319 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
08-26 12:46:07.616  1742  4319 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
08-26 12:46:07.616  1742  4319 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
08-26 12:46:07.616  1742  4319 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
08-26 12:46:07.616  1742  4319 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-26 12:46:07.616  1742  4319 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-26 12:46:07.616  1742  4319 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
08-26 12:46:07.616  1742  4319 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
08-26 12:46:07.616  1742  4319 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
08-26 12:46:07.616  1742  4319 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
08-26 12:46:07.616  1742  4319 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 12:46:07.616  1742  4319 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 12:46:07.616  1742  4319 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
08-26 12:46:07.618   872  1313 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
08-26 12:46:07.618   872  4323 E DropBoxManagerService: Can't write: system_app_crash
08-26 12:46:07.618   872  4323 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-26 12:46:07.618   872  4323 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 12:46:07.618   872  4323 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 12:46:07.618   872  4323 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 12:46:07.618   872  4323 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 12:46:07.618   872  4323 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 12:46:07.618   872  4323 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 12:46:07.618   872  4323 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 12:46:07.618   872  4323 E DropBoxManagerSe,rvice: 	at libcore.io.Posix.open(Native Method)
08-26 12:46:07.618   872  4323 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 12:46:07.618   872  4323 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 12:46:07.618   872  4323 E DropBoxManagerService: 	... 5 more
08-26 12:46:07.619  1742  4319 I Process : Sending signal. PID: 1742 SIG: 9
,08-26 12:46:07.640   872  1385 I ActivityManager: Process com.google.process.gapps (pid 4304) has died
,08-26 12:46:07.640   872  1385 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{ebca417 u0 com.google.android.gms/.config.ConfigService}
,08-26 12:46:07.640   872  1385 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{9e18f26 u0 com.google.android.gms/.auth.GetToken}
08-26 12:46:07.641   872  1385 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{70d0192 u0 com.google.android.gms/.gcm.GcmService}
,08-26 12:46:07.641   872  1385 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{4a77c19 u0 com.google.android.gms/.clearcut.service.ClearcutLoggerService}
08-26 12:46:07.645  4240  4255 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-26 12:46:07.651  4240  4272 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-26 12:46:07.651  4240  4272 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 12:46:07.651  4240  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 12:46:07.651  4240  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 12:46:07.651  4240  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 12:46:07.651  4240  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 12:46:07.651  4240  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 12:46:07.651  4240  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 12:46:07.651  4240  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 12:46:07.651  4240  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 12:46:07.651  4240  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 12:46:07.651  4240  4272 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 12:46:07.651  4240  4272 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 12:46:07.651  4240  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 12:46:07.651  4240  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 12:46:07.651  4240  4272 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-26 12:46:07.651  4240  4272 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-26 12:46:07.651  4240  4272 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-26 12:46:07.651  4240  4272 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-26 12:46:07.651  4240  4272 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-26 12:46:07.651  4240  4272 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-26 12:46:07.651  4240  4272 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-26 12:46:07.651  4240  4272 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:46:07.651  4240  4272 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:46:07.651  4240  4272 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 12:46:07.652  4240  4272 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-26 12:46:07.652  4240  4272 E AndroidRuntime: Process: android.process.acore, PID: 4240
08-26 12:46:07.652  4240  4272 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 12:46:07.652  4240  4272 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 12:46:07.652  4240  4272 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 12:46:07.652  4240  4272 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 12:46:07.652  4240  4272 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 12:46:07.652  4240  4272 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 12:46:07.652  4240  4272 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 12:46:07.652  4240  4272 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 12:46:07.652  4240  4272 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 12:46:07.652  4240  4272 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 12:46:07.652  4240  4272 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 12:46:07.652  4240  4272 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 12:46:07.652  4240  4272 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 12:46:07.652  4240  4272 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 12:46:07.652  4240  4272 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-26 12:46:07.652  4240  4272 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-26 12:46:07.652  4240  4272 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-26 12:46:07.652  4240  4272 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-26 12:46:07.652  4240  4272 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-26 12:46:07.652  4240  4272 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-26 12:46:07.652  4240  4272 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-26 12:46:07.652  4240  4272 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:46:07.652  4240  4272 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 12:46:07.652  4240  4272 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 12:46:07.653  4240  4255 I Process : Sending signal. PID: 4240 SIG: 9

```
