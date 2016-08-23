#### Test 817387961e8b1e5_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-23 23:11:51.021  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 23:11:51.029  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-23 23:11:51.032  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-23 23:11:51.064  1504  2041 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-23 23:11:51.064  1504  2041 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-23 23:11:51.064  1504  2041 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 23:11:51.065  1504  2041 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-23 23:11:51.082  3524  3524 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-23 23:11:51.083  3524  3524 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-23 23:11:51.083  3524  3524 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-23 23:11:51.608  3792  3792 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-23 23:11:51.613  3792  3792 D AndroidRuntime: CheckJNI is OFF
08-23 23:11:51.649  3792  3792 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-23 23:11:51.693  3792  3792 I Radio-JNI: register_android_hardware_Radio DONE
08-23 23:11:51.713  3792  3792 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-23 23:11:51.718   874  2352 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-23 23:11:51.757  1980  1992 W SearchService: Abort, client detached.
08-23 23:11:51.760  1980  2335 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@4236d39
08-23 23:11:51.761  1980  1980 I HotwordDetector: Closing mic
08-23 23:11:51.761  1980  2344 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-23 23:11:51.773  3792  3792 D AndroidRuntime: Shutting down VM
08-23 23:11:51.812   376  2353 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-23 23:11:51.813   376  2353 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-23 23:11:51.816   874   884 I ActivityManager: Start proc 3801:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-23 23:11:51.820   376  1279 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-23 23:11:51.824  1980  2340 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-23 23:11:51.824  1980  2343 I MicroRecognitionRnrImpl: Detection finished
08-23 23:11:51.838   874  1310 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2412
08-23 23:11:51.935  3801  3801 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-23 23:11:51.985  3801  3801 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-23 23:11:52.006  3801  3801 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4164-4167)
,08-23 23:11:52.006  3801  3801 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-23 23:11:52.028  3801  3801 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {29b0893}
,08-23 23:11:52.029  3801  3801 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-23 23:11:52.029  3801  3801 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-23 23:11:52.038  3801  3801 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-23 23:11:52.040  3801  3801 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-23 23:11:52.059  3801  3801 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-23 23:11:52.073  3801  3801 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-23 23:11:52.073  3801  3801 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-23 23:11:52.073  3801  3801 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-23 23:11:52.073  3801  3801 I Adreno  : Build Date                       : 10/20/15
08-23 23:11:52.073  3801  3801 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-23 23:11:52.073  3801  3801 I Adreno  : Local Branch                     : M14
08-23 23:11:52.073  3801  3801 I Adreno  : Remote Branch                    : 
08-23 23:11:52.073  3801  3801 I Adreno  : Remote Branch                    : 
08-23 23:11:52.073  3801  3801 I Adreno  : Reconstruct Branch               : 
,08-23 23:11:52.136   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3b3081e:true
,08-23 23:11:52.183  3801  3801 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-23 23:11:52.200  3801  3801 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-23 23:11:52.303  3801  3841 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-23 23:11:52.321  3801  3827 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-23 23:11:52.374  3801  3841 I OpenGLRenderer: Initialized EGL, version 1.4
,08-23 23:11:52.479   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +704ms
,08-23 23:11:52.482  1863  1863 I Keyboard.Facilitator: onFinishInput()
,08-23 23:11:52.620  3801  3801 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3801
,08-23 23:11:52.656   874   885 I ActivityManager: Killing 3214:com.google.android.gm/u0a78 (adj 15): empty #17
,08-23 23:11:52.709   874   885 I ActivityManager: Killing 3088:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,08-23 23:11:52.831  3801  3801 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-23 23:11:53.000  3801  3843 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1697646288
,08-23 23:11:53.026  3801  3843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 23:11:53.026  3801  3843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 23:11:53.026  3801  3843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 23:11:53.026  3801  3843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 23:11:53.026  3801  3843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-23 23:11:53.027  3801  3843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68a64a7 added. We now have 1 listener(s)
,08-23 23:11:53.032  3801  3843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-23 23:11:53.033  3801  3843 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-23 23:11:53.035  3801  3843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 23:11:53.035  3801  3843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 23:11:53.047  3801  3843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-23 23:11:53.047  3801  3843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 23:11:53.047  3801  3843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 23:11:53.047  3801  3843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-23 23:11:53.047  3801  3843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 23:11:53.047  3801  3843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 23:11:53.047  3801  3843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 23:11:53.047  3801  3843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 23:11:53.047  3801  3843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 23:11:53.047  3801  3843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 23:11:53.047  3801  3843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 23:11:53.047  3801  3843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 23:11:53.047  3801  3843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 23:11:53.047  3801  3843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-23 23:11:53.047  3801  3843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e52f5f2 added. We now have 1 listener(s)
,08-23 23:11:53.048  3801  3843 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 23:11:53.054   874  1311 D WifiService: New client listening to asynchronous messages
,08-23 23:11:53.055  3801  3843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 23:11:53.055  3801  3843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-23 23:11:53.056  3801  3843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-23 23:11:53.056  3801  3843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-23 23:11:53.056  3801  3843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-23 23:11:53.064  3801  3843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 23:11:53.065  3801  3843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-23 23:11:53.081  3801  3843 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-23 23:11:53.083  3801  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 23:11:53.083  3801  3843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:11:53.083  3801  3843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:11:53.083  3801  3843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 23:11:53.083  3801  3843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 23:11:53.083  3801  3843 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 23:11:53.083  3801  3843 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 23:11:53.083  3801  3843 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 23:11:53.083  3801  3843 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-23 23:11:53.084  3801  3843 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 23:11:53.087  3801  3843 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-23 23:11:53.229  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 23:11:53.232  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 23:11:53.236  3801  3801 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-23 23:11:53.670  3801  3811 I art     : Background sticky concurrent mark sweep GC freed 72046(6MB) AllocSpace objects, 17(1116KB) LOS objects, 27% free, 23MB/32MB, paused 2.458ms total 136.801ms
,08-23 23:11:54.490  3801  3851 W jxcore-log: Initializing JXcore engine
,08-23 23:11:54.490  3801  3851 W jxcore-log: JXcore engine is ready
,08-23 23:11:54.534  3851  3851 W Thread-325: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8787 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-23 23:11:54.534  3851  3851 W Thread-325: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10020]" dev="sockfs" ino=10020 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-23 23:11:54.534  3851  3851 W Thread-325: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-23 23:11:54.534  3851  3851 W Thread-325: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24220]" dev="sockfs" ino=24220 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-23 23:11:54.549  3801  3851 W jxcore-log: Starting JXcore engine
,08-23 23:11:54.644  3801  3851 W jxcore-log: Platform android
08-23 23:11:54.644  3801  3851 W jxcore-log: 
,08-23 23:11:54.644  3801  3851 W jxcore-log: Process ARCH arm
08-23 23:11:54.644  3801  3851 W jxcore-log: 
,08-23 23:11:54.921  3801  3851 I jxcore-log: JXcore Cordova bridge is ready!
08-23 23:11:54.921  3801  3851 I jxcore-log: 
,08-23 23:11:54.921  3801  3851 W jxcore-log: JXcore engine is started
,08-23 23:11:54.932  3801  3843 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-23 23:11:54.937  3801  3801 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-23 23:11:56.886  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 23:11:56.890  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 23:11:56.918  1504  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-23 23:11:56.918  1504  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-23 23:11:56.918  1504  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 23:11:56.918  1504  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 23:11:56.938  2994  3854 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-23 23:11:56.938  2994  3854 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-23 23:11:56.938  2994  3854 E HttpOperation: 	at jdm.a(PG:82)
08-23 23:11:56.938  2994  3854 E HttpOperation: 	at jcs.o(PG:406)
08-23 23:11:56.938  2994  3854 E HttpOperation: 	at jcn.a(PG:1379)
08-23 23:11:56.938  2994  3854 E HttpOperation: 	at jcs.i(PG:143)
08-23 23:11:56.938  2994  3854 E HttpOperation: 	at blb.a(PG:3937)
08-23 23:11:56.938  2994  3854 E HttpOperation: 	at czp.a(PG:18188)
08-23 23:11:56.938  2994  3854 E HttpOperation: 	at czp.a(PG:9081)
08-23 23:11:56.938  2994  3854 E HttpOperation: 	at czq.run(PG:1686)
08-23 23:11:56.938  2994  3854 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 23:11:56.938  2994  3854 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 23:11:56.938  2994  3854 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 23:11:56.938  2994  3854 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 23:11:56.938  2994  3854 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-23 23:11:56.938  2994  3854 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 23:11:56.938  2994  3854 E HttpOperation: 	at jdj.a(PG:4091)
08-23 23:11:56.938  2994  3854 E HttpOperation: 	at jdj.a(PG:1125)
08-23 23:11:56.938  2994  3854 E HttpOperation: 	at jdm.a(PG:77)
08-23 23:11:56.938  2994  3854 E HttpOperation: 	... 12 more
08-23 23:11:56.938  2994  3854 E HttpOperation: Caused by: faj: BadAuthentication
08-23 23:11:56.938  2994  3854 E HttpOperation: 	at fal.a(PG:38)
08-23 23:11:56.938  2994  3854 E HttpOperation: 	at jdj.a(PG:4089)
08-23 23:11:56.938  2994  3854 E HttpOperation: 	... 14 more
,08-23 23:11:57.007  1504  3148 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-23 23:11:57.007  1504  3148 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-23 23:11:57.008  1504  3148 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 23:11:57.009  1504  3148 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 23:11:57.030  2994  3854 E HttpOperation: [getmobileexperiments] Unexpected exception
08-23 23:11:57.030  2994  3854 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-23 23:11:57.030  2994  3854 E HttpOperation: 	at jdm.a(PG:82)
08-23 23:11:57.030  2994  3854 E HttpOperation: 	at jcs.o(PG:406)
08-23 23:11:57.030  2994  3854 E HttpOperation: 	at jcn.a(PG:1379)
08-23 23:11:57.030  2994  3854 E HttpOperation: 	at jcs.i(PG:143)
08-23 23:11:57.030  2994  3854 E HttpOperation: 	at hec.a(PG:42)
08-23 23:11:57.030  2994  3854 E HttpOperation: 	at hee.a(PG:102)
08-23 23:11:57.030  2994  3854 E HttpOperation: 	at czr.a(PG:65)
08-23 23:11:57.030  2994  3854 E HttpOperation: 	at kka.a(PG:108)
08-23 23:11:57.030  2994  3854 E HttpOperation: 	at czp.a(PG:19176)
08-23 23:11:57.030  2994  3854 E HttpOperation: 	at czp.a(PG:9081)
08-23 23:11:57.030  2994  3854 E HttpOperation: 	at czq.run(PG:1686)
08-23 23:11:57.030  2994  3854 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 23:11:57.030  2994  3854 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 23:11:57.030  2994  3854 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 23:11:57.030  2994  3854 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 23:11:57.030  2994  3854 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-23 23:11:57.030  2994  3854 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 23:11:57.030  2994  3854 E HttpOperation: 	at jdj.a(PG:4091)
08-23 23:11:57.030  2994  3854 E HttpOperation: 	at jdj.a(PG:1125)
08-23 23:11:57.030  2994  3854 E HttpOperation: 	at jdm.a(PG:77)
08-23 23:11:57.030  2994  3854 E HttpOperation: 	... 15 more
08-23 23:11:57.030  2994  3854 E HttpOperation: Caused by: faj: BadAuthentication
08-23 23:11:57.030  2994  3854 E HttpOperation: 	at fal.a(PG:38)
08-23 23:11:57.030  2994  3854 E HttpOperation: 	at jdj.a(PG:4089)
08-23 23:11:57.030  2994  3854 E HttpOperation: 	... 17 more
,08-23 23:11:57.031  2994  3854 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-23 23:11:57.031  2994  3854 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-23 23:11:57.031  2994  3854 E ExperimentLoader: 	at jdm.a(PG:82)
08-23 23:11:57.031  2994  3854 E ExperimentLoader: 	at jcs.o(PG:406)
08-23 23:11:57.031  2994  3854 E ExperimentLoader: 	at jcn.a(PG:1379)
08-23 23:11:57.031  2994  3854 E ExperimentLoader: 	at jcs.i(PG:143)
08-23 23:11:57.031  2994  3854 E ExperimentLoader: 	at hec.a(PG:42)
08-23 23:11:57.031  2994  3854 E ExperimentLoader: 	at hee.a(PG:102)
08-23 23:11:57.031  2994  3854 E ExperimentLoader: 	at czr.a(PG:65)
08-23 23:11:57.031  2994  3854 E ExperimentLoader: 	at kka.a(PG:108)
08-23 23:11:57.031  2994  3854 E ExperimentLoader: 	at czp.a(PG:19176)
08-23 23:11:57.031  2994  3854 E ExperimentLoader: 	at czp.a(PG:9081)
08-23 23:11:57.031  2994  3854 E ExperimentLoader: 	at czq.run(PG:1686)
08-23 23:11:57.031  2994  3854 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 23:11:57.031  2994  3854 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 23:11:57.031  2994  3854 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 23:11:57.031  2994  3854 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 23:11:57.031  2994  3854 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-23 23:11:57.031  2994  3854 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 23:11:57.031  2994  3854 E ExperimentLoader: 	at jdj.a(PG:4091)
08-23 23:11:57.031  2994  3854 E ExperimentLoader: 	at jdj.a(PG:1125)
08-23 23:11:57.031  2994  3854 E ExperimentLoader: 	at jdm.a(PG:77)
08-23 23:11:57.031  2994  3854 E ExperimentLoader: 	... 15 more
08-23 23:11:57.031  2994  3854 E ExperimentLoader: Caused by: faj: BadAuthentication
08-23 23:11:57.031  2994  3854 E ExperimentLoader: 	at fal.a(PG:38)
08-23 23:11:57.031  2994  3854 E ExperimentLoader: 	at jdj.a(PG:4089)
08-23 23:11:57.031  2994  3854 E ExperimentLoader: 	... 17 more
,08-23 23:11:57.130   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 128817, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-23 23:11:57.755   874  2081 D NetlinkSocketObserver: NeighborEvent{elapsedMs=129916, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-23 23:12:10.961  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-23 23:12:10.961  3801  3851 I jxcore-log: 
,08-23 23:12:10.964  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-23 23:12:10.964  3801  3851 I jxcore-log: 
,08-23 23:12:10.978  3801  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 23:12:10.978  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:12:10.978  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:12:10.978  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 23:12:10.978  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 23:12:10.978  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 23:12:10.978  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 23:12:10.978  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 23:12:10.983  3801  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 23:12:10.986  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-23 23:12:10.986  3801  3851 I jxcore-log: 
,08-23 23:12:10.988  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-23 23:12:10.988  3801  3851 I jxcore-log: 
,08-23 23:12:11.316  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 23:12:11.340  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 23:12:11.344  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 23:12:11.395  1504  2041 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-23 23:12:11.395  1504  2041 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-23 23:12:11.396  1504  2041 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 23:12:11.396  1504  2041 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 23:12:11.428  3524  3524 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-23 23:12:11.429  3524  3524 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-23 23:12:11.429  3524  3524 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-23 23:12:11.446  3801  3851 I jxcore-log: Running unit tests
08-23 23:12:11.446  3801  3851 I jxcore-log: 
,08-23 23:12:11.448  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-23 23:12:11.448  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc5f5a added. We now have 2 listener(s)
,08-23 23:12:11.452  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-23 23:12:11.452  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 23:12:11.452  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 23:12:11.452  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 23:12:11.452  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ede358b added. We now have 2 listener(s)
08-23 23:12:11.452  3801  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 23:12:11.453  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 23:12:11.454  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 23:12:11.459  3801  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 23:12:11.459  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:12:11.459  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:12:11.459  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 23:12:11.459  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 23:12:11.459  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 23:12:11.459  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 23:12:11.459  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 23:12:11.460  3801  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 23:12:11.460  3801  3851 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 23:12:11.460  3801  3851 D ExecuteNativeTests: Running unit tests
,08-23 23:12:11.462  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 23:12:11.464  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 23:12:11.525  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-23 23:12:11.525  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3335f1 added. We now have 3 listener(s)
,08-23 23:12:11.526  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-23 23:12:11.526  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 23:12:11.526  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 23:12:11.526  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 23:12:11.527  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 added. We now have 3 listener(s)
08-23 23:12:11.527  3801  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 23:12:11.527  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 23:12:11.530  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 23:12:11.533  3801  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 23:12:11.533  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:12:11.533  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:12:11.533  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 23:12:11.533  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 23:12:11.533  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 23:12:11.533  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 23:12:11.533  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 23:12:11.535  3801  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 23:12:11.535  3801  3851 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 23:12:11.538  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-23 23:12:11.539  3801  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-23 23:12:11.540  3801  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-23 23:12:11.540  3801  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-23 23:12:11.541  3801  3851 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-23 23:12:11.542  3801  3851 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-23 23:12:11.542  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-23 23:12:11.542  3801  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-23 23:12:11.543  3801  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-23 23:12:11.543  3801  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-23 23:12:11.544  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 23:12:11.543  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 23:12:11.544  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 23:12:11.544  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 23:12:11.545  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 23:12:11.545  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:11.545  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-23 23:12:11.545  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 23:12:11.545  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3335f1 removed from the list
08-23 23:12:11.545  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:12:11.545  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 removed from the list
,08-23 23:12:11.549  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 23:12:11.549  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-23 23:12:11.549  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:11.550  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:11.550  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:11.552  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 23:12:11.552  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 23:12:11.552  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:12:11.552  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
08-23 23:12:11.554  3801  3851 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-23 23:12:11.555  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 23:12:11.555  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 23:12:11.555  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 23:12:11.555  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 23:12:11.555  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:11.555  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:11.555  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3335f1 not in the list
,08-23 23:12:11.555  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:12:11.555  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
08-23 23:12:11.555  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-23 23:12:11.555  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:11.555  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 23:12:11.555  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:11.556  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:11.558  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 23:12:11.558  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 23:12:11.558  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:12:11.558  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
08-23 23:12:11.562  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-23 23:12:11.562  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-23 23:12:11.562  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-23 23:12:11.562  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-23 23:12:11.562  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-23 23:12:11.563  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-23 23:12:11.563  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-23 23:12:11.563  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-23 23:12:11.563  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-23 23:12:11.563  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-23 23:12:11.563  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-23 23:12:11.563  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-23 23:12:11.563  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-23 23:12:11.563  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-23 23:12:11.563  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-23 23:12:11.563  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-23 23:12:11.563  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-23 23:12:11.563  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-23 23:12:11.563  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-23 23:12:11.563  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-23 23:12:11.563  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-23 23:12:11.563  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-23 23:12:11.563  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-23 23:12:11.564  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-23 23:12:11.564  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-23 23:12:11.564  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-23 23:12:11.564  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-23 23:12:11.564  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-23 23:12:11.564  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-23 23:12:11.564  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-23 23:12:11.564  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-23 23:12:11.564  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 23:12:11.564  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 23:12:11.564  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 23:12:11.564  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 23:12:11.564  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:11.564  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:11.565  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3335f1 not in the list
08-23 23:12:11.565  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:12:11.565  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
08-23 23:12:11.565  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-23 23:12:11.565  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:11.565  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:11.565  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:11.565  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:11.566  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 23:12:11.566  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 23:12:11.566  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:12:11.566  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
08-23 23:12:11.566  3801  3851 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-23 23:12:11.569  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 23:12:11.576  3801  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 23:12:11.576  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:12:11.576  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:12:11.576  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 23:12:11.576  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 23:12:11.576  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 23:12:11.576  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 23:12:11.576  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 23:12:11.577  3801  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 23:12:11.577  3801  3851 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 23:12:11.578  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 23:12:11.578  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 23:12:11.578  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 23:12:11.578  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 23:12:11.578  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-23 23:12:11.582  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 23:12:11.584  3801  3851 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-23 23:12:11.584  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-23 23:12:11.588  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 23:12:11.589  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-23 23:12:11.590  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-23 23:12:11.590  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-23 23:12:11.592  3801  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-23 23:12:11.595  3801  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-23 23:12:11.595  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-23 23:12:11.595  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-23 23:12:11.596  3801  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-23 23:12:11.597  3801  3851 D BluetoothAdapter: STATE_ON
08-23 23:12:11.601  2695  2709 D BtGatt.GattService: registerClient() - UUID=44f08dd9-fea7-467e-8c6f-efce02de6e40
,08-23 23:12:11.603  2695  2749 D BtGatt.GattService: onClientRegistered() - UUID=44f08dd9-fea7-467e-8c6f-efce02de6e40, clientIf=5
08-23 23:12:11.605  3801  3812 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-23 23:12:11.605  2695  2708 D BtGatt.GattService: start scan with filters
08-23 23:12:11.611  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-23 23:12:11.611  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-23 23:12:11.611  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-23 23:12:11.611  2695  2755 D BtGatt.ScanManager: handling starting scan
08-23 23:12:11.611  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-23 23:12:11.616  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-23 23:12:11.616  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-23 23:12:11.616  3801  3801 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-23 23:12:11.617  2695  2755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2286885
08-23 23:12:11.617  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-23 23:12:11.621  3801  3851 I io.jxcore.node.ConnectionHelper: start: OK
08-23 23:12:11.628  2695  2749 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-23 23:12:11.628  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 23:12:11.629  2695  2755 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-23 23:12:11.637  2695  2749 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-23 23:12:11.637  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 23:12:11.638  2695  2755 D BtGatt.ScanManager: Starting BLE batch scan
08-23 23:12:11.638  2695  2755 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-23 23:12:11.668  2695  2749 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-23 23:12:11.668  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 23:12:11.678  2695  2749 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-23 23:12:11.678  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 23:12:12.118  3801  3801 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
08-23 23:12:12.118  3801  3801 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 23:12:12.119  3801  3801 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-23 23:12:13.184  2695  2695 D BtGatt.ScanManager: awakened up at time 145346
,08-23 23:12:13.188  2695  2755 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-23 23:12:13.221  2695  2749 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,08-23 23:12:13.221  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 23:12:13.221  2695  2749 D BtGatt.GattService: current time is 145383832199
08-23 23:12:13.222  2695  2749 D BtGatt.GattService: Batch record : [-102, -14, -36, 14, 85, 121, 1, -128, -98, 4, 0, 24, 2, 1, 26, 20, -1, 76, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 4, 0, 0, 0, 0, 0, 116, -43, -111, -91, -20, -29, 1, -128, -87, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -85, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -85, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -90, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -62, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -86, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-23 23:12:13.223  2695  2749 D BtGatt.GattService: ScanRecord : [2, 1, 26, 20, -1, 76, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 4, 0, 0, 0, 0]
,08-23 23:12:13.224  2695  2749 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91],
08-23 23:12:13.225  2695  2749 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-23 23:12:13.225  2695  2749 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-23 23:12:13.225  2695  2749 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-23 23:12:13.225  2695  2749 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
08-23 23:12:13.225  2695  2749 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-23 23:12:14.727  2695  2695 D BtGatt.ScanManager: awakened up at time 146889
08-23 23:12:14.730  2695  2755 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-23 23:12:14.741  2695  2749 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-23 23:12:14.742  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 23:12:16.244  2695  2695 D BtGatt.ScanManager: awakened up at time 148406
,08-23 23:12:16.248  2695  2755 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-23 23:12:16.276  2695  2749 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
08-23 23:12:16.276  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 23:12:16.276  2695  2749 D BtGatt.GattService: current time is 148438870444
,08-23 23:12:16.277  2695  2749 D BtGatt.GattService: Batch record : [-102, -14, -36, 14, 85, 121, 1, -128, -105, 3, 0, 24, 2, 1, 26, 20, -1, 76, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 4, 0, 0, 0, 0, 0, 116, -43, -111, -91, -20, -29, 1, -128, -83, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0]
,08-23 23:12:16.278  2695  2749 D BtGatt.GattService: ScanRecord : [2, 1, 26, 20, -1, 76, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 4, 0, 0, 0, 0]
,08-23 23:12:16.279  2695  2749 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,08-23 23:12:16.630  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 23:12:16.631  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-23 23:12:16.632  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-23 23:12:16.632  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:16.632  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-23 23:12:16.633  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-23 23:12:16.633  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 23:12:16.634  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-23 23:12:16.634  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-23 23:12:16.636  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-23 23:12:16.636  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-23 23:12:16.639  3801  3851 D BluetoothAdapter: STATE_ON
,08-23 23:12:16.642  2695  2709 D BtGatt.GattService: stopScan() - queue size =1
,08-23 23:12:16.645  2695  2881 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-23 23:12:16.647  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-23 23:12:16.648  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
08-23 23:12:16.648  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-23 23:12:16.648  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-23 23:12:16.649  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-23 23:12:16.653  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 23:12:16.654  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-23 23:12:16.655  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-23 23:12:16.657  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-23 23:12:16.659  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-23 23:12:16.663  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-23 23:12:16.663  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 23:12:16.664  3801  3801 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 23:12:16.665  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 23:12:16.665  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:16.665  2695  2749 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-23 23:12:16.665  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 23:12:16.666  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 23:12:16.666  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3335f1 not in the list
08-23 23:12:16.666  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:12:16.666  2695  2755 D BtGatt.ScanManager: stopping BLe Batch
08-23 23:12:16.666  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
08-23 23:12:16.666  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-23 23:12:16.667  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 23:12:16.678  2695  2749 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-23 23:12:16.678  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 23:12:16.679  2695  2755 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-23 23:12:16.715  2695  2749 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-23 23:12:16.716  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 23:12:16.716  2695  2749 D BtGatt.GattService: current time is 148878446610
,08-23 23:12:16.717  2695  2749 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -83, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -102, -14, -36, 14, 85, 121, 1, -128, -105, 8, 0, 24, 2, 1, 26, 20, -1, 76, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 4, 0, 0, 0, 0, 0, -46, -4, -117, 6, 105, -37, 1, -128, -92, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -82, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -91, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-23 23:12:16.718  2695  2749 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-23 23:12:16.719  2695  2749 D BtGatt.GattService: ScanRecord : [2, 1, 26, 20, -1, 76, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 4, 0, 0, 0, 0]
08-23 23:12:16.720  2695  2749 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-23 23:12:16.720  2695  2749 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-23 23:12:16.721  2695  2749 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-23 23:12:17.165  3801  3801 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-23 23:12:20.767   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-23 23:12:20.778  1863  1863 I Keyboard.Facilitator: onFinishInput()
,08-23 23:12:20.786   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-23 23:12:20.786   874   894 I Adreno  : Build Date                       : 10/20/15
08-23 23:12:20.786   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-23 23:12:20.786   874   894 I Adreno  : Local Branch                     : M14
08-23 23:12:20.786   874   894 I Adreno  : Remote Branch                    : 
08-23 23:12:20.786   874   894 I Adreno  : Remote Branch                    : 
08-23 23:12:20.786   874   894 I Adreno  : Reconstruct Branch               : 
,08-23 23:12:20.839   279  1303 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (319 us)
,08-23 23:12:21.481  3801  3801 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-23 23:12:21.481  3801  3801 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-23 23:12:21.515  3801  3801 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c0801 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@b0f93b0, 16908290=android.view.AbsSavedState$1@b0f93b0}, android:focusedViewId=100}]}]
,08-23 23:12:21.515  3801  3801 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-23 23:12:21.515  3801  3801 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-23 23:12:21.515  3801  3801 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-23 23:12:21.516   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-23 23:12:21.523   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-23 23:12:21.527   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-23 23:12:21.530   279   279 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
08-23 23:12:21.530   279   279 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-23 23:12:21.668  3801  3851 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-23 23:12:21.676  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 23:12:21.694  3801  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 23:12:21.694  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:12:21.694  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:12:21.694  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 23:12:21.694  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 23:12:21.694  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 23:12:21.694  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 23:12:21.694  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 23:12:21.703  3801  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 23:12:21.704  3801  3851 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 23:12:21.705  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 23:12:21.705  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 23:12:21.705  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-23 23:12:21.706  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 23:12:21.706  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-23 23:12:21.716  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 23:12:21.721  3801  3851 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-23 23:12:21.721  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-23 23:12:21.727  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 23:12:21.736  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-23 23:12:21.738  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-23 23:12:21.738  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-23 23:12:21.749  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-23 23:12:21.749  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-23 23:12:21.750  3801  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-23 23:12:21.751   279   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-23 23:12:21.752  3801  3851 D BluetoothAdapter: STATE_ON
08-23 23:12:21.753   279   279 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-23 23:12:21.758   874  1335 D SurfaceControl: Excessive delay in setPowerMode(): 231ms
08-23 23:12:21.762   874   894 I DreamManagerService: Entering dreamland.
,08-23 23:12:21.763   874   894 I PowerManagerService: Dozing...
,08-23 23:12:21.765  2695  2709 D BtGatt.GattService: registerClient() - UUID=96954950-2671-44fa-97dd-e7bb184e3ee4
,08-23 23:12:21.765   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-23 23:12:21.770  2695  2749 D BtGatt.GattService: onClientRegistered() - UUID=96954950-2671-44fa-97dd-e7bb184e3ee4, clientIf=5
,08-23 23:12:21.771  3801  3812 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-23 23:12:21.771  2695  2708 D BtGatt.GattService: start scan with filters
,08-23 23:12:21.776  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-23 23:12:21.776  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-23 23:12:21.776  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-23 23:12:21.776  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-23 23:12:21.777  2695  2755 D BtGatt.ScanManager: handling starting scan
08-23 23:12:21.779  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-23 23:12:21.780  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-23 23:12:21.780  3801  3801 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-23 23:12:21.781  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-23 23:12:21.786  2695  2749 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-23 23:12:21.786  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 23:12:21.786  2695  2755 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-23 23:12:21.786  3801  3851 I io.jxcore.node.ConnectionHelper: start: OK
,08-23 23:12:21.789  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 23:12:21.790  3801  3851 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-23 23:12:21.790  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-23 23:12:21.790  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-23 23:12:21.790  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:21.790  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-23 23:12:21.790  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-23 23:12:21.790  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 23:12:21.790  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 23:12:21.790  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-23 23:12:21.791  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-23 23:12:21.791  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-23 23:12:21.791  3801  3851 D BluetoothAdapter: STATE_ON
,08-23 23:12:21.792  2695  2749 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-23 23:12:21.792  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 23:12:21.792  2695  2755 D BtGatt.ScanManager: Starting BLE batch scan
08-23 23:12:21.792  2695  2709 D BtGatt.GattService: stopScan() - queue size =1
08-23 23:12:21.792  2695  2755 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-23 23:12:21.793  2695  2881 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-23 23:12:21.793  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 23:12:21.793  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-23 23:12:21.793  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-23 23:12:21.793  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-23 23:12:21.793  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-23 23:12:21.795  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 23:12:21.795  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-23 23:12:21.795  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-23 23:12:21.795  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-23 23:12:21.796  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 23:12:21.797  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 23:12:21.797  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:21.798  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 23:12:21.798  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3335f1 not in the list
08-23 23:12:21.798  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 23:12:21.798  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 23:12:21.798  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
08-23 23:12:21.798  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-23 23:12:21.798  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 23:12:21.798  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 23:12:21.798  3801  3801 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 23:12:21.798  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:21.798  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:21.799  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-23 23:12:21.799  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 23:12:21.800  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:12:21.800  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
,08-23 23:12:21.801  3801  3851 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-23 23:12:21.802  2695  2749 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-23 23:12:21.802  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 23:12:21.803  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 23:12:21.808  2695  2749 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-23 23:12:21.808  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 23:12:21.809  3801  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 23:12:21.809  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:12:21.809  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:12:21.809  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 23:12:21.809  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 23:12:21.809  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 23:12:21.809  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 23:12:21.809  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 23:12:21.811  3801  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 23:12:21.811  3801  3851 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 23:12:21.811  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 23:12:21.811  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-23 23:12:21.812  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 23:12:21.812  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 23:12:21.812  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-23 23:12:21.816  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 23:12:21.817  2695  2749 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-23 23:12:21.817  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 23:12:21.817  2695  2755 D BtGatt.ScanManager: stopping BLe Batch
,08-23 23:12:21.819  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 23:12:21.819  3801  3851 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-23 23:12:21.819  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-23 23:12:21.824  2695  2749 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-23 23:12:21.824  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 23:12:21.824  2695  2755 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-23 23:12:21.826  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-23 23:12:21.827  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-23 23:12:21.827  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-23 23:12:21.831  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-23 23:12:21.831  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-23 23:12:21.831  2695  2749 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-23 23:12:21.831  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 23:12:21.831  3801  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-23 23:12:21.833  3801  3851 D BluetoothAdapter: STATE_ON
08-23 23:12:21.835   376  1318 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
08-23 23:12:21.835   376  1318 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
08-23 23:12:21.837  2695  2709 D BtGatt.GattService: registerClient() - UUID=a9fe98ab-9b4a-48fa-874b-fd3f9f49215a
,08-23 23:12:21.837  2695  2749 D BtGatt.GattService: onClientRegistered() - UUID=a9fe98ab-9b4a-48fa-874b-fd3f9f49215a, clientIf=5
08-23 23:12:21.837  3801  3812 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-23 23:12:21.838  2695  2708 D BtGatt.GattService: start scan with filters
,08-23 23:12:21.842  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-23 23:12:21.842  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-23 23:12:21.842  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-23 23:12:21.842  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-23 23:12:21.842  2695  2755 D BtGatt.ScanManager: handling starting scan
,08-23 23:12:21.847   874  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,08-23 23:12:21.848  1906  3870 D NfcService: Discovery configuration equal, not updating.
,08-23 23:12:21.850  2695  2749 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-23 23:12:21.850  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 23:12:21.851  2695  2755 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-23 23:12:21.854  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 23:12:21.854  3801  3801 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 23:12:21.855  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-23 23:12:21.859   874  1310 E native  : do suspend false
,08-23 23:12:21.859  2695  2749 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-23 23:12:21.859  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 23:12:21.860  2695  2755 D BtGatt.ScanManager: Starting BLE batch scan
08-23 23:12:21.860  2695  2755 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-23 23:12:21.861  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-23 23:12:21.865  3801  3851 I io.jxcore.node.ConnectionHelper: start: OK
,08-23 23:12:21.873  2695  2749 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-23 23:12:21.873  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 23:12:21.878   874  1310 D WifiConfigStore: No blacklist allowed without epno enabled
,08-23 23:12:21.879  2695  2749 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-23 23:12:21.880  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 23:12:21.890   874  1310 D WifiConfigStore: Retrieve network priorities after PNO.
08-23 23:12:21.892   874  1310 E native  : do suspend true
,08-23 23:12:21.972   376  1280 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
08-23 23:12:21.973   376  1280 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-23 23:12:22.352   874  1310 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,08-23 23:12:22.356  3801  3801 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-23 23:12:22.357  3801  3801 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 23:12:22.357  3801  3801 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-23 23:12:23.387  2695  2695 D BtGatt.ScanManager: awakened up at time 155549
,08-23 23:12:23.390  2695  2755 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-23 23:12:23.440  2695  2749 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=8
,08-23 23:12:23.440  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 23:12:23.440  2695  2749 D BtGatt.GattService: current time is 155602493931
08-23 23:12:23.440  2695  2749 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -68, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -85, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -87, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -84, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -102, -14, -36, 14, 85, 121, 1, -128, -99, 7, 0, 24, 2, 1, 26, 20, -1, 76, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 4, 0, 0, 0, 0, 0, 81, 34, 97, 112, -14, -5, 1, -128, -89, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -78, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -69, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0]
08-23 23:12:23.441  2695  2749 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
08-23 23:12:23.441  2695  2749 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-23 23:12:23.441  2695  2749 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-23 23:12:23.441  2695  2749 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-23 23:12:23.442  2695  2749 D BtGatt.GattService: ScanRecord : [2, 1, 26, 20, -1, 76, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 4, 0, 0, 0, 0]
08-23 23:12:23.442  2695  2749 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-23 23:12:23.442  2695  2749 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-23 23:,12:23.442  2695  2749 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,08-23 23:12:23.622   874  2081 D NetlinkSocketObserver: NeighborEvent{elapsedMs=155784, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-23 23:12:24.947  2695  2695 D BtGatt.ScanManager: awakened up at time 157109
,08-23 23:12:24.953  2695  2755 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-23 23:12:24.962  2695  2749 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-23 23:12:24.962  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 23:12:26.064  2162  2627 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-23 23:12:26.464  2695  2695 D BtGatt.ScanManager: awakened up at time 158626
,08-23 23:12:26.469  2695  2755 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-23 23:12:26.517  2695  2749 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-23 23:12:26.518  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 23:12:26.518  2695  2749 D BtGatt.GattService: current time is 158680796844
,08-23 23:12:26.519  2695  2749 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -83, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -82, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -102, -14, -36, 14, 85, 121, 1, -128, -104, 2, 0, 24, 2, 1, 26, 20, -1, 76, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 4, 0, 0, 0, 0, 0, -46, -4, -117, 6, 105, -37, 1, -128, -93, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -82, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-23 23:12:26.520  2695  2749 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-23 23:12:26.521  2695  2749 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-23 23:12:26.522  2695  2749 D BtGatt.GattService: ScanRecord : [2, 1, 26, 20, -1, 76, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 4, 0, 0, 0, 0]
08-23 23:12:26.523  2695  2749 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-23 23:12:26.524  2695  2749 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-23 23:12:26.865  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 23:12:26.866  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-23 23:12:26.866  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-23 23:12:26.866  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:26.867  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-23 23:12:26.867  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-23 23:12:26.867  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 23:12:26.868  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 23:12:26.868  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-23 23:12:26.869  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-23 23:12:26.869  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-23 23:12:26.873  3801  3851 D BluetoothAdapter: STATE_ON
08-23 23:12:26.875  2695  2709 D BtGatt.GattService: stopScan() - queue size =1
,08-23 23:12:26.877  2695  2708 D BtGatt.GattService: unregisterClient() - clientIf=5
08-23 23:12:26.879  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 23:12:26.879  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-23 23:12:26.879  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-23 23:12:26.880  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-23 23:12:26.880  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-23 23:12:26.884  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 23:12:26.884  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-23 23:12:26.885  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-23 23:12:26.886  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-23 23:12:26.887  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-23 23:12:26.889  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-23 23:12:26.889  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 23:12:26.889  3801  3801 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 23:12:26.895  2695  2749 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-23 23:12:26.895  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 23:12:26.895  2695  2755 D BtGatt.ScanManager: stopping BLe Batch
,08-23 23:12:26.908  2695  2749 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-23 23:12:26.908  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 23:12:26.908  2695  2755 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-23 23:12:26.933  2695  2749 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,08-23 23:12:26.933  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 23:12:26.934  2695  2749 D BtGatt.GattService: current time is 159095977590
08-23 23:12:26.935  2695  2749 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -82, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -91, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-23 23:12:26.935  2695  2749 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-23 23:12:26.936  2695  2749 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-23 23:12:27.391  3801  3801 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-23 23:12:27.391  3801  3801 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 23:12:27.391  3801  3801 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-23 23:12:30.602  3731  3875 I BooksSync: Starting books sync for 61035162, extras: ade
,08-23 23:12:30.652  3731  3876 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-23 23:12:30.686  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 23:12:30.693  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 23:12:30.774  1504  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-23 23:12:30.775  1504  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-23 23:12:30.775  1504  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 23:12:30.776  1504  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 23:12:30.862  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 23:12:30.871  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 23:12:30.950  1504  2041 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-23 23:12:30.951  1504  2041 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-23 23:12:30.951  1504  2041 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 23:12:30.952  1504  2041 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 23:12:31.012  3731  3876 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-23 23:12:31.015  3731  3875 E BooksSync: Soft error
08-23 23:12:31.015  3731  3875 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-23 23:12:31.015  3731  3875 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-23 23:12:31.021  3731  3875 E BooksSync: Sync error
08-23 23:12:31.021  3731  3875 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-23 23:12:31.021  3731  3875 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-23 23:12:31.021  3731  3875 I BooksSync: Finished books sync
,08-23 23:12:31.036   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 162693, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-23 23:12:31.656  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 23:12:31.845   874  1310 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,08-23 23:12:31.892  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 23:12:31.892  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 23:12:31.892  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 23:12:31.893  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 23:12:31.893  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:31.893  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 23:12:31.893  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3335f1 not in the list
08-23 23:12:31.894  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:12:31.894  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
08-23 23:12:31.894  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-23 23:12:31.894  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:31.902  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:31.902  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:31.916  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 23:12:31.916  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 23:12:31.916  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:12:31.917  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
,08-23 23:12:31.918  3801  3851 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-23 23:12:31.920  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 23:12:31.921  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 23:12:31.921  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 23:12:31.921  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 23:12:31.922  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 23:12:31.922  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:31.922  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3335f1 not in the list
08-23 23:12:31.922  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:12:31.923  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
08-23 23:12:31.923  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 23:12:31.923  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:31.923  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:31.923  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:31.924  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 23:12:31.926  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-23 23:12:31.926  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 23:12:31.926  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:12:31.926  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
,08-23 23:12:31.927  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-23 23:12:31.927  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 23:12:31.928  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 23:12:31.928  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 23:12:31.928  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 23:12:31.928  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:31.928  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:31.928  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3335f1 not in the list
08-23 23:12:31.928  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 23:12:31.928  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
08-23 23:12:31.928  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-23 23:12:31.928  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:31.928  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:31.928  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:31.928  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:31.929  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 23:12:31.929  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 23:12:31.930  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:12:31.930  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
,08-23 23:12:31.930  3801  3851 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-23 23:12:31.930  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 23:12:31.931  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 23:12:31.931  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 23:12:31.931  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-23 23:12:31.931  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:31.931  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:31.931  1504  3878 I VacuumService: Vacuum at: now=1471986751931 tag=VacuumService
08-23 23:12:31.931  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3335f1 not in the list
08-23 23:12:31.931  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:12:31.931  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
08-23 23:12:31.931  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-23 23:12:31.931  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:31.931  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:31.931  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:31.932  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:31.932  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 23:12:31.932  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 23:12:31.933  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:12:31.933  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
08-23 23:12:31.933  3801  3851 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-23 23:12:31.933  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 23:12:31.934  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 23:12:31.934  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 23:12:31.934  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 23:12:31.934  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:31.934  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:31.934  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3335f1 not in the list
08-23 23:12:31.934  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:12:31.934  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
08-23 23:12:31.934  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 23:12:31.934  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:31.934  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:31.934  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:31.934  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:31.936  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 23:12:31.936  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 23:12:31.936  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:12:31.936  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
,08-23 23:12:31.937  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-23 23:12:31.938  3801  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-23 23:12:31.938  3801  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-23 23:12:31.938  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-23 23:12:31.938  3801  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-23 23:12:31.938  3801  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-23 23:12:31.938  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-23 23:12:31.938  3801  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-23 23:12:31.938  3801  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-23 23:12:31.939  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 23:12:31.939  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 23:12:31.939  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 23:12:31.941  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 23:12:31.941  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:31.941  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:31.941  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3335f1 not in the list
08-23 23:12:31.941  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 23:12:31.941  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
08-23 23:12:31.941  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-23 23:12:31.941  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:31.941  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:31.941  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 23:12:31.941  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:31.942  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 23:12:31.943  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 23:12:31.943  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:12:31.943  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
,08-23 23:12:31.944  3801  3851 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 23:12:31.944  3801  3851 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-23 23:12:31.944  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-23 23:12:31.947  3801  3851 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 23:12:31.948  3801  3851 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-23 23:12:31.948  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-23 23:12:31.948  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-23 23:12:31.948  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-23 23:12:31.948  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-23 23:12:31.948  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-23 23:12:31.948  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-23 23:12:31.948  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-23 23:12:31.948  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-23 23:12:31.949  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-23 23:12:31.949  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-23 23:12:31.949  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-23 23:12:31.949  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-23 23:12:31.949  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-23 23:12:31.949  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-23 23:12:31.949  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-23 23:12:31.949  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-23 23:12:31.949  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-23 23:12:31.949  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-23 23:12:31.949  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-23 23:12:31.949  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-23 23:12:31.949  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-23 23:12:31.949  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-23 23:12:31.950  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-23 23:12:31.950  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-23 23:12:31.950  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-23 23:12:31.950  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-23 23:12:31.950  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-23 23:12:31.950  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-23 23:12:31.950  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-23 23:12:31.950  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-23 23:12:31.950  3801  3851 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,08-23 23:12:31.951  3801  3851 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-23 23:12:31.951  3801  3851 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-23 23:12:31.951  3801  3851 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 23:12:31.951  3801  3851 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-23 23:12:31.951  3801  3851 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-23 23:12:31.951  3801  3851 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 23:12:31.951  3801  3851 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-23 23:12:31.951  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-23 23:12:31.953  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-23 23:12:31.954  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-23 23:12:31.954  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-23 23:12:31.954  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-23 23:12:31.954  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-23 23:12:31.954  3801  3851 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-23 23:12:31.954  3801  3851 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 23:12:31.955  3801  3851 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-23 23:12:31.955  3801  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 389)
08-23 23:12:31.955  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 23:12:31.955  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 23:12:31.955  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 23:12:31.955  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 23:12:31.955  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:31.956  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:31.956  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-23 23:12:31.956  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3335f1 not in the list
08-23 23:12:31.956  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:12:31.956  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
08-23 23:12:31.957  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 23:12:31.957  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:31.957  3801  3881 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 23:12:31.957  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:31.957  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 23:12:31.957  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:31.958  3801  3882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 389
08-23 23:12:31.958  3801  3882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 389)
08-23 23:12:31.958  3801  3882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 389)
08-23 23:12:31.959  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 23:12:31.959  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 23:12:31.959  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 23:12:31.959  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
08-23 23:12:31.959  3801  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 389)
08-23 23:12:31.960  3801  3851 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-23 23:12:31.960  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 23:12:31.960  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 23:12:31.960  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-23 23:12:31.961  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 23:12:31.961  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:31.961  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:31.961  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3335f1 not in the list
08-23 23:12:31.961  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:12:31.961  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
08-23 23:12:31.961  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-23 23:12:31.961  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:31.961  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:31.961  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:31.961  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:31.962  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 23:12:31.962  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 23:12:31.962  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:12:31.962  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
08-23 23:12:31.963  3801  3851 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-23 23:12:31.963  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 23:12:31.963  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 23:12:31.963  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-23 23:12:31.963  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 23:12:31.963  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:31.963  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:31.963  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3335f1 not in the list
,08-23 23:12:31.964  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:12:31.964  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
08-23 23:12:31.964  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-23 23:12:31.964  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:31.964  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:31.964  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:31.964  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:31.965  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 23:12:31.965  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 23:12:31.965  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 23:12:31.965  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
08-23 23:12:31.966  3801  3851 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-23 23:12:31.966  3801  3851 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-23 23:12:31.966  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-23 23:12:31.966  3801  3851 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-23 23:12:31.966  3801  3851 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,08-23 23:12:31.966  3801  3851 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-23 23:12:31.966  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-23 23:12:31.966  3801  3851 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-23 23:12:31.966  3801  3851 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-23 23:12:31.966  3801  3851 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-23 23:12:31.966  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-23 23:12:31.966  3801  3851 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-23 23:12:31.967  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 23:12:31.967  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 23:12:31.967  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 23:12:31.967  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 23:12:31.967  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:31.967  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:31.967  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3335f1 not in the list
08-23 23:12:31.967  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:12:31.967  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
08-23 23:12:31.967  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-23 23:12:31.967  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:31.967  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 23:12:31.967  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:31.968  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:31.968  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 23:12:31.968  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 23:12:31.968  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:12:31.969  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
08-23 23:12:31.969  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 23:12:31.969  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 23:12:31.969  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:31.969  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3335f1 not in the list
08-23 23:12:31.969  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:12:31.969  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
08-23 23:12:31.969  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-23 23:12:31.969  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:31.970  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 23:12:32.091  1504  3879 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-23 23:12:32.093  1504  3879 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
08-23 23:12:32.096  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 23:12:32.134  1504  3879 W Uploader:  no longer exists, so no auth token.
,08-23 23:12:32.159  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 23:12:32.163  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 23:12:32.236  1504  2985 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-23 23:12:32.236  1504  2985 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-23 23:12:32.236  1504  2985 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 23:12:32.236  1504  2985 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 23:12:32.261  3524  3524 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-23 23:12:32.261  3524  3524 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-23 23:12:32.261  3524  3524 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-23 23:12:36.970  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 23:12:36.971  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
08-23 23:12:36.971  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 23:12:36.971  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:36.972  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:36.972  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3335f1 not in the list
,08-23 23:12:36.973  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 23:12:36.973  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 23:12:36.973  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 23:12:36.974  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-23 23:12:36.975  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:36.975  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:36.975  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3335f1 not in the list
08-23 23:12:36.976  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 23:12:36.976  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
08-23 23:12:36.976  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 23:12:36.976  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:36.977  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:36.977  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:36.977  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 23:12:36.981  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 23:12:36.981  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 23:12:36.981  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:12:36.982  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
,08-23 23:12:36.987  3801  3851 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-23 23:12:36.988  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 23:12:36.990  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-23 23:12:36.991  3801  3851 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-23 23:12:36.991  3801  3851 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-23 23:12:36.992  3801  3801 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-23 23:12:36.992  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-23 23:12:36.992  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-23 23:12:36.992  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 23:12:36.992  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-23 23:12:36.992  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-23 23:12:36.992  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-23 23:12:36.993  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:36.993  3801  3851 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-23 23:12:36.993  3801  3801 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-23 23:12:36.993  3801  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-23 23:12:36.993  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3335f1 not in the list
08-23 23:12:36.993  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 23:12:36.993  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 23:12:36.994  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 23:12:36.993  3801  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-23 23:12:36.995  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-23 23:12:36.998  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:36.998  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 23:12:36.999  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 23:12:37.000  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 23:12:37.000  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-23 23:12:37.000  3801  3801 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-23 23:12:37.000  3801  3801 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 23:12:37.000  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
,08-23 23:12:37.000  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 23:12:37.000  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 23:12:37.001  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 23:12:37.001  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-23 23:12:37.001  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:37.001  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 23:12:37.002  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3335f1 not in the list
08-23 23:12:37.002  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:12:37.002  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
,08-23 23:12:37.003  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-23 23:12:37.003  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:37.003  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:37.003  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 23:12:37.004  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:37.005  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 23:12:37.006  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 23:12:37.006  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:12:37.006  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
08-23 23:12:37.009  3801  3851 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-23 23:12:37.010  3801  3851 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-23 23:12:37.010  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-23 23:12:37.010  3801  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-23 23:12:37.011  3801  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-23 23:12:37.011  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 23:12:37.011  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 23:12:37.011  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 23:12:37.012  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 23:12:37.012  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:37.012  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 23:12:37.013  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3335f1 not in the list
08-23 23:12:37.013  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:12:37.013  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
08-23 23:12:37.013  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-23 23:12:37.013  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 23:12:37.013  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:37.013  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:37.014  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 23:12:37.016  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 23:12:37.016  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 23:12:37.016  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 23:12:37.016  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
,08-23 23:12:37.023  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 23:12:37.023  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 23:12:37.023  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 23:12:37.023  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 23:12:37.023  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:37.023  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:37.024  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3335f1 not in the list
08-23 23:12:37.024  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:12:37.024  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
08-23 23:12:37.024  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-23 23:12:37.024  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:37.024  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:37.024  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:37.024  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 23:12:37.026  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 23:12:37.026  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 23:12:37.026  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:12:37.026  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
,08-23 23:12:37.028  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 23:12:37.028  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 23:12:37.029  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 23:12:37.029  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 23:12:37.029  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:37.029  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:37.030  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3335f1 not in the list
,08-23 23:12:37.030  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:12:37.030  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
08-23 23:12:37.030  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-23 23:12:37.030  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:37.030  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:12:37.031  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:37.031  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 23:12:37.032  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 23:12:37.033  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 23:12:37.033  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:12:37.033  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca395d6 not in the list
,08-23 23:12:37.036  3801  3851 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,08-23 23:12:37.036  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-23 23:12:37.036  3801  3851 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-23 23:12:37.036  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left,
08-23 23:12:37.037  3801  3851 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-23 23:12:37.037  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-23 23:12:37.046  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-23 23:12:37.047  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-23 23:12:37.048  3801  3851 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,08-23 23:12:37.049  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-23 23:12:37.049  3801  3851 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-23 23:12:37.049  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-23 23:12:37.049  3801  3851 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-23 23:12:37.049  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-23 23:12:37.050  3801  3851 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,08-23 23:12:37.050  3801  3851 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-23 23:12:37.051  3801  3851 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,08-23 23:12:37.051  3801  3851 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,08-23 23:12:37.051  3801  3851 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-23 23:12:37.051  3801  3851 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-23 23:12:37.052  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-23 23:12:37.052  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2ac7d61 added. We now have 3 listener(s)
08-23 23:12:37.052  3801  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 23:12:37.055  3801  3851 D BluetoothAdapter: enable(): BT is already enabled..!,
08-23 23:12:37.055   874  1945 D WifiService: setWifiEnabled: true pid=3801, uid=10000
08-23 23:12:37.055   874  1945 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-23 23:12:37.089  2695  2872 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,08-23 23:12:37.090  2695  2879 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,08-23 23:12:37.195   874  2081 D NetlinkSocketObserver: NeighborEvent{elapsedMs=169356, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-23 23:12:37.501  3801  3801 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-23 23:12:38.208  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 23:12:38.212  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 23:12:38.255  1504  3879 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-23 23:12:38.255  1504  3879 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-23 23:12:38.255  1504  3879 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 23:12:38.256  1504  3879 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 23:12:38.285  1504  3879 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-23 23:12:38.285  1504  3879 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-23 23:12:38.285  1504  3879 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-23 23:12:38.285  1504  3879 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-23 23:12:38.285  1504  3879 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-23 23:12:38.285  1504  3879 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-23 23:12:38.285  1504  3879 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-23 23:12:38.285  1504  3879 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-23 23:12:38.285  1504  3879 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-23 23:12:38.285  1504  3879 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-23 23:12:38.285  1504  3879 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-23 23:12:38.285  1504  3879 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-23 23:12:38.285  1504  3879 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-23 23:12:38.928  1504  3879 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-23 23:12:38.928  1504  3879 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-23 23:12:38.928  1504  3879 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 23:12:38.929  1504  3879 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 23:12:38.951  1504  3879 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-23 23:12:38.951  1504  3879 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-23 23:12:38.951  1504  3879 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-23 23:12:38.951  1504  3879 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-23 23:12:38.951  1504  3879 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-23 23:12:38.951  1504  3879 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-23 23:12:38.951  1504  3879 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-23 23:12:38.951  1504  3879 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-23 23:12:38.951  1504  3879 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-23 23:12:38.951  1504  3879 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-23 23:12:38.951  1504  3879 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-23 23:12:38.951  1504  3879 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-23 23:12:38.951  1504  3879 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-23 23:12:39.144  1504  3879 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-23 23:12:39.144  1504  3879 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-23 23:12:39.145  1504  3879 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 23:12:39.145  1504  3879 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 23:12:39.164  1504  3879 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-23 23:12:39.164  1504  3879 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-23 23:12:39.164  1504  3879 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-23 23:12:39.164  1504  3879 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-23 23:12:39.164  1504  3879 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-23 23:12:39.164  1504  3879 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-23 23:12:39.164  1504  3879 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-23 23:12:39.164  1504  3879 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-23 23:12:39.164  1504  3879 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-23 23:12:39.164  1504  3879 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-23 23:12:39.164  1504  3879 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-23 23:12:39.164  1504  3879 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-23 23:12:39.164  1504  3879 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-23 23:12:42.059  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 23:12:42.060  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bab2086 added. We now have 4 listener(s)
,08-23 23:12:42.060  3801  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 23:12:42.070  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 23:12:42.071  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bab2086 removed from the list
08-23 23:12:42.071  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-23 23:12:42.071  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:42.071  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 23:12:42.073  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 23:12:42.073  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@969dd47 added. We now have 4 listener(s)
,08-23 23:12:42.074  3801  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 23:12:42.076  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 23:12:42.076  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@969dd47 removed from the list
08-23 23:12:42.077  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-23 23:12:42.077  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:12:42.077  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 23:12:42.079  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 23:12:42.079  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f690974 added. We now have 4 listener(s)
,08-23 23:12:42.080  3801  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 23:12:42.084   874  1958 D WifiService: setWifiEnabled: false pid=3801, uid=10000
08-23 23:12:42.084   874  1958 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-23 23:12:42.097  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 23:12:42.098  2695  2745 D BluetoothAdapterState: Current state: ON, message: 23
,08-23 23:12:42.098  2695  2745 D BluetoothAdapterProperties: Setting state to 13
,08-23 23:12:42.098  2695  2745 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-23 23:12:42.099  2695  2745 D BluetoothAdapterProperties: onBluetoothDisable()
,08-23 23:12:42.102  2695  2745 I BluetoothAdapterState: Entering PendingCommandState
,08-23 23:12:42.103  2695  2695 D BluetoothMapService: onReceive
08-23 23:12:42.103  2695  2695 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-23 23:12:42.103  2695  2695 D BluetoothMapService: STATE_TURNING_OFF
08-23 23:12:42.104  2695  2695 D BluetoothMapService: MAP Service closeService in
08-23 23:12:42.105  2695  2695 D BluetoothMapMasInstance0: MAP Service shutdown
08-23 23:12:42.105  2695  2695 D ObexServerSockets0: shutdown(block = true)
,08-23 23:12:42.107  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-23 23:12:42.107  2695  2695 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-23 23:12:42.107  2695  2695 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-23 23:12:42.108  2695  2901 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-23 23:12:42.108  2695  2879 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-23 23:12:42.109  2695  2902 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-23 23:12:42.111   874  1310 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-23 23:12:42.111  2695  2695 I BtOppRfcommListener: stopping Accept Thread
08-23 23:12:42.111   874  1310 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-23 23:12:42.111   874  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-23 23:12:42.111  2695  3442 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-23 23:12:42.112   874  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-23 23:12:42.113  2695  3442 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-23 23:12:42.117  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 23:12:42.117  3801  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 23:12:42.117  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:12:42.117  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:12:42.117  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 23:12:42.117  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 23:12:42.117  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 23:12:42.117  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 23:12:42.117  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 23:12:42.118  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 23:12:42.118  3801  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 23:12:42.119  3801  3851 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 23:12:42.119   874  1310 E native  : do suspend true
08-23 23:12:42.121  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 23:12:42.124  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 23:12:42.126   874   887 I ActivityManager: Start proc 3897:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-23 23:12:42.126  2695  2749 D BluetoothAdapterProperties: Scan Mode:20
08-23 23:12:42.126  2695  2745 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-23 23:12:42.129  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 23:12:42.129  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 23:12:42.129  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:12:42.129  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:12:42.129  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 23:12:42.129  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 23:12:42.129  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 23:12:42.129  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 23:12:42.129  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 23:12:42.129  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 23:12:42.129  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 23:12:42.131   874  2085 D DhcpClient: Clearing IP address
08-23 23:12:42.131   372   872 D CommandListener: Clearing all IP addresses on wlan0
08-23 23:12:42.133  2695  2695 D HeadsetService: Received stop request...Stopping profile...
08-23 23:12:42.134  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 23:12:42.134  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 23:12:42.134  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:12:42.134  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:12:42.134  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 23:12:42.134  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 23:12:42.134  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 23:12:42.134  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 23:12:42.134  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 23:12:42.134   372   872 D CommandListener: Setting iface cfg
08-23 23:12:42.135  1923  1939 D BluetoothHeadset: Proxy object disconnected
08-23 23:12:42.136  2695  2695 D A2dpService: Received stop request...Stopping profile...
,08-23 23:12:42.137  2695  2884 D A2dpStateMachine: Exit Disconnected: -1
08-23 23:12:42.137  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 23:12:42.137  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 23:12:42.138  1355  1368 D BluetoothHeadset: Proxy object disconnected
08-23 23:12:42.138   874  2093 D DhcpClient: Receive thread stopped
08-23 23:12:42.138   874   874 D BluetoothHeadset: Proxy object disconnected
08-23 23:12:42.138   874   874 D BluetoothHeadset: Proxy object disconnected
08-23 23:12:42.138   874   874 D BluetoothHeadset: Proxy object disconnected
08-23 23:12:42.138   874   874 D BluetoothA2dp: Proxy object disconnected
08-23 23:12:42.139  2695  2695 D HidService: Received stop request...Stopping profile...
08-23 23:12:42.139  2695  2695 D HidService: Stopping Bluetooth HidService
08-23 23:12:42.139  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 23:12:42.140   874  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-23 23:12:42.140   874  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-23 23:12:42.140   874  1310 D WifiStateMachine: Start Disconnecting Watchdog 1
08-23 23:12:42.141   874  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-23 23:12:42.141   874  1310 E native  : do suspend true
08-23 23:12:42.141  1355  1355 D BluetoothA2dp: Proxy object disconnected
08-23 23:12:42.142  1355  1355 D HeadsetProfile: Bluetooth service disconnected
,08-23 23:12:42.142  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 23:12:42.142  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 23:12:42.142  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:12:42.142  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:12:42.142  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 23:12:42.142  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 23:12:42.142  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 23:12:42.142  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 23:12:42.142  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 23:12:42.143  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 23:12:42.143  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-23 23:12:42.144   397   397 E Parcel  : Reading a NULL string not supported here.
08-23 23:12:42.145  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 23:12:42.145  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 23:12:42.145  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:12:42.145  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:12:42.145  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 23:12:42.145  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 23:12:42.145  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 23:12:42.145  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 23:12:42.145  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 23:12:42.145  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 23:12:42.145  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-23 23:12:42.147  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 23:12:42.147  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 23:12:42.147  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:12:42.147  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:12:42.147  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 23:12:42.147  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 23:12:42.147  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 23:12:42.147  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 23:12:42.147  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 23:12:42.148   874  1312 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-23 23:12:42.148  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 23:12:42.148  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-23 23:12:42.150  1355  1355 D BluetoothInputDevice: Proxy object disconnected
,08-23 23:12:42.150  2695  2695 V BluetoothAdapterState: isTurningOff()=true
08-23 23:12:42.150  1355  1355 D HidProfile: Bluetooth service disconnected
08-23 23:12:42.150  2695  2695 V BluetoothAdapterState: isTurningOn()=false
08-23 23:12:42.150  2695  2695 V BluetoothAdapterState: isBleTurningOn()=false
08-23 23:12:42.150  2695  2695 V BluetoothAdapterState: isBleTurningOff()=false
08-23 23:12:42.150  2695  2695 D HealthService: Received stop request...Stopping profile...
,08-23 23:12:42.152  2695  2695 D PanService: Received stop request...Stopping profile...
08-23 23:12:42.154  1504  2522 V NativeCrypto: Read error: ssl=0x9ad6b400: I/O error during system call, Connection timed out
08-23 23:12:42.155  2695  2695 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-23 23:12:42.155  2695  2695 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-23 23:12:42.155  2695  2749 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-23 23:12:42.155  2695  2872 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-23 23:12:42.155  2695  2872 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-23 23:12:42.155  2695  2872 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-23 23:12:42.156  2695  2749 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-23 23:12:42.156  2695  2695 D BluetoothMapService: Received stop request...Stopping profile...
,08-23 23:12:42.156  2695  2695 D BluetoothMapService: stop()
08-23 23:12:42.157  2695  2695 D BluetoothMapAppObserver: deinitObservers()
,08-23 23:12:42.157  2695  2695 D BluetoothMapAppObserver: removeReceiver()
,08-23 23:12:42.160  1504  2522 V NativeCrypto: SSL shutdown failed: ssl=0x9ad6b400: I/O error during system call, Broken pipe
,08-23 23:12:42.158  2695  2695 V BluetoothAdapterState: isTurningOff()=true
08-23 23:12:42.163  2695  2695 V BluetoothAdapterState: isTurningOn()=false
08-23 23:12:42.163  2695  2695 V BluetoothAdapterState: isBleTurningOn()=false
08-23 23:12:42.163  2695  2695 V BluetoothAdapterState: isBleTurningOff()=false
08-23 23:12:42.165  2695  2749 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-23 23:12:42.165  2695  2872 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-23 23:12:42.165  2695  2872 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-23 23:12:42.165  2695  2872 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-23 23:12:42.165  2695  2872 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 23:12:42.165  2695  2872 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 23:12:42.165  2695  2872 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 23:12:42.165  2695  2695 V BluetoothAdapterState: isTurningOff()=true
,08-23 23:12:42.165  2695  2695 V BluetoothAdapterState: isTurningOn()=false
08-23 23:12:42.165  2695  2695 V BluetoothAdapterState: isBleTurningOn()=false
08-23 23:12:42.165  2695  2695 V BluetoothAdapterState: isBleTurningOff()=false
08-23 23:12:42.166  2695  2695 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-23 23:12:42.166  2695  2749 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-23 23:12:42.166  2695  2695 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-23 23:12:42.167  2695  2695 V BluetoothAdapterState: isTurningOff()=true
08-23 23:12:42.167  2695  2695 V BluetoothAdapterState: isTurningOn()=false
08-23 23:12:42.167  2695  2695 V BluetoothAdapterState: isBleTurningOn()=false
08-23 23:12:42.167  2695  2695 V BluetoothAdapterState: isBleTurningOff()=false
08-23 23:12:42.167  2695  2695 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-23 23:12:42.167  2695  2749 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-23 23:12:42.167  2695  2695 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-23 23:12:42.167  2695  2695 V BluetoothAdapterState: isTurningOff()=true
08-23 23:12:42.168  2695  2695 V BluetoothAdapterState: isTurningOn()=false
08-23 23:12:42.168  2695  2695 V BluetoothAdapterState: isBleTurningOn()=false
08-23 23:12:42.168  2695  2695 V BluetoothAdapterState: isBleTurningOff()=false
08-23 23:12:42.168  2695  2695 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-23 23:12:42.168  2695  2695 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-23 23:12:42.169  2695  2695 D BluetoothMapService: MAP Service closeService in
08-23 23:12:42.169  2695  2695 V BluetoothAdapterState: isTurningOff()=true
08-23 23:12:42.169  2695  2695 V BluetoothAdapterState: isTurningOn()=false
08-23 23:12:42.169  2695  2695 V BluetoothAdapterState: isBleTurningOn()=false
08-23 23:12:42.169  2695  2695 V BluetoothAdapterState: isBleTurningOff()=false
08-23 23:12:42.169  2695  2745 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-23 23:12:42.169  2695  2745 D BluetoothAdapterProperties: Setting state to 15
,08-23 23:12:42.169  2695  2745 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-23 23:12:42.169  1355  1355 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-23 23:12:42.170  1355  1355 D PanProfile: Bluetooth service disconnected
08-23 23:12:42.170  2695  2745 I BluetoothAdapterState: Entering BleOnState
08-23 23:12:42.170  1355  1355 D BluetoothMap: Proxy object disconnected
08-23 23:12:42.170  1355  1355 D MapProfile: Bluetooth service disconnected
08-23 23:12:42.170  2695  2695 D BluetoothMapService: cleanup()
08-23 23:12:42.170  2695  2695 D BluetoothMapService: MAP Service closeService in
08-23 23:12:42.170  1355  1368 D BluetoothPbap: onBluetoothStateChange: up=false
08-23 23:12:42.171  1355  1366 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 23:12:42.171  1355  2008 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-23 23:12:42.171  1355  1368 D BluetoothMap: onBluetoothStateChange: up=false
08-23 23:12:42.172  1355  1366 D BluetoothA2dp: onBluetoothStateChange: up=false
08-23 23:12:42.173  1355  2008 D BluetoothPan: onBluetoothStateChange on: false
08-23 23:12:42.173  1923  2087 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 23:12:42.174   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 23:12:42.174   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
08-23 23:12:42.174   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 23:12:42.174   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 23:12:42.174  2695  2745 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-23 23:12:42.174  2695  2745 D BluetoothAdapterProperties: Setting state to 16
,08-23 23:12:42.174  2695  2745 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-23 23:12:42.175  2695  2745 D BluetoothAdapterProperties: onBleDisable
08-23 23:12:42.175  2695  2745 I BluetoothAdapterState: Entering PendingCommandState
08-23 23:12:42.175  2695  2746 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-23 23:12:42.177  2695  2872 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-23 23:12:42.177  2695  2872 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-23 23:12:42.178  2695  2749 D BluetoothAdapterProperties: Scan Mode:20
08-23 23:12:42.180  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 23:12:42.180  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 23:12:42.180  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:12:42.180  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:12:42.180  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 23:12:42.180  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 23:12:42.180  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 23:12:42.180  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 23:12:42.180  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 23:12:42.182  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 23:12:42.182  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 23:12:42.182  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:12:42.182  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:12:42.182  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 23:12:42.182  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 23:12:42.182  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 23:12:42.182  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 23:12:42.182  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 23:12:42.183  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 23:12:42.183  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 23:12:42.183  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:12:42.183  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:12:42.183  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 23:12:42.183  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 23:12:42.183  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 23:12:42.183  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 23:12:42.183  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 23:12:42.184  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 23:12:42.185  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 23:12:42.186  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 23:12:42.196   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-23 23:12:42.201  3897  3897 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-23 23:12:42.210  3897  3897 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-23 23:12:42.216   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-23 23:12:42.216  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-23 23:12:42.216   372   872 D CommandListener: Clearing all IP addresses on wlan0
08-23 23:12:42.217   874  1312 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-23 23:12:42.217   874  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-23 23:12:42.219   874   891 D Tethering: MasterInitialState.processMessage what=3
08-23 23:12:42.222  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 23:12:42.223  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 23:12:42.224  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 23:12:42.232  3413  3413 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@c3ca245 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-23 23:12:42.233   874  2352 I ActivityManager: Start proc 3914:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
08-23 23:12:42.234  1980  1980 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-23 23:12:42.234   874  1310 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-23 23:12:42.246   874  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,08-23 23:12:42.249  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 23:12:42.249  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 23:12:42.249  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:12:42.249  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:12:42.249  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 23:12:42.249  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 23:12:42.249  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 23:12:42.249  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 23:12:42.249  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 23:12:42.249   874  1310 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-23 23:12:42.250  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 23:12:42.250  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 23:12:42.251  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 23:12:42.251  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 23:12:42.251  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:12:42.251  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:12:42.251  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 23:12:42.251  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 23:12:42.251  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 23:12:42.251  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 23:12:42.251  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 23:12:42.252  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 23:12:42.252  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 23:12:42.253  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 23:12:42.253  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 23:12:42.253  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:12:42.253  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:12:42.253  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 23:12:42.253  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 23:12:42.253  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 23:12:42.253  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 23:12:42.253  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 23:12:42.254  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 23:12:42.254  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 23:12:42.255  2162  2327 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 23:12:42.257   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b3b16e0:true
,08-23 23:12:42.272  3914  3914 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-23 23:12:42.274  3897  3897 D LocalBluetoothProfileManager: Adding local MAP profile
,08-23 23:12:42.276  3897  3897 D BluetoothMap: Create BluetoothMap proxy object
,08-23 23:12:42.279   372   872 E Netd    : netlink response contains error (No such file or directory)
,08-23 23:12:42.281  3897  3897 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-23 23:12:42.296  3897  3897 D DockEventReceiver: finishStartingService: stopping service
,08-23 23:12:42.299   874  1388 I ActivityManager: Killing 2972:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-23 23:12:42.380  2695  2749 I bt_hci  : shut_down
,08-23 23:12:42.387  2695  2756 I bt_vendor: low_power_mode_cb
,08-23 23:12:42.393  2695  2756 D bt_hwcfg: hw_epilog_process
,08-23 23:12:42.407  2695  2756 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-23 23:12:42.407  2695  2756 I bt_vendor: epilog_cb
08-23 23:12:42.407  2695  2756 I bt_hci  : epilog_finished_callback
,08-23 23:12:42.412  2695  2749 I bt_hci_h4: hal_close
,08-23 23:12:42.413  2695  2749 I bt_userial_vendor: device fd = 51 close
,08-23 23:12:42.483  3914  3914 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at java.io.File.exists(File.java:361)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 23:12:42.483  3914  3914 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 23:12:42.483  3914  3914 D StrictMode: StrictMode policy violation; ~duration=127 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5417)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 23:12:42.483  3914  3914 D StrictMode: StrictMode policy violation; ~duration=127 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.r.e.b(PG:170)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 23:12:42.483  3914  3914 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.r.k.d(PG:583)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.r.e.b(PG:170)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 23:12:42.483  3914  3914 D StrictMode: StrictMode policy violation; ~duration=61 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at java.io.File.exists(File.java:361)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 23:12:42.483  3914  3914 D StrictMode: StrictMode policy violation; ~duration=59 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at java.io.File.exists(File.java:361)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 23:12:42.483  3914  3914 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 23:12:42.484  3914  3914 D StrictMode: StrictMode policy violation; ~duration=58 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-23 23:12:42.484  3914  3914 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-23 23:12:42.484  3914  3914 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-23 23:12:42.484  3914  3914 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-23 23:12:42.484  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-23 23:12:42.484  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 23:12:42.484  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-23 23:12:42.484  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 23:12:42.484  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 23:12:42.484  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-23 23:12:42.484  3914  3914 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-23 23:12:42.484  3914  3914 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-23 23:12:42.484  3914  3914 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-23 23:12:42.484  3914  3914 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 23:12:42.484  3914  3914 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 23:12:42.484  3914  3914 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 23:12:42.484  3914  3914 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-23 23:12:42.484  3914  3914 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 23:12:42.484  3914  3914 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 23:12:42.484  3914  3914 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 23:12:42.484  3914  3914 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 23:12:42.498  3897  3897 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-23 23:12:42.512  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-23 23:12:42.520  3897  3897 D DockEventReceiver: finishStartingService: stopping service
08-23 23:12:42.529  2695  2746 D bt_stack_manager: event_shut_down_stack finished.
08-23 23:12:42.529  2695  2745 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-23 23:12:42.531  2695  2745 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-23 23:12:42.531  2695  2695 D BtGatt.DebugUtils: handleDebugAction() action=null
08-23 23:12:42.532  2695  2695 D BtGatt.GattService: Received stop request...Stopping profile...
08-23 23:12:42.532  2695  2695 D BtGatt.GattService: stop()
08-23 23:12:42.532  2695  2695 D BtGatt.AdvertiseManager: advertise clients cleared
08-23 23:12:42.535  2695  2695 V BluetoothAdapterState: isTurningOff()=false
08-23 23:12:42.535  2695  2695 V BluetoothAdapterState: isTurningOn()=false
08-23 23:12:42.535  2695  2695 V BluetoothAdapterState: isBleTurningOn()=false
08-23 23:12:42.535  2695  2695 V BluetoothAdapterState: isBleTurningOff()=true
08-23 23:12:42.536  2695  2745 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-23 23:12:42.536  2695  2745 D BluetoothAdapterProperties: Setting state to 10
08-23 23:12:42.536  2695  2745 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-23 23:12:42.537  2695  2745 I BluetoothAdapterState: Entering OffState
08-23 23:12:42.538   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
08-23 23:12:42.540   874  1388 I ActivityManager: Killing 3413:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-23 23:12:42.623  2695  2695 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-23 23:12:42.623  2695  2695 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-23 23:12:42.624  2695  2695 I BluetoothServiceJni: cleanupNative: return from cleanup
08-23 23:12:42.625  2695  2746 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-23 23:12:42.628  1722  1722 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-23 23:12:42.632  2695  2746 D bt_stack_manager: event_clean_up_stack finished.
,08-23 23:12:42.633  1722  1722 D SystemUpdateService: onCreate
,08-23 23:12:42.637  1722  1722 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-23 23:12:42.640  2695  2695 I art     : System.exit called, status: 0
,08-23 23:12:42.640  2695  2695 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-23 23:12:42.647  1722  1722 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-23 23:12:42.651  1722  2497 I iu.UploadsManager: num queued entries: 0
,08-23 23:12:42.666  1722  1722 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-23 23:12:42.667  1722  1722 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-23 23:12:42.685  1722  2497 I iu.UploadsManager: num updated entries: 0
,08-23 23:12:42.686  1722  2497 I iu.SyncManager: NEXT; no task
,08-23 23:12:42.676  1722  3949 I SystemUpdateService: active receiver: enabled
,08-23 23:12:42.691   874   884 I ActivityManager: Start proc 3951:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-23 23:12:42.704  1722  3949 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-23 23:12:42.708  1722  3949 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,08-23 23:12:42.709  1722  3949 I SystemUpdateService: now status is 0 (complete)
08-23 23:12:42.709  1722  3949 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-23 23:12:42.709  1722  3949 I SystemUpdateService: file has been verified
08-23 23:12:42.709  1722  3949 I SystemUpdateService: OTA package size = 12249756
,08-23 23:12:42.722  1722  3949 I SystemUpdateService: showing system update notification
,08-23 23:12:42.726   874  1934 I ActivityManager: Process com.android.bluetooth (pid 2695) has died
,08-23 23:12:42.738  3951  3951 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-23 23:12:42.741  3951  3951 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-23 23:12:42.747  3951  3951 D SprintDMHelper: simOperator: 
08-23 23:12:42.747  3951  3951 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-23 23:12:42.765   874   884 I ActivityManager: Start proc 3963:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-23 23:12:42.773  1722  1722 D SystemUpdateService: onDestroy
,08-23 23:12:42.775   874  1934 I ActivityManager: Killing 3461:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-23 23:12:42.866  3914  3943 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-23 23:12:42.953   874  2003 I ActivityManager: Start proc 3980:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-23 23:12:42.954  2398  3979 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-23 23:12:42.965   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2535735:true
,08-23 23:12:43.000  3980  3980 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-23 23:12:43.050  3980  3980 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-23 23:12:43.050  3980  3980 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-23 23:12:43.050  3980  3980 I GAv4    :   adb logcat -s GAv4
,08-23 23:12:43.070  3980  3980 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-23 23:12:43.076  3980  3980 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-23 23:12:43.107  3980  3998 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-23 23:12:43.210  3980  3980 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-23 23:12:43.252  3980  3980 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-23 23:12:43.264  3980  3980 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 5420-5423)
,08-23 23:12:43.264  3980  3980 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-23 23:12:43.275  3980  3980 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {9ffc597}
,08-23 23:12:43.275  3980  3980 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 23:12:43.275  3980  3980 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-23 23:12:43.284  3980  3980 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-23 23:12:43.286  3980  3980 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-23 23:12:43.305  3980  3980 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-23 23:12:43.317  3980  3980 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-23 23:12:43.317  3980  3980 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-23 23:12:43.319  3980  3980 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-23 23:12:43.319  3980  3980 I Adreno  : Build Date                       : 10/20/15
08-23 23:12:43.319  3980  3980 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-23 23:12:43.319  3980  3980 I Adreno  : Local Branch                     : M14
08-23 23:12:43.319  3980  3980 I Adreno  : Remote Branch                    : 
08-23 23:12:43.319  3980  3980 I Adreno  : Remote Branch                    : 
08-23 23:12:43.319  3980  3980 I Adreno  : Reconstruct Branch               : 
,08-23 23:12:43.384  3980  3980 I NSApplication: Starting up...
,08-23 23:12:43.399  3980  4026 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-23 23:12:43.433   874  1388 I ActivityManager: Start proc 4031:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-23 23:12:43.434   874  1388 I ActivityManager: Killing 3595:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-23 23:12:43.525  4031  4031 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-23 23:12:43.735   874  1945 I ActivityManager: Killing 1700:android.process.acore/u0a5 (adj 15): empty #17
,08-23 23:12:43.796   874  1945 I ActivityManager: Start proc 4045:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-23 23:12:43.867  4045  4045 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-23 23:12:43.914  4045  4045 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-23 23:12:43.975   874   884 I ActivityManager: Killing 3630:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-23 23:12:47.121   874  3149 D WifiService: setWifiEnabled: true pid=3801, uid=10000
,08-23 23:12:47.122   874  3149 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-23 23:12:47.158   874  1310 D WifiConfigStore: Loading config and enabling all networks 
,08-23 23:12:47.163  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 23:12:47.164  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 23:12:47.164  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:12:47.164  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:12:47.164  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 23:12:47.164  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 23:12:47.164  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 23:12:47.164  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 23:12:47.164  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 23:12:47.164  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 23:12:47.164  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-23 23:12:47.165  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 23:12:47.166  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 23:12:47.166  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:12:47.166  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:12:47.166  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 23:12:47.166  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 23:12:47.166  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
,08-23 23:12:47.166  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 23:12:47.166  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 23:12:47.166  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 23:12:47.166  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-23 23:12:47.167  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 23:12:47.167  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 23:12:47.167  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:12:47.167  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:12:47.167  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 23:12:47.167  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 23:12:47.167  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 23:12:47.167  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 23:12:47.167  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 23:12:47.167  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 23:12:47.167  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-23 23:12:47.175   874  1310 D WifiConfigStore: loaded 0 passpoint configs
,08-23 23:12:47.176   874  1310 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-23 23:12:47.177   874  1310 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-23 23:12:47.178   874  1310 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-23 23:12:47.178   874  1310 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-23 23:12:47.179   874  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-23 23:12:47.179   874  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-23 23:12:47.188   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-23 23:12:47.189   874  1310 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-23 23:12:47.190   372   872 D CommandListener: Setting iface cfg
08-23 23:12:47.191   874  1308 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '128 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 128 Failed to set address (No such device)'
08-23 23:12:47.191   874  1308 D WifiMonitor: startMonitoring(p2p0) with mConnected = true,
,08-23 23:12:47.199   874  1310 E native  : do suspend true
,08-23 23:12:47.200   874  1308 D WifiNative-HAL: p2pGetDeviceAddress
,08-23 23:12:47.206   874  1308 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-23 23:12:47.212   874  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,08-23 23:12:48.021   874   884 I ActivityManager: Killing 3647:com.android.musicfx/u0a18 (adj 15): empty #17
,08-23 23:12:48.603   874  1310 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-23 23:12:48.630   874  1310 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.69 rxSuccessRate=8.81 delta 1000 -> 994
,08-23 23:12:48.631   874  1310 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-23 23:12:48.631   874  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-23 23:12:48.648   874  1310 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-23 23:12:48.704   874  1310 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-23 23:12:48.706  1466  1466 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-23 23:12:49.130  1466  1466 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-23 23:12:49.171  1466  1466 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-23 23:12:49.172  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-23 23:12:49.185   874  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,08-23 23:12:49.196   874  1310 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-23 23:12:49.197   874  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-23 23:12:49.197   874  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-23 23:12:49.216   874  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-23 23:12:49.228   372   872 D CommandListener: Setting iface cfg
,08-23 23:12:49.229   874  1310 D WifiStateMachine: Start Dhcp Watchdog 2
,08-23 23:12:49.244   874  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-23 23:12:49.265   874  4080 D DhcpClient: Receive thread started
,08-23 23:12:49.351   874  1310 E native  : do suspend false
,08-23 23:12:49.371   874  2085 D DhcpClient: Broadcasting DHCPDISCOVER
,08-23 23:12:49.386   874  4080 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172643, domain null
,08-23 23:12:49.387   874  2085 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172643 seconds
,08-23 23:12:49.392   874  2085 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-23 23:12:49.408   874  4080 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-23 23:12:49.409   874  2085 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-23 23:12:49.416   372   872 D CommandListener: Setting iface cfg
,08-23 23:12:49.427   874  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-23 23:12:49.428   874  2085 D DhcpClient: Scheduling renewal in 86399s
,08-23 23:12:49.431   874  1310 E native  : do suspend true
,08-23 23:12:49.448   874  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-23 23:12:49.451   874  1310 D WifiConfigStore: No blacklist allowed without epno enabled
,08-23 23:12:49.453   874  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-23 23:12:49.455   874  1312 D ConnectivityService: Adding iface wlan0 to network 101
,08-23 23:12:49.462   874  1310 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-23 23:12:49.519   874  1312 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-23 23:12:49.519   874  1312 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-23 23:12:49.521   874  1312 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-23 23:12:49.522   874  1312 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101,
,08-23 23:12:49.523   874  1312 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-23 23:12:49.542   874  1312 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-23 23:12:49.550   874  1312 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-23 23:12:49.550   874  1312 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-23 23:12:49.550   874  1312 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-23 23:12:49.550   874  1310 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-23 23:12:49.550   874  1312 D ConnectivityService:    accepting network in place of null
08-23 23:12:49.551   874  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-23 23:12:49.551   874  1312 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-23 23:12:49.564   874  4079 D NetlinkSocketObserver: NeighborEvent{elapsedMs=181726, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-23 23:12:49.582   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-23 23:12:49.615   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-23 23:12:49.625   874  1312 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-23 23:12:49.625   874  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-23 23:12:49.629   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-23 23:12:49.636   874  1312 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-23 23:12:49.641   874  4078 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.142,2a00:1450:4001:817::200e
,08-23 23:12:49.646  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 23:12:49.646  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 23:12:49.646  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:12:49.646  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:12:49.646  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 23:12:49.646  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 23:12:49.646  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 23:12:49.646  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 23:12:49.646  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 23:12:49.646  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 23:12:49.646  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 23:12:49.651  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 23:12:49.652  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 23:12:49.652  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:12:49.652  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:12:49.652  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 23:12:49.652  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 23:12:49.652  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 23:12:49.652  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 23:12:49.652  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 23:12:49.652  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 23:12:49.652  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 23:12:49.655  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 23:12:49.655  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 23:12:49.655  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:12:49.655  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:12:49.655  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 23:12:49.655  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 23:12:49.655  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 23:12:49.655  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 23:12:49.655  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 23:12:49.655  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 23:12:49.656  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 23:12:49.664  1980  1980 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-23 23:12:49.669  1722  1722 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-23 23:12:49.676  1722  1722 D SystemUpdateService: onCreate
,08-23 23:12:49.679  1722  1722 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-23 23:12:49.698  1722  4091 I SystemUpdateService: active receiver: enabled
,08-23 23:12:49.703  1722  1722 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-23 23:12:49.707  1722  2497 I iu.UploadsManager: num queued entries: 0
,08-23 23:12:49.707  1722  2497 I iu.UploadsManager: num updated entries: 0
,08-23 23:12:49.716  1722  4091 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-23 23:12:49.718  1722  1722 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-23 23:12:49.719  1722  1722 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-23 23:12:49.721  3951  3951 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-23 23:12:49.727   874  4078 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 23 Aug 2016 21:12:49 GMT], X-Android-Received-Millis=[1471986769727], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471986769696]}
,08-23 23:12:49.729   874  1312 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-23 23:12:49.729   874  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,08-23 23:12:49.729   874  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-23 23:12:49.730   874  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-23 23:12:49.733  1722  4093 I MDM     : [180] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-23 23:12:49.733  1722  4093 W BaseAppContext: Using Auth Proxy for data requests.
08-23 23:12:49.734  1722  4093 V GoogleAuthProtoRequest: [180] a.<init>: mAccountName set to: thalitester@gmail.com
08-23 23:12:49.738  3951  3951 D SprintDMHelper: simOperator: 
,08-23 23:12:49.738  3951  3951 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-23 23:12:49.741  1722  2497 I iu.SyncManager: NEXT; no task
,08-23 23:12:49.742  1722  4091 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,08-23 23:12:49.747  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 23:12:49.750  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-23 23:12:49.750  1722  4091 I SystemUpdateService: now status is 0 (complete)
,08-23 23:12:49.750  1722  4091 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-23 23:12:49.750  1722  4091 I SystemUpdateService: file has been verified
08-23 23:12:49.750  1722  4091 I SystemUpdateService: OTA package size = 12249756
,08-23 23:12:49.757  1722  4091 I SystemUpdateService: showing system update notification
,08-23 23:12:49.852  1722  1722 D SystemUpdateService: onDestroy
,08-23 23:12:49.855  1504  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-23 23:12:49.855  1504  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-23 23:12:49.855  1504  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 23:12:49.856  1504  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 23:12:49.880  1722  4093 E MDM     : [180] SitrepService.a: Error sending sitrep.
,08-23 23:12:49.884  3741  4090 V KeepSync: Connecting to GoogleApiClient
,08-23 23:12:49.885   874  1387 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-23 23:12:49.898  2398  4099 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-23 23:12:49.947  1504  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-23 23:12:49.947  1504  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-23 23:12:49.947  1504  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 23:12:49.947  1504  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 23:12:49.965  1722  4106 V BaseAuthAsyncOperation: access token request failed
,08-23 23:12:49.965  3741  4090 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-23 23:12:50.027  1504  2041 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-23 23:12:50.027  1504  2041 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-23 23:12:50.027  1504  2041 I GLSUser : [GLSUser] Extracting token using key: Auth,
08-23 23:12:50.027  1504  2041 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 23:12:50.043  3741  4090 E KeepSync: IOException
08-23 23:12:50.043  3741  4090 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-23 23:12:50.043  3741  4090 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-23 23:12:50.043  3741  4090 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-23 23:12:50.043  3741  4090 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-23 23:12:50.043  3741  4090 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-23 23:12:50.043  3741  4090 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-23 23:12:50.043  3741  4090 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-23 23:12:50.043  3741  4090 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-23 23:12:50.043  3741  4090 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-23 23:12:50.043  3741  4090 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-23 23:12:50.043  3741  4090 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-23 23:12:50.043  3741  4090 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-23 23:12:50.043  3741  4090 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-23 23:12:50.043  3741  4090 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-23 23:12:50.043  3741  4090 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-23 23:12:50.043  3741  4090 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-23 23:12:50.043  3741  4090 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-23 23:12:50.043  3741  4090 E KeepSync: 	... 10 more
08-23 23:12:50.043  3741  4090 W KeepSync: Sync result 2
,08-23 23:12:50.050   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 163614, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-23 23:12:50.624   874  1312 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-23 23:12:52.146   874  2003 D WifiService: setWifiEnabled: false pid=3801, uid=10000
,08-23 23:12:52.146   874  2003 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-23 23:12:52.186  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-23 23:12:52.196   874  1310 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-23 23:12:52.197   874  1310 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-23 23:12:52.198   874  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-23 23:12:52.199   874  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-23 23:12:52.222   874  1310 E native  : do suspend true
,08-23 23:12:52.236   874  2085 D DhcpClient: Clearing IP address
,08-23 23:12:52.237   372   872 D CommandListener: Setting iface cfg
,08-23 23:12:52.242   372   872 D CommandListener: Clearing all IP addresses on wlan0
,08-23 23:12:52.244   874  4080 D DhcpClient: Receive thread stopped
,08-23 23:12:52.247  1504  4103 V NativeCrypto: Read error: ssl=0x9a6f9e00: I/O error during system call, Connection timed out
,08-23 23:12:52.251  1504  4103 V NativeCrypto: SSL shutdown failed: ssl=0x9a6f9e00: I/O error during system call, Broken pipe
,08-23 23:12:52.254   874  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-23 23:12:52.254   874  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-23 23:12:52.255   874  1310 D WifiStateMachine: Start Disconnecting Watchdog 2
08-23 23:12:52.258   874  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-23 23:12:52.259   874  1310 E native  : do suspend true
08-23 23:12:52.265   397   397 E Parcel  : Reading a NULL string not supported here.
,08-23 23:12:52.279   874  1312 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-23 23:12:52.280   372   872 D CommandListener: Clearing all IP addresses on wlan0
,08-23 23:12:52.289   874  1310 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-23 23:12:52.310   874  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,08-23 23:12:52.312  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 23:12:52.312  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 23:12:52.312  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:12:52.312  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:12:52.312  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 23:12:52.312  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 23:12:52.312  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 23:12:52.312  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 23:12:52.312  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 23:12:52.313  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 23:12:52.313  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 23:12:52.313  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 23:12:52.314  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 23:12:52.314  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:12:52.314  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:12:52.314  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 23:12:52.314  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 23:12:52.314  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 23:12:52.314  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 23:12:52.314  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 23:12:52.314  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 23:12:52.314  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 23:12:52.315  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 23:12:52.315  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 23:12:52.315  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:12:52.315  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:12:52.315  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 23:12:52.315  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 23:12:52.315  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 23:12:52.315  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 23:12:52.315  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 23:12:52.315  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 23:12:52.315  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 23:12:52.321  2162  2327 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 23:12:52.329   874  1310 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-23 23:12:52.334   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-23 23:12:52.365   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-23 23:12:52.366   874  1312 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-23 23:12:52.366   874  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-23 23:12:52.367   874   891 D Tethering: MasterInitialState.processMessage what=3,
08-23 23:12:52.370  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 23:12:52.370  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 23:12:52.371  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 23:12:52.374  1980  1980 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-23 23:12:52.379  1722  1722 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-23 23:12:52.383  1722  1722 D SystemUpdateService: onCreate
,08-23 23:12:52.394  1722  1722 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-23 23:12:52.403  1722  1722 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-23 23:12:52.410  1722  2497 I iu.UploadsManager: num queued entries: 0
,08-23 23:12:52.410  1722  2497 I iu.UploadsManager: num updated entries: 0
08-23 23:12:52.411  1722  2497 I iu.SyncManager: NEXT; no task
,08-23 23:12:52.414  1722  1722 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-23 23:12:52.415  1722  1722 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-23 23:12:52.417  3951  3951 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-23 23:12:52.421  3951  3951 D SprintDMHelper: simOperator: 
,08-23 23:12:52.421  3951  3951 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-23 23:12:52.427   372   872 E Netd    : netlink response contains error (No such file or directory)
08-23 23:12:52.428   874  1312 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-23 23:12:52.448  2398  4120 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-23 23:12:52.453  1722  4116 I SystemUpdateService: active receiver: enabled
,08-23 23:12:52.455  1722  4116 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-23 23:12:52.457  1722  4116 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,08-23 23:12:52.458  1722  4116 I SystemUpdateService: now status is 0 (complete)
08-23 23:12:52.458  1722  4116 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-23 23:12:52.458  1722  4116 I SystemUpdateService: file has been verified
,08-23 23:12:52.459  1722  4116 I SystemUpdateService: OTA package size = 12249756
,08-23 23:12:52.465  1722  4116 I SystemUpdateService: showing system update notification
,08-23 23:12:52.491  1722  1722 D SystemUpdateService: onDestroy
,08-23 23:12:52.548  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 23:12:52.577  1504  2985 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-23 23:12:52.577  1504  2985 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-23 23:12:52.577  1504  2985 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 23:12:52.577  1504  2985 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 23:12:52.597  3524  3524 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-23 23:12:52.597  3524  3524 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-23 23:12:52.597  3524  3524 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-23 23:12:57.202   874   891 I ActivityManager: Start proc 4123:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-23 23:12:57.348  4123  4123 D AdapterServiceConfig: Adding HeadsetService
08-23 23:12:57.348  4123  4123 D AdapterServiceConfig: Adding A2dpService
08-23 23:12:57.349  4123  4123 D AdapterServiceConfig: Adding HidService
08-23 23:12:57.349  4123  4123 D AdapterServiceConfig: Adding HealthService
08-23 23:12:57.349  4123  4123 D AdapterServiceConfig: Adding PanService
08-23 23:12:57.349  4123  4123 D AdapterServiceConfig: Adding GattService
08-23 23:12:57.350  4123  4123 D AdapterServiceConfig: Adding BluetoothMapService
,08-23 23:12:57.365   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@77b05d8:true
,08-23 23:12:57.366  4123  4123 D BluetoothAdapterState: make() - Creating AdapterState
,08-23 23:12:57.374  4123  4137 I BluetoothAdapterState: Entering OffState
,08-23 23:12:57.374  4123  4123 I bt_bluedroid: init
,08-23 23:12:57.377  4123  4138 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-23 23:12:57.378  4123  4138 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-23 23:12:57.378  4123  4138 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-23 23:12:57.378  4123  4138 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-23 23:12:57.379  4123  4123 I bt_bluedroid: get_profile_interface socket
,08-23 23:12:57.381  4123  4141 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-23 23:12:57.383  4123  4141 D BluetoothAdapterProperties: Name is: Nexus 6
,08-23 23:12:57.384  4123  4123 I bt_bluedroid: get_profile_interface sdp
,08-23 23:12:57.391  4123  4134 I bt_bluedroid: config_hci_snoop_log
,08-23 23:12:57.393   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-23 23:12:57.402  4123  4137 D BluetoothAdapterState: Current state: OFF, message: 0
,08-23 23:12:57.402  4123  4137 D BluetoothAdapterProperties: Setting state to 14
08-23 23:12:57.403  4123  4137 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-23 23:12:57.405  4123  4137 D BluetoothBondStateMachine: make
,08-23 23:12:57.411  4123  4142 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-23 23:12:57.417  4123  4137 I BluetoothAdapterState: Entering PendingCommandState
,08-23 23:12:57.419  4123  4123 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-23 23:12:57.424  4123  4123 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2286885
,08-23 23:12:57.425  4123  4123 D BtGatt.DebugUtils: handleDebugAction() action=null
08-23 23:12:57.425  4123  4123 D BtGatt.GattService: Received start request. Starting profile...
,08-23 23:12:57.425  4123  4123 D BtGatt.GattService: start()
08-23 23:12:57.426  4123  4123 I bt_bluedroid: get_profile_interface gatt
08-23 23:12:57.427  4123  4123 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2286885
08-23 23:12:57.427  4123  4123 D BtGatt.AdvertiseManager: advertise manager created
,08-23 23:12:57.441  4123  4123 V BluetoothAdapterState: isTurningOff()=false
08-23 23:12:57.442  4123  4123 V BluetoothAdapterState: isTurningOn()=false
08-23 23:12:57.442  4123  4123 V BluetoothAdapterState: isBleTurningOn()=true
08-23 23:12:57.442  4123  4123 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 23:12:57.442  4123  4137 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-23 23:12:57.443  4123  4137 I bt_bluedroid: enable
08-23 23:12:57.443  4123  4138 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-23 23:12:57.444  4123  4138 I bt_hci  : start_up
,08-23 23:12:57.452  4123  4138 I bt_vendor: alloc value 0xb39da189
,08-23 23:12:57.452  4123  4138 I bt_vendor: init
08-23 23:12:57.452  4123  4138 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-23 23:12:57.452  4123  4138 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-23 23:12:57.556   874  1312 D ConnectivityService: handlePromptUnvalidated 101
,08-23 23:12:57.561  4123  4138 D bt_hci  : start_up starting async portion
,08-23 23:12:57.561  4123  4145 I bt_hci  : event_finish_startup
08-23 23:12:57.562  4123  4145 I bt_hci_h4: hal_open
08-23 23:12:57.562  4123  4145 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-23 23:12:57.570  4123  4145 I bt_userial_vendor: device fd = 51 open
,08-23 23:12:57.609  4123  4145 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-23 23:12:57.634  4123  4145 D bt_hwcfg: Chipset BCM4354A2
,08-23 23:12:57.636  4123  4145 D bt_hwcfg: Target name = [BCM4354A2]
,08-23 23:12:57.636  4123  4145 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-23 23:12:58.182  4123  4145 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-23 23:12:58.184  4123  4145 D bt_hwcfg: Settlement delay -- 100 ms,
,08-23 23:12:58.184  4123  4145 I bt_hwcfg: Setting fw settlement delay to 100 
,08-23 23:12:58.300  4123  4145 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-23 23:12:58.302  4123  4145 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-23 23:12:58.331  4123  4145 I bt_hwcfg: vendor lib fwcfg completed
,08-23 23:12:58.331  4123  4145 I bt_vendor: firmware callback
08-23 23:12:58.332  4123  4145 I bt_hci  : firmware_config_callback
,08-23 23:12:58.343  4123  4147 I bt_btu  : btu_task pending for preload complete event
,08-23 23:12:58.343  4123  4147 I bt_btu_task: Bluetooth chip preload is complete
08-23 23:12:58.344  4123  4147 I bt_btu  : btu_task received preload complete event
,08-23 23:12:58.355  4123  4147 I         : BTE_InitTraceLevels -- TRC_HCI
08-23 23:12:58.356  4123  4147 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-23 23:12:58.356  4123  4147 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-23 23:12:58.356  4123  4147 I         : BTE_InitTraceLevels -- TRC_AVDT
08-23 23:12:58.357  4123  4147 I         : BTE_InitTraceLevels -- TRC_AVRC
08-23 23:12:58.357  4123  4147 I         : BTE_InitTraceLevels -- TRC_A2D
,08-23 23:12:58.357  4123  4147 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-23 23:12:58.358  4123  4147 I         : BTE_InitTraceLevels -- TRC_BTM
,08-23 23:12:58.358  4123  4147 I         : BTE_InitTraceLevels -- TRC_GAP
08-23 23:12:58.358  4123  4147 I         : BTE_InitTraceLevels -- TRC_PAN
08-23 23:12:58.359  4123  4147 I         : BTE_InitTraceLevels -- TRC_SDP
08-23 23:12:58.359  4123  4147 I         : BTE_InitTraceLevels -- TRC_GATT
08-23 23:12:58.359  4123  4147 I         : BTE_InitTraceLevels -- TRC_SMP
08-23 23:12:58.359  4123  4147 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-23 23:12:58.360  4123  4147 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-23 23:12:58.498  4123  4147 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3957d9d
,08-23 23:12:58.499  4123  4147 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3957d9d ,
,08-23 23:12:58.507  4123  4141 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false,
08-23 23:12:58.509  4123  4141 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000,
08-23 23:12:58.511  4123  4141 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-23 23:12:58.516  4123  4141 D BluetoothAdapterProperties: Name is: Nexus 6
,08-23 23:12:58.519  4123  4141 D BluetoothAdapterProperties: Scan Mode:20
,08-23 23:12:58.519  4123  4141 D BluetoothAdapterProperties: Discoverable Timeout:120
08-23 23:12:58.519  4123  4141 D bt_hci  : do_postload posting postload work item
,08-23 23:12:58.520  4123  4145 I bt_hci  : event_postload
08-23 23:12:58.520  4123  4145 I bt_vendor: sco_config_cb
,08-23 23:12:58.520  4123  4145 I bt_hci  : sco_config_callback postload finished.
08-23 23:12:58.523  4123  4141 D bt_bte_conf: Device ID record 1 : primary
,08-23 23:12:58.523  4123  4141 D bt_bte_conf:   vendorId            = 000f
,08-23 23:12:58.524  4123  4141 D bt_bte_conf:   vendorIdSource      = 0001
08-23 23:12:58.524  4123  4141 D bt_bte_conf:   product             = 1200
08-23 23:12:58.524  4123  4141 D bt_bte_conf:   version             = 1436
08-23 23:12:58.524  4123  4141 D bt_bte_conf:   clientExecutableURL = ,
08-23 23:12:58.524  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 23:12:58.524  4123  4141 D bt_bte_conf:   serviceDescription  = 
08-23 23:12:58.525  4123  4141 D bt_bte_conf:   documentationURL    = 
,08-23 23:12:58.525  4123  4141 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-23 23:12:58.525  4123  4138 D bt_stack_manager: event_start_up_stack finished
08-23 23:12:58.527  4123  4137 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-23 23:12:58.527  4123  4137 D BluetoothAdapterProperties: Setting state to 15
08-23 23:12:58.529  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 23:12:58.530  4123  4137 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-23 23:12:58.530  4123  4145 I bt_vendor: low_power_mode_cb
08-23 23:12:58.533  4123  4137 I BluetoothAdapterState: Entering BleOnState
,08-23 23:12:58.535  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 23:12:58.536  4123  4137 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-23 23:12:58.536  4123  4137 D BluetoothAdapterProperties: Setting state to 11
,08-23 23:12:58.536  4123  4137 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-23 23:12:58.541  4123  4123 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2286885
08-23 23:12:58.542  4123  4123 D HeadsetService: Received start request. Starting profile...
,08-23 23:12:58.544  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 23:12:58.545  4123  4123 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-23 23:12:58.545  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 23:12:58.545  4123  4123 D HeadsetStateMachine: make
,08-23 23:12:58.547  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 23:12:58.556  4123  4123 D HeadsetStateMachine: max_hf_connections = 1
08-23 23:12:58.557  4123  4123 I bt_bluedroid: get_profile_interface handsfree
08-23 23:12:58.557  4123  4137 I BluetoothAdapterState: Entering PendingCommandState
,08-23 23:12:58.558  4123  4141 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-23 23:12:58.558  4123  4141 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-23 23:12:58.563  4123  4123 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2286885
,08-23 23:12:58.564  4123  4123 D A2dpService: Received start request. Starting profile...
08-23 23:12:58.564  4123  4123 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-23 23:12:58.565  4123  4123 I bt_bluedroid: get_profile_interface avrcp
,08-23 23:12:58.571  4123  4123 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-23 23:12:58.571  4123  4123 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-23 23:12:58.571  4123  4123 D A2dpStateMachine: make
,08-23 23:12:58.573  4123  4123 I bt_bluedroid: get_profile_interface a2dp
,08-23 23:12:58.574  4123  4141 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-23 23:12:58.579  4123  4156 D A2dpStateMachine: Enter Disconnected: -2
,08-23 23:12:58.580  4123  4123 I BluetoothHidServiceJni: classInitNative: succeeds
,08-23 23:12:58.581  4123  4123 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2286885
08-23 23:12:58.582  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-23 23:12:58.583  4123  4123 D HidService: Received start request. Starting profile...
,08-23 23:12:58.583  4123  4123 I bt_bluedroid: get_profile_interface hidhost
08-23 23:12:58.583  4123  4123 D HidService: setHidService(): set to: null
08-23 23:12:58.583  4123  4141 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39393e5
08-23 23:12:58.583  3897  3897 D BluetoothInputDevice: Proxy object connected
08-23 23:12:58.583  4123  4141 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-23 23:12:58.585  3897  3897 D HidProfile: Bluetooth service connected
,08-23 23:12:58.586  4123  4123 I BluetoothHealthServiceJni: classInitNative: succeeds
08-23 23:12:58.587  4123  4123 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2286885
08-23 23:12:58.587  4123  4123 D HealthService: Received start request. Starting profile...
,08-23 23:12:58.590  4123  4123 I bt_bluedroid: get_profile_interface health
,08-23 23:12:58.591  4123  4123 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-23 23:12:58.592  4123  4123 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2286885
,08-23 23:12:58.593  4123  4123 D PanService: Received start request. Starting profile...
,08-23 23:12:58.593  4123  4123 D BluetoothPanServiceJni: initializeNative(L110): pan
08-23 23:12:58.593  3897  3897 D BluetoothPan: BluetoothPAN Proxy object connected
,08-23 23:12:58.594  4123  4123 I bt_bluedroid: get_profile_interface pan
08-23 23:12:58.595  4123  4141 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-23 23:12:58.596  3897  3897 D PanProfile: Bluetooth service connected
,08-23 23:12:58.601  4123  4123 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2286885
,08-23 23:12:58.604  4123  4123 D BluetoothMapService: Received start request. Starting profile...
,08-23 23:12:58.604  4123  4123 D BluetoothMapService: start()
,08-23 23:12:58.604  3897  3897 D BluetoothMap: Proxy object connected
08-23 23:12:58.605  3897  3897 D MapProfile: Bluetooth service connected
,08-23 23:12:58.605  3897  3897 D BluetoothMap: getConnectedDevices()
08-23 23:12:58.606  3897  3897 D BluetoothMap: Bluetooth is Not enabled
08-23 23:12:58.607  4123  4123 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-23 23:12:58.608  4123  4123 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-23 23:12:58.608  4123  4123 D BluetoothMapAppObserver: createReceiver()
,08-23 23:12:58.610  4123  4123 D BluetoothMapAppObserver: initObservers()
,08-23 23:12:58.610  4123  4123 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-23 23:12:58.618  4123  4123 V BluetoothAdapterState: isTurningOff()=false
08-23 23:12:58.618  4123  4123 V BluetoothAdapterState: isTurningOn()=true
,08-23 23:12:58.618  4123  4123 V BluetoothAdapterState: isBleTurningOn()=false
08-23 23:12:58.618  4123  4123 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 23:12:58.621  4123  4154 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-23 23:12:58.622  4123  4123 V BluetoothAdapterState: isTurningOff()=false
,08-23 23:12:58.622  4123  4123 V BluetoothAdapterState: isTurningOn()=true
08-23 23:12:58.622  4123  4123 V BluetoothAdapterState: isBleTurningOn()=false
08-23 23:12:58.622  4123  4123 V BluetoothAdapterState: isBleTurningOff()=false
08-23 23:12:58.622  4123  4123 V BluetoothAdapterState: isTurningOff()=false
08-23 23:12:58.622  4123  4123 V BluetoothAdapterState: isTurningOn()=true
08-23 23:12:58.622  4123  4123 V BluetoothAdapterState: isBleTurningOn()=false
08-23 23:12:58.622  4123  4123 V BluetoothAdapterState: isBleTurningOff()=false
08-23 23:12:58.625  4123  4123 V BluetoothAdapterState: isTurningOff()=false
,08-23 23:12:58.625  4123  4123 V BluetoothAdapterState: isTurningOn()=true
08-23 23:12:58.625  4123  4123 V BluetoothAdapterState: isBleTurningOn()=false
08-23 23:12:58.625  4123  4123 V BluetoothAdapterState: isBleTurningOff()=false
08-23 23:12:58.625  4123  4123 V BluetoothAdapterState: isTurningOff()=false
,08-23 23:12:58.625  4123  4123 V BluetoothAdapterState: isTurningOn()=true
08-23 23:12:58.625  4123  4123 V BluetoothAdapterState: isBleTurningOn()=false
08-23 23:12:58.626  4123  4123 V BluetoothAdapterState: isBleTurningOff()=false
08-23 23:12:58.626  4123  4123 V BluetoothAdapterState: isTurningOff()=false
08-23 23:12:58.626  4123  4123 V BluetoothAdapterState: isTurningOn()=true
08-23 23:12:58.626  4123  4123 V BluetoothAdapterState: isBleTurningOn()=false
08-23 23:12:58.626  4123  4123 V BluetoothAdapterState: isBleTurningOff()=false
08-23 23:12:58.627  4123  4137 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-23 23:12:58.627  4123  4137 D BluetoothAdapterProperties: ScanMode =  20
,08-23 23:12:58.627  4123  4137 D BluetoothAdapterProperties: State =  11
08-23 23:12:58.628  4123  4137 D BluetoothAdapterProperties: Setting state to 12
08-23 23:12:58.628  4123  4137 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-23 23:12:58.628  4123  4137 I BluetoothAdapterState: Entering OnState
08-23 23:12:58.628  1355  2008 D BluetoothPbap: onBluetoothStateChange: up=true
08-23 23:12:58.630  4123  4141 D BluetoothAdapterProperties: Scan Mode:21
08-23 23:12:58.630  4123  4141 D BluetoothAdapterProperties: Discoverable Timeout:120
08-23 23:12:58.633  3897  3909 D BluetoothPbap: onBluetoothStateChange: up=true
08-23 23:12:58.634  1355  1368 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-23 23:12:58.635  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 23:12:58.635  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:12:58.635  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:12:58.635  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 23:12:58.635  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 23:12:58.635  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 23:12:58.635  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 23:12:58.635  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 23:12:58.635  3897  3908 D BluetoothMap: onBluetoothStateChange: up=true
08-23 23:12:58.636  1355  1366 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-23 23:12:58.637  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 23:12:58.639  4123  4123 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-23 23:12:58.640  4123  4123 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-23 23:12:58.640  1355  1355 D BluetoothInputDevice: Proxy object connected
,08-23 23:12:58.640  1355  1355 D HidProfile: Bluetooth service connected
,08-23 23:12:58.641  1355  1368 D BluetoothMap: onBluetoothStateChange: up=true
,08-23 23:12:58.642  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 23:12:58.642  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:12:58.642  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:12:58.642  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 23:12:58.642  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 23:12:58.642  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 23:12:58.642  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 23:12:58.642  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 23:12:58.643  4123  4123 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 23:12:58.643  1355  1366 D BluetoothA2dp: onBluetoothStateChange: up=true
08-23 23:12:58.645  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 23:12:58.646  1355  2008 D BluetoothPan: onBluetoothStateChange on: true
08-23 23:12:58.648  1355  1355 D BluetoothMap: Proxy object connected
08-23 23:12:58.648  1923  1933 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 23:12:58.648  1355  1355 D MapProfile: Bluetooth service connected
08-23 23:12:58.648  1355  1355 D BluetoothMap: getConnectedDevices()
,08-23 23:12:58.648  4123  4123 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 23:12:58.648   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 23:12:58.649  3897  3909 D BluetoothPan: onBluetoothStateChange on: true
08-23 23:12:58.649   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
08-23 23:12:58.650  4123  4123 D ObexServerSockets: Succeed to create listening sockets 
08-23 23:12:58.650  4123  4123 D ObexServerSockets0: startAccept()
08-23 23:12:58.650  4123  4123 D ObexServerSockets0: prepareForNewConnect()
,08-23 23:12:58.650  1355  1355 D BluetoothPan: BluetoothPAN Proxy object connected
08-23 23:12:58.650  1355  1355 D PanProfile: Bluetooth service connected
08-23 23:12:58.651   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 23:12:58.651   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 23:12:58.651  3897  3908 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-23 23:12:58.653  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 23:12:58.653  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:12:58.653  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:12:58.653  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 23:12:58.653  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 23:12:58.653  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 23:12:58.653  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 23:12:58.653  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 23:12:58.656   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
08-23 23:12:58.658  4123  4123 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-23 23:12:58.658  4123  4123 D BluetoothSdpJni: SDP Create record success - handle: 0
08-23 23:12:58.659  3897  3897 D LocalBluetoothProfileManager: Adding local A2DP profile
08-23 23:12:58.660  4123  4163 D ObexServerSockets0: Accepting socket connection...
,08-23 23:12:58.660  4123  4164 D ObexServerSockets0: Accepting socket connection...
08-23 23:12:58.660   874   874 D BluetoothA2dp: Proxy object connected
08-23 23:12:58.661  4123  4123 D BluetoothMapService: onReceive
08-23 23:12:58.661  4123  4123 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-23 23:12:58.661  4123  4123 D BluetoothMapService: STATE_ON
08-23 23:12:58.661  1355  1355 D BluetoothA2dp: Proxy object connected
08-23 23:12:58.663  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 23:12:58.666  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 23:12:58.669  3897  3897 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-23 23:12:58.669  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 23:12:58.671  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 23:12:58.676  3897  3897 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-23 23:12:58.679  3897  3897 D BluetoothA2dp: Proxy object connected
,08-23 23:12:58.684  4123  4123 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-23 23:12:58.684  4123  4123 D ObexServerSockets0: prepareForNewConnect()
,08-23 23:12:58.692  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-23 23:12:58.697  1355  1355 D BluetoothPbap: Proxy object connected
08-23 23:12:58.697  1355  1355 D PbapServerProfile: Bluetooth service connected
,08-23 23:12:58.701  4123  4166 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 23:12:58.704  3897  3897 D DockEventReceiver: finishStartingService: stopping service
,08-23 23:12:58.705  3897  3897 D BluetoothPbap: Proxy object connected
08-23 23:12:58.705  3897  3897 D PbapServerProfile: Bluetooth service connected
,08-23 23:12:58.730  4123  4172 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 23:12:58.731  4123  4172 I BtOppRfcommListener: Accept thread started.
,08-23 23:12:58.737  1923  1939 D BluetoothHeadset: Proxy object connected
08-23 23:12:58.737  1355  1366 D BluetoothHeadset: Proxy object connected
08-23 23:12:58.737   874   874 D BluetoothHeadset: Proxy object connected
08-23 23:12:58.738  1355  1355 D HeadsetProfile: Bluetooth service connected
08-23 23:12:58.738   874   874 D BluetoothHeadset: Proxy object connected
08-23 23:12:58.738   874   874 D BluetoothHeadset: Proxy object connected
,08-23 23:12:58.748  1923  2256 D BluetoothHeadset: Proxy object connected
08-23 23:12:58.748   874   891 D BluetoothHeadset: Proxy object connected
,08-23 23:12:58.751   874   891 D BluetoothHeadset: Proxy object connected
08-23 23:12:58.751   874   891 D BluetoothHeadset: Proxy object connected
,08-23 23:12:58.772  3897  3908 D BluetoothHeadset: Proxy object connected
,08-23 23:12:58.773  3897  3897 D HeadsetProfile: Bluetooth service connected
,08-23 23:13:02.163  4123  4137 D BluetoothAdapterState: Current state: ON, message: 23
,08-23 23:13:02.163  4123  4137 D BluetoothAdapterProperties: Setting state to 13
,08-23 23:13:02.164  4123  4137 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-23 23:13:02.165  4123  4137 D BluetoothAdapterProperties: onBluetoothDisable()
,08-23 23:13:02.172  4123  4137 I BluetoothAdapterState: Entering PendingCommandState
,08-23 23:13:02.180  4123  4123 D BluetoothMapService: onReceive
08-23 23:13:02.181  4123  4123 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-23 23:13:02.181  4123  4123 D BluetoothMapService: STATE_TURNING_OFF
,08-23 23:13:02.182  4123  4123 D BluetoothMapService: MAP Service closeService in
08-23 23:13:02.182  4123  4123 D BluetoothMapMasInstance0: MAP Service shutdown
08-23 23:13:02.182  4123  4141 D BluetoothAdapterProperties: Scan Mode:20
,08-23 23:13:02.182  4123  4123 D ObexServerSockets0: shutdown(block = true)
,08-23 23:13:02.182  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 23:13:02.183  4123  4163 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-23 23:13:02.183  4123  4137 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-23 23:13:02.183  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 23:13:02.183  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:13:02.183  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:13:02.183  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 23:13:02.183  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 23:13:02.183  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 23:13:02.183  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 23:13:02.183  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 23:13:02.186  4123  4123 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-23 23:13:02.187  4123  4164 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-23 23:13:02.188  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 23:13:02.188  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 23:13:02.189  4123  4123 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-23 23:13:02.190  4123  4150 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-23 23:13:02.192  4123  4123 I BtOppRfcommListener: stopping Accept Thread
,08-23 23:13:02.192  4123  4172 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-23 23:13:02.194  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 23:13:02.194  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 23:13:02.194  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:13:02.194  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:13:02.194  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 23:13:02.194  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 23:13:02.194  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 23:13:02.194  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 23:13:02.194  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 23:13:02.194  4123  4172 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-23 23:13:02.195  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 23:13:02.195  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 23:13:02.197  3897  3897 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-23 23:13:02.197  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 23:13:02.197  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 23:13:02.197  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:13:02.197  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:13:02.197  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 23:13:02.197  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 23:13:02.197  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 23:13:02.197  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 23:13:02.197  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 23:13:02.197  4123  4123 D HeadsetService: Received stop request...Stopping profile...
08-23 23:13:02.198  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 23:13:02.198  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 23:13:02.201  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 23:13:02.202  3897  3909 D BluetoothHeadset: Proxy object disconnected
08-23 23:13:02.202  1923  2087 D BluetoothHeadset: Proxy object disconnected
08-23 23:13:02.202  4123  4123 D A2dpService: Received stop request...Stopping profile...
,08-23 23:13:02.202  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 23:13:02.203  4123  4156 D A2dpStateMachine: Exit Disconnected: -1
,08-23 23:13:02.203  1355  2008 D BluetoothHeadset: Proxy object disconnected
08-23 23:13:02.204   874   874 D BluetoothHeadset: Proxy object disconnected
08-23 23:13:02.204  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 23:13:02.204   874   874 D BluetoothHeadset: Proxy object disconnected
08-23 23:13:02.204   874   874 D BluetoothHeadset: Proxy object disconnected
08-23 23:13:02.205   874   874 D BluetoothA2dp: Proxy object disconnected
08-23 23:13:02.206  1355  1355 D HeadsetProfile: Bluetooth service disconnected
08-23 23:13:02.206  1355  1355 D BluetoothA2dp: Proxy object disconnected
08-23 23:13:02.207  4123  4123 D HidService: Received stop request...Stopping profile...
08-23 23:13:02.207  4123  4123 D HidService: Stopping Bluetooth HidService
,08-23 23:13:02.208  1355  1355 D BluetoothInputDevice: Proxy object disconnected
08-23 23:13:02.208  1355  1355 D HidProfile: Bluetooth service disconnected
08-23 23:13:02.209  4123  4123 D HealthService: Received stop request...Stopping profile...
08-23 23:13:02.209  3897  3897 D DockEventReceiver: finishStartingService: stopping service
08-23 23:13:02.210  4123  4123 D PanService: Received stop request...Stopping profile...
08-23 23:13:02.211  1355  1355 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-23 23:13:02.211  1355  1355 D PanProfile: Bluetooth service disconnected
08-23 23:13:02.211  4123  4123 V BluetoothAdapterState: isTurningOff()=true
08-23 23:13:02.211  3897  3897 D HeadsetProfile: Bluetooth service disconnected
,08-23 23:13:02.211  4123  4123 V BluetoothAdapterState: isTurningOn()=false
08-23 23:13:02.212  3897  3897 D BluetoothA2dp: Proxy object disconnected
08-23 23:13:02.212  3897  3897 D BluetoothInputDevice: Proxy object disconnected
08-23 23:13:02.212  3897  3897 D HidProfile: Bluetooth service disconnected
,08-23 23:13:02.212  4123  4123 V BluetoothAdapterState: isBleTurningOn()=false
08-23 23:13:02.215  3897  3897 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-23 23:13:02.218  3897  3897 D PanProfile: Bluetooth service disconnected
08-23 23:13:02.218  4123  4123 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 23:13:02.219  4123  4123 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-23 23:13:02.219  4123  4123 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-23 23:13:02.219  4123  4141 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-23 23:13:02.220  4123  4147 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-23 23:13:02.220  4123  4147 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-23 23:13:02.220  4123  4147 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-23 23:13:02.220  4123  4141 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-23 23:13:02.221  4123  4123 D BluetoothMapService: Received stop request...Stopping profile...
,08-23 23:13:02.221  4123  4123 D BluetoothMapService: stop()
08-23 23:13:02.222  4123  4123 D BluetoothMapAppObserver: deinitObservers()
08-23 23:13:02.222  4123  4123 D BluetoothMapAppObserver: removeReceiver()
,08-23 23:13:02.224  3897  3897 D BluetoothMap: Proxy object disconnected
,08-23 23:13:02.225  3897  3897 D MapProfile: Bluetooth service disconnected
08-23 23:13:02.225  1355  1355 D BluetoothMap: Proxy object disconnected
08-23 23:13:02.225  1355  1355 D MapProfile: Bluetooth service disconnected
,08-23 23:13:02.227  4123  4123 V BluetoothAdapterState: isTurningOff()=true
,08-23 23:13:02.227  4123  4123 V BluetoothAdapterState: isTurningOn()=false
08-23 23:13:02.227  4123  4123 V BluetoothAdapterState: isBleTurningOn()=false
08-23 23:13:02.227  4123  4123 V BluetoothAdapterState: isBleTurningOff()=false
08-23 23:13:02.228  4123  4147 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-23 23:13:02.228  4123  4147 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-23 23:13:02.228  4123  4123 V BluetoothAdapterState: isTurningOff()=true
08-23 23:13:02.228  4123  4123 V BluetoothAdapterState: isTurningOn()=false
08-23 23:13:02.228  4123  4147 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 23:13:02.228  4123  4123 V BluetoothAdapterState: isBleTurningOn()=false
08-23 23:13:02.228  4123  4147 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 23:13:02.228  4123  4147 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 23:13:02.228  4123  4123 V BluetoothAdapterState: isBleTurningOff()=false
08-23 23:13:02.228  4123  4147 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 23:13:02.228  4123  4141 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-23 23:13:02.229  4123  4123 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-23 23:13:02.229  4123  4123 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-23 23:13:02.229  4123  4123 V BluetoothAdapterState: isTurningOff()=true
08-23 23:13:02.229  4123  4123 V BluetoothAdapterState: isTurningOn()=false
08-23 23:13:02.229  4123  4123 V BluetoothAdapterState: isBleTurningOn()=false
08-23 23:13:02.229  4123  4123 V BluetoothAdapterState: isBleTurningOff()=false
08-23 23:13:02.229  4123  4141 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-23 23:13:02.229  4123  4123 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-23 23:13:02.229  4123  4141 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-23 23:13:02.229  4123  4123 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-23 23:13:02.230  4123  4123 V BluetoothAdapterState: isTurningOff()=true
08-23 23:13:02.230  4123  4123 V BluetoothAdapterState: isTurningOn()=false
08-23 23:13:02.230  4123  4123 V BluetoothAdapterState: isBleTurningOn()=false
,08-23 23:13:02.230  4123  4123 V BluetoothAdapterState: isBleTurningOff()=false
08-23 23:13:02.230  4123  4123 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-23 23:13:02.230  4123  4123 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-23 23:13:02.231  4123  4123 D BluetoothMapService: MAP Service closeService in
08-23 23:13:02.231  4123  4123 V BluetoothAdapterState: isTurningOff()=true
08-23 23:13:02.231  4123  4123 V BluetoothAdapterState: isTurningOn()=false
08-23 23:13:02.231  4123  4123 V BluetoothAdapterState: isBleTurningOn()=false
08-23 23:13:02.231  4123  4123 V BluetoothAdapterState: isBleTurningOff()=false
08-23 23:13:02.231  4123  4123 D BluetoothMapService: cleanup()
08-23 23:13:02.231  4123  4123 D BluetoothMapService: MAP Service closeService in
08-23 23:13:02.231  4123  4137 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-23 23:13:02.231  4123  4137 D BluetoothAdapterProperties: Setting state to 15
08-23 23:13:02.231  4123  4137 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-23 23:13:02.232  4123  4137 I BluetoothAdapterState: Entering BleOnState
,08-23 23:13:02.233  1355  2008 D BluetoothPbap: onBluetoothStateChange: up=false
08-23 23:13:02.234  3897  3909 D BluetoothPbap: onBluetoothStateChange: up=false
08-23 23:13:02.234  1355  1366 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 23:13:02.235  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-23 23:13:02.235  3897  3908 D BluetoothMap: onBluetoothStateChange: up=false
08-23 23:13:02.236  1355  1368 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-23 23:13:02.236  1355  2008 D BluetoothMap: onBluetoothStateChange: up=false
,08-23 23:13:02.239  1355  1366 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-23 23:13:02.240  1355  1368 D BluetoothPan: onBluetoothStateChange on: false
,08-23 23:13:02.241  3897  3909 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 23:13:02.241  3897  3908 D BluetoothA2dp: onBluetoothStateChange: up=false
08-23 23:13:02.241  1923  1933 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 23:13:02.242   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-23 23:13:02.242  3897  3909 D BluetoothPan: onBluetoothStateChange on: false
08-23 23:13:02.242   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
08-23 23:13:02.242   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 23:13:02.243   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 23:13:02.243  3897  3908 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-23 23:13:02.244  4123  4137 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-23 23:13:02.244  4123  4137 D BluetoothAdapterProperties: Setting state to 16
,08-23 23:13:02.244  4123  4137 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-23 23:13:02.244  4123  4137 D BluetoothAdapterProperties: onBleDisable
08-23 23:13:02.246  4123  4137 I BluetoothAdapterState: Entering PendingCommandState
08-23 23:13:02.246  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 23:13:02.247  4123  4138 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-23 23:13:02.248  4123  4147 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-23 23:13:02.248  4123  4147 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-23 23:13:02.248  4123  4141 D BluetoothAdapterProperties: Scan Mode:20
08-23 23:13:02.248  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 23:13:02.249  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 23:13:02.249  3897  3897 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-23 23:13:02.250  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 23:13:02.252  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 23:13:02.253  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 23:13:02.254  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-23 23:13:02.260  3897  3897 D DockEventReceiver: finishStartingService: stopping service
,08-23 23:13:02.452  4123  4141 I bt_hci  : shut_down
,08-23 23:13:02.452  4123  4145 D bt_hwcfg: hw_epilog_process
,08-23 23:13:02.467  4123  4145 I bt_vendor: low_power_mode_cb
,08-23 23:13:02.487  4123  4145 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-23 23:13:02.487  4123  4145 I bt_vendor: epilog_cb
08-23 23:13:02.487  4123  4145 I bt_hci  : epilog_finished_callback
,08-23 23:13:02.494  4123  4141 I bt_hci_h4: hal_close
,08-23 23:13:02.496  4123  4141 I bt_userial_vendor: device fd = 51 close
,08-23 23:13:02.615  4123  4138 D bt_stack_manager: event_shut_down_stack finished.
,08-23 23:13:02.616  4123  4137 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-23 23:13:02.622  4123  4123 D BtGatt.DebugUtils: handleDebugAction() action=null
08-23 23:13:02.623  4123  4137 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-23 23:13:02.624  4123  4123 D BtGatt.GattService: Received stop request...Stopping profile...
08-23 23:13:02.624  4123  4123 D BtGatt.GattService: stop()
,08-23 23:13:02.624  4123  4123 D BtGatt.AdvertiseManager: advertise clients cleared
,08-23 23:13:02.630  4123  4123 V BluetoothAdapterState: isTurningOff()=false
,08-23 23:13:02.631  4123  4123 V BluetoothAdapterState: isTurningOn()=false
08-23 23:13:02.631  4123  4123 V BluetoothAdapterState: isBleTurningOn()=false
08-23 23:13:02.631  4123  4123 V BluetoothAdapterState: isBleTurningOff()=true
08-23 23:13:02.633  4123  4137 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-23 23:13:02.635  4123  4137 D BluetoothAdapterProperties: Setting state to 10
,08-23 23:13:02.636  4123  4137 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-23 23:13:02.640  4123  4137 I BluetoothAdapterState: Entering OffState
,08-23 23:13:02.642   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-23 23:13:02.662  4123  4123 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-23 23:13:02.663  4123  4123 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-23 23:13:02.663  4123  4123 I BluetoothServiceJni: cleanupNative: return from cleanup
08-23 23:13:02.667  4123  4138 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-23 23:13:02.672  4123  4138 D bt_stack_manager: event_clean_up_stack finished.
,08-23 23:13:02.676  4123  4123 I art     : System.exit called, status: 0
,08-23 23:13:02.676  4123  4123 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-23 23:13:02.753   874  1388 I ActivityManager: Process com.android.bluetooth (pid 4123) has died
,08-23 23:13:07.160  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 23:13:07.161  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 23:13:07.168  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 23:13:07.168  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f690974 removed from the list
08-23 23:13:07.168  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-23 23:13:07.169  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 23:13:07.169  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 23:13:07.175  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-23 23:13:07.175  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@908bf12 added. We now have 4 listener(s)
08-23 23:13:07.176  3801  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 23:13:07.178  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:13:07.178  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@908bf12 removed from the list
08-23 23:13:07.178  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 23:13:07.179  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:13:07.179  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:13:07.181  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 23:13:07.182  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cdd06e3 added. We now have 4 listener(s)
08-23 23:13:07.182  3801  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 23:13:12.191  3801  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 23:13:12.243   874   891 I ActivityManager: Start proc 4184:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-23 23:13:12.373  4184  4184 D AdapterServiceConfig: Adding HeadsetService
,08-23 23:13:12.374  4184  4184 D AdapterServiceConfig: Adding A2dpService
,08-23 23:13:12.374  4184  4184 D AdapterServiceConfig: Adding HidService
08-23 23:13:12.375  4184  4184 D AdapterServiceConfig: Adding HealthService
08-23 23:13:12.375  4184  4184 D AdapterServiceConfig: Adding PanService
08-23 23:13:12.376  4184  4184 D AdapterServiceConfig: Adding GattService
08-23 23:13:12.377  4184  4184 D AdapterServiceConfig: Adding BluetoothMapService
,08-23 23:13:12.407   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a21d475:true
,08-23 23:13:12.408  4184  4184 D BluetoothAdapterState: make() - Creating AdapterState
,08-23 23:13:12.416  4184  4184 I bt_bluedroid: init
,08-23 23:13:12.416  4184  4196 I BluetoothAdapterState: Entering OffState
,08-23 23:13:12.420  4184  4197 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-23 23:13:12.420  4184  4197 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-23 23:13:12.420  4184  4197 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-23 23:13:12.420  4184  4197 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-23 23:13:12.422  4184  4184 I bt_bluedroid: get_profile_interface socket
,08-23 23:13:12.427  4184  4184 I bt_bluedroid: get_profile_interface sdp
,08-23 23:13:12.428  4184  4200 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-23 23:13:12.432  4184  4200 D BluetoothAdapterProperties: Name is: Nexus 6
,08-23 23:13:12.435  4184  4195 I bt_bluedroid: config_hci_snoop_log
,08-23 23:13:12.438   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-23 23:13:12.453  4184  4196 D BluetoothAdapterState: Current state: OFF, message: 0
,08-23 23:13:12.453  4184  4196 D BluetoothAdapterProperties: Setting state to 14
08-23 23:13:12.454  4184  4196 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-23 23:13:12.460  4184  4196 D BluetoothBondStateMachine: make
,08-23 23:13:12.465  4184  4201 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-23 23:13:12.474  4184  4196 I BluetoothAdapterState: Entering PendingCommandState
,08-23 23:13:12.476  4184  4184 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-23 23:13:12.482  4184  4184 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2286885
,08-23 23:13:12.484  4184  4184 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-23 23:13:12.485  4184  4184 D BtGatt.GattService: Received start request. Starting profile...
08-23 23:13:12.485  4184  4184 D BtGatt.GattService: start()
08-23 23:13:12.486  4184  4184 I bt_bluedroid: get_profile_interface gatt
,08-23 23:13:12.488  4184  4184 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2286885
08-23 23:13:12.488  4184  4184 D BtGatt.AdvertiseManager: advertise manager created
,08-23 23:13:12.504  4184  4184 V BluetoothAdapterState: isTurningOff()=false
08-23 23:13:12.504  4184  4184 V BluetoothAdapterState: isTurningOn()=false
,08-23 23:13:12.505  4184  4184 V BluetoothAdapterState: isBleTurningOn()=true
08-23 23:13:12.505  4184  4184 V BluetoothAdapterState: isBleTurningOff()=false
08-23 23:13:12.506  4184  4196 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-23 23:13:12.508  4184  4196 I bt_bluedroid: enable
,08-23 23:13:12.509  4184  4197 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-23 23:13:12.510  4184  4197 I bt_hci  : start_up
,08-23 23:13:12.525  4184  4197 I bt_vendor: alloc value 0xb39da189
08-23 23:13:12.525  4184  4197 I bt_vendor: init
08-23 23:13:12.526  4184  4197 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-23 23:13:12.526  4184  4197 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-23 23:13:12.634  4184  4197 D bt_hci  : start_up starting async portion
,08-23 23:13:12.634  4184  4204 I bt_hci  : event_finish_startup
08-23 23:13:12.635  4184  4204 I bt_hci_h4: hal_open
08-23 23:13:12.635  4184  4204 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-23 23:13:12.647  4184  4204 I bt_userial_vendor: device fd = 51 open
,08-23 23:13:12.676  4184  4204 I bt_hwcfg: bt vendor lib: set UART baud 3000000
08-23 23:13:12.708  4184  4204 D bt_hwcfg: Chipset BCM4354A2
08-23 23:13:12.708  4184  4204 D bt_hwcfg: Target name = [BCM4354A2]
08-23 23:13:12.709  4184  4204 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-23 23:13:13.537  4184  4204 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-23 23:13:13.538  4184  4204 D bt_hwcfg: Settlement delay -- 100 ms
08-23 23:13:13.538  4184  4204 I bt_hwcfg: Setting fw settlement delay to 100 
,08-23 23:13:13.655  4184  4204 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-23 23:13:13.656  4184  4204 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-23 23:13:13.686  4184  4204 I bt_hwcfg: vendor lib fwcfg completed
,08-23 23:13:13.687  4184  4204 I bt_vendor: firmware callback
,08-23 23:13:13.687  4184  4204 I bt_hci  : firmware_config_callback
,08-23 23:13:13.700  4184  4208 I bt_btu  : btu_task pending for preload complete event
,08-23 23:13:13.700  4184  4208 I bt_btu_task: Bluetooth chip preload is complete
08-23 23:13:13.701  4184  4208 I bt_btu  : btu_task received preload complete event
,08-23 23:13:13.712  4184  4208 I         : BTE_InitTraceLevels -- TRC_HCI
,08-23 23:13:13.712  4184  4208 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-23 23:13:13.713  4184  4208 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-23 23:13:13.713  4184  4208 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-23 23:13:13.713  4184  4208 I         : BTE_InitTraceLevels -- TRC_AVRC
08-23 23:13:13.714  4184  4208 I         : BTE_InitTraceLevels -- TRC_A2D
,08-23 23:13:13.714  4184  4208 I         : BTE_InitTraceLevels -- TRC_BNEP
08-23 23:13:13.715  4184  4208 I         : BTE_InitTraceLevels -- TRC_BTM
,08-23 23:13:13.715  4184  4208 I         : BTE_InitTraceLevels -- TRC_GAP
08-23 23:13:13.715  4184  4208 I         : BTE_InitTraceLevels -- TRC_PAN
,08-23 23:13:13.717  4184  4208 I         : BTE_InitTraceLevels -- TRC_SDP
08-23 23:13:13.717  4184  4208 I         : BTE_InitTraceLevels -- TRC_GATT
,08-23 23:13:13.717  4184  4208 I         : BTE_InitTraceLevels -- TRC_SMP
08-23 23:13:13.718  4184  4208 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-23 23:13:13.718  4184  4208 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-23 23:13:13.858  4184  4208 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3957d9d
,08-23 23:13:13.858  4184  4208 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3957d9d 
,08-23 23:13:13.865  4184  4200 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-23 23:13:13.867  4184  4200 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-23 23:13:13.868  4184  4200 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-23 23:13:13.871  4184  4200 D BluetoothAdapterProperties: Name is: Nexus 6
,08-23 23:13:13.875  4184  4200 D BluetoothAdapterProperties: Scan Mode:20
,08-23 23:13:13.875  4184  4200 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-23 23:13:13.876  4184  4200 D bt_hci  : do_postload posting postload work item
,08-23 23:13:13.879  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 23:13:13.882  4184  4204 I bt_hci  : event_postload
,08-23 23:13:13.882  4184  4204 I bt_vendor: sco_config_cb
,08-23 23:13:13.882  4184  4204 I bt_hci  : sco_config_callback postload finished.
08-23 23:13:13.882  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 23:13:13.887  4184  4200 D bt_bte_conf: Device ID record 1 : primary
,08-23 23:13:13.887  4184  4200 D bt_bte_conf:   vendorId            = 000f
08-23 23:13:13.887  4184  4200 D bt_bte_conf:   vendorIdSource      = 0001
,08-23 23:13:13.887  4184  4200 D bt_bte_conf:   product             = 1200
,08-23 23:13:13.888  4184  4200 D bt_bte_conf:   version             = 1436
08-23 23:13:13.888  4184  4200 D bt_bte_conf:   clientExecutableURL = 
08-23 23:13:13.888  4184  4200 D bt_bte_conf:   serviceDescription  = 
,08-23 23:13:13.888  4184  4200 D bt_bte_conf:   documentationURL    = 
08-23 23:13:13.889  4184  4200 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-23 23:13:13.889  4184  4197 D bt_stack_manager: event_start_up_stack finished
08-23 23:13:13.889  4184  4204 I bt_vendor: low_power_mode_cb
,08-23 23:13:13.890  4184  4196 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-23 23:13:13.890  4184  4196 D BluetoothAdapterProperties: Setting state to 15
08-23 23:13:13.890  4184  4196 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-23 23:13:13.892  4184  4196 I BluetoothAdapterState: Entering BleOnState
08-23 23:13:13.896  4184  4196 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-23 23:13:13.897  4184  4196 D BluetoothAdapterProperties: Setting state to 11
,08-23 23:13:13.897  4184  4196 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-23 23:13:13.901  4184  4184 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2286885
,08-23 23:13:13.903  4184  4184 D HeadsetService: Received start request. Starting profile...
,08-23 23:13:13.909  4184  4184 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-23 23:13:13.910  4184  4184 D HeadsetStateMachine: make
,08-23 23:13:13.916  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 23:13:13.919  4184  4196 I BluetoothAdapterState: Entering PendingCommandState
,08-23 23:13:13.919  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 23:13:13.925  4184  4184 D HeadsetStateMachine: max_hf_connections = 1
,08-23 23:13:13.926  4184  4184 I bt_bluedroid: get_profile_interface handsfree
08-23 23:13:13.926  4184  4200 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-23 23:13:13.926  4184  4200 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-23 23:13:13.931  4184  4184 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2286885
08-23 23:13:13.932  4184  4184 D A2dpService: Received start request. Starting profile...
,08-23 23:13:13.933  4184  4184 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-23 23:13:13.933  4184  4184 I bt_bluedroid: get_profile_interface avrcp
,08-23 23:13:13.940  4184  4184 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-23 23:13:13.940  4184  4184 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-23 23:13:13.941  4184  4184 D A2dpStateMachine: make
,08-23 23:13:13.942  4184  4184 I bt_bluedroid: get_profile_interface a2dp
,08-23 23:13:13.942  4184  4200 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-23 23:13:13.944  4184  4217 D A2dpStateMachine: Enter Disconnected: -2
,08-23 23:13:13.944  4184  4184 I BluetoothHidServiceJni: classInitNative: succeeds
,08-23 23:13:13.945  4184  4184 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2286885
08-23 23:13:13.946  4184  4184 D HidService: Received start request. Starting profile...
,08-23 23:13:13.946  4184  4184 I bt_bluedroid: get_profile_interface hidhost
08-23 23:13:13.946  4184  4184 D HidService: setHidService(): set to: null
08-23 23:13:13.946  4184  4200 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39393e5
08-23 23:13:13.946  4184  4200 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-23 23:13:13.947  4184  4184 I BluetoothHealthServiceJni: classInitNative: succeeds
08-23 23:13:13.947  4184  4184 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2286885
,08-23 23:13:13.948  4184  4184 D HealthService: Received start request. Starting profile...
,08-23 23:13:13.949  4184  4184 I bt_bluedroid: get_profile_interface health
,08-23 23:13:13.950  4184  4184 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-23 23:13:13.951  4184  4184 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2286885
,08-23 23:13:13.952  4184  4184 D PanService: Received start request. Starting profile...
,08-23 23:13:13.952  4184  4184 D BluetoothPanServiceJni: initializeNative(L110): pan
08-23 23:13:13.952  4184  4184 I bt_bluedroid: get_profile_interface pan
08-23 23:13:13.952  4184  4200 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-23 23:13:13.955  4184  4184 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2286885
,08-23 23:13:13.958  4184  4184 D BluetoothMapService: Received start request. Starting profile...
,08-23 23:13:13.958  4184  4184 D BluetoothMapService: start()
,08-23 23:13:13.961  4184  4184 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-23 23:13:13.962  4184  4184 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-23 23:13:13.962  4184  4184 D BluetoothMapAppObserver: createReceiver()
,08-23 23:13:13.964  4184  4184 D BluetoothMapAppObserver: initObservers()
,08-23 23:13:13.964  4184  4184 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-23 23:13:13.973  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-23 23:13:13.975  4184  4184 V BluetoothAdapterState: isTurningOff()=false
,08-23 23:13:13.975  4184  4184 V BluetoothAdapterState: isTurningOn()=true
08-23 23:13:13.975  4184  4184 V BluetoothAdapterState: isBleTurningOn()=false
08-23 23:13:13.975  4184  4184 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 23:13:13.977  4184  4184 V BluetoothAdapterState: isTurningOff()=false
,08-23 23:13:13.977  4184  4184 V BluetoothAdapterState: isTurningOn()=true
,08-23 23:13:13.977  4184  4184 V BluetoothAdapterState: isBleTurningOn()=false
08-23 23:13:13.977  4184  4184 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 23:13:13.977  4184  4214 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-23 23:13:13.977  4184  4184 V BluetoothAdapterState: isTurningOff()=false
,08-23 23:13:13.977  4184  4184 V BluetoothAdapterState: isTurningOn()=true
08-23 23:13:13.977  4184  4184 V BluetoothAdapterState: isBleTurningOn()=false
,08-23 23:13:13.978  4184  4184 V BluetoothAdapterState: isBleTurningOff()=false
08-23 23:13:13.978  4184  4184 V BluetoothAdapterState: isTurningOff()=false
,08-23 23:13:13.978  4184  4184 V BluetoothAdapterState: isTurningOn()=true
,08-23 23:13:13.978  4184  4184 V BluetoothAdapterState: isBleTurningOn()=false
08-23 23:13:13.978  4184  4184 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 23:13:13.978  4184  4184 V BluetoothAdapterState: isTurningOff()=false
08-23 23:13:13.978  4184  4184 V BluetoothAdapterState: isTurningOn()=true,
08-23 23:13:13.979  4184  4184 V BluetoothAdapterState: isBleTurningOn()=false
,08-23 23:13:13.979  4184  4184 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 23:13:13.979  4184  4184 V BluetoothAdapterState: isTurningOff()=false
08-23 23:13:13.979  4184  4184 V BluetoothAdapterState: isTurningOn()=true
,08-23 23:13:13.979  4184  4184 V BluetoothAdapterState: isBleTurningOn()=false
08-23 23:13:13.979  4184  4184 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 23:13:13.979  4184  4196 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-23 23:13:13.979  4184  4196 D BluetoothAdapterProperties: ScanMode =  20
,08-23 23:13:13.980  4184  4196 D BluetoothAdapterProperties: State =  11
08-23 23:13:13.980  4184  4196 D BluetoothAdapterProperties: Setting state to 12
08-23 23:13:13.980  4184  4196 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-23 23:13:13.982  4184  4200 D BluetoothAdapterProperties: Scan Mode:21
08-23 23:13:13.982  4184  4196 I BluetoothAdapterState: Entering OnState
,08-23 23:13:13.982  4184  4200 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-23 23:13:13.982  1355  2008 D BluetoothPbap: onBluetoothStateChange: up=true
08-23 23:13:13.987  3897  3908 D BluetoothPbap: onBluetoothStateChange: up=true
08-23 23:13:13.987  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 23:13:13.987  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:13:13.987  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:13:13.987  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 23:13:13.987  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 23:13:13.987  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 23:13:13.987  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 23:13:13.987  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 23:13:13.989  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 23:13:13.989  1355  1368 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-23 23:13:13.990  3897  3909 D BluetoothMap: onBluetoothStateChange: up=true
,08-23 23:13:13.992  4184  4184 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-23 23:13:13.992  1355  1366 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-23 23:13:13.993  4184  4184 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-23 23:13:13.994  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 23:13:13.994  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:13:13.994  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:13:13.994  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 23:13:13.994  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 23:13:13.994  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 23:13:13.994  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 23:13:13.994  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 23:13:13.995  1355  2008 D BluetoothMap: onBluetoothStateChange: up=true
,08-23 23:13:13.995  4184  4184 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 23:13:13.996  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 23:13:13.998  4184  4184 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 23:13:13.999  1355  1368 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-23 23:13:13.999  4184  4184 D ObexServerSockets: Succeed to create listening sockets 
,08-23 23:13:13.999  4184  4184 D ObexServerSockets0: startAccept()
08-23 23:13:13.999  4184  4184 D ObexServerSockets0: prepareForNewConnect()
,08-23 23:13:14.000  1355  1366 D BluetoothPan: onBluetoothStateChange on: true
,08-23 23:13:14.002  4184  4184 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-23 23:13:14.002  4184  4184 D BluetoothSdpJni: SDP Create record success - handle: 0
08-23 23:13:14.003  3897  3908 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 23:13:14.003  4184  4223 D ObexServerSockets0: Accepting socket connection...
,08-23 23:13:14.003  4184  4224 D ObexServerSockets0: Accepting socket connection...
08-23 23:13:14.003  1355  1355 D BluetoothMap: Proxy object connected
08-23 23:13:14.003  1355  1355 D MapProfile: Bluetooth service connected
08-23 23:13:14.004  1355  1355 D BluetoothMap: getConnectedDevices()
,08-23 23:13:14.004  3897  3909 D BluetoothA2dp: onBluetoothStateChange: up=true
08-23 23:13:14.005  1355  1355 D BluetoothInputDevice: Proxy object connected
08-23 23:13:14.005  1355  1355 D HidProfile: Bluetooth service connected
08-23 23:13:14.007  3897  3897 D BluetoothMap: Proxy object connected
,08-23 23:13:14.007  1923  1933 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 23:13:14.007  3897  3897 D MapProfile: Bluetooth service connected
08-23 23:13:14.007  3897  3897 D BluetoothMap: getConnectedDevices()
,08-23 23:13:14.007   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 23:13:14.008  3897  4225 D BluetoothPan: onBluetoothStateChange on: true
,08-23 23:13:14.008  1355  1355 D BluetoothA2dp: Proxy object connected
08-23 23:13:14.009  1355  1355 D BluetoothPan: BluetoothPAN Proxy object connected
08-23 23:13:14.010  1355  1355 D PanProfile: Bluetooth service connected
,08-23 23:13:14.010   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
08-23 23:13:14.010  3897  3897 D BluetoothA2dp: Proxy object connected
08-23 23:13:14.010   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 23:13:14.010   874   874 D BluetoothA2dp: Proxy object connected
08-23 23:13:14.010   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 23:13:14.011  3897  3909 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-23 23:13:14.013  3897  3897 D BluetoothPan: BluetoothPAN Proxy object connected
08-23 23:13:14.014  3897  3897 D PanProfile: Bluetooth service connected
08-23 23:13:14.014  3897  3897 D BluetoothInputDevice: Proxy object connected
08-23 23:13:14.014  3897  3897 D HidProfile: Bluetooth service connected
,08-23 23:13:14.014   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
08-23 23:13:14.016  4184  4184 D BluetoothMapService: onReceive
08-23 23:13:14.016  4184  4184 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-23 23:13:14.016  4184  4184 D BluetoothMapService: STATE_ON
08-23 23:13:14.017  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 23:13:14.018  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 23:13:14.024  3897  3897 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-23 23:13:14.030  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-23 23:13:14.036  3897  3897 D DockEventReceiver: finishStartingService: stopping service
,08-23 23:13:14.039  3897  3897 D BluetoothPbap: Proxy object connected
,08-23 23:13:14.039  3897  3897 D PbapServerProfile: Bluetooth service connected
,08-23 23:13:14.045  1355  1355 D BluetoothPbap: Proxy object connected
,08-23 23:13:14.045  1355  1355 D PbapServerProfile: Bluetooth service connected
,08-23 23:13:14.047  4184  4184 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-23 23:13:14.047  4184  4184 D ObexServerSockets0: prepareForNewConnect()
,08-23 23:13:14.052  4184  4229 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 23:13:14.077  4184  4233 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 23:13:14.078  4184  4233 I BtOppRfcommListener: Accept thread started.
,08-23 23:13:14.095  3897  3909 D BluetoothHeadset: Proxy object connected
,08-23 23:13:14.095  3897  3897 D HeadsetProfile: Bluetooth service connected
08-23 23:13:14.097  1923  1939 D BluetoothHeadset: Proxy object connected
,08-23 23:13:14.098  1355  1366 D BluetoothHeadset: Proxy object connected
08-23 23:13:14.098  1355  1355 D HeadsetProfile: Bluetooth service connected
08-23 23:13:14.098   874   874 D BluetoothHeadset: Proxy object connected
,08-23 23:13:14.099   874   874 D BluetoothHeadset: Proxy object connected
,08-23 23:13:14.099   874   874 D BluetoothHeadset: Proxy object connected
,08-23 23:13:14.105  3897  4225 D BluetoothHeadset: Proxy object connected
,08-23 23:13:14.105  3897  3897 D HeadsetProfile: Bluetooth service connected
08-23 23:13:14.107  1923  2256 D BluetoothHeadset: Proxy object connected
08-23 23:13:14.107   874   891 D BluetoothHeadset: Proxy object connected
08-23 23:13:14.111   874   891 D BluetoothHeadset: Proxy object connected
,08-23 23:13:14.111   874   891 D BluetoothHeadset: Proxy object connected
,08-23 23:13:17.212  3801  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 23:13:17.212  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:13:17.212  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:13:17.212  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 23:13:17.212  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 23:13:17.212  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 23:13:17.212  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 23:13:17.212  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 23:13:17.219  3801  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 23:13:17.220  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 23:13:17.221  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cdd06e3 removed from the list
08-23 23:13:17.222  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 23:13:17.223  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 23:13:17.225  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 23:13:17.227  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 23:13:17.228  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8c748e0 added. We now have 4 listener(s)
08-23 23:13:17.229  3801  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 23:13:17.233   874  2003 D WifiService: setWifiEnabled: false pid=3801, uid=10000
,08-23 23:13:17.233   874  2003 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-23 23:13:20.819  1863  1890 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-23 23:13:20.819  1863  1890 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-23 23:13:20.855  1504  1504 I ConfigService: onCreate
,08-23 23:13:22.244  3801  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 23:13:22.245   874  1934 D WifiService: setWifiEnabled: true pid=3801, uid=10000
08-23 23:13:22.246   874  1934 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-23 23:13:22.265   874  1310 D WifiConfigStore: Loading config and enabling all networks 
,08-23 23:13:22.281  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 23:13:22.281  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:13:22.281  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:13:22.281  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 23:13:22.281  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 23:13:22.281  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 23:13:22.281  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 23:13:22.281  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 23:13:22.287  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-23 23:13:22.298  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 23:13:22.298  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:13:22.298  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:13:22.298  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 23:13:22.298  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 23:13:22.298  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 23:13:22.298  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 23:13:22.298  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 23:13:22.301  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-23 23:13:22.303   874  1310 D WifiConfigStore: loaded 0 passpoint configs
,08-23 23:13:22.304   874  1310 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-23 23:13:22.304   874  1310 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-23 23:13:22.305   874  1310 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-23 23:13:22.305   874  1310 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-23 23:13:22.306   874  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-23 23:13:22.306   874  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-23 23:13:22.324   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-23 23:13:22.324   874  1310 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-23 23:13:22.325   372   872 D CommandListener: Setting iface cfg
,08-23 23:13:22.376   874  1308 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '153 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 153 Failed to set address (No such device)'
,08-23 23:13:22.376   874  1308 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-23 23:13:22.382   874  1310 E native  : do suspend true
,08-23 23:13:22.398   874  1308 D WifiNative-HAL: p2pGetDeviceAddress
,08-23 23:13:22.399   874  1308 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-23 23:13:22.413   874  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,08-23 23:13:23.837   874  1310 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-23 23:13:23.946   874  1310 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.50 rxSuccessRate=10.25 delta 1000 -> 994
,08-23 23:13:23.947   874  1310 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-23 23:13:23.947   874  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-23 23:13:23.962   874  1310 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-23 23:13:24.017   874  1310 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-23 23:13:24.019  1466  1466 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-23 23:13:24.452  1466  1466 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-23 23:13:24.496  1466  1466 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-23 23:13:24.499  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-23 23:13:24.504   874  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,08-23 23:13:24.524   874  1310 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-23 23:13:24.525   874  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-23 23:13:24.525   874  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-23 23:13:24.569   874  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-23 23:13:24.593   372   872 D CommandListener: Setting iface cfg
,08-23 23:13:24.595   874  1310 D WifiStateMachine: Start Dhcp Watchdog 3
,08-23 23:13:24.614   874  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-23 23:13:24.646   874  4243 D DhcpClient: Receive thread started
,08-23 23:13:24.740   874  1310 E native  : do suspend false
,08-23 23:13:24.765   874  2085 D DhcpClient: Broadcasting DHCPDISCOVER
,08-23 23:13:24.786   874  4243 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,08-23 23:13:24.787   874  2085 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,08-23 23:13:24.792   874  2085 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-23 23:13:24.806   874  4243 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-23 23:13:24.808   874  2085 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-23 23:13:24.813   372   872 D CommandListener: Setting iface cfg
,08-23 23:13:24.823   874  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-23 23:13:24.824   874  2085 D DhcpClient: Scheduling renewal in 86399s
,08-23 23:13:24.826   874  1310 E native  : do suspend true
,08-23 23:13:24.846   874  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-23 23:13:24.847   874  1310 D WifiConfigStore: No blacklist allowed without epno enabled
,08-23 23:13:24.848   874  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-23 23:13:24.853   874  1312 D ConnectivityService: Adding iface wlan0 to network 102
,08-23 23:13:24.853   874  1310 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-23 23:13:24.893   874  1312 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-23 23:13:24.894   874  1312 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-23 23:13:24.898   874  1312 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-23 23:13:24.900   874  1312 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-23 23:13:24.903   874  1312 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-23 23:13:24.920   874  1312 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-23 23:13:24.928   874  1312 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-23 23:13:24.928   874  1312 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-23 23:13:24.928   874  1312 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-23 23:13:24.929   874  1312 D ConnectivityService:    accepting network in place of null
08-23 23:13:24.929   874  1310 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-23 23:13:24.930   874  1312 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-23 23:13:24.931   874  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-23 23:13:24.941   874  4242 D NetlinkSocketObserver: NeighborEvent{elapsedMs=217102, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-23 23:13:24.987   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-23 23:13:25.009   874  4241 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.20.78,2a00:1450:4001:816::200e
,08-23 23:13:25.036   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-23 23:13:25.047   874  1312 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-23 23:13:25.047   874  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-23 23:13:25.057   874  1312 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-23 23:13:25.060   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-23 23:13:25.080  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 23:13:25.080  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:13:25.080  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:13:25.080  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 23:13:25.080  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 23:13:25.080  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 23:13:25.080  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 23:13:25.080  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 23:13:25.081   874  4241 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 23 Aug 2016 21:13:25 GMT], X-Android-Received-Millis=[1471986805080], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471986805054]}
08-23 23:13:25.082   874  1312 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-23 23:13:25.082  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 23:13:25.083   874  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-23 23:13:25.083   874  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-23 23:13:25.084   874  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-23 23:13:25.088  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 23:13:25.088  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:13:25.088  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:13:25.088  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 23:13:25.088  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 23:13:25.088  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 23:13:25.088  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 23:13:25.088  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 23:13:25.090  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 23:13:25.095  1980  1980 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
08-23 23:13:25.095  1722  1722 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-23 23:13:25.101  1722  1722 D SystemUpdateService: onCreate
,08-23 23:13:25.105  1722  1722 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-23 23:13:25.126  1722  4253 I SystemUpdateService: active receiver: enabled
,08-23 23:13:25.129  1722  1722 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-23 23:13:25.136  1722  2497 I iu.UploadsManager: num queued entries: 0
,08-23 23:13:25.136  1722  2497 I iu.UploadsManager: num updated entries: 0
08-23 23:13:25.137  1722  2497 I iu.SyncManager: NEXT; no task
,08-23 23:13:25.139  1722  4253 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-23 23:13:25.140  1722  1722 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-23 23:13:25.141  1722  1722 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-23 23:13:25.143  3951  3951 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-23 23:13:25.155  1722  4253 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,08-23 23:13:25.159  1722  4255 I MDM     : [187] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-23 23:13:25.159  1722  4255 W BaseAppContext: Using Auth Proxy for data requests.
,08-23 23:13:25.161  1722  4255 V GoogleAuthProtoRequest: [187] a.<init>: mAccountName set to: thalitester@gmail.com
,08-23 23:13:25.163  1722  4253 I SystemUpdateService: now status is 0 (complete)
08-23 23:13:25.163  1722  4253 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-23 23:13:25.163  1722  4253 I SystemUpdateService: file has been verified
08-23 23:13:25.163  1722  4253 I SystemUpdateService: OTA package size = 12249756
,08-23 23:13:25.164  3951  3951 D SprintDMHelper: simOperator: 
,08-23 23:13:25.164  3951  3951 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-23 23:13:25.176  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 23:13:25.178  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 23:13:25.185  1722  4253 I SystemUpdateService: showing system update notification
,08-23 23:13:25.279  1722  1722 D SystemUpdateService: onDestroy
,08-23 23:13:25.300  1504  2041 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-23 23:13:25.300  1504  2041 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-23 23:13:25.300  1504  2041 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 23:13:25.300  1504  2041 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 23:13:25.325  3741  4258 V KeepSync: Connecting to GoogleApiClient
,08-23 23:13:25.328   874  2003 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-23 23:13:25.355  1722  4255 E MDM     : [187] SitrepService.a: Error sending sitrep.
,08-23 23:13:25.357  2398  4259 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-23 23:13:25.401  1504  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-23 23:13:25.402  1504  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-23 23:13:25.402  1504  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 23:13:25.402  1504  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 23:13:25.422  1722  4265 V BaseAuthAsyncOperation: access token request failed
,08-23 23:13:25.423  3741  4258 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-23 23:13:25.500  1504  2319 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-23 23:13:25.500  1504  2319 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-23 23:13:25.500  1504  2319 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 23:13:25.500  1504  2319 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 23:13:25.534  3741  4258 E KeepSync: IOException
08-23 23:13:25.534  3741  4258 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-23 23:13:25.534  3741  4258 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-23 23:13:25.534  3741  4258 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-23 23:13:25.534  3741  4258 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-23 23:13:25.534  3741  4258 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-23 23:13:25.534  3741  4258 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-23 23:13:25.534  3741  4258 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-23 23:13:25.534  3741  4258 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-23 23:13:25.534  3741  4258 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-23 23:13:25.534  3741  4258 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-23 23:13:25.534  3741  4258 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-23 23:13:25.534  3741  4258 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-23 23:13:25.534  3741  4258 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-23 23:13:25.534  3741  4258 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-23 23:13:25.534  3741  4258 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-23 23:13:25.534  3741  4258 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-23 23:13:25.534  3741  4258 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-23 23:13:25.534  3741  4258 E KeepSync: 	... 10 more
,08-23 23:13:25.534  3741  4258 W KeepSync: Sync result 2
,08-23 23:13:25.542   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 214155, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-23 23:13:25.929  1504  1504 I ConfigService: onDestroy
,08-23 23:13:26.047   874  1312 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-23 23:13:27.273  3801  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 23:13:27.273  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:13:27.273  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:13:27.273  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 23:13:27.273  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 23:13:27.273  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 23:13:27.273  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 23:13:27.273  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 23:13:27.280  3801  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 23:13:27.282  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 23:13:27.283  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8c748e0 removed from the list
08-23 23:13:27.283  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-23 23:13:27.283  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:13:27.284  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 23:13:27.295  3801  4266 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-23 23:13:27.296  3801  4266 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-23 23:13:30.303  3801  4267 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,08-23 23:13:30.304  3801  4266 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
08-23 23:13:30.304  3801  4267 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-23 23:13:30.304  3801  4266 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-23 23:13:30.306  3801  4267 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-23 23:13:30.306  3801  4266 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-23 23:13:30.307  3801  4267 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-23 23:13:30.307  3801  4266 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-23 23:13:30.313  3801  4269 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 420, name: IncomingSocketThread/Sender)
,08-23 23:13:30.314  3801  4267 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-23 23:13:30.314  3801  4266 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-23 23:13:30.319  3801  4270 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 421, name: OutgoingSocketThread/Sender)
,08-23 23:13:30.320  3801  4271 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 422, name: IncomingSocketThread/Receiver)
,08-23 23:13:30.321  3801  4271 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 422, thread name: IncomingSocketThread/Receiver)
08-23 23:13:30.322  3801  4271 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,08-23 23:13:30.322  3801  4271 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 422, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-23 23:13:30.323  3801  4272 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 423, name: OutgoingSocketThread/Receiver)
,08-23 23:13:30.327  3801  4272 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 423, thread name: OutgoingSocketThread/Receiver)
,08-23 23:13:30.328  3801  4272 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,08-23 23:13:30.328  3801  4272 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 423, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-23 23:13:32.935   874  1312 D ConnectivityService: handlePromptUnvalidated 102
,08-23 23:13:33.303  3801  3851 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-23 23:13:33.305  3801  3851 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-23 23:13:33.313  3801  3851 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c0801 Bundle[{}]
,08-23 23:13:33.314  3801  3851 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-23 23:13:33.314  3801  3851 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-23 23:13:33.314  3801  3851 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-23 23:13:33.315  3801  3851 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-23 23:13:33.316  3801  3851 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-23 23:13:33.316  3801  3851 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-23 23:13:33.320  3801  3851 I System.out: Running OutgoingSocketThread
,08-23 23:13:33.324  3801  4273 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-23 23:13:33.324  3801  4273 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-23 23:13:36.333  3801  4274 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,08-23 23:13:36.333  3801  4274 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-23 23:13:36.334  3801  4274 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-23 23:13:36.334  3801  4273 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-23 23:13:36.334  3801  4273 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,08-23 23:13:36.335  3801  4274 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-23 23:13:36.336  3801  4273 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-23 23:13:36.338  3801  4274 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-23 23:13:36.342  3801  4273 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-23 23:13:36.343  3801  4276 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 432, name: IncomingSocketThread/Sender)
,08-23 23:13:36.347  3801  4277 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 434, name: IncomingSocketThread/Receiver)
,08-23 23:13:36.348  3801  4273 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-23 23:13:36.350  3801  4277 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 434, thread name: IncomingSocketThread/Receiver)
,08-23 23:13:36.350  3801  4277 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,08-23 23:13:36.351  3801  4278 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 433, name: OutgoingSocketThread/Sender)
,08-23 23:13:36.351  3801  4277 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 434, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-23 23:13:36.355  3801  4279 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 435, name: OutgoingSocketThread/Receiver)
08-23 23:13:36.357  3801  4279 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 435, thread name: OutgoingSocketThread/Receiver)
08-23 23:13:36.357  3801  4279 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-23 23:13:36.358  3801  4279 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 435, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-23 23:13:39.335  3801  3851 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 444)
,08-23 23:13:39.338  3801  3851 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-23 23:13:39.338  3801  3851 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 445)
,08-23 23:13:39.344  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 23:13:39.345  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24e7799 added. We now have 3 listener(s)
,08-23 23:13:39.346  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-23 23:13:39.346  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 23:13:39.346  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 23:13:39.347  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 23:13:39.347  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2fba5e added. We now have 4 listener(s)
,08-23 23:13:39.347  3801  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 23:13:39.348  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 23:13:39.355  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 23:13:39.369  3801  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 23:13:39.369  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:13:39.369  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:13:39.369  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 23:13:39.369  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 23:13:39.369  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 23:13:39.369  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 23:13:39.369  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 23:13:39.375  3801  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 23:13:39.376  3801  3851 D io.jxcore.node.ConnectivityMonitor: start: OK,
,08-23 23:13:39.377  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 23:13:39.377  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-23 23:13:39.377  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-23 23:13:39.378  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 23:13:39.378  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 23:13:39.378  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 23:13:39.381  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 23:13:39.382  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24e7799 removed from the list
,08-23 23:13:39.382  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:13:39.382  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2fba5e removed from the list
08-23 23:13:39.382  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 23:13:39.382  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-23 23:13:39.383  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:13:39.385  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 23:13:39.385  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:13:39.390  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-23 23:13:39.390  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 23:13:39.390  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 23:13:39.391  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2fba5e not in the list
08-23 23:13:39.391  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:13:39.391  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:13:39.392  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 23:13:39.396  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 23:13:39.396  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 23:13:39.396  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:13:39.396  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2fba5e not in the list
08-23 23:13:39.397  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 23:13:39.397  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:13:39.397  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:13:39.397  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24e7799 not in the list
08-23 23:13:39.399  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 23:13:39.400  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e08130c added. We now have 3 listener(s)
,08-23 23:13:39.406  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-23 23:13:39.406  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 23:13:39.406  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 23:13:39.406  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 23:13:39.406  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@685f455 added. We now have 4 listener(s)
08-23 23:13:39.406  3801  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 23:13:39.407  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 23:13:39.411  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 23:13:39.420  3801  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 23:13:39.420  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:13:39.420  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:13:39.420  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 23:13:39.420  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 23:13:39.420  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 23:13:39.420  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 23:13:39.420  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 23:13:39.426  3801  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 23:13:39.426  3801  3851 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 23:13:39.426  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 23:13:39.426  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 23:13:39.426  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 23:13:39.426  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 23:13:39.426  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-23 23:13:39.429  3801  3851 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-23 23:13:39.429  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-23 23:13:39.431  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 23:13:39.435  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 23:13:39.435  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-23 23:13:39.436  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-23 23:13:39.436  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-23 23:13:39.445  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-23 23:13:39.446  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-23 23:13:39.446  3801  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-23 23:13:39.448  3801  3851 D BluetoothAdapter: STATE_ON
,08-23 23:13:39.456  4184  4195 D BtGatt.GattService: registerClient() - UUID=c2762dcf-e8c5-45a2-8e48-3abc5d6b950f
,08-23 23:13:39.458  4184  4200 D BtGatt.GattService: onClientRegistered() - UUID=c2762dcf-e8c5-45a2-8e48-3abc5d6b950f, clientIf=5
,08-23 23:13:39.459  3801  3812 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-23 23:13:39.462  4184  4222 D BtGatt.GattService: start scan with filters
,08-23 23:13:39.471  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-23 23:13:39.471  4184  4203 D BtGatt.ScanManager: handling starting scan
,08-23 23:13:39.471  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-23 23:13:39.472  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-23 23:13:39.472  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-23 23:13:39.476  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 23:13:39.477  4184  4203 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2286885
08-23 23:13:39.477  3801  3801 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-23 23:13:39.477  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-23 23:13:39.481  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-23 23:13:39.489  3801  3851 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-23 23:13:39.489  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-23 23:13:39.489  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-23 23:13:39.490  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:13:39.490  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-23 23:13:39.490  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-23 23:13:39.490  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-23 23:13:39.490  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 23:13:39.490  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-23 23:13:39.490  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-23 23:13:39.490  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-23 23:13:39.491  4184  4200 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-23 23:13:39.491  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 23:13:39.492  3801  3851 D BluetoothAdapter: STATE_ON
08-23 23:13:39.493  4184  4203 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-23 23:13:39.494  4184  4215 D BtGatt.GattService: stopScan() - queue size =1
08-23 23:13:39.498  4184  4194 D BtGatt.GattService: unregisterClient() - clientIf=5
08-23 23:13:39.499  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-23 23:13:39.499  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-23 23:13:39.499  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-23 23:13:39.499  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-23 23:13:39.500  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-23 23:13:39.502  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 23:13:39.502  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-23 23:13:39.502  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-23 23:13:39.502  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-23 23:13:39.503  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 23:13:39.506  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-23 23:13:39.507  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-23 23:13:39.507  3801  3801 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 23:13:39.512  4184  4200 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-23 23:13:39.512  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 23:13:39.514  4184  4203 D BtGatt.ScanManager: Starting BLE batch scan
,08-23 23:13:39.515  4184  4203 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-23 23:13:39.547  4184  4200 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-23 23:13:39.547  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 23:13:39.569  4184  4200 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-23 23:13:39.570  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 23:13:39.599  4184  4200 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-23 23:13:39.600  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 23:13:39.601  4184  4203 D BtGatt.ScanManager: stopping BLe Batch
,08-23 23:13:39.623  4184  4200 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-23 23:13:39.623  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 23:13:39.624  4184  4203 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-23 23:13:39.668  4184  4200 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
08-23 23:13:39.669  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 23:13:39.669  4184  4200 D BtGatt.GattService: current time is 231831772321
,08-23 23:13:39.670  4184  4200 D BtGatt.GattService: Batch record : [-102, -14, -36, 14, 85, 121, 1, -128, -96, 1, 0, 24, 2, 1, 26, 20, -1, 76, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 4, 0, 0, 0, 0, 0]
,08-23 23:13:39.675  4184  4200 D BtGatt.GattService: ScanRecord : [2, 1, 26, 20, -1, 76, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 4, 0, 0, 0, 0]
,08-23 23:13:40.008  3801  3801 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-23 23:13:40.009  3801  3801 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 23:13:40.009  3801  3801 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-23 23:13:42.508  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 23:13:42.509  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 23:13:42.509  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-23 23:13:42.510  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 23:13:42.510  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 23:13:42.511  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 23:13:42.511  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-23 23:13:42.511  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e08130c removed from the list
,08-23 23:13:42.512  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:13:42.512  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@685f455 removed from the list
08-23 23:13:42.512  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-23 23:13:42.513  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:13:42.514  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:13:42.515  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 23:13:42.518  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 23:13:42.518  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 23:13:42.519  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:13:42.519  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@685f455 not in the list
08-23 23:13:42.519  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:13:42.519  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 23:13:42.523  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 23:13:42.524  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 23:13:42.524  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 23:13:42.525  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@685f455 not in the list
08-23 23:13:42.525  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 23:13:42.525  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:13:42.525  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:13:42.526  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e08130c not in the list
08-23 23:13:42.526  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 23:13:42.526  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8c2b736 added. We now have 3 listener(s)
08-23 23:13:42.528  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-23 23:13:42.528  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 23:13:42.528  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 23:13:42.529  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 23:13:42.529  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87ea637 added. We now have 4 listener(s)
08-23 23:13:42.529  3801  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 23:13:42.529  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 23:13:42.532  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 23:13:42.537  3801  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 23:13:42.537  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:13:42.537  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:13:42.537  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 23:13:42.537  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 23:13:42.537  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 23:13:42.537  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 23:13:42.537  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 23:13:42.539  3801  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 23:13:42.540  3801  3851 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 23:13:42.540  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-23 23:13:42.541  3801  3851 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-23 23:13:42.541  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-23 23:13:42.543  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-23 23:13:42.543  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,08-23 23:13:42.543  3801  3851 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-23 23:13:42.544  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 23:13:42.545  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-23 23:13:42.545  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 23:13:42.546  3801  3851 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-23 23:13:42.547  3801  3851 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-23 23:13:42.547  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-23 23:13:42.548  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-23 23:13:42.548  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 23:13:42.548  3801  3801 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-23 23:13:42.548  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 23:13:42.549  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-23 23:13:42.552  3801  4281 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 23:13:42.555  3801  4281 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-23 23:13:42.559  3801  3851 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-23 23:13:42.559  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-23 23:13:42.568  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-23 23:13:42.569  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-23 23:13:42.570  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-23 23:13:42.572  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-23 23:13:42.573  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-23 23:13:42.573  3801  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,08-23 23:13:42.575  3801  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-23 23:13:42.575  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-23 23:13:42.575  3801  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-23 23:13:42.576  3801  3851 D BluetoothAdapter: STATE_ON
,08-23 23:13:42.580  4184  4195 D BtGatt.GattService: registerClient() - UUID=1b11787f-64d0-4ef5-bbd4-6586b63e6b52
,08-23 23:13:42.581  4184  4200 D BtGatt.GattService: onClientRegistered() - UUID=1b11787f-64d0-4ef5-bbd4-6586b63e6b52, clientIf=5
08-23 23:13:42.581  3801  3812 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-23 23:13:42.584  4184  4202 D BtGatt.AdvertiseManager: message : 0
,08-23 23:13:42.588  4184  4202 D BtGatt.AdvertiseManager: starting multi advertising
,08-23 23:13:42.602  4184  4200 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-23 23:13:42.612  4184  4200 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-23 23:13:42.613  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-23 23:13:42.614  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-23 23:13:42.616  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-23 23:13:42.619  3801  3801 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-23 23:13:42.619  3801  3801 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-23 23:13:42.619  3801  3801 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,08-23 23:13:42.619  3801  3801 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-23 23:13:42.619  3801  3801 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,08-23 23:13:42.619  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
08-23 23:13:42.623  3801  3801 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true,
08-23 23:13:42.623  3801  3801 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
08-23 23:13:42.625  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-23 23:13:42.625  3801  3851 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-23 23:13:43.123  3801  3801 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-23 23:13:45.627  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 23:13:45.627  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
08-23 23:13:45.627  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-23 23:13:45.628  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-23 23:13:45.628  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-23 23:13:45.629  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-23 23:13:45.629  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-23 23:13:45.629  3801  4281 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-23 23:13:45.630  3801  4281 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-23 23:13:45.630  3801  3851 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-23 23:13:45.630  3801  4281 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-23 23:13:45.630  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-23 23:13:45.631  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 23:13:45.631  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-23 23:13:45.631  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-23 23:13:45.632  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-23 23:13:45.633  3801  3801 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-23 23:13:45.634  3801  3851 D BluetoothAdapter: STATE_ON
08-23 23:13:45.634  3801  3851 D BluetoothLeScanner: could not find callback wrapper
08-23 23:13:45.635  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 23:13:45.635  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-23 23:13:45.637  4184  4202 D BtGatt.AdvertiseManager: message : 1
08-23 23:13:45.639  4184  4202 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-23 23:13:45.648  4184  4200 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-23 23:13:45.649  4184  4200 D BtGatt.GattService: Client app is not null!
,08-23 23:13:45.651  4184  4215 D BtGatt.GattService: unregisterClient() - clientIf=5
08-23 23:13:45.652  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-23 23:13:45.652  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-23 23:13:45.652  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,08-23 23:13:45.653  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,08-23 23:13:45.653  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
08-23 23:13:45.655  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 23:13:45.656  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-23 23:13:45.656  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-23 23:13:45.657  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-23 23:13:45.660  3801  3801 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 23:13:45.660  3801  3801 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-23 23:13:45.661  3801  3801 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-23 23:13:45.661  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 23:13:45.661  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 23:13:45.661  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:13:45.662  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 23:13:45.662  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 23:13:45.662  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 23:13:45.662  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8c2b736 removed from the list
08-23 23:13:45.662  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:13:45.662  3801  3801 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 23:13:45.662  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87ea637 removed from the list
,08-23 23:13:45.662  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-23 23:13:45.662  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:13:45.663  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:13:45.663  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 23:13:45.666  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 23:13:45.666  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 23:13:45.667  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:13:45.667  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87ea637 not in the list
08-23 23:13:45.667  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:13:45.667  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 23:13:45.670  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 23:13:45.670  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 23:13:45.670  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:13:45.670  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87ea637 not in the list
08-23 23:13:45.670  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 23:13:45.671  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:13:45.671  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:13:45.671  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8c2b736 not in the list
,08-23 23:13:45.673  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 23:13:45.673  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@82eaa10 added. We now have 3 listener(s)
,08-23 23:13:45.678  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-23 23:13:45.678  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 23:13:45.678  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 23:13:45.679  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 23:13:45.679  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c0f7909 added. We now have 4 listener(s)
08-23 23:13:45.679  3801  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 23:13:45.680  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 23:13:45.684  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 23:13:45.693  3801  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 23:13:45.693  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:13:45.693  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:13:45.693  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 23:13:45.693  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 23:13:45.693  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 23:13:45.693  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 23:13:45.693  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 23:13:45.696  3801  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 23:13:45.697  3801  3851 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 23:13:45.697  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-23 23:13:45.697  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-23 23:13:45.697  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 23:13:45.697  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 23:13:45.697  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-23 23:13:45.701  3801  3851 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-23 23:13:45.701  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-23 23:13:45.702  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 23:13:45.707  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 23:13:45.708  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-23 23:13:45.709  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-23 23:13:45.709  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-23 23:13:45.716  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-23 23:13:45.716  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-23 23:13:45.716  3801  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-23 23:13:45.717  3801  3851 D BluetoothAdapter: STATE_ON
,08-23 23:13:45.721  4184  4195 D BtGatt.GattService: registerClient() - UUID=582b1830-b025-4ba0-b7bc-91bd2446a1da
,08-23 23:13:45.722  4184  4200 D BtGatt.GattService: onClientRegistered() - UUID=582b1830-b025-4ba0-b7bc-91bd2446a1da, clientIf=5
08-23 23:13:45.723  3801  3813 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-23 23:13:45.724  4184  4215 D BtGatt.GattService: start scan with filters
,08-23 23:13:45.729  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-23 23:13:45.730  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-23 23:13:45.730  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-23 23:13:45.730  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-23 23:13:45.730  4184  4203 D BtGatt.ScanManager: handling starting scan
,08-23 23:13:45.738  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 23:13:45.739  3801  3801 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-23 23:13:45.738  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-23 23:13:45.742  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-23 23:13:45.750  4184  4200 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-23 23:13:45.751  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 23:13:45.751  4184  4203 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-23 23:13:45.766  4184  4200 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-23 23:13:45.766  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 23:13:45.767  4184  4203 D BtGatt.ScanManager: Starting BLE batch scan
,08-23 23:13:45.768  4184  4203 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-23 23:13:45.786  4184  4200 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-23 23:13:45.786  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 23:13:45.796  4184  4200 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-23 23:13:45.796  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 23:13:46.163  3801  3801 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-23 23:13:46.240  3801  3801 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-23 23:13:46.240  3801  3801 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 23:13:46.240  3801  3801 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-23 23:13:47.303  4184  4184 D BtGatt.ScanManager: awakened up at time 239465
,08-23 23:13:47.306  4184  4203 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-23 23:13:47.353  4184  4200 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,08-23 23:13:47.353  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 23:13:47.353  4184  4200 D BtGatt.GattService: current time is 239515940106
08-23 23:13:47.355  4184  4200 D BtGatt.GattService: Batch record : [-102, -14, -36, 14, 85, 121, 1, -128, -97, 1, 0, 24, 2, 1, 26, 20, -1, 76, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 4, 0, 0, 0, 0, 0, -46, -4, -117, 6, 105, -37, 1, -128, -87, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -90, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -86, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -84, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -80, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -87, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-23 23:13:47.355  4184  4200 D BtGatt.GattService: ScanRecord : [2, 1, 26, 20, -1, 76, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 4, 0, 0, 0, 0]
08-23 23:13:47.356  4184  4200 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-23 23:13:47.357  4184  4200 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-23 23:13:47.358  4184  4200 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-23 23:13:47.359  4184  4200 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-23 23:13:47.359  4184  4200 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-23 23:13:47.360  4184  4200 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-23 23:13:48.757  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 23:13:48.758  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-23 23:13:48.758  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-23 23:13:48.758  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 23:13:48.759  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-23 23:13:48.759  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-23 23:13:48.759  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-23 23:13:48.760  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 23:13:48.760  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-23 23:13:48.760  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-23 23:13:48.761  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-23 23:13:48.763  3801  3851 D BluetoothAdapter: STATE_ON
,08-23 23:13:48.765  4184  4215 D BtGatt.GattService: stopScan() - queue size =1
,08-23 23:13:48.768  4184  4194 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-23 23:13:48.769  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-23 23:13:48.770  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-23 23:13:48.770  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-23 23:13:48.770  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-23 23:13:48.771  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-23 23:13:48.774  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 23:13:48.775  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-23 23:13:48.775  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-23 23:13:48.776  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-23 23:13:48.779  4184  4184 D BtGatt.ScanManager: awakened up at time 240941
08-23 23:13:48.781  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 23:13:48.785  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 23:13:48.785  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 23:13:48.785  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 23:13:48.785  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 23:13:48.785  3801  3801 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 23:13:48.785  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 23:13:48.786  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 23:13:48.786  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@82eaa10 removed from the list
08-23 23:13:48.786  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:13:48.786  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c0f7909 removed from the list
08-23 23:13:48.787  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-23 23:13:48.787  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:13:48.788  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 23:13:48.789  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:13:48.789  4184  4200 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-23 23:13:48.789  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 23:13:48.790  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 23:13:48.790  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 23:13:48.790  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:13:48.790  4184  4203 D BtGatt.ScanManager: stopping BLe Batch
08-23 23:13:48.790  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c0f7909 not in the list
08-23 23:13:48.790  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:13:48.790  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 23:13:48.793  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 23:13:48.793  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 23:13:48.794  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 23:13:48.794  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c0f7909 not in the list
08-23 23:13:48.794  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-23 23:13:48.794  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:13:48.795  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 23:13:48.795  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@82eaa10 not in the list
08-23 23:13:48.797  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-23 23:13:48.797  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90df61a added. We now have 3 listener(s)
,08-23 23:13:48.798  4184  4200 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-23 23:13:48.798  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 23:13:48.799  4184  4203 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-23 23:13:48.802  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-23 23:13:48.802  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-23 23:13:48.802  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 23:13:48.803  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 23:13:48.803  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09e54b added. We now have 4 listener(s)
08-23 23:13:48.803  3801  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 23:13:48.803  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 23:13:48.806  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 23:13:48.806  4184  4200 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-23 23:13:48.806  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 23:13:48.811  3801  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 23:13:48.811  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:13:48.811  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:13:48.811  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 23:13:48.811  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 23:13:48.811  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 23:13:48.811  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 23:13:48.811  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 23:13:48.812  3801  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 23:13:48.813  3801  3851 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 23:13:48.813  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 23:13:48.813  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 23:13:48.813  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 23:13:48.813  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 23:13:48.813  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:13:48.813  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 23:13:48.813  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-23 23:13:48.814  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90df61a removed from the list
08-23 23:13:48.814  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:13:48.814  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09e54b removed from the list
,08-23 23:13:48.816  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 23:13:48.816  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 23:13:48.816  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:13:48.817  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:13:48.817  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:13:48.819  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 23:13:48.819  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 23:13:48.819  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:13:48.819  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 23:13:48.819  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09e54b not in the list
08-23 23:13:48.819  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:13:48.820  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:13:48.820  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 23:13:48.820  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-23 23:13:48.821  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 23:13:48.821  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09e54b not in the list
08-23 23:13:48.821  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 23:13:48.821  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 23:13:48.821  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 23:13:48.821  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90df61a not in the list
08-23 23:13:48.822  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-23 23:13:48.822  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-23 23:13:48.822  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-23 23:13:48.822  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 23:13:48.823  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-23 23:13:48.823  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-23 23:13:49.285  3801  3801 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-23 23:13:50.837  3801  4282 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 454, name: My test thread name)
,08-23 23:13:52.835  3801  3851 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 454
,08-23 23:13:52.835  3801  3851 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 454, name: My test thread name)
,08-23 23:13:52.841  3801  4283 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 455, name: My test thread name)
,08-23 23:13:52.842  3801  4283 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 455, thread name: My test thread name)
,08-23 23:13:52.842  3801  4283 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 455, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
08-23 23:13:52.846  3801  3851 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-23 23:13:52.855  3801  4284 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 459, name: My test thread name)
08-23 23:13:52.856  3801  4284 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 459, thread name: My test thread name): Test exception.
08-23 23:13:52.856  3801  4284 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 459, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-23 23:13:52.864  3801  3851 I jxcore-log: Total number of executed tests:  82
08-23 23:13:52.864  3801  3851 I jxcore-log: 
,08-23 23:13:52.865  3801  3851 I jxcore-log: Number of passed tests:  82
08-23 23:13:52.865  3801  3851 I jxcore-log: 
,08-23 23:13:52.865  3801  3851 I jxcore-log: Number of failed tests:  0
08-23 23:13:52.865  3801  3851 I jxcore-log: 
,08-23 23:13:52.866  3801  3851 I jxcore-log: Number of ignored tests:  0
08-23 23:13:52.866  3801  3851 I jxcore-log: 
,08-23 23:13:52.868  3801  3851 I jxcore-log: Total duration:  101335
08-23 23:13:52.868  3801  3851 I jxcore-log: 
,08-23 23:13:52.876  3801  3851 I jxcore-log: Unit Test app is loaded
08-23 23:13:52.876  3801  3851 I jxcore-log: 
,08-23 23:13:52.878  3801  4282 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 454, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,08-23 23:13:52.884  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 23:13:52.884  3801  3851 I jxcore-log: 
,08-23 23:13:52.888  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 23:13:52.888  3801  3851 I jxcore-log: 
,08-23 23:13:52.890  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 23:13:52.890  3801  3851 I jxcore-log: 
,08-23 23:13:52.891  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 23:13:52.891  3801  3851 I jxcore-log: 
,08-23 23:13:52.893  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-23 23:13:52.893  3801  3851 I jxcore-log: 
,08-23 23:13:52.895  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-23 23:13:52.895  3801  3851 I jxcore-log: 
,08-23 23:13:52.898  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 23:13:52.898  3801  3851 I jxcore-log: 
,08-23 23:13:52.900  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 23:13:52.900  3801  3851 I jxcore-log: 
,08-23 23:13:52.901  3801  3801 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-23 23:13:52.902  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-23 23:13:52.902  3801  3851 I jxcore-log: 
,08-23 23:13:52.902  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-23 23:13:52.902  3801  3851 I jxcore-log: 
08-23 23:13:52.903  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-23 23:13:52.903  3801  3851 I jxcore-log: 
08-23 23:13:52.904  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 23:13:52.904  3801  3851 I jxcore-log: 
08-23 23:13:52.905  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 23:13:52.905  3801  3851 I jxcore-log: 
08-23 23:13:52.906  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 23:13:52.906  3801  3851 I jxcore-log: 
08-23 23:13:52.906  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-23 23:13:52.906  3801  3851 I jxcore-log: 
,08-23 23:13:52.908  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-23 23:13:52.908  3801  3851 I jxcore-log: 
,08-23 23:13:52.909  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-23 23:13:52.909  3801  3851 I jxcore-log: 
08-23 23:13:52.909  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 23:13:52.909  3801  3851 I jxcore-log: 
,08-23 23:13:52.910  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 23:13:52.910  3801  3851 I jxcore-log: 
08-23 23:13:52.911  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 23:13:52.911  3801  3851 I jxcore-log: 
,08-23 23:13:52.912  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-23 23:13:52.912  3801  3851 I jxcore-log: 
08-23 23:13:52.913  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-23 23:13:52.913  3801  3851 I jxcore-log: 
,08-23 23:13:52.914  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-23 23:13:52.914  3801  3851 I jxcore-log: 
,08-23 23:13:52.915  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 23:13:52.915  3801  3851 I jxcore-log: 
,08-23 23:13:52.916  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 23:13:52.916  3801  3851 I jxcore-log: 
08-23 23:13:52.916  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 23:13:52.916  3801  3851 I jxcore-log: 
08-23 23:13:52.917  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 23:13:52.917  3801  3851 I jxcore-log: 
,08-23 23:13:52.918  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 23:13:52.918  3801  3851 I jxcore-log: 
08-23 23:13:52.918  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 23:13:52.918  3801  3851 I jxcore-log: 
08-23 23:13:52.919  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 23:13:52.919  3801  3851 I jxcore-log: 
,08-23 23:13:52.919  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 23:13:52.919  3801  3851 I jxcore-log: 
08-23 23:13:52.920  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 23:13:52.920  3801  3851 I jxcore-log: 
,08-23 23:13:52.920  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 23:13:52.920  3801  3851 I jxcore-log: 
08-23 23:13:52.921  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 23:13:52.921  3801  3851 I jxcore-log: 
08-23 23:13:52.921  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 23:13:52.921  3801  3851 I jxcore-log: 
08-23 23:13:52.922  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 23:13:52.922  3801  3851 I jxcore-log: 
,08-23 23:13:52.922  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 23:13:52.922  3801  3851 I jxcore-log: 
08-23 23:13:52.923  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 23:13:52.923  3801  3851 I jxcore-log: 
,08-23 23:13:52.923  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-23 23:13:52.923  3801  3851 I jxcore-log: 
08-23 23:13:52.924  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-23 23:13:52.924  3801  3851 I jxcore-log: 
08-23 23:13:52.924  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 23:13:52.924  3801  3851 I jxcore-log: 
08-23 23:13:52.925  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 23:13:52.925  3801  3851 I jxcore-log: 
,08-23 23:13:52.925  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 23:13:52.925  3801  3851 I jxcore-log: 
08-23 23:13:52.926  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 23:13:52.926  3801  3851 I jxcore-log: 
,08-23 23:13:52.926  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 23:13:52.926  3801  3851 I jxcore-log: 
08-23 23:13:52.927  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-23 23:13:52.927  3801  3851 I jxcore-log: 
08-23 23:13:52.927  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 23:13:52.927  3801  3851 I jxcore-log: 
08-23 23:13:52.928  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-23 23:13:52.928  3801  3851 I jxcore-log: 
08-23 23:13:52.928  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 23:13:52.928  3801  3851 I jxcore-log: 
08-23 23:13:52.929  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-23 23:13:52.929  3801  3851 I jxcore-log: 
,08-23 23:13:52.929  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-23 23:13:52.929  3801  3851 I jxcore-log: 
08-23 23:13:52.930  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 23:13:52.930  3801  3851 I jxcore-log: 
08-23 23:13:52.930  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-23 23:13:52.930  3801  3851 I jxcore-log: 
,08-23 23:13:52.933  3801  3851 I jxcore-log: My device name is: motorola-Nexus 6
,08-23 23:13:52.933  3801  3851 I jxcore-log: 
08-23 23:13:52.934  3801  3851 I jxcore-log: WARN testUtils: myNameCallback not set!
08-23 23:13:52.934  3801  3851 I jxcore-log: 
,08-23 23:13:55.186  3801  3851 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-23 23:13:55.186  3801  3851 I jxcore-log: 
,08-23 23:13:55.199  3801  3851 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-23 23:13:55.201  3801  3851 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-23 23:13:55.201  3801  3851 I jxcore-log: 
,08-23 23:13:56.282   874  4242 D NetlinkSocketObserver: NeighborEvent{elapsedMs=248443, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-23 23:13:57.000  3741  4286 V KeepSync: Connecting to GoogleApiClient
,08-23 23:13:57.001   874   885 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-23 23:13:57.048  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 23:13:57.051  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 23:13:57.099  1504  2985 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-23 23:13:57.099  1504  2985 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-23 23:13:57.099  1504  2985 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 23:13:57.099  1504  2985 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 23:13:57.128  1722  4287 V BaseAuthAsyncOperation: access token request failed
,08-23 23:13:57.129  3741  4286 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-23 23:13:57.207  1504  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-23 23:13:57.207  1504  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-23 23:13:57.207  1504  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 23:13:57.207  1504  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 23:13:57.253  3741  4286 E KeepSync: IOException
08-23 23:13:57.253  3741  4286 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-23 23:13:57.253  3741  4286 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-23 23:13:57.253  3741  4286 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-23 23:13:57.253  3741  4286 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-23 23:13:57.253  3741  4286 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-23 23:13:57.253  3741  4286 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-23 23:13:57.253  3741  4286 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-23 23:13:57.253  3741  4286 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-23 23:13:57.253  3741  4286 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-23 23:13:57.253  3741  4286 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-23 23:13:57.253  3741  4286 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-23 23:13:57.253  3741  4286 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-23 23:13:57.253  3741  4286 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-23 23:13:57.253  3741  4286 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-23 23:13:57.253  3741  4286 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-23 23:13:57.253  3741  4286 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-23 23:13:57.253  3741  4286 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-23 23:13:57.253  3741  4286 E KeepSync: 	... 10 more
,08-23 23:13:57.253  3741  4286 W KeepSync: Sync result 2
,08-23 23:13:57.262   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 249020, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-23 23:14:01.702   874  4242 D NetlinkSocketObserver: NeighborEvent{elapsedMs=253864, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-23 23:14:27.642  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 23:14:27.645  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 23:14:27.687  1504  2319 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-23 23:14:27.687  1504  2319 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-23 23:14:27.687  1504  2319 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 23:14:27.688  1504  2319 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 23:14:27.713  2994  4290 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-23 23:14:27.713  2994  4290 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-23 23:14:27.713  2994  4290 E HttpOperation: 	at jdm.a(PG:82)
08-23 23:14:27.713  2994  4290 E HttpOperation: 	at jcs.o(PG:406)
08-23 23:14:27.713  2994  4290 E HttpOperation: 	at jcn.a(PG:1379)
08-23 23:14:27.713  2994  4290 E HttpOperation: 	at jcs.i(PG:143)
08-23 23:14:27.713  2994  4290 E HttpOperation: 	at blb.a(PG:3937)
08-23 23:14:27.713  2994  4290 E HttpOperation: 	at czp.a(PG:18188)
08-23 23:14:27.713  2994  4290 E HttpOperation: 	at czp.a(PG:9081)
08-23 23:14:27.713  2994  4290 E HttpOperation: 	at czq.run(PG:1686)
08-23 23:14:27.713  2994  4290 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 23:14:27.713  2994  4290 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 23:14:27.713  2994  4290 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 23:14:27.713  2994  4290 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 23:14:27.713  2994  4290 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-23 23:14:27.713  2994  4290 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 23:14:27.713  2994  4290 E HttpOperation: 	at jdj.a(PG:4091)
08-23 23:14:27.713  2994  4290 E HttpOperation: 	at jdj.a(PG:1125)
08-23 23:14:27.713  2994  4290 E HttpOperation: 	at jdm.a(PG:77)
08-23 23:14:27.713  2994  4290 E HttpOperation: 	... 12 more
08-23 23:14:27.713  2994  4290 E HttpOperation: Caused by: faj: BadAuthentication
08-23 23:14:27.713  2994  4290 E HttpOperation: 	at fal.a(PG:38)
08-23 23:14:27.713  2994  4290 E HttpOperation: 	at jdj.a(PG:4089)
08-23 23:14:27.713  2994  4290 E HttpOperation: 	... 14 more
,08-23 23:14:27.773  1504  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-23 23:14:27.773  1504  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-23 23:14:27.774  1504  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 23:14:27.774  1504  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 23:14:27.808  2994  4290 E HttpOperation: [getmobileexperiments] Unexpected exception
08-23 23:14:27.808  2994  4290 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-23 23:14:27.808  2994  4290 E HttpOperation: 	at jdm.a(PG:82)
08-23 23:14:27.808  2994  4290 E HttpOperation: 	at jcs.o(PG:406)
08-23 23:14:27.808  2994  4290 E HttpOperation: 	at jcn.a(PG:1379)
08-23 23:14:27.808  2994  4290 E HttpOperation: 	at jcs.i(PG:143)
08-23 23:14:27.808  2994  4290 E HttpOperation: 	at hec.a(PG:42)
08-23 23:14:27.808  2994  4290 E HttpOperation: 	at hee.a(PG:102)
08-23 23:14:27.808  2994  4290 E HttpOperation: 	at czr.a(PG:65)
08-23 23:14:27.808  2994  4290 E HttpOperation: 	at kka.a(PG:108)
08-23 23:14:27.808  2994  4290 E HttpOperation: 	at czp.a(PG:19176)
08-23 23:14:27.808  2994  4290 E HttpOperation: 	at czp.a(PG:9081)
08-23 23:14:27.808  2994  4290 E HttpOperation: 	at czq.run(PG:1686)
08-23 23:14:27.808  2994  4290 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 23:14:27.808  2994  4290 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 23:14:27.808  2994  4290 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 23:14:27.808  2994  4290 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 23:14:27.808  2994  4290 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-23 23:14:27.808  2994  4290 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 23:14:27.808  2994  4290 E HttpOperation: 	at jdj.a(PG:4091)
08-23 23:14:27.808  2994  4290 E HttpOperation: 	at jdj.a(PG:1125)
08-23 23:14:27.808  2994  4290 E HttpOperation: 	at jdm.a(PG:77)
08-23 23:14:27.808  2994  4290 E HttpOperation: 	... 15 more
08-23 23:14:27.808  2994  4290 E HttpOperation: Caused by: faj: BadAuthentication
08-23 23:14:27.808  2994  4290 E HttpOperation: 	at fal.a(PG:38)
08-23 23:14:27.808  2994  4290 E HttpOperation: 	at jdj.a(PG:4089)
08-23 23:14:27.808  2994  4290 E HttpOperation: 	... 17 more
,08-23 23:14:27.808  2994  4290 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-23 23:14:27.808  2994  4290 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-23 23:14:27.808  2994  4290 E ExperimentLoader: 	at jdm.a(PG:82)
08-23 23:14:27.808  2994  4290 E ExperimentLoader: 	at jcs.o(PG:406)
08-23 23:14:27.808  2994  4290 E ExperimentLoader: 	at jcn.a(PG:1379)
08-23 23:14:27.808  2994  4290 E ExperimentLoader: 	at jcs.i(PG:143)
08-23 23:14:27.808  2994  4290 E ExperimentLoader: 	at hec.a(PG:42)
08-23 23:14:27.808  2994  4290 E ExperimentLoader: 	at hee.a(PG:102)
08-23 23:14:27.808  2994  4290 E ExperimentLoader: 	at czr.a(PG:65)
08-23 23:14:27.808  2994  4290 E ExperimentLoader: 	at kka.a(PG:108)
08-23 23:14:27.808  2994  4290 E ExperimentLoader: 	at czp.a(PG:19176)
08-23 23:14:27.808  2994  4290 E ExperimentLoader: 	at czp.a(PG:9081)
08-23 23:14:27.808  2994  4290 E ExperimentLoader: 	at czq.run(PG:1686)
08-23 23:14:27.808  2994  4290 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 23:14:27.808  2994  4290 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 23:14:27.808  2994  4290 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 23:14:27.808  2994  4290 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 23:14:27.808  2994  4290 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-23 23:14:27.808  2994  4290 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 23:14:27.808  2994  4290 E ExperimentLoader: 	at jdj.a(PG:4091)
08-23 23:14:27.808  2994  4290 E ExperimentLoader: 	at jdj.a(PG:1125)
08-23 23:14:27.808  2994  4290 E ExperimentLoader: 	at jdm.a(PG:77)
08-23 23:14:27.808  2994  4290 E ExperimentLoader: 	... 15 more
08-23 23:14:27.808  2994  4290 E ExperimentLoader: Caused by: faj: BadAuthentication,
,08-23 23:14:27.808  2994  4290 E ExperimentLoader: 	at fal.a(PG:38)
08-23 23:14:27.808  2994  4290 E ExperimentLoader: 	at jdj.a(PG:4089)
08-23 23:14:27.808  2994  4290 E ExperimentLoader: 	... 17 more
,08-23 23:14:27.939   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 252320, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-23 23:14:32.582   874  4242 D NetlinkSocketObserver: NeighborEvent{elapsedMs=284743, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-23 23:14:42.342   874  4242 D NetlinkSocketObserver: NeighborEvent{elapsedMs=294504, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-23 23:14:58.032  3731  4297 I BooksSync: Starting books sync for 61035162, extras: ade
,08-23 23:14:58.050  3731  4298 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-23 23:14:58.065  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 23:14:58.070  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,08-23 23:14:58.105  1504  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-23 23:14:58.105  1504  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-23 23:14:58.105  1504  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 23:14:58.106  1504  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 23:14:58.138  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 23:14:58.141  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 23:14:58.168  1504  3148 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-23 23:14:58.168  1504  3148 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-23 23:14:58.168  1504  3148 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 23:14:58.168  1504  3148 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 23:14:58.189  3731  4298 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-23 23:14:58.190  3731  4297 E BooksSync: Soft error
08-23 23:14:58.190  3731  4297 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-23 23:14:58.190  3731  4297 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-23 23:14:58.190  3731  4297 E BooksSync: Sync error
08-23 23:14:58.190  3731  4297 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-23 23:14:58.190  3731  4297 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-23 23:14:58.190  3731  4297 I BooksSync: Finished books sync
,08-23 23:14:58.203   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 292446, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-23 23:15:13.222   874  4242 D NetlinkSocketObserver: NeighborEvent{elapsedMs=325384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-23 23:15:22.809   874  4242 D NetlinkSocketObserver: NeighborEvent{elapsedMs=334970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-23 23:15:28.583  3741  4310 V KeepSync: Connecting to GoogleApiClient
,08-23 23:15:28.583   874  2352 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-23 23:15:28.629  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,08-23 23:15:28.634  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 23:15:28.666  1504  2985 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-23 23:15:28.666  1504  2985 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-23 23:15:28.666  1504  2985 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 23:15:28.667  1504  2985 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 23:15:28.705  1722  4311 V BaseAuthAsyncOperation: access token request failed
,08-23 23:15:28.713  3741  4310 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-23 23:15:28.725  1504  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-23 23:15:28.725  1504  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-23 23:15:28.725  1504  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 23:15:28.725  1504  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 23:15:28.745  2994  4309 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-23 23:15:28.745  2994  4309 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-23 23:15:28.745  2994  4309 E HttpOperation: 	at jdm.a(PG:82)
08-23 23:15:28.745  2994  4309 E HttpOperation: 	at jcs.o(PG:406)
08-23 23:15:28.745  2994  4309 E HttpOperation: 	at jcn.a(PG:1379)
08-23 23:15:28.745  2994  4309 E HttpOperation: 	at jcs.i(PG:143)
08-23 23:15:28.745  2994  4309 E HttpOperation: 	at blb.a(PG:3937)
08-23 23:15:28.745  2994  4309 E HttpOperation: 	at czp.a(PG:18188)
08-23 23:15:28.745  2994  4309 E HttpOperation: 	at czp.a(PG:9081)
08-23 23:15:28.745  2994  4309 E HttpOperation: 	at czq.run(PG:1686)
08-23 23:15:28.745  2994  4309 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 23:15:28.745  2994  4309 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 23:15:28.745  2994  4309 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 23:15:28.745  2994  4309 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 23:15:28.745  2994  4309 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-23 23:15:28.745  2994  4309 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 23:15:28.745  2994  4309 E HttpOperation: 	at jdj.a(PG:4091)
08-23 23:15:28.745  2994  4309 E HttpOperation: 	at jdj.a(PG:1125)
08-23 23:15:28.745  2994  4309 E HttpOperation: 	at jdm.a(PG:77)
08-23 23:15:28.745  2994  4309 E HttpOperation: 	... 12 more
08-23 23:15:28.745  2994  4309 E HttpOperation: Caused by: faj: BadAuthentication
08-23 23:15:28.745  2994  4309 E HttpOperation: 	at fal.a(PG:38)
08-23 23:15:28.745  2994  4309 E HttpOperation: 	at jdj.a(PG:4089)
08-23 23:15:28.745  2994  4309 E HttpOperation: 	... 14 more
,08-23 23:15:28.815  1504  2985 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-23 23:15:28.815  1504  2985 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-23 23:15:28.815  1504  2985 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 23:15:28.815  1504  2985 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 23:15:28.830  2994  4309 E HttpOperation: [getmobileexperiments] Unexpected exception
08-23 23:15:28.830  2994  4309 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-23 23:15:28.830  2994  4309 E HttpOperation: 	at jdm.a(PG:82)
08-23 23:15:28.830  2994  4309 E HttpOperation: 	at jcs.o(PG:406)
08-23 23:15:28.830  2994  4309 E HttpOperation: 	at jcn.a(PG:1379)
08-23 23:15:28.830  2994  4309 E HttpOperation: 	at jcs.i(PG:143)
08-23 23:15:28.830  2994  4309 E HttpOperation: 	at hec.a(PG:42)
08-23 23:15:28.830  2994  4309 E HttpOperation: 	at hee.a(PG:102)
08-23 23:15:28.830  2994  4309 E HttpOperation: 	at czr.a(PG:65)
08-23 23:15:28.830  2994  4309 E HttpOperation: 	at kka.a(PG:108)
08-23 23:15:28.830  2994  4309 E HttpOperation: 	at czp.a(PG:19176)
08-23 23:15:28.830  2994  4309 E HttpOperation: 	at czp.a(PG:9081)
08-23 23:15:28.830  2994  4309 E HttpOperation: 	at czq.run(PG:1686)
08-23 23:15:28.830  2994  4309 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 23:15:28.830  2994  4309 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 23:15:28.830  2994  4309 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 23:15:28.830  2994  4309 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 23:15:28.830  2994  4309 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-23 23:15:28.830  2994  4309 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 23:15:28.830  2994  4309 E HttpOperation: 	at jdj.a(PG:4091)
08-23 23:15:28.830  2994  4309 E HttpOperation: 	at jdj.a(PG:1125)
08-23 23:15:28.830  2994  4309 E HttpOperation: 	at jdm.a(PG:77)
08-23 23:15:28.830  2994  4309 E HttpOperation: 	... 15 more
08-23 23:15:28.830  2994  4309 E HttpOperation: Caused by: faj: BadAuthentication
08-23 23:15:28.830  2994  4309 E HttpOperation: 	at fal.a(PG:38)
08-23 23:15:28.830  2994  4309 E HttpOperation: 	at jdj.a(PG:4089)
08-23 23:15:28.830  2994  4309 E HttpOperation: 	... 17 more
08-23 23:15:28.831  2994  4309 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-23 23:15:28.831  2994  4309 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-23 23:15:28.831  2994  4309 E ExperimentLoader: 	at jdm.a(PG:82)
08-23 23:15:28.831  2994  4309 E ExperimentLoader: 	at jcs.o(PG:406)
08-23 23:15:28.831  2994  4309 E ExperimentLoader: 	at jcn.a(PG:1379)
08-23 23:15:28.831  2994  4309 E ExperimentLoader: 	at jcs.i(PG:143)
08-23 23:15:28.831  2994  4309 E ExperimentLoader: 	at hec.a(PG:42)
08-23 23:15:28.831  2994  4309 E ExperimentLoader: 	at hee.a(PG:102)
08-23 23:15:28.831  2994  4309 E ExperimentLoader: 	at czr.a(PG:65)
08-23 23:15:28.831  2994  4309 E ExperimentLoader: 	at kka.a(PG:108)
08-23 23:15:28.831  2994  4309 E ExperimentLoader: 	at czp.a(PG:19176)
08-23 23:15:28.831  2994  4309 E ExperimentLoader: 	at czp.a(PG:9081)
08-23 23:15:28.831  2994  4309 E ExperimentLoader: 	at czq.run(PG:1686)
08-23 23:15:28.831  2994  4309 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 23:15:28.831  2994  4309 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 23:15:28.831  2994  4309 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 23:15:28.831  2994  4309 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 23:15:28.831  2994  4309 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-23 23:15:28.831  2994  4309 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 23:15:28.831  2994  4309 E ExperimentLoader: 	at jdj.a(PG:4091)
08-23 23:15:28.831  2994  4309 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-23 23:15:28.831  2994  4309 E ExperimentLoader: 	at jdm.a(PG:77)
08-23 23:15:28.831  2994  4309 E ExperimentLoader: 	... 15 more
08-23 23:15:28.831  2994  4309 E ExperimentLoader: Caused by: faj: BadAuthentication
08-23 23:15:28.831  2994  4309 E ExperimentLoader: 	at fal.a(PG:38)
08-23 23:15:28.831  2994  4309 E ExperimentLoader: 	at jdj.a(PG:4089)
08-23 23:15:28.831  2994  4309 E ExperimentLoader: 	... 17 more
,08-23 23:15:28.902  1504  3148 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-23 23:15:28.903  1504  3148 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-23 23:15:28.903  1504  3148 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 23:15:28.903  1504  3148 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 23:15:28.921  3741  4310 E KeepSync: IOException
08-23 23:15:28.921  3741  4310 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-23 23:15:28.921  3741  4310 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-23 23:15:28.921  3741  4310 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-23 23:15:28.921  3741  4310 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-23 23:15:28.921  3741  4310 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-23 23:15:28.921  3741  4310 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-23 23:15:28.921  3741  4310 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-23 23:15:28.921  3741  4310 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-23 23:15:28.921  3741  4310 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-23 23:15:28.921  3741  4310 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-23 23:15:28.921  3741  4310 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-23 23:15:28.921  3741  4310 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-23 23:15:28.921  3741  4310 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-23 23:15:28.921  3741  4310 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-23 23:15:28.921  3741  4310 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-23 23:15:28.921  3741  4310 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-23 23:15:28.921  3741  4310 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-23 23:15:28.921  3741  4310 E KeepSync: 	... 10 more
08-23 23:15:28.921  3741  4310 W KeepSync: Sync result 2
,08-23 23:15:28.936   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 312056, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-23 23:15:28.965  3731  4313 I BooksSync: Starting books sync for 61035162, extras: ade
,08-23 23:15:28.976   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 312827, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-23 23:15:28.989  3731  4314 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-23 23:15:29.013  1504  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-23 23:15:29.014  1504  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-23 23:15:29.014  1504  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 23:15:29.014  1504  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 23:15:29.049  1504  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-23 23:15:29.049  1504  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-23 23:15:29.049  1504  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 23:15:29.049  1504  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 23:15:29.075  3731  4314 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-23 23:15:29.075  3731  4313 E BooksSync: Soft error
08-23 23:15:29.075  3731  4313 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-23 23:15:29.075  3731  4313 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-23 23:15:29.075  3731  4313 E BooksSync: Sync error
08-23 23:15:29.075  3731  4313 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-23 23:15:29.075  3731  4313 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-23 23:15:29.075  3731  4313 I BooksSync: Finished books sync
,08-23 23:15:29.088   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 340607, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-23 23:15:32.240  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 23:15:32.282  1504  2985 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-23 23:15:32.282  1504  2985 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-23 23:15:32.283  1504  2985 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 23:15:32.283  1504  2985 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 23:15:32.307  1504  2985 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-23 23:15:32.307  1504  2985 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-23 23:15:32.307  1504  2985 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-23 23:15:32.307  1504  2985 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-23 23:15:32.307  1504  2985 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-23 23:15:32.307  1504  2985 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-23 23:15:32.307  1504  2985 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-23 23:15:32.317  3524  3555 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-23 23:15:32.317  3524  3555 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-23 23:15:32.317  3524  3555 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-23 23:15:32.317  3524  3555 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-23 23:15:32.317  3524  3555 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-23 23:15:32.317  3524  3555 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-23 23:15:32.317  3524  3555 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-23 23:16:29.775  3731  4321 I BooksSync: Starting books sync for 61035162, extras: ade
,08-23 23:16:29.821  3731  4322 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-23 23:16:29.861  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 23:16:29.869  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 23:16:29.925  1504  2319 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-23 23:16:29.925  1504  2319 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-23 23:16:29.925  1504  2319 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 23:16:29.925  1504  2319 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 23:16:29.968  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 23:16:29.974  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 23:16:30.019  1504  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-23 23:16:30.019  1504  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-23 23:16:30.019  1504  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 23:16:30.019  1504  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 23:16:30.054  3731  4322 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-23 23:16:30.056  3731  4321 E BooksSync: Soft error
08-23 23:16:30.056  3731  4321 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-23 23:16:30.056  3731  4321 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-23 23:16:30.056  3731  4321 E BooksSync: Sync error
08-23 23:16:30.056  3731  4321 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-23 23:16:30.056  3731  4321 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-23 23:16:30.056  3731  4321 I BooksSync: Finished books sync
,08-23 23:16:30.060   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 401734, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-23 23:17:00.403  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 23:17:00.404  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 23:17:00.442  1504  2041 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-23 23:17:00.442  1504  2041 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-23 23:17:00.442  1504  2041 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 23:17:00.442  1504  2041 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 23:17:00.458  2994  4325 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-23 23:17:00.458  2994  4325 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-23 23:17:00.458  2994  4325 E HttpOperation: 	at jdm.a(PG:82)
08-23 23:17:00.458  2994  4325 E HttpOperation: 	at jcs.o(PG:406)
08-23 23:17:00.458  2994  4325 E HttpOperation: 	at jcn.a(PG:1379)
08-23 23:17:00.458  2994  4325 E HttpOperation: 	at jcs.i(PG:143)
08-23 23:17:00.458  2994  4325 E HttpOperation: 	at blb.a(PG:3937)
08-23 23:17:00.458  2994  4325 E HttpOperation: 	at czp.a(PG:18188)
08-23 23:17:00.458  2994  4325 E HttpOperation: 	at czp.a(PG:9081)
08-23 23:17:00.458  2994  4325 E HttpOperation: 	at czq.run(PG:1686)
08-23 23:17:00.458  2994  4325 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 23:17:00.458  2994  4325 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 23:17:00.458  2994  4325 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 23:17:00.458  2994  4325 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 23:17:00.458  2994  4325 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-23 23:17:00.458  2994  4325 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 23:17:00.458  2994  4325 E HttpOperation: 	at jdj.a(PG:4091)
08-23 23:17:00.458  2994  4325 E HttpOperation: 	at jdj.a(PG:1125)
08-23 23:17:00.458  2994  4325 E HttpOperation: 	at jdm.a(PG:77)
08-23 23:17:00.458  2994  4325 E HttpOperation: 	... 12 more
08-23 23:17:00.458  2994  4325 E HttpOperation: Caused by: faj: BadAuthentication
08-23 23:17:00.458  2994  4325 E HttpOperation: 	at fal.a(PG:38)
08-23 23:17:00.458  2994  4325 E HttpOperation: 	at jdj.a(PG:4089)
08-23 23:17:00.458  2994  4325 E HttpOperation: 	... 14 more
,08-23 23:17:00.528  1504  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-23 23:17:00.529  1504  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-23 23:17:00.529  1504  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 23:17:00.529  1504  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 23:17:00.542  2994  4325 E HttpOperation: [getmobileexperiments] Unexpected exception
08-23 23:17:00.542  2994  4325 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-23 23:17:00.542  2994  4325 E HttpOperation: 	at jdm.a(PG:82)
08-23 23:17:00.542  2994  4325 E HttpOperation: 	at jcs.o(PG:406)
08-23 23:17:00.542  2994  4325 E HttpOperation: 	at jcn.a(PG:1379)
08-23 23:17:00.542  2994  4325 E HttpOperation: 	at jcs.i(PG:143)
08-23 23:17:00.542  2994  4325 E HttpOperation: 	at hec.a(PG:42)
08-23 23:17:00.542  2994  4325 E HttpOperation: 	at hee.a(PG:102)
08-23 23:17:00.542  2994  4325 E HttpOperation: 	at czr.a(PG:65)
08-23 23:17:00.542  2994  4325 E HttpOperation: 	at kka.a(PG:108)
08-23 23:17:00.542  2994  4325 E HttpOperation: 	at czp.a(PG:19176)
08-23 23:17:00.542  2994  4325 E HttpOperation: 	at czp.a(PG:9081)
08-23 23:17:00.542  2994  4325 E HttpOperation: 	at czq.run(PG:1686)
08-23 23:17:00.542  2994  4325 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 23:17:00.542  2994  4325 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 23:17:00.542  2994  4325 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 23:17:00.542  2994  4325 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 23:17:00.542  2994  4325 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-23 23:17:00.542  2994  4325 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 23:17:00.542  2994  4325 E HttpOperation: 	at jdj.a(PG:4091)
08-23 23:17:00.542  2994  4325 E HttpOperation: 	at jdj.a(PG:1125)
08-23 23:17:00.542  2994  4325 E HttpOperation: 	at jdm.a(PG:77)
08-23 23:17:00.542  2994  4325 E HttpOperation: 	... 15 more
08-23 23:17:00.542  2994  4325 E HttpOperation: Caused by: faj: BadAuthentication
08-23 23:17:00.542  2994  4325 E HttpOperation: 	at fal.a(PG:38)
08-23 23:17:00.542  2994  4325 E HttpOperation: 	at jdj.a(PG:4089)
08-23 23:17:00.542  2994  4325 E HttpOperation: 	... 17 more
,08-23 23:17:00.543  2994  4325 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-23 23:17:00.543  2994  4325 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-23 23:17:00.543  2994  4325 E ExperimentLoader: 	at jdm.a(PG:82)
08-23 23:17:00.543  2994  4325 E ExperimentLoader: 	at jcs.o(PG:406)
08-23 23:17:00.543  2994  4325 E ExperimentLoader: 	at jcn.a(PG:1379)
08-23 23:17:00.543  2994  4325 E ExperimentLoader: 	at jcs.i(PG:143)
08-23 23:17:00.543  2994  4325 E ExperimentLoader: 	at hec.a(PG:42)
08-23 23:17:00.543  2994  4325 E ExperimentLoader: 	at hee.a(PG:102)
08-23 23:17:00.543  2994  4325 E ExperimentLoader: 	at czr.a(PG:65)
08-23 23:17:00.543  2994  4325 E ExperimentLoader: 	at kka.a(PG:108)
08-23 23:17:00.543  2994  4325 E ExperimentLoader: 	at czp.a(PG:19176)
08-23 23:17:00.543  2994  4325 E ExperimentLoader: 	at czp.a(PG:9081)
08-23 23:17:00.543  2994  4325 E ExperimentLoader: 	at czq.run(PG:1686)
08-23 23:17:00.543  2994  4325 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 23:17:00.543  2994  4325 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 23:17:00.543  2994  4325 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 23:17:00.543  2994  4325 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 23:17:00.543  2994  4325 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-23 23:17:00.543  2994  4325 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 23:17:00.543  2994  4325 E ExperimentLoader: 	at jdj.a(PG:4091)
08-23 23:17:00.543  2994  4325 E ExperimentLoader: 	at jdj.a(PG:1125)
08-23 23:17:00.543  2994  4325 E ExperimentLoader: 	at jdm.a(PG:77)
08-23 23:17:00.543  2994  4325 E ExperimentLoader: 	... 15 more
08-23 23:17:00.543  2994  4325 E ExperimentLoader: Caused by: faj: BadAuthentication
08-23 23:17:00.543  2994  4325 E ExperimentLoader: 	at fal.a(PG:38)
08-23 23:17:00.543  2994  4325 E ExperimentLoader: 	at jdj.a(PG:4089)
08-23 23:17:00.543  2994  4325 E ExperimentLoader: 	... 17 more
,08-23 23:17:00.703   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 406590, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-23 23:17:29.104  1504  2201 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-23 23:17:34.363  3741  4328 V KeepSync: Connecting to GoogleApiClient
,08-23 23:17:34.364   874  1388 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-23 23:17:34.430  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 23:17:34.433  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 23:17:34.470  1504  3148 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-23 23:17:34.470  1504  3148 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-23 23:17:34.470  1504  3148 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 23:17:34.470  1504  3148 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 23:17:34.498  1722  4329 V BaseAuthAsyncOperation: access token request failed
,08-23 23:17:34.500  3741  4328 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-23 23:17:34.573  1504  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-23 23:17:34.573  1504  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-23 23:17:34.573  1504  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 23:17:34.573  1504  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 23:17:34.599  3741  4328 E KeepSync: IOException
08-23 23:17:34.599  3741  4328 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-23 23:17:34.599  3741  4328 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-23 23:17:34.599  3741  4328 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-23 23:17:34.599  3741  4328 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-23 23:17:34.599  3741  4328 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-23 23:17:34.599  3741  4328 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-23 23:17:34.599  3741  4328 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-23 23:17:34.599  3741  4328 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-23 23:17:34.599  3741  4328 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-23 23:17:34.599  3741  4328 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-23 23:17:34.599  3741  4328 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-23 23:17:34.599  3741  4328 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-23 23:17:34.599  3741  4328 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-23 23:17:34.599  3741  4328 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-23 23:17:34.599  3741  4328 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-23 23:17:34.599  3741  4328 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-23 23:17:34.599  3741  4328 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-23 23:17:34.599  3741  4328 E KeepSync: 	... 10 more
08-23 23:17:34.599  3741  4328 W KeepSync: Sync result 2
,08-23 23:17:34.613   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 466362, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-23 23:17:42.276  3801  3851 I jxcore-log: TAP version 13
08-23 23:17:42.276  3801  3851 I jxcore-log: 
,08-23 23:17:42.281  3801  3851 I jxcore-log: # setup
08-23 23:17:42.281  3801  3851 I jxcore-log: 
,08-23 23:17:42.965  3801  3851 I jxcore-log: # 1. onPeerLost calls jxcore
08-23 23:17:42.965  3801  3851 I jxcore-log: 
,08-23 23:17:43.032  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 23:17:43.032  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9504041 added. We now have 3 listener(s)
,08-23 23:17:43.034  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-23 23:17:43.035  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-23 23:17:43.035  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 23:17:43.035  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 23:17:43.035  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e0559e6 added. We now have 4 listener(s)
08-23 23:17:43.035  3801  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 23:17:43.036  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 23:17:43.042  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 23:17:43.056  3801  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 23:17:43.056  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:17:43.056  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:17:43.056  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 23:17:43.056  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 23:17:43.056  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 23:17:43.056  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 23:17:43.056  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 23:17:43.062  3801  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 23:17:43.062  3801  3851 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 23:17:43.063  3801  3851 I io.jxcore.node.ConnectionHelper: onPeerLost: [<no peer name> 11:22:33:22:11:00]
,08-23 23:17:43.063  3801  3851 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID 11:22:33:22:11:00
,08-23 23:17:43.069  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 23:17:43.078  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 23:17:45.071  3801  3851 I jxcore-log: onPeerLost
08-23 23:17:45.071  3801  3851 I jxcore-log: 
,08-23 23:17:45.076  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 23:17:45.076  3801  3851 I jxcore-log: 
,08-23 23:17:45.094  3801  3851 I jxcore-log: # teardown
08-23 23:17:45.094  3801  3851 I jxcore-log: 
,08-23 23:17:45.106  3801  3851 I jxcore-log: ok 1 check if callback was fired by onPeerLost
08-23 23:17:45.106  3801  3851 I jxcore-log: 
,08-23 23:17:45.108  3801  3851 I jxcore-log: ok 2 check if peerAvailable is false
08-23 23:17:45.108  3801  3851 I jxcore-log: 
,08-23 23:17:46.330  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-23 23:17:46.330  3801  3851 I jxcore-log: 
,08-23 23:17:46.335  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-23 23:17:46.335  3801  3851 I jxcore-log: 
,08-23 23:17:46.353  3801  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 23:17:46.353  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:17:46.353  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:17:46.353  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 23:17:46.353  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 23:17:46.353  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 23:17:46.353  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 23:17:46.353  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 23:17:46.362  3801  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 23:17:46.372  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-23 23:17:46.372  3801  3851 I jxcore-log: 
,08-23 23:17:46.378  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-23 23:17:46.378  3801  3851 I jxcore-log: 
,08-23 23:17:46.387  3801  3851 I jxcore-log: # setup
08-23 23:17:46.387  3801  3851 I jxcore-log: 
,08-23 23:17:46.395  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 23:17:46.395  3801  3851 I jxcore-log: 
,08-23 23:17:46.493  3801  3851 I jxcore-log: # 2. onPeerDiscovered calls jxcore
08-23 23:17:46.493  3801  3851 I jxcore-log: 
,08-23 23:17:46.715  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-23 23:17:46.715  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bae51d4 added. We now have 4 listener(s)
08-23 23:17:46.717  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-23 23:17:46.717  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 23:17:46.717  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 23:17:46.717  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 23:17:46.717  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@41f9f7d added. We now have 5 listener(s)
,08-23 23:17:46.717  3801  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 23:17:46.719  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 23:17:46.723  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 23:17:46.731  3801  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 23:17:46.731  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:17:46.731  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:17:46.731  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 23:17:46.731  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 23:17:46.731  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 23:17:46.731  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 23:17:46.731  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 23:17:46.737  3801  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 23:17:46.738  3801  3851 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 23:17:46.739  3801  3851 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 33:44:55:44:33:22], Bluetooth address: 33:44:55:44:33:22, device name: '', device address: ''
,08-23 23:17:46.744  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 23:17:46.750  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 23:17:48.742  3801  3851 I jxcore-log: onPeerDiscovered
08-23 23:17:48.742  3801  3851 I jxcore-log: 
,08-23 23:17:48.749  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 23:17:48.749  3801  3851 I jxcore-log: 
,08-23 23:17:48.763  3801  3851 I jxcore-log: # teardown
08-23 23:17:48.763  3801  3851 I jxcore-log: 
,08-23 23:17:48.771  3801  3851 I jxcore-log: ok 3 check if callback was fired by onPeerDiscovered
08-23 23:17:48.771  3801  3851 I jxcore-log: 
,08-23 23:17:48.772  3801  3851 I jxcore-log: ok 4 check if peerAvailable is true
08-23 23:17:48.772  3801  3851 I jxcore-log: 
,08-23 23:17:49.402  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-23 23:17:49.402  3801  3851 I jxcore-log: 
,08-23 23:17:49.407  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-23 23:17:49.407  3801  3851 I jxcore-log: 
,08-23 23:17:49.427  3801  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 23:17:49.427  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 23:17:49.427  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 23:17:49.427  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 23:17:49.427  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 23:17:49.427  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 23:17:49.427  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 23:17:49.427  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 23:17:49.432  3801  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 23:17:49.433  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-23 23:17:49.433  3801  3851 I jxcore-log: 
,08-23 23:17:49.437  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-23 23:17:49.437  3801  3851 I jxcore-log: 
,08-23 23:17:49.442  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 23:17:49.442  3801  3851 I jxcore-log: 
,08-23 23:17:49.540  3801  3851 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-23 23:17:49.540  3801  3851 I jxcore-log: 
,08-23 23:17:50.224  4330  4330 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-23 23:17:50.230  4330  4330 D AndroidRuntime: CheckJNI is OFF
,08-23 23:17:50.268  4330  4330 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-23 23:17:50.311  4330  4330 I Radio-JNI: register_android_hardware_Radio DONE
,08-23 23:17:50.333  4330  4330 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-23 23:17:50.352   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-23 23:17:50.352   874   887 I ActivityManager: Killing 3801:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-23 23:17:50.454   874  1311 D WifiService: Client connection lost with reason: 4
,08-23 23:17:50.455   874  1699 D GraphicsStats: Buffer count: 2
08-23 23:17:50.455   874  2352 I WindowState: WIN DEATH: Window{f3fb4ce u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-23 23:17:50.469   874   898 W PackageSettings: Skipping PackageSetting{2e9e39e com.example.hello/10273} due to missing metadata
,08-23 23:17:50.496   874   898 I art     : Starting a blocking GC Explicit
,08-23 23:17:50.514   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-23 23:17:50.516   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-23 23:17:50.517   874   887 E ActivityManager: Failure starting process com.test.thalitest
08-23 23:17:50.517   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-23 23:17:50.517   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-23 23:17:50.517   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-23 23:17:50.517   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-23 23:17:50.517   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-23 23:17:50.517   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-23 23:17:50.517   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-23 23:17:50.517   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-23 23:17:50.517   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-23 23:17:50.517   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-23 23:17:50.517   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-23 23:17:50.517   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-23 23:17:50.517   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-23 23:17:50.517   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-23 23:17:50.517   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-23 23:17:50.517   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 23:17:50.517   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-23 23:17:50.517   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 23:17:50.517   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-23 23:17:50.518   874   887 I ActivityManager:   Force finishing activity ActivityRecord{b2b0317 u0 com.test.thalitest/.MainActivity t2}
,08-23 23:17:50.530   874  1387 W ActivityManager: Spurious death for ProcessRecord{ba7a571 0:com.test.thalitest/u0a0}, curProc for 3801: null
,08-23 23:17:50.564   874   898 I art     : Explicit concurrent mark sweep GC freed 30872(1982KB) AllocSpace objects, 5(100KB) LOS objects, 33% free, 29MB/43MB, paused 819us total 66.650ms
,08-23 23:17:50.585   874   898 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-23 23:17:50.606  4330  4330 I art     : System.exit called, status: 0
,08-23 23:17:50.606  4330  4330 I AndroidRuntime: VM exiting with result code 0.
,08-23 23:17:50.622   874   898 I ActivityManager: Start proc 4342:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,08-23 23:17:50.623   874   898 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-23 23:17:50.641   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-23 23:17:50.645  4184  4184 D BluetoothMapAppObserver: onReceive
08-23 23:17:50.645  4184  4184 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-23 23:17:50.648  2162  2281 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-23 23:17:50.649  1863  1863 I Keyboard.Facilitator: resetDictionaries() : en_US
08-23 23:17:50.650   874  1299 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-23 23:17:50.653  3616  3616 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-23 23:17:50.669  1863  4354 I Keyboard.Facilitator.DecoderInitializer: run()
,08-23 23:17:50.683  1863  4354 I Decoder : createOrResetDecoder
,08-23 23:17:50.703  1923  1923 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-23 23:17:50.709   874  1388 I ActivityManager: Start proc 4357:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-23 23:17:50.713  1504  1504 I ConfigService: onCreate
,08-23 23:17:50.743   874  1699 I ActivityManager: Killing 3482:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-23 23:17:50.743   874  1934 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3801 uid 10000
08-23 23:17:50.743  1863  1863 I Keyboard.Facilitator: onFinishInput()
,08-23 23:17:50.754   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-23 23:17:50.766  1504  4364 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-23 23:17:50.766  1504  4364 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 23:17:50.766  1504  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 23:17:50.766  1504  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 23:17:50.766  1504  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 23:17:50.766  1504  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 23:17:50.766  1504  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 23:17:50.766  1504  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 23:17:50.766  1504  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 23:17:50.766  1504  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 23:17:50.766  1504  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 23:17:50.766  1504  4364 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 23:17:50.766  1504  4364 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 23:17:50.766  1504  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 23:17:50.766  1504  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-23 23:17:50.766  1504  4364 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-23 23:17:50.766  1504  4364 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-23 23:17:50.766  1504  4364 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-23 23:17:50.766  1504  4364 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-23 23:17:50.766  1504  4364 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 23:17:50.766  1504  4364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 23:17:50.766  1504  4364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 23:17:50.766  1504  4364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 23:17:50.766  1504  4364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 23:17:50.766  1504  4364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 23:17:50.766  1504  4364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 23:17:50.766  1504  4364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 23:17:50.766  1504  4364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 23:17:50.766  1504  4364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 23:17:50.766  1504  4364 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 23:17:50.766  1504  4364 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 23:17:50.766  1504  4364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 23:17:50.766  1504  4364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-23 23:17:50.766  1504  4364 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-23 23:17:50.766  1504  4364 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-23 23:17:50.766  1504  4364 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-23 23:17:50.767  1504  4364 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-23 23:17:50.777  4357  4357 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-23 23:17:50.788  1935  2005 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-23 23:17:50.790   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-23 23:17:50.791   874   886 E PackageManager: Failed to write settings, restoring backup
08-23 23:17:50.791   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-23 23:17:50.791   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-23 23:17:50.791   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-23 23:17:50.791   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-23 23:17:50.791   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-23 23:17:50.791   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 23:17:50.791   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-23 23:17:50.791   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-23 23:17:50.794  1863  4354 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-23 23:17:50.795   874   887 E DropBoxManagerService: Can't write: system_server_wtf
08-23 23:17:50.795   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-23 23:17:50.795   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 23:17:50.795   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 23:17:50.795   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 23:17:50.795   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 23:17:50.795   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 23:17:50.795   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 23:17:50.795   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-23 23:17:50.795   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-23 23:17:50.795   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-23 23:17:50.795   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 23:17:50.795   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 23:17:50.795   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-23 23:17:50.795   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 23:17:50.795   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-23 23:17:50.795   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 23:17:50.795   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 23:17:50.795   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 23:17:50.795   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 23:17:50.795   874   887 E DropBoxManagerService: 	... 13 more
,08-23 23:17:50.800   874  2003 I ActivityManager: Start proc 4371:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-23 23:17:50.801  1935  2005 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-23 23:17:50.801  1935  2005 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1935
08-23 23:17:50.801  1935  2005 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 23:17:50.801  1935  2005 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-23 23:17:50.801  1935  2005 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-23 23:17:50.801  1935  2005 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-23 23:17:50.801  1935  2005 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-23 23:17:50.801  1935  2005 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-23 23:17:50.801  1935  2005 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-23 23:17:50.801  1935  2005 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-23 23:17:50.801  1935  2005 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 23:17:50.801  1935  2005 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 23:17:50.801  1935  2005 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-23 23:17:50.801  1935  2005 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-23 23:17:50.803   874  2352 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-23 23:17:50.804   874  4377 E DropBoxManagerService: Can't write: system_app_crash
08-23 23:17:50.804   874  4377 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-23 23:17:50.804   874  4377 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 23:17:50.804   874  4377 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 23:17:50.804   874  4377 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 23:17:50.804   874  4377 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 23:17:50.804   874  4377 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 23:17:50.804   874  4377 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 23:17:50.804   874  4377 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 23:17:50.804   874  4377 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 23:17:50.804   874  4377 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 23:17:50.804   874  4377 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 23:17:50.804   874  4377 E DropBoxManagerService: 	... 5 more
,08-23 23:17:50.806  1935  2005 I Process : Sending signal. PID: 1935 SIG: 9
,08-23 23:17:50.847  1863  4354 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-23 23:17:50.849  1863  4354 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-23 23:17:50.849  1863  4354 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-23 23:17:50.850  1863  4354 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-23 23:17:50.850  1863  4354 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-23 23:17:50.851  1863  4354 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-23 23:17:50.851  1863  4354 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-23 23:17:50.852  1863  4354 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-23 23:17:50.852  1863  4354 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-23 23:17:50.852  1863  4354 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-23 23:17:50.852  1863  4354 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-23 23:17:50.852  1863  4354 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-23 23:17:50.852  1863  4354 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-23 23:17:50.875   874  1388 D GraphicsStats: Buffer count: 1
08-23 23:17:50.876   874  1387 I WindowState: WIN DEATH: Window{7697fcd u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-23 23:17:50.887   874  1388 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1935) has died
,08-23 23:17:50.888   874  1388 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-23 23:17:50.890   874  1388 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-23 23:17:50.899  4357  4357 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-23 23:17:50.907   874   887 I ActivityManager: Start proc 4390:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-23 23:17:50.930   874  2352 I ActivityManager: Start proc 4403:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-23 23:17:50.935  4357  4406 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-23 23:17:50.957  1722  4400 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-23 23:17:50.958  1722  4400 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-23 23:17:50.966  4390  4390 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-23 23:17:50.966  4390  4390 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 23:17:50.966  4390  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 23:17:50.966  4390  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 23:17:50.966  4390  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 23:17:50.966  4390  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 23:17:50.966  4390  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 23:17:50.966  4390  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 23:17:50.966  4390  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 23:17:50.966  4390  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 23:17:50.966  4390  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 23:17:50.966  4390  4390 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 23:17:50.966  4390  4390 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 23:17:50.966  4390  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 23:17:50.966  4390  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 23:17:50.966  4390  4390 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-23 23:17:50.966  4390  4390 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-23 23:17:50.966  4390  4390 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-23 23:17:50.966  4390  4390 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-23 23:17:50.966  4390  4390 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-23 23:17:50.966  4390  4390 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-23 23:17:50.966  4390  4390 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-23 23:17:50.966  4390  4390 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 23:17:50.966  4390  4390 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 23:17:50.966  4390  4390 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 23:17:50.966  4390  4390 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-23 23:17:50.966  4390  4390 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 23:17:50.966  4390  4390 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 23:17:50.966  4390  4390 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 23:17:50.966  4390  4390 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 23:17:50.966  4390  4390 D AndroidRuntime: Shutting down VM
,08-23 23:17:50.969  4403  4403 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-23 23:17:50.975  4390  4390 E AndroidRuntime: FATAL EXCEPTION: main
08-23 23:17:50.975  4390  4390 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4390
08-23 23:17:50.975  4390  4390 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 23:17:50.975  4390  4390 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-23 23:17:50.975  4390  4390 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-23 23:17:50.975  4390  4390 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-23 23:17:50.975  4390  4390 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 23:17:50.975  4390  4390 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 23:17:50.975  4390  4390 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 23:17:50.975  4390  4390 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-23 23:17:50.975  4390  4390 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 23:17:50.975  4390  4390 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 23:17:50.975  4390  4390 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 23:17:50.975  4390  4390 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 23:17:50.975  4390  4390 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 23:17:50.975  4390  4390 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 23:17:50.975  4390  4390 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 23:17:50.975  4390  4390 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 23:17:50.975  4390  4390 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 23:17:50.975  4390  4390 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 23:17:50.975  4390  4390 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 23:17:50.975  4390  4390 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 23:17:50.975  4390  4390 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 23:17:50.975  4390  4390 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 23:17:50.975  4390  4390 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 23:17:50.975  4390  4390 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 23:17:50.975  4390  4390 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 23:17:50.975  4390  4390 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 23:17:50.975  4390  4390 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-23 23:17:50.975  4390  4390 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-23 23:17:50.975  4390  4390 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-23 23:17:50.975  4390  4390 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-23 23:17:50.975  4390  4390 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-23 23:17:50.975  4390  4390 E AndroidRuntime: 	... 10 more
08-23 23:17:50.976   874  1387 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-23 23:17:50.977  4390  4390 I Process : Sending signal. PID: 4390 SIG: 9
,08-23 23:17:50.978   874  4416 E DropBoxManagerService: Can't write: system_app_crash
08-23 23:17:50.978   874  4416 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-23 23:17:50.978   874  4416 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 23:17:50.978   874  4416 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 23:17:50.978   874  4416 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 23:17:50.978   874  4416 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 23:17:50.978   874  4416 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 23:17:50.978   874  4416 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 23:17:50.978   874  4416 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 23:17:50.978   874  4416 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 23:17:50.978   874  4416 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 23:17:50.978   874  4416 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 23:17:50.978   874  4416 E DropBoxManagerService: 	... 5 more
08-23 23:17:50.985  1722  4400 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-23 23:17:50.985  1722  4400 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-23 23:17:51.002  1504  1504 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-23 23:17:51.003  1504  1504 D AndroidRuntime: Shutting down VM
,08-23 23:17:51.004  1504  1504 E AndroidRuntime: FATAL EXCEPTION: main
08-23 23:17:51.004  1504  1504 E AndroidRuntime: Process: com.google.process.gapps, PID: 1504
08-23 23:17:51.004  1504  1504 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 23:17:51.004  1504  1504 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-23 23:17:51.004  1504  1504 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-23 23:17:51.004  1504  1504 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-23 23:17:51.004  1504  1504 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 23:17:51.004  1504  1504 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-23 23:17:51.004  1504  1504 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 23:17:51.004  1504  1504 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 23:17:51.004  1504  1504 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 23:17:51.004  1504  1504 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 23:17:51.004  1504  1504 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 23:17:51.004  1504  1504 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method),
08-23 23:17:51.004  1504  1504 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-23 23:17:51.004  1504  1504 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-23 23:17:51.004  1504  1504 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-23 23:17:51.004  1504  1504 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-23 23:17:51.004  1504  1504 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-23 23:17:51.004  1504  1504 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-23 23:17:51.004  1504  1504 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-23 23:17:51.004  1504  1504 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-23 23:17:51.004  1504  1504 E AndroidRuntime: 	... 8 more
,08-23 23:17:51.007  1504  1504 I Process : Sending signal. PID: 1504 SIG: 9
,08-23 23:17:51.008   874  4420 E DropBoxManagerService: Can't write: system_app_crash
08-23 23:17:51.008   874  4420 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-23 23:17:51.008   874  4420 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 23:17:51.008   874  4420 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 23:17:51.008   874  4420 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 23:17:51.008   874  4420 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 23:17:51.008   874  4420 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 23:17:51.008   874  4420 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 23:17:51.008   874  4420 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 23:17:51.008   874  4420 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 23:17:51.008   874  4420 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 23:17:51.008   874  4420 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 23:17:51.008   874  4420 E DropBoxManagerService: 	... 5 more
,08-23 23:17:51.009   874  1945 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4390) has died
08-23 23:17:51.010   874  1945 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-23 23:17:51.015  4357  4386 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-23 23:17:51.015  4357  4386 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 23:17:51.015  4357  4386 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 23:17:51.015  4357  4386 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 23:17:51.015  4357  4386 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 23:17:51.015  4357  4386 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 23:17:51.015  4357  4386 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 23:17:51.015  4357  4386 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 23:17:51.015  4357  4386 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 23:17:51.015  4357  4386 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 23:17:51.015  4357  4386 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 23:17:51.015  4357  4386 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 23:17:51.015  4357  4386 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 23:17:51.015  4357  4386 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 23:17:51.015  4357  4386 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-23 23:17:51.015  4357  4386 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-23 23:17:51.015  4357  4386 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-23 23:17:51.015  4357  4386 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-23 23:17:51.015  4357  4386 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-23 23:17:51.015  4357  4386 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 23:17:51.015  4357  4386 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-23 23:17:51.015  4357  4386 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-23 23:17:51.015  4357  4386 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-23 23:17:51.015  4357  4386 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 23:17:51.015  4357  4386 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 23:17:51.015  4357  4386 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 23:17:51.015  4357  4386 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 23:17:51.015  4357  4386 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 23:17:51.015  4357  4386 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 23:17:51.015  4357  4386 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 23:17:51.015  4357  4386 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 23:17:51.015  4357  4386 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 23:17:51.015  4357  4386 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 23:17:51.015  4357  4386 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 23:17:51.015  4357  4386 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 23:17:51.015  4357  4386 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 23:17:51.015  4357  4386 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-23 23:17:51.015  4357  4386 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-23 23:17:51.015  4357  4386 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-23 23:17:51.015  4357  4386 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-23 23:17:51.015  4357  4386 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-23 23:17:51.015  4357  4386 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 23:17:51.015  4357  4386 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-23 23:17:51.015  4357  4386 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-23 23:17:51.024   874   887 I ActivityManager: Start proc 4421:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-23 23:17:51.026   874  2003 I ActivityManager: Killing 3668:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-23 23:17:51.052   874  1311 D WifiService: Client connection lost with reason: 4
,08-23 23:17:51.065  4357  4386 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-23 23:17:51.069  4357  4406 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-23 23:17:51.069  4357  4406 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 23:17:51.069  4357  4406 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 23:17:51.069  4357  4406 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 23:17:51.069  4357  4406 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 23:17:51.069  4357  4406 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 23:17:51.069  4357  4406 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 23:17:51.069  4357  4406 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 23:17:51.069  4357  4406 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 23:17:51.069  4357  4406 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 23:17:51.069  4357  4406 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 23:17:51.069  4357  4406 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 23:17:51.069  4357  4406 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 23:17:51.069  4357  4406 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 23:17:51.069  4357  4406 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 23:17:51.069  4357  4406 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-23 23:17:51.069  4357  4406 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-23 23:17:51.069  4357  4406 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-23 23:17:51.069  4357  4406 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-23 23:17:51.069  4357  4406 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-23 23:17:51.069  4357  4406 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-23 23:17:51.069  4357  4406 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-23 23:17:51.069  4357  4406 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 23:17:51.069  4357  4406 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-23 23:17:51.069  4357  4406 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-23 23:17:51.070  4357  4406 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-23 23:17:51.070  4357  4406 E AndroidRuntime: Process: android.process.acore, PID: 4357
08-23 23:17:51.070  4357  4406 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 23:17:51.070  4357  4406 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 23:17:51.070  4357  4406 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 23:17:51.070  4357  4406 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 23:17:51.070  4357  4406 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 23:17:51.070  4357  4406 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 23:17:51.070  4357  4406 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 23:17:51.070  4357  4406 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 23:17:51.070  4357  4406 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 23:17:51.070  4357  4406 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 23:17:51.070  4357  4406 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 23:17:51.070  4357  4406 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 23:17:51.070  4357  4406 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 23:17:51.070  4357  4406 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 23:17:51.070  4357  4406 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-23 23:17:51.070  4357  4406 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-23 23:17:51.070  4357  4406 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-23 23:17:51.070  4357  4406 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-23 23:17:51.070  4357  4406 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-23 23:17:51.070  4357  4406 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-23 23:17:51.070  4357  4406 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-23 23:17:51.070  4357  4406 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 23:17:51.070  4357  4406 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-23 23:17:51.070  4357  4406 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-23 23:17:51.070  4357  4386 I Process : Sending signal. PID: 4357 SIG: 9
,08-23 23:17:51.081   874   884 I ActivityManager: Process com.google.process.gapps (pid 1504) has died
,08-23 23:17:51.081   874   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
08-23 23:17:51.082   874   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 10999ms
08-23 23:17:51.082   874   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 20999ms
,08-23 23:17:51.089   874  4433 E DropBoxManagerService: Can't write: system_app_crash
08-23 23:17:51.089   874  4433 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-23 23:17:51.089   874  4433 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 23:17:51.089   874  4433 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 23:17:51.089   874  4433 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 23:17:51.089   874  4433 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 23:17:51.089   874  4433 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 23:17:51.089   874  4433 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 23:17:51.089   874  4433 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 23:17:51.089   874  4433 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 23:17:51.089   874  4433 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 23:17:51.089   874  4433 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 23:17:51.089   874  4433 E DropBoxManagerService: 	... 5 more
,08-23 23:17:51.101  1722  1722 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-23 23:17:51.103   874   885 I ActivityManager: Start proc 4434:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,08-23 23:17:51.109  4421  4421 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-23 23:17:51.109  4421  4421 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 23:17:51.109  4421  4421 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 23:17:51.109  4421  4421 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 23:17:51.109  4421  4421 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 23:17:51.109  4421  4421 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 23:17:51.109  4421  4421 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 23:17:51.109  4421  4421 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 23:17:51.109  4421  4421 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 23:17:51.109  4421  4421 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 23:17:51.109  4421  4421 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 23:17:51.109  4421  4421 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 23:17:51.109  4421  4421 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 23:17:51.109  4421  4421 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 23:17:51.109  4421  4421 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 23:17:51.109  4421  4421 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-23 23:17:51.109  4421  4421 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-23 23:17:51.109  4421  4421 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-23 23:17:51.109  4421  4421 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-23 23:17:51.109  4421  4421 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-23 23:17:51.109  4421  4421 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-23 23:17:51.109  4421  4421 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-23 23:17:51.109  4421  4421 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 23:17:51.109  4421  4421 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 23:17:51.109  4421  4421 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 23:17:51.109  4421  4421 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-23 23:17:51.109  4421  4421 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 23:17:51.109  4421  4421 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 23:17:51.109  4421  4421 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 23:17:51.109  4421  4421 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```
