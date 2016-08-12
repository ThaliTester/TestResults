#### Test 797638306af5278_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-12 18:22:27.333  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 18:22:27.348  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-12 18:22:27.353  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-12 18:22:27.428  1511  2287 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-12 18:22:27.428  1511  2287 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-12 18:22:27.428  1511  2287 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 18:22:27.429  1511  2287 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-12 18:22:27.465  3511  3511 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-12 18:22:27.466  3511  3511 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-12 18:22:27.467  3511  3511 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-12 18:22:27.986  3809  3809 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-12 18:22:27.991  3809  3809 D AndroidRuntime: CheckJNI is OFF
08-12 18:22:28.027  3809  3809 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-12 18:22:28.070  3809  3809 I Radio-JNI: register_android_hardware_Radio DONE
08-12 18:22:28.090  3809  3809 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-12 18:22:28.094   873  1936 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-12 18:22:28.133  3809  3809 D AndroidRuntime: Shutting down VM
08-12 18:22:28.135  1989  2004 W SearchService: Abort, client detached.
08-12 18:22:28.142  1989  1989 I HotwordDetector: Closing mic
08-12 18:22:28.143  1989  2341 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@3fa339e
08-12 18:22:28.143  1989  2352 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-12 18:22:28.177   873  1923 I ActivityManager: Start proc 3818:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-12 18:22:28.205   377  2354 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-12 18:22:28.207   377  2354 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-12 18:22:28.213   377  1285 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-12 18:22:28.216  1989  2348 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-12 18:22:28.218  1989  2351 I MicroRecognitionRnrImpl: Detection finished
08-12 18:22:28.285  3818  3818 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-12 18:22:28.315  3818  3818 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-12 18:22:28.328  3818  3818 I LibraryLoader: Time to load native libraries: 9 ms (timestamps 9675-9684)
08-12 18:22:28.328  3818  3818 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 18:22:28.351  3818  3818 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e7579dd}
08-12 18:22:28.353  3818  3818 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 18:22:28.354  3818  3818 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-12 18:22:28.376  3818  3818 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-12 18:22:28.378  3818  3818 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-12 18:22:28.418  3818  3818 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-12 18:22:28.436  3818  3818 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-12 18:22:28.436  3818  3818 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-12 18:22:28.436  3818  3818 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-12 18:22:28.436  3818  3818 I Adreno  : Build Date                       : 10/20/15
08-12 18:22:28.436  3818  3818 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-12 18:22:28.436  3818  3818 I Adreno  : Local Branch                     : M14
08-12 18:22:28.436  3818  3818 I Adreno  : Remote Branch                    : 
08-12 18:22:28.436  3818  3818 I Adreno  : Remote Branch                    : 
08-12 18:22:28.436  3818  3818 I Adreno  : Reconstruct Branch               : 
,08-12 18:22:28.527   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c088a31:true
,08-12 18:22:28.608  3818  3818 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-12 18:22:28.625  3818  3818 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-12 18:22:28.751  3818  3857 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-12 18:22:28.768  3818  3843 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-12 18:22:28.814  3818  3857 I OpenGLRenderer: Initialized EGL, version 1.4
,08-12 18:22:28.932   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +775ms
,08-12 18:22:28.938  1861  1861 I Keyboard.Facilitator: onFinishInput()
,08-12 18:22:29.013   873  1387 I ActivityManager: Killing 3382:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-12 18:22:29.036  3818  3818 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3818
,08-12 18:22:29.089   873  1387 I ActivityManager: Killing 2982:com.google.android.calendar/u0a37 (adj 15): empty #18
,08-12 18:22:29.157  3818  3818 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-12 18:22:29.337  3818  3860 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1699870416
,08-12 18:22:29.351  3818  3860 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 18:22:29.351  3818  3860 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 18:22:29.351  3818  3860 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 18:22:29.351  3818  3860 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 18:22:29.351  3818  3860 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-12 18:22:29.351  3818  3860 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2794f8 added. We now have 1 listener(s)
,08-12 18:22:29.357  3818  3860 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-12 18:22:29.358  3818  3860 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-12 18:22:29.359  3818  3860 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-12 18:22:29.360  3818  3860 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-12 18:22:29.367  3818  3860 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-12 18:22:29.367  3818  3860 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 18:22:29.367  3818  3860 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-12 18:22:29.367  3818  3860 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-12 18:22:29.367  3818  3860 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 18:22:29.367  3818  3860 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 18:22:29.367  3818  3860 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-12 18:22:29.367  3818  3860 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 18:22:29.367  3818  3860 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-12 18:22:29.367  3818  3860 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-12 18:22:29.367  3818  3860 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 18:22:29.367  3818  3860 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 18:22:29.367  3818  3860 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 18:22:29.367  3818  3860 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-12 18:22:29.367  3818  3860 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e9b37 added. We now have 1 listener(s)
,08-12 18:22:29.367  3818  3860 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-12 18:22:29.372   873  1314 D WifiService: New client listening to asynchronous messages
08-12 18:22:29.374  3818  3860 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-12 18:22:29.374  3818  3860 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-12 18:22:29.374  3818  3860 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-12 18:22:29.374  3818  3860 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-12 18:22:29.374  3818  3860 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-12 18:22:29.378  3818  3860 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 18:22:29.378  3818  3860 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-12 18:22:29.385  3818  3860 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-12 18:22:29.385  3818  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 18:22:29.385  3818  3860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 18:22:29.385  3818  3860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 18:22:29.385  3818  3860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 18:22:29.385  3818  3860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 18:22:29.385  3818  3860 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 18:22:29.385  3818  3860 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 18:22:29.385  3818  3860 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 18:22:29.385  3818  3860 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-12 18:22:29.385  3818  3860 D io.jxcore.node.ConnectivityMonitor: start: OK
08-12 18:22:29.386  3818  3860 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-12 18:22:29.390  3818  3818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 18:22:29.392  3818  3818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 18:22:29.546   873  2099 D NetlinkSocketObserver: NeighborEvent{elapsedMs=120903, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 18:22:29.603  3818  3818 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-12 18:22:30.688  3818  3868 W jxcore-log: Initializing JXcore engine
08-12 18:22:30.688  3818  3868 W jxcore-log: JXcore engine is ready
,08-12 18:22:30.753  3868  3868 W Thread-333: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8940 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-12 18:22:30.753  3868  3868 W Thread-333: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[10690]" dev="sockfs" ino=10690 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-12 18:22:30.753  3868  3868 W Thread-333: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-12 18:22:30.753  3868  3868 W Thread-333: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[26816]" dev="sockfs" ino=26816 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-12 18:22:30.772  3818  3868 W jxcore-log: Starting JXcore engine
,08-12 18:22:30.854  3818  3868 W jxcore-log: Platform android
08-12 18:22:30.854  3818  3868 W jxcore-log: 
08-12 18:22:30.854  3818  3868 W jxcore-log: Process ARCH arm
08-12 18:22:30.854  3818  3868 W jxcore-log: 
,08-12 18:22:31.018  3818  3868 I jxcore-log: JXcore Cordova bridge is ready!
08-12 18:22:31.018  3818  3868 I jxcore-log: 
08-12 18:22:31.018  3818  3868 W jxcore-log: JXcore engine is started
,08-12 18:22:31.025  3818  3860 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-12 18:22:31.033  3818  3818 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-12 18:22:31.868   873  1313 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-12 18:22:36.179  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 18:22:36.183  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 18:22:36.234  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-12 18:22:36.234  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-12 18:22:36.234  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 18:22:36.234  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 18:22:36.270  3549  3876 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-12 18:22:36.270  3549  3876 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 18:22:36.270  3549  3876 E HttpOperation: 	at jdm.a(PG:82)
08-12 18:22:36.270  3549  3876 E HttpOperation: 	at jcs.o(PG:406)
08-12 18:22:36.270  3549  3876 E HttpOperation: 	at jcn.a(PG:1379)
08-12 18:22:36.270  3549  3876 E HttpOperation: 	at jcs.i(PG:143)
08-12 18:22:36.270  3549  3876 E HttpOperation: 	at blb.a(PG:3937)
08-12 18:22:36.270  3549  3876 E HttpOperation: 	at czp.a(PG:18188)
08-12 18:22:36.270  3549  3876 E HttpOperation: 	at czp.a(PG:9081)
08-12 18:22:36.270  3549  3876 E HttpOperation: 	at czq.run(PG:1686)
08-12 18:22:36.270  3549  3876 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 18:22:36.270  3549  3876 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 18:22:36.270  3549  3876 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 18:22:36.270  3549  3876 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 18:22:36.270  3549  3876 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 18:22:36.270  3549  3876 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 18:22:36.270  3549  3876 E HttpOperation: 	at jdj.a(PG:4091)
08-12 18:22:36.270  3549  3876 E HttpOperation: 	at jdj.a(PG:1125)
08-12 18:22:36.270  3549  3876 E HttpOperation: 	at jdm.a(PG:77)
08-12 18:22:36.270  3549  3876 E HttpOperation: 	... 12 more
08-12 18:22:36.270  3549  3876 E HttpOperation: Caused by: faj: BadAuthentication
08-12 18:22:36.270  3549  3876 E HttpOperation: 	at fal.a(PG:38)
08-12 18:22:36.270  3549  3876 E HttpOperation: 	at jdj.a(PG:4089)
08-12 18:22:36.270  3549  3876 E HttpOperation: 	... 14 more
,08-12 18:22:36.359  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-12 18:22:36.359  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-12 18:22:36.359  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 18:22:36.359  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 18:22:36.392  3549  3876 E HttpOperation: [getmobileexperiments] Unexpected exception
08-12 18:22:36.392  3549  3876 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 18:22:36.392  3549  3876 E HttpOperation: 	at jdm.a(PG:82)
08-12 18:22:36.392  3549  3876 E HttpOperation: 	at jcs.o(PG:406)
08-12 18:22:36.392  3549  3876 E HttpOperation: 	at jcn.a(PG:1379)
08-12 18:22:36.392  3549  3876 E HttpOperation: 	at jcs.i(PG:143)
08-12 18:22:36.392  3549  3876 E HttpOperation: 	at hec.a(PG:42)
08-12 18:22:36.392  3549  3876 E HttpOperation: 	at hee.a(PG:102)
08-12 18:22:36.392  3549  3876 E HttpOperation: 	at czr.a(PG:65)
08-12 18:22:36.392  3549  3876 E HttpOperation: 	at kka.a(PG:108)
08-12 18:22:36.392  3549  3876 E HttpOperation: 	at czp.a(PG:19176)
08-12 18:22:36.392  3549  3876 E HttpOperation: 	at czp.a(PG:9081)
08-12 18:22:36.392  3549  3876 E HttpOperation: 	at czq.run(PG:1686)
08-12 18:22:36.392  3549  3876 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 18:22:36.392  3549  3876 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 18:22:36.392  3549  3876 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 18:22:36.392  3549  3876 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 18:22:36.392  3549  3876 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 18:22:36.392  3549  3876 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 18:22:36.392  3549  3876 E HttpOperation: 	at jdj.a(PG:4091)
08-12 18:22:36.392  3549  3876 E HttpOperation: 	at jdj.a(PG:1125)
08-12 18:22:36.392  3549  3876 E HttpOperation: 	at jdm.a(PG:77)
08-12 18:22:36.392  3549  3876 E HttpOperation: 	... 15 more
08-12 18:22:36.392  3549  3876 E HttpOperation: Caused by: faj: BadAuthentication
08-12 18:22:36.392  3549  3876 E HttpOperation: 	at fal.a(PG:38)
08-12 18:22:36.392  3549  3876 E HttpOperation: 	at jdj.a(PG:4089)
08-12 18:22:36.392  3549  3876 E HttpOperation: 	... 17 more
08-12 18:22:36.393  3549  3876 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-12 18:22:36.393  3549  3876 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-12 18:22:36.393  3549  3876 E ExperimentLoader: 	at jdm.a(PG:82)
08-12 18:22:36.393  3549  3876 E ExperimentLoader: 	at jcs.o(PG:406)
08-12 18:22:36.393  3549  3876 E ExperimentLoader: 	at jcn.a(PG:1379)
08-12 18:22:36.393  3549  3876 E ExperimentLoader: 	at jcs.i(PG:143)
08-12 18:22:36.393  3549  3876 E ExperimentLoader: 	at hec.a(PG:42)
08-12 18:22:36.393  3549  3876 E ExperimentLoader: 	at hee.a(PG:102)
08-12 18:22:36.393  3549  3876 E ExperimentLoader: 	at czr.a(PG:65)
08-12 18:22:36.393  3549  3876 E ExperimentLoader: 	at kka.a(PG:108)
08-12 18:22:36.393  3549  3876 E ExperimentLoader: 	at czp.a(PG:19176)
08-12 18:22:36.393  3549  3876 E ExperimentLoader: 	at czp.a(PG:9081)
08-12 18:22:36.393  3549  3876 E ExperimentLoader: 	at czq.run(PG:1686)
08-12 18:22:36.393  3549  3876 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 18:22:36.393  3549  3876 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 18:22:36.393  3549  3876 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 18:22:36.393  3549  3876 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 18:22:36.393  3549  3876 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-12 18:22:36.393  3549  3876 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 18:22:36.393  3549  3876 E ExperimentLoader: 	at jdj.a(PG:4091)
08-12 18:22:36.393  3549  3876 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-12 18:22:36.393  3549  3876 E ExperimentLoader: 	at jdm.a(PG:77)
08-12 18:22:36.393  3549  3876 E ExperimentLoader: 	... 15 more
08-12 18:22:36.393  3549  3876 E ExperimentLoader: Caused by: faj: BadAuthentication
08-12 18:22:36.393  3549  3876 E ExperimentLoader: 	at fal.a(PG:38)
08-12 18:22:36.393  3549  3876 E ExperimentLoader: 	at jdj.a(PG:4089)
08-12 18:22:36.393  3549  3876 E ExperimentLoader: 	... 17 more
,08-12 18:22:36.546   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 127245, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-12 18:22:41.128  3818  3868 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 18:22:41.128  3818  3868 I jxcore-log: 
,08-12 18:22:41.130  3818  3868 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 18:22:41.130  3818  3868 I jxcore-log: 
,08-12 18:22:41.141  3818  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 18:22:41.141  3818  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 18:22:41.141  3818  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 18:22:41.141  3818  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 18:22:41.141  3818  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 18:22:41.141  3818  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 18:22:41.141  3818  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 18:22:41.141  3818  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 18:22:41.148  3818  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-12 18:22:41.150  3818  3868 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 18:22:41.150  3818  3868 I jxcore-log: 
,08-12 18:22:41.152  3818  3868 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 18:22:41.152  3818  3868 I jxcore-log: 
,08-12 18:22:41.533  3818  3868 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
,08-12 18:22:41.533  3818  3868 I jxcore-log: Failed to execute UT.
08-12 18:22:41.533  3818  3868 I jxcore-log: 
,08-12 18:22:41.533  3818  3868 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-12 18:22:41.533  3818  3868 I jxcore-log: 
,08-12 18:22:41.536  3818  3868 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 18:22:41.536  3818  3868 I jxcore-log: 
,08-12 18:22:41.561  3818  3818 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-12 18:22:42.159  3882  3882 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-12 18:22:42.163  3882  3882 D AndroidRuntime: CheckJNI is OFF
,08-12 18:22:42.200  3882  3882 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-12 18:22:42.241  3882  3882 I Radio-JNI: register_android_hardware_Radio DONE
,08-12 18:22:42.262  3882  3882 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-12 18:22:42.275   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-12 18:22:42.276   873   886 I ActivityManager: Killing 3818:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-12 18:22:42.346   873  1304 W InputDispatcher: channel '69f61a1 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,08-12 18:22:42.346   873  1304 E InputDispatcher: channel '69f61a1 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,08-12 18:22:42.350   873  1314 D WifiService: Client connection lost with reason: 4
08-12 18:22:42.351   873  2243 D GraphicsStats: Buffer count: 2
08-12 18:22:42.353   873  1935 I WindowState: WIN DEATH: Window{69f61a1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 18:22:42.353   873  1935 W InputDispatcher: Attempted to unregister already unregistered input channel '69f61a1 com.test.thalitest/com.test.thalitest.MainActivity (server)'
,08-12 18:22:42.369   873   886 W ActivityManager: Force removing ActivityRecord{2ec338e u0 com.test.thalitest/.MainActivity t2}: app died, no saved state
,08-12 18:22:42.388   873   896 W PackageSettings: Skipping PackageSetting{100a870 com.example.hello/10273} due to missing metadata
,08-12 18:22:42.424   873   896 I art     : Starting a blocking GC Explicit
,08-12 18:22:42.437   873  2241 W ActivityManager: Spurious death for ProcessRecord{2ddb6fe 0:com.test.thalitest/u0a0}, curProc for 3818: null
,08-12 18:22:42.474   873  2080 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3818 uid 10000
,08-12 18:22:42.477  1861  1861 I Keyboard.Facilitator: onFinishInput()
,08-12 18:22:42.486   873   896 I art     : Explicit concurrent mark sweep GC freed 51874(3MB) AllocSpace objects, 15(324KB) LOS objects, 33% free, 29MB/43MB, paused 1.762ms total 61.021ms
,08-12 18:22:42.546   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-12 18:22:42.550  3882  3882 I art     : System.exit called, status: 0
08-12 18:22:42.551  3882  3882 I AndroidRuntime: VM exiting with result code 0.
,08-12 18:22:42.557  1989  3895 I MicroRecognitionRnrImpl: Starting detection.
,08-12 18:22:42.559  1989  3896 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@a811b4a
,08-12 18:22:42.561   377  3898 I AudioFlinger: AudioFlinger's thread 0xb1e00000 ready to run
,08-12 18:22:42.563   377  1285 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,08-12 18:22:42.563   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-12 18:22:42.564  1989  3896 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@a811b4a
,08-12 18:22:42.574   377  3898 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(61: voice-rec-mic)
,08-12 18:22:42.574   377  3898 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(61) acdb_id(62)
,08-12 18:22:42.574   377  3898 D audio_hw_primary: enable_snd_device: snd_device(61: voice-rec-mic)
,08-12 18:22:42.580  2689  2689 D BluetoothMapAppObserver: onReceive
,08-12 18:22:42.580  2689  2689 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-12 18:22:42.582  2014  2285 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-12 18:22:42.583   377  3898 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
08-12 18:22:42.585   873  1305 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-12 18:22:42.599  3634  3634 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-12 18:22:42.604  1861  1861 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-12 18:22:42.607  1861  3902 I Keyboard.Facilitator.DecoderInitializer: run()
,08-12 18:22:42.612  1861  3902 I Decoder : createOrResetDecoder
,08-12 18:22:42.642  1925  1925 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-12 18:22:42.646  1511  1511 I ConfigService: onCreate
,08-12 18:22:42.668  1989  1989 I HotwordWorkerImpl: onReady
,08-12 18:22:42.683  1861  3902 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-12 18:22:42.690  1511  1511 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-12 18:22:42.691  1511  1511 D AndroidRuntime: Shutting down VM,
--------- beginning of crash
08-12 18:22:42.692  1511  1511 E AndroidRuntime: FATAL EXCEPTION: main
08-12 18:22:42.692  1511  1511 E AndroidRuntime: Process: com.google.process.gapps, PID: 1511
08-12 18:22:42.692  1511  1511 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 18:22:42.692  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-12 18:22:42.692  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-12 18:22:42.692  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-12 18:22:42.692  1511  1511 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 18:22:42.692  1511  1511 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 18:22:42.692  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-12 18:22:42.692  1511  1511 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 18:22:42.692  1511  1511 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-12 18:22:42.692  1511  1511 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-12 18:22:42.692  1511  1511 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 18:22:42.692  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-12 18:22:42.692  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-12 18:22:42.692  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-12 18:22:42.692  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-12 18:22:42.692  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-12 18:22:42.692  1511  1511 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-12 18:22:42.692  1511  1511 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-12 18:22:42.692  1511  1511 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-12 18:22:42.692  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-12 18:22:42.692  1511  1511 E AndroidRuntime: 	... 8 more
,08-12 18:22:42.695   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-12 18:22:42.709   873  3908 E DropBoxManagerService: Can't write: system_app_crash
08-12 18:22:42.709   873  3908 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
08-12 18:22:42.709   873  3908 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 18:22:42.709   873  3908 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 18:22:42.709   873  3908 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 18:22:42.709   873  3908 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 18:22:42.709   873  3908 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 18:22:42.709   873  3908 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 18:22:42.709   873  3908 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 18:22:42.709   873  3908 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 18:22:42.709   873  3908 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 18:22:42.709   873  3908 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 18:22:42.709   873  3908 E DropBoxManagerService: 	... 5 more
,08-12 18:22:42.717  3493  3508 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj9560CA90E) - 
,08-12 18:22:42.718   873  3909 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-12 18:22:42.728  3493  3904 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-12 18:22:42.732  3493  3508 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
08-12 18:22:42.732  3493  3508 E AndroidRuntime: Process: android.process.acore, PID: 3493
08-12 18:22:42.732  3493  3508 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
08-12 18:22:42.732  3493  3508 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-12 18:22:42.732  3493  3508 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-12 18:22:42.732  3493  3508 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
08-12 18:22:42.732  3493  3508 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
08-12 18:22:42.732  3493  3508 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
08-12 18:22:42.732  3493  3508 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
08-12 18:22:42.732  3493  3508 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
08-12 18:22:42.732  3493  3508 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
08-12 18:22:42.732  3493  3508 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-12 18:22:42.732  3493  3508 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 18:22:42.732  3493  3508 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 18:22:42.732  3493  3508 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-12 18:22:42.737   873  3912 E DropBoxManagerService: Can't write: system_app_crash
08-12 18:22:42.737   873  3912 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop114.tmp: open failed: EROFS (Read-only file system)
08-12 18:22:42.737   873  3912 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 18:22:42.737   873  3912 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 18:22:42.737   873  3912 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 18:22:42.737   873  3912 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 18:22:42.737   873  3912 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 18:22:42.737   873  3912 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 18:22:42.737   873  3912 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 18:22:42.737   873  3912 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 18:22:42.737   873  3912 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 18:22:42.737   873  3912 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 18:22:42.737   873  3912 E DropBoxManagerService: 	... 5 more
,08-12 18:22:42.742  1861  3902 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-12 18:22:42.744  1861  3902 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-12 18:22:42.744  1861  3902 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-12 18:22:42.747  1861  3902 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-12 18:22:42.747  1861  3902 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-12 18:22:42.747  1861  3902 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-12 18:22:42.747  1861  3902 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-12 18:22:42.748  1861  3902 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-12 18:22:42.748  1861  3902 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-12 18:22:42.748  1861  3902 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-12 18:22:42.748  1861  3902 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-12 18:22:42.748  1861  3902 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-12 18:22:42.748  1861  3902 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-12 18:22:42.752  3493  3904 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,08-12 18:22:42.753  3493  3904 I Process : Sending signal. PID: 3493 SIG: 9
,08-12 18:22:42.759  1944  2032 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-12 18:22:42.759   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-12 18:22:42.760   873   885 E PackageManager: Failed to write settings, restoring backup
08-12 18:22:42.760   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-12 18:22:42.760   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-12 18:22:42.760   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-12 18:22:42.760   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-12 18:22:42.760   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-12 18:22:42.760   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 18:22:42.760   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-12 18:22:42.760   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-12 18:22:42.761   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-12 18:22:42.761   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-12 18:22:42.761   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 18:22:42.761   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 18:22:42.761   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 18:22:42.761   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 18:22:42.761   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 18:22:42.761   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 18:22:42.761   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-12 18:22:42.761   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-12 18:22:42.761   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-12 18:22:42.761   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 18:22:42.761   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 18:22:42.761   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-12 18:22:42.761   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 18:22:42.761   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-12 18:22:42.761   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 18:22:42.761   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 18:22:42.761   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 18:22:42.761   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 18:22:42.761   873   886 E DropBoxManagerService: 	... 13 more
,08-12 18:22:42.770   873  3909 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-12 18:22:42.770   873  3909 I Adreno  : Build Date                       : 10/20/15
08-12 18:22:42.770   873  3909 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-12 18:22:42.770   873  3909 I Adreno  : Local Branch                     : M14
08-12 18:22:42.770   873  3909 I Adreno  : Remote Branch                    : 
08-12 18:22:42.770   873  3909 I Adreno  : Remote Branch                    : 
08-12 18:22:42.770   873  3909 I Adreno  : Reconstruct Branch               : 
,08-12 18:22:42.777   873  2242 I ActivityManager: Start proc 3913:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,08-12 18:22:42.777  1944  2032 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-12 18:22:42.777  1944  2032 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1944
08-12 18:22:42.777  1944  2032 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 18:22:42.777  1944  2032 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-12 18:22:42.777  1944  2032 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-12 18:22:42.777  1944  2032 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-12 18:22:42.777  1944  2032 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-12 18:22:42.777  1944  2032 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-12 18:22:42.777  1944  2032 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-12 18:22:42.777  1944  2032 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-12 18:22:42.777  1944  2032 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 18:22:42.777  1944  2032 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 18:22:42.777  1944  2032 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 18:22:42.777  1944  2032 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 18:22:42.779   873  1936 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-12 18:22:42.781   873  3909 I OpenGLRenderer: Initialized EGL, version 1.4
08-12 18:22:42.782  1989  2002 W SearchService: Abort, client detached.
08-12 18:22:42.785  1989  1989 I HotwordDetector: Closing mic
08-12 18:22:42.786  1989  2341 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@a811b4a
08-12 18:22:42.786  1989  3896 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-12 18:22:42.790   278   278 E lowmemorykiller: Error writing /proc/3493/oom_score_adj; errno=22
08-12 18:22:42.790   873  3918 E DropBoxManagerService: Can't write: system_app_crash
08-12 18:22:42.790   873  3918 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop116.tmp: open failed: EROFS (Read-only file system)
08-12 18:22:42.790   873  3918 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 18:22:42.790   873  3918 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 18:22:42.790   873  3918 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 18:22:42.790   873  3918 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 18:22:42.790   873  3918 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 18:22:42.790   873  3918 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 18:22:42.790   873  3918 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 18:22:42.790   873  3918 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 18:22:42.790   873  3918 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 18:22:42.790   873  3918 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 18:22:42.790   873  3918 E DropBoxManagerService: 	... 5 more
,08-12 18:22:42.836   873   883 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-12 18:22:42.840   278   278 E lowmemorykiller: Error writing /proc/3493/oom_score_adj; errno=22
08-12 18:22:42.844  1944  1944 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@73c6b4c new=com.google.android.velvet.VelvetApplication@73c6b4c
08-12 18:22:42.850   377  3898 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-12 18:22:42.850   377  3898 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
,08-12 18:22:42.855   377  1285 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-12 18:22:42.860  1989  2348 I MicroRecognitionRnrImpl: Stopping hotword detection.
,08-12 18:22:42.861  1989  3895 I MicroRecognitionRnrImpl: Detection finished
08-12 18:22:42.878  1989  3926 E Search.SharedPreferencesProto: Failed to rename to backup file /data/user/0/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,08-12 18:22:42.904  1944  1944 I GEL     : handleIntent(Intent { act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL })
,08-12 18:22:42.916  1725  3934 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-12 18:22:42.918  1725  3934 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-12 18:22:42.948   873  2079 I ActivityManager: Process android.process.acore (pid 3493) has died
,08-12 18:22:42.949   873  2079 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,08-12 18:22:42.993   873   891 I ActivityManager: Displayed com.google.android.googlequicksearchbox/com.google.android.launcher.GEL: +155ms
,08-12 18:22:43.088   280   280 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
08-12 18:22:43.088   280   280 E qdoverlay: src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
08-12 18:22:43.088   280   280 E qdoverlay: src_rect mdp_rect x=0 y=0 w=720 h=2560
,08-12 18:22:43.088   280   280 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=720 h=2560
08-12 18:22:43.088   280   280 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
08-12 18:22:43.088   280   280 E qdoverlay: MdpCtrl close error in unset

```
