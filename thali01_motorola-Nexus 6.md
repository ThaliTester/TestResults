#### Test 832760823d6df89_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-31 11:15:44.849  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 11:15:44.859  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-31 11:15:44.864  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-31 11:15:44.905  1502  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-31 11:15:44.906  1502  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-31 11:15:44.906  1502  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 11:15:44.906  1502  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-31 11:15:44.939  3693  3693 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-31 11:15:44.940  3693  3693 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-31 11:15:44.940  3693  3693 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-31 11:15:45.499  3960  3960 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-31 11:15:45.504  3960  3960 D AndroidRuntime: CheckJNI is OFF
08-31 11:15:45.548  3960  3960 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-31 11:15:45.597  3960  3960 I Radio-JNI: register_android_hardware_Radio DONE
08-31 11:15:45.619  3960  3960 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-31 11:15:45.623   876  3232 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-31 11:15:45.659  2010  3920 W SearchService: Abort, client detached.
08-31 11:15:45.666  2010  2297 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@8167049
08-31 11:15:45.667  2010  2010 I HotwordDetector: Closing mic
08-31 11:15:45.667  2010  2311 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-31 11:15:45.670  3960  3960 D AndroidRuntime: Shutting down VM
08-31 11:15:45.715   377  2313 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-31 11:15:45.717   377  2313 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-31 11:15:45.723   377  1276 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-31 11:15:45.729  2010  2300 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-31 11:15:45.730  2010  2309 I MicroRecognitionRnrImpl: Detection finished
08-31 11:15:45.730   876   886 I ActivityManager: Start proc 3969:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-31 11:15:45.795  3969  3969 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-31 11:15:45.818  3969  3969 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-31 11:15:45.825  3969  3969 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3155-3157)
08-31 11:15:45.825  3969  3969 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 11:15:45.839  3969  3969 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f0100a2}
08-31 11:15:45.840  3969  3969 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 11:15:45.840  3969  3969 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-31 11:15:45.848  3969  3969 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-31 11:15:45.849  3969  3969 E SysUtils: ApplicationContext is null in ApplicationStatus
08-31 11:15:45.869  3969  3969 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-31 11:15:45.880  3969  3969 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-31 11:15:45.880  3969  3969 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-31 11:15:45.880  3969  3969 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-31 11:15:45.880  3969  3969 I Adreno  : Build Date                       : 10/20/15
08-31 11:15:45.880  3969  3969 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-31 11:15:45.880  3969  3969 I Adreno  : Local Branch                     : M14
08-31 11:15:45.880  3969  3969 I Adreno  : Remote Branch                    : 
08-31 11:15:45.880  3969  3969 I Adreno  : Remote Branch                    : 
08-31 11:15:45.880  3969  3969 I Adreno  : Reconstruct Branch               : 
,08-31 11:15:45.945   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8b30861:true
,08-31 11:15:45.983  3969  3969 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-31 11:15:45.999  3969  3969 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-31 11:15:46.057  3969  4007 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-31 11:15:46.067  3969  3993 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-31 11:15:46.112  3969  4007 I OpenGLRenderer: Initialized EGL, version 1.4
,08-31 11:15:46.180   876   894 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +488ms
,08-31 11:15:46.199  1867  1867 I Keyboard.Facilitator: onFinishInput()
,08-31 11:15:46.259  3969  3969 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3969
,08-31 11:15:46.357  3969  3969 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-31 11:15:46.532  3969  4010 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1679361744
,08-31 11:15:46.534   876  1939 I ActivityManager: Killing 3238:com.google.android.gm/u0a78 (adj 15): empty #17
,08-31 11:15:46.540  3969  4010 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-31 11:15:46.540  3969  4010 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-31 11:15:46.540  3969  4010 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-31 11:15:46.540  3969  4010 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-31 11:15:46.540  3969  4010 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-31 11:15:46.541  3969  4010 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@58ddb61 added. We now have 1 listener(s)
,08-31 11:15:46.544  3969  4010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-31 11:15:46.546  3969  4010 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 11:15:46.547  3969  4010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 11:15:46.547  3969  4010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 11:15:46.555  3969  4010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-31 11:15:46.555  3969  4010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-31 11:15:46.555  3969  4010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-31 11:15:46.555  3969  4010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-31 11:15:46.555  3969  4010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-31 11:15:46.555  3969  4010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-31 11:15:46.555  3969  4010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-31 11:15:46.555  3969  4010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-31 11:15:46.555  3969  4010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-31 11:15:46.555  3969  4010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-31 11:15:46.555  3969  4010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-31 11:15:46.555  3969  4010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-31 11:15:46.555  3969  4010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-31 11:15:46.555  3969  4010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-31 11:15:46.555  3969  4010 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc87f74 added. We now have 1 listener(s)
,08-31 11:15:46.555  3969  4010 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:15:46.558   876  1305 D WifiService: New client listening to asynchronous messages
,08-31 11:15:46.559  3969  4010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 11:15:46.559  3969  4010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-31 11:15:46.561  3969  4010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-31 11:15:46.561  3969  4010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-31 11:15:46.562  3969  4010 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-31 11:15:46.599   876  1939 I ActivityManager: Killing 3531:com.google.android.apps.photos/u0a71 (adj 15): empty #18
,08-31 11:15:46.643  3969  4010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:15:46.644  3969  4010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-31 11:15:46.650  3969  4010 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-31 11:15:46.650  3969  4010 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:15:46.650  3969  4010 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:15:46.650  3969  4010 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:15:46.650  3969  4010 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:15:46.650  3969  4010 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:15:46.650  3969  4010 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:15:46.650  3969  4010 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:15:46.650  3969  4010 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:15:46.650  3969  4010 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-31 11:15:46.650  3969  4010 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:15:46.651  3969  4010 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-31 11:15:46.705  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:15:46.707  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:15:46.709  3969  3969 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-31 11:15:47.532  3969  4018 W jxcore-log: Initializing JXcore engine
,08-31 11:15:47.532  3969  4018 W jxcore-log: JXcore engine is ready
,08-31 11:15:47.567  4018  4018 W Thread-353: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8984 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-31 11:15:47.567  4018  4018 W Thread-353: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12004]" dev="sockfs" ino=12004 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-31 11:15:47.567  4018  4018 W Thread-353: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-31 11:15:47.567  4018  4018 W Thread-353: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26360]" dev="sockfs" ino=26360 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-31 11:15:47.662  3969  4018 W jxcore-log: Platform android
08-31 11:15:47.662  3969  4018 W jxcore-log: 
,08-31 11:15:47.662  3969  4018 W jxcore-log: Process ARCH arm
08-31 11:15:47.662  3969  4018 W jxcore-log: 
,08-31 11:15:47.898  3969  4018 I jxcore-log: JXcore Cordova bridge is ready!
08-31 11:15:47.898  3969  4018 I jxcore-log: 
,08-31 11:15:47.899  3969  4018 W jxcore-log: JXcore engine is started
,08-31 11:15:47.905  3969  4010 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-31 11:15:47.908  3969  3969 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-31 11:15:51.370   876  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-31 11:15:51.676   876  1304 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-31 11:15:52.670  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 11:15:52.674  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 11:15:52.710  1502  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-31 11:15:52.711  1502  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-31 11:15:52.711  1502  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-31 11:15:52.711  1502  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 11:15:52.745  2686  4022 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-31 11:15:52.745  2686  4022 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-31 11:15:52.745  2686  4022 E HttpOperation: 	at jdm.a(PG:82)
08-31 11:15:52.745  2686  4022 E HttpOperation: 	at jcs.o(PG:406)
08-31 11:15:52.745  2686  4022 E HttpOperation: 	at jcn.a(PG:1379)
08-31 11:15:52.745  2686  4022 E HttpOperation: 	at jcs.i(PG:143)
08-31 11:15:52.745  2686  4022 E HttpOperation: 	at blb.a(PG:3937)
08-31 11:15:52.745  2686  4022 E HttpOperation: 	at czp.a(PG:18188)
08-31 11:15:52.745  2686  4022 E HttpOperation: 	at czp.a(PG:9081)
08-31 11:15:52.745  2686  4022 E HttpOperation: 	at czq.run(PG:1686)
08-31 11:15:52.745  2686  4022 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-31 11:15:52.745  2686  4022 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 11:15:52.745  2686  4022 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 11:15:52.745  2686  4022 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 11:15:52.745  2686  4022 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-31 11:15:52.745  2686  4022 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-31 11:15:52.745  2686  4022 E HttpOperation: 	at jdj.a(PG:4091)
08-31 11:15:52.745  2686  4022 E HttpOperation: 	at jdj.a(PG:1125)
08-31 11:15:52.745  2686  4022 E HttpOperation: 	at jdm.a(PG:77)
08-31 11:15:52.745  2686  4022 E HttpOperation: 	... 12 more
08-31 11:15:52.745  2686  4022 E HttpOperation: Caused by: faj: BadAuthentication
08-31 11:15:52.745  2686  4022 E HttpOperation: 	at fal.a(PG:38)
08-31 11:15:52.745  2686  4022 E HttpOperation: 	at jdj.a(PG:4089)
08-31 11:15:52.745  2686  4022 E HttpOperation: 	... 14 more
,08-31 11:15:52.796  1502  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-31 11:15:52.797  1502  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-31 11:15:52.797  1502  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 11:15:52.797  1502  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 11:15:52.813  2686  4022 E HttpOperation: [getmobileexperiments] Unexpected exception
08-31 11:15:52.813  2686  4022 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-31 11:15:52.813  2686  4022 E HttpOperation: 	at jdm.a(PG:82)
08-31 11:15:52.813  2686  4022 E HttpOperation: 	at jcs.o(PG:406)
08-31 11:15:52.813  2686  4022 E HttpOperation: 	at jcn.a(PG:1379)
08-31 11:15:52.813  2686  4022 E HttpOperation: 	at jcs.i(PG:143)
08-31 11:15:52.813  2686  4022 E HttpOperation: 	at hec.a(PG:42)
08-31 11:15:52.813  2686  4022 E HttpOperation: 	at hee.a(PG:102)
08-31 11:15:52.813  2686  4022 E HttpOperation: 	at czr.a(PG:65)
08-31 11:15:52.813  2686  4022 E HttpOperation: 	at kka.a(PG:108)
08-31 11:15:52.813  2686  4022 E HttpOperation: 	at czp.a(PG:19176)
08-31 11:15:52.813  2686  4022 E HttpOperation: 	at czp.a(PG:9081)
08-31 11:15:52.813  2686  4022 E HttpOperation: 	at czq.run(PG:1686)
08-31 11:15:52.813  2686  4022 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-31 11:15:52.813  2686  4022 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 11:15:52.813  2686  4022 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 11:15:52.813  2686  4022 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 11:15:52.813  2686  4022 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-31 11:15:52.813  2686  4022 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-31 11:15:52.813  2686  4022 E HttpOperation: 	at jdj.a(PG:4091)
08-31 11:15:52.813  2686  4022 E HttpOperation: 	at jdj.a(PG:1125)
08-31 11:15:52.813  2686  4022 E HttpOperation: 	at jdm.a(PG:77)
08-31 11:15:52.813  2686  4022 E HttpOperation: 	... 15 more
08-31 11:15:52.813  2686  4022 E HttpOperation: Caused by: faj: BadAuthentication
08-31 11:15:52.813  2686  4022 E HttpOperation: 	at fal.a(PG:38)
08-31 11:15:52.813  2686  4022 E HttpOperation: 	at jdj.a(PG:4089)
08-31 11:15:52.813  2686  4022 E HttpOperation: 	... 17 more
,08-31 11:15:52.814  2686  4022 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-31 11:15:52.814  2686  4022 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-31 11:15:52.814  2686  4022 E ExperimentLoader: 	at jdm.a(PG:82)
08-31 11:15:52.814  2686  4022 E ExperimentLoader: 	at jcs.o(PG:406)
08-31 11:15:52.814  2686  4022 E ExperimentLoader: 	at jcn.a(PG:1379)
08-31 11:15:52.814  2686  4022 E ExperimentLoader: 	at jcs.i(PG:143)
08-31 11:15:52.814  2686  4022 E ExperimentLoader: 	at hec.a(PG:42)
08-31 11:15:52.814  2686  4022 E ExperimentLoader: 	at hee.a(PG:102)
08-31 11:15:52.814  2686  4022 E ExperimentLoader: 	at czr.a(PG:65)
08-31 11:15:52.814  2686  4022 E ExperimentLoader: 	at kka.a(PG:108)
08-31 11:15:52.814  2686  4022 E ExperimentLoader: 	at czp.a(PG:19176)
08-31 11:15:52.814  2686  4022 E ExperimentLoader: 	at czp.a(PG:9081)
08-31 11:15:52.814  2686  4022 E ExperimentLoader: 	at czq.run(PG:1686)
08-31 11:15:52.814  2686  4022 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-31 11:15:52.814  2686  4022 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 11:15:52.814  2686  4022 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 11:15:52.814  2686  4022 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 11:15:52.814  2686  4022 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-31 11:15:52.814  2686  4022 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-31 11:15:52.814  2686  4022 E ExperimentLoader: 	at jdj.a(PG:4091)
08-31 11:15:52.814  2686  4022 E ExperimentLoader: 	at jdj.a(PG:1125)
08-31 11:15:52.814  2686  4022 E ExperimentLoader: 	at jdm.a(PG:77)
08-31 11:15:52.814  2686  4022 E ExperimentLoader: 	... 15 more
08-31 11:15:52.814  2686  4022 E ExperimentLoader: Caused by: faj: BadAuthentication
08-31 11:15:52.814  2686  4022 E ExperimentLoader: 	at fal.a(PG:38)
08-31 11:15:52.814  2686  4022 E ExperimentLoader: 	at jdj.a(PG:4089)
08-31 11:15:52.814  2686  4022 E ExperimentLoader: 	... 17 more
,08-31 11:15:52.908   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 129784, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-31 11:15:54.400   876  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-31 11:15:57.431   876  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-31 11:15:57.855  3969  4018 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-31 11:15:57.855  3969  4018 I jxcore-log: 
,08-31 11:15:57.862  3969  4018 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-31 11:15:57.862  3969  4018 I jxcore-log: 
,08-31 11:15:57.874  3969  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:15:57.874  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:15:57.874  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:15:57.874  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:15:57.874  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:15:57.874  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:15:57.874  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:15:57.874  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:15:57.881  3969  4018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:15:57.883  3969  4018 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-31 11:15:57.883  3969  4018 I jxcore-log: 
,08-31 11:15:57.885  3969  4018 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-31 11:15:57.885  3969  4018 I jxcore-log: 
,08-31 11:15:58.371  3969  4018 I jxcore-log: Unit Test app is loaded
08-31 11:15:58.371  3969  4018 I jxcore-log: 
,08-31 11:15:58.377  3969  4018 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:15:58.377  3969  4018 I jxcore-log: 
,08-31 11:15:58.383  3969  4018 D executeNativeTests: Running unit tests
,08-31 11:15:58.395  3969  3969 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-31 11:15:58.438  3969  4018 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:15:58.438  3969  4018 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9374fd6 added. We now have 2 listener(s)
08-31 11:15:58.439  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 11:15:58.439  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 11:15:58.439  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 11:15:58.439  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:15:58.439  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 added. We now have 2 listener(s)
,08-31 11:15:58.439  3969  4018 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:15:58.440  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 11:15:58.442  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:15:58.455  3969  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:15:58.455  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:15:58.455  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:15:58.455  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:15:58.455  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:15:58.455  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:15:58.455  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:15:58.455  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:15:58.458  3969  4018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:15:58.459  3969  4018 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 11:15:58.461  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-31 11:15:58.463  3969  4018 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-31 11:15:58.463  3969  4018 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 11:15:58.465  3969  4018 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-31 11:15:58.465  3969  4018 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-31 11:15:58.465  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:15:58.467  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 11:15:58.467  3969  4018 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-31 11:15:58.467  3969  4018 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-31 11:15:58.468  3969  4018 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:58.468  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 11:15:58.468  3969  4018 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:15:58.469  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 11:15:58.469  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.469  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:15:58.469  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:15:58.469  3969  4018 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9374fd6 removed from the list
08-31 11:15:58.469  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.469  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 removed from the list
08-31 11:15:58.472  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:15:58.472  3969  4018 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 11:15:58.472  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.473  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.473  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:15:58.473  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:15:58.473  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 11:15:58.474  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.474  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
,08-31 11:15:58.475  3969  4018 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-31 11:15:58.477  3969  4018 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:58.477  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 11:15:58.477  3969  4018 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:15:58.478  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:58.478  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:15:58.478  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.478  3969  4018 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9374fd6 not in the list
08-31 11:15:58.478  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.478  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
,08-31 11:15:58.478  3969  4018 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:58.478  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.478  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:15:58.478  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.478  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.481  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 11:15:58.481  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:15:58.481  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.482  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
,08-31 11:15:58.486  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-31 11:15:58.486  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-31 11:15:58.486  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 11:15:58.486  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 11:15:58.486  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-31 11:15:58.486  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 11:15:58.486  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 11:15:58.486  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-31 11:15:58.486  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 11:15:58.487  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 11:15:58.487  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 11:15:58.487  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-31 11:15:58.487  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 11:15:58.487  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 11:15:58.487  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-31 11:15:58.487  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 11:15:58.487  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-31 11:15:58.487  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 11:15:58.487  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 11:15:58.487  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 11:15:58.487  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-31 11:15:58.487  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 11:15:58.487  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 11:15:58.487  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 11:15:58.487  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 11:15:58.487  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 11:15:58.487  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-31 11:15:58.487  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 11:15:58.488  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 11:15:58.488  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-31 11:15:58.488  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 11:15:58.488  3969  4018 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:58.488  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:15:58.488  3969  4018 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 11:15:58.488  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:58.488  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.488  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.488  3969  4018 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9374fd6 not in the list
,08-31 11:15:58.488  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.488  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
08-31 11:15:58.488  3969  4018 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:58.488  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.488  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:15:58.488  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.489  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.490  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:15:58.490  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:15:58.490  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.490  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
08-31 11:15:58.490  3969  4018 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 11:15:58.492  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:15:58.496  3969  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:15:58.496  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:15:58.496  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:15:58.496  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:15:58.496  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:15:58.496  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:15:58.496  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:15:58.496  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:15:58.497  3969  4018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:15:58.497  3969  4018 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:15:58.498  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:15:58.498  3969  4018 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:15:58.498  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:15:58.498  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:15:58.498  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 11:15:58.500  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:15:58.501  3969  4018 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-31 11:15:58.502  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 11:15:58.502  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:15:58.506  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 11:15:58.507  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-31 11:15:58.508  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 11:15:58.511  3969  4018 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-31 11:15:58.514  3969  4018 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-31 11:15:58.514  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-31 11:15:58.514  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 11:15:58.515  3969  4018 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 11:15:58.516  3969  4018 D BluetoothAdapter: STATE_ON
,08-31 11:15:58.521  2556  2569 D BtGatt.GattService: registerClient() - UUID=875f183e-4dea-4671-94f2-b134ce74fa96
,08-31 11:15:58.521  2556  2581 D BtGatt.GattService: onClientRegistered() - UUID=875f183e-4dea-4671-94f2-b134ce74fa96, clientIf=5
,08-31 11:15:58.522  3969  3980 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-31 11:15:58.523  2556  2567 D BtGatt.GattService: start scan with filters
,08-31 11:15:58.525  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-31 11:15:58.525  2556  2586 D BtGatt.ScanManager: handling starting scan
,08-31 11:15:58.525  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 11:15:58.525  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 11:15:58.526  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-31 11:15:58.527  2556  2586 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@287c81c
,08-31 11:15:58.527  3969  4018 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 11:15:58.528  3969  4018 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 11:15:58.528  3969  3969 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 11:15:58.529  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 11:15:58.530  3969  4018 I io.jxcore.node.ConnectionHelper: start: OK
,08-31 11:15:58.533  3969  4018 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 11:15:58.533  3969  4018 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 11:15:58.533  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 11:15:58.533  3969  4018 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-31 11:15:58.533  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.533  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:15:58.533  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 11:15:58.534  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 11:15:58.534  3969  4018 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 11:15:58.534  2556  2581 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-31 11:15:58.534  2556  2581 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:15:58.534  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 11:15:58.534  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 11:15:58.534  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-31 11:15:58.534  2556  2586 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-31 11:15:58.535  3969  4018 D BluetoothAdapter: STATE_ON
,08-31 11:15:58.535  2556  2567 D BtGatt.GattService: stopScan() - queue size =1
,08-31 11:15:58.536  2556  2676 D BtGatt.GattService: unregisterClient() - clientIf=5
08-31 11:15:58.536  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:15:58.536  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 11:15:58.536  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 11:15:58.537  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 11:15:58.537  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-31 11:15:58.537  3969  4018 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:15:58.538  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-31 11:15:58.538  3969  4018 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 11:15:58.538  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 11:15:58.538  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:15:58.540  2556  2581 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-31 11:15:58.540  2556  2581 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:15:58.540  3969  3969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-31 11:15:58.540  3969  3969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:15:58.540  3969  3969 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:15:58.540  2556  2586 D BtGatt.ScanManager: Starting BLE batch scan
,08-31 11:15:58.540  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:58.540  2556  2586 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-31 11:15:58.540  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.540  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:15:58.541  3969  4018 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9374fd6 not in the list
,08-31 11:15:58.541  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.541  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
08-31 11:15:58.541  3969  4018 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:58.541  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.542  3969  4018 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 11:15:58.544  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:15:58.549  3969  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:15:58.549  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:15:58.549  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:15:58.549  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:15:58.549  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:15:58.549  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:15:58.549  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:15:58.549  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:15:58.551  2556  2581 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-31 11:15:58.551  2556  2581 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:15:58.553  3969  4018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:15:58.553  3969  4018 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 11:15:58.555  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-31 11:15:58.555  3969  4018 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:15:58.555  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:15:58.555  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:15:58.556  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 11:15:58.557  2556  2581 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1,
08-31 11:15:58.557  2556  2581 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:15:58.559  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:15:58.561  3969  4018 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-31 11:15:58.561  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 11:15:58.562  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:15:58.564  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 11:15:58.565  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-31 11:15:58.565  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 11:15:58.566  2556  2581 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-31 11:15:58.566  2556  2581 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:15:58.567  2556  2586 D BtGatt.ScanManager: stopping BLe Batch
,08-31 11:15:58.568  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-31 11:15:58.568  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 11:15:58.568  3969  4018 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-31 11:15:58.569  3969  4018 D BluetoothAdapter: STATE_ON
08-31 11:15:58.570  2556  2567 D BtGatt.GattService: registerClient() - UUID=122c4399-0adb-4f6e-8d6f-f4d98f567731
,08-31 11:15:58.571  2556  2581 D BtGatt.GattService: onClientRegistered() - UUID=122c4399-0adb-4f6e-8d6f-f4d98f567731, clientIf=5
,08-31 11:15:58.571  3969  3979 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-31 11:15:58.571  2556  2676 D BtGatt.GattService: start scan with filters
,08-31 11:15:58.574  2556  2581 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-31 11:15:58.574  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 11:15:58.575  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 11:15:58.574  2556  2581 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:15:58.575  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 11:15:58.575  2556  2586 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-31 11:15:58.575  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 11:15:58.576  3969  4018 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 11:15:58.577  3969  3969 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 11:15:58.577  3969  4018 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 11:15:58.578  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 11:15:58.579  3969  4018 I io.jxcore.node.ConnectionHelper: start: OK
,08-31 11:15:58.581  3969  4018 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:58.581  3969  4018 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 11:15:58.581  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 11:15:58.581  3969  4018 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 11:15:58.581  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:15:58.581  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:15:58.581  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 11:15:58.581  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 11:15:58.581  3969  4018 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-31 11:15:58.582  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 11:15:58.582  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 11:15:58.582  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-31 11:15:58.582  3969  4018 D BluetoothAdapter: STATE_ON
08-31 11:15:58.583  2556  2581 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-31 11:15:58.583  2556  2581 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:15:58.583  2556  2567 D BtGatt.GattService: stopScan() - queue size =0
08-31 11:15:58.583  2556  2676 D BtGatt.GattService: unregisterClient() - clientIf=5
08-31 11:15:58.583  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:15:58.583  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 11:15:58.583  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 11:15:58.583  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 11:15:58.583  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-31 11:15:58.584  3969  4018 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:15:58.584  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 11:15:58.584  3969  4018 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 11:15:58.584  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 11:15:58.585  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:15:58.585  2556  2586 D BtGatt.ScanManager: handling starting scan
08-31 11:15:58.585  3969  3969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:15:58.585  3969  3969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:15:58.585  3969  3969 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:15:58.586  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:58.586  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.586  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:15:58.586  3969  4018 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9374fd6 not in the list
08-31 11:15:58.586  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.586  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
08-31 11:15:58.586  3969  4018 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:58.586  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.586  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothMan,ager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.586  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.587  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:15:58.587  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:15:58.587  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.587  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
08-31 11:15:58.587  3969  4018 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 11:15:58.588  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:15:58.592  3969  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:15:58.592  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:15:58.592  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:15:58.592  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:15:58.592  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:15:58.592  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:15:58.592  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:15:58.592  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:15:58.593  2556  2581 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-31 11:15:58.593  2556  2581 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:15:58.593  3969  4018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:15:58.594  3969  4018 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:15:58.594  2556  2586 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-31 11:15:58.594  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:15:58.594  3969  4018 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:15:58.594  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:15:58.594  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:15:58.594  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 11:15:58.596  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:15:58.597  3969  4018 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-31 11:15:58.597  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 11:15:58.600  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 11:15:58.601  2556  2581 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-31 11:15:58.601  2556  2581 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:15:58.601  2556  2586 D BtGatt.ScanManager: Starting BLE batch scan
08-31 11:15:58.602  2556  2586 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-31 11:15:58.602  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:15:58.602  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-31 11:15:58.602  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 11:15:58.605  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-31 11:15:58.605  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 11:15:58.605  3969  4018 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-31 11:15:58.605  3969  4018 D BluetoothAdapter: STATE_ON
08-31 11:15:58.607  2556  2676 D BtGatt.GattService: registerClient() - UUID=df56fff6-6e54-4a8c-9856-f886d7bc6a5b
08-31 11:15:58.607  2556  2581 D BtGatt.GattService: onClientRegistered() - UUID=df56fff6-6e54-4a8c-9856-f886d7bc6a5b, clientIf=5
08-31 11:15:58.607  3969  3979 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-31 11:15:58.608  2556  2569 D BtGatt.GattService: start scan with filters
08-31 11:15:58.611  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 11:15:58.612  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 11:15:58.612  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 11:15:58.612  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-31 11:15:58.614  3969  4018 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 11:15:58.614  3969  4018 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 11:15:58.614  3969  3969 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 11:15:58.615  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-31 11:15:58.617  2556  2581 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-31 11:15:58.617  2556  2581 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:15:58.617  3969  4018 I io.jxcore.node.ConnectionHelper: start: OK
08-31 11:15:58.617  3969  4018 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:58.617  3969  4018 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 11:15:58.618  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 11:15:58.618  3969  4018 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 11:15:58.618  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.618  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:15:58.618  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 11:15:58.618  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 11:15:58.618  3969  4018 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 11:15:58.618  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 11:15:58.618  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 11:15:58.618  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-31 11:15:58.618  3969  4018 D BluetoothAdapter: STATE_ON
08-31 11:15:58.619  2556  2569 D BtGatt.GattService: stopScan() - queue size =1
08-31 11:15:58.619  2556  2567 D BtGatt.GattService: unregisterClient() - clientIf=5
08-31 11:15:58.620  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:15:58.620  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 11:15:58.620  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 11:15:58.620  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 11:15:58.620  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-31 11:15:58.621  3969  4018 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:15:58.621  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 11:15:58.621  3969  4018 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-31 11:15:58.622  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 11:15:58.622  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:15:58.623  3969  3969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:15:58.623  3969  3969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:15:58.623  3969  4018 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:58.623  3969  4018 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 11:15:58.623  3969  3969 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:15:58.623  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:15:58.623  3969  4018 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:15:58.623  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:58.623  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.623  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:15:58.623  3969  4018 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9374fd6 not in the list
08-31 11:15:58.623  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.623  2556  2581 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-31 11:15:58.623  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
08-31 11:15:58.623  3969  4018 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:58.623  2556  2581 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:15:58.623  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.624  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.624  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.625  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:15:58.625  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:15:58.625  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.625  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
08-31 11:15:58.625  3969  4018 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-31 11:15:58.626  3969  4018 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:58.626  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:15:58.626  3969  4018 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:15:58.626  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:58.626  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.626  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.626  3969  4018 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9374fd6 not in the list
08-31 11:15:58.626  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.626  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
08-31 11:15:58.626  3969  4018 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:58.626  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.626  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.626  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.626  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.627  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:15:58.627  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:15:58.627  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.629  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
08-31 11:15:58.629  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 11:15:58.629  3969  4018 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:58.630  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:15:58.630  3969  4018 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:15:58.630  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:58.630  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.630  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.630  3969  4018 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9374fd6 not in the list
08-31 11:15:58.630  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.630  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
08-31 11:15:58.630  3969  4018 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:58.630  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.630  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.630  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.630  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.631  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:15:58.631  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:15:58.631  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.631  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
08-31 11:15:58.632  3969  4018 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-31 11:15:58.632  3969  4018 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:58.632  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:15:58.632  3969  4018 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:15:58.632  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:58.632  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.632  2556  2581 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-31 11:15:58.632  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.632  3969  4018 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9374fd6 not in the list
08-31 11:15:58.632  2556  2581 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:15:58.632  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.632  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
08-31 11:15:58.632  3969  4018 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:58.632  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.633  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.632  2556  2586 D BtGatt.ScanManager: stopping BLe Batch
08-31 11:15:58.633  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.633  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.633  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:15:58.633  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:15:58.633  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.633  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
08-31 11:15:58.634  3969  4018 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-31 11:15:58.634  3969  4018 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:58.634  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:15:58.634  3969  4018 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:15:58.634  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:58.634  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.634  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.634  3969  4018 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9374fd6 not in the list
08-31 11:15:58.634  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.634  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
08-31 11:15:58.634  3969  4018 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:58.634  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.634  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.634  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.634  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.635  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:15:58.635  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:15:58.635  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.635  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
08-31 11:15:58.636  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 11:15:58.637  3969  4018 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 11:15:58.637  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 11:15:58.637  3969  4018 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 11:15:58.637  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 11:15:58.637  3969  4018 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 11:15:58.637  3969  4018 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:58.637  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:15:58.637  3969  4018 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:15:58.637  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:58.637  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.638  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.638  3969  4018 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9374fd6 not in the list
08-31 11:15:58.639  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.639  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
08-31 11:15:58.639  3969  4018 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:58.639  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.639  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.639  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.639  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.641  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:15:58.641  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:15:58.641  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.641  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
08-31 11:15:58.641  2556  2581 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-31 11:15:58.641  2556  2581 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:15:58.642  2556  2586 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-31 11:15:58.642  3969  4018 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:15:58.643  3969  4018 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 11:15:58.643  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-31 11:15:58.647  2556  2581 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-31 11:15:58.647  2556  2581 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:15:58.648  3969  4018 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:15:58.648  3969  4018 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-31 11:15:58.648  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 11:15:58.648  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 11:15:58.648  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 11:15:58.648  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 11:15:58.648  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 11:15:58.648  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 11:15:58.648  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 11:15:58.648  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 11:15:58.648  2556  2586 D BtGatt.ScanManager: handling starting scan
08-31 11:15:58.649  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 11:15:58.649  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 11:15:58.649  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 11:15:58.649  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 11:15:58.649  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 11:15:58.649  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 11:15:58.649  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 11:15:58.649  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 11:15:58.649  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 11:15:58.649  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 11:15:58.649  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 11:15:58.649  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 11:15:58.649  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 11:15:58.649  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 11:15:58.649  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 11:15:58.649  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 11:15:58.649  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 11:15:58.649  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 11:15:58.649  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 11:15:58.649  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 11:15:58.650  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 11:15:58.650  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 11:15:58.650  3969  4018 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-31 11:15:58.650  3969  4018 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 11:15:58.650  3969  4018 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-31 11:15:58.650  3969  4018 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:15:58.650  3969  4018 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 11:15:58.650  3969  4018 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-31 11:15:58.650  3969  4018 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:15:58.652  3969  4018 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 11:15:58.652  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-31 11:15:58.654  2556  2581 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-31 11:15:58.654  2556  2581 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:15:58.654  2556  2586 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-31 11:15:58.654  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-31 11:15:58.655  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,08-31 11:15:58.655  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-31 11:15:58.655  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-31 11:15:58.655  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-31 11:15:58.655  3969  4018 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-31 11:15:58.656  3969  4018 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:15:58.656  3969  4018 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-31 11:15:58.656  3969  4018 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:58.656  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:15:58.656  3969  4018 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:15:58.656  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:58.656  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.656  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.657  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-31 11:15:58.657  3969  4018 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9374fd6 not in the list
08-31 11:15:58.657  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.657  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
08-31 11:15:58.657  3969  4018 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:58.657  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.657  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.657  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.658  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.658  3969  4027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 417)
08-31 11:15:58.658  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:15:58.658  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:15:58.658  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.658  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
08-31 11:15:58.659  3969  4018 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-31 11:15:58.659  3969  4018 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:58.659  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:15:58.659  3969  4018 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:15:58.659  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:58.659  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.659  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.659  2556  2581 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-31 11:15:58.659  3969  4018 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9374fd6 not in the list
08-31 11:15:58.659  2556  2581 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:15:58.660  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.660  2556  2586 D BtGatt.ScanManager: Starting BLE batch scan
08-31 11:15:58.660  2556  2586 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-31 11:15:58.660  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
08-31 11:15:58.660  3969  4018 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:58.660  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.660  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.660  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.660  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.661  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:15:58.661  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:15:58.661  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.661  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
08-31 11:15:58.661  3969  4028 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 417
08-31 11:15:58.661  3969  4018 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-31 11:15:58.661  3969  4018 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:58.661  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:15:58.661  3969  4018 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:15:58.662  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:58.662  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.662  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.662  3969  4018 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9374fd6 not in the list
08-31 11:15:58.662  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.662  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
08-31 11:15:58.662  3969  4018 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:58.662  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.662  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.662  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.662  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.663  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:15:58.663  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:15:58.663  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.663  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
08-31 11:15:58.663  3969  4018 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-31 11:15:58.663  3969  4018 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-31 11:15:58.663  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 11:15:58.663  3969  4018 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-31 11:15:58.664  3969  4018 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 11:15:58.664  3969  4018 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-31 11:15:58.664  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 11:15:58.664  3969  4018 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-31 11:15:58.664  3969  4018 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 11:15:58.664  3969  4018 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 11:15:58.664  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 11:15:58.664  3969  4018 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-31 11:15:58.664  3969  4018 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:58.664  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:15:58.664  3969  4018 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:15:58.664  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:58.665  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.665  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.665  3969  4018 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9374fd6 not in the list
08-31 11:15:58.664  3969  4027 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:15:58.665  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.665  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
08-31 11:15:58.665  3969  4018 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:58.665  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.665  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.665  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.665  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.666  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:15:58.666  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:15:58.666  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.666  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
08-31 11:15:58.667  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:58.667  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.667  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.667  3969  4018 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9374fd6 not in the list
08-31 11:15:58.667  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.667  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
08-31 11:15:58.667  3969  4018 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:58.667  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.667  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.668  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.668  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
08-31 11:15:58.668  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:58.668  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.668  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.668  3969  4018 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9374fd6 not in the list
08-31 11:15:58.668  3969  4018 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:58.668  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:15:58.668  3969  4018 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:15:58.668  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:58.668  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.668  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.668  3969  4018 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9374fd6 not in the list
08-31 11:15:58.668  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.668  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
08-31 11:15:58.668  3969  4018 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:58.668  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.668  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.668  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.668  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.669  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:15:58.669  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:15:58.669  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.669  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
08-31 11:15:58.670  3969  4018 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-31 11:15:58.671  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:15:58.671  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-31 11:15:58.672  3969  4018 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-31 11:15:58.672  3969  4018 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-31 11:15:58.672  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-31 11:15:58.672  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 11:15:58.672  3969  3969 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-31 11:15:58.672  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:58.672  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-31 11:15:58.672  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-31 11:15:58.672  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-31 11:15:58.672  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.672  3969  4018 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-31 11:15:58.673  3969  4018 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9374fd6 not in the list
08-31 11:15:58.673  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.673  3969  3969 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-31 11:15:58.673  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 11:15:58.673  3969  4018 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 11:15:58.673  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 11:15:58.673  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.673  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.673  2556  2581 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-31 11:15:58.673  2556  2581 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:15:58.674  3969  4018 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:15:58.675  3969  4029 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-31 11:15:58.675  3969  4029 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-31 11:15:58.676  3969  3969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:15:58.676  3969  3969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:15:58.676  3969  3969 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:15:58.676  3969  3969 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-31 11:15:58.677  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
08-31 11:15:58.677  3969  4018 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:58.677  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:15:58.677  3969  4018 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:15:58.677  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:58.677  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.677  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.677  3969  4018 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9374fd6 not in the list
08-31 11:15:58.678  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.678  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
08-31 11:15:58.678  3969  4018 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:58.678  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.678  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.678  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.678  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.679  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:15:58.679  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:15:58.679  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.679  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
08-31 11:15:58.680  3969  4018 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-31 11:15:58.680  3969  4018 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 11:15:58.680  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 11:15:58.681  3969  4018 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 11:15:58.681  3969  4018 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:58.682  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:15:58.682  3969  4018 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:15:58.683  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:58.683  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.683  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.683  3969  4018 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9374fd6 not in the list
08-31 11:15:58.683  2556  2581 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-31 11:15:58.683  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.683  2556  2581 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:15:58.683  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
08-31 11:15:58.683  3969  4018 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:58.683  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.683  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.683  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.683  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.684  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:15:58.684  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:15:58.684  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.686  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
08-31 11:15:58.688  2556  2581 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-31 11:15:58.688  2556  2581 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:15:58.689  2556  2586 D BtGatt.ScanManager: stopping BLe Batch
08-31 11:15:58.689  3969  4018 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:58.689  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:15:58.689  3969  4018 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:15:58.689  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:58.689  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.689  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.689  3969  4018 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9374fd6 not in the list
08-31 11:15:58.689  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.689  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
08-31 11:15:58.689  3969  4018 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:58.689  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.689  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.689  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.689  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.690  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:15:58.690  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:15:58.690  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.690  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
08-31 11:15:58.691  3969  4018 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:58.691  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:15:58.691  3969  4018 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:15:58.691  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:58.691  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.691  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.692  3969  4018 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9374fd6 not in the list
08-31 11:15:58.692  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.692  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
08-31 11:15:58.692  3969  4018 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:58.692  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.692  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:15:58.692  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:58.692  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:58.693  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:15:58.693  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:15:58.693  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:58.693  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c646257 not in the list
08-31 11:15:58.694  3969  4018 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-31 11:15:58.694  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 11:15:58.694  2556  2581 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-31 11:15:58.694  3969  4018 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-31 11:15:58.694  2556  2581 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:15:58.694  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 11:15:58.694  3969  4018 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-31 11:15:58.694  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 11:15:58.695  2556  2586 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-31 11:15:58.696  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 11:15:58.697  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-31 11:15:58.697  3969  4018 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-31 11:15:58.697  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 11:15:58.697  3969  4018 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-31 11:15:58.698  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 11:15:58.698  3969  4018 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-31 11:15:58.698  3969  4018 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-31 11:15:58.698  3969  4018 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-31 11:15:58.698  3969  4018 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-31 11:15:58.699  3969  4018 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-31 11:15:58.699  3969  4018 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-31 11:15:58.699  3969  4018 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-31 11:15:58.699  3969  4018 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-31 11:15:58.699  2556  2581 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-31 11:15:58.699  2556  2581 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:15:58.700  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:15:58.700  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@60f5f61 added. We now have 2 listener(s)
08-31 11:15:58.700  3969  4018 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:15:58.702  3969  4018 D BluetoothAdapter: enable(): BT is already enabled..!
08-31 11:15:58.702   876  1938 D WifiService: setWifiEnabled: true pid=3969, uid=10000
08-31 11:15:58.702   876  1938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-31 11:15:58.703  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:15:58.703  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9a15a86 added. We now have 3 listener(s)
08-31 11:15:58.703  3969  4018 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:15:58.710  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:15:58.710  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cec8f47 added. We now have 4 listener(s)
08-31 11:15:58.710  3969  4018 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:15:58.712  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:15:58.712  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c4ad374 added. We now have 5 listener(s)
08-31 11:15:58.712  3969  4018 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:15:58.715   876  1673 D WifiService: setWifiEnabled: false pid=3969, uid=10000
08-31 11:15:58.715   876  1673 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-31 11:15:58.718  2556  2576 D BluetoothAdapterState: Current state: ON, message: 23
08-31 11:15:58.718  2556  2576 D BluetoothAdapterProperties: Setting state to 13
08-31 11:15:58.718  2556  2576 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-31 11:15:58.719  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:15:58.719  2556  2576 D BluetoothAdapterProperties: onBluetoothDisable()
08-31 11:15:58.723  2556  2576 I BluetoothAdapterState: Entering PendingCommandState
08-31 11:15:58.726  2556  2556 D BluetoothMapService: onReceive
08-31 11:15:58.726  2556  2556 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:15:58.726  2556  2556 D BluetoothMapService: STATE_TURNING_OFF
08-31 11:15:58.726  2556  2556 D BluetoothMapService: MAP Service closeService in
08-31 11:15:58.726  2556  2556 D BluetoothMapMasInstance0: MAP Service shutdown
08-31 11:15:58.726  2556  2556 D ObexServerSockets0: shutdown(block = true)
08-31 11:15:58.727  2556  2556 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-31 11:15:58.727  2556  2556 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-31 11:15:58.727  2556  2672 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-31 11:15:58.727  2556  2684 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-31 11:15:58.727  2556  2685 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-31 11:15:58.728  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:15:58.728  3969  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:15:58.728  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:15:58.728  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:15:58.728  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:15:58.728  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:15:58.728  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:15:58.728  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:15:58.728  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:15:58.729  2556  2556 I BtOppRfcommListener: stopping Accept Thread
08-31 11:15:58.730  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:15:58.730  3969  4018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:15:58.730  3969  4018 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:15:58.730  2556  3590 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 11:15:58.730  2556  3590 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-31 11:15:58.730  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 11:15:58.731   876  1304 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-31 11:15:58.731   876  1304 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-31 11:15:58.731   876  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-31 11:15:58.731   876  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 11:15:58.734  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:15:58.739  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:15:58.740   876  2085 D DhcpClient: Clearing IP address
,08-31 11:15:58.740   373   874 D CommandListener: Clearing all IP addresses on wlan0
,08-31 11:15:58.742  3969  3969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:15:58.742  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:15:58.742  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:15:58.742  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:15:58.742  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:15:58.742  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:15:58.742  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:15:58.742  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:15:58.742  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:15:58.743   373   874 D CommandListener: Setting iface cfg
,08-31 11:15:58.745  3969  3969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:15:58.746  3969  3969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:15:58.746  1502  3654 V NativeCrypto: Read error: ssl=0x9b4f7000: I/O error during system call, Connection timed out
,08-31 11:15:58.747   876  2529 D DhcpClient: Receive thread stopped
,08-31 11:15:58.748  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:15:58.748  1502  3654 V NativeCrypto: SSL shutdown failed: ssl=0x9b4f7000: I/O error during system call, Broken pipe
08-31 11:15:58.750   876  1938 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,08-31 11:15:58.750   876  2520 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
08-31 11:15:58.752   876  2520 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,08-31 11:15:58.753   876  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
,08-31 11:15:58.753   876  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-31 11:15:58.754   876  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-31 11:15:58.760   876   889 I ActivityManager: Start proc 4033:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-31 11:15:58.761  2556  2581 D BluetoothAdapterProperties: Scan Mode:20
08-31 11:15:58.762  2556  2576 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-31 11:15:58.762   876  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-31 11:15:58.762   876  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-31 11:15:58.764  3969  3969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:15:58.764  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:15:58.764  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:15:58.764  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:15:58.764  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:15:58.764  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:15:58.764  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:15:58.764  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:15:58.764  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:15:58.765  3969  3969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:15:58.765  3969  3969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:15:58.766   397   397 E Parcel  : Reading a NULL string not supported here.
08-31 11:15:58.767  3969  3969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:15:58.768  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:15:58.768  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:15:58.768  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:15:58.768  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:15:58.768  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:15:58.768  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:15:58.768  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:15:58.768  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:15:58.768   876  1304 D WifiStateMachine: Start Disconnecting Watchdog 2
08-31 11:15:58.768   876  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0,
08-31 11:15:58.768  3969  3969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:15:58.768  3969  3969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:15:58.769  2556  2556 D HeadsetService: Received stop request...Stopping profile...
08-31 11:15:58.770   373   874 D CommandListener: Clearing all IP addresses on wlan0,
08-31 11:15:58.775   876   876 D BluetoothHeadset: Proxy object disconnected
08-31 11:15:58.775   876   876 D BluetoothHeadset: Proxy object disconnected
08-31 11:15:58.776  1350  1381 D BluetoothHeadset: Proxy object disconnected
,08-31 11:15:58.775   876  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 11:15:58.777  2556  2556 D A2dpService: Received stop request...Stopping profile...
08-31 11:15:58.779  2556  2678 D A2dpStateMachine: Exit Disconnected: -1
08-31 11:15:58.781   876  1306 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-31 11:15:58.781  2556  2556 D HidService: Received stop request...Stopping profile...
08-31 11:15:58.781  2556  2556 D HidService: Stopping Bluetooth HidService
08-31 11:15:58.782  3969  3969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:15:58.782  2101  2307 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:58.782  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:15:58.782  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:15:58.782  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:15:58.782  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:15:58.782  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:15:58.782  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:15:58.782  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:15:58.782  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:15:58.783  2556  2556 D HealthService: Received stop request...Stopping profile...
08-31 11:15:58.783  3969  3969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:15:58.783  3969  3969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:15:58.783  2556  2556 D PanService: Received stop request...Stopping profile...
08-31 11:15:58.783   876  1304 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-31 11:15:58.785  2556  2556 V BluetoothAdapterState: isTurningOff()=true
08-31 11:15:58.785  2556  2556 V BluetoothAdapterState: isTurningOn()=false
08-31 11:15:58.785  2556  2556 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:15:58.785  2556  2556 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:15:58.785  3969  3969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:15:58.785  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:15:58.785  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:15:58.785  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:15:58.785  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:15:58.785  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:15:58.785  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:15:58.785  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:15:58.785  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:15:58.786   876   876 D BluetoothHeadset: Proxy object disconnected
08-31 11:15:58.786  1921  2125 D BluetoothHeadset: Proxy object disconnected
08-31 11:15:58.786  3969  3969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:15:58.786  2556  2556 D BluetoothMapService: Received stop request...Stopping profile...
08-31 11:15:58.786  3969  3969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:15:58.786  2556  2556 D BluetoothMapService: stop()
08-31 11:15:58.786   876   876 D BluetoothA2dp: Proxy object disconnected
08-31 11:15:58.787  1350  1350 D HeadsetProfile: Bluetooth service disconnected
08-31 11:15:58.787  1350  1350 D BluetoothA2dp: Proxy obje,ct disconnected
08-31 11:15:58.787  2556  2556 D BluetoothMapAppObserver: deinitObservers()
08-31 11:15:58.787  2556  2556 D BluetoothMapAppObserver: removeReceiver()
08-31 11:15:58.787  1350  1350 D BluetoothInputDevice: Proxy object disconnected
08-31 11:15:58.787  1350  1350 D HidProfile: Bluetooth service disconnected
08-31 11:15:58.787  1350  1350 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-31 11:15:58.787  1350  1350 D PanProfile: Bluetooth service disconnected
,08-31 11:15:58.788  1350  1350 D BluetoothMap: Proxy object disconnected
,08-31 11:15:58.788  1350  1350 D MapProfile: Bluetooth service disconnected
08-31 11:15:58.790  2556  2556 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-31 11:15:58.790  2556  2556 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 11:15:58.790  2556  2556 V BluetoothAdapterState: isTurningOff()=true
08-31 11:15:58.790  2556  2556 V BluetoothAdapterState: isTurningOn()=false
08-31 11:15:58.790  2556  2556 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:15:58.790  2556  2556 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:15:58.791  2556  2581 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-31 11:15:58.791  2556  2670 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 11:15:58.791  2556  2670 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 11:15:58.791  2556  2670 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 11:15:58.792  2556  2581 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-31 11:15:58.794  2556  2556 V BluetoothAdapterState: isTurningOff()=true
,08-31 11:15:58.794  2556  2556 V BluetoothAdapterState: isTurningOn()=false
08-31 11:15:58.794  2556  2556 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:15:58.794  2556  2556 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:15:58.795  2556  2556 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 11:15:58.795  2556  2556 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-31 11:15:58.795  2556  2556 V BluetoothAdapterState: isTurningOff()=true
,08-31 11:15:58.795  2556  2556 V BluetoothAdapterState: isTurningOn()=false
08-31 11:15:58.795  2556  2556 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:15:58.795  2556  2556 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:15:58.795  2556  2556 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 11:15:58.795  2556  2581 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-31 11:15:58.795  2556  2581 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-31 11:15:58.795  2556  2670 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 11:15:58.795  2556  2581 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-31 11:15:58.795  2556  2670 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-31 11:15:58.796  2556  2556 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 11:15:58.796  2556  2556 V BluetoothAdapterState: isTurningOff()=true
08-31 11:15:58.796  2556  2670 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:15:58.796  2556  2556 V BluetoothAdapterState: isTurningOn()=false
08-31 11:15:58.796  2556  2670 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:15:58.796  2556  2556 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:15:58.796  2556  2670 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:15:58.796  2556  2556 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:15:58.796  2556  2670 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:15:58.796  2556  2556 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 11:15:58.796  2556  2556 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-31 11:15:58.796  2556  2556 D BluetoothMapService: MAP Service closeService in
08-31 11:15:58.797  2556  2556 V BluetoothAdapterState: isTurningOff()=true
08-31 11:15:58.797  2556  2556 V BluetoothAdapterState: isTurningOn()=false
08-31 11:15:58.797  2556  2556 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:15:58.797  2556  2556 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:15:58.797  2556  2576 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-31 11:15:58.797  2556  2576 D BluetoothAdapterProperties: Setting state to 15
08-31 11:15:58.797  2556  2576 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-31 11:15:58.798  2556  2576 I BluetoothAdapterState: Entering BleOnState
08-31 11:15:58.798  1350  2045 D BluetoothPan: onBluetoothStateChange on: false
08-31 11:15:58.798   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:15:58.799  1921  1937 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:15:58.799  1350  1381 D BluetoothMap: onBluetoothStateChange: up=false
08-31 11:15:58.800  1350  2044 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 11:15:58.801  2556  2556 D BluetoothMapService: cleanup()
08-31 11:15:58.801  2556  2556 D BluetoothMapService: MAP Service closeService in
08-31 11:15:58.805  1350  2128 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-31 11:15:58.806  1350  1372 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 11:15:58.808   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:15:58.808   876   893 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 11:15:58.808   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:15:58.808  1350  1381 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:15:58.809  2556  2576 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-31 11:15:58.809  2556  2576 D BluetoothAdapterProperties: Setting state to 16
08-31 11:15:58.809  2556  2576 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-31 11:15:58.810  2556  2576 D BluetoothAdapterProperties: onBleDisable
08-31 11:15:58.810  2556  2576 I BluetoothAdapterState: Entering PendingCommandState
08-31 11:15:58.810  2556  2577 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-31 11:15:58.811  3969  4027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 417)
08-31 11:15:58.811  2556  2581 D BluetoothAdapterProperties: Scan Mode:20
08-31 11:15:58.812  2556  2670 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-31 11:15:58.812  2556  2670 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 11:15:58.818   373   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 11:15:58.819  3969  3969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:15:58.819  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:15:58.819  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:15:58.819  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:15:58.819  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:15:58.819  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:15:58.819  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:15:58.819  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:15:58.819  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:15:58.820  3969  3969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:15:58.820  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:15:58.820  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:15:58.820  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:15:58.820  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:15:58.820  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:15:58.820  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:15:58.820  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:15:58.820  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:15:58.821  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:15:58.822  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:15:58.825  4033  4033 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-31 11:15:58.835  4033  4033 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 11:15:58.836   373   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 11:15:58.837   876  1306 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-31 11:15:58.837   876  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-31 11:15:58.842   876   893 D Tethering: MasterInitialState.processMessage what=3
08-31 11:15:58.844  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:15:58.845  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:15:58.848  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 11:15:58.849  3410  3410 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@c81c5e5 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-31 11:15:58.854   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1efa4f7:true
,08-31 11:15:58.864   876   887 I ActivityManager: Start proc 4052:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-31 11:15:58.873  4033  4033 D LocalBluetoothProfileManager: Adding local MAP profile
,08-31 11:15:58.877  4033  4033 D BluetoothMap: Create BluetoothMap proxy object
,08-31 11:15:58.887  4033  4033 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-31 11:15:58.888   373   874 E Netd    : netlink response contains error (No such file or directory)
08-31 11:15:58.889   876  1306 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-31 11:15:58.901  4033  4033 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:15:58.904  4052  4052 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-31 11:15:58.910   876  1976 I ActivityManager: Killing 3017:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-31 11:15:59.017  2556  2581 I bt_hci  : shut_down
08-31 11:15:59.018  2556  2587 D bt_hwcfg: hw_epilog_process
,08-31 11:15:59.029  2556  2587 I bt_vendor: low_power_mode_cb
,08-31 11:15:59.051  2556  2587 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-31 11:15:59.051  2556  2587 I bt_vendor: epilog_cb
08-31 11:15:59.051  2556  2587 I bt_hci  : epilog_finished_callback
,08-31 11:15:59.057  2556  2581 I bt_hci_h4: hal_close
,08-31 11:15:59.058  2556  2581 I bt_userial_vendor: device fd = 51 close,
,08-31 11:15:59.081  4052  4052 D StrictMode: StrictMode policy violation; ~duration=85 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 11:15:59.081  4052  4052 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 11:15:59.081  4052  4052 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 11:15:59.081  4052  4052 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-31 11:15:59.081  4052  4052 D StrictMode: 	at java.io.File.exists(File.java:361)
08-31 11:15:59.081  4052  4052 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-31 11:15:59.081  4052  4052 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-31 11:15:59.081  4052  4052 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-31 11:15:59.081  4052  4052 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-31 11:15:59.081  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-31 11:15:59.081  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 11:15:59.081  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:15:59.081  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 11:15:59.081  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:15:59.081  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:15:59.081  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 11:15:59.081  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 11:15:59.081  4052  4052 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 11:15:59.081  4052  4052 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 11:15:59.081  4052  4052 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 11:15:59.081  4052  4052 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 11:15:59.081  4052  4052 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:15:59.081  4052  4052 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:15:59.081  4052  4052 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 11:15:59.081  4052  4052 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:15:59.081  4052  4052 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:15:59.081  4052  4052 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 11:15:59.082  4052  4052 D StrictMode: StrictMode policy violation; ~duration=85 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.shared.,f.a.a(PG:48)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 11:15:59.082  4052  4052 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.app.ActivityThread.main(Act,ivityThread.java:5417)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 11:15:59.082  4052  4052 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.r.e.b(PG:170)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 11:15:59.082  4052  4052 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.r.k.d(PG:583)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.r.e.b(PG:170)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 11:15:59.082  4052  4052 D StrictMode: StrictMode policy violation; ~duration=60 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at java.io.File.exists(File.java:361)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 11:15:59.082  4052  4052 D StrictMode: StrictMode policy violation; ~duration=59 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at java.io.File.exists(File.java:361)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 11:15:59.082  4052  4052 D StrictMode: StrictMode policy violation; ~duration=57 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:15:59.082  4052  4052 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 11:15:59.124   876  1939 I ActivityManager: Start proc 4082:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-31 11:15:59.125   876  1939 I ActivityManager: Killing 3410:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-31 11:15:59.177  3969  3969 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 11:15:59.190  2556  2577 D bt_stack_manager: event_shut_down_stack finished.
,08-31 11:15:59.191  2556  2576 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-31 11:15:59.194  2556  2576 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-31 11:15:59.195  2556  2556 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 11:15:59.196  2556  2556 D BtGatt.GattService: Received stop request...Stopping profile...
,08-31 11:15:59.196  2556  2556 D BtGatt.GattService: stop()
08-31 11:15:59.197  2556  2556 D BtGatt.AdvertiseManager: advertise clients cleared
,08-31 11:15:59.199  4082  4082 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-31 11:15:59.200  2556  2556 V BluetoothAdapterState: isTurningOff()=false
08-31 11:15:59.201  2556  2556 V BluetoothAdapterState: isTurningOn()=false
08-31 11:15:59.201  2556  2556 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 11:15:59.201  2556  2556 V BluetoothAdapterState: isBleTurningOff()=true
08-31 11:15:59.202  2556  2576 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-31 11:15:59.202  2556  2576 D BluetoothAdapterProperties: Setting state to 10
,08-31 11:15:59.202  2556  2576 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-31 11:15:59.203  2556  2576 I BluetoothAdapterState: Entering OffState
,08-31 11:15:59.205   876   893 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-31 11:15:59.217  2556  2556 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-31 11:15:59.217  2556  2556 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-31 11:15:59.217  2556  2556 I BluetoothServiceJni: cleanupNative: return from cleanup
08-31 11:15:59.218  2556  2577 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-31 11:15:59.220  2556  2577 D bt_stack_manager: event_clean_up_stack finished.
,08-31 11:15:59.224  2556  2556 I art     : System.exit called, status: 0
,08-31 11:15:59.224  2556  2556 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-31 11:15:59.298  4082  4082 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-31 11:15:59.300   876  1938 I ActivityManager: Process com.android.bluetooth (pid 2556) has died
,08-31 11:15:59.338  4033  4033 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 11:15:59.366   876  1673 I ActivityManager: Start proc 4110:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-31 11:15:59.390  4033  4033 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:15:59.462  4110  4110 D AdapterServiceConfig: Adding HeadsetService
,08-31 11:15:59.462  4110  4110 D AdapterServiceConfig: Adding A2dpService
08-31 11:15:59.462  4110  4110 D AdapterServiceConfig: Adding HidService
,08-31 11:15:59.463  4110  4110 D AdapterServiceConfig: Adding HealthService
,08-31 11:15:59.463  4110  4110 D AdapterServiceConfig: Adding PanService
08-31 11:15:59.463  4110  4110 D AdapterServiceConfig: Adding GattService
,08-31 11:15:59.463  4110  4110 D AdapterServiceConfig: Adding BluetoothMapService
,08-31 11:15:59.468   876  1673 I ActivityManager: Killing 3633:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-31 11:15:59.498  4052  4072 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-31 11:15:59.525   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8bdcc71:true
,08-31 11:15:59.528  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 11:15:59.557  1732  1732 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-31 11:15:59.565  1732  1732 D SystemUpdateService: onCreate
,08-31 11:15:59.573  1732  1732 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-31 11:15:59.582  1732  4123 I SystemUpdateService: active receiver: enabled
,08-31 11:15:59.588  1732  1732 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-31 11:15:59.590  1732  4123 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-31 11:15:59.591  1732  4123 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-31 11:15:59.591  1732  4123 I SystemUpdateService: now status is 0 (complete)
08-31 11:15:59.591  1732  4123 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-31 11:15:59.591  1732  4123 I SystemUpdateService: file has been verified
,08-31 11:15:59.592  1732  4123 I SystemUpdateService: OTA package size = 12249756
,08-31 11:15:59.594  1732  2532 I iu.UploadsManager: num queued entries: 0
,08-31 11:15:59.595  1732  2532 I iu.UploadsManager: num updated entries: 0,
,08-31 11:15:59.597  1732  2532 I iu.SyncManager: NEXT; no task
,08-31 11:15:59.598  1732  4123 I SystemUpdateService: showing system update notification
,08-31 11:15:59.608  1732  1732 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-31 11:15:59.610  1732  1732 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-31 11:15:59.626   876  1673 I ActivityManager: Start proc 4125:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-31 11:15:59.629  1732  1732 D SystemUpdateService: onDestroy
,08-31 11:15:59.668  4125  4125 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-31 11:15:59.670  4125  4125 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:15:59.676  4125  4125 D SprintDMHelper: simOperator: 
,08-31 11:15:59.676  4125  4125 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-31 11:15:59.691   876  1969 I ActivityManager: Start proc 4137:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-31 11:15:59.692   876  1969 I ActivityManager: Killing 3130:android.process.acore/u0a5 (adj 15): empty #17
,08-31 11:15:59.815  2419  4151 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-31 11:15:59.835   876  1387 I ActivityManager: Start proc 4152:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-31 11:15:59.842   876  1387 I ActivityManager: Killing 3825:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-31 11:15:59.917  4152  4152 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-31 11:15:59.975  4152  4152 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-31 11:15:59.975  4152  4152 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-31 11:15:59.975  4152  4152 I GAv4    :   adb logcat -s GAv4
,08-31 11:15:59.995  4152  4152 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-31 11:16:00.002  4152  4152 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-31 11:16:00.035  4152  4169 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-31 11:16:00.134  4152  4152 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-31 11:16:00.173  4152  4152 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-31 11:16:00.186  4152  4152 I LibraryLoader: Time to load native libraries: 7 ms (timestamps 7511-7518)
,08-31 11:16:00.186  4152  4152 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-31 11:16:00.196  4152  4152 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4a93d36}
,08-31 11:16:00.196  4152  4152 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-31 11:16:00.196  4152  4152 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-31 11:16:00.205  4152  4152 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-31 11:16:00.207  4152  4152 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-31 11:16:00.227  4152  4152 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-31 11:16:00.242  4152  4152 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-31 11:16:00.243  4152  4152 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-31 11:16:00.243  4152  4152 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-31 11:16:00.243  4152  4152 I Adreno  : Build Date                       : 10/20/15
08-31 11:16:00.243  4152  4152 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-31 11:16:00.243  4152  4152 I Adreno  : Local Branch                     : M14
08-31 11:16:00.243  4152  4152 I Adreno  : Remote Branch                    : 
08-31 11:16:00.243  4152  4152 I Adreno  : Remote Branch                    : 
08-31 11:16:00.243  4152  4152 I Adreno  : Reconstruct Branch               : 
,08-31 11:16:00.323  4152  4152 I NSApplication: Starting up...
,08-31 11:16:00.333  4152  4198 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-31 11:16:00.369   876  1673 I ActivityManager: Start proc 4203:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-31 11:16:00.370   876  1673 I ActivityManager: Killing 3841:com.android.musicfx/u0a18 (adj 15): empty #17
,08-31 11:16:00.431  4203  4203 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-31 11:16:00.586   876   887 I ActivityManager: Killing 3626:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-31 11:16:01.735   876   886 D WifiService: setWifiEnabled: true pid=3969, uid=10000
,08-31 11:16:01.735   876   886 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 11:16:01.748   876  1304 D WifiConfigStore: Loading config and enabling all networks 
,08-31 11:16:01.756  3969  3969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:16:01.756  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:16:01.756  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:01.756  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:16:01.756  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:16:01.756  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:16:01.756  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:16:01.756  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:16:01.756  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:16:01.757  3969  3969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:16:01.758  3969  3969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:16:01.760  3969  3969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:16:01.761  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:16:01.761  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:01.761  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:16:01.761  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:16:01.761  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:16:01.761  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:16:01.761  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:16:01.761  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:16:01.761  3969  3969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:16:01.761  3969  3969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:16:01.783   876  1304 D WifiConfigStore: loaded 0 passpoint configs
,08-31 11:16:01.784   876  1304 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-31 11:16:01.785   876  1304 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-31 11:16:01.786   876  1304 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-31 11:16:01.786   876  1304 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-31 11:16:01.786   876  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-31 11:16:01.786   876  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-31 11:16:01.807   876  1304 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.38 rxSuccessRate=15.00 delta 1000 -> 994
,08-31 11:16:01.807   373   874 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-31 11:16:01.809   373   874 D CommandListener: Setting iface cfg
,08-31 11:16:01.811   876  1303 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '156 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 156 Failed to set address (No such device)'
08-31 11:16:01.811   876  1303 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-31 11:16:01.816   876  1304 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-31 11:16:01.816   876  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 11:16:01.819   876  1303 D WifiNative-HAL: p2pGetDeviceAddress
,08-31 11:16:01.831   876  1304 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-31 11:16:01.831   876  1303 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-31 11:16:01.915   876  1304 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-31 11:16:01.917  1469  1469 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-31 11:16:02.339  1469  1469 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-31 11:16:02.389  1469  1469 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-31 11:16:02.390  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-31 11:16:02.394   876  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 11:16:02.404   876  1304 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-31 11:16:02.404   876  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 11:16:02.405   876  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-31 11:16:02.423   876  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 11:16:02.438   373   874 D CommandListener: Setting iface cfg
,08-31 11:16:02.442   876  1304 D WifiStateMachine: Start Dhcp Watchdog 3
,08-31 11:16:02.459   876  4227 D DhcpClient: Receive thread started
,08-31 11:16:02.461   876  1306 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,08-31 11:16:02.466   876  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-31 11:16:02.561   876  1304 E native  : do suspend false
,08-31 11:16:02.583   876  2085 D DhcpClient: Broadcasting DHCPDISCOVER
,08-31 11:16:02.596   876  4227 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172689, domain null
,08-31 11:16:02.597   876  2085 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172689 seconds
,08-31 11:16:02.601   876  2085 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-31 11:16:02.614   876  4227 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-31 11:16:02.615   876  2085 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-31 11:16:02.619   373   874 D CommandListener: Setting iface cfg
,08-31 11:16:02.630   876  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-31 11:16:02.632   876  2085 D DhcpClient: Scheduling renewal in 86399s
,08-31 11:16:02.653   876  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-31 11:16:02.656   876  1304 D WifiConfigStore: No blacklist allowed without epno enabled
08-31 11:16:02.656   876  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-31 11:16:02.658   876  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-31 11:16:02.662   876  1306 D ConnectivityService: Adding iface wlan0 to network 102
,08-31 11:16:02.674   876  1304 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-31 11:16:02.720   876  1306 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-31 11:16:02.720   876  1306 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-31 11:16:02.721   876  1306 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-31 11:16:02.722   876  1306 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-31 11:16:02.723   876  1306 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-31 11:16:02.730   876  1306 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-31 11:16:02.738   876  1306 D ConnectivityService: scheduleUnvalidatedPrompt 102
08-31 11:16:02.738   876  1306 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-31 11:16:02.738   876  1304 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-31 11:16:02.739   876  1306 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-31 11:16:02.739   876  1306 D ConnectivityService:    accepting network in place of null
08-31 11:16:02.740   876  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-31 11:16:02.741   876  1306 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -61]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-31 11:16:02.779   373   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 11:16:02.811   373   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 11:16:02.815   876  1306 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-31 11:16:02.816   876  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-31 11:16:02.817   876  1306 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-31 11:16:02.821   876   893 D Tethering: MasterInitialState.processMessage what=3
,08-31 11:16:02.841  3969  3969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:16:02.841  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:16:02.841  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:02.841  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:16:02.841  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:16:02.841  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:16:02.841  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:16:02.841  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:16:02.841  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:16:02.842  3969  3969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:16:02.842  3969  3969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:16:02.845  3969  3969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:16:02.845  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:16:02.845  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:02.845  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:16:02.845  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:16:02.845  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:16:02.845  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:16:02.845  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:16:02.845  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:16:02.845  3969  3969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:16:02.845  3969  3969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:16:02.851  1732  1732 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-31 11:16:02.854  1732  1732 D SystemUpdateService: onCreate
08-31 11:16:02.857  1732  1732 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-31 11:16:02.861  1732  4238 I SystemUpdateService: active receiver: enabled
08-31 11:16:02.869  1732  4238 I SystemUpdateService: Already downloaded, skipping offpeak checks.
08-31 11:16:02.872  1732  4238 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-31 11:16:02.872  1732  4238 I SystemUpdateService: now status is 0 (complete)
08-31 11:16:02.872  1732  4238 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-31 11:16:02.873  1732  1732 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
08-31 11:16:02.873  1732  4238 I SystemUpdateService: file has been verified
08-31 11:16:02.874  1732  4238 I SystemUpdateService: OTA package size = 12249756
08-31 11:16:02.876  1732  4238 I SystemUpdateService: showing system update notification
08-31 11:16:02.880  1732  2532 I iu.UploadsManager: num queued entries: 0
08-31 11:16:02.881  1732  2532 I iu.UploadsManager: num updated entries: 0
08-31 11:16:02.881  1732  4241 I MDM     : [181] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-31 11:16:02.881  1732  4241 W BaseAppContext: Using Auth Proxy for data requests.
08-31 11:16:02.882  1732  4241 V GoogleAuthProtoRequest: [181] a.<init>: mAccountName set to: thalitester@gmail.com
08-31 11:16:02.882  1732  2532 I iu.SyncManager: NEXT; no task
,08-31 11:16:02.888  1732  1732 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-31 11:16:02.888  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 11:16:02.890  1732  1732 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-31 11:16:02.890  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 11:16:02.899  4125  4125 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:16:02.900  1732  1732 D SystemUpdateService: onDestroy
,08-31 11:16:02.903  4125  4125 D SprintDMHelper: simOperator: 
,08-31 11:16:02.903  4125  4125 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-31 11:16:02.933  1502  2364 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-31 11:16:02.933  1502  2364 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-31 11:16:02.933  1502  2364 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 11:16:02.933  1502  2364 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 11:16:02.951  1732  4241 E MDM     : [181] SitrepService.a: Error sending sitrep.
,08-31 11:16:02.960  3743  4243 V KeepSync: Connecting to GoogleApiClient
,08-31 11:16:02.960   876  1939 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-31 11:16:03.006  1502  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-31 11:16:03.006  1502  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-31 11:16:03.006  1502  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 11:16:03.006  1502  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 11:16:03.020  1732  4248 V BaseAuthAsyncOperation: access token request failed
,08-31 11:16:03.021  3743  4243 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-31 11:16:03.080  1502  2363 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-31 11:16:03.081  1502  2363 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-31 11:16:03.081  1502  2363 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 11:16:03.081  1502  2363 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 11:16:03.102  3743  4243 E KeepSync: IOException
08-31 11:16:03.102  3743  4243 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-31 11:16:03.102  3743  4243 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-31 11:16:03.102  3743  4243 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-31 11:16:03.102  3743  4243 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-31 11:16:03.102  3743  4243 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-31 11:16:03.102  3743  4243 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-31 11:16:03.102  3743  4243 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-31 11:16:03.102  3743  4243 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-31 11:16:03.102  3743  4243 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-31 11:16:03.102  3743  4243 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-31 11:16:03.102  3743  4243 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-31 11:16:03.102  3743  4243 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-31 11:16:03.102  3743  4243 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-31 11:16:03.102  3743  4243 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-31 11:16:03.102  3743  4243 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-31 11:16:03.102  3743  4243 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-31 11:16:03.102  3743  4243 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-31 11:16:03.102  3743  4243 E KeepSync: 	... 10 more
08-31 11:16:03.103  3743  4243 W KeepSync: Sync result 2
,08-31 11:16:03.108   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 130832, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-31 11:16:03.813   876  4226 D NetlinkSocketObserver: NeighborEvent{elapsedMs=141145, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-31 11:16:03.817   876  1306 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-31 11:16:04.742   876  1968 D WifiService: setWifiEnabled: false pid=3969, uid=10000
,08-31 11:16:04.742   876  1968 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 11:16:04.773  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-31 11:16:04.778   876  1304 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-31 11:16:04.778   876  1304 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-31 11:16:04.779   876  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-31 11:16:04.780   876  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 11:16:04.804   876  2085 D DhcpClient: Clearing IP address
08-31 11:16:04.804   373   874 D CommandListener: Clearing all IP addresses on wlan0
,08-31 11:16:04.815  2419  4244 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
08-31 11:16:04.815   373   874 D CommandListener: Setting iface cfg
,08-31 11:16:04.819  2419  4244 W Babel_NetworkConnectionCheckingService: java.net.SocketTimeoutException: failed to connect to clients3.google.com/216.58.209.206 (port 80) after 5000ms: isConnected failed: ETIMEDOUT (Connection timed out)
08-31 11:16:04.819  2419  4244 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.isConnected(IoBridge.java:232)
08-31 11:16:04.819  2419  4244 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connectErrno(IoBridge.java:171)
08-31 11:16:04.819  2419  4244 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connect(IoBridge.java:122)
08-31 11:16:04.819  2419  4244 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
08-31 11:16:04.819  2419  4244 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:452)
08-31 11:16:04.819  2419  4244 W Babel_NetworkConnectionCheckingService: 	at java.net.Socket.connect(Socket.java:884)
08-31 11:16:04.819  2419  4244 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.Platform.connectSocket(Platform.java:117)
08-31 11:16:04.819  2419  4244 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectRawSocket(SocketConnector.java:160)
08-31 11:16:04.819  2419  4244 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectCleartext(SocketConnector.java:67)
08-31 11:16:04.819  2419  4244 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connect(Connection.java:152)
08-31 11:16:04.819  2419  4244 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connectAndSetOwner(Connection.java:185)
08-31 11:16:04.819  2419  4244 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.OkHttpClient$1.connectAndSetOwner(OkHttpClient.java:128)
08-31 11:16:04.819  2419  4244 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.nextConnection(HttpEngine.java:341)
08-31 11:16:04.819  2419  4244 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:330)
08-31 11:16:04.819  2419  4244 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:248)
08-31 11:16:04.819  2419  4244 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:437)
08-31 11:16:04.819  2419  4244 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
08-31 11:16:04.819  2419  4244 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
08-31 11:16:04.819  2419  4244 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
08-31 11:16:04.819  2419  4244 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
08-31 11:16:04.819  2419  4244 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-31 11:16:04.819  2419  4244 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:16:04.819  2419  4244 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:16:04.819  2419  4244 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 11:16:04.819  2419  4244 W Babel_NetworkConnectionCheckingService: Caused by: android.system.ErrnoException: isConnected failed: ETIMEDOUT (Connection timed out)
08-31 11:16:04.819  2419  4244 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.isConne,cted(IoBridge.java:223)
08-31 11:16:04.819  2419  4244 W Babel_NetworkConnectionCheckingService: 	... 23 more
08-31 11:16:04.819  2419  4244 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-31 11:16:04.824   876  3232 I ActivityManager: Killing 3863:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-31 11:16:04.838   876  4227 D DhcpClient: Receive thread stopped
,08-31 11:16:04.900   876  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-31 11:16:04.900   876  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] got DISCONNECTED, was satisfying 3
,08-31 11:16:04.902   876  1304 D WifiStateMachine: Start Disconnecting Watchdog 3
,08-31 11:16:04.913   397   397 E Parcel  : Reading a NULL string not supported here.
,08-31 11:16:04.914   876  1306 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 102]
,08-31 11:16:04.918   876  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-31 11:16:04.920   373   874 D CommandListener: Clearing all IP addresses on wlan0
08-31 11:16:04.928   876  1304 D WifiConfigStore: Retrieve network priorities after PNO.
08-31 11:16:04.931  3969  3969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-31 11:16:04.931  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:16:04.931  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:04.931  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:16:04.931  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:16:04.931  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:16:04.931  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:16:04.931  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:16:04.931  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:16:04.931  3969  3969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-31 11:16:04.931  3969  3969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:16:04.932  3969  3969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:16:04.932  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:16:04.932  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:04.932  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:16:04.932  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:16:04.932  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:16:04.932  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:16:04.932  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:16:04.932  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:16:04.932  3969  3969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:16:04.932  3969  3969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:16:04.935   876  1304 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-31 11:16:04.938  2101  2307 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 11:16:04.961   373   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 11:16:04.988   373   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 11:16:04.990   876  1306 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-31 11:16:04.990   876  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:16:04.997   876   893 D Tethering: MasterInitialState.processMessage what=3
,08-31 11:16:05.000  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:16:05.004  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:16:05.012  1732  1732 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-31 11:16:05.015  1732  1732 D SystemUpdateService: onCreate
,08-31 11:16:05.020  1732  1732 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-31 11:16:05.024  1732  4260 I SystemUpdateService: active receiver: enabled
,08-31 11:16:05.027  1732  4260 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-31 11:16:05.031  1732  4260 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-31 11:16:05.031  1732  4260 I SystemUpdateService: now status is 0 (complete)
08-31 11:16:05.031  1732  4260 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-31 11:16:05.031  1732  4260 I SystemUpdateService: file has been verified
08-31 11:16:05.032  1732  4260 I SystemUpdateService: OTA package size = 12249756
,08-31 11:16:05.037  1732  1732 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-31 11:16:05.045  1732  2532 I iu.UploadsManager: num queued entries: 0
08-31 11:16:05.045  1732  2532 I iu.UploadsManager: num updated entries: 0
08-31 11:16:05.046  1732  2532 I iu.SyncManager: NEXT; no task
,08-31 11:16:05.048  1732  1732 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-31 11:16:05.049  1732  1732 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-31 11:16:05.051  4125  4125 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:16:05.056  4125  4125 D SprintDMHelper: simOperator: 
08-31 11:16:05.056  4125  4125 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-31 11:16:05.062  1732  4260 I SystemUpdateService: showing system update notification
,08-31 11:16:05.069  2419  4264 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-31 11:16:05.074   373   874 E Netd    : netlink response contains error (No such file or directory)
,08-31 11:16:05.076   876  1306 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-31 11:16:05.101  1732  1732 D SystemUpdateService: onDestroy
,08-31 11:16:07.787   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d085efe:true
,08-31 11:16:07.788  4110  4110 D BluetoothAdapterState: make() - Creating AdapterState
,08-31 11:16:07.798  4110  4110 I bt_bluedroid: init
,08-31 11:16:07.798  4110  4266 I BluetoothAdapterState: Entering OffState
,08-31 11:16:07.804  4110  4267 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-31 11:16:07.805  4110  4267 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-31 11:16:07.805  4110  4267 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-31 11:16:07.805  4110  4267 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-31 11:16:07.807  4110  4110 I bt_bluedroid: get_profile_interface socket
,08-31 11:16:07.811  4110  4110 I bt_bluedroid: get_profile_interface sdp
,08-31 11:16:07.815  4110  4270 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-31 11:16:07.816  4110  4120 I bt_bluedroid: config_hci_snoop_log
,08-31 11:16:07.818  4110  4270 D BluetoothAdapterProperties: Name is: Nexus 6
08-31 11:16:07.818   876   893 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-31 11:16:07.826  4110  4266 D BluetoothAdapterState: Current state: OFF, message: 0
,08-31 11:16:07.827  4110  4266 D BluetoothAdapterProperties: Setting state to 14
,08-31 11:16:07.827  4110  4266 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-31 11:16:07.832  4110  4266 D BluetoothBondStateMachine: make
,08-31 11:16:07.836  4110  4271 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-31 11:16:07.844  4110  4266 I BluetoothAdapterState: Entering PendingCommandState
,08-31 11:16:07.846  4110  4110 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-31 11:16:07.853  4110  4110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@287c81c
,08-31 11:16:07.855  4110  4110 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 11:16:07.856  4110  4110 D BtGatt.GattService: Received start request. Starting profile...
,08-31 11:16:07.857  4110  4110 D BtGatt.GattService: start()
08-31 11:16:07.857  4110  4110 I bt_bluedroid: get_profile_interface gatt
,08-31 11:16:07.859  4110  4110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@287c81c
,08-31 11:16:07.860  4110  4110 D BtGatt.AdvertiseManager: advertise manager created
,08-31 11:16:07.875  4110  4110 V BluetoothAdapterState: isTurningOff()=false
,08-31 11:16:07.875  4110  4110 V BluetoothAdapterState: isTurningOn()=false
08-31 11:16:07.875  4110  4110 V BluetoothAdapterState: isBleTurningOn()=true
,08-31 11:16:07.875  4110  4110 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 11:16:07.877  4110  4266 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-31 11:16:07.877  4110  4266 I bt_bluedroid: enable
,08-31 11:16:07.878  4110  4267 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-31 11:16:07.879  4110  4267 I bt_hci  : start_up
,08-31 11:16:07.898  4110  4267 I bt_vendor: alloc value 0xb39cc189
,08-31 11:16:07.898  4110  4267 I bt_vendor: init
,08-31 11:16:07.898  4110  4267 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-31 11:16:07.898  4110  4267 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-31 11:16:08.004  4110  4267 D bt_hci  : start_up starting async portion
,08-31 11:16:08.005  4110  4274 I bt_hci  : event_finish_startup
,08-31 11:16:08.005  4110  4274 I bt_hci_h4: hal_open
08-31 11:16:08.005  4110  4274 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-31 11:16:08.016  4110  4274 I bt_userial_vendor: device fd = 51 open
,08-31 11:16:08.047  4110  4274 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 11:16:08.080  4110  4274 D bt_hwcfg: Chipset BCM4354A2
,08-31 11:16:08.080  4110  4274 D bt_hwcfg: Target name = [BCM4354A2]
08-31 11:16:08.081  4110  4274 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-31 11:16:08.761  4110  4274 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-31 11:16:08.762  4110  4274 D bt_hwcfg: Settlement delay -- 100 ms
08-31 11:16:08.762  4110  4274 I bt_hwcfg: Setting fw settlement delay to 100 
,08-31 11:16:08.878  4110  4274 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 11:16:08.878  4110  4274 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-31 11:16:08.910  4110  4274 I bt_hwcfg: vendor lib fwcfg completed
,08-31 11:16:08.911  4110  4274 I bt_vendor: firmware callback
08-31 11:16:08.911  4110  4274 I bt_hci  : firmware_config_callback
,08-31 11:16:08.918  4110  4278 I bt_btu  : btu_task pending for preload complete event
,08-31 11:16:08.919  4110  4278 I bt_btu_task: Bluetooth chip preload is complete
08-31 11:16:08.919  4110  4278 I bt_btu  : btu_task received preload complete event
,08-31 11:16:08.926  4110  4278 I         : BTE_InitTraceLevels -- TRC_HCI
08-31 11:16:08.927  4110  4278 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-31 11:16:08.927  4110  4278 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-31 11:16:08.927  4110  4278 I         : BTE_InitTraceLevels -- TRC_AVDT
08-31 11:16:08.928  4110  4278 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-31 11:16:08.928  4110  4278 I         : BTE_InitTraceLevels -- TRC_A2D
,08-31 11:16:08.928  4110  4278 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 11:16:08.928  4110  4278 I         : BTE_InitTraceLevels -- TRC_BTM
,08-31 11:16:08.928  4110  4278 I         : BTE_InitTraceLevels -- TRC_GAP
08-31 11:16:08.929  4110  4278 I         : BTE_InitTraceLevels -- TRC_PAN
,08-31 11:16:08.929  4110  4278 I         : BTE_InitTraceLevels -- TRC_SDP
08-31 11:16:08.929  4110  4278 I         : BTE_InitTraceLevels -- TRC_GATT
,08-31 11:16:08.929  4110  4278 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 11:16:08.930  4110  4278 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-31 11:16:08.930  4110  4278 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-31 11:16:08.994  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 11:16:09.004  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 11:16:09.008  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 11:16:09.059  4110  4278 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3949d9d
,08-31 11:16:09.059  4110  4278 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3949d9d 
,08-31 11:16:09.071  4110  4270 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-31 11:16:09.075  4110  4270 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-31 11:16:09.075  4110  4270 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-31 11:16:09.076  1502  2363 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-31 11:16:09.076  1502  2363 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-31 11:16:09.077  1502  2363 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 11:16:09.077  1502  2363 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-31 11:16:09.078  4110  4270 D BluetoothAdapterProperties: Name is: Nexus 6
,08-31 11:16:09.087  4110  4270 D BluetoothAdapterProperties: Scan Mode:20
,08-31 11:16:09.087  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:16:09.088  4110  4270 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 11:16:09.088  4110  4270 D bt_hci  : do_postload posting postload work item
,08-31 11:16:09.088  4110  4274 I bt_hci  : event_postload
,08-31 11:16:09.089  4110  4274 I bt_vendor: sco_config_cb
08-31 11:16:09.089  4110  4274 I bt_hci  : sco_config_callback postload finished.
08-31 11:16:09.091  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:16:09.092  4110  4274 I bt_vendor: low_power_mode_cb
08-31 11:16:09.093  4110  4270 D bt_bte_conf: Device ID record 1 : primary
08-31 11:16:09.093  4110  4270 D bt_bte_conf:   vendorId            = 000f
08-31 11:16:09.093  4110  4270 D bt_bte_conf:   vendorIdSource      = 0001
,08-31 11:16:09.094  4110  4270 D bt_bte_conf:   product             = 1200
,08-31 11:16:09.094  4110  4270 D bt_bte_conf:   version             = 1436
08-31 11:16:09.094  4110  4270 D bt_bte_conf:   clientExecutableURL = 
08-31 11:16:09.094  4110  4270 D bt_bte_conf:   serviceDescription  = 
,08-31 11:16:09.094  4110  4270 D bt_bte_conf:   documentationURL    = 
08-31 11:16:09.095  4110  4270 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-31 11:16:09.095  4110  4267 D bt_stack_manager: event_start_up_stack finished
,08-31 11:16:09.096  4110  4266 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-31 11:16:09.097  4110  4266 D BluetoothAdapterProperties: Setting state to 15
08-31 11:16:09.097  4110  4266 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-31 11:16:09.099  4110  4266 I BluetoothAdapterState: Entering BleOnState
08-31 11:16:09.101  4110  4266 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-31 11:16:09.101  4110  4266 D BluetoothAdapterProperties: Setting state to 11
,08-31 11:16:09.102  4110  4266 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-31 11:16:09.107  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:16:09.110  4110  4110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@287c81c
,08-31 11:16:09.111  4110  4110 D HeadsetService: Received start request. Starting profile...
08-31 11:16:09.112  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-31 11:16:09.114  4110  4110 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-31 11:16:09.115  4110  4110 D HeadsetStateMachine: make
,08-31 11:16:09.125  4110  4266 I BluetoothAdapterState: Entering PendingCommandState
,08-31 11:16:09.128  3693  3693 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-31 11:16:09.128  3693  3693 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-31 11:16:09.129  3693  3693 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-31 11:16:09.129  4110  4110 D HeadsetStateMachine: max_hf_connections = 1
08-31 11:16:09.129  4110  4110 I bt_bluedroid: get_profile_interface handsfree
08-31 11:16:09.129  4110  4270 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-31 11:16:09.130  4110  4270 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
08-31 11:16:09.133  4110  4110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@287c81c
08-31 11:16:09.133  4110  4110 D A2dpService: Received start request. Starting profile...
08-31 11:16:09.134  4110  4110 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-31 11:16:09.134  4110  4110 I bt_bluedroid: get_profile_interface avrcp
,08-31 11:16:09.141  4110  4110 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-31 11:16:09.142  4110  4110 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 11:16:09.142  4110  4110 D A2dpStateMachine: make
,08-31 11:16:09.143  4110  4110 I bt_bluedroid: get_profile_interface a2dp
08-31 11:16:09.144  4110  4270 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-31 11:16:09.145  4110  4287 D A2dpStateMachine: Enter Disconnected: -2
08-31 11:16:09.145  4110  4110 I BluetoothHidServiceJni: classInitNative: succeeds
08-31 11:16:09.146  4110  4110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@287c81c
,08-31 11:16:09.147  4033  4033 D BluetoothInputDevice: Proxy object connected
08-31 11:16:09.147  4110  4110 D HidService: Received start request. Starting profile...
08-31 11:16:09.148  4110  4110 I bt_bluedroid: get_profile_interface hidhost
,08-31 11:16:09.148  4110  4110 D HidService: setHidService(): set to: null
08-31 11:16:09.148  4110  4270 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb392b3e5
08-31 11:16:09.148  4110  4270 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-31 11:16:09.148  4110  4110 I BluetoothHealthServiceJni: classInitNative: succeeds
08-31 11:16:09.149  4033  4033 D HidProfile: Bluetooth service connected
,08-31 11:16:09.149  4110  4110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@287c81c
08-31 11:16:09.150  4110  4110 D HealthService: Received start request. Starting profile...
,08-31 11:16:09.151  4110  4110 I bt_bluedroid: get_profile_interface health
,08-31 11:16:09.153  4110  4110 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-31 11:16:09.154  4110  4110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@287c81c,
,08-31 11:16:09.155  4110  4110 D PanService: Received start request. Starting profile...
,08-31 11:16:09.155  4033  4033 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 11:16:09.155  4110  4110 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 11:16:09.155  4110  4110 I bt_bluedroid: get_profile_interface pan
08-31 11:16:09.155  4033  4033 D PanProfile: Bluetooth service connected
08-31 11:16:09.155  4110  4270 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-31 11:16:09.157  4110  4110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@287c81c
,08-31 11:16:09.158  4110  4110 D BluetoothMapService: Received start request. Starting profile...
,08-31 11:16:09.158  4033  4033 D BluetoothMap: Proxy object connected
08-31 11:16:09.158  4110  4110 D BluetoothMapService: start()
08-31 11:16:09.159  4033  4033 D MapProfile: Bluetooth service connected
08-31 11:16:09.159  4033  4033 D BluetoothMap: getConnectedDevices()
08-31 11:16:09.159  4033  4033 D BluetoothMap: Bluetooth is Not enabled
08-31 11:16:09.160  4110  4110 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-31 11:16:09.161  4110  4110 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-31 11:16:09.161  4110  4110 D BluetoothMapAppObserver: createReceiver()
,08-31 11:16:09.162  4110  4110 D BluetoothMapAppObserver: initObservers()
,08-31 11:16:09.162  4110  4110 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-31 11:16:09.169  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 11:16:09.169  4110  4284 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-31 11:16:09.170  4110  4110 V BluetoothAdapterState: isTurningOff()=false
08-31 11:16:09.170  4110  4110 V BluetoothAdapterState: isTurningOn()=true
08-31 11:16:09.170  4110  4110 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:16:09.170  4110  4110 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 11:16:09.171  4110  4110 V BluetoothAdapterState: isTurningOff()=false
08-31 11:16:09.171  4110  4110 V BluetoothAdapterState: isTurningOn()=true
,08-31 11:16:09.171  4110  4110 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:16:09.171  4110  4110 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:16:09.172  4110  4110 V BluetoothAdapterState: isTurningOff()=false
08-31 11:16:09.172  4110  4110 V BluetoothAdapterState: isTurningOn()=true
08-31 11:16:09.172  4110  4110 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:16:09.172  4110  4110 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 11:16:09.172  4110  4110 V BluetoothAdapterState: isTurningOff()=false
,08-31 11:16:09.172  4110  4110 V BluetoothAdapterState: isTurningOn()=true
,08-31 11:16:09.172  4110  4110 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:16:09.172  4110  4110 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 11:16:09.172  4110  4110 V BluetoothAdapterState: isTurningOff()=false
,08-31 11:16:09.172  4110  4110 V BluetoothAdapterState: isTurningOn()=true
08-31 11:16:09.172  4110  4110 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:16:09.172  4110  4110 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:16:09.173  4110  4110 V BluetoothAdapterState: isTurningOff()=false
,08-31 11:16:09.173  4110  4110 V BluetoothAdapterState: isTurningOn()=true
08-31 11:16:09.173  4110  4110 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:16:09.173  4110  4110 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:16:09.173  4110  4266 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-31 11:16:09.173  4110  4266 D BluetoothAdapterProperties: ScanMode =  20
08-31 11:16:09.173  4110  4266 D BluetoothAdapterProperties: State =  11
,08-31 11:16:09.175  4110  4270 D BluetoothAdapterProperties: Scan Mode:21
08-31 11:16:09.175  4110  4270 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 11:16:09.175  4110  4266 D BluetoothAdapterProperties: Setting state to 12
08-31 11:16:09.175  4110  4266 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-31 11:16:09.175  4110  4266 I BluetoothAdapterState: Entering OnState
,08-31 11:16:09.176  1350  2044 D BluetoothPan: onBluetoothStateChange on: true
,08-31 11:16:09.177   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:16:09.177  1350  1350 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 11:16:09.177  1350  1350 D PanProfile: Bluetooth service connected
08-31 11:16:09.178  1921  1937 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:16:09.178  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:16:09.178  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:09.178  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:16:09.178  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:16:09.178  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:16:09.178  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null,
08-31 11:16:09.178  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:16:09.178  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:16:09.178  4033  4045 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 11:16:09.180  3969  3969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:16:09.181  1350  1372 D BluetoothMap: onBluetoothStateChange: up=true
,08-31 11:16:09.182  1350  1350 D BluetoothMap: Proxy object connected
,08-31 11:16:09.182  1350  1350 D MapProfile: Bluetooth service connected
08-31 11:16:09.182  4033  4043 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 11:16:09.182  1350  1350 D BluetoothMap: getConnectedDevices()
,08-31 11:16:09.183  1350  2045 D BluetoothPbap: onBluetoothStateChange: up=true
,08-31 11:16:09.184  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:16:09.184  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:09.184  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:16:09.184  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:16:09.184  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:16:09.184  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:16:09.184  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:16:09.184  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:16:09.184  1350  2044 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 11:16:09.185  4033  4045 D BluetoothMap: onBluetoothStateChange: up=true
08-31 11:16:09.185  3969  3969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:16:09.186  1350  1381 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 11:16:09.186  1350  1350 D BluetoothInputDevice: Proxy object connected
,08-31 11:16:09.186  1350  1350 D HidProfile: Bluetooth service connected
,08-31 11:16:09.187   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 11:16:09.187   876   893 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 11:16:09.188   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:16:09.188  1350  2128 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:16:09.188  4110  4110 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-31 11:16:09.189  4110  4110 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-31 11:16:09.190  4033  4043 D BluetoothPan: onBluetoothStateChange on: true
08-31 11:16:09.190  4110  4110 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:16:09.191   876   876 I Telecom : BluetoothPhoneService: queryPhoneState
08-31 11:16:09.194  4110  4110 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:16:09.195  4033  4033 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-31 11:16:09.195  4110  4110 D ObexServerSockets: Succeed to create listening sockets 
08-31 11:16:09.195  4110  4110 D ObexServerSockets0: startAccept()
08-31 11:16:09.195  4110  4110 D ObexServerSockets0: prepareForNewConnect()
08-31 11:16:09.197  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:16:09.198  4110  4110 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-31 11:16:09.198  4110  4294 D ObexServerSockets0: Accepting socket connection...
08-31 11:16:09.198  4110  4110 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-31 11:16:09.198  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:09.199   876   876 D BluetoothA2dp: Proxy object connected
08-31 11:16:09.199  4033  4033 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-31 11:16:09.200  1350  1350 D BluetoothA2dp: Proxy object connected,
08-31 11:16:09.200  4110  4110 D BluetoothMapService: onReceive
08-31 11:16:09.200  4110  4110 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:16:09.200  4110  4110 D BluetoothMapService: STATE_ON
08-31 11:16:09.200  4110  4295 D ObexServerSockets0: Accepting socket connection...
,08-31 11:16:09.210  4033  4033 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 11:16:09.213  4033  4033 D BluetoothA2dp: Proxy object connected
,08-31 11:16:09.218  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 11:16:09.219  4033  4033 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:16:09.224  4033  4033 D BluetoothPbap: Proxy object connected
,08-31 11:16:09.224  4110  4110 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-31 11:16:09.224  4110  4110 D ObexServerSockets0: prepareForNewConnect()
08-31 11:16:09.224  4033  4033 D PbapServerProfile: Bluetooth service connected
,08-31 11:16:09.228  1350  1350 D BluetoothPbap: Proxy object connected
,08-31 11:16:09.229  1350  1350 D PbapServerProfile: Bluetooth service connected
,08-31 11:16:09.239  4110  4299 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 11:16:09.260  4110  4303 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 11:16:09.261  4110  4303 I BtOppRfcommListener: Accept thread started.
,08-31 11:16:09.278   876   876 D BluetoothHeadset: Proxy object connected
08-31 11:16:09.279   876   876 D BluetoothHeadset: Proxy object connected
,08-31 11:16:09.279  1350  2045 D BluetoothHeadset: Proxy object connected
08-31 11:16:09.279  1350  1350 D HeadsetProfile: Bluetooth service connected
08-31 11:16:09.279   876   876 D BluetoothHeadset: Proxy object connected
,08-31 11:16:09.280  1921  1934 D BluetoothHeadset: Proxy object connected
,08-31 11:16:09.288   876   893 D BluetoothHeadset: Proxy object connected
,08-31 11:16:09.288   876   893 D BluetoothHeadset: Proxy object connected
,08-31 11:16:09.289  1350  1372 D BluetoothHeadset: Proxy object connected
08-31 11:16:09.290  1350  1350 D HeadsetProfile: Bluetooth service connected
,08-31 11:16:09.305  4033  4045 D BluetoothHeadset: Proxy object connected
,08-31 11:16:09.307  4033  4033 D HeadsetProfile: Bluetooth service connected
,08-31 11:16:09.494   876  4225 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on <unknown ssid>, connectivitycheck.gstatic.com=2a00:1450:400d:807::200e
,08-31 11:16:09.500   876  4225 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Probably not a portal: exception java.net.SocketException: Binding socket to network 102 failed: ENONET (Machine is not on the network)
,08-31 11:16:09.502   876  1306 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-31 11:16:10.739   876  1306 D ConnectivityService: handlePromptUnvalidated 102
,08-31 11:16:10.761  4110  4266 D BluetoothAdapterState: Current state: ON, message: 23,
08-31 11:16:10.761  4110  4266 D BluetoothAdapterProperties: Setting state to 13
08-31 11:16:10.761  4110  4266 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-31 11:16:10.763  4110  4266 D BluetoothAdapterProperties: onBluetoothDisable()
,08-31 11:16:10.767  4110  4266 I BluetoothAdapterState: Entering PendingCommandState
,08-31 11:16:10.775  4110  4110 D BluetoothMapService: onReceive
08-31 11:16:10.775  4110  4110 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:16:10.776  4110  4110 D BluetoothMapService: STATE_TURNING_OFF
,08-31 11:16:10.777  4110  4110 D BluetoothMapService: MAP Service closeService in
08-31 11:16:10.777  4110  4110 D BluetoothMapMasInstance0: MAP Service shutdown
08-31 11:16:10.779  4110  4110 D ObexServerSockets0: shutdown(block = true)
08-31 11:16:10.779  3969  3969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:16:10.779  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:16:10.779  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:10.779  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:16:10.779  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:16:10.779  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:16:10.779  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:16:10.779  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:16:10.779  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:16:10.779  4110  4294 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-31 11:16:10.781  3969  3969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:16:10.782  3969  3969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:16:10.783  4110  4270 D BluetoothAdapterProperties: Scan Mode:20
08-31 11:16:10.784  4110  4266 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-31 11:16:10.785  4110  4110 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-31 11:16:10.785  4033  4033 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-31 11:16:10.785  4110  4295 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-31 11:16:10.786  4110  4280 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-31 11:16:10.787  4110  4110 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-31 11:16:10.789  4110  4110 I BtOppRfcommListener: stopping Accept Thread
08-31 11:16:10.790  4110  4303 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-31 11:16:10.790  3969  3969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:16:10.790  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:16:10.790  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:10.790  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:16:10.790  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:16:10.790  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:16:10.790  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:16:10.790  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:16:10.790  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:16:10.793  3969  3969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:16:10.793  3969  3969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:16:10.796  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:10.798  4110  4303 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-31 11:16:10.800  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:10.800  4110  4110 D HeadsetService: Received stop request...Stopping profile...
08-31 11:16:10.802   876   876 D BluetoothHeadset: Proxy object disconnected
08-31 11:16:10.802   876   876 D BluetoothHeadset: Proxy object disconnected
,08-31 11:16:10.802  1350  2045 D BluetoothHeadset: Proxy object disconnected
08-31 11:16:10.802  1350  1350 D HeadsetProfile: Bluetooth service disconnected
08-31 11:16:10.802   876   876 D BluetoothHeadset: Proxy object disconnected
08-31 11:16:10.803  4110  4110 D A2dpService: Received stop request...Stopping profile...
08-31 11:16:10.803  4110  4287 D A2dpStateMachine: Exit Disconnected: -1
08-31 11:16:10.803  4033  4043 D BluetoothHeadset: Proxy object disconnected
08-31 11:16:10.804  1921  2125 D BluetoothHeadset: Proxy object disconnected
08-31 11:16:10.804   876   876 D BluetoothA2dp: Proxy object disconnected
08-31 11:16:10.806  1350  1350 D BluetoothA2dp: Proxy object disconnected
08-31 11:16:10.806  4110  4110 D HidService: Received stop request...Stopping profile...
08-31 11:16:10.807  4110  4110 D HidService: Stopping Bluetooth HidService
08-31 11:16:10.807  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 11:16:10.809  1350  1350 D BluetoothInputDevice: Proxy object disconnected
08-31 11:16:10.809  1350  1350 D HidProfile: Bluetooth service disconnected
08-31 11:16:10.811  4110  4110 D HealthService: Received stop request...Stopping profile...
,08-31 11:16:10.811  4110  4110 V BluetoothAdapterState: isTurningOff()=true
08-31 11:16:10.811  4110  4110 V BluetoothAdapterState: isTurningOn()=false
08-31 11:16:10.812  4110  4110 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:16:10.812  4110  4110 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 11:16:10.813  4033  4033 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:16:10.813  4110  4110 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-31 11:16:10.813  4110  4110 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 11:16:10.813  4110  4270 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-31 11:16:10.813  4110  4278 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-31 11:16:10.813  4110  4278 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 11:16:10.813  4110  4278 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 11:16:10.813  4110  4270 E bt_btif : btif_hf_upstreams_evt: Invalid index 17
08-31 11:16:10.814  4033  4033 D HeadsetProfile: Bluetooth service disconnected
08-31 11:16:10.814  4033  4033 D BluetoothA2dp: Proxy object disconnected
,08-31 11:16:10.814  4033  4033 D BluetoothInputDevice: Proxy object disconnected
,08-31 11:16:10.814  4033  4033 D HidProfile: Bluetooth service disconnected
08-31 11:16:10.815  4110  4110 D PanService: Received stop request...Stopping profile...
08-31 11:16:10.817  1350  1350 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-31 11:16:10.817  4110  4110 V BluetoothAdapterState: isTurningOff()=true
,08-31 11:16:10.817  4110  4110 V BluetoothAdapterState: isTurningOn()=false
08-31 11:16:10.817  1350  1350 D PanProfile: Bluetooth service disconnected
08-31 11:16:10.817  4110  4110 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:16:10.817  4110  4110 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 11:16:10.817  4033  4033 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-31 11:16:10.817  4033  4033 D PanProfile: Bluetooth service disconnected
08-31 11:16:10.818  4110  4270 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-31 11:16:10.818  4110  4278 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 11:16:10.818  4110  4278 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 11:16:10.819  4110  4278 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:16:10.819  4110  4278 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:16:10.819  4110  4278 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:16:10.819  4110  4278 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-31 11:16:10.821  4110  4110 D BluetoothMapService: Received stop request...Stopping profile...
08-31 11:16:10.821  4110  4110 D BluetoothMapService: stop()
08-31 11:16:10.821  4110  4110 D BluetoothMapAppObserver: deinitObservers()
08-31 11:16:10.822  4110  4110 D BluetoothMapAppObserver: removeReceiver()
,08-31 11:16:10.823  4033  4033 D BluetoothMap: Proxy object disconnected
08-31 11:16:10.823  4033  4033 D MapProfile: Bluetooth service disconnected
08-31 11:16:10.823  1350  1350 D BluetoothMap: Proxy object disconnected
08-31 11:16:10.823  1350  1350 D MapProfile: Bluetooth service disconnected
08-31 11:16:10.825  4033  4033 D BluetoothPbap: Proxy object disconnected
08-31 11:16:10.825  4033  4033 D PbapServerProfile: Bluetooth service disconnected
08-31 11:16:10.825  4110  4110 V BluetoothAdapterState: isTurningOff()=true
08-31 11:16:10.825  1350  1350 D BluetoothPbap: Proxy object disconnected
08-31 11:16:10.825  4110  4110 V BluetoothAdapterState: isTurningOn()=false
,08-31 11:16:10.825  4110  4110 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:16:10.825  4110  4110 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:16:10.825  1350  1350 D PbapServerProfile: Bluetooth service disconnected
08-31 11:16:10.826  4110  4110 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-31 11:16:10.826  4110  4270 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-31 11:16:10.826  4110  4110 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-31 11:16:10.826  4110  4110 V BluetoothAdapterState: isTurningOff()=true
,08-31 11:16:10.826  4110  4110 V BluetoothAdapterState: isTurningOn()=false
,08-31 11:16:10.826  4110  4110 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:16:10.827  4110  4110 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:16:10.827  4110  4110 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 11:16:10.827  4110  4270 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-31 11:16:10.827  4110  4110 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-31 11:16:10.827  4110  4110 V BluetoothAdapterState: isTurningOff()=true
08-31 11:16:10.827  4110  4110 V BluetoothAdapterState: isTurningOn()=false
08-31 11:16:10.827  4110  4110 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 11:16:10.827  4110  4110 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:16:10.828  4110  4110 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 11:16:10.828  4110  4110 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-31 11:16:10.828  4110  4110 D BluetoothMapService: MAP Service closeService in
,08-31 11:16:10.828  4110  4110 V BluetoothAdapterState: isTurningOff()=true
08-31 11:16:10.829  4110  4110 V BluetoothAdapterState: isTurningOn()=false
08-31 11:16:10.829  4110  4110 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:16:10.829  4110  4110 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:16:10.829  4110  4266 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-31 11:16:10.829  4110  4266 D BluetoothAdapterProperties: Setting state to 15
08-31 11:16:10.829  4110  4266 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-31 11:16:10.829  4110  4266 I BluetoothAdapterState: Entering BleOnState
08-31 11:16:10.829  4110  4110 D BluetoothMapService: cleanup()
08-31 11:16:10.829  4110  4110 D BluetoothMapService: MAP Service closeService in
08-31 11:16:10.831  1350  2044 D BluetoothPan: onBluetoothStateChange on: false
,08-31 11:16:10.833   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:16:10.833  4033  4045 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 11:16:10.834  1921  1937 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:16:10.834  4033  4043 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 11:16:10.835  4033  4045 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:16:10.835  1350  1381 D BluetoothMap: onBluetoothStateChange: up=false
,08-31 11:16:10.835  4033  4043 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-31 11:16:10.836  1350  2128 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 11:16:10.836  1350  2045 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-31 11:16:10.837  4033  4045 D BluetoothMap: onBluetoothStateChange: up=false
08-31 11:16:10.837  1350  1372 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 11:16:10.838   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:16:10.838   876   893 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 11:16:10.838   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:16:10.838  1350  2044 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:16:10.838  4033  4043 D BluetoothPan: onBluetoothStateChange on: false
08-31 11:16:10.839  4110  4266 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-31 11:16:10.839  4110  4266 D BluetoothAdapterProperties: Setting state to 16
,08-31 11:16:10.839  4110  4266 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-31 11:16:10.839  4110  4266 D BluetoothAdapterProperties: onBleDisable
08-31 11:16:10.840  4110  4266 I BluetoothAdapterState: Entering PendingCommandState
08-31 11:16:10.840  4110  4267 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-31 11:16:10.841  4110  4278 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-31 11:16:10.841  4110  4278 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 11:16:10.843  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:16:10.844  4110  4270 D BluetoothAdapterProperties: Scan Mode:20
08-31 11:16:10.844  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:10.845  4033  4033 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 11:16:10.845  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:16:10.847  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:16:10.849  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 11:16:10.850  4033  4033 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:16:11.042  4110  4270 I bt_hci  : shut_down
,08-31 11:16:11.052  4110  4274 D bt_hwcfg: hw_epilog_process
,08-31 11:16:11.052  4110  4274 I bt_vendor: low_power_mode_cb
,08-31 11:16:11.079  4110  4274 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-31 11:16:11.079  4110  4274 I bt_vendor: epilog_cb
,08-31 11:16:11.080  4110  4274 I bt_hci  : epilog_finished_callback
,08-31 11:16:11.087  4110  4270 I bt_hci_h4: hal_close
,08-31 11:16:11.089  4110  4270 I bt_userial_vendor: device fd = 51 close
,08-31 11:16:11.215  4110  4267 D bt_stack_manager: event_shut_down_stack finished.
,08-31 11:16:11.216  4110  4266 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-31 11:16:11.222  4110  4110 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 11:16:11.222  4110  4266 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-31 11:16:11.224  4110  4110 D BtGatt.GattService: Received stop request...Stopping profile...
,08-31 11:16:11.224  4110  4110 D BtGatt.GattService: stop()
,08-31 11:16:11.225  4110  4110 D BtGatt.AdvertiseManager: advertise clients cleared
08-31 11:16:11.230  4110  4110 V BluetoothAdapterState: isTurningOff()=false
08-31 11:16:11.230  4110  4110 V BluetoothAdapterState: isTurningOn()=false
08-31 11:16:11.231  4110  4110 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 11:16:11.231  4110  4110 V BluetoothAdapterState: isBleTurningOff()=true
08-31 11:16:11.232  4110  4266 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-31 11:16:11.233  4110  4266 D BluetoothAdapterProperties: Setting state to 10
08-31 11:16:11.233  4110  4266 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-31 11:16:11.235  4110  4266 I BluetoothAdapterState: Entering OffState
08-31 11:16:11.236   876   893 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-31 11:16:11.260  4110  4110 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-31 11:16:11.260  4110  4110 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-31 11:16:11.261  4110  4267 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-31 11:16:11.268  4110  4110 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-31 11:16:11.280  4110  4267 D bt_stack_manager: event_clean_up_stack finished.
,08-31 11:16:11.283  4110  4110 I art     : System.exit called, status: 0
,08-31 11:16:11.284  4110  4110 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-31 11:16:11.328   876  1970 I ActivityManager: Process com.android.bluetooth (pid 4110) has died
,08-31 11:16:12.552   876   896 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-31 11:16:12.561  1867  1867 I Keyboard.Facilitator: onFinishInput()
,08-31 11:16:12.580   876   896 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-31 11:16:12.580   876   896 I Adreno  : Build Date                       : 10/20/15
08-31 11:16:12.580   876   896 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-31 11:16:12.580   876   896 I Adreno  : Local Branch                     : M14
08-31 11:16:12.580   876   896 I Adreno  : Remote Branch                    : 
08-31 11:16:12.580   876   896 I Adreno  : Remote Branch                    : 
08-31 11:16:12.580   876   896 I Adreno  : Reconstruct Branch               : 
,08-31 11:16:12.626   282   691 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (196 us)
,08-31 11:16:13.242  3969  3969 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-31 11:16:13.243  3969  3969 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-31 11:16:13.278   876   896 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-31 11:16:13.281  3969  3969 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@470ec25 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@9289912, 16908290=android.view.AbsSavedState$1@9289912}, android:focusedViewId=100}]}]
,08-31 11:16:13.282  3969  3969 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-31 11:16:13.282  3969  3969 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-31 11:16:13.282  3969  3969 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-31 11:16:13.290   876   896 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-31 11:16:13.293   876   894 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-31 11:16:13.293   282   282 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
08-31 11:16:13.294   282   282 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-31 11:16:13.525   282   339 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-31 11:16:13.527   282   282 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-31 11:16:13.527   876  1331 D SurfaceControl: Excessive delay in setPowerMode(): 234ms
,08-31 11:16:13.540   876   896 I DreamManagerService: Entering dreamland.
,08-31 11:16:13.543   876   891 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-31 11:16:13.544   876   896 I PowerManagerService: Dozing...
,08-31 11:16:13.591   377  1973 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
08-31 11:16:13.592   377  1973 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-31 11:16:13.600   876  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 11:16:13.604   876  1304 E native  : do suspend false
,08-31 11:16:13.615  1908  4315 D NfcService: Discovery configuration equal, not updating.
,08-31 11:16:13.632   876  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 11:16:13.635   876  1304 E native  : do suspend true
,08-31 11:16:13.732   377   377 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-31 11:16:13.732   377   377 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-31 11:16:13.757  3969  4018 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 11:16:13.758  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:16:16.766  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 11:16:16.767  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ad8d8e3 added. We now have 6 listener(s)
08-31 11:16:16.767  3969  4018 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:16:16.773  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 11:16:16.773  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2fbb2e0 added. We now have 7 listener(s)
08-31 11:16:16.773  3969  4018 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:16:16.775  3969  4018 I System.out: IsBluetoothEnabled
,08-31 11:16:16.787  3969  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:16:16.838   876   893 I ActivityManager: Start proc 4323:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-31 11:16:16.966  4323  4323 D AdapterServiceConfig: Adding HeadsetService
,08-31 11:16:16.966  4323  4323 D AdapterServiceConfig: Adding A2dpService
,08-31 11:16:16.966  4323  4323 D AdapterServiceConfig: Adding HidService
,08-31 11:16:16.967  4323  4323 D AdapterServiceConfig: Adding HealthService
,08-31 11:16:16.967  4323  4323 D AdapterServiceConfig: Adding PanService
,08-31 11:16:16.967  4323  4323 D AdapterServiceConfig: Adding GattService
,08-31 11:16:16.967  4323  4323 D AdapterServiceConfig: Adding BluetoothMapService
,08-31 11:16:16.981   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a590788:true
08-31 11:16:16.981  4323  4323 D BluetoothAdapterState: make() - Creating AdapterState
,08-31 11:16:16.986  4323  4323 I bt_bluedroid: init
08-31 11:16:16.987  4323  4335 I BluetoothAdapterState: Entering OffState
,08-31 11:16:16.991  4323  4336 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-31 11:16:16.991  4323  4336 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 11:16:16.991  4323  4336 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-31 11:16:16.991  4323  4336 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-31 11:16:16.993  4323  4323 I bt_bluedroid: get_profile_interface socket
,08-31 11:16:16.995  4323  4323 I bt_bluedroid: get_profile_interface sdp
,08-31 11:16:16.998  4323  4334 I bt_bluedroid: config_hci_snoop_log
,08-31 11:16:16.999  4323  4339 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-31 11:16:16.999   876   893 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
08-31 11:16:17.002  4323  4339 D BluetoothAdapterProperties: Name is: Nexus 6
,08-31 11:16:17.007  4323  4335 D BluetoothAdapterState: Current state: OFF, message: 0
,08-31 11:16:17.007  4323  4335 D BluetoothAdapterProperties: Setting state to 14
08-31 11:16:17.008  4323  4335 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-31 11:16:17.011  4323  4335 D BluetoothBondStateMachine: make
,08-31 11:16:17.017  4323  4340 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-31 11:16:17.024  4323  4335 I BluetoothAdapterState: Entering PendingCommandState
,08-31 11:16:17.025  4323  4323 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-31 11:16:17.028  4323  4323 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@287c81c
,08-31 11:16:17.029  4323  4323 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 11:16:17.029  4323  4323 D BtGatt.GattService: Received start request. Starting profile...
08-31 11:16:17.029  4323  4323 D BtGatt.GattService: start()
,08-31 11:16:17.029  4323  4323 I bt_bluedroid: get_profile_interface gatt
08-31 11:16:17.030  4323  4323 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@287c81c
08-31 11:16:17.030  4323  4323 D BtGatt.AdvertiseManager: advertise manager created
,08-31 11:16:17.042  4323  4323 V BluetoothAdapterState: isTurningOff()=false
,08-31 11:16:17.043  4323  4323 V BluetoothAdapterState: isTurningOn()=false
,08-31 11:16:17.043  4323  4323 V BluetoothAdapterState: isBleTurningOn()=true
,08-31 11:16:17.044  4323  4323 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 11:16:17.047  4323  4335 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-31 11:16:17.048  4323  4335 I bt_bluedroid: enable
08-31 11:16:17.048  4323  4336 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-31 11:16:17.049  4323  4336 I bt_hci  : start_up
,08-31 11:16:17.069  4323  4336 I bt_vendor: alloc value 0xb39dc189
,08-31 11:16:17.070  4323  4336 I bt_vendor: init
08-31 11:16:17.070  4323  4336 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-31 11:16:17.071  4323  4336 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-31 11:16:17.180  4323  4336 D bt_hci  : start_up starting async portion
,08-31 11:16:17.180  4323  4343 I bt_hci  : event_finish_startup
,08-31 11:16:17.181  4323  4343 I bt_hci_h4: hal_open
,08-31 11:16:17.183  4323  4343 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-31 11:16:17.195  4323  4343 I bt_userial_vendor: device fd = 51 open
,08-31 11:16:17.221  4323  4343 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 11:16:17.253  4323  4343 D bt_hwcfg: Chipset BCM4354A2
,08-31 11:16:17.253  4323  4343 D bt_hwcfg: Target name = [BCM4354A2]
08-31 11:16:17.254  4323  4343 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-31 11:16:17.913  4323  4343 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-31 11:16:17.914  4323  4343 D bt_hwcfg: Settlement delay -- 100 ms
08-31 11:16:17.915  4323  4343 I bt_hwcfg: Setting fw settlement delay to 100 
,08-31 11:16:18.031  4323  4343 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 11:16:18.032  4323  4343 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-31 11:16:18.063  4323  4343 I bt_hwcfg: vendor lib fwcfg completed
,08-31 11:16:18.063  4323  4343 I bt_vendor: firmware callback
08-31 11:16:18.063  4323  4343 I bt_hci  : firmware_config_callback
,08-31 11:16:18.074  4323  4345 I bt_btu  : btu_task pending for preload complete event
,08-31 11:16:18.075  4323  4345 I bt_btu_task: Bluetooth chip preload is complete
08-31 11:16:18.075  4323  4345 I bt_btu  : btu_task received preload complete event
,08-31 11:16:18.087  4323  4345 I         : BTE_InitTraceLevels -- TRC_HCI
08-31 11:16:18.088  4323  4345 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-31 11:16:18.088  4323  4345 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-31 11:16:18.088  4323  4345 I         : BTE_InitTraceLevels -- TRC_AVDT
08-31 11:16:18.089  4323  4345 I         : BTE_InitTraceLevels -- TRC_AVRC
08-31 11:16:18.089  4323  4345 I         : BTE_InitTraceLevels -- TRC_A2D
08-31 11:16:18.089  4323  4345 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 11:16:18.089  4323  4345 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 11:16:18.090  4323  4345 I         : BTE_InitTraceLevels -- TRC_GAP
08-31 11:16:18.090  4323  4345 I         : BTE_InitTraceLevels -- TRC_PAN
08-31 11:16:18.090  4323  4345 I         : BTE_InitTraceLevels -- TRC_SDP
,08-31 11:16:18.090  4323  4345 I         : BTE_InitTraceLevels -- TRC_GATT
08-31 11:16:18.091  4323  4345 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 11:16:18.091  4323  4345 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-31 11:16:18.091  4323  4345 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-31 11:16:18.225  4323  4345 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3959d9d
,08-31 11:16:18.226  4323  4345 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3959d9d 
,08-31 11:16:18.239  4323  4339 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-31 11:16:18.242  4323  4339 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-31 11:16:18.243  4323  4339 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-31 11:16:18.246  4323  4339 D BluetoothAdapterProperties: Name is: Nexus 6
,08-31 11:16:18.250  4323  4339 D BluetoothAdapterProperties: Scan Mode:20
,08-31 11:16:18.250  4323  4339 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 11:16:18.251  4323  4339 D bt_hci  : do_postload posting postload work item
,08-31 11:16:18.251  4323  4343 I bt_hci  : event_postload
08-31 11:16:18.251  4323  4343 I bt_vendor: sco_config_cb
08-31 11:16:18.251  4323  4343 I bt_hci  : sco_config_callback postload finished.
08-31 11:16:18.255  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:18.255  4323  4339 D bt_bte_conf: Device ID record 1 : primary
08-31 11:16:18.255  4323  4339 D bt_bte_conf:   vendorId            = 000f
08-31 11:16:18.255  4323  4339 D bt_bte_conf:   vendorIdSource      = 0001
08-31 11:16:18.255  4323  4339 D bt_bte_conf:   product             = 1200
08-31 11:16:18.256  4323  4339 D bt_bte_conf:   version             = 1436
08-31 11:16:18.256  4323  4339 D bt_bte_conf:   clientExecutableURL = 
08-31 11:16:18.256  4323  4339 D bt_bte_conf:   serviceDescription  = 
08-31 11:16:18.256  4323  4339 D bt_bte_conf:   documentationURL    = 
08-31 11:16:18.257  4323  4339 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-31 11:16:18.257  4323  4336 D bt_stack_manager: event_start_up_stack finished
08-31 11:16:18.259  4323  4343 I bt_vendor: low_power_mode_cb
08-31 11:16:18.259  4323  4335 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-31 11:16:18.260  4323  4335 D BluetoothAdapterProperties: Setting state to 15
08-31 11:16:18.260  4323  4335 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-31 11:16:18.263  4323  4335 I BluetoothAdapterState: Entering BleOnState
,08-31 11:16:18.268  4323  4335 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-31 11:16:18.268  4323  4335 D BluetoothAdapterProperties: Setting state to 11
08-31 11:16:18.268  4323  4335 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-31 11:16:18.275  4323  4323 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@287c81c
08-31 11:16:18.276  4323  4323 D HeadsetService: Received start request. Starting profile...
,08-31 11:16:18.280  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:16:18.285  4323  4323 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-31 11:16:18.285  4323  4323 D HeadsetStateMachine: make
,08-31 11:16:18.292  4323  4335 I BluetoothAdapterState: Entering PendingCommandState
,08-31 11:16:18.294  4323  4323 D HeadsetStateMachine: max_hf_connections = 1
,08-31 11:16:18.294  4323  4323 I bt_bluedroid: get_profile_interface handsfree
08-31 11:16:18.295  4323  4339 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-31 11:16:18.295  4323  4339 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-31 11:16:18.298  4323  4323 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@287c81c
08-31 11:16:18.299  4323  4323 D A2dpService: Received start request. Starting profile...
08-31 11:16:18.300  4323  4323 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-31 11:16:18.300  4323  4323 I bt_bluedroid: get_profile_interface avrcp
,08-31 11:16:18.306  4323  4323 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-31 11:16:18.307  4323  4323 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 11:16:18.307  4323  4323 D A2dpStateMachine: make
,08-31 11:16:18.308  4323  4323 I bt_bluedroid: get_profile_interface a2dp
,08-31 11:16:18.309  4323  4339 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-31 11:16:18.311  4323  4323 I BluetoothHidServiceJni: classInitNative: succeeds
,08-31 11:16:18.312  4323  4323 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@287c81c
,08-31 11:16:18.313  4323  4355 D A2dpStateMachine: Enter Disconnected: -2
,08-31 11:16:18.314  4323  4323 D HidService: Received start request. Starting profile...
,08-31 11:16:18.314  4323  4323 I bt_bluedroid: get_profile_interface hidhost
08-31 11:16:18.314  4323  4339 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb393b3e5
08-31 11:16:18.314  4323  4323 D HidService: setHidService(): set to: null
,08-31 11:16:18.314  4323  4339 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-31 11:16:18.318  4323  4323 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-31 11:16:18.318  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 11:16:18.319  4323  4323 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@287c81c
,08-31 11:16:18.319  4323  4323 D HealthService: Received start request. Starting profile...
,08-31 11:16:18.321  4323  4323 I bt_bluedroid: get_profile_interface health
,08-31 11:16:18.322  4323  4323 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-31 11:16:18.323  4323  4323 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@287c81c
,08-31 11:16:18.324  4323  4323 D PanService: Received start request. Starting profile...
,08-31 11:16:18.324  4323  4323 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 11:16:18.324  4323  4323 I bt_bluedroid: get_profile_interface pan
08-31 11:16:18.325  4323  4339 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-31 11:16:18.330  4323  4323 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@287c81c
,08-31 11:16:18.331  4323  4323 D BluetoothMapService: Received start request. Starting profile...
,08-31 11:16:18.332  4323  4323 D BluetoothMapService: start()
,08-31 11:16:18.335  4323  4323 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-31 11:16:18.336  4323  4323 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-31 11:16:18.336  4323  4323 D BluetoothMapAppObserver: createReceiver()
,08-31 11:16:18.338  4323  4323 D BluetoothMapAppObserver: initObservers()
,08-31 11:16:18.338  4323  4323 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-31 11:16:18.351  4323  4323 V BluetoothAdapterState: isTurningOff()=false
08-31 11:16:18.352  4323  4323 V BluetoothAdapterState: isTurningOn()=true
08-31 11:16:18.352  4323  4323 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 11:16:18.352  4323  4323 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 11:16:18.354  4323  4323 V BluetoothAdapterState: isTurningOff()=false
,08-31 11:16:18.354  4323  4323 V BluetoothAdapterState: isTurningOn()=true
08-31 11:16:18.354  4323  4323 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:16:18.354  4323  4323 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 11:16:18.354  4323  4353 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 11:16:18.355  4323  4323 V BluetoothAdapterState: isTurningOff()=false
08-31 11:16:18.355  4323  4323 V BluetoothAdapterState: isTurningOn()=true
08-31 11:16:18.355  4323  4323 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:16:18.355  4323  4323 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 11:16:18.357  4323  4323 V BluetoothAdapterState: isTurningOff()=false
,08-31 11:16:18.357  4323  4323 V BluetoothAdapterState: isTurningOn()=true
,08-31 11:16:18.358  4323  4323 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:16:18.358  4323  4323 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:16:18.358  4323  4323 V BluetoothAdapterState: isTurningOff()=false
,08-31 11:16:18.358  4323  4323 V BluetoothAdapterState: isTurningOn()=true
,08-31 11:16:18.358  4323  4323 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:16:18.358  4323  4323 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:16:18.359  4323  4323 V BluetoothAdapterState: isTurningOff()=false,
08-31 11:16:18.359  4323  4323 V BluetoothAdapterState: isTurningOn()=true
,08-31 11:16:18.359  4323  4323 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 11:16:18.359  4323  4323 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 11:16:18.359  4323  4335 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-31 11:16:18.359  4323  4335 D BluetoothAdapterProperties: ScanMode =  20
,08-31 11:16:18.360  4323  4335 D BluetoothAdapterProperties: State =  11
08-31 11:16:18.362  4323  4339 D BluetoothAdapterProperties: Scan Mode:21
,08-31 11:16:18.362  4323  4335 D BluetoothAdapterProperties: Setting state to 12
08-31 11:16:18.362  4323  4335 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-31 11:16:18.362  4323  4339 D BluetoothAdapterProperties: Discoverable Timeout:120,
08-31 11:16:18.363  4323  4335 I BluetoothAdapterState: Entering OnState
08-31 11:16:18.363  1350  1372 D BluetoothPan: onBluetoothStateChange on: true
,08-31 11:16:18.366   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 11:16:18.366  4033  4043 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 11:16:18.367  1350  1350 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 11:16:18.367  1350  1350 D PanProfile: Bluetooth service connected
,08-31 11:16:18.369  1921  1934 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 11:16:18.369  4033  4045 D BluetoothPbap: onBluetoothStateChange: up=true
,08-31 11:16:18.371  4323  4323 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-31 11:16:18.371  4033  4043 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:16:18.372  4323  4323 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-31 11:16:18.372  1350  1381 D BluetoothMap: onBluetoothStateChange: up=true
08-31 11:16:18.374  4323  4323 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:16:18.374  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:16:18.374  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:18.374  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:16:18.374  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
,08-31 11:16:18.374  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:16:18.374  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:16:18.374  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:16:18.374  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:16:18.376  4033  4312 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-31 11:16:18.378  3969  3969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:16:18.378  4323  4323 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:16:18.378  1350  2128 D BluetoothPbap: onBluetoothStateChange: up=true
,08-31 11:16:18.380  4323  4323 D ObexServerSockets: Succeed to create listening sockets 
,08-31 11:16:18.380  4033  4033 D BluetoothA2dp: Proxy object connected
08-31 11:16:18.380  4323  4323 D ObexServerSockets0: startAccept()
,08-31 11:16:18.380  4323  4323 D ObexServerSockets0: prepareForNewConnect()
08-31 11:16:18.381  1350  2045 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 11:16:18.383  4033  4045 D BluetoothMap: onBluetoothStateChange: up=true
08-31 11:16:18.383  4323  4323 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-31 11:16:18.383  4323  4323 D BluetoothSdpJni: SDP Create record success - handle: 0
08-31 11:16:18.384  4323  4360 D ObexServerSockets0: Accepting socket connection...
08-31 11:16:18.385  4323  4361 D ObexServerSockets0: Accepting socket connection...
,08-31 11:16:18.385  1350  1372 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 11:16:18.387  1350  1350 D BluetoothMap: Proxy object connected
08-31 11:16:18.387  1350  1350 D MapProfile: Bluetooth service connected
08-31 11:16:18.387  1350  1350 D BluetoothMap: getConnectedDevices()
08-31 11:16:18.388  4033  4033 D BluetoothMap: Proxy object connected
08-31 11:16:18.388  4033  4033 D MapProfile: Bluetooth service connected
08-31 11:16:18.388  4033  4033 D BluetoothMap: getConnectedDevices()
,08-31 11:16:18.389   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:16:18.389   876   893 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 11:16:18.389  1350  1350 D BluetoothInputDevice: Proxy object connected
08-31 11:16:18.389  1350  1350 D HidProfile: Bluetooth service connected
08-31 11:16:18.389   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 11:16:18.389  4033  4033 D BluetoothInputDevice: Proxy object connected
08-31 11:16:18.389   876   876 D BluetoothA2dp: Proxy object connected
08-31 11:16:18.389  4033  4033 D HidProfile: Bluetooth service connected
08-31 11:16:18.390  1350  2044 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:16:18.390  4033  4045 D BluetoothPan: onBluetoothStateChange on: true
08-31 11:16:18.391  1350  1350 D BluetoothA2dp: Proxy object connected
,08-31 11:16:18.392  4033  4033 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 11:16:18.392  4033  4033 D PanProfile: Bluetooth service connected
,08-31 11:16:18.394   876   876 I Telecom : BluetoothPhoneService: queryPhoneState
08-31 11:16:18.394  4323  4323 D BluetoothMapService: onReceive
,08-31 11:16:18.395  4323  4323 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:16:18.395  4323  4323 D BluetoothMapService: STATE_ON
,08-31 11:16:18.397  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:16:18.400  4033  4033 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 11:16:18.406  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 11:16:18.406  4033  4033 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:16:18.414  4033  4033 D BluetoothPbap: Proxy object connected
,08-31 11:16:18.414  4033  4033 D PbapServerProfile: Bluetooth service connected
,08-31 11:16:18.418  1350  1350 D BluetoothPbap: Proxy object connected
,08-31 11:16:18.418  1350  1350 D PbapServerProfile: Bluetooth service connected
,08-31 11:16:18.420  4323  4323 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-31 11:16:18.421  4323  4323 D ObexServerSockets0: prepareForNewConnect()
,08-31 11:16:18.422  4323  4367 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 11:16:18.437  4323  4371 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 11:16:18.438  4323  4371 I BtOppRfcommListener: Accept thread started.
,08-31 11:16:18.468   876   876 D BluetoothHeadset: Proxy object connected
08-31 11:16:18.468   876   876 D BluetoothHeadset: Proxy object connected
,08-31 11:16:18.468  1350  1372 D BluetoothHeadset: Proxy object connected
,08-31 11:16:18.468  1350  1350 D HeadsetProfile: Bluetooth service connected
,08-31 11:16:18.469   876   876 D BluetoothHeadset: Proxy object connected
08-31 11:16:18.469  4033  4045 D BluetoothHeadset: Proxy object connected
08-31 11:16:18.469  1921  2125 D BluetoothHeadset: Proxy object connected
08-31 11:16:18.470  4033  4033 D HeadsetProfile: Bluetooth service connected
,08-31 11:16:18.470  1921  1937 D BluetoothHeadset: Proxy object connected
08-31 11:16:18.472  4033  4312 D BluetoothHeadset: Proxy object connected
,08-31 11:16:18.472  4033  4033 D HeadsetProfile: Bluetooth service connected
,08-31 11:16:18.489   876   893 D BluetoothHeadset: Proxy object connected
08-31 11:16:18.489   876   893 D BluetoothHeadset: Proxy object connected
08-31 11:16:18.489  1350  2044 D BluetoothHeadset: Proxy object connected
08-31 11:16:18.489  1350  1350 D HeadsetProfile: Bluetooth service connected
,08-31 11:16:18.810  3969  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:16:18.810  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:18.810  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:16:18.810  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:16:18.810  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:16:18.810  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:16:18.810  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:16:18.810  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:16:18.817  3969  4018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:16:18.820  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 11:16:18.821  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@eeb9999 added. We now have 8 listener(s)
08-31 11:16:18.821  3969  4018 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:16:18.827   876  1939 D WifiService: setWifiEnabled: false pid=3969, uid=10000
,08-31 11:16:18.827   876  1939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 11:16:18.840  3969  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:16:18.841   876  1390 D WifiService: setWifiEnabled: true pid=3969, uid=10000
08-31 11:16:18.841   876  1390 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 11:16:18.865   876  1304 D WifiConfigStore: Loading config and enabling all networks 
,08-31 11:16:18.873  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:16:18.873  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:18.873  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:16:18.873  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:16:18.873  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:16:18.873  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:16:18.873  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:16:18.873  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:16:18.880  3969  3969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:16:18.881   876  1304 D WifiConfigStore: loaded 0 passpoint configs
,08-31 11:16:18.882   876  1304 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-31 11:16:18.883   876  1304 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-31 11:16:18.884   876  1304 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-31 11:16:18.884   876  1304 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-31 11:16:18.884   876  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-31 11:16:18.885   876  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-31 11:16:18.900   373   874 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-31 11:16:18.901   876  1304 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.18 rxSuccessRate=0.26 delta 1000 -> 1000
,08-31 11:16:18.902   373   874 D CommandListener: Setting iface cfg
,08-31 11:16:18.903   876  1304 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-31 11:16:18.905   876  1303 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '181 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 181 Failed to set address (No such device)'
,08-31 11:16:18.905   876  1303 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-31 11:16:18.955   876  1304 E native  : do suspend true
,08-31 11:16:18.972   876  1303 D WifiNative-HAL: p2pGetDeviceAddress
,08-31 11:16:18.976   876  1303 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-31 11:16:18.978   876  1304 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-31 11:16:18.979   876  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 11:16:18.988   876  1304 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-31 11:16:19.056   876  1304 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-31 11:16:19.062  1469  1469 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-31 11:16:19.501  1469  1469 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-31 11:16:19.549  1469  1469 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-31 11:16:19.552  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-31 11:16:19.561   876  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 11:16:19.581   876  1304 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{103}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-31 11:16:19.582   876  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 11:16:19.583   876  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 103] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-31 11:16:19.609   876  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 11:16:19.631   373   874 D CommandListener: Setting iface cfg
,08-31 11:16:19.632   876  1304 D WifiStateMachine: Start Dhcp Watchdog 4
,08-31 11:16:19.647   876  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-31 11:16:19.660   876  4379 D DhcpClient: Receive thread started
,08-31 11:16:19.747   876  1304 E native  : do suspend false
,08-31 11:16:19.770   876  2085 D DhcpClient: Broadcasting DHCPDISCOVER
,08-31 11:16:19.791   876  4379 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-31 11:16:19.793   876  2085 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-31 11:16:19.796   876  2085 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-31 11:16:19.814   876  4379 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-31 11:16:19.815   876  2085 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-31 11:16:19.820   373   874 D CommandListener: Setting iface cfg
,08-31 11:16:19.832   876  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-31 11:16:19.834   876  2085 D DhcpClient: Scheduling renewal in 86399s
,08-31 11:16:19.835   876  1304 E native  : do suspend true
,08-31 11:16:19.853   876  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-31 11:16:19.854   876  1304 D WifiConfigStore: No blacklist allowed without epno enabled
,08-31 11:16:19.855   876  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 103] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-31 11:16:19.856   876  1304 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-31 11:16:19.864   876  1306 D ConnectivityService: Adding iface wlan0 to network 103
08-31 11:16:19.873  3969  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:16:19.873  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:19.873  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:16:19.873  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:16:19.873  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:16:19.873  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:16:19.873  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:16:19.873  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:16:19.878  3969  4018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:16:19.883  3969  4018 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-31 11:16:19.884  3969  4018 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-31 11:16:19.886  3969  4018 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@470ec25 Bundle[{}]
,08-31 11:16:19.887  3969  4018 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-31 11:16:19.887  3969  4018 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-31 11:16:19.888  3969  4018 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-31 11:16:19.889  3969  4018 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-31 11:16:19.889  3969  4018 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-31 11:16:19.890  3969  4018 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-31 11:16:19.895  3969  4018 I System.out: Running OutgoingSocketThread
,08-31 11:16:19.896  3969  4382 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 447)
,08-31 11:16:19.897  3969  4382 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47797
,08-31 11:16:19.897  3969  4382 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-31 11:16:19.909   876  1306 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-31 11:16:19.909   876  1306 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 103
,08-31 11:16:19.910   876  1306 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 103
,08-31 11:16:19.912   876  1306 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 103
,08-31 11:16:19.913   876  1306 D ConnectivityService: Setting Dns servers for network 103 to [/192.168.1.1]
,08-31 11:16:19.922   876  1306 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,08-31 11:16:19.929   876  1306 D ConnectivityService: scheduleUnvalidatedPrompt 103
,08-31 11:16:19.929   876  1306 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 103]
,08-31 11:16:19.929   876  1306 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 103]
08-31 11:16:19.929   876  1304 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-31 11:16:19.930   876  1306 D ConnectivityService:    accepting network in place of null
,08-31 11:16:19.930   876  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-31 11:16:19.933   876  1306 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{103}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-31 11:16:19.962   373   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 11:16:20.040   373   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 11:16:20.050   876  1306 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 103] isDefaultNetwork=true
,08-31 11:16:20.050   876  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:16:20.058   876  1306 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 103]
,08-31 11:16:20.062   876   893 D Tethering: MasterInitialState.processMessage what=3
,08-31 11:16:20.079  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:16:20.079  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:20.079  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:16:20.079  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:16:20.079  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:16:20.079  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:16:20.079  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:16:20.079  3969  3969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:16:20.082  3969  3969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:16:20.090  1732  1732 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-31 11:16:20.095  1732  1732 D SystemUpdateService: onCreate
,08-31 11:16:20.098  1732  1732 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-31 11:16:20.112  1732  4389 I SystemUpdateService: active receiver: enabled
,08-31 11:16:20.115  1732  1732 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-31 11:16:20.120  1732  2532 I iu.UploadsManager: num queued entries: 0
,08-31 11:16:20.121  1732  4389 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-31 11:16:20.123  1732  1732 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-31 11:16:20.124  1732  1732 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-31 11:16:20.126  4125  4125 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:16:20.131  1732  4392 I MDM     : [187] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-31 11:16:20.131  1732  4392 W BaseAppContext: Using Auth Proxy for data requests.
,08-31 11:16:20.131  4125  4125 D SprintDMHelper: simOperator: 
,08-31 11:16:20.131  4125  4125 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-31 11:16:20.132  1732  4392 V GoogleAuthProtoRequest: [187] a.<init>: mAccountName set to: thalitester@gmail.com
08-31 11:16:20.133  1732  2532 I iu.UploadsManager: num updated entries: 0
08-31 11:16:20.136  1732  4389 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-31 11:16:20.136  1732  4389 I SystemUpdateService: now status is 0 (complete)
08-31 11:16:20.137  1732  4389 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-31 11:16:20.137  1732  4389 I SystemUpdateService: file has been verified
08-31 11:16:20.137  1732  4389 I SystemUpdateService: OTA package size = 12249756
,08-31 11:16:20.145  1732  2532 I iu.SyncManager: NEXT; no task
,08-31 11:16:20.151  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 11:16:20.153  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 11:16:20.157  1732  4389 I SystemUpdateService: showing system update notification
,08-31 11:16:20.187  1732  1732 D SystemUpdateService: onDestroy
,08-31 11:16:20.203  1502  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-31 11:16:20.203  1502  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-31 11:16:20.203  1502  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 11:16:20.203  1502  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 11:16:20.229  1732  4392 E MDM     : [187] SitrepService.a: Error sending sitrep.
,08-31 11:16:20.898  3969  4018 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 448)
08-31 11:16:20.898  3969  4018 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 448)
,08-31 11:16:20.908  3969  4018 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 453)
,08-31 11:16:20.910  3969  4018 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-31 11:16:20.910  3969  4018 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 454)
,08-31 11:16:20.916  3969  4018 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:16:20.916  3969  4018 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@873345e added. We now have 2 listener(s)
,08-31 11:16:20.918  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 11:16:20.918  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 11:16:20.918  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:16:20.918  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 11:16:20.918  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b6203f added. We now have 9 listener(s)
08-31 11:16:20.919  3969  4018 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:16:20.919  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 11:16:20.923  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:16:20.931  3969  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:16:20.931  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:20.931  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:16:20.931  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:16:20.931  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:16:20.931  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:16:20.931  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:16:20.931  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:16:20.935  3969  4018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:16:20.935  3969  4018 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 11:16:20.935  3969  4018 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 11:16:20.935  3969  4018 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cd33655 added. We now have 3 listener(s)
,08-31 11:16:20.937  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 11:16:20.937  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 11:16:20.937  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 11:16:20.938  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 11:16:20.938  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3a386a added. We now have 10 listener(s)
08-31 11:16:20.938  3969  4018 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-31 11:16:20.938  3969  4018 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 11:16:20.938  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 11:16:20.938  3969  4018 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:16:20.938  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:16:20.938  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:20.939  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:16:20.939  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:16:20.939  3969  4018 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@873345e removed from the list
08-31 11:16:20.939  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:20.939  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b6203f removed from the list
08-31 11:16:20.940  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:20.941  3969  4018 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:16:20.941  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:20.941  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:20.941  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:20.951  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:16:20.951  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:16:20.951  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:20.951  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b6203f not in the list
08-31 11:16:20.952  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:20.952  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:20.952  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:20.953  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:16:20.953  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:16:20.953  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:20.954  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3a386a removed from the list
08-31 11:16:20.954  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:16:20.954  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:20.954  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:20.954  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:16:20.954  3969  4018 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cd33655 rem,oved from the list
08-31 11:16:20.955  3969  4018 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:16:20.955  3969  4018 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f6815b added. We now have 2 listener(s)
08-31 11:16:20.957  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 11:16:20.957  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:16:20.957  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:16:20.957  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:16:20.957  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc0fdf8 added. We now have 9 listener(s)
08-31 11:16:20.957  3969  4018 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:16:20.958  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 11:16:20.961  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:16:20.966  3969  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:16:20.966  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:20.966  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:16:20.966  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:16:20.966  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:16:20.966  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:16:20.966  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:16:20.966  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:16:20.969  3969  4018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:16:20.969  3969  4018 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:16:20.970  3969  4018 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:16:20.971  3969  4018 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5bb7136 added. We now have 3 listener(s)
08-31 11:16:20.972  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:20.974  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 11:16:20.974  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:16:20.974  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:16:20.975  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:16:20.975  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@311d837 added. We now have 10 listener(s)
08-31 11:16:20.975  3969  4018 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:16:20.975  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:16:20.975  3969  4018 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:16:20.975  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:16:20.975  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:16:20.975  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 11:16:20.978  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:20.982  3969  4018 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-31 11:16:20.983  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 11:16:20.992  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 11:16:20.993  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-31 11:16:20.993  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 11:16:20.998  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-31 11:16:20.998  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 11:16:20.998  3969  4018 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-31 11:16:20.999  3969  4018 D BluetoothAdapter: STATE_ON
08-31 11:16:21.004  4323  4363 D BtGatt.GattService: registerClient() - UUID=17dc4aeb-dae2-4f60-9803-752e3ec4efed
08-31 11:16:21.006  4323  4339 D BtGatt.GattService: onClientRegistered() - UUID=17dc4aeb-dae2-4f60-9803-752e3ec4efed, clientIf=5
08-31 11:16:21.006  3969  3979 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-31 11:16:21.008  4323  4362 D BtGatt.GattService: start scan with filters
08-31 11:16:21.012  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 11:16:21.012  4323  4342 D BtGatt.ScanManager: handling starting scan
08-31 11:16:21.012  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 11:16:21.013  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 11:16:21.013  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-31 11:16:21.015  4323  4342 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@287c81c
08-31 11:16:21.020  4323  4339 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-31 11:16:21.020  4323  4339 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:16:21.021  4323  4342 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-31 11:16:21.024  3969  4018 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 11:16:21.024  3969  4018 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 11:16:21.024  3969  3969 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 11:16:21.028  4323  4339 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-31 11:16:21.028  4323  4339 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:16:21.028  4323  4342 D BtGatt.ScanManager: Starting BLE batch scan
08-31 11:16:21.028  4323  4342 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-31 11:16:21.030  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 11:16:21.040  3969  4018 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-31 11:16:21.041  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 11:16:21.042  3969  4018 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything,
,08-31 11:16:21.042  4323  4339 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-31 11:16:21.042  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:21.042  4323  4339 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:16:21.042  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-31 11:16:21.043  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 11:16:21.043  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 11:16:21.043  3969  4018 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-31 11:16:21.044  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-31 11:16:21.045  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 11:16:21.045  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-31 11:16:21.047   876  1306 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 102] cleared because we found a replacement network
,08-31 11:16:21.048  3969  4018 D BluetoothAdapter: STATE_ON
08-31 11:16:21.048  4323  4363 D BtGatt.GattService: stopScan() - queue size =1
08-31 11:16:21.050  4323  4362 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-31 11:16:21.050  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:16:21.050  4323  4339 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-31 11:16:21.051  4323  4339 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:16:21.051  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-31 11:16:21.051  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-31 11:16:21.051  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-31 11:16:21.051  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 11:16:21.052  3969  4018 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:16:21.052  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 11:16:21.052  3969  4018 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 11:16:21.052  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 11:16:21.053  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:16:21.054  3969  3969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:16:21.055  3969  3969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-31 11:16:21.055  3969  3969 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:16:21.057  3969  4018 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:16:21.057  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:16:21.057  3969  4018 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:16:21.057  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:16:21.057  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:21.057  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:16:21.057  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:16:21.057  3969  4018 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f6815b removed from the list
,08-31 11:16:21.057  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:21.058  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc0fdf8 removed from the list
08-31 11:16:21.058  3969  4018 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:16:21.058  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:21.058  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:21.058  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:21.059  4323  4339 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-31 11:16:21.059  4323  4339 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:16:21.059  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:16:21.059  4323  4342 D BtGatt.ScanManager: stopping BLe Batch
08-31 11:16:21.059  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:16:21.060  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:21.060  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc0fdf8 not in the list
08-31 11:16:21.060  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:21.060  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:16:21.061  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:16:21.061  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:16:21.061  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:21.061  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@311d837 removed from the list
08-31 11:16:21.061  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:16:21.061  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:21.061  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:16:21.061  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:16:21.062  3969  4018 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5bb7136 removed from the list
08-31 11:16:21.062  3969  4018 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:16:21.062  3969  4018 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@821c0d3 added. We now have 2 listener(s)
08-31 11:16:21.065  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 11:16:21.065  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:16:21.065  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:16:21.065  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:16:21.065  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5519410 added. We now have 9 listener(s)
08-31 11:16:21.065  3969  4018 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:16:21.066  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 11:16:21.066  4323  4339 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-31 11:16:21.066  4323  4339 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:16:21.067  4323  4342 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-31 11:16:21.068  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:16:21.073  4323  4339 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-31 11:16:21.073  4323  4339 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:16:21.073  3969  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:16:21.073  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:21.073  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:16:21.073  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:16:21.073  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:16:21.073  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:16:21.073  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:16:21.073  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:16:21.075  3969  4018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:16:21.075  3969  4018 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:16:21.075  3969  4018 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:16:21.076  3969  4018 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@783710e added. We now have 3 listener(s)
,08-31 11:16:21.077  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:21.078  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 11:16:21.078  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:16:21.078  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:16:21.078  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 11:16:21.078  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3d972f added. We now have 10 listener(s)
08-31 11:16:21.078  3969  4018 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:16:21.079  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:16:21.079  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:16:21.079  3969  4018 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-31 11:16:21.080  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:16:21.080  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:16:21.080  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 11:16:21.080  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:16:21.083  3969  4018 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-31 11:16:21.083  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 11:16:21.086  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 11:16:21.087  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-31 11:16:21.087  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 11:16:21.090  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 11:16:21.090  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 11:16:21.090  3969  4018 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-31 11:16:21.091  3969  4018 D BluetoothAdapter: STATE_ON
,08-31 11:16:21.093  4323  4363 D BtGatt.GattService: registerClient() - UUID=635e2b2e-243b-4c37-8e94-ef3fb88f6024
,08-31 11:16:21.093  4323  4339 D BtGatt.GattService: onClientRegistered() - UUID=635e2b2e-243b-4c37-8e94-ef3fb88f6024, clientIf=5
08-31 11:16:21.093  3969  3979 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-31 11:16:21.094  4323  4333 D BtGatt.GattService: start scan with filters
,08-31 11:16:21.096  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 11:16:21.096  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-31 11:16:21.096  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 11:16:21.096  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-31 11:16:21.096  4323  4342 D BtGatt.ScanManager: handling starting scan
,08-31 11:16:21.101  3969  4018 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 11:16:21.101  3969  3969 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 11:16:21.101  3969  4018 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 11:16:21.103  4323  4339 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-31 11:16:21.103  4323  4339 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:16:21.103  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-31 11:16:21.103  4323  4342 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-31 11:16:21.106  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-31 11:16:21.106  3969  4018 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-31 11:16:21.107  3969  4018 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:16:21.107  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 11:16:21.107  3969  4018 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:16:21.107  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:16:21.107  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:21.107  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-31 11:16:21.107  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:16:21.107  3969  4018 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@821c0d3 removed from the list
08-31 11:16:21.107  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:21.107  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5519410 removed from the list
08-31 11:16:21.108  3969  4018 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:16:21.108  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:16:21.108  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:16:21.109  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-31 11:16:21.109  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:21.109  4323  4339 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-31 11:16:21.109  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:16:21.109  4323  4339 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:16:21.109  4323  4342 D BtGatt.ScanManager: Starting BLE batch scan
08-31 11:16:21.109  4323  4342 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-31 11:16:21.110  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:16:21.110  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 11:16:21.110  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:21.110  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5519410 not in the list
08-31 11:16:21.110  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 11:16:21.110  3969  4018 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 11:16:21.111  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 11:16:21.111  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 11:16:21.111  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-31 11:16:21.111  3969  4018 D BluetoothAdapter: STATE_ON
,08-31 11:16:21.112  4323  4333 D BtGatt.GattService: stopScan() - queue size =1
08-31 11:16:21.113  4323  4352 D BtGatt.GattService: unregisterClient() - clientIf=5
08-31 11:16:21.113  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:16:21.113  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 11:16:21.113  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 11:16:21.113  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 11:16:21.113  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 11:16:21.115  3969  4018 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 11:16:21.115  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 11:16:21.115  3969  4018 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 11:16:21.115  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 11:16:21.115  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:16:21.116  3969  3969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:16:21.117  3969  3969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-31 11:16:21.117  3969  3969 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:16:21.117  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:16:21.117  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 11:16:21.117  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:21.117  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3d972f removed from the list
08-31 11:16:21.117  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:16:21.117  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:21.117  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:16:21.117  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:16:21.118  3969  4018 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@783710e removed from the list
08-31 11:16:21.118  3969  4018 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:16:21.118  3969  4018 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@396774b added. We now have 2 listener(s)
,08-31 11:16:21.120  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 11:16:21.121  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 11:16:21.121  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:16:21.121  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:16:21.121  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e6bd528 added. We now have 9 listener(s)
08-31 11:16:21.121  4323  4339 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-31 11:16:21.121  4323  4339 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:16:21.121  3969  4018 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:16:21.122  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 11:16:21.124  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:16:21.128  4323  4339 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-31 11:16:21.128  4323  4339 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:16:21.129  3969  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:16:21.129  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:21.129  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:16:21.129  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:16:21.129  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:16:21.129  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:16:21.129  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:16:21.129  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:16:21.132  3969  4018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:16:21.132  3969  4018 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 11:16:21.134  3969  4018 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:16:21.134  3969  4018 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fa093e6 added. We now have 3 listener(s)
,08-31 11:16:21.136  4323  4339 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-31 11:16:21.136  4323  4339 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:16:21.136  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 11:16:21.136  4323  4342 D BtGatt.ScanManager: stopping BLe Batch
08-31 11:16:21.136  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:16:21.136  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:16:21.136  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:16:21.136  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:16:21.136  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e533d27 added. We now have 10 listener(s)
,08-31 11:16:21.137  3969  4018 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:16:21.137  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:16:21.137  3969  4018 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-31 11:16:21.137  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:16:21.137  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:16:21.137  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 11:16:21.141  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:21.142  3969  4018 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-31 11:16:21.142  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 11:16:21.142  4323  4339 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-31 11:16:21.142  4323  4339 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:16:21.143  4323  4342 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-31 11:16:21.145  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 11:16:21.145  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-31 11:16:21.146  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 11:16:21.148  4323  4339 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-31 11:16:21.148  4323  4339 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:16:21.149  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-31 11:16:21.149  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 11:16:21.149  3969  4018 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-31 11:16:21.150  3969  4018 D BluetoothAdapter: STATE_ON
,08-31 11:16:21.151  4323  4333 D BtGatt.GattService: registerClient() - UUID=433b0c6e-c5ca-430d-92b1-c9ed7a352476
,08-31 11:16:21.151  4323  4339 D BtGatt.GattService: onClientRegistered() - UUID=433b0c6e-c5ca-430d-92b1-c9ed7a352476, clientIf=5
08-31 11:16:21.152  3969  3980 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-31 11:16:21.152  4323  4352 D BtGatt.GattService: start scan with filters
,08-31 11:16:21.154  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-31 11:16:21.154  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 11:16:21.154  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 11:16:21.154  4323  4342 D BtGatt.ScanManager: handling starting scan
08-31 11:16:21.154  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 11:16:21.156  3969  4018 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 11:16:21.157  3969  4018 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 11:16:21.157  3969  3969 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 11:16:21.158  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 11:16:21.160  4323  4339 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-31 11:16:21.160  4323  4339 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:16:21.160  4323  4342 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-31 11:16:21.163  3969  4018 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:16:21.163  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:16:21.163  3969  4018 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:16:21.163  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 11:16:21.163  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:16:21.163  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-31 11:16:21.163  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-31 11:16:21.163  3969  4018 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@396774b removed from the list
,08-31 11:16:21.163  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:21.163  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e6bd528 removed from the list
08-31 11:16:21.163  3969  4018 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 11:16:21.163  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:16:21.164  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed,
,08-31 11:16:21.164  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-31 11:16:21.164  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:16:21.164  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:16:21.165  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 11:16:21.165  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 11:16:21.165  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:16:21.165  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e6bd528 not in the list,
,08-31 11:16:21.165  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 11:16:21.165  3969  4018 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-31 11:16:21.165  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-31 11:16:21.165  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-31 11:16:21.165  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
,08-31 11:16:21.166  3969  4018 D BluetoothAdapter: STATE_ON
08-31 11:16:21.166  4323  4339 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-31 11:16:21.166  4323  4339 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:16:21.166  4323  4363 D BtGatt.GattService: stopScan() - queue size =1,
,08-31 11:16:21.166  4323  4342 D BtGatt.ScanManager: Starting BLE batch scan
,08-31 11:16:21.166  4323  4342 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-31 11:16:21.168  4323  4333 D BtGatt.GattService: unregisterClient() - clientIf=5
08-31 11:16:21.168  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-31 11:16:21.168  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 11:16:21.168  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-31 11:16:21.168  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-31 11:16:21.168  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 11:16:21.169  3969  4018 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:16:21.169  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 11:16:21.169  3969  4018 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 11:16:21.169  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 11:16:21.170  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:21.170  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:16:21.171  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 11:16:21.171  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:21.171  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e533d27 removed from the list
08-31 11:16:21.171  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:16:21.171  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:21.171  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:16:21.171  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:16:21.171  3969  4018 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fa093e6 removed from the list
08-31 11:16:21.171  3969  3969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:16:21.171  3969  3969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:16:21.171  3969  3969 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:16:21.172  3969  4018 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 11:16:21.172  3969  4018 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@62c84c3 added. We now have 2 listener(s)
08-31 11:16:21.173  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 11:16:21.173  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:16:21.173  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:16:21.173  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 11:16:21.173  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33a2140 added. We now have 9 listener(s)
08-31 11:16:21.174  3969  4018 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:16:21.174  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 11:16:21.176  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:16:21.178  4323  4339 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-31 11:16:21.178  4323  4339 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:16:21.183  3969  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:16:21.183  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:21.183  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:16:21.183  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:16:21.183  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:16:21.183  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:16:21.183  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:16:21.183  3969  4018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:16:21.186  3969  4018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:16:21.186  3969  4018 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:16:21.186  3969  4018 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:16:21.186  3969  4018 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93439be added. We now have 3 listener(s)
08-31 11:16:21.188  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 11:16:21.189  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 11:16:21.189  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:16:21.189  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:21.189  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:16:21.189  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc8aa1f added. We now have 10 listener(s)
08-31 11:16:21.189  3969  4018 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:16:21.190  3969  4018 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:16:21.190  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:16:21.190  3969  4018 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:16:21.190  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:16:21.190  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:21.190  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:16:21.191  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:16:21.191  3969  4018 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@62c84c3 removed from the list
08-31 11:16:21.191  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:21.191  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33a2140 removed from the list
08-31 11:16:21.191  3969  3969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:21.191  3969  4018 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:16:21.191  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:21.192  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:21.192  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:21.193  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:16:21.193  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:16:21.193  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:21.193  3969  4018 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33a2140 not in the list
08-31 11:16:21.193  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:21.193  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:21.194  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:16:21.194  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:16:21.194  3969  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryMana,ger: dispose
08-31 11:16:21.194  3969  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc8aa1f removed from the list
08-31 11:16:21.194  3969  4018 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:16:21.194  4323  4339 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-31 11:16:21.194  3969  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:21.194  4323  4339 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:16:21.194  3969  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:21.194  3969  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:16:21.195  3969  4018 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93439be removed from the list
08-31 11:16:21.196  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-31 11:16:21.196  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-31 11:16:21.196  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-31 11:16:21.197  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:16:21.197  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-31 11:16:21.197  3969  4018 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 11:16:21.201  4323  4339 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-31 11:16:21.201  4323  4339 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:16:21.201  4323  4342 D BtGatt.ScanManager: stopping BLe Batch
08-31 11:16:21.204  3969  4398 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 461, name: My test thread name)
08-31 11:16:21.204  3969  4398 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 461, thread name: My test thread name)
08-31 11:16:21.204  3969  4398 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 461, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-31 11:16:21.207  3969  4399 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 463, name: My test thread name)
08-31 11:16:21.207  3969  4399 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 463, thread name: My test thread name)
08-31 11:16:21.207  3969  4399 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 463, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-31 11:16:21.207  4323  4339 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-31 11:16:21.208  4323  4339 D Bt,Gatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:16:21.208  4323  4342 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-31 11:16:21.209  3969  4018 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-31 11:16:21.209  3969  4018 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-31 11:16:21.209  3969  4018 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-31 11:16:21.209  3969  4018 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-31 11:16:21.209  3969  4018 D com.test.thalitest.ThaliTestRunner: Total duration: 22773 ms
08-31 11:16:21.211  3969  4018 I jxcore-log: Total number of executed tests:  80
08-31 11:16:21.211  3969  4018 I jxcore-log: 
08-31 11:16:21.211  3969  4018 I jxcore-log: Number of passed tests:  80
08-31 11:16:21.211  3969  4018 I jxcore-log: 
08-31 11:16:21.211  3969  4018 I jxcore-log: Number of failed tests:  0
08-31 11:16:21.211  3969  4018 I jxcore-log: 
08-31 11:16:21.212  3969  4018 I jxcore-log: Number of ignored tests:  0
08-31 11:16:21.212  3969  4018 I jxcore-log: 
08-31 11:16:21.212  3969  4018 I jxcore-log: Total duration:  22773
08-31 11:16:21.212  3969  4018 I jxcore-log: 
08-31 11:16:21.213  4323  4339 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-31 11:16:21.213  4323  4339 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:16:21.214  3969  4018 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-31 11:16:21.214  3969  4018 I jxcore-log: 
08-31 11:16:21.215  3969  4018 I jxcore-log: My device name is: motorola-Nexus 6
08-31 11:16:21.215  3969  4018 I jxcore-log: 
08-31 11:16:21.217  3969  4018 I jxcore-log: WARN testUtils: myNameCallback not set!
08-31 11:16:21.217  3969  4018 I jxcore-log: 
08-31 11:16:21.221  3969  4018 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:16:21.221  3969  4018 I jxcore-log: 
08-31 11:16:21.222  3969  4018 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:16:21.222  3969  4018 I jxcore-log: 
08-31 11:16:21.223  3969  4018 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:16:21.223  3969  4018 I jxcore-log: 
08-31 11:16:21.225  3969  4018 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:16:21.225  3969  4018 I jxcore-log: 
08-31 11:16:21.228  3969  4018 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:16:21.228  3969  4018 I jxcore-log: 
08-31 11:16:21.231  3969  4018 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:16:21.231  3969  4018 I jxcore-log: 
08-31 11:16:21.233  3969  4018 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 11:16:21.233  3969  4018 I jxcore-log: 
08-31 11:16:21.233  3969  4018 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 11:16:21.233  3969  4018 I jxcore-log: 
08-31 11:16:21.234  3969  4018 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:16:21.234  3969  4018 I jxcore-log: 
08-31 11:16:21.235  3969  4018 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:16:21.235  3969  4018 I jxcore-log: 
08-31 11:16:21.236  3969  4018 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 11:16:21.236  3969  4018 I jxcore-log: 
08-31 11:16:21.238  3969  4018 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 11:16:21.238  3969  4018 I jxcore-log: 
08-31 11:16:21.239  3969  4018 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 11:16:21.239  3969  4018 I jxcore-log: 
08-31 11:16:21.240  3969  4018 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:16:21.240  3969  4018 I jxcore-log: 
08-31 11:16:21.241  3969  4018 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:16:21.241  3969  4018 I jxcore-log: 
08-31 11:16:21.242  3969  4018 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:16:21.242  3969  4018 I jxcore-log: 
08-31 11:16:21.243  3969  4018 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:16:21.243  3969  4018 I jxcore-log: 
08-31 11:16:21.243  3969  4018 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 11:16:21.243  3969  4018 I jxcore-log: 
08-31 11:16:21.244  3969  4018 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 11:16:21.244  3969  4018 I jxcore-log: 
08-31 11:16:21.245  3969  4018 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:16:21.245  3969  4018 I jxcore-log: 
08-31 11:16:21.246  3969  4018 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:16:21.246  3969  4018 I jxcore-log: 
,08-31 11:16:21.247  3969  4018 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 11:16:21.247  3969  4018 I jxcore-log: 
08-31 11:16:21.247  3969  4018 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 11:16:21.247  3969  4018 I jxcore-log: 
08-31 11:16:21.248  3969  4018 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 11:16:21.248  3969  4018 I jxcore-log: 
08-31 11:16:21.249  3969  4018 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 11:16:21.249  3969  4018 I jxcore-log: 
08-31 11:16:21.250  3969  4018 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:16:21.250  3969  4018 I jxcore-log: 
08-31 11:16:21.251  3969  4018 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:16:21.251  3969  4018 I jxcore-log: 
08-31 11:16:21.252  3969  4018 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:16:21.252  3969  4018 I jxcore-log: 
08-31 11:16:21.253  3969  4018 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:16:21.253  3969  4018 I jxcore-log: 
08-31 11:16:21.254  3969  4018 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:16:21.254  3969  4018 I jxcore-log: 
08-31 11:16:21.255  3969  4018 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:16:21.255  3969  4018 I jxcore-log: 
,08-31 11:16:21.556  3969  3969 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 11:16:21.617  3969  3969 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 11:16:21.671  3969  3969 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 11:16:21.946  4401  4401 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-31 11:16:21.951  4401  4401 D AndroidRuntime: CheckJNI is OFF
,08-31 11:16:21.968   876  4378 D NetlinkSocketObserver: NeighborEvent{elapsedMs=159300, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-31 11:16:21.995  4401  4401 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-31 11:16:22.040  4401  4401 I Radio-JNI: register_android_hardware_Radio DONE
,08-31 11:16:22.062  4401  4401 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-31 11:16:22.078   876   889 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-31 11:16:22.079   876   889 I ActivityManager: Killing 3969:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-31 11:16:22.159   876  1673 D GraphicsStats: Buffer count: 2
08-31 11:16:22.159   876  1969 I WindowState: WIN DEATH: Window{fbdcbd1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-31 11:16:22.160   876  1305 D WifiService: Client connection lost with reason: 4
,08-31 11:16:22.202   876   899 W PackageSettings: Skipping PackageSetting{89a1f79 com.example.hello/10273} due to missing metadata
,08-31 11:16:22.231   876   889 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-31 11:16:22.231   876   889 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-31 11:16:22.232   876   889 E ActivityManager: Failure starting process com.test.thalitest
08-31 11:16:22.232   876   889 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-31 11:16:22.232   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-31 11:16:22.232   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-31 11:16:22.232   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-31 11:16:22.232   876   889 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-31 11:16:22.232   876   889 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-31 11:16:22.232   876   889 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-31 11:16:22.232   876   889 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-31 11:16:22.232   876   889 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-31 11:16:22.232   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-31 11:16:22.232   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-31 11:16:22.232   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-31 11:16:22.232   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-31 11:16:22.232   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-31 11:16:22.232   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-31 11:16:22.232   876   889 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:16:22.232   876   889 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:16:22.232   876   889 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 11:16:22.232   876   889 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-31 11:16:22.233   876   889 I ActivityManager:   Force finishing activity ActivityRecord{49073fe u0 com.test.thalitest/.MainActivity t2},
,08-31 11:16:22.235   876   899 I art     : Starting a blocking GC Explicit
,08-31 11:16:22.244   876  1673 W ActivityManager: Spurious death for ProcessRecord{3a8384 0:com.test.thalitest/u0a0}, curProc for 3969: null
,08-31 11:16:22.272   876   899 I art     : Explicit concurrent mark sweep GC freed 13619(964KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 690us total 36.568ms
08-31 11:16:22.294   876   899 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-31 11:16:22.297  4401  4401 I art     : System.exit called, status: 0
08-31 11:16:22.298  4401  4401 I AndroidRuntime: VM exiting with result code 0.
08-31 11:16:22.307   876   899 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-31 11:16:22.338   876   889 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-31 11:16:22.342  4323  4323 D BluetoothMapAppObserver: onReceive
,08-31 11:16:22.342  4323  4323 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-31 11:16:22.347   876  1296 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-31 11:16:22.348  2101  2285 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-31 11:16:22.350  3811  3811 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-31 11:16:22.350  1867  1867 I Keyboard.Facilitator: resetDictionaries() : en_US
08-31 11:16:22.360  1867  4412 I Keyboard.Facilitator.DecoderInitializer: run()
,08-31 11:16:22.363  1867  4412 I Decoder : createOrResetDecoder
,08-31 11:16:22.393   876  1976 I ActivityManager: Start proc 4415:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-31 11:16:22.394  1921  1921 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-31 11:16:22.414  1502  1502 I ConfigService: onCreate
,08-31 11:16:22.423  1502  4427 W FileUtils: Failed to chmod(/data/user/0/com.google.android.gms/databases/config.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,08-31 11:16:22.435  1867  4412 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-31 11:16:22.446  4415  4415 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-31 11:16:22.448   876   876 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-31 11:16:22.461   876  1969 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3969 uid 10000
,08-31 11:16:22.463  1867  1867 I Keyboard.Facilitator: onFinishInput()
,08-31 11:16:22.463  1940  2041 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-31 11:16:22.464   876   888 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-31 11:16:22.464   876   888 E PackageManager: Failed to write settings, restoring backup
08-31 11:16:22.464   876   888 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-31 11:16:22.464   876   888 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-31 11:16:22.464   876   888 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-31 11:16:22.464   876   888 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-31 11:16:22.464   876   888 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-31 11:16:22.464   876   888 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:16:22.464   876   888 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:16:22.464   876   888 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 11:16:22.468   876   889 E DropBoxManagerService: Can't write: system_server_wtf
08-31 11:16:22.468   876   889 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-31 11:16:22.468   876   889 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 11:16:22.468   876   889 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 11:16:22.468   876   889 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 11:16:22.468   876   889 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 11:16:22.468   876   889 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 11:16:22.468   876   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 11:16:22.468   876   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-31 11:16:22.468   876   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-31 11:16:22.468   876   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-31 11:16:22.468   876   889 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 11:16:22.468   876   889 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 11:16:22.468   876   889 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:16:22.468   876   889 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 11:16:22.468   876   889 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-31 11:16:22.468   876   889 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 11:16:22.468   876   889 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 11:16:22.468   876   889 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 11:16:22.468   876   889 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 11:16:22.468   876   889 E DropBoxManagerService: 	... 13 more
,08-31 11:16:22.476  1867  4412 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-31 11:16:22.476   876  1970 I ActivityManager: Start proc 4429:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-31 11:16:22.477  1940  2041 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-31 11:16:22.477  1940  2041 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1940
08-31 11:16:22.477  1940  2041 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 11:16:22.477  1940  2041 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-31 11:16:22.477  1940  2041 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-31 11:16:22.477  1940  2041 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-31 11:16:22.477  1940  2041 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-31 11:16:22.477  1940  2041 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-31 11:16:22.477  1940  2041 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-31 11:16:22.477  1940  2041 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-31 11:16:22.477  1940  2041 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 11:16:22.477  1940  2041 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 11:16:22.477  1940  2041 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:16:22.477  1940  2041 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 11:16:22.479  1867  4412 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-31 11:16:22.479  1867  4412 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-31 11:16:22.481   876  1387 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-31 11:16:22.485  1940  2041 I Process : Sending signal. PID: 1940 SIG: 9
,08-31 11:16:22.485   876  4435 E DropBoxManagerService: Can't write: system_app_crash
08-31 11:16:22.485   876  4435 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-31 11:16:22.485   876  4435 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 11:16:22.485   876  4435 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 11:16:22.485   876  4435 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 11:16:22.485   876  4435 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 11:16:22.485   876  4435 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 11:16:22.485   876  4435 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 11:16:22.485   876  4435 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 11:16:22.485   876  4435 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 11:16:22.485   876  4435 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 11:16:22.485   876  4435 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 11:16:22.485   876  4435 E DropBoxManagerService: 	... 5 more
08-31 11:16:22.490  1867  4412 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-31 11:16:22.490  1867  4412 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-31 11:16:22.493  1867  4412 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-31 11:16:22.493  1867  4412 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-31 11:16:22.495  1867  4412 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-31 11:16:22.495  1867  4412 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-31 11:16:22.495  1867  4412 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-31 11:16:22.500  1867  4412 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-31 11:16:22.500  1867  4412 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-31 11:16:22.501  1867  4412 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-31 11:16:22.523  4415  4415 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-31 11:16:22.529   876  1970 D GraphicsStats: Buffer count: 1
08-31 11:16:22.529   876   886 I WindowState: WIN DEATH: Window{dcb2d52 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-31 11:16:22.535   876  1938 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1940) has died
,08-31 11:16:22.535   876  1938 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-31 11:16:22.536   876  1938 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-31 11:16:22.551   876   889 I ActivityManager: Start proc 4447:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-31 11:16:22.553  4415  4445 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-31 11:16:22.564   876  1387 I ActivityManager: Start proc 4457:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-31 11:16:22.605  4447  4447 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-31 11:16:22.605  4447  4447 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:16:22.605  4447  4447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:16:22.605  4447  4447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 11:16:22.605  4447  4447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 11:16:22.605  4447  4447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 11:16:22.605  4447  4447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 11:16:22.605  4447  4447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 11:16:22.605  4447  4447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 11:16:22.605  4447  4447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 11:16:22.605  4447  4447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 11:16:22.605  4447  4447 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 11:16:22.605  4447  4447 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 11:16:22.605  4447  4447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:16:22.605  4447  4447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 11:16:22.605  4447  4447 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-31 11:16:22.605  4447  4447 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-31 11:16:22.605  4447  4447 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-31 11:16:22.605  4447  4447 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-31 11:16:22.605  4447  4447 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-31 11:16:22.605  4447  4447 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-31 11:16:22.605  4447  4447 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-31 11:16:22.605  4447  4447 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 11:16:22.605  4447  4447 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 11:16:22.605  4447  4447 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:16:22.605  4447  4447 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:16:22.605  4447  4447 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 11:16:22.605  4447  4447 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:16:22.605  4447  4447 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:16:22.605  4447  4447 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 11:16:22.605  4447  4447 D AndroidRuntime: Shutting down VM
,08-31 11:16:22.613  4447  4447 E AndroidRuntime: FATAL EXCEPTION: main
08-31 11:16:22.613  4447  4447 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4447
08-31 11:16:22.613  4447  4447 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:16:22.613  4447  4447 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-31 11:16:22.613  4447  4447 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-31 11:16:22.613  4447  4447 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-31 11:16:22.613  4447  4447 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 11:16:22.613  4447  4447 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 11:16:22.613  4447  4447 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:16:22.613  4447  4447 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:16:22.613  4447  4447 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 11:16:22.613  4447  4447 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:16:22.613  4447  4447 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:16:22.613  4447  4447 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 11:16:22.613  4447  4447 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:16:22.613  4447  4447 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:16:22.613  4447  4447 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 11:16:22.613  4447  4447 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 11:16:22.613  4447  4447 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 11:16:22.613  4447  4447 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 11:16:22.613  4447  4447 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 11:16:22.613  4447  4447 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 11:16:22.613  4447  4447 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 11:16:22.613  4447  4447 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 11:16:22.613  4447  4447 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 11:16:22.613  4447  4447 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 11:16:22.613  4447  4447 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:16:22.613  4447  4447 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 11:16:22.613  4447  4447 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-31 11:16:22.613  4447  4447 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-31 11:16:22.613  4447  4447 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-31 11:16:22.613  4447  4447 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-31 11:16:22.613  4447  4447 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-31 11:16:22.613  4447  4447 E AndroidRuntime: 	... 10 more
,08-31 11:16:22.614   876  3232 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-31 11:16:22.614  4447  4447 I Process : Sending signal. PID: 4447 SIG: 9
,08-31 11:16:22.621   876  4473 E DropBoxManagerService: Can't write: system_app_crash
08-31 11:16:22.621   876  4473 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-31 11:16:22.621   876  4473 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 11:16:22.621   876  4473 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 11:16:22.621   876  4473 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 11:16:22.621   876  4473 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 11:16:22.621   876  4473 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 11:16:22.621   876  4473 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 11:16:22.621   876  4473 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 11:16:22.621   876  4473 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 11:16:22.621   876  4473 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 11:16:22.621   876  4473 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 11:16:22.621   876  4473 E DropBoxManagerService: 	... 5 more
,08-31 11:16:22.629  4457  4457 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-31 11:16:22.633  1732  4472 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-31 11:16:22.634  1732  4472 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-31 11:16:22.645  1732  4472 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-31 11:16:22.645  1732  4472 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-31 11:16:22.646  1502  1502 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-31 11:16:22.646  1502  1502 D AndroidRuntime: Shutting down VM
,08-31 11:16:22.647  1502  1502 E AndroidRuntime: FATAL EXCEPTION: main
08-31 11:16:22.647  1502  1502 E AndroidRuntime: Process: com.google.process.gapps, PID: 1502
08-31 11:16:22.647  1502  1502 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 11:16:22.647  1502  1502 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-31 11:16:22.647  1502  1502 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-31 11:16:22.647  1502  1502 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-31 11:16:22.647  1502  1502 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:16:22.647  1502  1502 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:16:22.647  1502  1502 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 11:16:22.647  1502  1502 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:16:22.647  1502  1502 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:16:22.647  1502  1502 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 11:16:22.647  1502  1502 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 11:16:22.647  1502  1502 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-31 11:16:22.647  1502  1502 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-31 11:16:22.647  1502  1502 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-31 11:16:22.647  1502  1502 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-31 11:16:22.647  1502  1502 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-31 11:16:22.647  1502  1502 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-31 11:16:22.647  1502  1502 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-31 11:16:22.647  1502  1502 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-31 11:16:22.647  1502  1502 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-31 11:16:22.647  1502  1502 E AndroidRuntime: 	... 8 more
,08-31 11:16:22.649  1502  1502 I Process : Sending signal. PID: 1502 SIG: 9
,08-31 11:16:22.651   876  1969 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4447) has died
08-31 11:16:22.651   876  4476 E DropBoxManagerService: Can't write: system_app_crash
08-31 11:16:22.651   876  4476 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-31 11:16:22.651   876  4476 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 11:16:22.651   876  4476 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 11:16:22.651   876  4476 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 11:16:22.651   876  4476 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 11:16:22.651   876  4476 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 11:16:22.651   876  4476 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 11:16:22.651   876  4476 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 11:16:22.651   876  4476 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 11:16:22.651   876  4476 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 11:16:22.651   876  4476 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 11:16:22.651   876  4476 E DropBoxManagerService: 	... 5 more
08-31 11:16:22.651  4415  4443 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-31 11:16:22.651  4415  4443 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:16:22.651  4415  4443 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:16:22.651  4415  4443 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 11:16:22.651  4415  4443 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 11:16:22.651  4415  4443 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 11:16:22.651  4415  4443 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 11:16:22.651  4415  4443 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 11:16:22.651  4415  4443 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 11:16:22.651  4415  4443 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 11:16:22.651  4415  4443 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 11:16:22.651  4415  4443 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 11:16:22.651  4415  4443 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 11:16:22.651  4415  4443 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:16:22.651  4415  4443 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 11:16:22.651  4415  4443 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-31 11:16:22.651  4415  4443 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-31 11:16:22.651  4415  4443 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.,java:1687)
08-31 11:16:22.651  4415  4443 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-31 11:16:22.651  4415  4443 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:16:22.651  4415  4443 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:16:22.651  4415  4443 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 11:16:22.651  4415  4443 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-31 11:16:22.651  4415  4443 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:16:22.651  4415  4443 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:16:22.651  4415  4443 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 11:16:22.651  4415  4443 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 11:16:22.651  4415  4443 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 11:16:22.651  4415  4443 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 11:16:22.651  4415  4443 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 11:16:22.651  4415  4443 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 11:16:22.651  4415  4443 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 11:16:22.651  4415  4443 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 11:16:22.651  4415  4443 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 11:16:22.651  4415  4443 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 11:16:22.651  4415  4443 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:16:22.651  4415  4443 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 11:16:22.651  4415  4443 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-31 11:16:22.651  4415  4443 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-31 11:16:22.651  4415  4443 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-31 11:16:22.651  4415  4443 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-31 11:16:22.651  4415  4443 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:16:22.651  4415  4443 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:16:22.651  4415  4443 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 11:16:22.652   876  1969 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-31 11:16:22.666   876   889 I ActivityManager: Start proc 4478:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-31 11:16:22.684  4415  4443 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-31 11:16:22.694  4415  4445 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-31 11:16:22.694  4415  4445 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:16:22.694  4415  4445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:16:22.694  4415  4445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 11:16:22.694  4415  4445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 11:16:22.694  4415  4445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 11:16:22.694  4415  4445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 11:16:22.694  4415  4445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 11:16:22.694  4415  4445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 11:16:22.694  4415  4445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 11:16:22.694  4415  4445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 11:16:22.694  4415  4445 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 11:16:22.694  4415  4445 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 11:16:22.694  4415  4445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:16:22.694  4415  4445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 11:16:22.694  4415  4445 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-31 11:16:22.694  4415  4445 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-31 11:16:22.694  4415  4445 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-31 11:16:22.694  4415  4445 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-31 11:16:22.694  4415  4445 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-31 11:16:22.694  4415  4445 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-31 11:16:22.694  4415  4445 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-31 11:16:22.694  4415  4445 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:16:22.694  4415  4445 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:16:22.694  4415  4445 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 11:16:22.694  4415  4445 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-31 11:16:22.694  4415  4445 E AndroidRuntime: Process: android.process.acore, PID: 4415
08-31 11:16:22.694  4415  4445 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:16:22.694  4415  4445 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:16:22.694  4415  4445 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 11:16:22.694  4415  4445 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 11:16:22.694  4415  4445 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 11:16:22.694  4415  4445 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 11:16:22.694  4415  4445 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 11:16:22.694  4415  4445 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 11:16:22.694  4415  4445 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 11:16:22.694  4415  4445 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 11:16:22.694  4415  4445 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 11:16:22.694  4415  4445 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 11:16:22.694  4415  4445 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:16:22.694  4415  4445 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 11:16:22.694  4415  4445 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-31 11:16:22.694  4415  4445 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-31 11:16:22.694  4415  4445 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-31 11:16:22.694  4415  4445 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-31 11:16:22.694  4415  4445 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-31 11:16:22.694  4415  4445 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-31 11:16:22.694  4415  4445 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-31 11:16:22.694  4415  4445 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:16:22.694  4415  4445 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:16:22.694  4415  4445 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 11:16:22.697  4415  4443 I Process : Sending signal. PID: 4415 SIG: 9
,08-31 11:16:22.700   876  4490 E DropBoxManagerService: Can't write: system_app_crash
08-31 11:16:22.700   876  4490 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-31 11:16:22.700   876  4490 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 11:16:22.700   876  4490 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 11:16:22.700   876  4490 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 11:16:22.700   876  4490 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 11:16:22.700   876  4490 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 11:16:22.700   876  4490 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 11:16:22.700   876  4490 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 11:16:22.700   876  4490 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 11:16:22.700   876  4490 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 11:16:22.700   876  4490 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 11:16:22.700   876  4490 E DropBoxManagerService: 	... 5 more
,08-31 11:16:22.710   876  1305 D WifiService: Client connection lost with reason: 4
,08-31 11:16:22.717   876  1390 I ActivityManager: Process com.google.process.gapps (pid 1502) has died
08-31 11:16:22.717   876  1390 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 1000ms
08-31 11:16:22.717   876  1390 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
08-31 11:16:22.718   876  1390 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 21000ms
08-31 11:16:22.718   876  1390 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 31000ms
,08-31 11:16:22.721   876  1304 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 15 -> obsolete
,08-31 11:16:22.727  4478  4478 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-31 11:16:22.727  4478  4478 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:16:22.727  4478  4478 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:16:22.727  4478  4478 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 11:16:22.727  4478  4478 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 11:16:22.727  4478  4478 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 11:16:22.727  4478  4478 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 11:16:22.727  4478  4478 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 11:16:22.727  4478  4478 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 11:16:22.727  4478  4478 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 11:16:22.727  4478  4478 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 11:16:22.727  4478  4478 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 11:16:22.727  4478  4478 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 11:16:22.727  4478  4478 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:16:22.727  4478  4478 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 11:16:22.727  4478  4478 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-31 11:16:22.727  4478  4478 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-31 11:16:22.727  4478  4478 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-31 11:16:22.727  4478  4478 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-31 11:16:22.727  4478  4478 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-31 11:16:22.727  4478  4478 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-31 11:16:22.727  4478  4478 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-31 11:16:22.727  4478  4478 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 11:16:22.727  4478  4478 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 11:16:22.727  4478  4478 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:16:22.727  4478  4478 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:16:22.727  4478  4478 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 11:16:22.727  4478  4478 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:16:22.727  4478  4478 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:16:22.727  4478  4478 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 11:16:22.728  4478  4478 D AndroidRuntime: Shutting down VM
,08-31 11:16:22.738  1732  1732 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-31 11:16:22.740   876  1969 I ActivityManager: Start proc 4491:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,08-31 11:16:22.751   876  1390 I ActivityManager: Process android.process.acore (pid 4415) has died
,08-31 11:16:22.751   876  1390 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 30967ms
,08-31 11:16:22.758  4478  4478 E AndroidRuntime: FATAL EXCEPTION: main
08-31 11:16:22.758  4478  4478 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4478
08-31 11:16:22.758  4478  4478 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:16:22.758  4478  4478 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-31 11:16:22.758  4478  4478 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-31 11:16:22.758  4478  4478 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-31 11:16:22.758  4478  4478 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 11:16:22.758  4478  4478 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 11:16:22.758  4478  4478 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:16:22.758  4478  4478 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:16:22.758  4478  4478 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 11:16:22.758  4478  4478 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:16:22.758  4478  4478 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:16:22.758  4478  4478 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 11:16:22.758  4478  4478 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:16:22.758  4478  4478 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:16:22.758  4478  4478 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 11:16:22.758  4478  4478 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 11:16:22.758  4478  4478 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 11:16:22.758  4478  4478 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 11:16:22.758  4478  4478 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 11:16:22.758  4478  4478 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 11:16:22.758  4478  4478 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 11:16:22.758  4478  4478 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 11:16:22.758  4478  4478 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 11:16:22.758  4478  4478 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 11:16:22.758  4478  4478 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:16:22.758  4478  4478 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 11:16:22.758  4478  4478 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-31 11:16:22.758  4478  4478 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-31 11:16:22.758  4478  4478 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-31 11:16:22.758  4478  4478 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-31 11:16:22.758  4478  4478 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-31 11:16:22.758  4478  4478 E AndroidRuntime: 	... 10 more
08-31 11:16:22.763   876   887 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-31 11:16:22.764   876  4504 E DropBoxManagerService: Can't write: system_app_crash
08-31 11:16:22.764   876  4504 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-31 11:16:22.764   876  4504 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 11:16:22.764   876  4504 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 11:16:22.764   876  4504 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 11:16:22.764   876  4504 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 11:16:22.764   876  4504 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 11:16:22.764   876  4504 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 11:16:22.764   876  4504 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 11:16:22.764   876  4504 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 11:16:22.764   876  4504 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 11:16:22.764   876  4504 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 11:16:22.764   876  4504 E DropBoxManagerService: 	... 5 more
08-31 11:16:22.764  4478  4478 I Process : Sending signal. PID: 4478 SIG: 9
,08-31 11:16:22.780  1732  1732 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-31 11:16:22.781  1732  1732 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-31 11:16:22.786  1732  1732 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-31 11:16:22.786  1732  1732 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-31 11:16:22.790  1732  4472 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-31 11:16:22.791  1732  4472 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-31 11:16:22.794  4491  4491 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-31 11:16:22.795   876  1969 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 2712)
08-31 11:16:22.796   876  1969 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver}
08-31 11:16:22.796   876  1969 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
08-31 11:16:22.796   876  1969 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 11:16:22.796   876  1969 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
08-31 11:16:22.796   876  1969 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
08-31 11:16:22.796   876  1969 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
08-31 11:16:22.796   876  1969 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
08-31 11:16:22.796   876  1969 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17118)
08-31 11:16:22.796   876  1969 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
08-31 11:16:22.796   876  1969 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
08-31 11:16:22.796   876  1969 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
,08-31 11:16:22.796  1732  4507 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-31 11:16:22.807  4491  4491 I MultiDex: VM with version 2.1.0 has multidex support
08-31 11:16:22.807  4491  4491 I MultiDex: install
08-31 11:16:22.807  4491  4491 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-31 11:16:22.811  1732  4507 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
08-31 11:16:22.811  1732  4507 E AndroidRuntime: Process: com.google.android.gms, PID: 1732
08-31 11:16:22.811  1732  4507 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 11:16:22.811  1732  4507 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-31 11:16:22.811  1732  4507 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-31 11:16:22.811  1732  4507 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-31 11:16:22.811  1732  4507 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-31 11:16:22.811  1732  4507 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-31 11:16:22.811  1732  4507 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
08-31 11:16:22.811  1732  4507 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
08-31 11:16:22.811  1732  4507 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
08-31 11:16:22.811  1732  4507 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
08-31 11:16:22.811  1732  4507 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-31 11:16:22.811  1732  4507 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-31 11:16:22.811  1732  4507 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
08-31 11:16:22.811  1732  4507 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
08-31 11:16:22.811  1732  4507 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
08-31 11:16:22.811  1732  4507 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
08-31 11:16:22.811  1732  4507 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 11:16:22.811  1732  4507 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 11:16:22.811  1732  4507 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
,08-31 11:16:22.818   876  1969 I ActivityManager: Start proc 4509:com.google.android.googlequicksearchbox/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver
,08-31 11:16:22.819   876  3232 W ActivityManager: Spurious death for ProcessRecord{d286c27 4509:com.google.android.googlequicksearchbox/u0a28}, curProc for 4478: null
,08-31 11:16:22.821  4491  4491 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
08-31 11:16:22.822   876  4517 E DropBoxManagerService: Can't write: system_app_crash
08-31 11:16:22.822   876  4517 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-31 11:16:22.822   876  4517 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 11:16:22.822   876  4517 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 11:16:22.822   876  4517 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 11:16:22.822   876  4517 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 11:16:22.822   876  4517 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 11:16:22.822   876  4517 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 11:16:22.822   876  4517 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 11:16:22.822   876  4517 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 11:16:22.822   876  4517 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 11:16:22.822   876  4517 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 11:16:22.822   876  4517 E DropBoxManagerService: 	... 5 more
08-31 11:16:22.823   282   339 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
