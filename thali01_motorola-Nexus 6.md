#### Test 84618637d5e9757_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-09 11:41:48.925  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:41:48.937  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-09 11:41:48.942  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-09 11:41:48.987  1524  2122 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-09 11:41:48.987  1524  2122 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-09 11:41:48.988  1524  2122 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 11:41:48.988  1524  2122 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-09 11:41:49.030  3521  3521 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-09 11:41:49.030  3521  3521 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-09 11:41:49.032  3521  3521 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
09-09 11:41:49.587  3817  3817 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-09 11:41:49.592  3817  3817 D AndroidRuntime: CheckJNI is OFF
09-09 11:41:49.636  3817  3817 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-09 11:41:49.688  3817  3817 I Radio-JNI: register_android_hardware_Radio DONE
09-09 11:41:49.712  3817  3817 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-09 11:41:49.717   874  1977 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-09 11:41:49.762  1999  2012 W SearchService: Abort, client detached.
09-09 11:41:49.763  3817  3817 D AndroidRuntime: Shutting down VM
09-09 11:41:49.772  1999  2342 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@cd183ac
09-09 11:41:49.772  1999  2352 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-09 11:41:49.772  1999  1999 I HotwordDetector: Closing mic
09-09 11:41:49.782   874  3188 I ActivityManager: Start proc 3826:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-09 11:41:49.827   376  2356 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-09 11:41:49.828   376  2356 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-09 11:41:49.837   376  1279 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-09 11:41:49.840  1999  2351 I MicroRecognitionRnrImpl: Detection finished
09-09 11:41:49.840  1999  2346 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-09 11:41:49.865  3826  3826 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-09 11:41:49.891  3826  3826 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-09 11:41:49.897  3826  3826 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 1880-1882)
09-09 11:41:49.897  3826  3826 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 11:41:49.913  3826  3826 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8524868}
09-09 11:41:49.914  3826  3826 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 11:41:49.914  3826  3826 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-09 11:41:49.920  3826  3826 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-09 11:41:49.922  3826  3826 E SysUtils: ApplicationContext is null in ApplicationStatus
09-09 11:41:49.938  3826  3826 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-09 11:41:49.948  3826  3826 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 11:41:49.948  3826  3826 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 11:41:49.948  3826  3826 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 11:41:49.948  3826  3826 I Adreno  : Build Date                       : 10/20/15
09-09 11:41:49.948  3826  3826 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 11:41:49.948  3826  3826 I Adreno  : Local Branch                     : M14
09-09 11:41:49.948  3826  3826 I Adreno  : Remote Branch                    : 
09-09 11:41:49.948  3826  3826 I Adreno  : Remote Branch                    : 
09-09 11:41:49.948  3826  3826 I Adreno  : Reconstruct Branch               : 
,09-09 11:41:50.003   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@15fd414:true
,09-09 11:41:50.035  3826  3826 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-09 11:41:50.050  3826  3826 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-09 11:41:50.106  3826  3865 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-09 11:41:50.115  3826  3851 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-09 11:41:50.149  3826  3865 I OpenGLRenderer: Initialized EGL, version 1.4
,09-09 11:41:50.230   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +462ms
,09-09 11:41:50.251  1861  1861 I Keyboard.Facilitator: onFinishInput()
,09-09 11:41:50.289  3826  3826 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3826
,09-09 11:41:50.392  3826  3826 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-09 11:41:50.536  3826  3868 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1684014800
,09-09 11:41:50.541  3826  3868 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-09 11:41:50.541  3826  3868 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-09 11:41:50.541  3826  3868 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-09 11:41:50.541  3826  3868 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-09 11:41:50.541  3826  3868 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-09 11:41:50.541  3826  3868 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce1121f added. We now have 1 listener(s)
09-09 11:41:50.544  3826  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-09 11:41:50.545  3826  3868 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 11:41:50.545  3826  3868 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 11:41:50.545  3826  3868 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 11:41:50.549  3826  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-09 11:41:50.549  3826  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-09 11:41:50.549  3826  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-09 11:41:50.549  3826  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-09 11:41:50.549  3826  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-09 11:41:50.549  3826  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-09 11:41:50.549  3826  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-09 11:41:50.549  3826  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-09 11:41:50.549  3826  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-09 11:41:50.549  3826  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-09 11:41:50.549  3826  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-09 11:41:50.549  3826  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-09 11:41:50.549  3826  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-09 11:41:50.549  3826  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-09 11:41:50.549  3826  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@497bbca added. We now have 1 listener(s)
09-09 11:41:50.549  3826  3868 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 11:41:50.552   874  1308 D WifiService: New client listening to asynchronous messages
,09-09 11:41:50.553  3826  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 11:41:50.553  3826  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-09 11:41:50.553  3826  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-09 11:41:50.553  3826  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3,
,09-09 11:41:50.553  3826  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-09 11:41:50.567  3826  3868 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 11:41:50.567  3826  3868 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-09 11:41:50.573  3826  3868 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-09 11:41:50.573  3826  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 11:41:50.573  3826  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:41:50.573  3826  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:41:50.573  3826  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 11:41:50.573  3826  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 11:41:50.573  3826  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 11:41:50.573  3826  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 11:41:50.573  3826  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 11:41:50.573  3826  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-09 11:41:50.573  3826  3868 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 11:41:50.575  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 11:41:50.578  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 11:41:50.578  3826  3868 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-09 11:41:50.604  3826  3826 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-09 11:41:50.611   874  1383 I ActivityManager: Killing 3243:com.google.android.gm/u0a78 (adj 15): empty #17
,09-09 11:41:50.653   874  1383 I ActivityManager: Killing 3143:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,09-09 11:41:50.868   874  1307 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-09 11:41:51.426  3826  3876 W jxcore-log: Initializing JXcore engine
,09-09 11:41:51.427  3826  3876 W jxcore-log: JXcore engine is ready
,09-09 11:41:51.463  3876  3876 W Thread-325: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8988 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-09 11:41:51.463  3876  3876 W Thread-325: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[10875]" dev="sockfs" ino=10875 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-09 11:41:51.463  3876  3876 W Thread-325: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-09 11:41:51.463  3876  3876 W Thread-325: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[25381]" dev="sockfs" ino=25381 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-09 11:41:51.478  3826  3876 W jxcore-log: Starting JXcore engine
,09-09 11:41:51.561  3826  3876 W jxcore-log: Platform android
09-09 11:41:51.561  3826  3876 W jxcore-log: 
,09-09 11:41:51.562  3826  3876 W jxcore-log: Process ARCH arm
09-09 11:41:51.562  3826  3876 W jxcore-log: 
,09-09 11:41:51.761  3826  3876 I jxcore-log: JXcore Cordova bridge is ready!
09-09 11:41:51.761  3826  3876 I jxcore-log: 
,09-09 11:41:51.762  3826  3876 W jxcore-log: JXcore engine is started
09-09 11:41:51.766  3826  3868 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-09 11:41:51.771  3826  3826 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-09 11:41:55.535  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:41:55.539  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:41:55.594  1524  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 11:41:55.594  1524  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-09 11:41:55.595  1524  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 11:41:55.595  1524  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:41:55.638  3562  3883 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 11:41:55.638  3562  3883 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 11:41:55.638  3562  3883 E HttpOperation: 	at jdm.a(PG:82)
09-09 11:41:55.638  3562  3883 E HttpOperation: 	at jcs.o(PG:406)
09-09 11:41:55.638  3562  3883 E HttpOperation: 	at jcn.a(PG:1379)
09-09 11:41:55.638  3562  3883 E HttpOperation: 	at jcs.i(PG:143)
09-09 11:41:55.638  3562  3883 E HttpOperation: 	at blb.a(PG:3937)
09-09 11:41:55.638  3562  3883 E HttpOperation: 	at czp.a(PG:18188)
09-09 11:41:55.638  3562  3883 E HttpOperation: 	at czp.a(PG:9081)
09-09 11:41:55.638  3562  3883 E HttpOperation: 	at czq.run(PG:1686)
09-09 11:41:55.638  3562  3883 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 11:41:55.638  3562  3883 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 11:41:55.638  3562  3883 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 11:41:55.638  3562  3883 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 11:41:55.638  3562  3883 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 11:41:55.638  3562  3883 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 11:41:55.638  3562  3883 E HttpOperation: 	at jdj.a(PG:4091)
09-09 11:41:55.638  3562  3883 E HttpOperation: 	at jdj.a(PG:1125)
09-09 11:41:55.638  3562  3883 E HttpOperation: 	at jdm.a(PG:77)
09-09 11:41:55.638  3562  3883 E HttpOperation: 	... 12 more
09-09 11:41:55.638  3562  3883 E HttpOperation: Caused by: faj: BadAuthentication
09-09 11:41:55.638  3562  3883 E HttpOperation: 	at fal.a(PG:38)
09-09 11:41:55.638  3562  3883 E HttpOperation: 	at jdj.a(PG:4089)
09-09 11:41:55.638  3562  3883 E HttpOperation: 	... 14 more
,09-09 11:41:55.717  1524  2892 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 11:41:55.717  1524  2892 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 11:41:55.717  1524  2892 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 11:41:55.717  1524  2892 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:41:55.731  3562  3883 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 11:41:55.731  3562  3883 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 11:41:55.731  3562  3883 E HttpOperation: 	at jdm.a(PG:82)
09-09 11:41:55.731  3562  3883 E HttpOperation: 	at jcs.o(PG:406)
09-09 11:41:55.731  3562  3883 E HttpOperation: 	at jcn.a(PG:1379)
09-09 11:41:55.731  3562  3883 E HttpOperation: 	at jcs.i(PG:143)
09-09 11:41:55.731  3562  3883 E HttpOperation: 	at hec.a(PG:42)
09-09 11:41:55.731  3562  3883 E HttpOperation: 	at hee.a(PG:102)
09-09 11:41:55.731  3562  3883 E HttpOperation: 	at czr.a(PG:65)
09-09 11:41:55.731  3562  3883 E HttpOperation: 	at kka.a(PG:108)
09-09 11:41:55.731  3562  3883 E HttpOperation: 	at czp.a(PG:19176)
09-09 11:41:55.731  3562  3883 E HttpOperation: 	at czp.a(PG:9081)
09-09 11:41:55.731  3562  3883 E HttpOperation: 	at czq.run(PG:1686)
09-09 11:41:55.731  3562  3883 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 11:41:55.731  3562  3883 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 11:41:55.731  3562  3883 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 11:41:55.731  3562  3883 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 11:41:55.731  3562  3883 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 11:41:55.731  3562  3883 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 11:41:55.731  3562  3883 E HttpOperation: 	at jdj.a(PG:4091)
09-09 11:41:55.731  3562  3883 E HttpOperation: 	at jdj.a(PG:1125)
09-09 11:41:55.731  3562  3883 E HttpOperation: 	at jdm.a(PG:77)
09-09 11:41:55.731  3562  3883 E HttpOperation: 	... 15 more
09-09 11:41:55.731  3562  3883 E HttpOperation: Caused by: faj: BadAuthentication
09-09 11:41:55.731  3562  3883 E HttpOperation: 	at fal.a(PG:38)
09-09 11:41:55.731  3562  3883 E HttpOperation: 	at jdj.a(PG:4089)
09-09 11:41:55.731  3562  3883 E HttpOperation: 	... 17 more
,09-09 11:41:55.731  3562  3883 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 11:41:55.731  3562  3883 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 11:41:55.731  3562  3883 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 11:41:55.731  3562  3883 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 11:41:55.731  3562  3883 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 11:41:55.731  3562  3883 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 11:41:55.731  3562  3883 E ExperimentLoader: 	at hec.a(PG:42)
09-09 11:41:55.731  3562  3883 E ExperimentLoader: 	at hee.a(PG:102)
09-09 11:41:55.731  3562  3883 E ExperimentLoader: 	at czr.a(PG:65)
09-09 11:41:55.731  3562  3883 E ExperimentLoader: 	at kka.a(PG:108)
09-09 11:41:55.731  3562  3883 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 11:41:55.731  3562  3883 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 11:41:55.731  3562  3883 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 11:41:55.731  3562  3883 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 11:41:55.731  3562  3883 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 11:41:55.731  3562  3883 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 11:41:55.731  3562  3883 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 11:41:55.731  3562  3883 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 11:41:55.731  3562  3883 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 11:41:55.731  3562  3883 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 11:41:55.731  3562  3883 E ExperimentLoader: 	at jdj.a(PG:1125)
09-09 11:41:55.731  3562  3883 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 11:41:55.731  3562  3883 E ExperimentLoader: 	... 15 more
09-09 11:41:55.731  3562  3883 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 11:41:55.731  3562  3883 E ExperimentLoader: 	at fal.a(PG:38)
09-09 11:41:55.731  3562  3883 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 11:41:55.731  3562  3883 E ExperimentLoader: 	... 17 more
,09-09 11:41:55.808   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 127300, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-09 11:42:05.567  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-09 11:42:05.567  3826  3876 I jxcore-log: 
09-09 11:42:05.570  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-09 11:42:05.570  3826  3876 I jxcore-log: 
,09-09 11:42:05.579  3826  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 11:42:05.579  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:42:05.579  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:42:05.579  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 11:42:05.579  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 11:42:05.579  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 11:42:05.579  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 11:42:05.579  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 11:42:05.587  3826  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 11:42:05.593   874  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-09 11:42:05.597  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-09 11:42:05.597  3826  3876 I jxcore-log: 
,09-09 11:42:05.610  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-09 11:42:05.610  3826  3876 I jxcore-log: 
,09-09 11:42:05.962  3826  3876 I jxcore-log: Running unit tests
09-09 11:42:05.962  3826  3876 I jxcore-log: 
,09-09 11:42:05.963  3826  3876 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 11:42:05.963  3826  3876 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9f641ec added. We now have 2 listener(s)
,09-09 11:42:05.965  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 11:42:05.966  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 11:42:05.966  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 11:42:05.966  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 11:42:05.966  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e7829b5 added. We now have 2 listener(s)
,09-09 11:42:05.966  3826  3876 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 11:42:05.968  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 11:42:05.973  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 11:42:05.985  3826  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 11:42:05.985  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:42:05.985  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:42:05.985  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 11:42:05.985  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 11:42:05.985  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 11:42:05.985  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 11:42:05.985  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 11:42:05.992  3826  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 11:42:05.993  3826  3876 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 11:42:05.994  3826  3876 D executeNativeTests: Running unit tests
,09-09 11:42:05.997  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 11:42:06.000  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 11:42:06.082  3826  3876 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 11:42:06.082  3826  3876 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1f61ab added. We now have 3 listener(s)
,09-09 11:42:06.083  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 11:42:06.083  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 11:42:06.083  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 11:42:06.083  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 11:42:06.084  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 added. We now have 3 listener(s)
09-09 11:42:06.084  3826  3876 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 11:42:06.084  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 11:42:06.087  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 11:42:06.091  3826  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 11:42:06.091  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:42:06.091  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:42:06.091  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 11:42:06.091  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 11:42:06.091  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 11:42:06.091  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 11:42:06.091  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 11:42:06.093  3826  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 11:42:06.093  3826  3876 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 11:42:06.096  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-09 11:42:06.097  3826  3876 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 11:42:06.098  3826  3876 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 11:42:06.098  3826  3876 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 11:42:06.100  3826  3876 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-09 11:42:06.100  3826  3876 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 11:42:06.100  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 11:42:06.100  3826  3876 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-09 11:42:06.100  3826  3876 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1,
09-09 11:42:06.100  3826  3876 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-09 11:42:06.101  3826  3876 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 11:42:06.101  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 11:42:06.101  3826  3876 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 11:42:06.104  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 11:42:06.105  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 11:42:06.105  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 11:42:06.105  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 11:42:06.101  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 11:42:06.105  3826  3876 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1f61ab removed from the list
09-09 11:42:06.105  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:42:06.105  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 removed from the list
09-09 11:42:06.110  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 11:42:06.110  3826  3876 D io.jxcore.node.ConnectivityMonitor: stop
09-09 11:42:06.110  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:06.111  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:06.111  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:06.112  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 11:42:06.112  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 11:42:06.112  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 11:42:06.112  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
09-09 11:42:06.113  3826  3876 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-09 11:42:06.114  3826  3876 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 11:42:06.114  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 11:42:06.114  3826  3876 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 11:42:06.114  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 11:42:06.114  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 11:42:06.114  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:06.114  3826  3876 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1f61ab not in the list
09-09 11:42:06.114  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:42:06.114  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
09-09 11:42:06.114  3826  3876 D io.jxcore.node.ConnectivityMonitor: stop
09-09 11:42:06.114  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:06.114  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:06.114  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:06.114  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 11:42:06.115  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 11:42:06.115  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 11:42:06.115  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:42:06.115  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
,09-09 11:42:06.121  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-09 11:42:06.121  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 11:42:06.121  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 11:42:06.121  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 11:42:06.121  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 11:42:06.121  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 11:42:06.122  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 11:42:06.122  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 11:42:06.122  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-09 11:42:06.122  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 11:42:06.122  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 11:42:06.122  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 11:42:06.122  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 11:42:06.122  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 11:42:06.122  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-09 11:42:06.122  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 11:42:06.122  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 11:42:06.122  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 11:42:06.122  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 11:42:06.122  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 11:42:06.122  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 11:42:06.122  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 11:42:06.123  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-09 11:42:06.123  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 11:42:06.123  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 11:42:06.123  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 11:42:06.123  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 11:42:06.123  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 11:42:06.123  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 11:42:06.123  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 11:42:06.123  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-09 11:42:06.123  3826  3876 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 11:42:06.123  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 11:42:06.124  3826  3876 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 11:42:06.124  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 11:42:06.124  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:06.124  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:06.124  3826  3876 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1f61ab not in the list
09-09 11:42:06.124  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:42:06.124  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
09-09 11:42:06.124  3826  3876 D io.jxcore.node.ConnectivityMonitor: stop
09-09 11:42:06.124  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:06.124  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:06.124  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:06.124  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:06.125  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 11:42:06.125  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 11:42:06.125  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:42:06.125  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
09-09 11:42:06.126  3826  3876 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 11:42:06.127  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 11:42:06.136  3826  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 11:42:06.136  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:42:06.136  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:42:06.136  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 11:42:06.136  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 11:42:06.136  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 11:42:06.136  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 11:42:06.136  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 11:42:06.140  3826  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 11:42:06.141  3826  3876 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 11:42:06.142  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 11:42:06.142  3826  3876 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 11:42:06.142  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 11:42:06.143  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 11:42:06.143  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 11:42:06.144  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 11:42:06.146  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 11:42:06.151  3826  3876 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 11:42:06.151  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 11:42:06.164  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 11:42:06.166  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 11:42:06.166  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 11:42:06.171  3826  3876 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-09 11:42:06.176  3826  3876 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-09 11:42:06.177  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-09 11:42:06.177  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 11:42:06.179  3826  3876 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 11:42:06.187  3826  3876 D BluetoothAdapter: STATE_ON
09-09 11:42:06.193  2659  2670 D BtGatt.GattService: registerClient() - UUID=efbec4c7-c5e7-42d3-afea-d1d0fa76b492
09-09 11:42:06.195  2659  2680 D BtGatt.GattService: onClientRegistered() - UUID=efbec4c7-c5e7-42d3-afea-d1d0fa76b492, clientIf=5
09-09 11:42:06.195  3826  3837 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-09 11:42:06.196  2659  3484 D BtGatt.GattService: start scan with filters
,09-09 11:42:06.199  2659  2699 D BtGatt.ScanManager: handling starting scan
,09-09 11:42:06.201  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 11:42:06.201  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-09 11:42:06.201  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-09 11:42:06.202  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 11:42:06.202  2659  2699 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@222e1b2
,09-09 11:42:06.205  3826  3876 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 11:42:06.206  3826  3876 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 11:42:06.206  3826  3826 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 11:42:06.207  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 11:42:06.211  3826  3876 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 11:42:06.212  2659  2680 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-09 11:42:06.212  2659  2680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 11:42:06.212  2659  2699 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 11:42:06.227  2659  2680 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-09 11:42:06.227  2659  2680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 11:42:06.227  2659  2699 D BtGatt.ScanManager: Starting BLE batch scan
09-09 11:42:06.227  2659  2699 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-09 11:42:06.238  2659  2680 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-09 11:42:06.238  2659  2680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 11:42:06.244  2659  2680 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-09 11:42:06.244  2659  2680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 11:42:06.708  3826  3826 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
09-09 11:42:06.708  3826  3826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 11:42:06.709  3826  3826 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 11:42:07.751  2659  2659 D BtGatt.ScanManager: awakened up at time 139737
,09-09 11:42:07.754  2659  2699 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 11:42:07.780  2659  2680 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-09 11:42:07.780  2659  2680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 11:42:07.781  2659  2680 D BtGatt.GattService: current time is 139766568931
,09-09 11:42:07.782  2659  2680 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -82, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -95, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -83, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -83, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -79, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -79, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-09 11:42:07.786  2659  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-09 11:42:07.788  2659  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-09 11:42:07.789  2659  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-09 11:42:07.790  2659  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-09 11:42:07.790  2659  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-09 11:42:07.791  2659  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-09 11:42:08.630   874  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-09 11:42:09.287  2659  2659 D BtGatt.ScanManager: awakened up at time 141272
,09-09 11:42:09.290  2659  2699 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 11:42:09.382  2659  2680 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,09-09 11:42:09.382  2659  2680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 11:42:09.383  2659  2680 D BtGatt.GattService: current time is 141368813570
,09-09 11:42:09.384  2659  2680 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -85, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -86, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -78, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -82, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-09 11:42:09.385  2659  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-09 11:42:09.385  2659  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-09 11:42:09.386  2659  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-09 11:42:09.387  2659  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-09 11:42:09.621  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:42:09.655  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:42:09.661  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:42:09.731  1524  2122 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-09 11:42:09.731  1524  2122 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-09 11:42:09.731  1524  2122 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 11:42:09.732  1524  2122 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:42:09.756  3521  3521 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-09 11:42:09.756  3521  3521 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-09 11:42:09.757  3521  3521 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-09 11:42:10.884  2659  2659 D BtGatt.ScanManager: awakened up at time 142870
,09-09 11:42:10.887  2659  2699 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 11:42:10.895  2659  2680 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-09 11:42:10.895  2659  2680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 11:42:11.221  3826  3876 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 11:42:11.222  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 11:42:11.222  3826  3876 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-09 11:42:11.223  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:11.223  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 11:42:11.225  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-09 11:42:11.225  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-09 11:42:11.226  3826  3876 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 11:42:11.226  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 11:42:11.230  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 11:42:11.231  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 11:42:11.234  3826  3876 D BluetoothAdapter: STATE_ON
,09-09 11:42:11.236  2659  2670 D BtGatt.GattService: stopScan() - queue size =1
,09-09 11:42:11.239  2659  3890 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 11:42:11.240  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 11:42:11.241  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 11:42:11.241  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-09 11:42:11.242  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-09 11:42:11.242  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 11:42:11.245  3826  3876 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 11:42:11.246  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 11:42:11.247  3826  3876 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 11:42:11.248  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 11:42:11.249  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 11:42:11.252  3826  3826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 11:42:11.252  3826  3826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 11:42:11.252  3826  3826 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 11:42:11.252  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 11:42:11.253  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:11.253  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 11:42:11.253  3826  3876 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1f61ab not in the list
09-09 11:42:11.253  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:42:11.253  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
,09-09 11:42:11.253  3826  3876 D io.jxcore.node.ConnectivityMonitor: stop
09-09 11:42:11.253  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:11.254  2659  2680 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 11:42:11.255  2659  2680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 11:42:11.255  2659  2699 D BtGatt.ScanManager: stopping BLe Batch
,09-09 11:42:11.262  2659  2680 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-09 11:42:11.262  2659  2680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 11:42:11.263  2659  2699 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 11:42:11.270  2659  2680 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-09 11:42:11.270  2659  2680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 11:42:11.649   874  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-09 11:42:11.753  3826  3826 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 11:42:14.679   874  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-09 11:42:16.254  3826  3876 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-09 11:42:16.260  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 11:42:16.275  3826  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 11:42:16.275  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:42:16.275  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:42:16.275  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 11:42:16.275  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 11:42:16.275  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 11:42:16.275  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 11:42:16.275  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 11:42:16.284  3826  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 11:42:16.284  3826  3876 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 11:42:16.286  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 11:42:16.287  3826  3876 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-09 11:42:16.288  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-09 11:42:16.288  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
09-09 11:42:16.289  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 11:42:16.293  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 11:42:16.300  3826  3876 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 11:42:16.300  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 11:42:16.302  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 11:42:16.311  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 11:42:16.313  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 11:42:16.313  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 11:42:16.323  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 11:42:16.323  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-09 11:42:16.323  3826  3876 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 11:42:16.325  3826  3876 D BluetoothAdapter: STATE_ON
,09-09 11:42:16.331  2659  2669 D BtGatt.GattService: registerClient() - UUID=af54019f-f114-415d-a348-7c8713b51bf7
,09-09 11:42:16.332  2659  2680 D BtGatt.GattService: onClientRegistered() - UUID=af54019f-f114-415d-a348-7c8713b51bf7, clientIf=5
09-09 11:42:16.333  3826  3838 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-09 11:42:16.335  2659  2782 D BtGatt.GattService: start scan with filters
,09-09 11:42:16.343  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 11:42:16.343  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 11:42:16.343  2659  2699 D BtGatt.ScanManager: handling starting scan
09-09 11:42:16.344  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-09 11:42:16.344  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 11:42:16.353  2659  2680 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-09 11:42:16.353  2659  2680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 11:42:16.353  3826  3876 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 11:42:16.354  3826  3876 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 11:42:16.354  2659  2699 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-09 11:42:16.354  3826  3826 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 11:42:16.359  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 11:42:16.368  3826  3876 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 11:42:16.374  2659  2680 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 11:42:16.374  2659  2680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 11:42:16.375  2659  2699 D BtGatt.ScanManager: Starting BLE batch scan
,09-09 11:42:16.375  3826  3876 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 11:42:16.375  2659  2699 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-09 11:42:16.375  3826  3876 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 11:42:16.375  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 11:42:16.375  3826  3876 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 11:42:16.375  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:16.376  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 11:42:16.376  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 11:42:16.376  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 11:42:16.376  3826  3876 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-09 11:42:16.376  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 11:42:16.376  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 11:42:16.376  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 11:42:16.377  3826  3876 D BluetoothAdapter: STATE_ON
,09-09 11:42:16.378  2659  3890 D BtGatt.GattService: stopScan() - queue size =1
09-09 11:42:16.379  2659  2669 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 11:42:16.380  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 11:42:16.380  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 11:42:16.380  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 11:42:16.381  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 11:42:16.381  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 11:42:16.384  3826  3876 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 11:42:16.385  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 11:42:16.385  3826  3876 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 11:42:16.386  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 11:42:16.388  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 11:42:16.391  3826  3826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 11:42:16.391  3826  3826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 11:42:16.391  3826  3826 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 11:42:16.391  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 11:42:16.391  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:16.391  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 11:42:16.392  3826  3876 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1f61ab not in the list
09-09 11:42:16.392  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:42:16.392  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
09-09 11:42:16.392  3826  3876 D io.jxcore.node.ConnectivityMonitor: stop
09-09 11:42:16.392  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:16.392  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:16.392  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:16.393  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 11:42:16.394  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 11:42:16.394  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:42:16.394  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
09-09 11:42:16.395  3826  3876 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-09 11:42:16.397  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 11:42:16.403  2659  2680 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-09 11:42:16.403  2659  2680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 11:42:16.404  3826  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 11:42:16.404  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:42:16.404  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:42:16.404  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 11:42:16.404  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 11:42:16.404  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 11:42:16.404  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 11:42:16.404  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 11:42:16.408  3826  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 11:42:16.408  3826  3876 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 11:42:16.409  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 11:42:16.409  3826  3876 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-09 11:42:16.410  2659  2680 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-09 11:42:16.410  2659  2680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 11:42:16.409  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 11:42:16.410  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 11:42:16.410  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 11:42:16.413  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 11:42:16.415  3826  3876 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 11:42:16.415  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 11:42:16.418  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 11:42:16.420  2659  2680 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-09 11:42:16.420  2659  2680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 11:42:16.420  2659  2699 D BtGatt.ScanManager: stopping BLe Batch
09-09 11:42:16.422  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 11:42:16.423  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 11:42:16.423  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 11:42:16.428  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 11:42:16.428  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 11:42:16.428  3826  3876 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 11:42:16.429  3826  3876 D BluetoothAdapter: STATE_ON
,09-09 11:42:16.429  2659  2680 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 11:42:16.429  2659  2680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 11:42:16.430  2659  2699 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 11:42:16.432  2659  3890 D BtGatt.GattService: registerClient() - UUID=b2509514-c028-423a-8738-8572d0c785a0
,09-09 11:42:16.433  2659  2680 D BtGatt.GattService: onClientRegistered() - UUID=b2509514-c028-423a-8738-8572d0c785a0, clientIf=5
,09-09 11:42:16.434  3826  3837 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-09 11:42:16.436  2659  2782 D BtGatt.GattService: start scan with filters
,09-09 11:42:16.436  2659  2680 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 11:42:16.436  2659  2680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 11:42:16.439  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 11:42:16.439  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 11:42:16.439  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 11:42:16.439  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 11:42:16.440  2659  2699 D BtGatt.ScanManager: handling starting scan
,09-09 11:42:16.443  3826  3876 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 11:42:16.443  3826  3826 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 11:42:16.444  3826  3876 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 11:42:16.446  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-09 11:42:16.448  3826  3876 I io.jxcore.node.ConnectionHelper: start: OK
09-09 11:42:16.452  2659  2680 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-09 11:42:16.452  2659  2680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 11:42:16.452  2659  2699 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 11:42:16.462  2659  2680 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-09 11:42:16.462  2659  2680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 11:42:16.462  2659  2699 D BtGatt.ScanManager: Starting BLE batch scan
09-09 11:42:16.463  2659  2699 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-09 11:42:16.474  2659  2680 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 11:42:16.474  2659  2680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 11:42:16.480  2659  2680 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-09 11:42:16.481  2659  2680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 11:42:16.944  3826  3826 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-09 11:42:16.945  3826  3826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 11:42:16.945  3826  3826 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 11:42:17.987  2659  2659 D BtGatt.ScanManager: awakened up at time 149972
09-09 11:42:17.989  2659  2699 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 11:42:18.057  2659  2680 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=8
09-09 11:42:18.057  2659  2680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 11:42:18.058  2659  2680 D BtGatt.GattService: current time is 150043876830
,09-09 11:42:18.059  2659  2680 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -82, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -80, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -80, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -82, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -100, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -85, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -79, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -80, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-09 11:42:18.061  2659  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-09 11:42:18.063  2659  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-09 11:42:18.065  2659  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-09 11:42:18.069  2659  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-09 11:42:18.071  2659  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,09-09 11:42:18.073  2659  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-09 11:42:18.076  2659  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-09 11:42:18.078  2659  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-09 11:42:18.338   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-09 11:42:18.357  1861  1861 I Keyboard.Facilitator: onFinishInput()
,09-09 11:42:18.365   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 11:42:18.365   874   894 I Adreno  : Build Date                       : 10/20/15
09-09 11:42:18.365   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 11:42:18.365   874   894 I Adreno  : Local Branch                     : M14
09-09 11:42:18.365   874   894 I Adreno  : Remote Branch                    : 
09-09 11:42:18.365   874   894 I Adreno  : Remote Branch                    : 
09-09 11:42:18.365   874   894 I Adreno  : Reconstruct Branch               : 
,09-09 11:42:18.400   281   300 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (270 us)
,09-09 11:42:19.068  3826  3826 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-09 11:42:19.069  3826  3826 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-09 11:42:19.105  3826  3826 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@ed966fe Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@780a695, 16908290=android.view.AbsSavedState$1@780a695}, android:focusedViewId=100}]}]
,09-09 11:42:19.105   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-09 11:42:19.105  3826  3826 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-09 11:42:19.105  3826  3826 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-09 11:42:19.105  3826  3826 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-09 11:42:19.114   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-09 11:42:19.117   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-09 11:42:19.117   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
09-09 11:42:19.117   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-09 11:42:19.354   281   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-09 11:42:19.359   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-09 11:42:19.360   874  1332 D SurfaceControl: Excessive delay in setPowerMode(): 243ms
,09-09 11:42:19.368   874   894 I DreamManagerService: Entering dreamland.
,09-09 11:42:19.369   874   894 I PowerManagerService: Dozing...
09-09 11:42:19.370   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-09 11:42:19.443   376  1472 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-09 11:42:19.443   376  1472 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-09 11:42:19.453  2659  2659 D BtGatt.ScanManager: awakened up at time 151438
,09-09 11:42:19.455  2659  2699 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 11:42:19.460   874  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 11:42:19.474   874  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-09 11:42:19.476   874  1307 E native  : do suspend false
09-09 11:42:19.478  1912  3896 D NfcService: Discovery configuration equal, not updating.
,09-09 11:42:19.489  2659  2680 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-09 11:42:19.489  2659  2680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 11:42:19.489  2659  2680 D BtGatt.GattService: current time is 151475473691
,09-09 11:42:19.490  2659  2680 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -91, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -89, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -78, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -82, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -86, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -102, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-09 11:42:19.490  2659  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-09 11:42:19.490  2659  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-09 11:42:19.491  2659  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-09 11:42:19.491  2659  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-09 11:42:19.491  2659  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
09-09 11:42:19.492  2659  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-09 11:42:19.495   874  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,09-09 11:42:19.507   874  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 11:42:19.510   874  1307 E native  : do suspend true
,09-09 11:42:19.573   376  1280 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-09 11:42:19.574   376  1280 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-09 11:42:19.966   874  1307 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,09-09 11:42:20.997  2659  2659 D BtGatt.ScanManager: awakened up at time 152982
,09-09 11:42:21.000  2659  2699 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 11:42:21.027  2659  2680 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,09-09 11:42:21.027  2659  2680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 11:42:21.028  2659  2680 D BtGatt.GattService: current time is 153013864024
,09-09 11:42:21.028  2659  2680 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -88, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-09 11:42:21.029  2659  2680 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-09 11:42:21.449  3826  3876 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 11:42:21.449  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 11:42:21.450  3826  3876 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-09 11:42:21.450  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:21.450  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-09 11:42:21.450  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 11:42:21.451  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 11:42:21.451  3826  3876 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 11:42:21.451  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 11:42:21.452  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 11:42:21.453  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 11:42:21.461  3826  3876 D BluetoothAdapter: STATE_ON
,09-09 11:42:21.463  2659  2782 D BtGatt.GattService: stopScan() - queue size =1
,09-09 11:42:21.468  2659  3890 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 11:42:21.469  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 11:42:21.470  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-09 11:42:21.470  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 11:42:21.470  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 11:42:21.470  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 11:42:21.473  3826  3876 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 11:42:21.474  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 11:42:21.475  3826  3876 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 11:42:21.475  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 11:42:21.477  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 11:42:21.480  3826  3826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 11:42:21.481  3826  3826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 11:42:21.481  3826  3826 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 11:42:21.487  2659  2680 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-09 11:42:21.488  2659  2680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 11:42:21.488  2659  2699 D BtGatt.ScanManager: stopping BLe Batch
,09-09 11:42:21.501  2659  2680 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-09 11:42:21.501  2659  2680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 11:42:21.501  2659  2699 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 11:42:21.512  2659  2680 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 11:42:21.512  2659  2680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 11:42:21.983  3826  3826 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 11:42:21.983  3826  3826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 11:42:21.984  3826  3826 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 11:42:25.512  2123  2643 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-09 11:42:26.483  3826  3876 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 11:42:26.484  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 11:42:26.484  3826  3876 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 11:42:26.485  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 11:42:26.486  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:26.486  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 11:42:26.486  3826  3876 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1f61ab not in the list
,09-09 11:42:26.487  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:42:26.487  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
09-09 11:42:26.487  3826  3876 D io.jxcore.node.ConnectivityMonitor: stop
09-09 11:42:26.487  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 11:42:26.489  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:26.490  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 11:42:26.493  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 11:42:26.493  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 11:42:26.494  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 11:42:26.494  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
09-09 11:42:26.496  3826  3876 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-09 11:42:26.498  3826  3876 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 11:42:26.499  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 11:42:26.499  3826  3876 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 11:42:26.500  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 11:42:26.500  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:26.501  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:26.501  3826  3876 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1f61ab not in the list
09-09 11:42:26.501  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:42:26.502  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
,09-09 11:42:26.502  3826  3876 D io.jxcore.node.ConnectivityMonitor: stop
09-09 11:42:26.502  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:26.503  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:26.503  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:26.503  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:26.505  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 11:42:26.505  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 11:42:26.506  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:42:26.506  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
,09-09 11:42:26.508  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-09 11:42:26.508  3826  3876 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 11:42:26.509  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 11:42:26.509  3826  3876 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 11:42:26.509  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 11:42:26.510  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:26.510  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:26.510  3826  3876 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1f61ab not in the list
09-09 11:42:26.510  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:42:26.510  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
,09-09 11:42:26.511  3826  3876 D io.jxcore.node.ConnectivityMonitor: stop
09-09 11:42:26.511  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:26.511  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:26.511  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:26.511  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 11:42:26.513  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 11:42:26.513  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 11:42:26.514  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:42:26.514  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
,09-09 11:42:26.515  3826  3876 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-09 11:42:26.516  3826  3876 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 11:42:26.516  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 11:42:26.516  3826  3876 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 11:42:26.517  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 11:42:26.517  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 11:42:26.517  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:26.517  3826  3876 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1f61ab not in the list
09-09 11:42:26.517  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:42:26.518  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
09-09 11:42:26.518  3826  3876 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 11:42:26.518  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:26.518  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:26.518  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:26.519  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 11:42:26.520  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 11:42:26.520  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 11:42:26.521  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:42:26.521  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
,09-09 11:42:26.522  3826  3876 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-09 11:42:26.522  3826  3876 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 11:42:26.523  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 11:42:26.523  3826  3876 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 11:42:26.523  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 11:42:26.523  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:26.523  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:26.524  3826  3876 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1f61ab not in the list
09-09 11:42:26.524  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:42:26.524  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
09-09 11:42:26.524  3826  3876 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 11:42:26.524  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:26.524  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:26.524  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:26.525  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 11:42:26.526  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 11:42:26.526  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 11:42:26.526  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:42:26.526  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
,09-09 11:42:26.527  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 11:42:26.528  3826  3876 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 11:42:26.528  3826  3876 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 11:42:26.528  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 11:42:26.528  3826  3876 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 11:42:26.528  3826  3876 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 11:42:26.529  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 11:42:26.529  3826  3876 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 11:42:26.529  3826  3876 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 11:42:26.529  3826  3876 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 11:42:26.529  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 11:42:26.529  3826  3876 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 11:42:26.531  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 11:42:26.531  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 11:42:26.532  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:26.532  3826  3876 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1f61ab not in the list
09-09 11:42:26.533  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 11:42:26.533  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
09-09 11:42:26.533  3826  3876 D io.jxcore.node.ConnectivityMonitor: stop
09-09 11:42:26.533  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:26.534  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 11:42:26.534  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:26.535  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 11:42:26.537  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 11:42:26.537  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 11:42:26.537  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:42:26.537  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
,09-09 11:42:26.538  3826  3876 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-09 11:42:26.538  3826  3876 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,09-09 11:42:26.538  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-09 11:42:26.543  3826  3876 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-09 11:42:26.543  3826  3876 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,09-09 11:42:26.543  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-09 11:42:26.543  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 11:42:26.543  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-09 11:42:26.543  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 11:42:26.543  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-09 11:42:26.543  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 11:42:26.543  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 11:42:26.543  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-09 11:42:26.544  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 11:42:26.544  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-09 11:42:26.544  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 11:42:26.544  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 11:42:26.544  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-09 11:42:26.544  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-09 11:42:26.544  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-09 11:42:26.544  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 11:42:26.544  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610],
09-09 11:42:26.544  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-09 11:42:26.544  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-09 11:42:26.545  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-09 11:42:26.545  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-09 11:42:26.545  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-09 11:42:26.545  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-09 11:42:26.545  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-09 11:42:26.545  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-09 11:42:26.545  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-09 11:42:26.545  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-09 11:42:26.545  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-09 11:42:26.545  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-09 11:42:26.545  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-09 11:42:26.546  3826  3876 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,09-09 11:42:26.546  3826  3876 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-09 11:42:26.546  3826  3876 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,09-09 11:42:26.546  3826  3876 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-09 11:42:26.546  3826  3876 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 11:42:26.547  3826  3876 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection,
09-09 11:42:26.547  3826  3876 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-09 11:42:26.547  3826  3876 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 11:42:26.547  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-09 11:42:26.552  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-09 11:42:26.553  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1,
09-09 11:42:26.553  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-09 11:42:26.554  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-09 11:42:26.554  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,09-09 11:42:26.554  3826  3876 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-09 11:42:26.554  3826  3876 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 11:42:26.555  3826  3876 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,09-09 11:42:26.555  3826  3876 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 11:42:26.555  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 11:42:26.555  3826  3876 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 11:42:26.556  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 11:42:26.556  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:26.556  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 11:42:26.556  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-09 11:42:26.556  3826  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 389)
09-09 11:42:26.557  3826  3876 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1f61ab not in the list
09-09 11:42:26.557  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:42:26.557  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
09-09 11:42:26.557  3826  3876 D io.jxcore.node.ConnectivityMonitor: stop
09-09 11:42:26.557  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:26.557  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:26.557  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:26.557  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:26.559  3826  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 389
09-09 11:42:26.559  3826  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 389)
09-09 11:42:26.559  3826  3901 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 11:42:26.560  3826  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 389)
09-09 11:42:26.564  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 11:42:26.564  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 11:42:26.564  3826  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 389)
09-09 11:42:26.564  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:42:26.565  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
09-09 11:42:26.565  3826  3876 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-09 11:42:26.566  3826  3876 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 11:42:26.566  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 11:42:26.566  3826  3876 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 11:42:26.566  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 11:42:26.566  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:26.566  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:26.566  3826  3876 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1f61ab not in, the list
09-09 11:42:26.567  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:42:26.567  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
09-09 11:42:26.567  3826  3876 D io.jxcore.node.ConnectivityMonitor: stop
09-09 11:42:26.567  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:26.567  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:26.567  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:26.567  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:26.569  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 11:42:26.569  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 11:42:26.569  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:42:26.569  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
09-09 11:42:26.570  3826  3876 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-09 11:42:26.570  3826  3876 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 11:42:26.570  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 11:42:26.570  3826  3876 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 11:42:26.570  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 11:42:26.572  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:26.572  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:26.572  3826  3876 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1f61ab not in the list
09-09 11:42:26.572  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:42:26.572  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
09-09 11:42:26.572  3826  3876 D io.jxcore.node.ConnectivityMonitor: stop
09-09 11:42:26.572  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:26.572  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:26.572  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:26.573  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:26.574  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 11:42:26.574  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 11:42:26.574  3826  38,76 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:42:26.574  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
09-09 11:42:26.575  3826  3876 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-09 11:42:26.575  3826  3876 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-09 11:42:26.575  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 11:42:26.575  3826  3876 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-09 11:42:26.575  3826  3876 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 11:42:26.575  3826  3876 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-09 11:42:26.575  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 11:42:26.575  3826  3876 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-09 11:42:26.576  3826  3876 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 11:42:26.576  3826  3876 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 11:42:26.576  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 11:42:26.576  3826  3876 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-09 11:42:26.576  3826  3876 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 11:42:26.576  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 11:42:26.576  3826  3876 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 11:42:26.576  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 11:42:26.576  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:26.576  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:26.577  3826  3876 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1f61ab not in the list
09-09 11:42:26.577  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:42:26.577  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
09-09 11:42:26.577  3826  3876 D io.jxcore.node.ConnectivityMonitor: stop
09-09 11:42:26.577  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:26.577  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:26.577  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:26.577  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:26.578  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 11:42:26.578  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 11:42:26.578  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:42:26.578  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
09-09 11:42:26.579  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 11:42:26.579  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:26.579  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:26.579  3826  3876 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1f61ab not in the list
09-09 11:42:26.579  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:42:26.580  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
09-09 11:42:26.580  3826  3876 D io.jxcore.node.ConnectivityMonitor: stop
09-09 11:42:26.580  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:26.580  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 11:42:28.577  3767  3903 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 11:42:28.616  3767  3904 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 11:42:28.632  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:42:28.634  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:42:28.676  1524  2892 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 11:42:28.676  1524  2892 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 11:42:28.677  1524  2892 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 11:42:28.677  1524  2892 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:42:28.744  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:42:28.752  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:42:28.827  1524  2122 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 11:42:28.828  1524  2122 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 11:42:28.829  1524  2122 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 11:42:28.829  1524  2122 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:42:28.885  3767  3904 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 11:42:28.889  3767  3903 E BooksSync: Soft error
09-09 11:42:28.889  3767  3903 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 11:42:28.889  3767  3903 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 11:42:28.890  3767  3903 E BooksSync: Sync error
09-09 11:42:28.890  3767  3903 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 11:42:28.890  3767  3903 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 11:42:28.890  3767  3903 I BooksSync: Finished books sync
,09-09 11:42:28.911   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 160443, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 11:42:29.915  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:42:30.094  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:42:30.094  1524  3906 I VacuumService: Vacuum at: now=1473414150093 tag=VacuumService
,09-09 11:42:30.102  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:42:30.105  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:42:30.145  1524  2307 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-09 11:42:30.145  1524  2307 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-09 11:42:30.145  1524  2307 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 11:42:30.146  1524  2307 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:42:30.167  3521  3521 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-09 11:42:30.169  3521  3521 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-09 11:42:30.170  3521  3521 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-09 11:42:30.205  1524  3907 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-09 11:42:30.207  1524  3907 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-09 11:42:30.242  1524  3907 W Uploader:  no longer exists, so no auth token.
,09-09 11:42:30.885   874  1307 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,09-09 11:42:31.581  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 11:42:31.581  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
09-09 11:42:31.582  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 11:42:31.582  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:31.582  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 11:42:31.583  3826  3876 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1f61ab not in the list
09-09 11:42:31.583  3826  3876 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 11:42:31.583  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 11:42:31.584  3826  3876 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 11:42:31.584  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 11:42:31.584  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:31.585  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:31.585  3826  3876 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1f61ab not in the list
09-09 11:42:31.585  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:42:31.585  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
,09-09 11:42:31.586  3826  3876 D io.jxcore.node.ConnectivityMonitor: stop
09-09 11:42:31.586  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:31.586  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:31.586  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:31.587  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 11:42:31.589  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 11:42:31.590  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 11:42:31.590  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:42:31.590  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
,09-09 11:42:31.594  3826  3876 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-09 11:42:31.595  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 11:42:31.596  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-09 11:42:31.599  3826  3876 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-09 11:42:31.599  3826  3876 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 11:42:31.600  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 11:42:31.600  3826  3826 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-09 11:42:31.600  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 11:42:31.601  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 11:42:31.602  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-09 11:42:31.602  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 11:42:31.602  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 11:42:31.602  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:31.603  3826  3876 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-09 11:42:31.603  3826  3876 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1f61ab not in the list
09-09 11:42:31.603  3826  3826 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 11:42:31.603  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:42:31.603  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 11:42:31.604  3826  3913 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 11:42:31.604  3826  3876 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 11:42:31.604  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 11:42:31.605  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:31.605  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 11:42:31.607  3826  3876 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 11:42:31.607  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
,09-09 11:42:31.608  3826  3876 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 11:42:31.607  3826  3826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 11:42:31.608  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 11:42:31.608  3826  3876 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 11:42:31.608  3826  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 11:42:31.608  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 11:42:31.608  3826  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 11:42:31.608  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 11:42:31.608  3826  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 11:42:31.608  3826  3826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 11:42:31.608  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:31.608  3826  3876 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1f61ab not in the list
09-09 11:42:31.608  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:42:31.608  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
09-09 11:42:31.608  3826  3826 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 11:42:31.609  3826  3876 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 11:42:31.609  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:31.609  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 11:42:31.609  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:31.609  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 11:42:31.609  3826  3826 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 11:42:31.610  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 11:42:31.610  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 11:42:31.610  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 11:42:31.610  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
,09-09 11:42:31.612  3826  3876 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-09 11:42:31.612  3826  3876 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-09 11:42:31.612  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 11:42:31.613  3826  3876 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-09 11:42:31.613  3826  3876 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-09 11:42:31.613  3826  3876 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 11:42:31.613  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
09-09 11:42:31.613  3826  3876 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 11:42:31.613  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 11:42:31.613  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:31.613  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 11:42:31.613  3826  3876 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1f61ab not in the list
09-09 11:42:31.613  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:42:31.614  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
,09-09 11:42:31.614  3826  3876 D io.jxcore.node.ConnectivityMonitor: stop
09-09 11:42:31.614  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:31.614  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 11:42:31.614  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:31.614  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:31.615  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 11:42:31.615  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 11:42:31.615  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:42:31.615  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
09-09 11:42:31.620  3826  3876 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 11:42:31.620  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 11:42:31.620  3826  3876 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 11:42:31.621  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 11:42:31.621  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:31.621  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:31.621  3826  3876 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1f61ab not in the list
09-09 11:42:31.621  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:42:31.621  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
09-09 11:42:31.621  3826  3876 D io.jxcore.node.ConnectivityMonitor: stop
09-09 11:42:31.621  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:31.621  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:31.621  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:31.621  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:31.622  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 11:42:31.622  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 11:42:31.622  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:42:31.622  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
09-09 11:42:31.624  3826  3876 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 11:42:31.624  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 11:42:31.624  3826  3876 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 11:42:31.624  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 11:42:31.624  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:31.624  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:31.624  3826  3876 E org.thaliproject.p2p.btconnectorlib.Conn,ectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1f61ab not in the list
09-09 11:42:31.625  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:42:31.625  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
09-09 11:42:31.625  3826  3876 D io.jxcore.node.ConnectivityMonitor: stop
09-09 11:42:31.625  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:31.625  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:31.625  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:31.625  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:42:31.626  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 11:42:31.626  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 11:42:31.627  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:42:31.627  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b60e008 not in the list
09-09 11:42:31.628  3826  3876 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-09 11:42:31.628  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 11:42:31.629  3826  3876 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-09 11:42:31.629  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 11:42:31.629  3826  3876 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-09 11:42:31.629  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-09 11:42:31.632  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 11:42:31.632  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-09 11:42:31.633  3826  3876 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,09-09 11:42:31.633  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 11:42:31.633  3826  3876 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-09 11:42:31.633  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 11:42:31.633  3826  3876 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-09 11:42:31.633  3826  3876 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-09 11:42:31.634  3826  3876 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-09 11:42:31.634  3826  3876 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-09 11:42:31.634  3826  3876 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-09 11:42:31.635  3826  3876 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-09 11:42:31.635  3826  3876 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,09-09 11:42:31.635  3826  3876 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-09 11:42:31.636  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 11:42:31.636  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@200b9b added. We now have 3 listener(s)
09-09 11:42:31.636  3826  3876 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 11:42:31.638  3826  3876 D BluetoothAdapter: enable(): BT is already enabled..!
09-09 11:42:31.639   874  1700 D WifiService: setWifiEnabled: true pid=3826, uid=10000
09-09 11:42:31.639   874  1700 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 11:42:31.696  2659  2759 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-09 11:42:31.698  2659  2772 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,09-09 11:42:32.109  3826  3826 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 11:42:32.792  1524  3907 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
09-09 11:42:32.792  1524  3907 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,09-09 11:42:32.793  1524  3907 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 11:42:32.793  1524  3907 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:42:32.812  1524  3907 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-09 11:42:32.812  1524  3907 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-09 11:42:32.812  1524  3907 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-09 11:42:32.812  1524  3907 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-09 11:42:32.812  1524  3907 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-09 11:42:32.812  1524  3907 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-09 11:42:32.812  1524  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-09 11:42:32.812  1524  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-09 11:42:32.812  1524  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-09 11:42:32.812  1524  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-09 11:42:32.812  1524  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-09 11:42:32.812  1524  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-09 11:42:32.812  1524  3907 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-09 11:42:33.117  1524  3907 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-09 11:42:33.117  1524  3907 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,09-09 11:42:33.117  1524  3907 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 11:42:33.118  1524  3907 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:42:33.137  1524  3907 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-09 11:42:33.137  1524  3907 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-09 11:42:33.137  1524  3907 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-09 11:42:33.137  1524  3907 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-09 11:42:33.137  1524  3907 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-09 11:42:33.137  1524  3907 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-09 11:42:33.137  1524  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-09 11:42:33.137  1524  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-09 11:42:33.137  1524  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-09 11:42:33.137  1524  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-09 11:42:33.137  1524  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-09 11:42:33.137  1524  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-09 11:42:33.137  1524  3907 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-09 11:42:33.707  1524  3907 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-09 11:42:33.707  1524  3907 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,09-09 11:42:33.707  1524  3907 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 11:42:33.707  1524  3907 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:42:33.727  1524  3907 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-09 11:42:33.727  1524  3907 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-09 11:42:33.727  1524  3907 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-09 11:42:33.727  1524  3907 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-09 11:42:33.727  1524  3907 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-09 11:42:33.727  1524  3907 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-09 11:42:33.727  1524  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-09 11:42:33.727  1524  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-09 11:42:33.727  1524  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-09 11:42:33.727  1524  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-09 11:42:33.727  1524  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-09 11:42:33.727  1524  3907 E Uploader: 	,at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-09 11:42:33.727  1524  3907 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-09 11:42:36.648  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 11:42:36.648  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6105b38 added. We now have 4 listener(s)
09-09 11:42:36.649  3826  3876 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 11:42:36.667  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 11:42:36.667  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6105b38 removed from the list
,09-09 11:42:36.668  3826  3876 D io.jxcore.node.ConnectivityMonitor: stop
09-09 11:42:36.668  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:36.668  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 11:42:36.670  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 11:42:36.671  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6121711 added. We now have 4 listener(s)
,09-09 11:42:36.671  3826  3876 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 11:42:36.675  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 11:42:36.675  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6121711 removed from the list
09-09 11:42:36.676  3826  3876 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 11:42:36.676  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:42:36.676  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 11:42:36.679  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 11:42:36.679  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e13076 added. We now have 4 listener(s)
,09-09 11:42:36.679  3826  3876 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 11:42:36.686   874   884 D WifiService: setWifiEnabled: false pid=3826, uid=10000
,09-09 11:42:36.686   874   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 11:42:36.699  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 11:42:36.700  2659  2675 D BluetoothAdapterState: Current state: ON, message: 23
,09-09 11:42:36.701  2659  2675 D BluetoothAdapterProperties: Setting state to 13
,09-09 11:42:36.701  2659  2675 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-09 11:42:36.703  2659  2675 D BluetoothAdapterProperties: onBluetoothDisable()
09-09 11:42:36.704  2659  2675 I BluetoothAdapterState: Entering PendingCommandState
,09-09 11:42:36.708  2659  2680 D BluetoothAdapterProperties: Scan Mode:20
,09-09 11:42:36.708  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 11:42:36.709  2659  2675 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-09 11:42:36.709  3826  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 11:42:36.709  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:42:36.709  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:42:36.709  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 11:42:36.709  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 11:42:36.709  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 11:42:36.709  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 11:42:36.709  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 11:42:36.712  2659  2659 D BluetoothMapService: onReceive
,09-09 11:42:36.713  2659  2659 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 11:42:36.713  2659  2659 D BluetoothMapService: STATE_TURNING_OFF
09-09 11:42:36.713  2659  2659 D BluetoothMapService: MAP Service closeService in
,09-09 11:42:36.714  2659  2659 D BluetoothMapMasInstance0: MAP Service shutdown
,09-09 11:42:36.714  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 11:42:36.714  2659  2659 D ObexServerSockets0: shutdown(block = true)
09-09 11:42:36.715  3826  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 11:42:36.715  3826  3876 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 11:42:36.716  2659  2801 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-09 11:42:36.722  2659  2659 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 11:42:36.723  2659  2802 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-09 11:42:36.724  2659  2772 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-09 11:42:36.725  2659  2659 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-09 11:42:36.725  2659  2659 I BtOppRfcommListener: stopping Accept Thread
,09-09 11:42:36.726  2659  3446 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 11:42:36.726  2659  3446 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-09 11:42:36.730  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 11:42:36.733  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 11:42:36.736  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 11:42:36.737  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 11:42:36.737  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:42:36.737  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:42:36.737  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 11:42:36.737  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 11:42:36.737  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 11:42:36.737  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 11:42:36.737  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 11:42:36.737  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 11:42:36.738  3826  3826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 11:42:36.739  1475  1475 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-09 11:42:36.742   874  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-09 11:42:36.742   874  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[],
09-09 11:42:36.742  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 11:42:36.742  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
09-09 11:42:36.742  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:42:36.742  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:42:36.742  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 11:42:36.742  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 11:42:36.742  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 11:42:36.742  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 11:42:36.742  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 11:42:36.742   874  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 11:42:36.742   874  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 11:42:36.743   874   887 I ActivityManager: Start proc 3923:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-09 11:42:36.743  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 11:42:36.743  3826  3826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 11:42:36.748  2659  2659 D HeadsetService: Received stop request...Stopping profile...
,09-09 11:42:36.750  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 11:42:36.752  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 11:42:36.754  1927  1940 D BluetoothHeadset: Proxy object disconnected
09-09 11:42:36.754   874   874 D BluetoothHeadset: Proxy object disconnected
09-09 11:42:36.755   874   874 D BluetoothHeadset: Proxy object disconnected
09-09 11:42:36.755  1349  2033 D BluetoothHeadset: Proxy object disconnected
,09-09 11:42:36.755   874   874 D BluetoothHeadset: Proxy object disconnected
09-09 11:42:36.756  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 11:42:36.757  1349  1349 D HeadsetProfile: Bluetooth service disconnected
09-09 11:42:36.757   874  1307 E native  : do suspend true
09-09 11:42:36.757  2659  2659 D A2dpService: Received stop request...Stopping profile...
,09-09 11:42:36.758  2659  2784 D A2dpStateMachine: Exit Disconnected: -1
09-09 11:42:36.759   874   874 D BluetoothA2dp: Proxy object disconnected
09-09 11:42:36.759  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 11:42:36.759  1349  1349 D BluetoothA2dp: Proxy object disconnected
09-09 11:42:36.760  2659  2659 D HidService: Received stop request...Stopping profile...
,09-09 11:42:36.760  2659  2659 D HidService: Stopping Bluetooth HidService
09-09 11:42:36.762  1349  1349 D BluetoothInputDevice: Proxy object disconnected
09-09 11:42:36.762  1349  1349 D HidProfile: Bluetooth service disconnected
,09-09 11:42:36.763  2659  2659 D HealthService: Received stop request...Stopping profile...
,09-09 11:42:36.763  2659  2659 V BluetoothAdapterState: isTurningOff()=true
,09-09 11:42:36.763  2659  2659 V BluetoothAdapterState: isTurningOn()=false
,09-09 11:42:36.763  2659  2659 V BluetoothAdapterState: isBleTurningOn()=false
09-09 11:42:36.763  2659  2659 V BluetoothAdapterState: isBleTurningOff()=false
09-09 11:42:36.765  2659  2659 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 11:42:36.765  2659  2680 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-09 11:42:36.765  2659  2759 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 11:42:36.765  2659  2759 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-09 11:42:36.765  2659  2759 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 11:42:36.766  2659  2680 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-09 11:42:36.766  2659  2659 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 11:42:36.766  2659  2659 D PanService: Received stop request...Stopping profile...
09-09 11:42:36.767  1349  1349 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-09 11:42:36.767  1349  1349 D PanProfile: Bluetooth service disconnected
09-09 11:42:36.767  2659  2659 D BluetoothMapService: Received stop request...Stopping profile...
09-09 11:42:36.767  2659  2659 D BluetoothMapService: stop()
09-09 11:42:36.768  2659  2659 D BluetoothMapAppObserver: deinitObservers()
09-09 11:42:36.768  2659  2659 D BluetoothMapAppObserver: removeReceiver()
09-09 11:42:36.769  1349  1349 D BluetoothMap: Proxy object disconnected
09-09 11:42:36.769  1349  1349 D MapProfile: Bluetooth service disconnected
09-09 11:42:36.769  2659  2659 V BluetoothAdapterState: isTurningOff()=true
09-09 11:42:36.769  2659  2659 V BluetoothAdapterState: isTurningOn()=false
09-09 11:42:36.769  2659  2659 V BluetoothAdapterState: isBleTurningOn()=false
09-09 11:42:36.769  2659  2659 V BluetoothAdapterState: isBleTurningOff()=false
09-09 11:42:36.770   874  1891 D DhcpClient: Clearing IP address
09-09 11:42:36.770   372   872 D CommandListener: Clearing all IP addresses on wlan0
09-09 11:42:36.771  2659  2680 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-09 11:42:36.771  2659  2759 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 11:42:36.771  2659  2759 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-09 11:42:36.772  2659  2759 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 11:42:36.772  2659  2759 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 11:42:36.772  2659  2759 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 11:42:36.772  2659  2759 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 11:42:36.772  2659  2659 V BluetoothAdapterState: isTurningOff()=true
09-09 11:42:36.772  2659  2659 V BluetoothAdapterState: isTurningOn()=false
09-09 11:42:36.772  2659  2659 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 11:42:36.772  2659  2659 V BluetoothAdapterState: isBleTurningOff()=false
09-09 11:42:36.772  2659  2659 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 11:42:36.772  2659  2680 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-09 11:42:36.772  2659  2659 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 11:42:36.773  2659  2659 V BluetoothAdapterState: isTurningOff()=true
09-09 11:42:36.773  2659  2659 V BluetoothAdapterState: isTurningOn()=false
09-09 11:42:36.773  2659  2659 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 11:42:36.773   372   872 D CommandListener: Setting iface cfg
09-09 11:42:36.773  2659  2659 V BluetoothAdapterState: isBleTurningOff()=false
09-09 11:42:36.773  2659  2659 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 11:42:36.773  2659  2680 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-09 11:42:36.773  2659  2659 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 11:42:36.774  2659  2659 V BluetoothAdapterState: isTurningOff()=true
09-09 11:42:36.774  2659  2659 V BluetoothAdapterState: isTurningOn()=false
,09-09 11:42:36.774  2659  2659 V BluetoothAdapterState: isBleTurningOn()=false
09-09 11:42:36.774  2659  2659 V BluetoothAdapterState: isBleTurningOff()=false
09-09 11:42:36.775  2659  2659 D BluetoothMapService: MAP Service closeService in
09-09 11:42:36.775  2659  2659 V BluetoothAdapterState: isTurningOff()=true
09-09 11:42:36.775  2659  2659 V BluetoothAdapterState: isTurningOn()=false
09-09 11:42:36.775  2659  2659 V BluetoothAdapterState: isBleTurningOn()=false
09-09 11:42:36.775  2659  2659 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 11:42:36.776  2659  2675 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-09 11:42:36.776  2659  2675 D BluetoothAdapterProperties: Setting state to 15
09-09 11:42:36.776  2659  2675 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-09 11:42:36.776  2659  2675 I BluetoothAdapterState: Entering BleOnState
09-09 11:42:36.777  1349  1369 D BluetoothPan: onBluetoothStateChange on: false
09-09 11:42:36.777  2659  2659 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 11:42:36.777   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-09 11:42:36.777   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-09 11:42:36.777   874  1307 D WifiStateMachine: Start Disconnecting Watchdog 1
,09-09 11:42:36.778   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 11:42:36.778  1927  1939 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 11:42:36.778   874  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 11:42:36.778   874  1307 E native  : do suspend true
09-09 11:42:36.777  2659  2659 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-09 11:42:36.778   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 11:42:36.780   395   395 E Parcel  : Reading a NULL string not supported here.
,09-09 11:42:36.781  1349  1369 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 11:42:36.782   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 11:42:36.782  1349  2029 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 11:42:36.783  2659  2659 D BluetoothMapService: cleanup()
09-09 11:42:36.783  2659  2659 D BluetoothMapService: MAP Service closeService in
09-09 11:42:36.784   874  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-09 11:42:36.785  1349  2033 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 11:42:36.786  1349  1369 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 11:42:36.786   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 11:42:36.787  1349  1362 D BluetoothMap: onBluetoothStateChange: up=false
09-09 11:42:36.787  2659  2675 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-09 11:42:36.788  2659  2675 D BluetoothAdapterProperties: Setting state to 16
09-09 11:42:36.788  2659  2675 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-09 11:42:36.788  2659  2675 D BluetoothAdapterProperties: onBleDisable
09-09 11:42:36.789  2659  2675 I BluetoothAdapterState: Entering PendingCommandState
09-09 11:42:36.789  2659  2676 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-09 11:42:36.790  2659  2680 D BluetoothAdapterProperties: Scan Mode:20
,09-09 11:42:36.790  2659  2759 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-09 11:42:36.790  2659  2759 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 11:42:36.791  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 11:42:36.791  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 11:42:36.791  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:42:36.791  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:42:36.791  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 11:42:36.791  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 11:42:36.791  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 11:42:36.791  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 11:42:36.791  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 11:42:36.792  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 11:42:36.792  3826  3826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 11:42:36.793   874  1895 D DhcpClient: Receive thread stopped
09-09 11:42:36.794  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 11:42:36.794  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 11:42:36.794  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:42:36.794  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:42:36.794  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 11:42:36.794  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 11:42:36.794  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 11:42:36.794  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 11:42:36.794  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 11:42:36.795  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 11:42:36.795  3826  3826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 11:42:36.811  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 11:42:36.811  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 11:42:36.811  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:42:36.811  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:42:36.811  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 11:42:36.811  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 11:42:36.811  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 11:42:36.811  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 11:42:36.811  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 11:42:36.812  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 11:42:36.812  3826  3826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 11:42:36.813  1524  2191 V NativeCrypto: Read error: ssl=0xaecbd600: I/O error during system call, Connection timed out
09-09 11:42:36.813  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 11:42:36.814  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 11:42:36.814  1524  2191 V NativeCrypto: SSL shutdown failed: ssl=0xaecbd600: I/O error during system call, Broken pipe
09-09 11:42:36.815  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 11:42:36.825   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 11:42:36.837  3923  3923 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-09 11:42:36.842   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 11:42:36.842   372   872 D CommandListener: Clearing all IP addresses on wlan0
,09-09 11:42:36.843   874  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-09 11:42:36.843   874  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-09 11:42:36.844   874  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-09 11:42:36.846   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-09 11:42:36.849  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 11:42:36.849  3438  3438 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@254596c and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-09 11:42:36.850  1999  1999 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
09-09 11:42:36.850  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 11:42:36.852  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 11:42:36.858  3923  3923 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 11:42:36.861   874  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 11:42:36.864   874  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 11:42:36.866  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 11:42:36.866  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 11:42:36.866  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 11:42:36.866  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:42:36.866  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:42:36.866  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 11:42:36.866  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 11:42:36.866  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 11:42:36.866  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 11:42:36.866  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 11:42:36.867   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ba8978e:true
09-09 11:42:36.867  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 11:42:36.867  3826  3826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 11:42:36.868  2123  2315 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 11:42:36.869  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 11:42:36.869  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 11:42:36.869  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:42:36.869  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:42:36.869  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 11:42:36.869  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 11:42:36.869  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 11:42:36.869  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 11:42:36.869  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 11:42:36.870  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 11:42:36.870  3826  3826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 11:42:36.872  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 11:42:36.872  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 11:42:36.872  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:42:36.872  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:42:36.872  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 11:42:36.872  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 11:42:36.872  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 11:42:36.872  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 11:42:36.872  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 11:42:36.873  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 11:42:36.873  3826  3826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 11:42:36.882   874  1383 I ActivityManager: Start proc 3942:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-09 11:42:36.890  3923  3923 D LocalBluetoothProfileManager: Adding local MAP profile
,09-09 11:42:36.893  3923  3923 D BluetoothMap: Create BluetoothMap proxy object
,09-09 11:42:36.905  3923  3923 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-09 11:42:36.911   372   872 E Netd    : netlink response contains error (No such file or directory)
09-09 11:42:36.912   874  1309 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-09 11:42:36.912  3942  3942 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-09 11:42:36.917  3923  3923 D DockEventReceiver: finishStartingService: stopping service
,09-09 11:42:36.924   874  1700 I ActivityManager: Killing 2972:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-09 11:42:36.996  2659  2680 I bt_hci  : shut_down
,09-09 11:42:37.003  2659  2700 I bt_vendor: low_power_mode_cb
,09-09 11:42:37.007  2659  2700 D bt_hwcfg: hw_epilog_process
,09-09 11:42:37.030  2659  2700 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-09 11:42:37.030  2659  2700 I bt_vendor: epilog_cb
09-09 11:42:37.030  2659  2700 I bt_hci  : epilog_finished_callback
,09-09 11:42:37.035  2659  2680 I bt_hci_h4: hal_close
,09-09 11:42:37.036  2659  2680 I bt_userial_vendor: device fd = 51 close
,09-09 11:42:37.154  2659  2676 D bt_stack_manager: event_shut_down_stack finished.
,09-09 11:42:37.155  2659  2675 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-09 11:42:37.160  2659  2659 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 11:42:37.160  2659  2675 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-09 11:42:37.161  2659  2659 D BtGatt.GattService: Received stop request...Stopping profile...
09-09 11:42:37.161  2659  2659 D BtGatt.GattService: stop()
,09-09 11:42:37.161  2659  2659 D BtGatt.AdvertiseManager: advertise clients cleared
,09-09 11:42:37.163  2659  2659 V BluetoothAdapterState: isTurningOff()=false
,09-09 11:42:37.163  2659  2659 V BluetoothAdapterState: isTurningOn()=false
,09-09 11:42:37.163  2659  2659 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 11:42:37.163  2659  2659 V BluetoothAdapterState: isBleTurningOff()=true
,09-09 11:42:37.164  2659  2675 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-09 11:42:37.164  2659  2675 D BluetoothAdapterProperties: Setting state to 10
,09-09 11:42:37.164  2659  2675 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-09 11:42:37.166  2659  2675 I BluetoothAdapterState: Entering OffState
09-09 11:42:37.167   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-09 11:42:37.189  2659  2659 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-09 11:42:37.189  2659  2659 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-09 11:42:37.190  2659  2659 I BluetoothServiceJni: cleanupNative: return from cleanup
09-09 11:42:37.190  2659  2676 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-09 11:42:37.194  2659  2676 D bt_stack_manager: event_clean_up_stack finished.
,09-09 11:42:37.201  3942  3942 D StrictMode: StrictMode policy violation; ~duration=173 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 11:42:37.201  3942  3942 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 11:42:37.201  3942  3942 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 11:42:37.201  3942  3942 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 11:42:37.201  3942  3942 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 11:42:37.201  3942  3942 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-09 11:42:37.201  3942  3942 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-09 11:42:37.201  3942  3942 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-09 11:42:37.201  3942  3942 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 11:42:37.201  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 11:42:37.201  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 11:42:37.201  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 11:42:37.201  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 11:42:37.201  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 11:42:37.201  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 11:42:37.201  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 11:42:37.201  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 11:42:37.201  3942  3942 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 11:42:37.201  3942  3942 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 11:42:37.201  3942  3942 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 11:42:37.201  3942  3942 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 11:42:37.201  3942  3942 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 11:42:37.201  3942  3942 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 11:42:37.201  3942  3942 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 11:42:37.201  3942  3942 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 11:42:37.201  3942  3942 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 11:42:37.201  3942  3942 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 11:42:37.202  3942  3942 D StrictMode: StrictMode policy violation; ~duration=172 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 11:42:37.202  3942  3942 D StrictMode: StrictMode policy violation; ~duration=171 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 11:42:37.202  3942  3942 D StrictMode: StrictMode policy violation; ~duration=169 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-09 11:42:37.202  3,942  3942 D StrictMode: 	at com.google.r.e.b(PG:170)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 11:42:37.202  3942  3942 D StrictMode: StrictMode policy violation; ~duration=164 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.r.k.d(PG:583)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.r.e.b(PG:170)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 1,1:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 11:42:37.202  3942  3942 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 11:42:37.202  3942  3942 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 11:42:37.202  3942  3942 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 11:42:37.202  3942  3942 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 11:42:37.208  3923  3923 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-09 11:42:37.215  2659  2659 I art     : System.exit called, status: 0
09-09 11:42:37.215  2659  2659 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-09 11:42:37.239  3923  3923 D DockEventReceiver: finishStartingService: stopping service
09-09 11:42:37.247   874  1976 I ActivityManager: Killing 3074:com.google.android.talk/u0a61 (adj 15): empty #17
,09-09 11:42:37.320   874  1392 I ActivityManager: Process com.android.bluetooth (pid 2659) has died
,09-09 11:42:37.338  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 11:42:37.360   874  1700 I ActivityManager: Start proc 3975:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver
,09-09 11:42:37.486  3975  3975 D AdapterServiceConfig: Adding HeadsetService
,09-09 11:42:37.486  3975  3975 D AdapterServiceConfig: Adding A2dpService
,09-09 11:42:37.486  3975  3975 D AdapterServiceConfig: Adding HidService
09-09 11:42:37.486  3975  3975 D AdapterServiceConfig: Adding HealthService
09-09 11:42:37.486  3975  3975 D AdapterServiceConfig: Adding PanService
09-09 11:42:37.486  3975  3975 D AdapterServiceConfig: Adding GattService
09-09 11:42:37.487  3975  3975 D AdapterServiceConfig: Adding BluetoothMapService
,09-09 11:42:37.504   874  1981 I ActivityManager: Start proc 3989:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,09-09 11:42:37.509  3942  3966 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-09 11:42:37.526   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a0efd8f:true
,09-09 11:42:37.550  3989  3989 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,09-09 11:42:37.698  3989  4006 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,09-09 11:42:37.698  3989  4006 I Babel_SMS: MmsConfig.loadMmsSettings
,09-09 11:42:37.713  3989  4006 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-09 11:42:37.713  3989  4006 I Babel_SMS: MmsConfig.loadFromDatabase
,09-09 11:42:37.744  3989  4006 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,09-09 11:42:37.744  3989  4006 I Babel_SMS: MmsConfig.loadFromResources
09-09 11:42:37.745  3989  4006 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-09 11:42:37.746  3989  4006 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-09 11:42:37.778  3989  3989 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 11:42:37.780  3989  3989 I Babel_Crash: startup - clean
,09-09 11:42:37.802  3989  3989 I Babel_telephony: TeleModule.launchCompleted
,09-09 11:42:37.816   874  1981 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-09 11:42:37.831  3989  3989 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,09-09 11:42:37.839  3989  3989 W Babel   : BAM#gBA: invalid account id: -1
,09-09 11:42:37.839  3989  3989 W Babel   : BAM#gBA: invalid account id: -1
,09-09 11:42:37.839  3989  3989 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,09-09 11:42:37.844  3989  4011 I Babel   : deleted: false for 0
,09-09 11:42:37.851   874  3124 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-09 11:42:37.870  1751  1751 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 11:42:37.875  1751  1751 D SystemUpdateService: onCreate
,09-09 11:42:37.886  1751  1751 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 11:42:37.904  1751  4013 I SystemUpdateService: active receiver: enabled
,09-09 11:42:37.913  1751  4013 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 11:42:37.918  1751  4013 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-09 11:42:37.919  1751  4013 I SystemUpdateService: now status is 0 (complete)
,09-09 11:42:37.919  1751  1751 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-09 11:42:37.920  1751  4013 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-09 11:42:37.920  1751  4013 I SystemUpdateService: file has been verified
09-09 11:42:37.921  1751  4013 I SystemUpdateService: OTA package size = 12249756
09-09 11:42:37.924  1751  2427 I iu.UploadsManager: num queued entries: 0
09-09 11:42:37.925  1751  2427 I iu.UploadsManager: num updated entries: 0
,09-09 11:42:37.926  1751  2427 I iu.SyncManager: NEXT; no task
,09-09 11:42:37.930  1751  4013 I SystemUpdateService: showing system update notification
,09-09 11:42:37.943  1751  1751 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 11:42:37.945  1751  1751 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 11:42:37.963   874  1392 I ActivityManager: Start proc 4015:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-09 11:42:37.965  1751  1751 D SystemUpdateService: onDestroy
09-09 11:42:37.967  3989  3989 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 11:42:38.005  4015  4015 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-09 11:42:38.018  4015  4015 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 11:42:38.032  4015  4015 D SprintDMHelper: simOperator: 
,09-09 11:42:38.032  4015  4015 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 11:42:38.036  3989  3989 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-09 11:42:38.051  3989  3989 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 11:42:38.053  3989  3989 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 11:42:38.057  3989  3989 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 11:42:38.069   874  1948 I ActivityManager: Start proc 4027:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-09 11:42:38.069  3989  3989 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 11:42:38.073   874  1948 I ActivityManager: Killing 3438:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-09 11:42:38.134  3989  3989 I vclib   : onServiceConnected
,09-09 11:42:38.136   874  1948 I ActivityManager: Killing 3487:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-09 11:42:38.265   874   885 I ActivityManager: Start proc 4042:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-09 11:42:38.268  3989  4041 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-09 11:42:38.274   874  1383 I ActivityManager: Killing 1699:android.process.acore/u0a5 (adj 15): empty #17
,09-09 11:42:38.357  4042  4042 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-09 11:42:38.419  4042  4042 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-09 11:42:38.419  4042  4042 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-09 11:42:38.419  4042  4042 I GAv4    :   adb logcat -s GAv4
,09-09 11:42:38.433  4042  4042 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-09 11:42:38.440  4042  4042 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-09 11:42:38.474  4042  4059 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-09 11:42:38.579  4042  4042 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-09 11:42:38.622  4042  4042 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-09 11:42:38.631  4042  4042 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 612-616)
,09-09 11:42:38.631  4042  4042 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-09 11:42:38.646  4042  4042 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ad6f59c}
09-09 11:42:38.646  4042  4042 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 11:42:38.647  4042  4042 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-09 11:42:38.656  4042  4042 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-09 11:42:38.658  4042  4042 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-09 11:42:38.674  4042  4042 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-09 11:42:38.688  4042  4042 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 11:42:38.688  4042  4042 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 11:42:38.688  4042  4042 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 11:42:38.688  4042  4042 I Adreno  : Build Date                       : 10/20/15
09-09 11:42:38.688  4042  4042 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 11:42:38.688  4042  4042 I Adreno  : Local Branch                     : M14
09-09 11:42:38.688  4042  4042 I Adreno  : Remote Branch                    : 
09-09 11:42:38.688  4042  4042 I Adreno  : Remote Branch                    : 
09-09 11:42:38.688  4042  4042 I Adreno  : Reconstruct Branch               : 
,09-09 11:42:38.754  4042  4042 I NSApplication: Starting up...
,09-09 11:42:38.763  4042  4088 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-09 11:42:38.797   874  1700 I ActivityManager: Start proc 4093:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
09-09 11:42:38.798   874  1700 I ActivityManager: Killing 3658:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-09 11:42:38.855  4093  4093 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-09 11:42:39.056   874   885 I ActivityManager: Killing 3674:com.android.musicfx/u0a18 (adj 15): empty #17
,09-09 11:42:39.174   874  1981 I ActivityManager: Start proc 4107:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-09 11:42:39.228  4107  4107 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-09 11:42:39.282  4107  4107 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-09 11:42:39.356   874  1392 I ActivityManager: Killing 2231:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-09 11:42:41.719   874  3124 D WifiService: setWifiEnabled: true pid=3826, uid=10000
,09-09 11:42:41.719   874  3124 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 11:42:41.734   874  1307 D WifiConfigStore: Loading config and enabling all networks 
,09-09 11:42:41.741  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 11:42:41.743  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 11:42:41.743  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:42:41.743  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:42:41.743  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 11:42:41.743  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 11:42:41.743  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 11:42:41.743  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 11:42:41.743  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 11:42:41.743  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 11:42:41.744  3826  3826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 11:42:41.755  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 11:42:41.755  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 11:42:41.755  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:42:41.755  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:42:41.755  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 11:42:41.755  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 11:42:41.755  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 11:42:41.755  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 11:42:41.755  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 11:42:41.756  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 11:42:41.756  3826  3826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 11:42:41.757  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 11:42:41.757  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 11:42:41.757  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:42:41.757  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:42:41.757  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 11:42:41.757  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 11:42:41.757  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 11:42:41.757  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 11:42:41.757  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 11:42:41.757  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 11:42:41.757  3826  3826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 11:42:41.780   874  1307 D WifiConfigStore: loaded 0 passpoint configs
,09-09 11:42:41.781   874  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-09 11:42:41.782   874  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-09 11:42:41.783   874  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-09 11:42:41.783   874  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-09 11:42:41.783   874  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-09 11:42:41.783   874  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-09 11:42:41.818   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-09 11:42:41.819   874  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-09 11:42:41.819   372   872 D CommandListener: Setting iface cfg
09-09 11:42:41.820   874  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-09 11:42:41.820   874  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-09 11:42:41.831   874  1306 D WifiNative-HAL: p2pGetDeviceAddress
,09-09 11:42:41.831   874  1307 E native  : do suspend true
,09-09 11:42:41.831   874  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-09 11:42:41.847   874  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 11:42:42.556   874  1948 I ActivityManager: Killing 3696:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-09 11:42:43.144   874  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-09 11:42:43.227   874  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.12 rxSuccessRate=10.88 delta 1000 -> 994
,09-09 11:42:43.229   874  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-09 11:42:43.229   874  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 11:42:43.244   874  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-09 11:42:43.295   874  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-09 11:42:43.298  1475  1475 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-09 11:42:43.742  1475  1475 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-09 11:42:43.838  1475  1475 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-09 11:42:43.839  1475  1475 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-09 11:42:43.846   874  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 11:42:43.866   874  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 11:42:43.867   874  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 11:42:43.867   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-09 11:42:43.883   874  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 11:42:43.894   372   872 D CommandListener: Setting iface cfg
09-09 11:42:43.895   874  1307 D WifiStateMachine: Start Dhcp Watchdog 2
,09-09 11:42:43.900   874  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-09 11:42:43.920   874  4144 D DhcpClient: Receive thread started
,09-09 11:42:44.006   874  1307 E native  : do suspend false
,09-09 11:42:44.028   874  1891 D DhcpClient: Broadcasting DHCPDISCOVER
,09-09 11:42:44.041   874  4144 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172647, domain null
,09-09 11:42:44.043   874  1891 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172647 seconds
,09-09 11:42:44.047   874  1891 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-09 11:42:44.070   874  4144 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-09 11:42:44.071   874  1891 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-09 11:42:44.076   372   872 D CommandListener: Setting iface cfg
,09-09 11:42:44.088   874  1891 D DhcpClient: Scheduling renewal in 86399s
,09-09 11:42:44.088   874  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-09 11:42:44.093   874  1307 E native  : do suspend true
,09-09 11:42:44.116   874  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-09 11:42:44.120   874  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,09-09 11:42:44.122   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-09 11:42:44.127   874  1309 D ConnectivityService: Adding iface wlan0 to network 101
,09-09 11:42:44.133   874  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-09 11:42:44.203   874  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-09 11:42:44.203   874  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-09 11:42:44.205   874  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-09 11:42:44.208   874  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-09 11:42:44.209   874  1309 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-09 11:42:44.220   874  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-09 11:42:44.227   874  1309 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-09 11:42:44.228   874  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-09 11:42:44.228   874  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-09 11:42:44.228   874  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 11:42:44.229   874  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-09 11:42:44.229   874  1309 D ConnectivityService:    accepting network in place of null
,09-09 11:42:44.230   874  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 11:42:44.269   874  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=176254, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 11:42:44.286   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 11:42:44.336   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 11:42:44.344   874  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-09 11:42:44.344   874  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 11:42:44.348   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-09 11:42:44.352   874  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-09 11:42:44.356  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 11:42:44.356  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 11:42:44.356  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:42:44.356  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:42:44.356  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 11:42:44.356  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 11:42:44.356  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 11:42:44.356  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 11:42:44.356  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 11:42:44.357  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 11:42:44.357  3826  3826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 11:42:44.363   874  4140 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-09 11:42:44.364  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 11:42:44.364  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 11:42:44.364  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:42:44.364  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:42:44.364  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 11:42:44.364  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 11:42:44.364  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 11:42:44.364  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 11:42:44.364  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 11:42:44.364  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 11:42:44.364  3826  3826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 11:42:44.366  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 11:42:44.366  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 11:42:44.366  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:42:44.366  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:42:44.366  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 11:42:44.366  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 11:42:44.366  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 11:42:44.366  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 11:42:44.366  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 11:42:44.366  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 11:42:44.366  3826  3826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 11:42:44.374  1999  1999 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-09 11:42:44.384  1751  1751 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 11:42:44.388  1751  1751 D SystemUpdateService: onCreate
,09-09 11:42:44.391  1751  1751 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 11:42:44.416  1751  4154 I SystemUpdateService: active receiver: enabled
,09-09 11:42:44.418  1751  1751 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-09 11:42:44.427  1751  2427 I iu.UploadsManager: num queued entries: 0
,09-09 11:42:44.427  1751  2427 I iu.UploadsManager: num updated entries: 0
,09-09 11:42:44.430  1751  4154 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 11:42:44.432  1751  1751 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 11:42:44.434   874  4140 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 09:42:44 GMT], X-Android-Received-Millis=[1473414164433], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473414164403]}
09-09 11:42:44.435   874  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-09 11:42:44.435   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-09 11:42:44.435   874  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-09 11:42:44.436   874  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-09 11:42:44.436  1751  1751 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-09 11:42:44.438  4015  4015 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 11:42:44.452  1751  4156 I MDM     : [177] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-09 11:42:44.453  1751  4156 W BaseAppContext: Using Auth Proxy for data requests.
09-09 11:42:44.455  4015  4015 D SprintDMHelper: simOperator: 
,09-09 11:42:44.455  4015  4015 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 11:42:44.459  1751  4156 V GoogleAuthProtoRequest: [177] a.<init>: mAccountName set to: thalitester@gmail.com
,09-09 11:42:44.461  1751  4154 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-09 11:42:44.461  1751  4154 I SystemUpdateService: now status is 0 (complete)
09-09 11:42:44.461  1751  4154 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-09 11:42:44.461  1751  4154 I SystemUpdateService: file has been verified
,09-09 11:42:44.467  1751  2427 I iu.SyncManager: NEXT; no task
,09-09 11:42:44.467  1751  4154 I SystemUpdateService: OTA package size = 12249756
,09-09 11:42:44.475  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:42:44.477  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:42:44.500  1751  4154 I SystemUpdateService: showing system update notification
,09-09 11:42:44.553  1751  1751 D SystemUpdateService: onDestroy
,09-09 11:42:44.569  1524  2122 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-09 11:42:44.570  1524  2122 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-09 11:42:44.570  1524  2122 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 11:42:44.570  1524  2122 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:42:44.601  1751  4156 E MDM     : [177] SitrepService.a: Error sending sitrep.
,09-09 11:42:44.605  3755  4153 V KeepSync: Connecting to GoogleApiClient
,09-09 11:42:44.606   874  1978 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 11:42:44.649  1524  3636 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-09 11:42:44.649  1524  3636 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-09 11:42:44.649  1524  3636 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 11:42:44.649  1524  3636 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:42:44.664  1751  4167 V BaseAuthAsyncOperation: access token request failed
,09-09 11:42:44.665  3755  4153 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 11:42:44.710  1524  2122 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-09 11:42:44.711  1524  2122 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-09 11:42:44.711  1524  2122 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 11:42:44.711  1524  2122 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:42:44.727  3755  4153 E KeepSync: IOException
09-09 11:42:44.727  3755  4153 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 11:42:44.727  3755  4153 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 11:42:44.727  3755  4153 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 11:42:44.727  3755  4153 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 11:42:44.727  3755  4153 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 11:42:44.727  3755  4153 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 11:42:44.727  3755  4153 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 11:42:44.727  3755  4153 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 11:42:44.727  3755  4153 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 11:42:44.727  3755  4153 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 11:42:44.727  3755  4153 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 11:42:44.727  3755  4153 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 11:42:44.727  3755  4153 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 11:42:44.727  3755  4153 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 11:42:44.727  3755  4153 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 11:42:44.727  3755  4153 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 11:42:44.727  3755  4153 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 11:42:44.727  3755  4153 E KeepSync: 	... 10 more
,09-09 11:42:44.728  3755  4153 W KeepSync: Sync result 2
,09-09 11:42:44.739   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 161503, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 11:42:44.758  3989  4160 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-09 11:42:45.343   874  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-09 11:42:46.728   874  1392 D WifiService: setWifiEnabled: false pid=3826, uid=10000
09-09 11:42:46.728   874  1392 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 11:42:46.766  1475  1475 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-09 11:42:46.773   874  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-09 11:42:46.774   874  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-09 11:42:46.774   874  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 11:42:46.774   874  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 11:42:46.787   874  1307 E native  : do suspend true
,09-09 11:42:46.802   874  1891 D DhcpClient: Clearing IP address
,09-09 11:42:46.802   372   872 D CommandListener: Setting iface cfg
,09-09 11:42:46.810   874  4144 D DhcpClient: Receive thread stopped
,09-09 11:42:46.811   372   872 D CommandListener: Clearing all IP addresses on wlan0
,09-09 11:42:46.816  1524  4166 V NativeCrypto: Read error: ssl=0x999db200: I/O error during system call, Connection timed out
,09-09 11:42:46.826   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-09 11:42:46.827   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-09 11:42:46.829   395   395 E Parcel  : Reading a NULL string not supported here.
,09-09 11:42:46.833   874  1307 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-09 11:42:46.835   874  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 11:42:46.835   874  1307 E native  : do suspend true
,09-09 11:42:46.838   874  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-09 11:42:46.845  1524  4166 V NativeCrypto: SSL shutdown failed: ssl=0x999db200: I/O error during system call, Broken pipe
,09-09 11:42:46.882   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 11:42:46.938   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-09 11:42:46.938   372   872 D CommandListener: Clearing all IP addresses on wlan0
,09-09 11:42:46.940   874  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-09 11:42:46.940   874  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 11:42:46.943   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-09 11:42:46.953  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 11:42:46.953  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 11:42:46.953  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:42:46.953  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:42:46.953  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 11:42:46.953  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 11:42:46.953  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 11:42:46.953  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 11:42:46.953  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 11:42:46.953  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 11:42:46.954  3826  3826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 11:42:46.956   874  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-09 11:42:46.958  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 11:42:46.963  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 11:42:46.963  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:42:46.963  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:42:46.963  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 11:42:46.963  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 11:42:46.963  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 11:42:46.963  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 11:42:46.963  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 11:42:46.963  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 11:42:46.964  3826  3826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 11:42:46.968  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 11:42:46.969  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 11:42:46.969  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:42:46.969  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:42:46.969  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 11:42:46.969  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 11:42:46.969  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 11:42:46.969  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 11:42:46.969  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 11:42:46.970  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 11:42:46.970  3826  3826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 11:42:46.960  1999  1999 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
09-09 11:42:46.976  1751  1751 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-09 11:42:46.978   874  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 11:42:46.981  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 11:42:46.981  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 11:42:46.981  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:42:46.981  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:42:46.981  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 11:42:46.981  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 11:42:46.981  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 11:42:46.981  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 11:42:46.981  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 11:42:46.981  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 11:42:46.981  3826  3826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 11:42:46.983  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 11:42:46.983  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 11:42:46.983  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:42:46.983  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:42:46.983  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 11:42:46.983  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 11:42:46.983  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 11:42:46.983  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 11:42:46.983  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 11:42:46.983  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 11:42:46.983  3826  3826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 11:42:46.983  2123  2315 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 11:42:46.984  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 11:42:46.984  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 11:42:46.984  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:42:46.984  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:42:46.984  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 11:42:46.984  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 11:42:46.984  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 11:42:46.984  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 11:42:46.984  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 11:42:46.984  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 11:42:46.984  3826  3826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 11:42:46.989  1751  1751 D SystemUpdateService: onCreate
09-09 11:42:46.992  1751  1751 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 11:42:46.996   874  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-09 11:42:47.014  1751  1751 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-09 11:42:47.016  1751  2427 I iu.UploadsManager: num queued entries: 0
,09-09 11:42:47.016  1751  2427 I iu.UploadsManager: num updated entries: 0
,09-09 11:42:47.017  1751  4177 I SystemUpdateService: active receiver: enabled
,09-09 11:42:47.021  1751  2427 I iu.SyncManager: NEXT; no task
,09-09 11:42:47.023  1751  4177 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 11:42:47.024  1751  1751 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 11:42:47.027  1751  1751 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 11:42:47.029  4015  4015 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 11:42:47.033  4015  4015 D SprintDMHelper: simOperator: 
,09-09 11:42:47.033  4015  4015 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 11:42:47.035  1751  4177 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-09 11:42:47.035  1751  4177 I SystemUpdateService: now status is 0 (complete)
09-09 11:42:47.035  1751  4177 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-09 11:42:47.035  1751  4177 I SystemUpdateService: file has been verified
,09-09 11:42:47.037  1751  4177 I SystemUpdateService: OTA package size = 12249756
,09-09 11:42:47.039   372   872 E Netd    : netlink response contains error (No such file or directory)
09-09 11:42:47.040   874  1309 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-09 11:42:47.072  3989  4181 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-09 11:42:47.083  1751  4177 I SystemUpdateService: showing system update notification
,09-09 11:42:47.094  1751  1751 D SystemUpdateService: onDestroy
,09-09 11:42:51.782   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ff88121:true
,09-09 11:42:51.784  3975  3975 D BluetoothAdapterState: make() - Creating AdapterState
,09-09 11:42:51.793  3975  3975 I bt_bluedroid: init
,09-09 11:42:51.794  3975  4184 I BluetoothAdapterState: Entering OffState
,09-09 11:42:51.799  3975  4185 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-09 11:42:51.800  3975  4185 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-09 11:42:51.800  3975  4185 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-09 11:42:51.800  3975  4185 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-09 11:42:51.803  3975  3975 I bt_bluedroid: get_profile_interface socket
,09-09 11:42:51.807  3975  3975 I bt_bluedroid: get_profile_interface sdp
,09-09 11:42:51.810  3975  4188 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 11:42:51.816  3975  4188 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 11:42:51.817  3975  3987 I bt_bluedroid: config_hci_snoop_log,
,09-09 11:42:51.820   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-09 11:42:51.831  3975  4184 D BluetoothAdapterState: Current state: OFF, message: 0
,09-09 11:42:51.831  3975  4184 D BluetoothAdapterProperties: Setting state to 14
,09-09 11:42:51.831  3975  4184 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-09 11:42:51.835  3975  4184 D BluetoothBondStateMachine: make
,09-09 11:42:51.838  3975  4189 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-09 11:42:51.844  3975  4184 I BluetoothAdapterState: Entering PendingCommandState
,09-09 11:42:51.845  3975  3975 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-09 11:42:51.851  3975  3975 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@222e1b2
,09-09 11:42:51.852  3975  3975 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 11:42:51.853  3975  3975 D BtGatt.GattService: Received start request. Starting profile...
,09-09 11:42:51.853  3975  3975 D BtGatt.GattService: start()
,09-09 11:42:51.854  3975  3975 I bt_bluedroid: get_profile_interface gatt
,09-09 11:42:51.855  3975  3975 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@222e1b2
,09-09 11:42:51.856  3975  3975 D BtGatt.AdvertiseManager: advertise manager created
,09-09 11:42:51.864  3975  3975 V BluetoothAdapterState: isTurningOff()=false
,09-09 11:42:51.864  3975  3975 V BluetoothAdapterState: isTurningOn()=false
09-09 11:42:51.865  3975  3975 V BluetoothAdapterState: isBleTurningOn()=true
,09-09 11:42:51.865  3975  3975 V BluetoothAdapterState: isBleTurningOff()=false
09-09 11:42:51.865  3975  4184 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-09 11:42:51.866  3975  4184 I bt_bluedroid: enable
09-09 11:42:51.866  3975  4185 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-09 11:42:51.866  3975  4185 I bt_hci  : start_up
,09-09 11:42:51.874  3975  4185 I bt_vendor: alloc value 0xb39a9189
09-09 11:42:51.874  3975  4185 I bt_vendor: init
09-09 11:42:51.874  3975  4185 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-09 11:42:51.875  3975  4185 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-09 11:42:51.984  3975  4185 D bt_hci  : start_up starting async portion
09-09 11:42:51.985  3975  4192 I bt_hci  : event_finish_startup
,09-09 11:42:51.985  3975  4192 I bt_hci_h4: hal_open
09-09 11:42:51.985  3975  4192 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-09 11:42:51.995  3975  4192 I bt_userial_vendor: device fd = 51 open
,09-09 11:42:52.025  3975  4192 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 11:42:52.057  3975  4192 D bt_hwcfg: Chipset BCM4354A2
09-09 11:42:52.057  3975  4192 D bt_hwcfg: Target name = [BCM4354A2]
,09-09 11:42:52.058  3975  4192 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-09 11:42:52.232   874  1309 D ConnectivityService: handlePromptUnvalidated 101
,09-09 11:42:52.723  3975  4192 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-09 11:42:52.725  3975  4192 D bt_hwcfg: Settlement delay -- 100 ms
09-09 11:42:52.725  3975  4192 I bt_hwcfg: Setting fw settlement delay to 100 
,09-09 11:42:52.841  3975  4192 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 11:42:52.843  3975  4192 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-09 11:42:52.872  3975  4192 I bt_hwcfg: vendor lib fwcfg completed
09-09 11:42:52.872  3975  4192 I bt_vendor: firmware callback
09-09 11:42:52.872  3975  4192 I bt_hci  : firmware_config_callback
,09-09 11:42:52.884  3975  4194 I bt_btu  : btu_task pending for preload complete event
09-09 11:42:52.884  3975  4194 I bt_btu_task: Bluetooth chip preload is complete
,09-09 11:42:52.884  3975  4194 I bt_btu  : btu_task received preload complete event
,09-09 11:42:52.894  3975  4194 I         : BTE_InitTraceLevels -- TRC_HCI
09-09 11:42:52.894  3975  4194 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-09 11:42:52.895  3975  4194 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-09 11:42:52.895  3975  4194 I         : BTE_InitTraceLevels -- TRC_AVDT
09-09 11:42:52.895  3975  4194 I         : BTE_InitTraceLevels -- TRC_AVRC
09-09 11:42:52.896  3975  4194 I         : BTE_InitTraceLevels -- TRC_A2D
09-09 11:42:52.896  3975  4194 I         : BTE_InitTraceLevels -- TRC_BNEP
09-09 11:42:52.896  3975  4194 I         : BTE_InitTraceLevels -- TRC_BTM
09-09 11:42:52.896  3975  4194 I         : BTE_InitTraceLevels -- TRC_GAP
09-09 11:42:52.897  3975  4194 I         : BTE_InitTraceLevels -- TRC_PAN
09-09 11:42:52.897  3975  4194 I         : BTE_InitTraceLevels -- TRC_SDP
09-09 11:42:52.897  3975  4194 I         : BTE_InitTraceLevels -- TRC_GATT
09-09 11:42:52.898  3975  4194 I         : BTE_InitTraceLevels -- TRC_SMP
09-09 11:42:52.898  3975  4194 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-09 11:42:52.898  3975  4194 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-09 11:42:53.033  3975  4194 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3926d9d
,09-09 11:42:53.033  3975  4194 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3926d9d 
,09-09 11:42:53.045  3975  4188 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-09 11:42:53.047  3975  4188 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-09 11:42:53.048  3975  4188 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 11:42:53.052  3975  4188 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 11:42:53.056  3975  4188 D BluetoothAdapterProperties: Scan Mode:20
,09-09 11:42:53.056  3975  4188 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 11:42:53.059  3975  4188 D bt_hci  : do_postload posting postload work item
,09-09 11:42:53.059  3975  4192 I bt_hci  : event_postload
09-09 11:42:53.059  3975  4192 I bt_vendor: sco_config_cb
09-09 11:42:53.059  3975  4192 I bt_hci  : sco_config_callback postload finished.
09-09 11:42:53.062  3975  4188 D bt_bte_conf: Device ID record 1 : primary
,09-09 11:42:53.062  3975  4188 D bt_bte_conf:   vendorId            = 000f
09-09 11:42:53.062  3975  4188 D bt_bte_conf:   vendorIdSource      = 0001
09-09 11:42:53.063  3975  4188 D bt_bte_conf:   product             = 1200
09-09 11:42:53.063  3975  4188 D bt_bte_conf:   version             = 1436
09-09 11:42:53.063  3975  4188 D bt_bte_conf:   clientExecutableURL = 
09-09 11:42:53.063  3975  4188 D bt_bte_conf:   serviceDescription  = 
,09-09 11:42:53.063  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 11:42:53.063  3975  4188 D bt_bte_conf:   documentationURL    = 
,09-09 11:42:53.064  3975  4188 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-09 11:42:53.064  3975  4185 D bt_stack_manager: event_start_up_stack finished
09-09 11:42:53.066  3975  4184 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-09 11:42:53.067  3975  4184 D BluetoothAdapterProperties: Setting state to 15
09-09 11:42:53.067  3975  4184 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-09 11:42:53.068  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 11:42:53.069  3975  4184 I BluetoothAdapterState: Entering BleOnState
09-09 11:42:53.070  3975  4192 I bt_vendor: low_power_mode_cb
09-09 11:42:53.073  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 11:42:53.075  3975  4184 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-09 11:42:53.076  3975  4184 D BluetoothAdapterProperties: Setting state to 11
,09-09 11:42:53.076  3975  4184 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-09 11:42:53.085  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 11:42:53.086  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 11:42:53.089  3975  3975 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@222e1b2
09-09 11:42:53.089  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 11:42:53.090  3975  3975 D HeadsetService: Received start request. Starting profile...
,09-09 11:42:53.093  3975  3975 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-09 11:42:53.094  3975  3975 D HeadsetStateMachine: make
,09-09 11:42:53.101  3975  4184 I BluetoothAdapterState: Entering PendingCommandState
,09-09 11:42:53.103  3975  3975 D HeadsetStateMachine: max_hf_connections = 1
,09-09 11:42:53.103  3975  3975 I bt_bluedroid: get_profile_interface handsfree
,09-09 11:42:53.103  3975  4188 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-09 11:42:53.103  3975  4188 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-09 11:42:53.111  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 11:42:53.111  3975  3975 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@222e1b2
,09-09 11:42:53.111  3975  3975 D A2dpService: Received start request. Starting profile...
09-09 11:42:53.112  3975  3975 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-09 11:42:53.112  3975  3975 I bt_bluedroid: get_profile_interface avrcp
,09-09 11:42:53.121  3975  3975 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-09 11:42:53.121  3975  3975 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-09 11:42:53.122  3975  3975 D A2dpStateMachine: make
,09-09 11:42:53.124  3975  3975 I bt_bluedroid: get_profile_interface a2dp
,09-09 11:42:53.125  3975  4188 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-09 11:42:53.127  3975  4204 D A2dpStateMachine: Enter Disconnected: -2
,09-09 11:42:53.128  3975  3975 I BluetoothHidServiceJni: classInitNative: succeeds
,09-09 11:42:53.129  3975  3975 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@222e1b2
,09-09 11:42:53.130  3975  3975 D HidService: Received start request. Starting profile...
,09-09 11:42:53.130  3975  3975 I bt_bluedroid: get_profile_interface hidhost
09-09 11:42:53.130  3975  3975 D HidService: setHidService(): set to: null
09-09 11:42:53.130  3975  4188 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39083e5
09-09 11:42:53.130  3975  4188 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-09 11:42:53.130  3923  3923 D BluetoothInputDevice: Proxy object connected
,09-09 11:42:53.131  3975  3975 I BluetoothHealthServiceJni: classInitNative: succeeds
09-09 11:42:53.132  3975  3975 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@222e1b2
09-09 11:42:53.132  3975  3975 D HealthService: Received start request. Starting profile...
,09-09 11:42:53.133  3923  3923 D HidProfile: Bluetooth service connected
,09-09 11:42:53.135  3975  3975 I bt_bluedroid: get_profile_interface health
,09-09 11:42:53.136  3975  3975 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-09 11:42:53.136  3975  3975 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@222e1b2
,09-09 11:42:53.138  3975  3975 D PanService: Received start request. Starting profile...
,09-09 11:42:53.138  3975  3975 D BluetoothPanServiceJni: initializeNative(L110): pan
09-09 11:42:53.138  3975  3975 I bt_bluedroid: get_profile_interface pan
,09-09 11:42:53.140  3975  4188 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-09 11:42:53.141  3923  3923 D BluetoothPan: BluetoothPAN Proxy object connected
,09-09 11:42:53.141  3975  3975 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@222e1b2
09-09 11:42:53.142  3923  3923 D PanProfile: Bluetooth service connected
09-09 11:42:53.143  3923  3923 D BluetoothMap: Proxy object connected
,09-09 11:42:53.143  3975  3975 D BluetoothMapService: Received start request. Starting profile...
09-09 11:42:53.143  3975  3975 D BluetoothMapService: start()
09-09 11:42:53.143  3923  3923 D MapProfile: Bluetooth service connected
09-09 11:42:53.143  3923  3923 D BluetoothMap: getConnectedDevices(),
09-09 11:42:53.144  3923  3923 D BluetoothMap: Bluetooth is Not enabled
,09-09 11:42:53.145  3975  3975 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-09 11:42:53.145  3975  3975 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-09 11:42:53.145  3975  3975 D BluetoothMapAppObserver: createReceiver()
09-09 11:42:53.146  3975  3975 D BluetoothMapAppObserver: initObservers()
09-09 11:42:53.146  3975  3975 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-09 11:42:53.154  3975  3975 V BluetoothAdapterState: isTurningOff()=false
,09-09 11:42:53.154  3975  3975 V BluetoothAdapterState: isTurningOn()=true
09-09 11:42:53.155  3975  3975 V BluetoothAdapterState: isBleTurningOn()=false
09-09 11:42:53.155  3975  3975 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 11:42:53.155  3975  4202 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-09 11:42:53.158  3975  3975 V BluetoothAdapterState: isTurningOff()=false
,09-09 11:42:53.158  3975  3975 V BluetoothAdapterState: isTurningOn()=true
09-09 11:42:53.158  3975  3975 V BluetoothAdapterState: isBleTurningOn()=false
09-09 11:42:53.159  3975  3975 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 11:42:53.159  3975  3975 V BluetoothAdapterState: isTurningOff()=false
09-09 11:42:53.160  3975  3975 V BluetoothAdapterState: isTurningOn()=true
09-09 11:42:53.160  3975  3975 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 11:42:53.160  3975  3975 V BluetoothAdapterState: isBleTurningOff()=false
09-09 11:42:53.161  3975  3975 V BluetoothAdapterState: isTurningOff()=false
09-09 11:42:53.161  3975  3975 V BluetoothAdapterState: isTurningOn()=true,
09-09 11:42:53.161  3975  3975 V BluetoothAdapterState: isBleTurningOn()=false
09-09 11:42:53.161  3975  3975 V BluetoothAdapterState: isBleTurningOff()=false,
09-09 11:42:53.161  3975  3975 V BluetoothAdapterState: isTurningOff()=false
09-09 11:42:53.162  3975  3975 V BluetoothAdapterState: isTurningOn()=true
,09-09 11:42:53.162  3975  3975 V BluetoothAdapterState: isBleTurningOn()=false
09-09 11:42:53.162  3975  3975 V BluetoothAdapterState: isBleTurningOff()=false
09-09 11:42:53.162  3975  3975 V BluetoothAdapterState: isTurningOff()=false,
09-09 11:42:53.162  3975  3975 V BluetoothAdapterState: isTurningOn()=true
09-09 11:42:53.162  3975  3975 V BluetoothAdapterState: isBleTurningOn()=false
09-09 11:42:53.162  3975  3975 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 11:42:53.162  3975  4184 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-09 11:42:53.163  3975  4184 D BluetoothAdapterProperties: ScanMode =  20
,09-09 11:42:53.163  3975  4184 D BluetoothAdapterProperties: State =  11
09-09 11:42:53.165  3975  4188 D BluetoothAdapterProperties: Scan Mode:21
09-09 11:42:53.166  3975  4184 D BluetoothAdapterProperties: Setting state to 12
,09-09 11:42:53.166  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 11:42:53.166  3975  4188 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 11:42:53.166  3975  4184 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-09 11:42:53.168  1349  2029 D BluetoothPan: onBluetoothStateChange on: true
09-09 11:42:53.168  3975  4184 I BluetoothAdapterState: Entering OnState
09-09 11:42:53.170  1349  1349 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 11:42:53.170  1349  1349 D PanProfile: Bluetooth service connected
09-09 11:42:53.170   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 11:42:53.170  3923  3933 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-09 11:42:53.171  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 11:42:53.171  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:42:53.171  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:42:53.171  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 11:42:53.171  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 11:42:53.171  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 11:42:53.171  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 11:42:53.171  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 11:42:53.171  1927  1939 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 11:42:53.172  3975  3975 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-09 11:42:53.172  3923  3934 D BluetoothPan: onBluetoothStateChange on: true
,09-09 11:42:53.172   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 11:42:53.172  3975  3975 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-09 11:42:53.173  1349  1369 D BluetoothPbap: onBluetoothStateChange: up=true
,09-09 11:42:53.173  3826  3826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 11:42:53.174  3975  3975 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 11:42:53.174   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 11:42:53.175  1349  1362 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 11:42:53.176  1349  1349 D BluetoothInputDevice: Proxy object connected
,09-09 11:42:53.176  1349  1349 D HidProfile: Bluetooth service connected
09-09 11:42:53.177  1349  1369 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 11:42:53.177  3975  3975 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 11:42:53.179  3923  3933 D BluetoothMap: onBluetoothStateChange: up=true
,09-09 11:42:53.179  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 11:42:53.179  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:42:53.179  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:42:53.179  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 11:42:53.179  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 11:42:53.179  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 11:42:53.179  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 11:42:53.179  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 11:42:53.181  3826  3826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 11:42:53.179  3975  3975 D ObexServerSockets: Succeed to create listening sockets 
09-09 11:42:53.179  1349  1362 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 11:42:53.181  3975  3975 D ObexServerSockets0: startAccept()
09-09 11:42:53.181   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 11:42:53.181  3975  3975 D ObexServerSockets0: prepareForNewConnect()
09-09 11:42:53.182  3923  3934 D BluetoothPbap: onBluetoothStateChange: up=true
,09-09 11:42:53.183  1349  2033 D BluetoothMap: onBluetoothStateChange: up=true
09-09 11:42:53.184  1349  1349 D BluetoothMap: Proxy object connected
09-09 11:42:53.184  1349  1349 D MapProfile: Bluetooth service connected
09-09 11:42:53.184  1349  1349 D BluetoothMap: getConnectedDevices()
09-09 11:42:53.185   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
09-09 11:42:53.188  3923  3923 D LocalBluetoothProfileManager: Adding local A2DP profile
09-09 11:42:53.189  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 11:42:53.189  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:42:53.189  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:42:53.189  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 11:42:53.189  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 11:42:53.189  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 11:42:53.189  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 11:42:53.189  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 11:42:53.191  3975  3975 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-09 11:42:53.191  3975  4210 D ObexServerSockets0: Accepting socket connection...
09-09 11:42:53.191  3826  3826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 11:42:53.192  3975  3975 D BluetoothSdpJni: SDP Create record success - handle: 0
09-09 11:42:53.193  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 11:42:53.193  3923  3923 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-09 11:42:53.194  3975  4211 D ObexServerSockets0: Accepting socket connection...
09-09 11:42:53.194   874   874 D BluetoothA2dp: Proxy object connected
09-09 11:42:53.194  1349  1349 D BluetoothA2dp: Proxy object connected
09-09 11:42:53.194  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 11:42:53.196  3975  3975 D BluetoothMapService: onReceive
09-09 11:42:53.196  3975  3975 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 11:42:53.197  3975  3975 D BluetoothMapService: STATE_ON
09-09 11:42:53.202  3923  3923 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-09 11:42:53.205  3923  3923 D BluetoothA2dp: Proxy object connected
,09-09 11:42:53.211  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 11:42:53.214  3923  3923 D DockEventReceiver: finishStartingService: stopping service
,09-09 11:42:53.219  3923  3923 D BluetoothPbap: Proxy object connected
,09-09 11:42:53.219  1349  1349 D BluetoothPbap: Proxy object connected
09-09 11:42:53.219  1349  1349 D PbapServerProfile: Bluetooth service connected
09-09 11:42:53.219  3923  3923 D PbapServerProfile: Bluetooth service connected
,09-09 11:42:53.227  3975  3975 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-09 11:42:53.227  3975  3975 D ObexServerSockets0: prepareForNewConnect()
,09-09 11:42:53.231  3975  4215 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 11:42:53.246  3975  4219 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 11:42:53.247  3975  4219 I BtOppRfcommListener: Accept thread started.
,09-09 11:42:53.272  1927  2066 D BluetoothHeadset: Proxy object connected
09-09 11:42:53.272  1927  1940 D BluetoothHeadset: Proxy object connected
09-09 11:42:53.272   874   874 D BluetoothHeadset: Proxy object connected
09-09 11:42:53.272   874   874 D BluetoothHeadset: Proxy object connected
,09-09 11:42:53.273  1349  1369 D BluetoothHeadset: Proxy object connected
,09-09 11:42:53.273   874   874 D BluetoothHeadset: Proxy object connected
09-09 11:42:53.273  1349  1349 D HeadsetProfile: Bluetooth service connected
09-09 11:42:53.274   874   891 D BluetoothHeadset: Proxy object connected
,09-09 11:42:53.282  1349  1362 D BluetoothHeadset: Proxy object connected
,09-09 11:42:53.282   874   891 D BluetoothHeadset: Proxy object connected
09-09 11:42:53.282  1349  1349 D HeadsetProfile: Bluetooth service connected
,09-09 11:42:53.297  3923  3933 D BluetoothHeadset: Proxy object connected
,09-09 11:42:53.297  3923  3923 D HeadsetProfile: Bluetooth service connected
,09-09 11:42:55.977  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:42:55.989  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:42:55.993  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:42:56.043  1524  2307 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-09 11:42:56.044  1524  2307 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-09 11:42:56.044  1524  2307 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 11:42:56.045  1524  2307 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:42:56.096  3521  3521 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-09 11:42:56.097  3521  3521 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-09 11:42:56.098  3521  3521 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-09 11:42:56.746  3975  4184 D BluetoothAdapterState: Current state: ON, message: 23
,09-09 11:42:56.746  3975  4184 D BluetoothAdapterProperties: Setting state to 13
09-09 11:42:56.746  3975  4184 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-09 11:42:56.748  3975  4184 D BluetoothAdapterProperties: onBluetoothDisable()
09-09 11:42:56.751  3975  4184 I BluetoothAdapterState: Entering PendingCommandState
,09-09 11:42:56.759  3975  3975 D BluetoothMapService: onReceive
,09-09 11:42:56.759  3975  3975 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-09 11:42:56.760  3975  3975 D BluetoothMapService: STATE_TURNING_OFF
,09-09 11:42:56.761  3975  3975 D BluetoothMapService: MAP Service closeService in
09-09 11:42:56.762  3975  3975 D BluetoothMapMasInstance0: MAP Service shutdown
,09-09 11:42:56.762  3975  3975 D ObexServerSockets0: shutdown(block = true)
09-09 11:42:56.763  3975  4210 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-09 11:42:56.766  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 11:42:56.767  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 11:42:56.767  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:42:56.767  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:42:56.767  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 11:42:56.767  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 11:42:56.767  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 11:42:56.767  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 11:42:56.767  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 11:42:56.770  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 11:42:56.770  3826  3826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 11:42:56.772  3975  3975 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 11:42:56.773  3975  4211 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-09 11:42:56.774  3975  4188 D BluetoothAdapterProperties: Scan Mode:20
,09-09 11:42:56.775  3975  4184 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-09 11:42:56.777  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 11:42:56.777  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 11:42:56.777  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:42:56.777  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:42:56.777  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 11:42:56.777  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 11:42:56.777  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 11:42:56.777  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 11:42:56.777  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 11:42:56.777  3923  3923 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 11:42:56.778  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 11:42:56.778  3826  3826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 11:42:56.779  3975  4197 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-09 11:42:56.779  3975  3975 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 11:42:56.781  3975  3975 D HeadsetService: Received stop request...Stopping profile...
09-09 11:42:56.781  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 11:42:56.781  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 11:42:56.781  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:42:56.781  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:42:56.781  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 11:42:56.781  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 11:42:56.781  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 11:42:56.781  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 11:42:56.781  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 11:42:56.782  3826  3826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 11:42:56.782  3826  3826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 11:42:56.785  1927  2116 D BluetoothHeadset: Proxy object disconnected
09-09 11:42:56.785  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 11:42:56.785  3923  3934 D BluetoothHeadset: Proxy object disconnected
09-09 11:42:56.785   874   874 D BluetoothHeadset: Proxy object disconnected
09-09 11:42:56.786   874   874 D BluetoothHeadset: Proxy object disconnected
09-09 11:42:56.786  1349  1369 D BluetoothHeadset: Proxy object disconnected
09-09 11:42:56.786  3975  3975 D A2dpService: Received stop request...Stopping profile...
09-09 11:42:56.786  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 11:42:56.786   874   874 D BluetoothHeadset: Proxy object disconnected
09-09 11:42:56.786  1349  1349 D HeadsetProfile: Bluetooth service disconnected
09-09 11:42:56.787  3975  4204 D A2dpStateMachine: Exit Disconnected: -1
,09-09 11:42:56.788  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 11:42:56.790   874   874 D BluetoothA2dp: Proxy object disconnected
09-09 11:42:56.790  1349  1349 D BluetoothA2dp: Proxy object disconnected
09-09 11:42:56.790  3975  3975 I BtOppRfcommListener: stopping Accept Thread
,09-09 11:42:56.791  3975  4219 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 11:42:56.791  3975  4219 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-09 11:42:56.792  3975  3975 D HidService: Received stop request...Stopping profile...
09-09 11:42:56.792  3975  3975 D HidService: Stopping Bluetooth HidService
09-09 11:42:56.793  3975  3975 V BluetoothAdapterState: isTurningOff()=true
09-09 11:42:56.793  1349  1349 D BluetoothInputDevice: Proxy object disconnected
09-09 11:42:56.793  1349  1349 D HidProfile: Bluetooth service disconnected
09-09 11:42:56.793  3975  3975 V BluetoothAdapterState: isTurningOn()=false
09-09 11:42:56.794  3975  3975 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 11:42:56.794  3975  3975 V BluetoothAdapterState: isBleTurningOff()=false
09-09 11:42:56.794  3975  3975 D HealthService: Received stop request...Stopping profile...
09-09 11:42:56.795  3923  3923 D DockEventReceiver: finishStartingService: stopping service
09-09 11:42:56.796  3975  3975 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 11:42:56.797  3975  4188 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-09 11:42:56.797  3975  4194 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 11:42:56.797  3975  4194 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 11:42:56.797  3923  3923 D HeadsetProfile: Bluetooth service disconnected
,09-09 11:42:56.797  3975  4194 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 11:42:56.798  3975  3975 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 11:42:56.798  3975  4188 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-09 11:42:56.797  3923  3923 D BluetoothA2dp: Proxy object disconnected
09-09 11:42:56.798  3923  3923 D BluetoothInputDevice: Proxy object disconnected
09-09 11:42:56.798  3923  3923 D HidProfile: Bluetooth service disconnected
,09-09 11:42:56.798  3975  3975 D PanService: Received stop request...Stopping profile...
09-09 11:42:56.802  1349  1349 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 11:42:56.802  1349  1349 D PanProfile: Bluetooth service disconnected
09-09 11:42:56.802  3923  3923 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 11:42:56.802  3923  3923 D PanProfile: Bluetooth service disconnected
09-09 11:42:56.803  3975  3975 D BluetoothMapService: Received stop request...Stopping profile...
09-09 11:42:56.803  3975  3975 D BluetoothMapService: stop()
,09-09 11:42:56.803  3975  3975 D BluetoothMapAppObserver: deinitObservers()
09-09 11:42:56.803  3975  3975 D BluetoothMapAppObserver: removeReceiver()
09-09 11:42:56.805  1349  1349 D BluetoothMap: Proxy object disconnected
09-09 11:42:56.805  1349  1349 D MapProfile: Bluetooth service disconnected
09-09 11:42:56.805  3923  3923 D BluetoothMap: Proxy object disconnected
09-09 11:42:56.806  3923  3923 D MapProfile: Bluetooth service disconnected
,09-09 11:42:56.808  3975  3975 V BluetoothAdapterState: isTurningOff()=true
,09-09 11:42:56.808  3975  3975 V BluetoothAdapterState: isTurningOn()=false
,09-09 11:42:56.808  3975  3975 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 11:42:56.808  3975  3975 V BluetoothAdapterState: isBleTurningOff()=false
09-09 11:42:56.809  3975  4188 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-09 11:42:56.809  3975  4194 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 11:42:56.809  3975  4194 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 11:42:56.810  3975  4194 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 11:42:56.810  3975  4194 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-09 11:42:56.810  3975  4194 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 11:42:56.810  3975  4194 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-09 11:42:56.810  3975  3975 V BluetoothAdapterState: isTurningOff()=true
,09-09 11:42:56.810  3975  3975 V BluetoothAdapterState: isTurningOn()=false
09-09 11:42:56.811  3975  3975 V BluetoothAdapterState: isBleTurningOn()=false
09-09 11:42:56.810  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 11:42:56.811  3975  3975 V BluetoothAdapterState: isBleTurningOff()=false
09-09 11:42:56.811  3975  3975 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-09 11:42:56.811  3975  3975 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-09 11:42:56.815  3975  4188 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-09 11:42:56.818  3975  3975 V BluetoothAdapterState: isTurningOff()=true
09-09 11:42:56.818  3975  3975 V BluetoothAdapterState: isTurningOn()=false
09-09 11:42:56.818  3975  3975 V BluetoothAdapterState: isBleTurningOn()=false
09-09 11:42:56.818  3975  3975 V BluetoothAdapterState: isBleTurningOff()=false
09-09 11:42:56.819  3975  3975 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-09 11:42:56.819  3975  4188 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-09 11:42:56.819  3975  3975 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 11:42:56.819  3975  3975 V BluetoothAdapterState: isTurningOff()=true
09-09 11:42:56.820  3975  3975 V BluetoothAdapterState: isTurningOn()=false
,09-09 11:42:56.820  3975  3975 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 11:42:56.820  3975  3975 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 11:42:56.820  3975  3975 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 11:42:56.820  3975  3975 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-09 11:42:56.821  3975  3975 D BluetoothMapService: MAP Service closeService in
,09-09 11:42:56.821  3975  3975 V BluetoothAdapterState: isTurningOff()=true
09-09 11:42:56.821  3975  3975 V BluetoothAdapterState: isTurningOn()=false
09-09 11:42:56.821  3975  3975 V BluetoothAdapterState: isBleTurningOn()=false
09-09 11:42:56.821  3975  3975 V BluetoothAdapterState: isBleTurningOff()=false
09-09 11:42:56.822  3975  3975 D BluetoothMapService: cleanup()
,09-09 11:42:56.822  3975  3975 D BluetoothMapService: MAP Service closeService in
09-09 11:42:56.824  1349  1349 D BluetoothPbap: Proxy object disconnected
09-09 11:42:56.824  1349  1349 D PbapServerProfile: Bluetooth service disconnected
,09-09 11:42:56.824  3975  4184 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-09 11:42:56.824  3975  4184 D BluetoothAdapterProperties: Setting state to 15
09-09 11:42:56.825  3975  4184 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-09 11:42:56.825  3923  3923 D BluetoothPbap: Proxy object disconnected
09-09 11:42:56.827  3923  3923 D PbapServerProfile: Bluetooth service disconnected
09-09 11:42:56.826  3975  4184 I BluetoothAdapterState: Entering BleOnState
09-09 11:42:56.826  1349  2029 D BluetoothPan: onBluetoothStateChange on: false
09-09 11:42:56.828   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 11:42:56.828  3923  3933 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-09 11:42:56.829  1927  1939 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 11:42:56.829  3923  3934 D BluetoothPan: onBluetoothStateChange on: false
09-09 11:42:56.829   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 11:42:56.830  1349  1369 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 11:42:56.830   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 11:42:56.830  3923  3933 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 11:42:56.831  1349  1362 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-09 11:42:56.831  1349  2033 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 11:42:56.832  3923  3934 D BluetoothMap: onBluetoothStateChange: up=false
09-09 11:42:56.833  3923  3933 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 11:42:56.834  1349  2029 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 11:42:56.835   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 11:42:56.835  3923  3934 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 11:42:56.836  1349  1369 D BluetoothMap: onBluetoothStateChange: up=false
09-09 11:42:56.837  3975  4184 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-09 11:42:56.837  3975  4184 D BluetoothAdapterProperties: Setting state to 16
09-09 11:42:56.837  3975  4184 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-09 11:42:56.837  3975  4184 D BluetoothAdapterProperties: onBleDisable
09-09 11:42:56.838  3975  4184 I BluetoothAdapterState: Entering PendingCommandState
09-09 11:42:56.838  3975  4185 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-09 11:42:56.839  3975  4194 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms,
09-09 11:42:56.839  3975  4194 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-09 11:42:56.842  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 11:42:56.843  3923  3923 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-09 11:42:56.844  3975  4188 D BluetoothAdapterProperties: Scan Mode:20
09-09 11:42:56.844  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 11:42:56.845  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 11:42:56.848  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 11:42:56.850  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 11:42:56.851  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 11:42:56.851  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 11:42:56.860  3923  3923 D DockEventReceiver: finishStartingService: stopping service
,09-09 11:42:57.051  3975  4188 I bt_hci  : shut_down
,09-09 11:42:57.069  3975  4192 I bt_vendor: low_power_mode_cb
,09-09 11:42:57.075  3975  4192 D bt_hwcfg: hw_epilog_process
,09-09 11:42:57.091  3975  4192 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-09 11:42:57.091  3975  4192 I bt_vendor: epilog_cb
,09-09 11:42:57.091  3975  4192 I bt_hci  : epilog_finished_callback
,09-09 11:42:57.108  3975  4188 I bt_hci_h4: hal_close
,09-09 11:42:57.110  3975  4188 I bt_userial_vendor: device fd = 51 close
,09-09 11:42:57.238  3975  4185 D bt_stack_manager: event_shut_down_stack finished.
,09-09 11:42:57.239  3975  4184 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-09 11:42:57.245  3975  4184 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-09 11:42:57.245  3975  3975 D BtGatt.DebugUtils: handleDebugAction() action=null
09-09 11:42:57.246  3975  3975 D BtGatt.GattService: Received stop request...Stopping profile...
09-09 11:42:57.247  3975  3975 D BtGatt.GattService: stop()
,09-09 11:42:57.247  3975  3975 D BtGatt.AdvertiseManager: advertise clients cleared
,09-09 11:42:57.252  3975  3975 V BluetoothAdapterState: isTurningOff()=false
,09-09 11:42:57.252  3975  3975 V BluetoothAdapterState: isTurningOn()=false
09-09 11:42:57.252  3975  3975 V BluetoothAdapterState: isBleTurningOn()=false
09-09 11:42:57.253  3975  3975 V BluetoothAdapterState: isBleTurningOff()=true
09-09 11:42:57.253  3975  4184 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-09 11:42:57.254  3975  4184 D BluetoothAdapterProperties: Setting state to 10
,09-09 11:42:57.254  3975  4184 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-09 11:42:57.257  3975  4184 I BluetoothAdapterState: Entering OffState
09-09 11:42:57.257   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-09 11:42:57.286  3975  3975 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-09 11:42:57.287  3975  3975 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-09 11:42:57.287  3975  4185 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-09 11:42:57.299  3975  3975 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-09 11:42:57.300  3975  4185 D bt_stack_manager: event_clean_up_stack finished.
,09-09 11:42:57.303  3975  3975 I art     : System.exit called, status: 0
,09-09 11:42:57.303  3975  3975 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-09 11:42:57.344   874  3188 I ActivityManager: Process com.android.bluetooth (pid 3975) has died
,09-09 11:43:01.742  3826  3876 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 11:43:01.743  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 11:43:01.748  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 11:43:01.748  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e13076 removed from the list
09-09 11:43:01.748  3826  3876 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 11:43:01.749  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:43:01.749  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:43:01.752  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 11:43:01.752  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e0bf2e4 added. We now have 4 listener(s)
09-09 11:43:01.752  3826  3876 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 11:43:01.754  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:43:01.755  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e0bf2e4 removed from the list
09-09 11:43:01.755  3826  3876 D io.jxcore.node.ConnectivityMonitor: stop
09-09 11:43:01.755  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 11:43:01.755  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:43:01.759  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 11:43:01.759  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f70134d added. We now have 4 listener(s)
09-09 11:43:01.759  3826  3876 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 11:43:06.772  3826  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 11:43:06.822   874   891 I ActivityManager: Start proc 4231:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-09 11:43:06.976  4231  4231 D AdapterServiceConfig: Adding HeadsetService
,09-09 11:43:06.976  4231  4231 D AdapterServiceConfig: Adding A2dpService
09-09 11:43:06.976  4231  4231 D AdapterServiceConfig: Adding HidService
09-09 11:43:06.977  4231  4231 D AdapterServiceConfig: Adding HealthService
09-09 11:43:06.977  4231  4231 D AdapterServiceConfig: Adding PanService
09-09 11:43:06.977  4231  4231 D AdapterServiceConfig: Adding GattService
09-09 11:43:06.977  4231  4231 D AdapterServiceConfig: Adding BluetoothMapService
,09-09 11:43:06.993   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6802a8c:true
09-09 11:43:06.993  4231  4231 D BluetoothAdapterState: make() - Creating AdapterState
,09-09 11:43:06.998  4231  4231 I bt_bluedroid: init
,09-09 11:43:06.999  4231  4243 I BluetoothAdapterState: Entering OffState
,09-09 11:43:07.004  4231  4244 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-09 11:43:07.005  4231  4244 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-09 11:43:07.005  4231  4244 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-09 11:43:07.005  4231  4244 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-09 11:43:07.008  4231  4231 I bt_bluedroid: get_profile_interface socket,
09-09 11:43:07.011  4231  4247 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 11:43:07.012  4231  4247 D BluetoothAdapterProperties: Name is: Nexus 6
09-09 11:43:07.013  4231  4231 I bt_bluedroid: get_profile_interface sdp
,09-09 11:43:07.020  4231  4242 I bt_bluedroid: config_hci_snoop_log
,09-09 11:43:07.023   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-09 11:43:07.040  4231  4243 D BluetoothAdapterState: Current state: OFF, message: 0
,09-09 11:43:07.040  4231  4243 D BluetoothAdapterProperties: Setting state to 14
,09-09 11:43:07.041  4231  4243 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-09 11:43:07.046  4231  4243 D BluetoothBondStateMachine: make
,09-09 11:43:07.052  4231  4248 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-09 11:43:07.062  4231  4243 I BluetoothAdapterState: Entering PendingCommandState
,09-09 11:43:07.064  4231  4231 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-09 11:43:07.073  4231  4231 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@222e1b2
,09-09 11:43:07.075  4231  4231 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 11:43:07.078  4231  4231 D BtGatt.GattService: Received start request. Starting profile...
,09-09 11:43:07.078  4231  4231 D BtGatt.GattService: start()
,09-09 11:43:07.079  4231  4231 I bt_bluedroid: get_profile_interface gatt
,09-09 11:43:07.081  4231  4231 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@222e1b2
,09-09 11:43:07.082  4231  4231 D BtGatt.AdvertiseManager: advertise manager created,
,09-09 11:43:07.099  4231  4231 V BluetoothAdapterState: isTurningOff()=false
09-09 11:43:07.100  4231  4231 V BluetoothAdapterState: isTurningOn()=false
09-09 11:43:07.100  4231  4231 V BluetoothAdapterState: isBleTurningOn()=true
09-09 11:43:07.100  4231  4231 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 11:43:07.102  4231  4243 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-09 11:43:07.103  4231  4243 I bt_bluedroid: enable
09-09 11:43:07.103  4231  4244 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-09 11:43:07.104  4231  4244 I bt_hci  : start_up
,09-09 11:43:07.124  4231  4244 I bt_vendor: alloc value 0xb39f9189
09-09 11:43:07.125  4231  4244 I bt_vendor: init
,09-09 11:43:07.125  4231  4244 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-09 11:43:07.125  4231  4244 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-09 11:43:07.234  4231  4244 D bt_hci  : start_up starting async portion
,09-09 11:43:07.234  4231  4251 I bt_hci  : event_finish_startup
,09-09 11:43:07.235  4231  4251 I bt_hci_h4: hal_open
09-09 11:43:07.235  4231  4251 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-09 11:43:07.247  4231  4251 I bt_userial_vendor: device fd = 51 open
,09-09 11:43:07.276  4231  4251 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 11:43:07.307  4231  4251 D bt_hwcfg: Chipset BCM4354A2
,09-09 11:43:07.307  4231  4251 D bt_hwcfg: Target name = [BCM4354A2]
09-09 11:43:07.308  4231  4251 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-09 11:43:08.152  4231  4251 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-09 11:43:08.154  4231  4251 D bt_hwcfg: Settlement delay -- 100 ms
09-09 11:43:08.154  4231  4251 I bt_hwcfg: Setting fw settlement delay to 100 
,09-09 11:43:08.272  4231  4251 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 11:43:08.274  4231  4251 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-09 11:43:08.302  4231  4251 I bt_hwcfg: vendor lib fwcfg completed
09-09 11:43:08.302  4231  4251 I bt_vendor: firmware callback
09-09 11:43:08.302  4231  4251 I bt_hci  : firmware_config_callback
,09-09 11:43:08.316  4231  4253 I bt_btu  : btu_task pending for preload complete event
09-09 11:43:08.316  4231  4253 I bt_btu_task: Bluetooth chip preload is complete
09-09 11:43:08.316  4231  4253 I bt_btu  : btu_task received preload complete event
,09-09 11:43:08.326  4231  4253 I         : BTE_InitTraceLevels -- TRC_HCI
09-09 11:43:08.327  4231  4253 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-09 11:43:08.327  4231  4253 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-09 11:43:08.327  4231  4253 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-09 11:43:08.328  4231  4253 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-09 11:43:08.328  4231  4253 I         : BTE_InitTraceLevels -- TRC_A2D
09-09 11:43:08.328  4231  4253 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-09 11:43:08.328  4231  4253 I         : BTE_InitTraceLevels -- TRC_BTM
09-09 11:43:08.329  4231  4253 I         : BTE_InitTraceLevels -- TRC_GAP
09-09 11:43:08.329  4231  4253 I         : BTE_InitTraceLevels -- TRC_PAN
,09-09 11:43:08.329  4231  4253 I         : BTE_InitTraceLevels -- TRC_SDP
09-09 11:43:08.329  4231  4253 I         : BTE_InitTraceLevels -- TRC_GATT
09-09 11:43:08.330  4231  4253 I         : BTE_InitTraceLevels -- TRC_SMP
,09-09 11:43:08.330  4231  4253 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-09 11:43:08.330  4231  4253 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-09 11:43:08.485  4231  4253 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3976d9d
,09-09 11:43:08.485  4231  4253 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3976d9d 
,09-09 11:43:08.518  4231  4247 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-09 11:43:08.520  4231  4247 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-09 11:43:08.520  4231  4247 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 11:43:08.523  4231  4247 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 11:43:08.526  4231  4247 D BluetoothAdapterProperties: Scan Mode:20
,09-09 11:43:08.527  4231  4247 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-09 11:43:08.528  4231  4247 D bt_hci  : do_postload posting postload work item
09-09 11:43:08.528  4231  4251 I bt_hci  : event_postload,
,09-09 11:43:08.528  4231  4251 I bt_vendor: sco_config_cb
,09-09 11:43:08.528  4231  4251 I bt_hci  : sco_config_callback postload finished.
,09-09 11:43:08.533  4231  4247 D bt_bte_conf: Device ID record 1 : primary
,09-09 11:43:08.533  4231  4247 D bt_bte_conf:   vendorId            = 000f
,09-09 11:43:08.533  4231  4247 D bt_bte_conf:   vendorIdSource      = 0001
,09-09 11:43:08.533  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 11:43:08.534  4231  4247 D bt_bte_conf:   product             = 1200
09-09 11:43:08.534  4231  4247 D bt_bte_conf:   version             = 1436
09-09 11:43:08.534  4231  4247 D bt_bte_conf:   clientExecutableURL = 
09-09 11:43:08.535  4231  4247 D bt_bte_conf:   serviceDescription  = 
,09-09 11:43:08.535  4231  4247 D bt_bte_conf:   documentationURL    = 
09-09 11:43:08.535  4231  4247 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-09 11:43:08.536  4231  4244 D bt_stack_manager: event_start_up_stack finished
,09-09 11:43:08.538  4231  4251 I bt_vendor: low_power_mode_cb
09-09 11:43:08.538  4231  4243 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-09 11:43:08.539  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 11:43:08.539  4231  4243 D BluetoothAdapterProperties: Setting state to 15
09-09 11:43:08.539  4231  4243 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-09 11:43:08.541  4231  4243 I BluetoothAdapterState: Entering BleOnState
,09-09 11:43:08.546  4231  4243 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-09 11:43:08.546  4231  4243 D BluetoothAdapterProperties: Setting state to 11
09-09 11:43:08.546  4231  4243 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-09 11:43:08.560  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 11:43:08.561  4231  4231 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@222e1b2
09-09 11:43:08.562  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 11:43:08.562  4231  4231 D HeadsetService: Received start request. Starting profile...
,09-09 11:43:08.566  4231  4231 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-09 11:43:08.566  4231  4231 D HeadsetStateMachine: make
,09-09 11:43:08.579  4231  4231 D HeadsetStateMachine: max_hf_connections = 1
,09-09 11:43:08.579  4231  4231 I bt_bluedroid: get_profile_interface handsfree
09-09 11:43:08.580  4231  4247 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-09 11:43:08.580  4231  4247 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-09 11:43:08.586  4231  4243 I BluetoothAdapterState: Entering PendingCommandState
,09-09 11:43:08.589  4231  4231 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@222e1b2
,09-09 11:43:08.590  4231  4231 D A2dpService: Received start request. Starting profile...
09-09 11:43:08.591  4231  4231 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-09 11:43:08.592  4231  4231 I bt_bluedroid: get_profile_interface avrcp
,09-09 11:43:08.607  4231  4231 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-09 11:43:08.608  4231  4231 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-09 11:43:08.608  4231  4231 D A2dpStateMachine: make
,09-09 11:43:08.610  4231  4231 I bt_bluedroid: get_profile_interface a2dp
,09-09 11:43:08.611  4231  4247 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-09 11:43:08.615  4231  4262 D A2dpStateMachine: Enter Disconnected: -2
,09-09 11:43:08.618  4231  4231 I BluetoothHidServiceJni: classInitNative: succeeds
,09-09 11:43:08.618  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 11:43:08.618  4231  4231 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@222e1b2
,09-09 11:43:08.620  4231  4231 D HidService: Received start request. Starting profile...
,09-09 11:43:08.621  4231  4231 I bt_bluedroid: get_profile_interface hidhost
09-09 11:43:08.621  4231  4231 D HidService: setHidService(): set to: null
09-09 11:43:08.621  4231  4247 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39583e5
09-09 11:43:08.621  4231  4247 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-09 11:43:08.622  4231  4231 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-09 11:43:08.622  4231  4231 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@222e1b2
09-09 11:43:08.623  4231  4231 D HealthService: Received start request. Starting profile...
,09-09 11:43:08.625  4231  4231 I bt_bluedroid: get_profile_interface health
09-09 11:43:08.625  4231  4231 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-09 11:43:08.626  4231  4231 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@222e1b2
09-09 11:43:08.627  4231  4231 D PanService: Received start request. Starting profile...
09-09 11:43:08.627  4231  4231 D BluetoothPanServiceJni: initializeNative(L110): pan
09-09 11:43:08.627  4231  4231 I bt_bluedroid: get_profile_interface pan
09-09 11:43:08.628  4231  4247 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-09 11:43:08.630  4231  4231 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@222e1b2
,09-09 11:43:08.630  4231  4231 D BluetoothMapService: Received start request. Starting profile...
09-09 11:43:08.630  4231  4231 D BluetoothMapService: start()
,09-09 11:43:08.633  4231  4231 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-09 11:43:08.634  4231  4231 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-09 11:43:08.634  4231  4231 D BluetoothMapAppObserver: createReceiver()
,09-09 11:43:08.635  4231  4231 D BluetoothMapAppObserver: initObservers()
09-09 11:43:08.635  4231  4231 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-09 11:43:08.641  4231  4231 V BluetoothAdapterState: isTurningOff()=false
,09-09 11:43:08.641  4231  4231 V BluetoothAdapterState: isTurningOn()=true
09-09 11:43:08.641  4231  4231 V BluetoothAdapterState: isBleTurningOn()=false
09-09 11:43:08.641  4231  4231 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 11:43:08.643  4231  4231 V BluetoothAdapterState: isTurningOff()=false
,09-09 11:43:08.643  4231  4260 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-09 11:43:08.643  4231  4231 V BluetoothAdapterState: isTurningOn()=true
,09-09 11:43:08.644  4231  4231 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 11:43:08.644  4231  4231 V BluetoothAdapterState: isBleTurningOff()=false
09-09 11:43:08.644  4231  4231 V BluetoothAdapterState: isTurningOff()=false
09-09 11:43:08.645  4231  4231 V BluetoothAdapterState: isTurningOn()=true
,09-09 11:43:08.645  4231  4231 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 11:43:08.645  4231  4231 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 11:43:08.645  4231  4231 V BluetoothAdapterState: isTurningOff()=false
,09-09 11:43:08.645  4231  4231 V BluetoothAdapterState: isTurningOn()=true
09-09 11:43:08.645  4231  4231 V BluetoothAdapterState: isBleTurningOn()=false
09-09 11:43:08.645  4231  4231 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 11:43:08.646  4231  4231 V BluetoothAdapterState: isTurningOff()=false
09-09 11:43:08.646  4231  4231 V BluetoothAdapterState: isTurningOn()=true
09-09 11:43:08.646  4231  4231 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 11:43:08.646  4231  4231 V BluetoothAdapterState: isBleTurningOff()=false
09-09 11:43:08.646  4231  4231 V BluetoothAdapterState: isTurningOff()=false
09-09 11:43:08.646  4231  4231 V BluetoothAdapterState: isTurningOn()=true
09-09 11:43:08.647  4231  4231 V BluetoothAdapterState: isBleTurningOn()=false
09-09 11:43:08.647  4231  4231 V BluetoothAdapterState: isBleTurningOff()=false
09-09 11:43:08.648  4231  4243 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-09 11:43:08.648  4231  4243 D BluetoothAdapterProperties: ScanMode =  20
09-09 11:43:08.648  4231  4243 D BluetoothAdapterProperties: State =  11
09-09 11:43:08.648  4231  4243 D BluetoothAdapterProperties: Setting state to 12
09-09 11:43:08.649  4231  4243 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-09 11:43:08.649  1349  1369 D BluetoothPan: onBluetoothStateChange on: true
09-09 11:43:08.651  4231  4243 I BluetoothAdapterState: Entering OnState
09-09 11:43:08.651  4231  4247 D BluetoothAdapterProperties: Scan Mode:21
09-09 11:43:08.655  4231  4247 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 11:43:08.655  1349  1349 D BluetoothPan: BluetoothPAN Proxy object connected
,09-09 11:43:08.655  1349  1349 D PanProfile: Bluetooth service connected
09-09 11:43:08.655   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 11:43:08.656  3923  3934 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 11:43:08.658  1927  1939 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 11:43:08.658  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 11:43:08.658  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:43:08.658  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:43:08.658  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 11:43:08.658  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 11:43:08.658  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 11:43:08.658  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 11:43:08.658  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 11:43:08.658  3923  3934 D BluetoothPan: onBluetoothStateChange on: true
09-09 11:43:08.659  3923  3923 D BluetoothInputDevice: Proxy object connected
,09-09 11:43:08.659  3923  3923 D HidProfile: Bluetooth service connected
09-09 11:43:08.660   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 11:43:08.661  1349  2033 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 11:43:08.661  4231  4231 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-09 11:43:08.661  3826  3826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 11:43:08.662  4231  4231 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-09 11:43:08.663  3923  3923 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 11:43:08.665  3923  3923 D PanProfile: Bluetooth service connected
09-09 11:43:08.663   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 11:43:08.663  4231  4231 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 11:43:08.666  3923  4268 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 11:43:08.666  1349  2029 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 11:43:08.666  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 11:43:08.666  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:43:08.666  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:43:08.666  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 11:43:08.666  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 11:43:08.666  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 11:43:08.666  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 11:43:08.666  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 11:43:08.668  4231  4231 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 11:43:08.669  3826  3826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 11:43:08.669  1349  1349 D BluetoothInputDevice: Proxy object connected
09-09 11:43:08.669  1349  1349 D HidProfile: Bluetooth service connected
09-09 11:43:08.669  1349  2033 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 11:43:08.670  4231  4231 D ObexServerSockets: Succeed to create listening sockets 
09-09 11:43:08.670  4231  4231 D ObexServerSockets0: startAccept()
09-09 11:43:08.670  4231  4231 D ObexServerSockets0: prepareForNewConnect()
09-09 11:43:08.671  3923  3934 D BluetoothMap: onBluetoothStateChange: up=true
09-09 11:43:08.672  4231  4231 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-09 11:43:08.672  4231  4231 D BluetoothSdpJni: SDP Create record success - handle: 0
09-09 11:43:08.673  4231  4269 D ObexServerSockets0: Accepting socket connection...
09-09 11:43:08.673   874   874 D BluetoothA2dp: Proxy object connected
09-09 11:43:08.673  1349  1349 D BluetoothA2dp: Proxy object connected
09-09 11:43:08.675  4231  4270 D ObexServerSockets0: Accepting socket connection...
,09-09 11:43:08.676  3923  4268 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 11:43:08.679  1349  2029 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 11:43:08.679  3923  3923 D BluetoothMap: Proxy object connected
,09-09 11:43:08.679  3923  3923 D MapProfile: Bluetooth service connected
09-09 11:43:08.679  3923  3923 D BluetoothMap: getConnectedDevices()
09-09 11:43:08.679   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 11:43:08.679  3923  3933 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 11:43:08.681  3923  3923 D BluetoothA2dp: Proxy object connected
09-09 11:43:08.682  1349  1369 D BluetoothMap: onBluetoothStateChange: up=true
,09-09 11:43:08.683  1349  1349 D BluetoothMap: Proxy object connected
,09-09 11:43:08.683  1349  1349 D MapProfile: Bluetooth service connected
09-09 11:43:08.683  1349  1349 D BluetoothMap: getConnectedDevices()
,09-09 11:43:08.685   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
,09-09 11:43:08.686  4231  4231 D BluetoothMapService: onReceive
09-09 11:43:08.686  4231  4231 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 11:43:08.686  4231  4231 D BluetoothMapService: STATE_ON
09-09 11:43:08.687  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 11:43:08.688  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 11:43:08.690  3923  3923 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 11:43:08.696  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 11:43:08.698  3923  3923 D DockEventReceiver: finishStartingService: stopping service
,09-09 11:43:08.705  3923  3923 D BluetoothPbap: Proxy object connected
09-09 11:43:08.705  3923  3923 D PbapServerProfile: Bluetooth service connected
,09-09 11:43:08.711  4231  4231 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-09 11:43:08.711  4231  4231 D ObexServerSockets0: prepareForNewConnect()
09-09 11:43:08.714  4231  4275 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 11:43:08.715  1349  1349 D BluetoothPbap: Proxy object connected
,09-09 11:43:08.715  1349  1349 D PbapServerProfile: Bluetooth service connected
,09-09 11:43:08.731  4231  4279 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 11:43:08.732  4231  4279 I BtOppRfcommListener: Accept thread started.
,09-09 11:43:08.758  1927  2066 D BluetoothHeadset: Proxy object connected
,09-09 11:43:08.758  3923  4268 D BluetoothHeadset: Proxy object connected
09-09 11:43:08.758   874   874 D BluetoothHeadset: Proxy object connected
09-09 11:43:08.758   874   874 D BluetoothHeadset: Proxy object connected
09-09 11:43:08.758  3923  3923 D HeadsetProfile: Bluetooth service connected
09-09 11:43:08.759  1349  1369 D BluetoothHeadset: Proxy object connected
09-09 11:43:08.759  1349  1349 D HeadsetProfile: Bluetooth service connected
09-09 11:43:08.759   874   874 D BluetoothHeadset: Proxy object connected
09-09 11:43:08.760  1927  1940 D BluetoothHeadset: Proxy object connected
,09-09 11:43:08.765   874   891 D BluetoothHeadset: Proxy object connected
09-09 11:43:08.766  3923  3933 D BluetoothHeadset: Proxy object connected
09-09 11:43:08.766  3923  3923 D HeadsetProfile: Bluetooth service connected
,09-09 11:43:08.780  1349  1369 D BluetoothHeadset: Proxy object connected
,09-09 11:43:08.780  1349  1349 D HeadsetProfile: Bluetooth service connected
09-09 11:43:08.781   874   891 D BluetoothHeadset: Proxy object connected
,09-09 11:43:11.792  3826  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 11:43:11.792  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:43:11.792  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:43:11.792  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 11:43:11.792  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 11:43:11.792  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 11:43:11.792  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 11:43:11.792  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 11:43:11.799  3826  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 11:43:11.800  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 11:43:11.801  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f70134d removed from the list
09-09 11:43:11.801  3826  3876 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 11:43:11.801  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 11:43:11.802  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 11:43:11.804  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 11:43:11.805  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@327de02 added. We now have 4 listener(s)
,09-09 11:43:11.805  3826  3876 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 11:43:11.809   874  1977 D WifiService: setWifiEnabled: false pid=3826, uid=10000
,09-09 11:43:11.809   874  1977 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 11:43:16.825  3826  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 11:43:16.826   874  1978 D WifiService: setWifiEnabled: true pid=3826, uid=10000
,09-09 11:43:16.826   874  1978 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 11:43:16.838   874  1307 D WifiConfigStore: Loading config and enabling all networks 
,09-09 11:43:16.855  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 11:43:16.855  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:43:16.855  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:43:16.855  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 11:43:16.855  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 11:43:16.855  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 11:43:16.855  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 11:43:16.855  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 11:43:16.861  3826  3826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 11:43:16.868  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 11:43:16.868  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:43:16.868  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:43:16.868  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 11:43:16.868  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 11:43:16.868  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 11:43:16.868  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 11:43:16.868  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 11:43:16.871  3826  3826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 11:43:16.874   874  1307 D WifiConfigStore: loaded 0 passpoint configs
09-09 11:43:16.875   874  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-09 11:43:16.876   874  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-09 11:43:16.877   874  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-09 11:43:16.877   874  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-09 11:43:16.878   874  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-09 11:43:16.878   874  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-09 11:43:16.894   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-09 11:43:16.895   874  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-09 11:43:16.897   372   872 D CommandListener: Setting iface cfg
,09-09 11:43:16.947   874  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
,09-09 11:43:16.948   874  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-09 11:43:16.953   874  1307 E native  : do suspend true
,09-09 11:43:16.978   874  1306 D WifiNative-HAL: p2pGetDeviceAddress
,09-09 11:43:16.989   874  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-09 11:43:16.993   874  1307 D WifiConfigStore: Retrieve network priorities after PNO.,
,09-09 11:43:18.291   874  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-09 11:43:18.398  1861  1956 I Keyboard.Facilitator.LanguageModelFlusher: run()
09-09 11:43:18.398  1861  1956 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-09 11:43:18.429   874  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.81 rxSuccessRate=12.50 delta 1000 -> 994
,09-09 11:43:18.430   874  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-09 11:43:18.430   874  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 11:43:18.459  1524  1524 I ConfigService: onCreate
09-09 11:43:18.461   874  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-09 11:43:18.513   874  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-09 11:43:18.514  1475  1475 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-09 11:43:18.944  1475  1475 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-09 11:43:18.991  1475  1475 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-09 11:43:18.992  1475  1475 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-09 11:43:19.003   874  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 11:43:19.019   874  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 11:43:19.019   874  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 11:43:19.019   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-09 11:43:19.044   874  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 11:43:19.066   372   872 D CommandListener: Setting iface cfg
,09-09 11:43:19.068   874  1307 D WifiStateMachine: Start Dhcp Watchdog 3
,09-09 11:43:19.079   874  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-09 11:43:19.103   874  4290 D DhcpClient: Receive thread started
,09-09 11:43:19.200   874  1307 E native  : do suspend false
,09-09 11:43:19.227   874  1891 D DhcpClient: Broadcasting DHCPDISCOVER
,09-09 11:43:19.245   874  4290 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-09 11:43:19.247   874  1891 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,09-09 11:43:19.250   874  1891 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-09 11:43:19.274   874  4290 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-09 11:43:19.275   874  1891 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-09 11:43:19.280   372   872 D CommandListener: Setting iface cfg
,09-09 11:43:19.291   874  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-09 11:43:19.293   874  1891 D DhcpClient: Scheduling renewal in 86399s
,09-09 11:43:19.294   874  1307 E native  : do suspend true
,09-09 11:43:19.324   874  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-09 11:43:19.327   874  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,09-09 11:43:19.329   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-09 11:43:19.332   874  1309 D ConnectivityService: Adding iface wlan0 to network 102
,09-09 11:43:19.334   874  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-09 11:43:19.375   874  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-09 11:43:19.375   874  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-09 11:43:19.377   874  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-09 11:43:19.379   874  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-09 11:43:19.381   874  1309 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-09 11:43:19.390   874  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-09 11:43:19.397   874  1309 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-09 11:43:19.397   874  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-09 11:43:19.397   874  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-09 11:43:19.398   874  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 11:43:19.398   874  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-09 11:43:19.398   874  1309 D ConnectivityService:    accepting network in place of null
,09-09 11:43:19.399   874  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 11:43:19.426   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=211411, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 11:43:19.435   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 11:43:19.476   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 11:43:19.486   874  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-09 11:43:19.486   874  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 11:43:19.494   874  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-09 11:43:19.496   874   891 D Tethering: MasterInitialState.processMessage what=3
09-09 11:43:19.502   874  4288 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.206,2a00:1450:400d:803::200e
,09-09 11:43:19.519  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 11:43:19.519  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:43:19.519  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:43:19.519  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 11:43:19.519  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 11:43:19.519  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 11:43:19.519  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 11:43:19.519  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 11:43:19.522  3826  3826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 11:43:19.527  1999  1999 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
09-09 11:43:19.528  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 11:43:19.528  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:43:19.528  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:43:19.528  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 11:43:19.528  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 11:43:19.528  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 11:43:19.528  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 11:43:19.528  3826  3826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 11:43:19.531  3826  3826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 11:43:19.537  1751  1751 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 11:43:19.541  1751  1751 D SystemUpdateService: onCreate
,09-09 11:43:19.545  1751  1751 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 11:43:19.571  1751  4300 I SystemUpdateService: active receiver: enabled
,09-09 11:43:19.573  1751  1751 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-09 11:43:19.579  1751  2427 I iu.UploadsManager: num queued entries: 0
09-09 11:43:19.579  1751  2427 I iu.UploadsManager: num updated entries: 0
,09-09 11:43:19.580  1751  2427 I iu.SyncManager: NEXT; no task
,09-09 11:43:19.584  1751  1751 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 11:43:19.585  1751  1751 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 11:43:19.587  4015  4015 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 11:43:19.600  1751  4302 I MDM     : [184] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-09 11:43:19.600  1751  4302 W BaseAppContext: Using Auth Proxy for data requests.
09-09 11:43:19.603   874  4288 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 09:43:19 GMT], X-Android-Received-Millis=[1473414199601], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473414199562]}
09-09 11:43:19.605  4015  4015 D SprintDMHelper: simOperator: 
,09-09 11:43:19.605  4015  4015 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-09 11:43:19.606   874  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-09 11:43:19.607   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-09 11:43:19.608   874  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-09 11:43:19.616   874  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-09 11:43:19.635  1751  4302 V GoogleAuthProtoRequest: [184] a.<init>: mAccountName set to: thalitester@gmail.com
,09-09 11:43:19.647  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:43:19.648  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:43:19.651  1751  4300 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 11:43:19.666  1751  4300 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-09 11:43:19.666  1751  4300 I SystemUpdateService: now status is 0 (complete)
,09-09 11:43:19.666  1751  4300 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-09 11:43:19.666  1751  4300 I SystemUpdateService: file has been verified
,09-09 11:43:19.666  1751  4300 I SystemUpdateService: OTA package size = 12249756
,09-09 11:43:19.686  1751  4300 I SystemUpdateService: showing system update notification
,09-09 11:43:19.704  1524  1537 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-09 11:43:19.704  1524  1537 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-09 11:43:19.704  1524  1537 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 11:43:19.704  1524  1537 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:43:19.726  1751  4302 E MDM     : [184] SitrepService.a: Error sending sitrep.
,09-09 11:43:19.762  1751  1751 D SystemUpdateService: onDestroy
,09-09 11:43:19.765  3989  4306 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-09 11:43:19.772  3755  4298 V KeepSync: Connecting to GoogleApiClient
,09-09 11:43:19.772   874  1392 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 11:43:19.831  1524  2892 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-09 11:43:19.831  1524  2892 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-09 11:43:19.831  1524  2892 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 11:43:19.831  1524  2892 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:43:19.845  1751  4312 V BaseAuthAsyncOperation: access token request failed
,09-09 11:43:19.846  3755  4298 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 11:43:19.908  1524  1537 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-09 11:43:19.908  1524  1537 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-09 11:43:19.909  1524  1537 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 11:43:19.909  1524  1537 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:43:19.921  3755  4298 E KeepSync: IOException
09-09 11:43:19.921  3755  4298 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 11:43:19.921  3755  4298 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 11:43:19.921  3755  4298 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 11:43:19.921  3755  4298 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 11:43:19.921  3755  4298 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 11:43:19.921  3755  4298 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 11:43:19.921  3755  4298 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 11:43:19.921  3755  4298 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 11:43:19.921  3755  4298 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 11:43:19.921  3755  4298 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 11:43:19.921  3755  4298 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 11:43:19.921  3755  4298 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 11:43:19.921  3755  4298 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 11:43:19.921  3755  4298 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 11:43:19.921  3755  4298 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 11:43:19.921  3755  4298 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 11:43:19.921  3755  4298 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 11:43:19.921  3755  4298 E KeepSync: 	... 10 more
,09-09 11:43:19.922  3755  4298 W KeepSync: Sync result 2
,09-09 11:43:19.927   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 207879, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 11:43:20.486   874  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-09 11:43:21.853  3826  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 11:43:21.853  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:43:21.853  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:43:21.853  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 11:43:21.853  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 11:43:21.853  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 11:43:21.853  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 11:43:21.853  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 11:43:21.860  3826  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 11:43:21.861  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 11:43:21.862  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@327de02 removed from the list
,09-09 11:43:21.862  3826  3876 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 11:43:21.864  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 11:43:21.864  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 11:43:21.876  3826  4313 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-09 11:43:21.877  3826  4313 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-09 11:43:23.517  1524  1524 I ConfigService: onDestroy
,09-09 11:43:24.886  3826  4313 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-09 11:43:24.888  3826  4313 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-09 11:43:24.889  3826  4313 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes,
,09-09 11:43:24.890  3826  4313 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 11:43:24.891  3826  4315 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-09 11:43:24.891  3826  4315 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-09 11:43:24.892  3826  4315 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 11:43:24.893  3826  4317 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 420, name: OutgoingSocketThread/Sender)
,09-09 11:43:24.893  3826  4313 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-09 11:43:24.894  3826  4315 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 11:43:24.896  3826  4315 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-09 11:43:24.896  3826  4318 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 421, name: OutgoingSocketThread/Receiver)
09-09 11:43:24.897  3826  4318 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 421, thread name: OutgoingSocketThread/Receiver)
,09-09 11:43:24.899  3826  4318 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-09 11:43:24.900  3826  4318 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 421, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-09 11:43:24.901  3826  4319 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 422, name: IncomingSocketThread/Sender)
,09-09 11:43:24.904  3826  4320 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 423, name: IncomingSocketThread/Receiver)
09-09 11:43:24.905  3826  4320 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 423, thread name: IncomingSocketThread/Receiver)
,09-09 11:43:24.905  3826  4320 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-09 11:43:24.905  3826  4320 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 423, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-09 11:43:27.404   874  1309 D ConnectivityService: handlePromptUnvalidated 102
,09-09 11:43:27.884  3826  3876 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-09 11:43:27.886  3826  3876 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-09 11:43:27.893  3826  3876 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@ed966fe Bundle[{}]
,09-09 11:43:27.894  3826  3876 I io.jxcore.node.LifeCycleMonitor: start: OK
09-09 11:43:27.894  3826  3876 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-09 11:43:27.896  3826  3876 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-09 11:43:27.897  3826  3876 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-09 11:43:27.899  3826  3876 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-09 11:43:27.900  3826  3876 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-09 11:43:27.912  3826  3876 I System.out: Running OutgoingSocketThread
,09-09 11:43:27.917  3826  4321 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-09 11:43:27.917  3826  4321 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-09 11:43:30.926  3826  4322 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-09 11:43:30.927  3826  4322 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-09 11:43:30.927  3826  4322 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 11:43:30.928  3826  4321 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-09 11:43:30.928  3826  4321 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-09 11:43:30.928  3826  4322 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 11:43:30.929  3826  4321 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 11:43:30.930  3826  4322 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-09 11:43:30.933  3826  4321 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 11:43:30.936  3826  4324 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 432, name: IncomingSocketThread/Sender)
,09-09 11:43:30.939  3826  4325 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 433, name: IncomingSocketThread/Receiver)
,09-09 11:43:30.941  3826  4321 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-09 11:43:30.943  3826  4325 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 433, thread name: IncomingSocketThread/Receiver)
09-09 11:43:30.943  3826  4325 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-09 11:43:30.944  3826  4325 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 433, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-09 11:43:30.944  3826  4326 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 434, name: OutgoingSocketThread/Sender)
09-09 11:43:30.949  3826  4327 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 435, name: OutgoingSocketThread/Receiver)
,09-09 11:43:30.950  3826  4327 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 435, thread name: OutgoingSocketThread/Receiver)
09-09 11:43:30.950  3826  4327 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-09 11:43:30.950  3826  4327 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 435, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-09 11:43:33.928  3826  3876 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 444)
,09-09 11:43:33.930  3826  3876 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-09 11:43:33.931  3826  3876 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 445)
,09-09 11:43:33.937  3826  3876 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 11:43:33.937  3826  3876 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@52a5313 added. We now have 3 listener(s)
,09-09 11:43:33.939  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 11:43:33.939  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 11:43:33.939  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 11:43:33.939  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 11:43:33.939  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c075950 added. We now have 4 listener(s)
09-09 11:43:33.940  3826  3876 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 11:43:33.940  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 11:43:33.945  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 11:43:33.958  3826  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 11:43:33.958  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:43:33.958  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:43:33.958  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 11:43:33.958  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 11:43:33.958  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 11:43:33.958  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 11:43:33.958  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 11:43:33.964  3826  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 11:43:33.964  3826  3876 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 11:43:33.967  3826  3876 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 11:43:33.967  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 11:43:33.967  3826  3876 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 11:43:33.968  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 11:43:33.968  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:43:33.968  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 11:43:33.968  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 11:43:33.969  3826  3876 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@52a5313 removed from the list
09-09 11:43:33.969  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:43:33.969  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c075950 removed from the list
09-09 11:43:33.971  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 11:43:33.974  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 11:43:33.974  3826  3876 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 11:43:33.975  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:43:33.977  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:43:33.978  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 11:43:33.982  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 11:43:33.982  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 11:43:33.983  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 11:43:33.983  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c075950 not in the list
09-09 11:43:33.983  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:43:33.983  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 11:43:33.986  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 11:43:33.987  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 11:43:33.987  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:43:33.987  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c075950 not in the list
,09-09 11:43:33.988  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 11:43:33.988  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:43:33.988  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:43:33.989  3826  3876 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@52a5313 not in the list
,09-09 11:43:33.990  3826  3876 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 11:43:33.991  3826  3876 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@339d84e added. We now have 3 listener(s)
,09-09 11:43:33.997  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 11:43:33.997  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 11:43:33.998  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 11:43:33.998  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 11:43:33.999  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9dd0d6f added. We now have 4 listener(s)
09-09 11:43:33.999  3826  3876 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 11:43:34.000  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 11:43:34.007  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 11:43:34.020  3826  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 11:43:34.020  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:43:34.020  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:43:34.020  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 11:43:34.020  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 11:43:34.020  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 11:43:34.020  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 11:43:34.020  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 11:43:34.025  3826  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 11:43:34.026  3826  3876 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 11:43:34.027  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 11:43:34.027  3826  3876 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-09 11:43:34.028  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 11:43:34.028  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 11:43:34.028  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 11:43:34.031  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 11:43:34.036  3826  3876 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 11:43:34.036  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 11:43:34.040  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 11:43:34.050  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 11:43:34.052  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 11:43:34.052  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 11:43:34.065  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 11:43:34.066  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 11:43:34.066  3826  3876 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 11:43:34.068  3826  3876 D BluetoothAdapter: STATE_ON
,09-09 11:43:34.077  4231  4267 D BtGatt.GattService: registerClient() - UUID=18e2c588-0cda-4e50-9fb8-be0a8c47c310
,09-09 11:43:34.079  4231  4247 D BtGatt.GattService: onClientRegistered() - UUID=18e2c588-0cda-4e50-9fb8-be0a8c47c310, clientIf=5
,09-09 11:43:34.081  3826  3837 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-09 11:43:34.084  4231  4259 D BtGatt.GattService: start scan with filters
,09-09 11:43:34.096  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 11:43:34.097  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 11:43:34.097  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 11:43:34.097  4231  4250 D BtGatt.ScanManager: handling starting scan
,09-09 11:43:34.097  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 11:43:34.103  4231  4250 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@222e1b2
,09-09 11:43:34.107  3826  3876 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 11:43:34.108  3826  3826 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 11:43:34.109  3826  3876 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 11:43:34.116  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 11:43:34.119  4231  4247 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-09 11:43:34.119  4231  4247 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 11:43:34.123  4231  4250 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0,
09-09 11:43:34.124  3826  3876 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 11:43:34.125  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 11:43:34.125  3826  3876 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 11:43:34.126  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 11:43:34.126  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 11:43:34.126  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 11:43:34.126  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 11:43:34.126  3826  3876 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-09 11:43:34.127  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 11:43:34.128  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 11:43:34.128  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 11:43:34.130  3826  3876 D BluetoothAdapter: STATE_ON
,09-09 11:43:34.133  4231  4247 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-09 11:43:34.133  4231  4267 D BtGatt.GattService: stopScan() - queue size =1
09-09 11:43:34.133  4231  4247 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 11:43:34.134  4231  4250 D BtGatt.ScanManager: Starting BLE batch scan
,09-09 11:43:34.134  4231  4250 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-09 11:43:34.135  4231  4259 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 11:43:34.136  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 11:43:34.136  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-09 11:43:34.137  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 11:43:34.137  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 11:43:34.138  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 11:43:34.139  3826  3876 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 11:43:34.140  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 11:43:34.140  3826  3876 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 11:43:34.140  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 11:43:34.141  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 11:43:34.142  3826  3826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 11:43:34.142  3826  3826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 11:43:34.142  3826  3826 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 11:43:34.147  4231  4247 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 11:43:34.147  4231  4247 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 11:43:34.155  4231  4247 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-09 11:43:34.155  4231  4247 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 11:43:34.167  4231  4247 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-09 11:43:34.167  4231  4247 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 11:43:34.167  4231  4250 D BtGatt.ScanManager: stopping BLe Batch
,09-09 11:43:34.175  4231  4247 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-09 11:43:34.175  4231  4247 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 11:43:34.176  4231  4250 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 11:43:34.183  4231  4247 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-09 11:43:34.183  4231  4247 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 11:43:34.643  3826  3826 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 11:43:34.644  3826  3826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 11:43:34.644  3826  3826 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 11:43:37.143  3826  3876 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 11:43:37.144  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 11:43:37.144  3826  3876 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 11:43:37.145  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 11:43:37.146  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:43:37.146  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 11:43:37.146  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 11:43:37.147  3826  3876 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@339d84e removed from the list
09-09 11:43:37.147  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:43:37.147  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9dd0d6f removed from the list
09-09 11:43:37.147  3826  3876 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 11:43:37.148  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:43:37.149  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:43:37.150  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:43:37.153  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 11:43:37.153  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 11:43:37.153  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:43:37.154  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9dd0d6f not in the list
09-09 11:43:37.154  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:43:37.154  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 11:43:37.157  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 11:43:37.158  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 11:43:37.158  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:43:37.158  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9dd0d6f not in the list
,09-09 11:43:37.158  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 11:43:37.159  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:43:37.159  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:43:37.159  3826  3876 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@339d84e not in the list
09-09 11:43:37.162  3826  3876 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 11:43:37.162  3826  3876 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aed0268 added. We now have 3 listener(s)
09-09 11:43:37.164  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 11:43:37.164  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 11:43:37.164  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 11:43:37.165  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 11:43:37.165  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@215e681 added. We now have 4 listener(s)
09-09 11:43:37.165  3826  3876 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 11:43:37.165  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 11:43:37.169  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 11:43:37.176  3826  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 11:43:37.176  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:43:37.176  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:43:37.176  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 11:43:37.176  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 11:43:37.176  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 11:43:37.176  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 11:43:37.176  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 11:43:37.178  3826  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 11:43:37.178  3826  3876 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 11:43:37.180  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 11:43:37.182  3826  3876 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-09 11:43:37.182  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,09-09 11:43:37.182  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 11:43:37.182  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 11:43:37.182  3826  3876 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 11:43:37.182  3826  3876 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 11:43:37.182  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 11:43:37.184  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-09 11:43:37.185  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 11:43:37.185  3826  3876 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 11:43:37.185  3826  3876 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 11:43:37.186  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 11:43:37.186  3826  3826 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-09 11:43:37.186  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 11:43:37.186  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 11:43:37.186  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 11:43:37.190  3826  3876 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 11:43:37.190  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 11:43:37.195  3826  4328 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 11:43:37.197  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 11:43:37.197  3826  4328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-09 11:43:37.199  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 11:43:37.199  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 11:43:37.203  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-09 11:43:37.204  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 11:43:37.205  3826  3876 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,09-09 11:43:37.208  3826  3876 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-09 11:43:37.208  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 11:43:37.208  3826  3876 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-09 11:43:37.209  3826  3876 D BluetoothAdapter: STATE_ON
,09-09 11:43:37.212  4231  4267 D BtGatt.GattService: registerClient() - UUID=0c1d1444-dd2e-4355-9c88-b6175d88719b
09-09 11:43:37.213  4231  4247 D BtGatt.GattService: onClientRegistered() - UUID=0c1d1444-dd2e-4355-9c88-b6175d88719b, clientIf=5
,09-09 11:43:37.213  3826  3838 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-09 11:43:37.216  4231  4249 D BtGatt.AdvertiseManager: message : 0
,09-09 11:43:37.219  4231  4249 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 11:43:37.236  4231  4247 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-09 11:43:37.249  4231  4247 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-09 11:43:37.252  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-09 11:43:37.253  3826  3876 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 11:43:37.259  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 11:43:37.262  3826  3826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 11:43:37.263  3826  3826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-09 11:43:37.263  3826  3826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-09 11:43:37.264  3826  3826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-09 11:43:37.264  3826  3826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-09 11:43:37.265  3826  3826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-09 11:43:37.270  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-09 11:43:37.272  3826  3826 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-09 11:43:37.272  3826  3826 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 11:43:37.773  3826  3826 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-09 11:43:37.773  3826  3826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-09 11:43:37.774  3826  3826 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 11:43:40.272  3826  3876 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 11:43:40.272  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-09 11:43:40.273  3826  3876 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 11:43:40.273  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 11:43:40.273  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-09 11:43:40.274  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-09 11:43:40.275  3826  4328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 11:43:40.275  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 11:43:40.275  3826  4328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-09 11:43:40.275  3826  3876 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 11:43:40.275  3826  4328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 11:43:40.275  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-09 11:43:40.276  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 11:43:40.276  3826  3876 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 11:43:40.276  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 11:43:40.276  3826  3826 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-09 11:43:40.276  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 11:43:40.279  3826  3876 D BluetoothAdapter: STATE_ON
09-09 11:43:40.279  3826  3876 D BluetoothLeScanner: could not find callback wrapper
,09-09 11:43:40.280  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 11:43:40.280  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-09 11:43:40.282  4231  4249 D BtGatt.AdvertiseManager: message : 1
09-09 11:43:40.284  4231  4249 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-09 11:43:40.295  4231  4247 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-09 11:43:40.295  4231  4247 D BtGatt.GattService: Client app is not null!
,09-09 11:43:40.297  4231  4241 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 11:43:40.298  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 11:43:40.298  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-09 11:43:40.299  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-09 11:43:40.299  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-09 11:43:40.299  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-09 11:43:40.301  3826  3876 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 11:43:40.302  3826  3876 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 11:43:40.302  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 11:43:40.303  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 11:43:40.305  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 11:43:40.305  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:43:40.305  3826  3826 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 11:43:40.305  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 11:43:40.305  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 11:43:40.305  3826  3826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 11:43:40.305  3826  3876 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aed0268 removed from the list
09-09 11:43:40.305  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:43:40.305  3826  3826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 11:43:40.305  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@215e681 removed from the list
09-09 11:43:40.305  3826  3826 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 11:43:40.305  3826  3876 D io.jxcore.node.ConnectivityMonitor: stop
09-09 11:43:40.306  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 11:43:40.306  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:43:40.307  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:43:40.309  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 11:43:40.309  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 11:43:40.310  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:43:40.310  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@215e681 not in the list
,09-09 11:43:40.310  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:43:40.310  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 11:43:40.312  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 11:43:40.313  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 11:43:40.313  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:43:40.313  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@215e681 not in the list
,09-09 11:43:40.313  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 11:43:40.314  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:43:40.314  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:43:40.314  3826  3876 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aed0268 not in the list
,09-09 11:43:40.316  3826  3876 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 11:43:40.316  3826  3876 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d7cbb2 added. We now have 3 listener(s)
,09-09 11:43:40.322  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 11:43:40.322  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 11:43:40.323  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 11:43:40.323  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 11:43:40.323  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49e2703 added. We now have 4 listener(s)
09-09 11:43:40.324  3826  3876 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 11:43:40.325  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 11:43:40.330  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 11:43:40.336  3826  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 11:43:40.336  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:43:40.336  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:43:40.336  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 11:43:40.336  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 11:43:40.336  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 11:43:40.336  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 11:43:40.336  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 11:43:40.338  3826  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 11:43:40.339  3826  3876 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 11:43:40.339  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 11:43:40.340  3826  3876 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 11:43:40.340  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-09 11:43:40.340  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 11:43:40.340  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 11:43:40.343  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 11:43:40.344  3826  3876 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 11:43:40.344  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 11:43:40.347  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 11:43:40.350  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 11:43:40.351  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 11:43:40.351  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 11:43:40.358  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 11:43:40.358  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 11:43:40.358  3826  3876 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 11:43:40.360  3826  3876 D BluetoothAdapter: STATE_ON
,09-09 11:43:40.365  4231  4259 D BtGatt.GattService: registerClient() - UUID=2d3ebc67-fc9e-4886-a8c0-6ea2bbb32eb1
,09-09 11:43:40.366  4231  4247 D BtGatt.GattService: onClientRegistered() - UUID=2d3ebc67-fc9e-4886-a8c0-6ea2bbb32eb1, clientIf=5
09-09 11:43:40.366  3826  3838 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-09 11:43:40.366  4231  4241 D BtGatt.GattService: start scan with filters
,09-09 11:43:40.372  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 11:43:40.372  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 11:43:40.372  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 11:43:40.372  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 11:43:40.372  4231  4250 D BtGatt.ScanManager: handling starting scan
,09-09 11:43:40.380  3826  3876 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 11:43:40.380  3826  3876 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
,09-09 11:43:40.380  3826  3826 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
,09-09 11:43:40.386  4231  4247 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-09 11:43:40.386  4231  4247 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 11:43:40.386  4231  4250 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 11:43:40.386  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 11:43:40.395  4231  4247 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-09 11:43:40.395  4231  4247 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 11:43:40.396  4231  4250 D BtGatt.ScanManager: Starting BLE batch scan
,09-09 11:43:40.396  4231  4250 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-09 11:43:40.417  4231  4247 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-09 11:43:40.417  4231  4247 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 11:43:40.428  4231  4247 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-09 11:43:40.428  4231  4247 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 11:43:40.807  3826  3826 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 11:43:40.881  3826  3826 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-09 11:43:40.881  3826  3826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 11:43:40.882  3826  3826 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 11:43:41.934  4231  4231 D BtGatt.ScanManager: awakened up at time 233920
,09-09 11:43:41.938  4231  4250 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 11:43:41.976  4231  4247 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-09 11:43:41.976  4231  4247 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 11:43:41.977  4231  4247 D BtGatt.GattService: current time is 233963033504
09-09 11:43:41.979  4231  4247 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -82, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -99, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -83, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -81, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -81, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -84, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-09 11:43:41.982  4231  4247 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-09 11:43:41.985  4231  4247 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-09 11:43:41.985  4231  4247 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-09 11:43:41.986  4231  4247 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-09 11:43:41.987  4231  4247 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-09 11:43:41.988  4231  4247 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-09 11:43:43.403  3826  3876 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 11:43:43.403  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 11:43:43.403  3826  3876 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 11:43:43.404  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:43:43.404  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 11:43:43.404  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-09 11:43:43.405  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 11:43:43.405  3826  3876 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 11:43:43.405  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 11:43:43.406  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 11:43:43.406  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 11:43:43.412  3826  3876 D BluetoothAdapter: STATE_ON
,09-09 11:43:43.414  4231  4242 D BtGatt.GattService: stopScan() - queue size =1
,09-09 11:43:43.417  4231  4241 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 11:43:43.418  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 11:43:43.418  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-09 11:43:43.419  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 11:43:43.419  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 11:43:43.420  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 11:43:43.423  3826  3876 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 11:43:43.424  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 11:43:43.424  3826  3876 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 11:43:43.425  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 11:43:43.427  4231  4231 D BtGatt.ScanManager: awakened up at time 235412
09-09 11:43:43.428  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 11:43:43.432  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 11:43:43.432  3826  3826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 11:43:43.432  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:43:43.432  3826  3826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 11:43:43.432  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 11:43:43.433  3826  3826 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 11:43:43.433  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 11:43:43.433  3826  3876 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d7cbb2 removed from the list
09-09 11:43:43.433  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:43:43.434  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49e2703 removed from the list
09-09 11:43:43.437  3826  3876 D io.jxcore.node.ConnectivityMonitor: stop
09-09 11:43:43.438  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:43:43.438  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 11:43:43.438  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:43:43.439  4231  4247 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 11:43:43.440  4231  4247 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 11:43:43.440  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 11:43:43.440  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 11:43:43.440  4231  4250 D BtGatt.ScanManager: stopping BLe Batch
,09-09 11:43:43.441  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:43:43.441  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49e2703 not in the list
,09-09 11:43:43.441  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:43:43.441  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:43:43.443  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 11:43:43.443  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 11:43:43.444  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:43:43.444  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49e2703 not in the list
09-09 11:43:43.444  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 11:43:43.445  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 11:43:43.445  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:43:43.445  3826  3876 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d7cbb2 not in the list
,09-09 11:43:43.447  3826  3876 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 11:43:43.447  3826  3876 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c35baac added. We now have 3 listener(s)
,09-09 11:43:43.450  4231  4247 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-09 11:43:43.450  4231  4247 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 11:43:43.451  4231  4250 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 11:43:43.455  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 11:43:43.455  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 11:43:43.455  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 11:43:43.456  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 11:43:43.456  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ec91375 added. We now have 4 listener(s)
,09-09 11:43:43.457  3826  3876 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 11:43:43.458  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 11:43:43.463  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 11:43:43.469  3826  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 11:43:43.469  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 11:43:43.469  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 11:43:43.469  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 11:43:43.469  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 11:43:43.469  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 11:43:43.469  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 11:43:43.469  3826  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 11:43:43.472  3826  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 11:43:43.473  3826  3876 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 11:43:43.473  3826  3876 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 11:43:43.474  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 11:43:43.475  3826  3876 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 11:43:43.475  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 11:43:43.475  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 11:43:43.475  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 11:43:43.475  3826  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 11:43:43.476  3826  3876 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c35baac removed from the list
09-09 11:43:43.476  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 11:43:43.476  3826  3876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ec91375 removed from the list
09-09 11:43:43.476  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 11:43:43.476  3826  3876 D io.jxcore.node.ConnectivityMonitor: stop
09-09 11:43:43.477  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:43:43.479  4231  4247 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,09-09 11:43:43.478  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:43:43.479  4231  4247 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 11:43:43.480  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:43:43.481  4231  4247 D BtGatt.GattService: current time is 235467289281
09-09 11:43:43.482  4231  4247 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -86, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-09 11:43:43.482  4231  4247 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-09 11:43:43.482  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 11:43:43.482  3826  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 11:43:43.483  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 11:43:43.483  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:43:43.483  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ec91375 not in the list
09-09 11:43:43.483  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:43:43.483  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:43:43.484  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 11:43:43.484  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 11:43:43.484  3826  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 11:43:43.484  3826  3876 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ec91375 not in the list
09-09 11:43:43.484  3826  3876 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 11:43:43.484  3826  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 11:43:43.485  3826  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 11:43:43.485  3826  3876 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c35baac not in the list
09-09 11:43:43.486  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-09 11:43:43.487  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-09 11:43:43.487  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-09 11:43:43.487  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 11:43:43.487  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-09 11:43:43.487  3826  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 11:43:43.935  3826  3826 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 11:43:45.502  3826  4330 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 454, name: My test thread name)
,09-09 11:43:47.500  3826  3876 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 454
,09-09 11:43:47.500  3826  3876 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 454, name: My test thread name)
,09-09 11:43:47.507  3826  4331 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 455, name: My test thread name)
,09-09 11:43:47.508  3826  4331 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 455, thread name: My test thread name)
,09-09 11:43:47.508  3826  4331 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 455, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-09 11:43:47.512  3826  3876 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 11:43:47.521  3826  4332 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 459, name: My test thread name)
,09-09 11:43:47.522  3826  4332 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 459, thread name: My test thread name): Test exception.
,09-09 11:43:47.522  3826  4332 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 459, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-09 11:43:47.530  3826  3876 I jxcore-log: Total number of executed tests:  82
09-09 11:43:47.530  3826  3876 I jxcore-log: 
,09-09 11:43:47.531  3826  3876 I jxcore-log: Number of passed tests:  82
09-09 11:43:47.531  3826  3876 I jxcore-log: 
,09-09 11:43:47.532  3826  3876 I jxcore-log: Number of failed tests:  0
09-09 11:43:47.532  3826  3876 I jxcore-log: 
,09-09 11:43:47.532  3826  3876 I jxcore-log: Number of ignored tests:  0
09-09 11:43:47.532  3826  3876 I jxcore-log: 
,09-09 11:43:47.533  3826  3876 I jxcore-log: Total duration:  101444
09-09 11:43:47.533  3826  3876 I jxcore-log: 
,09-09 11:43:47.542  3826  3876 I jxcore-log: Unit Test app is loaded
09-09 11:43:47.542  3826  3876 I jxcore-log: 
,09-09 11:43:47.560  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 11:43:47.560  3826  3876 I jxcore-log: 
,09-09 11:43:47.565  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 11:43:47.565  3826  3876 I jxcore-log: 
,09-09 11:43:47.566  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 11:43:47.566  3826  3876 I jxcore-log: 
,09-09 11:43:47.567  3826  3826 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-09 11:43:47.567  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 11:43:47.567  3826  3876 I jxcore-log: 
,09-09 11:43:47.569  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-09 11:43:47.569  3826  3876 I jxcore-log: 
,09-09 11:43:47.570  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
09-09 11:43:47.570  3826  3876 I jxcore-log: 
,09-09 11:43:47.573  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 11:43:47.573  3826  3876 I jxcore-log: 
,09-09 11:43:47.575  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 11:43:47.575  3826  3876 I jxcore-log: 
,09-09 11:43:47.576  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-09 11:43:47.576  3826  3876 I jxcore-log: 
,09-09 11:43:47.578  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 11:43:47.578  3826  3876 I jxcore-log: 
,09-09 11:43:47.579  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 11:43:47.579  3826  3876 I jxcore-log: 
,09-09 11:43:47.579  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 11:43:47.579  3826  3876 I jxcore-log: 
09-09 11:43:47.580  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 11:43:47.580  3826  3876 I jxcore-log: 
,09-09 11:43:47.581  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 11:43:47.581  3826  3876 I jxcore-log: 
,09-09 11:43:47.582  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 11:43:47.582  3826  3876 I jxcore-log: 
09-09 11:43:47.583  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 11:43:47.583  3826  3876 I jxcore-log: 
,09-09 11:43:47.584  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 11:43:47.584  3826  3876 I jxcore-log: 
,09-09 11:43:47.585  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 11:43:47.585  3826  3876 I jxcore-log: 
09-09 11:43:47.586  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 11:43:47.586  3826  3876 I jxcore-log: 
09-09 11:43:47.586  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 11:43:47.586  3826  3876 I jxcore-log: 
09-09 11:43:47.588  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 11:43:47.588  3826  3876 I jxcore-log: 
09-09 11:43:47.588  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 11:43:47.588  3826  3876 I jxcore-log: 
09-09 11:43:47.589  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 11:43:47.589  3826  3876 I jxcore-log: 
,09-09 11:43:47.590  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 11:43:47.590  3826  3876 I jxcore-log: 
09-09 11:43:47.590  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 11:43:47.590  3826  3876 I jxcore-log: 
,09-09 11:43:47.591  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 11:43:47.591  3826  3876 I jxcore-log: 
09-09 11:43:47.592  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 11:43:47.592  3826  3876 I jxcore-log: 
09-09 11:43:47.593  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 11:43:47.593  3826  3876 I jxcore-log: 
09-09 11:43:47.594  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 11:43:47.594  3826  3876 I jxcore-log: 
,09-09 11:43:47.595  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 11:43:47.595  3826  3876 I jxcore-log: 
09-09 11:43:47.595  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 11:43:47.595  3826  3876 I jxcore-log: 
09-09 11:43:47.596  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 11:43:47.596  3826  3876 I jxcore-log: 
,09-09 11:43:47.597  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 11:43:47.597  3826  3876 I jxcore-log: 
,09-09 11:43:47.599  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 11:43:47.599  3826  3876 I jxcore-log: 
,09-09 11:43:47.599  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 11:43:47.599  3826  3876 I jxcore-log: 
,09-09 11:43:47.600  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 11:43:47.600  3826  3876 I jxcore-log: 
09-09 11:43:47.600  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 11:43:47.600  3826  3876 I jxcore-log: 
09-09 11:43:47.600  3826  4330 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 454, name: My test thread name), during the lifetime of the thread the total number of bytes read was 132 and the total number of bytes written 132
,09-09 11:43:47.601  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 11:43:47.601  3826  3876 I jxcore-log: 
,09-09 11:43:47.602  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 11:43:47.602  3826  3876 I jxcore-log: ,
09-09 11:43:47.602  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 11:43:47.602  3826  3876 I jxcore-log: 
09-09 11:43:47.603  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 11:43:47.603  3826  3876 I jxcore-log: 
09-09 11:43:47.603  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
,09-09 11:43:47.603  3826  3876 I jxcore-log: 
09-09 11:43:47.604  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 11:43:47.604  3826  3876 I jxcore-log: 
09-09 11:43:47.604  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 11:43:47.604  3826  3876 I jxcore-log: 
09-09 11:43:47.605  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,09-09 11:43:47.605  3826  3876 I jxcore-log: 
09-09 11:43:47.605  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 11:43:47.605  3826  3876 I jxcore-log: 
09-09 11:43:47.606  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 11:43:47.606  3826  3876 I jxcore-log: 
09-09 11:43:47.606  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 11:43:47.606  3826  3876 I jxcore-log: 
,09-09 11:43:47.607  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 11:43:47.607  3826  3876 I jxcore-log: 
09-09 11:43:47.608  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 11:43:47.608  3826  3876 I jxcore-log: 
09-09 11:43:47.608  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-09 11:43:47.608  3826  3876 I jxcore-log: ,
09-09 11:43:47.609  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 11:43:47.609  3826  3876 I jxcore-log: 
09-09 11:43:47.609  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 11:43:47.609  3826  3876 I jxcore-log: 
09-09 11:43:47.610  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
09-09 11:43:47.610  3826  3876 I jxcore-log: 
09-09 11:43:47.610  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 11:43:47.610  3826  3876 I jxcore-log: 
,09-09 11:43:47.611  3826  3876 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 11:43:47.611  3826  3876 I jxcore-log: 
09-09 11:43:47.616  3826  3876 I jxcore-log: Network status after Unit Tests:  { bluetoothLowEnergy: 'on',
09-09 11:43:47.616  3826  3876 I jxcore-log:   bluetooth: 'on',
09-09 11:43:47.616  3826  3876 I jxcore-log:   wifi: 'on',
09-09 11:43:47.616  3826  3876 I jxcore-log:   cellular: 'doNotCare',
,09-09 11:43:47.616  3826  3876 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-09 11:43:47.616  3826  3876 I jxcore-log: 
,09-09 11:43:47.621  3826  3876 I jxcore-log: Network status before Coordination Tests:  { bluetoothLowEnergy: 'on',,
09-09 11:43:47.621  3826  3876 I jxcore-log:   bluetooth: 'on',
09-09 11:43:47.621  3826  3876 I jxcore-log:   wifi: 'on',
09-09 11:43:47.621  3826  3876 I jxcore-log:   cellular: 'doNotCare',
09-09 11:43:47.621  3826  3876 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-09 11:43:47.621  3826  3876 I jxcore-log: 
09-09 11:43:47.622  3826  3876 I jxcore-log: My device name is: motorola-Nexus 6
,09-09 11:43:47.622  3826  3876 I jxcore-log: 
09-09 11:43:47.623  3826  3876 I jxcore-log: Running for WIFI network type
09-09 11:43:47.623  3826  3876 I jxcore-log: 
,09-09 11:43:50.084  3826  3876 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-09 11:43:50.084  3826  3876 I jxcore-log: 
,09-09 11:43:50.539  3826  3876 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-09 11:43:50.539  3826  3876 I jxcore-log: 
,09-09 11:43:50.573  3826  3876 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
09-09 11:43:50.573  3826  3876 I jxcore-log: 
,09-09 11:43:51.489  3755  4333 V KeepSync: Connecting to GoogleApiClient
,09-09 11:43:51.490   874  1948 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 11:43:51.534  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:43:51.537  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:43:51.553  1524  2122 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-09 11:43:51.554  1524  2122 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-09 11:43:51.554  1524  2122 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 11:43:51.554  1524  2122 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:43:51.566  1751  4334 V BaseAuthAsyncOperation: access token request failed
,09-09 11:43:51.568  3755  4333 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 11:43:51.608  1524  2892 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-09 11:43:51.608  1524  2892 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-09 11:43:51.608  1524  2892 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 11:43:51.608  1524  2892 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:43:51.638  3755  4333 E KeepSync: IOException
09-09 11:43:51.638  3755  4333 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 11:43:51.638  3755  4333 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 11:43:51.638  3755  4333 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 11:43:51.638  3755  4333 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 11:43:51.638  3755  4333 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 11:43:51.638  3755  4333 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 11:43:51.638  3755  4333 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 11:43:51.638  3755  4333 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 11:43:51.638  3755  4333 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 11:43:51.638  3755  4333 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 11:43:51.638  3755  4333 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 11:43:51.638  3755  4333 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 11:43:51.638  3755  4333 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 11:43:51.638  3755  4333 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 11:43:51.638  3755  4333 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 11:43:51.638  3755  4333 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 11:43:51.638  3755  4333 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 11:43:51.638  3755  4333 E KeepSync: 	... 10 more
,09-09 11:43:51.638  3755  4333 W KeepSync: Sync result 2
,09-09 11:43:51.643   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 243346, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 11:43:52.014  3826  3876 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
09-09 11:43:52.014  3826  3876 I jxcore-log: 
,09-09 11:43:52.261  3826  3876 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-09 11:43:52.261  3826  3876 I jxcore-log: 
,09-09 11:43:52.266  3826  3876 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
09-09 11:43:52.266  3826  3876 I jxcore-log: 
,09-09 11:43:52.273  3826  3876 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
09-09 11:43:52.273  3826  3876 I jxcore-log: 
,09-09 11:43:52.542  3826  3876 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-09 11:43:52.542  3826  3876 I jxcore-log: 
,09-09 11:43:52.558  3826  3876 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-09 11:43:52.558  3826  3876 I jxcore-log: 
,09-09 11:43:52.562  3826  3876 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js
09-09 11:43:52.562  3826  3876 I jxcore-log: 
,09-09 11:43:53.276  3826  3876 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js
09-09 11:43:53.276  3826  3876 I jxcore-log: 
,09-09 11:43:53.448  3826  3876 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-09 11:43:53.448  3826  3876 I jxcore-log: 
,09-09 11:43:53.785  3826  3876 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-09 11:43:53.785  3826  3876 I jxcore-log: 
,09-09 11:43:53.795  3826  3876 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-09 11:43:53.795  3826  3876 I jxcore-log: 
,09-09 11:43:53.803  3826  3876 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
09-09 11:43:53.803  3826  3876 I jxcore-log: 
,09-09 11:43:53.810  3826  3876 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
09-09 11:43:53.810  3826  3876 I jxcore-log: 
,09-09 11:43:53.851  3826  3876 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
09-09 11:43:53.851  3826  3876 I jxcore-log: 
,09-09 11:43:53.899  3826  3876 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
09-09 11:43:53.899  3826  3876 I jxcore-log: 
,09-09 11:43:53.906  3826  3876 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
09-09 11:43:53.906  3826  3876 I jxcore-log: 
,09-09 11:43:53.914  3826  3876 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
09-09 11:43:53.914  3826  3876 I jxcore-log: 
,09-09 11:43:53.935  3826  3876 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
09-09 11:43:53.935  3826  3876 I jxcore-log: 
,09-09 11:43:53.940  3826  3876 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
09-09 11:43:53.940  3826  3876 I jxcore-log: 
,09-09 11:43:53.946  3826  3876 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
09-09 11:43:53.946  3826  3876 I jxcore-log: 
,09-09 11:43:53.962  3826  3876 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
09-09 11:43:53.962  3826  3876 I jxcore-log: 
,09-09 11:43:53.989  3826  3876 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
09-09 11:43:53.989  3826  3876 I jxcore-log: 
,09-09 11:43:54.001  3826  3876 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
09-09 11:43:54.001  3826  3876 I jxcore-log: 
,09-09 11:43:54.015  3826  3876 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
09-09 11:43:54.015  3826  3876 I jxcore-log: 
,09-09 11:43:54.027  3826  3876 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
09-09 11:43:54.027  3826  3876 I jxcore-log: 
,09-09 11:43:54.043  3826  3876 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
09-09 11:43:54.043  3826  3876 I jxcore-log: 
,09-09 11:43:54.054  3826  3876 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
09-09 11:43:54.054  3826  3876 I jxcore-log: 
,09-09 11:43:54.060  3826  3876 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
09-09 11:43:54.060  3826  3876 I jxcore-log: 
,09-09 11:43:54.091  3826  3876 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
09-09 11:43:54.091  3826  3876 I jxcore-log: 
,09-09 11:43:54.102  3826  3876 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-09 11:43:54.104  3826  3876 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
09-09 11:43:54.104  3826  3876 I jxcore-log: 
,09-09 11:43:54.106  3826  3876 I jxcore-log: ThaliTestRunner :: Running ThaliTape
09-09 11:43:54.106  3826  3876 I jxcore-log: 
09-09 11:43:54.106  3826  3876 I jxcore-log: ThaliTape :: Started ThaliTape
09-09 11:43:54.106  3826  3876 I jxcore-log: 
,09-09 11:43:54.111  3826  3876 I jxcore-log: ThaliTape ::  Connecting to  http://85.14.110.168:3000/
09-09 11:43:54.111  3826  3876 I jxcore-log: 
,09-09 11:43:54.183  3826  3876 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 11:43:54.183  3826  3876 I jxcore-log: 
09-09 11:43:54.184  3826  3876 I jxcore-log: websocket error
09-09 11:43:54.184  3826  3876 I jxcore-log: 
09-09 11:43:54.184  3826  3876 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 11:43:54.184  3826  3876 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 11:43:54.184  3826  3876 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 11:43:54.184  3826  3876 I jxcore-log: emit@events.js:82:1
09-09 11:43:54.184  3826  3876 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 11:43:54.184  3826  3876 I jxcore-log: emit@events.js:82:1
09-09 11:43:54.184  3826  3876 I jxcore-log: 
,09-09 11:43:55.036  3826  3876 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 11:43:55.036  3826  3876 I jxcore-log: 
09-09 11:43:55.038  3826  3876 I jxcore-log: websocket error
09-09 11:43:55.038  3826  3876 I jxcore-log: 
09-09 11:43:55.038  3826  3876 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 11:43:55.038  3826  3876 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 11:43:55.038  3826  3876 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 11:43:55.038  3826  3876 I jxcore-log: emit@events.js:82:1
09-09 11:43:55.038  3826  3876 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 11:43:55.038  3826  3876 I jxcore-log: emit@events.js:82:1
09-09 11:43:55.038  3826  3876 I jxcore-log: 
,09-09 11:43:55.636  1524  2218 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-09 11:43:56.684  3826  3876 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 11:43:56.684  3826  3876 I jxcore-log: 
,09-09 11:43:56.685  3826  3876 I jxcore-log: websocket error
09-09 11:43:56.685  3826  3876 I jxcore-log: 
,09-09 11:43:56.685  3826  3876 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 11:43:56.685  3826  3876 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 11:43:56.685  3826  3876 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 11:43:56.685  3826  3876 I jxcore-log: emit@events.js:82:1
09-09 11:43:56.685  3826  3876 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 11:43:56.685  3826  3876 I jxcore-log: emit@events.js:82:1
09-09 11:43:56.685  3826  3876 I jxcore-log: ,
,09-09 11:44:00.309  3826  3876 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 11:44:00.309  3826  3876 I jxcore-log: 
,09-09 11:44:00.310  3826  3876 I jxcore-log: websocket error
09-09 11:44:00.310  3826  3876 I jxcore-log: 
,09-09 11:44:00.310  3826  3876 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 11:44:00.310  3826  3876 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 11:44:00.310  3826  3876 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 11:44:00.310  3826  3876 I jxcore-log: emit@events.js:82:1
09-09 11:44:00.310  3826  3876 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 11:44:00.310  3826  3876 I jxcore-log: emit@events.js:82:1
09-09 11:44:00.310  3826  3876 I jxcore-log: 
,09-09 11:44:03.072   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=255057, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 11:44:05.381  3826  3876 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 11:44:05.381  3826  3876 I jxcore-log: 
,09-09 11:44:05.381  3826  3876 I jxcore-log: websocket error
09-09 11:44:05.381  3826  3876 I jxcore-log: 
,09-09 11:44:05.382  3826  3876 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 11:44:05.382  3826  3876 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 11:44:05.382  3826  3876 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 11:44:05.382  3826  3876 I jxcore-log: emit@events.js:82:1
09-09 11:44:05.382  3826  3876 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 11:44:05.382  3826  3876 I jxcore-log: emit@events.js:82:1
09-09 11:44:05.382  3826  3876 I jxcore-log: 
,09-09 11:44:10.346   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=262331, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-09 11:44:10.433  3826  3876 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 11:44:10.433  3826  3876 I jxcore-log: 
,09-09 11:44:10.433  3826  3876 I jxcore-log: websocket error
09-09 11:44:10.433  3826  3876 I jxcore-log: 
,09-09 11:44:10.433  3826  3876 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 11:44:10.433  3826  3876 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 11:44:10.433  3826  3876 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 11:44:10.433  3826  3876 I jxcore-log: emit@events.js:82:1
09-09 11:44:10.433  3826  3876 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 11:44:10.433  3826  3876 I jxcore-log: emit@events.js:82:1
09-09 11:44:10.433  3826  3876 I jxcore-log: 
,09-09 11:44:15.490  3826  3876 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 11:44:15.490  3826  3876 I jxcore-log: 
,09-09 11:44:15.490  3826  3876 I jxcore-log: websocket error
09-09 11:44:15.490  3826  3876 I jxcore-log: 
,09-09 11:44:15.491  3826  3876 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 11:44:15.491  3826  3876 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 11:44:15.491  3826  3876 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 11:44:15.491  3826  3876 I jxcore-log: emit@events.js:82:1
09-09 11:44:15.491  3826  3876 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 11:44:15.491  3826  3876 I jxcore-log: emit@events.js:82:1
09-09 11:44:15.491  3826  3876 I jxcore-log: 
,09-09 11:44:20.559  3826  3876 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 11:44:20.559  3826  3876 I jxcore-log: 
,09-09 11:44:20.559  3826  3876 I jxcore-log: websocket error
09-09 11:44:20.559  3826  3876 I jxcore-log: 
09-09 11:44:20.559  3826  3876 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 11:44:20.559  3826  3876 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 11:44:20.559  3826  3876 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 11:44:20.559  3826  3876 I jxcore-log: emit@events.js:82:1
09-09 11:44:20.559  3826  3876 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 11:44:20.559  3826  3876 I jxcore-log: emit@events.js:82:1
09-09 11:44:20.559  3826  3876 I jxcore-log: 
,09-09 11:44:22.029  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:44:22.031  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:44:22.078  1524  2892 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 11:44:22.078  1524  2892 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 11:44:22.078  1524  2892 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 11:44:22.078  1524  2892 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:44:22.108  3562  4337 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 11:44:22.108  3562  4337 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 11:44:22.108  3562  4337 E HttpOperation: 	at jdm.a(PG:82)
09-09 11:44:22.108  3562  4337 E HttpOperation: 	at jcs.o(PG:406)
09-09 11:44:22.108  3562  4337 E HttpOperation: 	at jcn.a(PG:1379)
09-09 11:44:22.108  3562  4337 E HttpOperation: 	at jcs.i(PG:143)
09-09 11:44:22.108  3562  4337 E HttpOperation: 	at blb.a(PG:3937)
09-09 11:44:22.108  3562  4337 E HttpOperation: 	at czp.a(PG:18188)
09-09 11:44:22.108  3562  4337 E HttpOperation: 	at czp.a(PG:9081)
09-09 11:44:22.108  3562  4337 E HttpOperation: 	at czq.run(PG:1686)
09-09 11:44:22.108  3562  4337 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 11:44:22.108  3562  4337 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 11:44:22.108  3562  4337 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 11:44:22.108  3562  4337 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 11:44:22.108  3562  4337 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 11:44:22.108  3562  4337 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 11:44:22.108  3562  4337 E HttpOperation: 	at jdj.a(PG:4091)
09-09 11:44:22.108  3562  4337 E HttpOperation: 	at jdj.a(PG:1125)
09-09 11:44:22.108  3562  4337 E HttpOperation: 	at jdm.a(PG:77)
09-09 11:44:22.108  3562  4337 E HttpOperation: 	... 12 more
09-09 11:44:22.108  3562  4337 E HttpOperation: Caused by: faj: BadAuthentication
09-09 11:44:22.108  3562  4337 E HttpOperation: 	at fal.a(PG:38)
09-09 11:44:22.108  3562  4337 E HttpOperation: 	at jdj.a(PG:4089)
09-09 11:44:22.108  3562  4337 E HttpOperation: 	... 14 more
,09-09 11:44:22.197  1524  3636 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 11:44:22.198  1524  3636 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-09 11:44:22.198  1524  3636 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 11:44:22.198  1524  3636 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,09-09 11:44:22.233  3562  4337 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 11:44:22.233  3562  4337 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 11:44:22.233  3562  4337 E HttpOperation: 	at jdm.a(PG:82)
09-09 11:44:22.233  3562  4337 E HttpOperation: 	at jcs.o(PG:406)
09-09 11:44:22.233  3562  4337 E HttpOperation: 	at jcn.a(PG:1379)
09-09 11:44:22.233  3562  4337 E HttpOperation: 	at jcs.i(PG:143)
09-09 11:44:22.233  3562  4337 E HttpOperation: 	at hec.a(PG:42)
09-09 11:44:22.233  3562  4337 E HttpOperation: 	at hee.a(PG:102)
09-09 11:44:22.233  3562  4337 E HttpOperation: 	at czr.a(PG:65)
09-09 11:44:22.233  3562  4337 E HttpOperation: 	at kka.a(PG:108)
09-09 11:44:22.233  3562  4337 E HttpOperation: 	at czp.a(PG:19176)
09-09 11:44:22.233  3562  4337 E HttpOperation: 	at czp.a(PG:9081)
09-09 11:44:22.233  3562  4337 E HttpOperation: 	at czq.run(PG:1686)
09-09 11:44:22.233  3562  4337 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 11:44:22.233  3562  4337 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 11:44:22.233  3562  4337 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 11:44:22.233  3562  4337 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 11:44:22.233  3562  4337 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 11:44:22.233  3562  4337 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 11:44:22.233  3562  4337 E HttpOperation: 	at jdj.a(PG:4091)
09-09 11:44:22.233  3562  4337 E HttpOperation: 	at jdj.a(PG:1125)
09-09 11:44:22.233  3562  4337 E HttpOperation: 	at jdm.a(PG:77)
09-09 11:44:22.233  3562  4337 E HttpOperation: 	... 15 more
09-09 11:44:22.233  3562  4337 E HttpOperation: Caused by: faj: BadAuthentication
09-09 11:44:22.233  3562  4337 E HttpOperation: 	at fal.a(PG:38)
09-09 11:44:22.233  3562  4337 E HttpOperation: 	at jdj.a(PG:4089)
09-09 11:44:22.233  3562  4337 E HttpOperation: 	... 17 more
,09-09 11:44:22.233  3562  4337 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 11:44:22.233  3562  4337 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 11:44:22.233  3562  4337 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 11:44:22.233  3562  4337 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 11:44:22.233  3562  4337 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 11:44:22.233  3562  4337 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 11:44:22.233  3562  4337 E ExperimentLoader: 	at hec.a(PG:42)
09-09 11:44:22.233  3562  4337 E ExperimentLoader: 	at hee.a(PG:102)
09-09 11:44:22.233  3562  4337 E ExperimentLoader: 	at czr.a(PG:65),
09-09 11:44:22.233  3562  4337 E ExperimentLoader: 	at kka.a(PG:108)
09-09 11:44:22.233  3562  4337 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 11:44:22.233  3562  4337 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 11:44:22.233  3562  4337 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 11:44:22.233  3562  4337 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 11:44:22.233  3562  4337 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 11:44:22.233  3562  4337 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 11:44:22.233  3562  4337 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 11:44:22.233  3562  4337 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 11:44:22.233  3562  4337 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 11:44:22.233  3562  4337 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 11:44:22.233  3562  4337 E ExperimentLoader: 	at jdj.a(PG:1125)
09-09 11:44:22.233  3562  4337 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 11:44:22.233  3562  4337 E ExperimentLoader: 	... 15 more
09-09 11:44:22.233  3562  4337 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 11:44:22.233  3562  4337 E ExperimentLoader: 	at fal.a(PG:38)
09-09 11:44:22.233  3562  4337 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 11:44:22.233  3562  4337 E ExperimentLoader: 	... 17 more
,09-09 11:44:22.375   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 250466, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-09 11:44:25.615  3826  3876 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 11:44:25.615  3826  3876 I jxcore-log: 
,09-09 11:44:25.616  3826  3876 I jxcore-log: websocket error
09-09 11:44:25.616  3826  3876 I jxcore-log: 
09-09 11:44:25.616  3826  3876 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 11:44:25.616  3826  3876 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 11:44:25.616  3826  3876 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 11:44:25.616  3826  3876 I jxcore-log: emit@events.js:82:1
09-09 11:44:25.616  3826  3876 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 11:44:25.616  3826  3876 I jxcore-log: emit@events.js:82:1
09-09 11:44:25.616  3826  3876 I jxcore-log: 
,09-09 11:44:30.705  3826  3876 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 11:44:30.705  3826  3876 I jxcore-log: 
,09-09 11:44:30.706  3826  3876 I jxcore-log: websocket error
09-09 11:44:30.706  3826  3876 I jxcore-log: 
09-09 11:44:30.706  3826  3876 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 11:44:30.706  3826  3876 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 11:44:30.706  3826  3876 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 11:44:30.706  3826  3876 I jxcore-log: emit@events.js:82:1
09-09 11:44:30.706  3826  3876 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 11:44:30.706  3826  3876 I jxcore-log: emit@events.js:82:1
09-09 11:44:30.706  3826  3876 I jxcore-log: 
,09-09 11:44:35.794  3826  3876 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 11:44:35.794  3826  3876 I jxcore-log: 
09-09 11:44:35.794  3826  3876 I jxcore-log: websocket error
09-09 11:44:35.794  3826  3876 I jxcore-log: 
,09-09 11:44:35.795  3826  3876 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 11:44:35.795  3826  3876 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 11:44:35.795  3826  3876 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 11:44:35.795  3826  3876 I jxcore-log: emit@events.js:82:1
09-09 11:44:35.795  3826  3876 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 11:44:35.795  3826  3876 I jxcore-log: emit@events.js:82:1
09-09 11:44:35.795  3826  3876 I jxcore-log: 
,09-09 11:44:40.869  3826  3876 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 11:44:40.869  3826  3876 I jxcore-log: 
09-09 11:44:40.869  3826  3876 I jxcore-log: websocket error
09-09 11:44:40.869  3826  3876 I jxcore-log: 
09-09 11:44:40.870  3826  3876 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 11:44:40.870  3826  3876 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 11:44:40.870  3826  3876 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 11:44:40.870  3826  3876 I jxcore-log: emit@events.js:82:1
09-09 11:44:40.870  3826  3876 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 11:44:40.870  3826  3876 I jxcore-log: emit@events.js:82:1
09-09 11:44:40.870  3826  3876 I jxcore-log: 
,09-09 11:44:45.937  3826  3876 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 11:44:45.937  3826  3876 I jxcore-log: 
09-09 11:44:45.937  3826  3876 I jxcore-log: websocket error
09-09 11:44:45.937  3826  3876 I jxcore-log: 
09-09 11:44:45.938  3826  3876 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 11:44:45.938  3826  3876 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 11:44:45.938  3826  3876 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 11:44:45.938  3826  3876 I jxcore-log: emit@events.js:82:1
09-09 11:44:45.938  3826  3876 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 11:44:45.938  3826  3876 I jxcore-log: emit@events.js:82:1
09-09 11:44:45.938  3826  3876 I jxcore-log: 
,09-09 11:44:51.000  3826  3876 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 11:44:51.000  3826  3876 I jxcore-log: 
,09-09 11:44:51.000  3826  3876 I jxcore-log: websocket error
09-09 11:44:51.000  3826  3876 I jxcore-log: 
09-09 11:44:51.000  3826  3876 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 11:44:51.000  3826  3876 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 11:44:51.000  3826  3876 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 11:44:51.000  3826  3876 I jxcore-log: emit@events.js:82:1
09-09 11:44:51.000  3826  3876 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 11:44:51.000  3826  3876 I jxcore-log: emit@events.js:82:1
09-09 11:44:51.000  3826  3876 I jxcore-log: 
,09-09 11:44:52.581  3767  4344 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 11:44:52.620  3767  4345 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 11:44:52.633  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:44:52.635  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:44:52.665  1524  2122 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-09 11:44:52.665  1524  2122 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 11:44:52.665  1524  2122 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 11:44:52.665  1524  2122 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:44:52.705  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:44:52.708  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:44:52.752  1524  2307 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-09 11:44:52.752  1524  2307 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-09 11:44:52.753  1524  2307 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 11:44:52.753  1524  2307 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:44:52.778  3767  4345 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 11:44:52.779  3767  4344 E BooksSync: Soft error
09-09 11:44:52.779  3767  4344 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 11:44:52.779  3767  4344 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 11:44:52.779  3767  4344 E BooksSync: Sync error
09-09 11:44:52.779  3767  4344 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 11:44:52.779  3767  4344 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 11:44:52.779  3767  4344 I BooksSync: Finished books sync
,09-09 11:44:52.791   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 288313, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 11:44:53.559   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=305544, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 11:44:56.059  3826  3876 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 11:44:56.059  3826  3876 I jxcore-log: 
,09-09 11:44:56.059  3826  3876 I jxcore-log: websocket error
09-09 11:44:56.059  3826  3876 I jxcore-log: 
09-09 11:44:56.060  3826  3876 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 11:44:56.060  3826  3876 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 11:44:56.060  3826  3876 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 11:44:56.060  3826  3876 I jxcore-log: emit@events.js:82:1
09-09 11:44:56.060  3826  3876 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 11:44:56.060  3826  3876 I jxcore-log: emit@events.js:82:1
09-09 11:44:56.060  3826  3876 I jxcore-log: 
,09-09 11:45:01.039   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=313024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-09 11:45:01.121  3826  3876 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 11:45:01.121  3826  3876 I jxcore-log: 
,09-09 11:45:01.122  3826  3876 I jxcore-log: websocket error
09-09 11:45:01.122  3826  3876 I jxcore-log: 
,09-09 11:45:01.122  3826  3876 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 11:45:01.122  3826  3876 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 11:45:01.122  3826  3876 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 11:45:01.122  3826  3876 I jxcore-log: emit@events.js:82:1,
09-09 11:45:01.122  3826  3876 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 11:45:01.122  3826  3876 I jxcore-log: emit@events.js:82:1
09-09 11:45:01.122  3826  3876 I jxcore-log: 
,09-09 11:45:06.182  3826  3876 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 11:45:06.182  3826  3876 I jxcore-log: 
,09-09 11:45:06.182  3826  3876 I jxcore-log: websocket error
09-09 11:45:06.182  3826  3876 I jxcore-log: 
,09-09 11:45:06.182  3826  3876 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 11:45:06.182  3826  3876 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 11:45:06.182  3826  3876 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 11:45:06.182  3826  3876 I jxcore-log: emit@events.js:82:1
09-09 11:45:06.182  3826  3876 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 11:45:06.182  3826  3876 I jxcore-log: emit@events.js:82:1
09-09 11:45:06.182  3826  3876 I jxcore-log: 
,09-09 11:45:11.231  3826  3876 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 11:45:11.231  3826  3876 I jxcore-log: 
,09-09 11:45:11.231  3826  3876 I jxcore-log: websocket error
09-09 11:45:11.231  3826  3876 I jxcore-log: 
09-09 11:45:11.231  3826  3876 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 11:45:11.231  3826  3876 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 11:45:11.231  3826  3876 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 11:45:11.231  3826  3876 I jxcore-log: emit@events.js:82:1
09-09 11:45:11.231  3826  3876 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 11:45:11.231  3826  3876 I jxcore-log: emit@events.js:82:1
09-09 11:45:11.231  3826  3876 I jxcore-log: 
,09-09 11:45:16.524  3826  3876 I jxcore-log: ThaliTape :: Reconnected to the test server
09-09 11:45:16.524  3826  3876 I jxcore-log: 
,09-09 11:45:16.542  3826  3876 I jxcore-log: ThaliTape :: Connected to the test server
09-09 11:45:16.542  3826  3876 I jxcore-log: 
,09-09 11:45:23.080  3755  4356 V KeepSync: Connecting to GoogleApiClient
09-09 11:45:23.080   874  1978 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 11:45:23.126  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:45:23.128  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:45:23.152  1524  2307 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-09 11:45:23.153  1524  2307 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-09 11:45:23.153  1524  2307 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 11:45:23.153  1524  2307 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:45:23.172  1751  4358 V BaseAuthAsyncOperation: access token request failed
,09-09 11:45:23.173  3755  4356 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 11:45:23.228  1524  2122 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 11:45:23.228  1524  2122 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 11:45:23.228  1524  2122 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 11:45:23.228  1524  2122 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:45:23.242  3562  4357 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 11:45:23.242  3562  4357 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 11:45:23.242  3562  4357 E HttpOperation: 	at jdm.a(PG:82)
09-09 11:45:23.242  3562  4357 E HttpOperation: 	at jcs.o(PG:406)
09-09 11:45:23.242  3562  4357 E HttpOperation: 	at jcn.a(PG:1379)
09-09 11:45:23.242  3562  4357 E HttpOperation: 	at jcs.i(PG:143)
09-09 11:45:23.242  3562  4357 E HttpOperation: 	at blb.a(PG:3937)
09-09 11:45:23.242  3562  4357 E HttpOperation: 	at czp.a(PG:18188)
09-09 11:45:23.242  3562  4357 E HttpOperation: 	at czp.a(PG:9081)
09-09 11:45:23.242  3562  4357 E HttpOperation: 	at czq.run(PG:1686)
09-09 11:45:23.242  3562  4357 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 11:45:23.242  3562  4357 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 11:45:23.242  3562  4357 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 11:45:23.242  3562  4357 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 11:45:23.242  3562  4357 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 11:45:23.242  3562  4357 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 11:45:23.242  3562  4357 E HttpOperation: 	at jdj.a(PG:4091)
09-09 11:45:23.242  3562  4357 E HttpOperation: 	at jdj.a(PG:1125)
09-09 11:45:23.242  3562  4357 E HttpOperation: 	at jdm.a(PG:77)
09-09 11:45:23.242  3562  4357 E HttpOperation: 	... 12 more
09-09 11:45:23.242  3562  4357 E HttpOperation: Caused by: faj: BadAuthentication
09-09 11:45:23.242  3562  4357 E HttpOperation: 	at fal.a(PG:38)
09-09 11:45:23.242  3562  4357 E HttpOperation: 	at jdj.a(PG:4089)
09-09 11:45:23.242  3562  4357 E HttpOperation: 	... 14 more
,09-09 11:45:23.291  1524  2892 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-09 11:45:23.291  1524  2892 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-09 11:45:23.291  1524  2892 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 11:45:23.291  1524  2892 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:45:23.307  3562  4357 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 11:45:23.307  3562  4357 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 11:45:23.307  3562  4357 E HttpOperation: 	at jdm.a(PG:82)
09-09 11:45:23.307  3562  4357 E HttpOperation: 	at jcs.o(PG:406)
09-09 11:45:23.307  3562  4357 E HttpOperation: 	at jcn.a(PG:1379)
09-09 11:45:23.307  3562  4357 E HttpOperation: 	at jcs.i(PG:143)
09-09 11:45:23.307  3562  4357 E HttpOperation: 	at hec.a(PG:42)
09-09 11:45:23.307  3562  4357 E HttpOperation: 	at hee.a(PG:102)
09-09 11:45:23.307  3562  4357 E HttpOperation: 	at czr.a(PG:65)
09-09 11:45:23.307  3562  4357 E HttpOperation: 	at kka.a(PG:108)
09-09 11:45:23.307  3562  4357 E HttpOperation: 	at czp.a(PG:19176)
09-09 11:45:23.307  3562  4357 E HttpOperation: 	at czp.a(PG:9081)
09-09 11:45:23.307  3562  4357 E HttpOperation: 	at czq.run(PG:1686)
09-09 11:45:23.307  3562  4357 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 11:45:23.307  3562  4357 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 11:45:23.307  3562  4357 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 11:45:23.307  3562  4357 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 11:45:23.307  3562  4357 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 11:45:23.307  3562  4357 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 11:45:23.307  3562  4357 E HttpOperation: 	at jdj.a(PG:4091)
09-09 11:45:23.307  3562  4357 E HttpOperation: 	at jdj.a(PG:1125)
09-09 11:45:23.307  3562  4357 E HttpOperation: 	at jdm.a(PG:77)
09-09 11:45:23.307  3562  4357 E HttpOperation: 	... 15 more
09-09 11:45:23.307  3562  4357 E HttpOperation: Caused by: faj: BadAuthentication
09-09 11:45:23.307  3562  4357 E HttpOperation: 	at fal.a(PG:38)
09-09 11:45:23.307  3562  4357 E HttpOperation: 	at jdj.a(PG:4089)
09-09 11:45:23.307  3562  4357 E HttpOperation: 	... 17 more
,09-09 11:45:23.308  3562  4357 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 11:45:23.308  3562  4357 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 11:45:23.308  3562  4357 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 11:45:23.308  3562  4357 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 11:45:23.308  3562  4357 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 11:45:23.308  3562  4357 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 11:45:23.308  3562  4357 E ExperimentLoader: 	at hec.a(PG:42)
09-09 11:45:23.308  3562  4357 E ExperimentLoader: 	at hee.a(PG:102)
09-09 11:45:23.308  3562  4357 E ExperimentLoader: 	at czr.a(PG:65)
09-09 11:45:23.308  3562  4357 E ExperimentLoader: 	at kka.a(PG:108)
09-09 11:45:23.308  3562  4357 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 11:45:23.308  3562  4357 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 11:45:23.308  3562  4357 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 11:45:23.308  3562  4357 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 11:45:23.308  3562  4357 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 11:45:23.308  3562  4357 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 11:45:23.308  3562  4357 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 11:45:23.308  3562  4357 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 11:45:23.308  3562  4357 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 11:45:23.308  3562  4357 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 11:45:23.308  3562  4357 E ExperimentLoader: 	at jdj.a(PG:1125)
09-09 11:45:23.308  3562  4357 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 11:45:23.308  3562  4357 E ExperimentLoader: 	... 15 more
09-09 11:45:23.308  3562  4357 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 11:45:23.308  3562  4357 E ExperimentLoader: 	at fal.a(PG:38)
09-09 11:45:23.308  3562  4357 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 11:45:23.308  3562  4357 E ExperimentLoader: 	... 17 more
,09-09 11:45:23.382  1524  3636 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-09 11:45:23.382  1524  3636 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-09 11:45:23.382  1524  3636 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 11:45:23.382  1524  3636 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:45:23.407  3755  4356 E KeepSync: IOException
09-09 11:45:23.407  3755  4356 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 11:45:23.407  3755  4356 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 11:45:23.407  3755  4356 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 11:45:23.407  3755  4356 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 11:45:23.407  3755  4356 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 11:45:23.407  3755  4356 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 11:45:23.407  3755  4356 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 11:45:23.407  3755  4356 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 11:45:23.407  3755  4356 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 11:45:23.407  3755  4356 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 11:45:23.407  3755  4356 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 11:45:23.407  3755  4356 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 11:45:23.407  3755  4356 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 11:45:23.407  3755  4356 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 11:45:23.407  3755  4356 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 11:45:23.407  3755  4356 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 11:45:23.407  3755  4356 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 11:45:23.407  3755  4356 E KeepSync: 	... 10 more
09-09 11:45:23.407  3755  4356 W KeepSync: Sync result 2
,09-09 11:45:23.417   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 306495, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
09-09 11:45:23.442   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 306090, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-09 11:45:30.764  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:45:30.776  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:45:30.780  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:45:30.848  1524  3636 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-09 11:45:30.848  1524  3636 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-09 11:45:30.848  1524  3636 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 11:45:30.849  1524  3636 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:45:30.889  1524  3636 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-09 11:45:30.889  1524  3636 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-09 11:45:30.889  1524  3636 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-09 11:45:30.889  1524  3636 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-09 11:45:30.889  1524  3636 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-09 11:45:30.889  1524  3636 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-09 11:45:30.889  1524  3636 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-09 11:45:30.897  3521  3554 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-09 11:45:30.897  3521  3554 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-09 11:45:30.897  3521  3554 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-09 11:45:30.897  3521  3554 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-09 11:45:30.897  3521  3554 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-09 11:45:30.897  3521  3554 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-09 11:45:30.897  3521  3554 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-09 11:45:53.544  3767  4364 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 11:45:53.592  3767  4365 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 11:45:53.608  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:45:53.610  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:45:53.635  1524  3636 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 11:45:53.635  1524  3636 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 11:45:53.635  1524  3636 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 11:45:53.636  1524  3636 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:45:53.667  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:45:53.669  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:45:53.693  1524  2307 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-09 11:45:53.693  1524  2307 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 11:45:53.693  1524  2307 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 11:45:53.693  1524  2307 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:45:53.710  3767  4365 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 11:45:53.711  3767  4364 E BooksSync: Soft error
09-09 11:45:53.711  3767  4364 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 11:45:53.711  3767  4364 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 11:45:53.711  3767  4364 E BooksSync: Sync error
09-09 11:45:53.711  3767  4364 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 11:45:53.711  3767  4364 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 11:45:53.711  3767  4364 I BooksSync: Finished books sync
,09-09 11:45:53.726   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 336729, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 11:46:22.147  1524  2218 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-09 11:46:27.208  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:46:27.210  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:46:27.242  1524  3636 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-09 11:46:27.242  1524  3636 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-09 11:46:27.242  1524  3636 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 11:46:27.242  1524  3636 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:46:27.273  3562  4373 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 11:46:27.273  3562  4373 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 11:46:27.273  3562  4373 E HttpOperation: 	at jdm.a(PG:82)
09-09 11:46:27.273  3562  4373 E HttpOperation: 	at jcs.o(PG:406)
09-09 11:46:27.273  3562  4373 E HttpOperation: 	at jcn.a(PG:1379)
09-09 11:46:27.273  3562  4373 E HttpOperation: 	at jcs.i(PG:143)
09-09 11:46:27.273  3562  4373 E HttpOperation: 	at blb.a(PG:3937)
09-09 11:46:27.273  3562  4373 E HttpOperation: 	at czp.a(PG:18188)
09-09 11:46:27.273  3562  4373 E HttpOperation: 	at czp.a(PG:9081)
09-09 11:46:27.273  3562  4373 E HttpOperation: 	at czq.run(PG:1686)
09-09 11:46:27.273  3562  4373 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 11:46:27.273  3562  4373 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 11:46:27.273  3562  4373 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 11:46:27.273  3562  4373 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 11:46:27.273  3562  4373 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 11:46:27.273  3562  4373 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 11:46:27.273  3562  4373 E HttpOperation: 	at jdj.a(PG:4091)
09-09 11:46:27.273  3562  4373 E HttpOperation: 	at jdj.a(PG:1125)
09-09 11:46:27.273  3562  4373 E HttpOperation: 	at jdm.a(PG:77)
09-09 11:46:27.273  3562  4373 E HttpOperation: 	... 12 more
09-09 11:46:27.273  3562  4373 E HttpOperation: Caused by: faj: BadAuthentication
09-09 11:46:27.273  3562  4373 E HttpOperation: 	at fal.a(PG:38)
09-09 11:46:27.273  3562  4373 E HttpOperation: 	at jdj.a(PG:4089)
09-09 11:46:27.273  3562  4373 E HttpOperation: 	... 14 more
,09-09 11:46:27.318  1524  2307 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 11:46:27.318  1524  2307 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 11:46:27.318  1524  2307 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 11:46:27.319  1524  2307 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:46:27.341  3562  4373 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 11:46:27.341  3562  4373 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 11:46:27.341  3562  4373 E HttpOperation: 	at jdm.a(PG:82)
09-09 11:46:27.341  3562  4373 E HttpOperation: 	at jcs.o(PG:406)
09-09 11:46:27.341  3562  4373 E HttpOperation: 	at jcn.a(PG:1379)
09-09 11:46:27.341  3562  4373 E HttpOperation: 	at jcs.i(PG:143)
09-09 11:46:27.341  3562  4373 E HttpOperation: 	at hec.a(PG:42)
09-09 11:46:27.341  3562  4373 E HttpOperation: 	at hee.a(PG:102)
09-09 11:46:27.341  3562  4373 E HttpOperation: 	at czr.a(PG:65)
09-09 11:46:27.341  3562  4373 E HttpOperation: 	at kka.a(PG:108)
09-09 11:46:27.341  3562  4373 E HttpOperation: 	at czp.a(PG:19176)
09-09 11:46:27.341  3562  4373 E HttpOperation: 	at czp.a(PG:9081)
09-09 11:46:27.341  3562  4373 E HttpOperation: 	at czq.run(PG:1686)
09-09 11:46:27.341  3562  4373 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 11:46:27.341  3562  4373 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 11:46:27.341  3562  4373 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 11:46:27.341  3562  4373 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 11:46:27.341  3562  4373 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 11:46:27.341  3562  4373 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 11:46:27.341  3562  4373 E HttpOperation: 	at jdj.a(PG:4091)
09-09 11:46:27.341  3562  4373 E HttpOperation: 	at jdj.a(PG:1125)
09-09 11:46:27.341  3562  4373 E HttpOperation: 	at jdm.a(PG:77)
09-09 11:46:27.341  3562  4373 E HttpOperation: 	... 15 more
09-09 11:46:27.341  3562  4373 E HttpOperation: Caused by: faj: BadAuthentication
09-09 11:46:27.341  3562  4373 E HttpOperation: 	at fal.a(PG:38)
09-09 11:46:27.341  3562  4373 E HttpOperation: 	at jdj.a(PG:4089)
09-09 11:46:27.341  3562  4373 E HttpOperation: 	... 17 more
,09-09 11:46:27.341  3562  4373 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 11:46:27.341  3562  4373 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 11:46:27.341  3562  4373 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 11:46:27.341  3562  4373 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 11:46:27.341  3562  4373 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 11:46:27.341  3562  4373 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 11:46:27.341  3562  4373 E ExperimentLoader: 	at hec.a(PG:42)
09-09 11:46:27.341  3562  4373 E ExperimentLoader: 	at hee.a(PG:102)
09-09 11:46:27.341  3562  4373 E ExperimentLoader: 	at czr.a(PG:65)
09-09 11:46:27.341  3562  4373 E ExperimentLoader: 	at kka.a(PG:108)
09-09 11:46:27.341  3562  4373 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 11:46:27.341  3562  4373 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 11:46:27.341  3562  4373 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 11:46:27.341  3562  4373 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 11:46:27.341  3562  4373 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 11:46:27.341  3562  4373 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 11:46:27.341  3562  4373 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 11:46:27.341  3562  4373 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 11:46:27.341  3562  4373 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 11:46:27.341  3562  4373 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 11:46:27.341  3562  4373 E ExperimentLoader: 	at jdj.a(PG:1125)
09-09 11:46:27.341  3562  4373 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 11:46:27.341  3562  4373 E ExperimentLoader: 	... 15 more
09-09 11:46:27.341  3562  4373 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 11:46:27.341  3562  4373 E ExperimentLoader: 	at fal.a(PG:38)
09-09 11:46:27.341  3562  4373 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 11:46:27.341  3562  4373 E ExperimentLoader: 	... 17 more
,09-09 11:46:27.444   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 398886, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-09 11:46:57.836  3767  4379 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 11:46:57.863  3767  4380 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 11:46:57.874  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:46:57.877  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:46:57.907  1524  1537 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-09 11:46:57.907  1524  1537 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-09 11:46:57.908  1524  1537 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 11:46:57.908  1524  1537 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:46:57.938  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:46:57.941  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:46:57.969  1524  2122 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 11:46:57.970  1524  2122 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 11:46:57.970  1524  2122 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 11:46:57.970  1524  2122 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:46:57.992  3767  4380 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 11:46:57.993  3767  4379 E BooksSync: Soft error
09-09 11:46:57.993  3767  4379 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 11:46:57.993  3767  4379 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 11:46:57.993  3767  4379 E BooksSync: Sync error
09-09 11:46:57.993  3767  4379 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 11:46:57.993  3767  4379 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 11:46:57.993  3767  4379 I BooksSync: Finished books sync
,09-09 11:46:58.009   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 429616, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 11:47:29.273  3755  4382 V KeepSync: Connecting to GoogleApiClient
,09-09 11:47:29.274   874  1948 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 11:47:29.351  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:47:29.357  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:47:29.431  1524  1537 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-09 11:47:29.432  1524  1537 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-09 11:47:29.432  1524  1537 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 11:47:29.433  1524  1537 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:47:29.477  1751  4383 V BaseAuthAsyncOperation: access token request failed
,09-09 11:47:29.479  3755  4382 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 11:47:29.580  1524  2892 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-09 11:47:29.580  1524  2892 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-09 11:47:29.580  1524  2892 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 11:47:29.581  1524  2892 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:47:29.620  3755  4382 E KeepSync: IOException
09-09 11:47:29.620  3755  4382 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 11:47:29.620  3755  4382 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 11:47:29.620  3755  4382 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 11:47:29.620  3755  4382 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 11:47:29.620  3755  4382 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 11:47:29.620  3755  4382 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 11:47:29.620  3755  4382 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 11:47:29.620  3755  4382 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 11:47:29.620  3755  4382 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 11:47:29.620  3755  4382 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 11:47:29.620  3755  4382 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 11:47:29.620  3755  4382 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 11:47:29.620  3755  4382 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 11:47:29.620  3755  4382 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 11:47:29.620  3755  4382 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 11:47:29.620  3755  4382 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 11:47:29.620  3755  4382 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 11:47:29.620  3755  4382 E KeepSync: 	... 10 more
,09-09 11:47:29.620  3755  4382 W KeepSync: Sync result 2
,09-09 11:47:29.633   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 461134, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 11:48:34.630  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:48:34.633  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:48:34.670  1524  2892 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 11:48:34.670  1524  2892 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 11:48:34.670  1524  2892 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 11:48:34.670  1524  2892 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:48:34.698  3562  4387 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 11:48:34.698  3562  4387 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 11:48:34.698  3562  4387 E HttpOperation: 	at jdm.a(PG:82)
09-09 11:48:34.698  3562  4387 E HttpOperation: 	at jcs.o(PG:406)
09-09 11:48:34.698  3562  4387 E HttpOperation: 	at jcn.a(PG:1379)
09-09 11:48:34.698  3562  4387 E HttpOperation: 	at jcs.i(PG:143)
09-09 11:48:34.698  3562  4387 E HttpOperation: 	at blb.a(PG:3937)
09-09 11:48:34.698  3562  4387 E HttpOperation: 	at czp.a(PG:18188)
09-09 11:48:34.698  3562  4387 E HttpOperation: 	at czp.a(PG:9081)
09-09 11:48:34.698  3562  4387 E HttpOperation: 	at czq.run(PG:1686)
09-09 11:48:34.698  3562  4387 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 11:48:34.698  3562  4387 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 11:48:34.698  3562  4387 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 11:48:34.698  3562  4387 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 11:48:34.698  3562  4387 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 11:48:34.698  3562  4387 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 11:48:34.698  3562  4387 E HttpOperation: 	at jdj.a(PG:4091)
09-09 11:48:34.698  3562  4387 E HttpOperation: 	at jdj.a(PG:1125)
09-09 11:48:34.698  3562  4387 E HttpOperation: 	at jdm.a(PG:77)
09-09 11:48:34.698  3562  4387 E HttpOperation: 	... 12 more
09-09 11:48:34.698  3562  4387 E HttpOperation: Caused by: faj: BadAuthentication
09-09 11:48:34.698  3562  4387 E HttpOperation: 	at fal.a(PG:38)
09-09 11:48:34.698  3562  4387 E HttpOperation: 	at jdj.a(PG:4089)
09-09 11:48:34.698  3562  4387 E HttpOperation: 	... 14 more
,09-09 11:48:34.784  1524  1537 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 11:48:34.784  1524  1537 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 11:48:34.784  1524  1537 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 11:48:34.784  1524  1537 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:48:34.814  3562  4387 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 11:48:34.814  3562  4387 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 11:48:34.814  3562  4387 E HttpOperation: 	at jdm.a(PG:82)
09-09 11:48:34.814  3562  4387 E HttpOperation: 	at jcs.o(PG:406)
09-09 11:48:34.814  3562  4387 E HttpOperation: 	at jcn.a(PG:1379)
09-09 11:48:34.814  3562  4387 E HttpOperation: 	at jcs.i(PG:143)
09-09 11:48:34.814  3562  4387 E HttpOperation: 	at hec.a(PG:42)
09-09 11:48:34.814  3562  4387 E HttpOperation: 	at hee.a(PG:102)
09-09 11:48:34.814  3562  4387 E HttpOperation: 	at czr.a(PG:65)
09-09 11:48:34.814  3562  4387 E HttpOperation: 	at kka.a(PG:108)
09-09 11:48:34.814  3562  4387 E HttpOperation: 	at czp.a(PG:19176)
09-09 11:48:34.814  3562  4387 E HttpOperation: 	at czp.a(PG:9081)
09-09 11:48:34.814  3562  4387 E HttpOperation: 	at czq.run(PG:1686)
09-09 11:48:34.814  3562  4387 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 11:48:34.814  3562  4387 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 11:48:34.814  3562  4387 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 11:48:34.814  3562  4387 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 11:48:34.814  3562  4387 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 11:48:34.814  3562  4387 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 11:48:34.814  3562  4387 E HttpOperation: 	at jdj.a(PG:4091)
09-09 11:48:34.814  3562  4387 E HttpOperation: 	at jdj.a(PG:1125)
09-09 11:48:34.814  3562  4387 E HttpOperation: 	at jdm.a(PG:77)
09-09 11:48:34.814  3562  4387 E HttpOperation: 	... 15 more
09-09 11:48:34.814  3562  4387 E HttpOperation: Caused by: faj: BadAuthentication
09-09 11:48:34.814  3562  4387 E HttpOperation: 	at fal.a(PG:38)
09-09 11:48:34.814  3562  4387 E HttpOperation: 	at jdj.a(PG:4089)
09-09 11:48:34.814  3562  4387 E HttpOperation: 	... 17 more
,09-09 11:48:34.814  3562  4387 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 11:48:34.814  3562  4387 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 11:48:34.814  3562  4387 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 11:48:34.814  3562  4387 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 11:48:34.814  3562  4387 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 11:48:34.814  3562  4387 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 11:48:34.814  3562  4387 E ExperimentLoader: 	at hec.a(PG:42)
09-09 11:48:34.814  3562  4387 E ExperimentLoader: 	at hee.a(PG:102)
09-09 11:48:34.814  3562  4387 E ExperimentLoader: 	at czr.a(PG:65)
09-09 11:48:34.814  3562  4387 E ExperimentLoader: 	at kka.a(PG:108)
09-09 11:48:34.814  3562  4387 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 11:48:34.814  3562  4387 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 11:48:34.814  3562  4387 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 11:48:34.814  3562  4387 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 11:48:34.814  3562  4387 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 11:48:34.814  3562  4387 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 11:48:34.814  3562  4387 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 11:48:34.814  3562  4387 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 11:48:34.814  3562  4387 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 11:48:34.814  3562  4387 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 11:48:34.814  3562  4387 E ExperimentLoader: 	at jdj.a(PG:1125)
09-09 11:48:34.814  3562  4387 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 11:48:34.814  3562  4387 E ExperimentLoader: 	... 15 more
09-09 11:48:34.814  3562  4387 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 11:48:34.814  3562  4387 E ExperimentLoader: 	at fal.a(PG:38)
09-09 11:48:34.814  3562  4387 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 11:48:34.814  3562  4387 E ExperimentLoader: 	... 17 more
,09-09 11:48:34.930   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 526346, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-09 11:49:05.895  3767  4390 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 11:49:05.948  3767  4391 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 11:49:05.963  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:49:05.966  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:49:06.009  1524  1537 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 11:49:06.010  1524  1537 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-09 11:49:06.010  1524  1537 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 11:49:06.010  1524  1537 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:49:06.046  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:49:06.051  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:49:06.083  1524  3636 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 11:49:06.084  1524  3636 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-09 11:49:06.084  1524  3636 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 11:49:06.084  1524  3636 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:49:06.107  3767  4391 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 11:49:06.108  3767  4390 E BooksSync: Soft error
09-09 11:49:06.108  3767  4390 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 11:49:06.108  3767  4390 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 11:49:06.108  3767  4390 E BooksSync: Sync error
09-09 11:49:06.108  3767  4390 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 11:49:06.108  3767  4390 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 11:49:06.108  3767  4390 I BooksSync: Finished books sync
,09-09 11:49:06.122   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 557803, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 11:54:46.305   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=898290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 11:54:58.265   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=910250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 11:55:09.505   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=921490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 11:55:23.318   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=935303, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 11:55:34.572   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=946557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 11:55:48.385   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=960370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 11:55:59.639   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=971624, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 11:56:13.466   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=985451, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 11:56:24.865   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=996850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 11:56:38.679   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1010664, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 11:56:49.932   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1021917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 11:57:03.745   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1035730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 11:57:14.999   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1046984, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 11:57:28.812   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1060797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 11:57:40.065   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1072050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 11:57:53.878   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1085863, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 11:58:05.132   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1097117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 11:58:18.945   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1110930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 11:58:19.892  3521  3521 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,09-09 11:58:19.917  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:58:19.929  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:58:19.935  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:58:20.021  1524  2307 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-09 11:58:20.022  1524  2307 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-09 11:58:20.022  1524  2307 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 11:58:20.023  1524  2307 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:58:20.083  3521  3521 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,09-09 11:58:20.126  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:58:20.195  1524  2122 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
09-09 11:58:20.195  1524  2122 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-09 11:58:20.195  1524  2122 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 11:58:20.195  1524  2122 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:58:20.234  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:58:20.295  1524  2307 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-09 11:58:20.295  1524  2307 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-09 11:58:20.296  1524  2307 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 11:58:20.296  1524  2307 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:58:20.366  3521  3521 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,09-09 11:58:20.627  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:58:20.682  1524  1537 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-09 11:58:20.682  1524  1537 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-09 11:58:20.682  1524  1537 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 11:58:20.682  1524  1537 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:58:20.723  3521  3521 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,09-09 11:58:20.724  3521  3521 D Finsky  : [1] WearSupportService.startHygiene: disabled
,09-09 11:58:20.726  3521  3521 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,09-09 11:58:20.734  3521  3597 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,09-09 11:58:20.737  3521  3521 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 28 minutes (failures=2)
,09-09 11:58:35.596  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:58:35.605  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:58:35.608  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:58:35.655  1524  2122 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-09 11:58:35.655  1524  2122 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-09 11:58:35.655  1524  2122 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 11:58:35.656  1524  2122 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:58:35.714  3521  3521 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-09 11:58:35.715  3521  3521 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-09 11:58:35.716  3521  3521 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,09-09 11:58:36.199   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1128184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 11:58:44.012   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1135997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 11:58:55.265   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1147250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 11:58:56.032  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:58:56.057  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:58:56.061  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:58:56.101  1524  3636 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-09 11:58:56.102  1524  3636 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-09 11:58:56.102  1524  3636 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 11:58:56.102  1524  3636 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,09-09 11:58:56.138  3521  3521 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-09 11:58:56.138  3521  3521 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-09 11:58:56.139  3521  3521 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,09-09 11:59:09.065   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1161050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 11:59:16.322  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:59:16.331  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:59:16.332  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:59:16.362  1524  2122 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-09 11:59:16.362  1524  2122 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-09 11:59:16.362  1524  2122 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 11:59:16.362  1524  2122 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,09-09 11:59:16.402  3521  3521 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-09 11:59:16.402  3521  3521 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-09 11:59:16.402  3521  3521 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-09 11:59:20.332   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1172317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 11:59:34.145   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1186130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 11:59:36.665  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:59:36.676  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:59:36.680  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:59:36.726  1524  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-09 11:59:36.726  1524  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-09 11:59:36.726  1524  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 11:59:36.726  1524  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:59:36.763  3521  3521 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-09 11:59:36.763  3521  3521 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-09 11:59:36.764  3521  3521 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-09 11:59:40.972   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1192957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 11:59:57.128  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:59:57.136  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:59:57.138  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 11:59:57.178  1524  2122 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-09 11:59:57.178  1524  2122 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-09 11:59:57.179  1524  2122 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 11:59:57.179  1524  2122 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 11:59:57.215  3521  3521 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-09 11:59:57.216  3521  3521 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-09 11:59:57.216  3521  3521 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-09 11:59:59.199   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1211184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 12:00:06.038   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1218023, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 12:00:06.638   874   886 I UsageStatsService: User[0] Flushing usage stats to disk
,09-09 12:00:17.490  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 12:00:17.500  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 12:00:17.502  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 12:00:17.535  1524  2122 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-09 12:00:17.536  1524  2122 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-09 12:00:17.536  1524  2122 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 12:00:17.536  1524  2122 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 12:00:17.567  3521  3521 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-09 12:00:17.567  3521  3521 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-09 12:00:17.568  3521  3521 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-09 12:00:24.265   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1236250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 12:00:31.425   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1243410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 12:00:49.665   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1261650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 12:00:56.492   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1268477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 12:01:14.759   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1286744, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 12:01:21.585   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1293570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 12:01:39.812   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1311797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 12:01:46.652   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1318637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 12:02:04.905   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1336890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 12:02:11.745   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1343730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 12:02:29.985   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1361970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 12:02:36.839   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1368824, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 12:02:55.065   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1387050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 12:03:01.892   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1393877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 12:03:20.119   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1412104, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 12:03:26.945   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1418930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 12:03:45.185   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1437170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 12:03:52.012   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1443997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 12:04:10.239   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1462224, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 12:04:17.078   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1469063, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 12:04:35.318   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1487303, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 12:04:38.958   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1490943, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 12:05:00.372   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1512357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 12:05:04.011   874  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1515997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,TIME-OUT KILL (timeout was 1400000ms),09-09 12:05:20.635  4441  4441 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-09 12:05:20.639  4441  4441 D AndroidRuntime: CheckJNI is OFF
09-09 12:05:20.675  4441  4441 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-09 12:05:20.716  4441  4441 I Radio-JNI: register_android_hardware_Radio DONE
09-09 12:05:20.736  4441  4441 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-09 12:05:20.748   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
09-09 12:05:20.749   874   887 I ActivityManager: Killing 3826:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
09-09 12:05:20.866   874   897 W PackageSettings: Skipping PackageSetting{fef1ef7 com.example.hello/10273} due to missing metadata
09-09 12:05:20.886   874  1308 D WifiService: Client connection lost with reason: 4
09-09 12:05:20.887   874  1977 I WindowState: WIN DEATH: Window{d2a6a44 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-09 12:05:20.886   874  1383 D GraphicsStats: Buffer count: 2
09-09 12:05:20.906   874   897 I art     : Starting a blocking GC Explicit
09-09 12:05:20.948   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-09 12:05:20.948   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-09 12:05:20.948   874   887 E ActivityManager: Failure starting process com.test.thalitest
09-09 12:05:20.948   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-09 12:05:20.948   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-09 12:05:20.948   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-09 12:05:20.948   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-09 12:05:20.948   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-09 12:05:20.948   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-09 12:05:20.948   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-09 12:05:20.948   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-09 12:05:20.948   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-09 12:05:20.948   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-09 12:05:20.948   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-09 12:05:20.948   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-09 12:05:20.948   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-09 12:05:20.948   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-09 12:05:20.948   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-09 12:05:20.948   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 12:05:20.948   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-09 12:05:20.948   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 12:05:20.948   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-09 12:05:20.950   874   887 I ActivityManager:   Force finishing activity ActivityRecord{683b195 u0 com.test.thalitest/.MainActivity t4}
09-09 12:05:20.955   874  1981 W ActivityManager: Spurious death for ProcessRecord{9c72769 0:com.test.thalitest/u0a0}, curProc for 3826: null
09-09 12:05:20.984   874   897 I art     : Explicit concurrent mark sweep GC freed 45875(3MB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 29MB/43MB, paused 794us total 75.199ms
09-09 12:05:21.003   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-09 12:05:21.005  4441  4441 I art     : System.exit called, status: 0
09-09 12:05:21.005  4441  4441 I AndroidRuntime: VM exiting with result code 0.
09-09 12:05:21.009   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
09-09 12:05:21.031   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-09 12:05:21.036  2123  2278 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-09 12:05:21.038  4231  4231 D BluetoothMapAppObserver: onReceive
09-09 12:05:21.038  4231  4231 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-09 12:05:21.041  3644  3644 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-09 12:05:21.045   874  1299 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-09 12:05:21.077  1861  1861 I Keyboard.Facilitator: resetDictionaries() : en_US
09-09 12:05:21.086   874  1948 I ActivityManager: Start proc 4456:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
09-09 12:05:21.089  1927  1927 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-09 12:05:21.105  1861  4467 I Keyboard.Facilitator.DecoderInitializer: run()
09-09 12:05:21.109  1861  4467 I Decoder : createOrResetDecoder
09-09 12:05:21.134  1524  1524 I ConfigService: onCreate
09-09 12:05:21.139  1524  4470 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-09 12:05:21.139  1524  4470 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 12:05:21.139  1524  4470 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 12:05:21.139  1524  4470 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 12:05:21.139  1524  4470 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 12:05:21.139  1524  4470 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 12:05:21.139  1524  4470 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 12:05:21.139  1524  4470 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 12:05:21.139  1524  4470 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 12:05:21.139  1524  4470 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 12:05:21.139  1524  4470 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 12:05:21.139  1524  4470 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 12:05:21.139  1524  4470 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 12:05:21.139  1524  4470 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 12:05:21.139  1524  4470 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 12:05:21.139  1524  4470 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-09 12:05:21.139  1524  4470 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-09 12:05:21.139  1524  4470 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-09 12:05:21.140  1524  4470 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-09 12:05:21.140  1524  4470 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 12:05:21.140  1524  4470 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 12:05:21.140  1524  4470 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 12:05:21.140  1524  4470 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 12:05:21.140  1524  4470 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 12:05:21.140  1524  4470 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 12:05:21.140  1524  4470 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 12:05:21.140  1524  4470 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 12:05:21.140  1524  4470 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 12:05:21.140  1524  4470 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 12:05:21.140  1524  4470 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 12:05:21.140  1524  4470 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 12:05:21.140  1524  4470 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 12:05:21.140  1524  4470 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 12:05:21.140  1524  4470 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-09 12:05:21.140  1524  4470 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-09 12:05:21.140  1524  4470 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-09 12:05:21.141  1524  4470 W SQLiteOpenHelper: Opened config.db in read-only mode
09-09 12:05:21.148  4456  4456 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
09-09 12:05:21.150   874  1955 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3826 uid 10000
09-09 12:05:21.151  1861  1861 I Keyboard.Facilitator: onFinishInput()
09-09 12:05:21.151   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-09 12:05:21.163  1861  4467 I Keyboard.Facilitator.MainLanguageModelLoader: run()
09-09 12:05:21.167  1941  2022 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-09 12:05:21.167   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-09 12:05:21.168   874   886 E PackageManager: Failed to write settings, restoring backup
09-09 12:05:21.168   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-09 12:05:21.168   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-09 12:05:21.168   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-09 12:05:21.168   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-09 12:05:21.168   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-09 12:05:21.168   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 12:05:21.168   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-09 12:05:21.168   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 12:05:21.175   874   887 E DropBoxManagerService: Can't write: system_server_wtf
09-09 12:05:21.175   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-09 12:05:21.175   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 12:05:21.175   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 12:05:21.175   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 12:05:21.175   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 12:05:21.175   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 12:05:21.175   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 12:05:21.175   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-09 12:05:21.175   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-09 12:05:21.175   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-09 12:05:21.175   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 12:05:21.175   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 12:05:21.175   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-09 12:05:21.175   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 12:05:21.175   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-09 12:05:21.175   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 12:05:21.175   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 12:05:21.175   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 12:05:21.175   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 12:05:21.175   874   887 E DropBoxManagerService: 	... 13 more
09-09 12:05:21.179   874  1955 I ActivityManager: Start proc 4471:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-09 12:05:21.180  1941  2022 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-09 12:05:21.180  1941  2022 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1941
09-09 12:05:21.180  1941  2022 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 12:05:21.180  1941  2022 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-09 12:05:21.180  1941  2022 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-09 12:05:21.180  1941  2022 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-09 12:05:21.180  1941  2022 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-09 12:05:21.180  1941  2022 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-09 12:05:21.180  1941  2022 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-09 12:05:21.180  1941  2022 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-09 12:05:21.180  1941  2022 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 12:05:21.180  1941  2022 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 12:05:21.180  1941  2022 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 12:05:21.180  1941  2022 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 12:05:21.182   874  3802 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-09 12:05:21.183   874  4477 E DropBoxManagerService: Can't write: system_app_crash
09-09 12:05:21.183   874  4477 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-09 12:05:21.183   874  4477 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 12:05:21.183   874  4477 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 12:05:21.183   874  4477 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 12:05:21.183   874  4477 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 12:05:21.183   874  4477 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 12:05:21.183   874  4477 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 12:05:21.183   874  4477 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 12:05:21.183   874  4477 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 12:05:21.183   874  4477 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 12:05:21.183   874  4477 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 12:05:21.183   874  4477 E DropBoxManagerService: 	... 5 more
09-09 12:05:21.187  1941  2022 I Process : Sending signal. PID: 1941 SIG: 9
09-09 12:05:21.213  1861  4467 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
09-09 12:05:21.214  1861  4467 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-09 12:05:21.215  1861  4467 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-09 12:05:21.216  1861  4467 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-09 12:05:21.216  1861  4467 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-09 12:05:21.217  1861  4467 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-09 12:05:21.217  1861  4467 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-09 12:05:21.218  1861  4467 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-09 12:05:21.218  1861  4467 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-09 12:05:21.218  1861  4467 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-09 12:05:21.218  1861  4467 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-09 12:05:21.218  1861  4467 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-09 12:05:21.218  1861  4467 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
09-09 12:05:21.225   874  1298 W InputDispatcher: channel 'ddf22f1 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
09-09 12:05:21.225   874  1298 E InputDispatcher: channel 'ddf22f1 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
09-09 12:05:21.225   874  1948 D GraphicsStats: Buffer count: 1
09-09 12:05:21.225   874  1978 I WindowState: WIN DEATH: Window{ddf22f1 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-09 12:05:21.225   874  1978 W InputDispatcher: Attempted to unregister already unregistered input channel 'ddf22f1 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
09-09 12:05:21.235   874  1383 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1941) has died
09-09 12:05:21.236   874  1383 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-09 12:05:21.237   874  1383 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-09 12:05:21.255   874   887 I ActivityManager: Start proc 4489:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-09 12:05:21.265  4456  4456 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
09-09 12:05:21.279  4456  4486 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-09 12:05:21.279  4456  4486 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 12:05:21.279  4456  4486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 12:05:21.279  4456  4486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 12:05:21.279  4456  4486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 12:05:21.279  4456  4486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 12:05:21.279  4456  4486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 12:05:21.279  4456  4486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 12:05:21.279  4456  4486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 12:05:21.279  4456  4486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 12:05:21.279  4456  4486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 12:05:21.279  4456  4486 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 12:05:21.279  4456  4486 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 12:05:21.279  4456  4486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 12:05:21.279  4456  4486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 12:05:21.279  4456  4486 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-09 12:05:21.279  4456  4486 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-09 12:05:21.279  4456  4486 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-09 12:05:21.279  4456  4486 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-09 12:05:21.279  4456  4486 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 12:05:21.279  4456  4486 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 12:05:21.279  4456  4486 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 12:05:21.279  4456  4486 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-09 12:05:21.279  4456  4486 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 12:05:21.279  4456  4486 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 12:05:21.279  4456  4486 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 12:05:21.279  4456  4486 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 12:05:21.279  4456  4486 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 12:05:21.279  4456  4486 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 12:05:21.279  4456  4486 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 12:05:21.279  4456  4486 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 12:05:21.279  4456  4486 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 12:05:21.279  4456  4486 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 12:05:21.279  4456  4486 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 12:05:21.279  4456  4486 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 12:05:21.279  4456  4486 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 12:05:21.279  4456  4486 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 12:05:21.279  4456  4486 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-09 12:05:21.279  4456  4486 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-09 12:05:21.279  4456  4486 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-09 12:05:21.279  4456  4486 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-09 12:05:21.279  4456  4486 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 12:05:21.279  4456  4486 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-09 12:05:21.279  4456  4486 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 12:05:21.294   874  1955 I ActivityManager: Start proc 4503:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
09-09 12:05:21.310  4489  4489 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-09 12:05:21.310  4489  4489 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 12:05:21.310  4489  4489 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 12:05:21.310  4489  4489 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 12:05:21.310  4489  4489 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 12:05:21.310  4489  4489 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 12:05:21.310  4489  4489 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 12:05:21.310  4489  4489 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 12:05:21.310  4489  4489 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 12:05:21.310  4489  4489 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 12:05:21.310  4489  4489 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 12:05:21.310  4489  4489 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 12:05:21.310  4489  4489 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 12:05:21.310  4489  4489 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 12:05:21.310  4489  4489 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 12:05:21.310  4489  4489 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-09 12:05:21.310  4489  4489 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-09 12:05:21.310  4489  4489 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-09 12:05:21.310  4489  4489 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-09 12:05:21.310  4489  4489 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-09 12:05:21.310  4489  4489 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-09 12:05:21.310  4489  4489 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-09 12:05:21.310  4489  4489 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 12:05:21.310  4489  4489 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 12:05:21.310  4489  4489 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 12:05:21.310  4489  4489 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 12:05:21.310  4489  4489 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 12:05:21.310  4489  4489 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 12:05:21.310  4489  4489 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 12:05:21.310  4489  4489 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 12:05:21.310  4489  4489 D AndroidRuntime: Shutting down VM
09-09 12:05:21.314  4456  4502 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-09 12:05:21.318  4489  4489 E AndroidRuntime: FATAL EXCEPTION: main
09-09 12:05:21.318  4489  4489 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4489
09-09 12:05:21.318  4489  4489 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 12:05:21.318  4489  4489 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-09 12:05:21.318  4489  4489 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-09 12:05:21.318  4489  4489 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-09 12:05:21.318  4489  4489 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 12:05:21.318  4489  4489 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 12:05:21.318  4489  4489 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 12:05:21.318  4489  4489 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 12:05:21.318  4489  4489 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 12:05:21.318  4489  4489 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 12:05:21.318  4489  4489 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 12:05:21.318  4489  4489 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 12:05:21.318  4489  4489 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 12:05:21.318  4489  4489 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 12:05:21.318  4489  4489 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 12:05:21.318  4489  4489 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 12:05:21.318  4489  4489 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 12:05:21.318  4489  4489 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 12:05:21.318  4489  4489 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 12:05:21.318  4489  4489 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 12:05:21.318  4489  4489 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 12:05:21.318  4489  4489 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 12:05:21.318  4489  4489 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 12:05:21.318  4489  4489 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 12:05:21.318  4489  4489 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 12:05:21.318  4489  4489 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 12:05:21.318  4489  4489 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-09 12:05:21.318  4489  4489 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-09 12:05:21.318  4489  4489 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-09 12:05:21.318  4489  4489 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-09 12:05:21.318  4489  4489 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-09 12:05:21.318  4489  4489 E AndroidRuntime: 	... 10 more
09-09 12:05:21.319   874  1383 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-09 12:05:21.320  4489  4489 I Process : Sending signal. PID: 4489 SIG: 9
09-09 12:05:21.320   874  4516 E DropBoxManagerService: Can't write: system_app_crash
09-09 12:05:21.320   874  4516 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-09 12:05:21.320   874  4516 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 12:05:21.320   874  4516 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 12:05:21.320   874  4516 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 12:05:21.320   874  4516 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 12:05:21.320   874  4516 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 12:05:21.320   874  4516 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 12:05:21.320   874  4516 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 12:05:21.320   874  4516 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 12:05:21.320   874  4516 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 12:05:21.320   874  4516 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 12:05:21.320   874  4516 E DropBoxManagerService: 	... 5 more
09-09 12:05:21.339   874  3188 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4489) has died
09-09 12:05:21.340   874  3188 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-09 12:05:21.348  1751  4514 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
09-09 12:05:21.349  1751  4514 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
09-09 12:05:21.354   874   887 I ActivityManager: Start proc 4517:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-09 12:05:21.357  4503  4503 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
09-09 12:05:21.363  1751  4514 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
09-09 12:05:21.364  1751  4514 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
09-09 12:05:21.385  1524  1524 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-09 12:05:21.387  1524  1524 D AndroidRuntime: Shutting down VM
09-09 12:05:21.388  1524  1524 E AndroidRuntime: FATAL EXCEPTION: main
09-09 12:05:21.388  1524  1524 E AndroidRuntime: Process: com.google.process.gapps, PID: 1524
09-09 12:05:21.388  1524  1524 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 12:05:21.388  1524  1524 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-09 12:05:21.388  1524  1524 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-09 12:05:21.388  1524  1524 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-09 12:05:21.388  1524  1524 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 12:05:21.388  1524  1524 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 12:05:21.388  1524  1524 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 12:05:21.388  1524  1524 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 12:05:21.388  1524  1524 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 12:05:21.388  1524  1524 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 12:05:21.388  1524  1524 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 12:05:21.388  1524  1524 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-09 12:05:21.388  1524  1524 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-09 12:05:21.388  1524  1524 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-09 12:05:21.388  1524  1524 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-09 12:05:21.388  1524  1524 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-09 12:05:21.388  1524  1524 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-09 12:05:21.388  1524  1524 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-09 12:05:21.388  1524  1524 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-09 12:05:21.388  1524  1524 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-09 12:05:21.388  1524  1524 E AndroidRuntime: 	... 8 more
09-09 12:05:21.392   874  4532 E DropBoxManagerService: Can't write: system_app_crash
09-09 12:05:21.392   874  4532 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-09 12:05:21.392   874  4532 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 12:05:21.392   874  4532 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 12:05:21.392   874  4532 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 12:05:21.392   874  4532 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 12:05:21.392   874  4532 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 12:05:21.392   874  4532 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 12:05:21.392   874  4532 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 12:05:21.392   874  4532 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 12:05:21.392   874  4532 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 12:05:21.392   874  4532 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 12:05:21.392   874  4532 E DropBoxManagerService: 	... 5 more
09-09 12:05:21.393  1524  1524 I Process : Sending signal. PID: 1524 SIG: 9
09-09 12:05:21.396  4517  4517 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-09 12:05:21.396  4517  4517 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 12:05:21.396  4517  4517 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 12:05:21.396  4517  4517 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 12:05:21.396  4517  4517 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 12:05:21.396  4517  4517 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 12:05:21.396  4517  4517 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 12:05:21.396  4517  4517 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 12:05:21.396  4517  4517 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 12:05:21.396  4517  4517 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 12:05:21.396  4517  4517 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 12:05:21.396  4517  4517 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 12:05:21.396  4517  4517 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 12:05:21.396  4517  4517 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 12:05:21.396  4517  4517 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 12:05:21.396  4517  4517 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-09 12:05:21.396  4517  4517 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-09 12:05:21.396  4517  4517 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-09 12:05:21.396  4517  4517 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-09 12:05:21.396  4517  4517 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-09 12:05:21.396  4517  4517 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-09 12:05:21.396  4517  4517 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-09 12:05:21.396  4517  4517 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 12:05:21.396  4517  4517 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 12:05:21.396  4517  4517 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 12:05:21.396  4517  4517 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 12:05:21.396  4517  4517 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 12:05:21.396  4517  4517 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 12:05:21.396  4517  4517 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 12:05:21.396  4517  4517 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 12:05:21.396  4517  4517 D AndroidRuntime: Shutting down VM
09-09 12:05:21.404  4517  4517 E AndroidRuntime: FATAL EXCEPTION: main
09-09 12:05:21.404  4517  4517 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4517
09-09 12:05:21.404  4517  4517 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 12:05:21.404  4517  4517 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-09 12:05:21.404  4517  4517 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-09 12:05:21.404  4517  4517 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-09 12:05:21.404  4517  4517 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 12:05:21.404  4517  4517 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 12:05:21.404  4517  4517 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 12:05:21.404  4517  4517 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 12:05:21.404  4517  4517 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 12:05:21.404  4517  4517 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 12:05:21.404  4517  4517 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 12:05:21.404  4517  4517 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 12:05:21.404  4517  4517 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 12:05:21.404  4517  4517 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 12:05:21.404  4517  4517 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 12:05:21.404  4517  4517 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 12:05:21.404  4517  4517 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 12:05:21.404  4517  4517 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 12:05:21.404  4517  4517 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 12:05:21.404  4517  4517 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 12:05:21.404  4517  4517 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 12:05:21.404  4517  4517 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 12:05:21.404  4517  4517 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 12:05:21.404  4517  4517 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 12:05:21.404  4517  4517 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 12:05:21.404  4517  4517 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 12:05:21.404  4517  4517 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-09 12:05:21.404  4517  4517 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-09 12:05:21.404  4517  4517 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-09 12:05:21.404  4517  4517 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-09 12:05:21.404  4517  4517 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-09 12:05:21.404  4517  4517 E AndroidRuntime: 	... 10 more
09-09 12:05:21.405   874  3802 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-09 12:05:21.406   874  4533 E DropBoxManagerService: Can't write: system_app_crash
09-09 12:05:21.406   874  4533 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
09-09 12:05:21.406   874  4533 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 12:05:21.406   874  4533 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 12:05:21.406   874  4533 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 12:05:21.406   874  4533 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 12:05:21.406   874  4533 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 12:05:21.406   874  4533 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 12:05:21.406   874  4533 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 12:05:21.406   874  4533 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 12:05:21.406   874  4533 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 12:05:21.406   874  4533 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 12:05:21.406   874  4533 E DropBoxManagerService: 	... 5 more
09-09 12:05:21.406  4517  4517 I Process : Sending signal. PID: 4517 SIG: 9
09-09 12:05:21.416  1751  4514 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
09-09 12:05:21.417  1751  4514 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
09-09 12:05:21.441  4456  4486 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
09-09 12:05:21.445  4456  4502 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-09 12:05:21.445  4456  4502 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 12:05:21.445  4456  4502 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 12:05:21.445  4456  4502 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 12:05:21.445  4456  4502 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 12:05:21.445  4456  4502 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 12:05:21.445  4456  4502 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 12:05:21.445  4456  4502 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 12:05:21.445  4456  4502 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 12:05:21.445  4456  4502 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 12:05:21.445  4456  4502 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 12:05:21.445  4456  4502 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 12:05:21.445  4456  4502 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 12:05:21.445  4456  4502 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 12:05:21.445  4456  4502 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 12:05:21.445  4456  4502 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-09 12:05:21.445  4456  4502 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-09 12:05:21.445  4456  4502 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-09 12:05:21.445  4456  4502 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-09 12:05:21.445  4456  4502 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-09 12:05:21.445  4456  4502 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-09 12:05:21.445  4456  4502 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-09 12:05:21.445  4456  4502 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 12:05:21.445  4456  4502 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 12:05:21.445  4456  4502 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 12:05:21.446  4456  4502 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-09 12:05:21.446  4456  4502 E AndroidRuntime: Process: android.process.acore, PID: 4456
09-09 12:05:21.446  4456  4502 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 12:05:21.446  4456  4502 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 12:05:21.446  4456  4502 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 12:05:21.446  4456  4502 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 12:05:21.446  4456  4502 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 12:05:21.446  4456  4502 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 12:05:21.446  4456  4502 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 12:05:21.446  4456  4502 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 12:05:21.446  4456  4502 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 12:05:21.446  4456  4502 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 12:05:21.446  4456  4502 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 12:05:21.446  4456  4502 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 12:05:21.446  4456  4502 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 12:05:21.446  4456  4502 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 12:05:21.446  4456  4502 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-09 12:05:21.446  4456  4502 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-09 12:05:21.446  4456  4502 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-09 12:05:21.446  4456  4502 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-09 12:05:21.446  4456  4502 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-09 12:05:21.446  4456  4502 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-09 12:05:21.446  4456  4502 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-09 12:05:21.446  4456  4502 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 12:05:21.446  4456  4502 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 12:05:21.446  4456  4502 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 12:05:21.447   874  3124 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4517) has died
09-09 12:05:21.448   874  3124 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-09 12:05:21.450  4456  4486 I Process : Sending signal. PID: 4456 SIG: 9
09-09 12:05:21.454   874  4534 E DropBoxManagerService: Can't write: system_app_crash
09-09 12:05:21.454   874  4534 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
09-09 12:05:21.454   874  4534 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 12:05:21.454   874  4534 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 12:05:21.454   874  4534 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 12:05:21.454   874  4534 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 12:05:21.454   874  4534 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 12:05:21.454   874  4534 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 12:05:21.454   874  4534 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 12:05:21.454   874  4534 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 12:05:21.454   874  4534 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 12:05:21.454   874  4534 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 12:05:21.454   874  4534 E DropBoxManagerService: 	... 5 more
09-09 12:05:21.463   874  1308 D WifiService: Client connection lost with reason: 4
09-09 12:05:21.463   874   887 I ActivityManager: Start proc 4535:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-09 12:05:21.471   874  1981 I ActivityManager: Process com.google.process.gapps (pid 1524) has died
09-09 12:05:21.471   874  1981 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
09-09 12:05:21.471   874  1981 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
09-09 12:05:21.471   874  1981 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms
09-09 12:05:21.478  1751  1751 W RocketImpressions: ClearcutLogger connection suspended: 1
09-09 12:05:21.495   874  1955 I ActivityManager: Start proc 4547:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService

```
