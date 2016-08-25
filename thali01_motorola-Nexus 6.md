#### Test 82728424d2195a9_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-25 20:52:58.449  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 20:52:58.462  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-25 20:52:58.466  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-25 20:52:58.539  1508  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-25 20:52:58.540  1508  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-25 20:52:58.540  1508  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 20:52:58.540  1508  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-25 20:52:58.577  3689  3689 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-25 20:52:58.577  3689  3689 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-25 20:52:58.578  3689  3689 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
08-25 20:52:59.089  3978  3978 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-25 20:52:59.093  3978  3978 D AndroidRuntime: CheckJNI is OFF
08-25 20:52:59.128  3978  3978 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-25 20:52:59.171  3978  3978 I Radio-JNI: register_android_hardware_Radio DONE
08-25 20:52:59.191  3978  3978 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-25 20:52:59.194   876  1985 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-25 20:52:59.233  2044  2074 W SearchService: Abort, client detached.
08-25 20:52:59.240  2044  2044 I HotwordDetector: Closing mic
08-25 20:52:59.240  2044  2356 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@61b472
08-25 20:52:59.240  2044  2362 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-25 20:52:59.242  3978  3978 D AndroidRuntime: Shutting down VM
08-25 20:52:59.265   876   886 I ActivityManager: Start proc 3987:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-25 20:52:59.289   378  2364 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-25 20:52:59.295   378  2364 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-25 20:52:59.301   378  1289 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-25 20:52:59.304  2044  2359 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-25 20:52:59.305  2044  2361 I MicroRecognitionRnrImpl: Detection finished
08-25 20:52:59.365  3987  3987 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-25 20:52:59.392  3987  3987 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-25 20:52:59.401  3987  3987 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 2172-2176)
08-25 20:52:59.402  3987  3987 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 20:52:59.424  3987  3987 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {198aa4}
08-25 20:52:59.425  3987  3987 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 20:52:59.426  3987  3987 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-25 20:52:59.433  3987  3987 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-25 20:52:59.435  3987  3987 E SysUtils: ApplicationContext is null in ApplicationStatus
08-25 20:52:59.453  3987  3987 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-25 20:52:59.495  3987  3987 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-25 20:52:59.496  3987  3987 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-25 20:52:59.496  3987  3987 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-25 20:52:59.496  3987  3987 I Adreno  : Build Date                       : 10/20/15
08-25 20:52:59.496  3987  3987 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-25 20:52:59.496  3987  3987 I Adreno  : Local Branch                     : M14
08-25 20:52:59.496  3987  3987 I Adreno  : Remote Branch                    : 
08-25 20:52:59.496  3987  3987 I Adreno  : Remote Branch                    : 
08-25 20:52:59.496  3987  3987 I Adreno  : Reconstruct Branch               : 
,08-25 20:52:59.571   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b1acdf6:true
,08-25 20:52:59.676  3987  3987 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-25 20:52:59.703  3987  3987 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-25 20:52:59.792  3987  4025 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-25 20:52:59.801  3987  4012 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-25 20:52:59.847  3987  4025 I OpenGLRenderer: Initialized EGL, version 1.4
,08-25 20:52:59.910   876   894 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +667ms
,08-25 20:52:59.912  1871  1871 I Keyboard.Facilitator: onFinishInput()
,08-25 20:53:00.001  3987  3987 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3987
,08-25 20:53:00.116   876  1716 I ActivityManager: Killing 3400:com.google.android.gm/u0a78 (adj 15): empty #17
,08-25 20:53:00.130  3987  3987 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-25 20:53:00.156   876  1716 I ActivityManager: Killing 2851:com.google.android.apps.fitness/u0a51 (adj 15): empty #18
,08-25 20:53:00.302  3987  4027 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1679886032
,08-25 20:53:00.311  3987  4027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-25 20:53:00.311  3987  4027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-25 20:53:00.311  3987  4027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-25 20:53:00.311  3987  4027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-25 20:53:00.311  3987  4027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-25 20:53:00.311  3987  4027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@113640b added. We now have 1 listener(s)
,08-25 20:53:00.314  3987  4027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-25 20:53:00.314   876  1318 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2412
08-25 20:53:00.315  3987  4027 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 20:53:00.315  3987  4027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 20:53:00.316  3987  4027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 20:53:00.320  3987  4027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-25 20:53:00.320  3987  4027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-25 20:53:00.320  3987  4027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-25 20:53:00.320  3987  4027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-25 20:53:00.320  3987  4027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-25 20:53:00.320  3987  4027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-25 20:53:00.320  3987  4027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-25 20:53:00.320  3987  4027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-25 20:53:00.320  3987  4027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-25 20:53:00.320  3987  4027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE,
08-25 20:53:00.320  3987  4027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-25 20:53:00.320  3987  4027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-25 20:53:00.320  3987  4027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-25 20:53:00.320  3987  4027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-25 20:53:00.320  3987  4027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@90f7a6 added. We now have 1 listener(s)
08-25 20:53:00.321  3987  4027 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 20:53:00.326   876  1319 D WifiService: New client listening to asynchronous messages
08-25 20:53:00.328  3987  4027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 20:53:00.328  3987  4027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-25 20:53:00.328  3987  4027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-25 20:53:00.328  3987  4027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-25 20:53:00.329  3987  4027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-25 20:53:00.333  3987  4027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 20:53:00.333  3987  4027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-25 20:53:00.339  3987  4027 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-25 20:53:00.339  3987  4027 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 20:53:00.339  3987  4027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:53:00.339  3987  4027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 20:53:00.339  3987  4027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:53:00.339  3987  4027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 20:53:00.339  3987  4027 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 20:53:00.339  3987  4027 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 20:53:00.339  3987  4027 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 20:53:00.339  3987  4027 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-25 20:53:00.339  3987  4027 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 20:53:00.342  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 20:53:00.342  3987  4027 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-25 20:53:00.343  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 20:53:00.376  3987  3987 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-25 20:53:01.342  3987  4038 W jxcore-log: Initializing JXcore engine
,08-25 20:53:01.342  3987  4038 W jxcore-log: JXcore engine is ready
,08-25 20:53:01.375  4038  4038 W Thread-370: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8942 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-25 20:53:01.375  4038  4038 W Thread-370: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11726]" dev="sockfs" ino=11726 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-25 20:53:01.375  4038  4038 W Thread-370: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-25 20:53:01.375  4038  4038 W Thread-370: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24303]" dev="sockfs" ino=24303 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-25 20:53:01.392  3987  4038 W jxcore-log: Starting JXcore engine
,08-25 20:53:01.476  3987  4038 W jxcore-log: Platform android
08-25 20:53:01.476  3987  4038 W jxcore-log: 
,08-25 20:53:01.477  3987  4038 W jxcore-log: Process ARCH arm
08-25 20:53:01.477  3987  4038 W jxcore-log: 
,08-25 20:53:01.724  3987  4038 I jxcore-log: JXcore Cordova bridge is ready!
08-25 20:53:01.724  3987  4038 I jxcore-log: 
,08-25 20:53:01.725  3987  4038 W jxcore-log: JXcore engine is started
,08-25 20:53:01.731  3987  4027 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-25 20:53:01.735  3987  3987 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-25 20:53:05.276   876  2082 D NetlinkSocketObserver: NeighborEvent{elapsedMs=128050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-25 20:53:06.730  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 20:53:06.734  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 20:53:06.790  1508  2042 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-25 20:53:06.790  1508  2042 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-25 20:53:06.790  1508  2042 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 20:53:06.791  1508  2042 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 20:53:06.827  3728  4047 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-25 20:53:06.827  3728  4047 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-25 20:53:06.827  3728  4047 E HttpOperation: 	at jdm.a(PG:82)
,08-25 20:53:06.827  3728  4047 E HttpOperation: 	at jcs.o(PG:406)
08-25 20:53:06.827  3728  4047 E HttpOperation: 	at jcn.a(PG:1379)
08-25 20:53:06.827  3728  4047 E HttpOperation: 	at jcs.i(PG:143)
08-25 20:53:06.827  3728  4047 E HttpOperation: 	at blb.a(PG:3937)
08-25 20:53:06.827  3728  4047 E HttpOperation: 	at czp.a(PG:18188)
08-25 20:53:06.827  3728  4047 E HttpOperation: 	at czp.a(PG:9081)
08-25 20:53:06.827  3728  4047 E HttpOperation: 	at czq.run(PG:1686)
08-25 20:53:06.827  3728  4047 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-25 20:53:06.827  3728  4047 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-25 20:53:06.827  3728  4047 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 20:53:06.827  3728  4047 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 20:53:06.827  3728  4047 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-25 20:53:06.827  3728  4047 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-25 20:53:06.827  3728  4047 E HttpOperation: 	at jdj.a(PG:4091)
08-25 20:53:06.827  3728  4047 E HttpOperation: 	at jdj.a(PG:1125)
08-25 20:53:06.827  3728  4047 E HttpOperation: 	at jdm.a(PG:77)
08-25 20:53:06.827  3728  4047 E HttpOperation: 	... 12 more
08-25 20:53:06.827  3728  4047 E HttpOperation: Caused by: faj: BadAuthentication
08-25 20:53:06.827  3728  4047 E HttpOperation: 	at fal.a(PG:38)
08-25 20:53:06.827  3728  4047 E HttpOperation: 	at jdj.a(PG:4089)
08-25 20:53:06.827  3728  4047 E HttpOperation: 	... 14 more
,08-25 20:53:06.911  1508  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-25 20:53:06.912  1508  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-25 20:53:06.912  1508  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 20:53:06.913  1508  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 20:53:06.942  3728  4047 E HttpOperation: [getmobileexperiments] Unexpected exception
08-25 20:53:06.942  3728  4047 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-25 20:53:06.942  3728  4047 E HttpOperation: 	at jdm.a(PG:82)
08-25 20:53:06.942  3728  4047 E HttpOperation: 	at jcs.o(PG:406)
08-25 20:53:06.942  3728  4047 E HttpOperation: 	at jcn.a(PG:1379)
08-25 20:53:06.942  3728  4047 E HttpOperation: 	at jcs.i(PG:143)
08-25 20:53:06.942  3728  4047 E HttpOperation: 	at hec.a(PG:42)
08-25 20:53:06.942  3728  4047 E HttpOperation: 	at hee.a(PG:102)
08-25 20:53:06.942  3728  4047 E HttpOperation: 	at czr.a(PG:65)
08-25 20:53:06.942  3728  4047 E HttpOperation: 	at kka.a(PG:108)
08-25 20:53:06.942  3728  4047 E HttpOperation: 	at czp.a(PG:19176)
08-25 20:53:06.942  3728  4047 E HttpOperation: 	at czp.a(PG:9081)
08-25 20:53:06.942  3728  4047 E HttpOperation: 	at czq.run(PG:1686)
08-25 20:53:06.942  3728  4047 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-25 20:53:06.942  3728  4047 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-25 20:53:06.942  3728  4047 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 20:53:06.942  3728  4047 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 20:53:06.942  3728  4047 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-25 20:53:06.942  3728  4047 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-25 20:53:06.942  3728  4047 E HttpOperation: 	at jdj.a(PG:4091)
08-25 20:53:06.942  3728  4047 E HttpOperation: 	at jdj.a(PG:1125)
08-25 20:53:06.942  3728  4047 E HttpOperation: 	at jdm.a(PG:77)
08-25 20:53:06.942  3728  4047 E HttpOperation: 	... 15 more
08-25 20:53:06.942  3728  4047 E HttpOperation: Caused by: faj: BadAuthentication
08-25 20:53:06.942  3728  4047 E HttpOperation: 	at fal.a(PG:38)
08-25 20:53:06.942  3728  4047 E HttpOperation: 	at jdj.a(PG:4089)
08-25 20:53:06.942  3728  4047 E HttpOperation: 	... 17 more
,08-25 20:53:06.942  3728  4047 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-25 20:53:06.942  3728  4047 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-25 20:53:06.942  3728  4047 E ExperimentLoader: 	at jdm.a(PG:82)
08-25 20:53:06.942  3728  4047 E ExperimentLoader: 	at jcs.o(PG:406)
08-25 20:53:06.942  3728  4047 E ExperimentLoader: 	at jcn.a(PG:1379)
08-25 20:53:06.942  3728  4047 E ExperimentLoader: 	at jcs.i(PG:143)
08-25 20:53:06.942  3728  4047 E ExperimentLoader: 	at hec.a(PG:42)
08-25 20:53:06.942  3728  4047 E ExperimentLoader: 	at hee.a(PG:102)
08-25 20:53:06.942  3728  4047 E ExperimentLoader: 	at czr.a(PG:65)
08-25 20:53:06.942  3728  4047 E ExperimentLoader: 	at kka.a(PG:108)
08-25 20:53:06.942  3728  4047 E ExperimentLoader: 	at czp.a(PG:19176)
08-25 20:53:06.942  3728  4047 E ExperimentLoader: 	at czp.a(PG:9081)
08-25 20:53:06.942  3728  4047 E ExperimentLoader: 	at czq.run(PG:1686)
,08-25 20:53:06.942  3728  4047 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-25 20:53:06.942  3728  4047 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-25 20:53:06.942  3728  4047 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 20:53:06.942  3728  4047 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 20:53:06.942  3728  4047 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-25 20:53:06.942  3728  4047 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-25 20:53:06.942  3728  4047 E ExperimentLoader: 	at jdj.a(PG:4091)
08-25 20:53:06.942  3728  4047 E ExperimentLoader: 	at jdj.a(PG:1125)
08-25 20:53:06.942  3728  4047 E ExperimentLoader: 	at jdm.a(PG:77)
08-25 20:53:06.942  3728  4047 E ExperimentLoader: 	... 15 more
08-25 20:53:06.942  3728  4047 E ExperimentLoader: Caused by: faj: BadAuthentication
08-25 20:53:06.942  3728  4047 E ExperimentLoader: 	at fal.a(PG:38)
08-25 20:53:06.942  3728  4047 E ExperimentLoader: 	at jdj.a(PG:4089)
08-25 20:53:06.942  3728  4047 E ExperimentLoader: 	... 17 more
,08-25 20:53:07.148   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 128923, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-25 20:53:11.721  3987  4038 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-25 20:53:11.721  3987  4038 I jxcore-log: 
,08-25 20:53:11.724  3987  4038 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-25 20:53:11.724  3987  4038 I jxcore-log: 
,08-25 20:53:11.734  3987  4038 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 20:53:11.734  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:53:11.734  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 20:53:11.734  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:53:11.734  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 20:53:11.734  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 20:53:11.734  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 20:53:11.734  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 20:53:11.739  3987  4038 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 20:53:11.746  3987  4038 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-25 20:53:11.746  3987  4038 I jxcore-log: 
,08-25 20:53:11.754  3987  4038 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-25 20:53:11.754  3987  4038 I jxcore-log: 
,08-25 20:53:12.271  3987  4038 D executeNativeTests: Running unit tests
,08-25 20:53:12.331  3987  4038 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 20:53:12.331  3987  4038 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf76fb8 added. We now have 2 listener(s)
08-25 20:53:12.332  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 20:53:12.332  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 20:53:12.332  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 20:53:12.333  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 20:53:12.333  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 added. We now have 2 listener(s)
08-25 20:53:12.333  3987  4038 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 20:53:12.334  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 20:53:12.340  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 20:53:12.356  3987  4038 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 20:53:12.356  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:53:12.356  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 20:53:12.356  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:53:12.356  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 20:53:12.356  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 20:53:12.356  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 20:53:12.356  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 20:53:12.363  3987  4038 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 20:53:12.363  3987  4038 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 20:53:12.365  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-25 20:53:12.367  3987  4038 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-25 20:53:12.367  3987  4038 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-25 20:53:12.369  3987  4038 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-25 20:53:12.369  3987  4038 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 20:53:12.369  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 20:53:12.369  3987  4038 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 20:53:12.369  3987  4038 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-25 20:53:12.370  3987  4038 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:53:12.370  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:53:12.370  3987  4038 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 20:53:12.371  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:53:12.371  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.371  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 20:53:12.371  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:53:12.371  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-25 20:53:12.371  3987  4038 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf76fb8 removed from the list
08-25 20:53:12.371  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.371  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 removed from the list
08-25 20:53:12.378  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:53:12.379  3987  4038 D io.jxcore.node.ConnectivityMonitor: stop,
08-25 20:53:12.379  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.379  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.379  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.381  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:53:12.381  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:53:12.381  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.381  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
08-25 20:53:12.385  3987  4038 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-25 20:53:12.385  3987  4038 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:53:12.385  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:53:12.385  3987  4038 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:53:12.386  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:53:12.386  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.386  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.386  3987  4038 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf76fb8 not in the list
08-25 20:53:12.386  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.386  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
08-25 20:53:12.386  3987  4038 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 20:53:12.386  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.386  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.386  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.386  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.390  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 20:53:12.390  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:53:12.390  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.391  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
,08-25 20:53:12.410  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-25 20:53:12.411  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 20:53:12.411  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 20:53:12.412  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-25 20:53:12.412  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 20:53:12.412  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 20:53:12.412  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 20:53:12.412  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 20:53:12.412  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 20:53:12.412  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-25 20:53:12.412  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 20:53:12.412  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 20:53:12.412  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 20:53:12.412  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 20:53:12.412  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 20:53:12.412  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-25 20:53:12.412  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 20:53:12.413  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 20:53:12.413  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 20:53:12.413  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 20:53:12.413  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 20:53:12.413  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-25 20:53:12.413  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 20:53:12.413  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 20:53:12.413  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 20:53:12.413  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 20:53:12.413  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 20:53:12.413  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 20:53:12.413  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-25 20:53:12.413  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 20:53:12.413  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 20:53:12.414  3987  4038 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:53:12.414  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:53:12.414  3987  4038 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:53:12.414  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:53:12.414  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 20:53:12.414  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.414  3987  4038 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf76fb8 not in the list
08-25 20:53:12.414  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.414  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
08-25 20:53:12.414  3987  4038 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:53:12.414  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.414  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.414  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.414  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 20:53:12.415  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:53:12.415  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:53:12.415  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.416  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
08-25 20:53:12.416  3987  4038 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 20:53:12.418  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 20:53:12.429  3987  4038 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 20:53:12.429  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:53:12.429  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 20:53:12.429  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:53:12.429  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 20:53:12.429  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 20:53:12.429  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 20:53:12.429  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 20:53:12.434  3987  4038 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 20:53:12.434  3987  4038 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 20:53:12.435  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 20:53:12.435  3987  4038 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 20:53:12.436  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 20:53:12.436  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 20:53:12.436  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 20:53:12.437  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 20:53:12.440  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 20:53:12.446  3987  4038 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-25 20:53:12.446  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 20:53:12.454  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 20:53:12.455  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-25 20:53:12.456  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 20:53:12.458  3987  4038 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-25 20:53:12.461  3987  4038 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-25 20:53:12.461  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-25 20:53:12.461  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-25 20:53:12.462  3987  4038 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 20:53:12.464  3987  4038 D BluetoothAdapter: STATE_ON
,08-25 20:53:12.475  2687  2698 D BtGatt.GattService: registerClient() - UUID=82cd27bc-56dc-4bec-9cae-22b8a4ddf5cb
,08-25 20:53:12.477  2687  2709 D BtGatt.GattService: onClientRegistered() - UUID=82cd27bc-56dc-4bec-9cae-22b8a4ddf5cb, clientIf=5
,08-25 20:53:12.477  3987  3998 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-25 20:53:12.478  2687  2867 D BtGatt.GattService: start scan with filters
,08-25 20:53:12.481  2687  2714 D BtGatt.ScanManager: handling starting scan
,08-25 20:53:12.482  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 20:53:12.483  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-25 20:53:12.483  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 20:53:12.483  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 20:53:12.484  2687  2714 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04b20e
,08-25 20:53:12.491  3987  4038 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 20:53:12.493  3987  3987 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
08-25 20:53:12.494  2687  2709 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-25 20:53:12.494  2687  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 20:53:12.494  3987  4038 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 20:53:12.494  2687  2714 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-25 20:53:12.495  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 20:53:12.499  3987  4038 I io.jxcore.node.ConnectionHelper: start: OK
,08-25 20:53:12.504  2687  2709 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-25 20:53:12.504  2687  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 20:53:12.504  3987  4038 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:53:12.504  3987  4038 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-25 20:53:12.505  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-25 20:53:12.505  2687  2714 D BtGatt.ScanManager: Starting BLE batch scan
08-25 20:53:12.505  2687  2714 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-25 20:53:12.505  3987  4038 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-25 20:53:12.505  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 20:53:12.505  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 20:53:12.505  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 20:53:12.506  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 20:53:12.506  3987  4038 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 20:53:12.506  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-25 20:53:12.507  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-25 20:53:12.507  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 20:53:12.509  3987  4038 D BluetoothAdapter: STATE_ON
08-25 20:53:12.510  2687  2867 D BtGatt.GattService: stopScan() - queue size =1
08-25 20:53:12.511  2687  2699 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-25 20:53:12.511  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 20:53:12.512  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 20:53:12.512  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-25 20:53:12.512  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 20:53:12.512  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-25 20:53:12.513  3987  4038 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 20:53:12.514  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-25 20:53:12.515  3987  4038 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-25 20:53:12.516  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 20:53:12.517  2687  2709 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-25 20:53:12.517  2687  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 20:53:12.517  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 20:53:12.520  3987  3987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 20:53:12.520  3987  3987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 20:53:12.521  3987  3987 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 20:53:12.521  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 20:53:12.522  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 20:53:12.522  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 20:53:12.522  3987  4038 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf76fb8 not in the list
,08-25 20:53:12.522  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.523  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
08-25 20:53:12.523  3987  4038 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:53:12.523  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.524  2687  2709 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-25 20:53:12.524  2687  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 20:53:12.524  3987  4038 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-25 20:53:12.529  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 20:53:12.535  2687  2709 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-25 20:53:12.536  2687  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 20:53:12.536  2687  2714 D BtGatt.ScanManager: stopping BLe Batch
,08-25 20:53:12.539  3987  4038 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 20:53:12.539  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:53:12.539  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 20:53:12.539  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:53:12.539  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 20:53:12.539  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 20:53:12.539  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 20:53:12.539  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 20:53:12.541  3987  4038 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 20:53:12.542  3987  4038 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 20:53:12.542  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 20:53:12.542  3987  4038 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 20:53:12.542  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 20:53:12.542  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 20:53:12.542  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 20:53:12.544  2687  2709 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-25 20:53:12.544  2687  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 20:53:12.545  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:53:12.545  2687  2714 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 20:53:12.547  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 20:53:12.549  3987  4038 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-25 20:53:12.549  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 20:53:12.552  2687  2709 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-25 20:53:12.552  2687  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 20:53:12.558  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 20:53:12.559  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-25 20:53:12.560  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 20:53:12.567  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-25 20:53:12.567  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-25 20:53:12.567  3987  4038 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 20:53:12.569  3987  4038 D BluetoothAdapter: STATE_ON
,08-25 20:53:12.573  2687  2698 D BtGatt.GattService: registerClient() - UUID=05771007-49a5-483b-85f5-33c867c474a5
,08-25 20:53:12.574  2687  2709 D BtGatt.GattService: onClientRegistered() - UUID=05771007-49a5-483b-85f5-33c867c474a5, clientIf=5
,08-25 20:53:12.575  3987  3999 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-25 20:53:12.576  2687  2867 D BtGatt.GattService: start scan with filters
,08-25 20:53:12.582  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 20:53:12.582  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 20:53:12.583  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 20:53:12.583  2687  2714 D BtGatt.ScanManager: handling starting scan
,08-25 20:53:12.583  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 20:53:12.590  3987  4038 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 20:53:12.591  3987  4038 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 20:53:12.591  3987  3987 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 20:53:12.592  2687  2709 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-25 20:53:12.592  2687  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 20:53:12.593  2687  2714 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-25 20:53:12.595  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 20:53:12.602  3987  4038 I io.jxcore.node.ConnectionHelper: start: OK
08-25 20:53:12.602  2687  2709 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-25 20:53:12.602  2687  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 20:53:12.602  2687  2714 D BtGatt.ScanManager: Starting BLE batch scan
08-25 20:53:12.602  2687  2714 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-25 20:53:12.605  3987  4038 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:53:12.605  3987  4038 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-25 20:53:12.606  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-25 20:53:12.606  3987  4038 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-25 20:53:12.606  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.606  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-25 20:53:12.606  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 20:53:12.606  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 20:53:12.606  3987  4038 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-25 20:53:12.606  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 20:53:12.606  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-25 20:53:12.606  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 20:53:12.607  3987  4038 D BluetoothAdapter: STATE_ON
08-25 20:53:12.608  2687  2698 D BtGatt.GattService: stopScan() - queue size =1
,08-25 20:53:12.609  2687  2867 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-25 20:53:12.609  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-25 20:53:12.609  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 20:53:12.609  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 20:53:12.610  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-25 20:53:12.610  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 20:53:12.611  3987  4038 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 20:53:12.612  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 20:53:12.612  3987  4038 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 20:53:12.612  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 20:53:12.613  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 20:53:12.615  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:53:12.615  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 20:53:12.615  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 20:53:12.615  3987  4038 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf76fb8 not in the list
08-25 20:53:12.615  3987  3987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 20:53:12.615  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.615  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
08-25 20:53:12.615  3987  4038 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:53:12.615  3987  3987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 20:53:12.615  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 20:53:12.615  3987  3987 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 20:53:12.616  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.616  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.617  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:53:12.617  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 20:53:12.617  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.617  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
08-25 20:53:12.618  3987  4038 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 20:53:12.619  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 20:53:12.619  2687  2709 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-25 20:53:12.619  2687  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 20:53:12.625  3987  4038 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 20:53:12.625  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:53:12.625  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 20:53:12.625  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:53:12.625  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 20:53:12.625  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 20:53:12.625  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 20:53:12.625  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 20:53:12.626  2687  2709 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-25 20:53:12.626  2687  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 20:53:12.628  3987  4038 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 20:53:12.628  3987  4038 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 20:53:12.628  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 20:53:12.628  3987  4038 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 20:53:12.628  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 20:53:12.629  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 20:53:12.629  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 20:53:12.632  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:53:12.634  3987  4038 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-25 20:53:12.634  2687  2709 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-25 20:53:12.635  2687  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 20:53:12.635  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 20:53:12.635  2687  2714 D BtGatt.ScanManager: stopping BLe Batch
08-25 20:53:12.636  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:53:12.639  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 20:53:12.639  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-25 20:53:12.639  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 20:53:12.642  2687  2709 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-25 20:53:12.642  2687  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 20:53:12.642  2687  2714 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-25 20:53:12.645  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-25 20:53:12.645  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 20:53:12.646  3987  4038 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-25 20:53:12.646  3987  4038 D BluetoothAdapter: STATE_ON
08-25 20:53:12.649  2687  2699 D BtGatt.GattService: registerClient() - UUID=1065c4fa-fba0-4037-936c-46ecc52c3400
08-25 20:53:12.649  2687  2709 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-25 20:53:12.649  2687  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 20:53:12.649  2687  2709 D BtGatt.GattService: onClientRegistered() - UUID=1065c4fa-fba0-4037-936c-46ecc52c3400, clientIf=5
08-25 20:53:12.650  3987  3998 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-25 20:53:12.650  2687  2698 D BtGatt.GattService: start scan with filters
08-25 20:53:12.654  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 20:53:12.655  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 20:53:12.655  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 20:53:12.655  2687  2714 D BtGatt.ScanManager: handling starting scan
08-25 20:53:12.655  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-25 20:53:12.658  3987  4038 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 20:53:12.659  3987  4038 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-25 20:53:12.659  3987  3987 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 20:53:12.660  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-25 20:53:12.662  2687  2709 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-25 20:53:12.662  2687  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 20:53:12.663  2687  2714 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-25 20:53:12.663  3987  4038 I io.jxcore.node.ConnectionHelper: start: OK
08-25 20:53:12.664  3987  4038 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:53:12.664  3987  4038 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 20:53:12.664  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 20:53:12.664  3987  4038 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-25 20:53:12.664  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.664  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 20:53:12.664  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 20:53:12.664  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 20:53:12.664  3987  4038 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 20:53:12.664  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 20:53:12.664  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 20:53:12.665  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 20:53:12.665  3987  4038 D BluetoothAdapter: STATE_ON
08-25 20:53:12.666  2687  2698 D BtGatt.GattService: stopScan() - queue size =1
08-25 20:53:12.667  2687  2875 D BtGatt.GattService: unregisterClient() - clientIf=5
08-25 20:53:12.667  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 20:53:12.667  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 20:53:12.667  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 20:53:12.667  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 20:53:12.668  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-25 20:53:12.669  3987  4038 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 20:53:12.670  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 20:53:12.670  3987  4038 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 20:53:12.670  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 20:53:12.670  2687  2709 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-25 20:53:12.670  2687  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 20:53:12.670  2687  2714 D BtGatt.ScanManager: Starting BLE batch scan
08-25 20:53:12.671  2687  2714 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-25 20:53:12.671  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 20:53:12.674  3987  3987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 20:53:12.674  3987  4038 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:53:12.674  3987  3987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 20:53:12.674  3987  4038 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 20:53:12.674  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:53:12.674  3987  3987 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 20:53:12.674  3987  4038 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:53:12.674  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:53:12.675  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.675  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 20:53:12.675  3987  4038 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf76fb8 not in the list
08-25 20:53:12.675  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.675  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
08-25 20:53:12.675  3987  4038 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:53:12.675  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.676  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.676  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.677  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:53:12.677  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:53:12.677  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.678  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
08-25 20:53:12.678  3987  4038 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-25 20:53:12.679  3987  4038 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:53:12.679  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:53:12.679  3987  4038 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:53:12.679  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:53:12.680  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.680  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.680  3987  4038 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf76fb8 not in the list
08-25 20:53:12.680  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.680  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
,08-25 20:53:12.680  3987  4038 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:53:12.680  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.680  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.680  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.680  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.681  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:53:12.681  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:53:12.682  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.682  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
08-25 20:53:12.683  2687  2709 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-25 20:53:12.683  2687  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 20:53:12.683  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-25 20:53:12.683  3987  4038 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:53:12.683  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:53:12.683  3987  4038 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:53:12.683  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:53:12.683  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.684  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.684  3987  4038 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf76fb8 not in the list
08-25 20:53:12.684  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.684  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
08-25 20:53:12.684  3987  4038 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:53:12.684  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.684  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.684  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.684  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.685  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:53:12.685  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:53:12.685  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.686  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
08-25 20:53:12.686  3987  4038 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-25 20:53:12.686  3987  4038 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:53:12.686  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:53:12.687  3987  4038 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:53:12.687  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:53:12.687  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.687  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.687  3987  4038 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf76fb8 not in the list
08-25 20:53:12.687  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.687  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
08-25 20:53:12.687  3987  4038 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:53:12.687  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.687  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.687  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.687  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.688  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:53:12.689  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:53:12.689  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.689  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
08-25 20:53:12.689  2687  2709 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-25 20:53:12.689  2687  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 20:53:12.689  3987  4038 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-25 20:53:12.690  3987  4038 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:53:12.690  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:53:12.690  3987  4038 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:53:12.690  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:53:12.690  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.690  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.690  3987  4038 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf76fb8 not in the list
08-25 20:53:12.690  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.690  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
08-25 20:53:12.690  3987  4038 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:53:12.690  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.690  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.690  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.690  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.691  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:53:12.692  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:53:12.692  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.692  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
08-25 20:53:12.692  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 20:53:12.694  3987  4038 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 20:53:12.694  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 20:53:12.694  3987  4038 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 20:53:12.694  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 20:53:12.695  3987  4038 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 20:53:12.695  3987  4038 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:53:12.695  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:53:12.695  3987  4038 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:53:12.695  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:53:12.695  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.695  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 20:53:12.696  3987  4038 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf76fb8 not in the list
08-25 20:53:12.696  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.696  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
08-25 20:53:12.696  3987  4038 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:53:12.696  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.696  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.696  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.696  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.697  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:53:12.697  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:53:12.697  2687  2709 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-25 20:53:12.698  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.698  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
08-25 20:53:12.698  2687  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 20:53:12.698  2687  2714 D BtGatt.ScanManager: stopping BLe Batch
08-25 20:53:12.699  3987  4038 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 20:53:12.699  3987  4038 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 20:53:12.700  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-25 20:53:12.704  3987  4038 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 20:53:12.704  3987  4038 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-25 20:53:12.705  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 20:53:12.705  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 20:53:12.705  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-25 20:53:12.705  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 20:53:12.705  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 20:53:12.705  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 20:53:12.706  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 20:53:12.706  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 20:53:12.706  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-25 20:53:12.706  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 20:53:12.706  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 20:53:12.706  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 20:53:12.706  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 20:53:12.706  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 20:53:12.706  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 20:53:12.706  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 20:53:12.706  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 20:53:12.706  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 20:53:12.706  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 20:53:12.706  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 20:53:12.706  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 20:53:12.707  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 20:53:12.707  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 20:53:12.707  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 20:53:12.707  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 20:53:12.707  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 20:53:12.707  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 20:53:12.707  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 20:53:12.707  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 20:53:12.707  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 20:53:12.707  3987  4038 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-25 20:53:12.708  3987  4038 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 20:53:12.708  2687  2709 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-25 20:53:12.708  3987  4038 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-25 20:53:12.708  3987  4038 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 20:53:12.708  2687  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 20:53:12.708  3987  4038 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 20:53:12.708  2687  2714 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-25 20:53:12.708  3987  4038 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-25 20:53:12.709  3987  4038 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 20:53:12.709  3987  4038 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 20:53:12.709  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-25 20:53:12.716  2687  2709 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-25 20:53:12.716  2687  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 20:53:12.714  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-25 20:53:12.717  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-25 20:53:12.717  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-25 20:53:12.717  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-25 20:53:12.717  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-25 20:53:12.718  3987  4038 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-25 20:53:12.718  3987  4038 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 20:53:12.718  3987  4038 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-25 20:53:12.718  3987  4052 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 434)
08-25 20:53:12.719  3987  4038 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:53:12.719  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:53:12.719  3987  4038 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:53:12.719  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:53:12.719  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.719  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.719  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-25 20:53:12.720  3987  4038 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf76fb8 not in the list
08-25 20:53:12.721  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.721  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
08-25 20:53:12.721  3987  4038 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:53:12.721  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.721  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.721  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.721  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.721  3987  4052 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 20:53:12.721  3987  4053 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 434
08-25 20:53:12.721  3987  4053 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 434)
08-25 20:53:12.722  3987  4053 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 434)
08-25 20:53:12.722  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:53:12.722  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:53:12.722  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.722  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
08-25 20:53:12.723  3987  4038 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-25 20:53:12.723  3987  4038 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:53:12.723  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:53:12.723  3987  4038 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:53:12.723  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:53:12.723  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.723  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.724  3987  4038 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf76fb8 not in the list
08-25 20:53:12.724  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.724  3987  4052 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 434)
08-25 20:53:12.724  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
08-25 20:53:12.724  3987  4038 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:53:12.724  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.724  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.724  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.724  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.725  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:53:12.725  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:53:12.725  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.725  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
08-25 20:53:12.726  3987  4038 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-25 20:53:12.726  3987  4038 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:53:12.726  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:53:12.726  3987  4038 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:53:12.726  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:53:12.726  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.726  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.726  3987  4038 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf76fb8 not in the list
08-25 20:53:12.726  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.726  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
08-25 20:53:12.726  3987  4038 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:53:12.726  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.727  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.727  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.727  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.728  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:53:12.728  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:53:12.728  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.728  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
08-25 20:53:12.728  3987  4038 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-25 20:53:12.728  3987  4038 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-25 20:53:12.728  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 20:53:12.729  3987  4038 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-25 20:53:12.729  3987  4038 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 20:53:12.729  3987  4038 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-25 20:53:12.729  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 20:53:12.729  3987  4038 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-25 20:53:12.729  3987  4038 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 20:53:12.729  3987  4038 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 20:53:12.729  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 20:53:12.729  3987  4038 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-25 20:53:12.729  3987  4038 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:53:12.729  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:53:12.729  3987  4038 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:53:12.730  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:53:12.730  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.730  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.730  3987  4038 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf76fb8 not in the list
08-25 20:53:12.730  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.730  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
08-25 20:53:12.730  3987  4038 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:53:12.730  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.730  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.730  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.730  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.732  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:53:12.732  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:53:12.732  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.732  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
08-25 20:53:12.732  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:53:12.732  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.732  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.732  3987  4038 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf76fb8 not in the list
08-25 20:53:12.733  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.733  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
08-25 20:53:12.733  3987  4038 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:53:12.733  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.733  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.733  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.733  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
08-25 20:53:12.733  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:53:12.733  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.733  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.733  3987  4038 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf76fb8 not in the list
08-25 20:53:12.733  3987  4038 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:53:12.733  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:53:12.733  3987  4038 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:53:12.734  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:53:12.734  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.734  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.734  3987  4038 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf76fb8 not in the list
08-25 20:53:12.734  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.734  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
08-25 20:53:12.734  3987  4038 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:53:12.734  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.734  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.734  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.734  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.735  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:53:12.735  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:53:12.735  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.735  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
08-25 20:53:12.736  3987  4038 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-25 20:53:12.736  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 20:53:12.737  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-25 20:53:12.738  3987  4038 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-25 20:53:12.738  3987  4038 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-25 20:53:12.738  3987  3987 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-25 20:53:12.738  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-25 20:53:12.738  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 20:53:12.739  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:53:12.739  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-25 20:53:12.739  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-25 20:53:12.739  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-25 20:53:12.739  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.739  3987  4038 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-25 20:53:12.739  3987  3987 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-25 20:53:12.739  3987  4038 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf76fb8 not in the list
08-25 20:53:12.739  3987  4054 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 20:53:12.739  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.739  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 20:53:12.739  3987  4038 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 20:53:12.739  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 20:53:12.740  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.740  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.741  3987  4038 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 20:53:12.741  3987  3987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 20:53:12.741  3987  3987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 20:53:12.741  3987  3987 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED,, is discovering: false, is advertising: false
08-25 20:53:12.741  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
08-25 20:53:12.741  3987  4038 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:53:12.741  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:53:12.741  3987  4038 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:53:12.741  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:53:12.742  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.742  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.742  3987  4038 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf76fb8 not in the list
08-25 20:53:12.742  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.742  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
08-25 20:53:12.742  3987  4038 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:53:12.742  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.742  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.742  3987  4054 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-25 20:53:12.742  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.742  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.742  3987  4054 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-25 20:53:12.742  3987  4054 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-25 20:53:12.743  3987  3987 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-25 20:53:12.743  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:53:12.743  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:53:12.743  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.743  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
08-25 20:53:12.744  3987  4038 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-25 20:53:12.744  3987  4038 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 20:53:12.745  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 20:53:12.745  3987  4038 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 20:53:12.745  3987  4038 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:53:12.745  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:53:12.745  3987  4038 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:53:12.745  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:53:12.745  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.745  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.745  3987  4038 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf76fb8 not in the list
08-25 20:53:12.745  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.745  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
08-25 20:53:12.746  3987  4038 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:53:12.746  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.746  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.746  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.746  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.747  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:53:12.747  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:53:12.747  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.747  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
08-25 20:53:12.754  3987  4038 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:53:12.754  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:53:12.754  3987  4038 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:53:12.754  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:53:12.754  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.754  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.755  3987  4038 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf76fb8 not in the list
08-25 20:53:12.755  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.755  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
08-25 20:53:12.755  3987  4038 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:53:12.755  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.755  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.755  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.755  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.757  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:53:12.757  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:53:12.757  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.757  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
08-25 20:53:12.758  3987  4038 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:53:12.758  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:53:12.758  3987  4038 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:53:12.759  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:53:12.759  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.759  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.759  3987  4038 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf76fb8 not in the list
08-25 20:53:12.759  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.759  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
08-25 20:53:12.759  3987  4038 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:53:12.759  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.759  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.760  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:12.760  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:12.761  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:53:12.761  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:53:12.761  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:12.761  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb4d191 not in the list
08-25 20:53:12.763  3987  4038 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-25 20:53:12.763  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 20:53:12.763  3987  4038 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-25 20:53:12.763  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 20:53:12.763  3987  4038 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-25 20:53:12.763  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 20:53:12.766  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-25 20:53:12.766  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-25 20:53:12.767  3987  4038 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-25 20:53:12.767  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 20:53:12.767  3987  4038 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-25 20:53:12.767  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 20:53:12.767  3987  4038 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-25 20:53:12.768  3987  4038 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-25 20:53:12.769  3987  4038 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-25 20:53:12.769  3987  4038 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-25 20:53:12.769  3987  4038 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,08-25 20:53:12.770  3987  4038 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-25 20:53:12.770  3987  4038 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-25 20:53:12.770  3987  4038 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-25 20:53:12.771  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 20:53:12.771  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@466480b added. We now have 2 listener(s)
08-25 20:53:12.772  3987  4038 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 20:53:12.774  3987  4038 D BluetoothAdapter: enable(): BT is already enabled..!
08-25 20:53:12.774   876  1997 D WifiService: setWifiEnabled: true pid=3987, uid=10000
08-25 20:53:12.774   876  1997 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 20:53:12.776  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 20:53:12.776  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d0236e8 added. We now have 3 listener(s)
08-25 20:53:12.776  3987  4038 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 20:53:12.783  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 20:53:12.784  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@61c4101 added. We now have 4 listener(s)
08-25 20:53:12.784  3987  4038 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 20:53:12.786  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 20:53:12.786  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d9c2ba6 added. We now have 5 listener(s)
08-25 20:53:12.786  3987  4038 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 20:53:12.789   876  1522 D WifiService: setWifiEnabled: false pid=3987, uid=10000
08-25 20:53:12.789   876  1522 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 20:53:12.794  2687  2704 D BluetoothAdapterState: Current state: ON, message: 23
08-25 20:53:12.794  2687  2704 D BluetoothAdapterProperties: Setting state to 13
08-25 20:53:12.794  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 20:53:12.794  2687  2704 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-25 20:53:12.802  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 20:53:12.802  2687  2704 D BluetoothAdapterProperties: onBluetoothDisable()
08-25 20:53:12.804  2687  2704 I BluetoothAdapterState: Entering PendingCommandState
,08-25 20:53:12.806  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 20:53:12.807  3987  4038 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 20:53:12.807  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:53:12.807  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 20:53:12.807  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:53:12.807  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 20:53:12.807  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 20:53:12.807  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 20:53:12.807  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 20:53:12.807   876  1318 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-25 20:53:12.807   876  1318 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-25 20:53:12.807   876  1318 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-25 20:53:12.807   876  1318 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 20:53:12.808  2687  2709 D BluetoothAdapterProperties: Scan Mode:20
08-25 20:53:12.809  2687  2704 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-25 20:53:12.810  2687  2687 D BluetoothMapService: onReceive
08-25 20:53:12.810  2687  2687 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:53:12.810  2687  2687 D BluetoothMapService: STATE_TURNING_OFF
08-25 20:53:12.811  2687  2687 D BluetoothMapService: MAP Service closeService in
08-25 20:53:12.811  2687  2687 D BluetoothMapMasInstance0: MAP Service shutdown
08-25 20:53:12.811  2687  2687 D ObexServerSockets0: shutdown(block = true)
,08-25 20:53:12.812  2687  2687 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-25 20:53:12.812  2687  2687 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-25 20:53:12.812  2687  2865 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-25 20:53:12.813  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 20:53:12.813  3987  4038 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 20:53:12.813  2687  2877 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-25 20:53:12.813  3987  4038 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 20:53:12.814  2687  2876 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-25 20:53:12.817  2687  2687 I BtOppRfcommListener: stopping Accept Thread
08-25 20:53:12.817  2687  3609 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 20:53:12.817  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:53:12.819  2687  3609 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-25 20:53:12.820  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:53:12.822   876   889 I ActivityManager: Start proc 4057:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-25 20:53:12.822   876  2084 D DhcpClient: Clearing IP address
08-25 20:53:12.823   374   874 D CommandListener: Clearing all IP addresses on wlan0
08-25 20:53:12.824  3987  3987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 20:53:12.828   374   874 D CommandListener: Setting iface cfg
08-25 20:53:12.828  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:53:12.828  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:53:12.828  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 20:53:12.828  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:53:12.828  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 20:53:12.828  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 20:53:12.828  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 20:53:12.828  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 20:53:12.829   876  2094 D DhcpClient: Receive thread stopped
08-25 20:53:12.832  1508  2528 V NativeCrypto: Read error: ssl=0x9a77d000: I/O error during system call, Connection timed out
08-25 20:53:12.833  1508  2528 V NativeCrypto: SSL shutdown failed: ssl=0x9a77d000: I/O error during system call, Broken pipe
08-25 20:53:12.835  3987  3987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:53:12.835  3987  3987 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 20:53:12.836   876  1986 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-25 20:53:12.837   876  2078 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
,08-25 20:53:12.838  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:53:12.839   876  2078 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-25 20:53:12.839   876  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
08-25 20:53:12.840   876  1320 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-25 20:53:12.840  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:53:12.840  2687  2687 D HeadsetService: Received stop request...Stopping profile...
08-25 20:53:12.841   876  1320 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-25 20:53:12.842  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 20:53:12.843  1362  1373 D BluetoothHeadset: Proxy object disconnected
08-25 20:53:12.843   876   876 D BluetoothHeadset: Proxy object disconnected
08-25 20:53:12.843   876   876 D BluetoothHeadset: Proxy object disconnected
08-25 20:53:12.843   876  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-25 20:53:12.844   876  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-25 20:53:12.844  1943  2168 D BluetoothHeadset: Proxy object disconnected
,08-25 20:53:12.845   876   876 D BluetoothHeadset: Proxy object disconnected
08-25 20:53:12.846   876  1318 D WifiStateMachine: Start Disconnecting Watchdog 1
08-25 20:53:12.846   397   397 E Parcel  : Reading a NULL string not supported here.
08-25 20:53:12.846   876  1318 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-25 20:53:12.847  2687  2687 D A2dpService: Received stop request...Stopping profile...
08-25 20:53:12.847  2687  2870 D A2dpStateMachine: Exit Disconnected: -1
08-25 20:53:12.849   876   876 D BluetoothA2dp: Proxy object disconnected
,08-25 20:53:12.850  2687  2687 D HidService: Received stop request...Stopping profile...
08-25 20:53:12.851  2687  2687 D HidService: Stopping Bluetooth HidService
08-25 20:53:12.853  2687  2687 D HealthService: Received stop request...Stopping profile...
08-25 20:53:12.854  2687  2687 D PanService: Received stop request...Stopping profile...
08-25 20:53:12.856  2687  2687 D BluetoothMapService: Received stop request...Stopping profile...
08-25 20:53:12.856  2687  2687 D BluetoothMapService: stop()
,08-25 20:53:12.856  2687  2687 D BluetoothMapAppObserver: deinitObservers()
08-25 20:53:12.856  2687  2687 D BluetoothMapAppObserver: removeReceiver()
08-25 20:53:12.858  2687  2687 V BluetoothAdapterState: isTurningOff()=true
08-25 20:53:12.858  2687  2687 V BluetoothAdapterState: isTurningOn()=false
08-25 20:53:12.858  2687  2687 V BluetoothAdapterState: isBleTurningOn()=false
08-25 20:53:12.858  2687  2687 V BluetoothAdapterState: isBleTurningOff()=false
08-25 20:53:12.858   374   874 D CommandListener: Clearing all IP addresses on wlan0
,08-25 20:53:12.860  1362  1362 D HeadsetProfile: Bluetooth service disconnected
08-25 20:53:12.860   876  1320 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-25 20:53:12.860  1362  1362 D BluetoothA2dp: Proxy object disconnected
08-25 20:53:12.860  1362  1362 D BluetoothInputDevice: Proxy object disconnected
08-25 20:53:12.860  1362  1362 D HidProfile: Bluetooth service disconnected
,08-25 20:53:12.860  2687  2687 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-25 20:53:12.861  2687  2709 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-25 20:53:12.861  2687  2846 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 20:53:12.861  2687  2687 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 20:53:12.861  2687  2846 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-25 20:53:12.861  2687  2846 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 20:53:12.861  2687  2709 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-25 20:53:12.864   876  1318 D WifiConfigStore: Retrieve network priorities after PNO.
08-25 20:53:12.868  3987  3987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:53:12.868  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:53:12.868  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:53:12.868  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 20:53:12.868  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 20:53:12.868  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 20:53:12.868  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 20:53:12.868  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 20:53:12.868  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 20:53:12.868  3987  3987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:53:12.868  3987  3987 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 20:53:12.869  2687  2687 V BluetoothAdapterState: isTurningOff()=true
,08-25 20:53:12.869  2687  2687 V BluetoothAdapterState: isTurningOn()=false
08-25 20:53:12.869  2687  2687 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 20:53:12.869  2687  2687 V BluetoothAdapterState: isBleTurningOff()=false
08-25 20:53:12.870  3987  3987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:53:12.870  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:53:12.870  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:53:12.870  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 20:53:12.870  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 20:53:12.870  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 20:53:12.870  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 20:53:12.870  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 20:53:12.870  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 20:53:12.871  3987  3987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:53:12.871  3987  3987 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 20:53:12.872  2029  2326 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:53:12.873  2687  2709 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-25 20:53:12.873  2687  2846 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 20:53:12.874  2687  2687 V BluetoothAdapterState: isTurningOff()=true
08-25 20:53:12.874  2687  2687 V BluetoothAdapterState: isTurningOn()=false
08-25 20:53:12.874  2687  2687 V BluetoothAdapterState: isBleTurningOn()=false
08-25 20:53:12.874  2687  2687 V BluetoothAdapterState: isBleTurningOff()=false
08-25 20:53:12.874  2687  2687 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-25 20:53:12.874  2687  2709 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-25 20:53:12.874  2687  2846 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 20:53:12.874  2687  2687 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 20:53:12.874  2687  2846 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 20:53:12.874  2687  2846 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 20:53:12.874  2687  2687 V BluetoothAdapterState: isTurningOff()=true
08-25 20:53:12.874  2687  2846 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 20:53:12.874  2687  2687 V BluetoothAdapterState: isTurningOn()=false
,08-25 20:53:12.874  2687  2846 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 20:53:12.874  2687  2687 V BluetoothAdapterState: isBleTurningOn()=false
08-25 20:53:12.874  2687  2687 V BluetoothAdapterState: isBleTurningOff()=false
08-25 20:53:12.875  2687  2687 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-25 20:53:12.875  2687  2709 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-25 20:53:12.875  2687  2687 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-25 20:53:12.876  2687  2687 V BluetoothAdapterState: isTurningOff()=true
08-25 20:53:12.876  2687  2687 V BluetoothAdapterState: isTurningOn()=false
08-25 20:53:12.876  2687  2687 V BluetoothAdapterState: isBleTurningOn()=false
08-25 20:53:12.876  2687  2687 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 20:53:12.876  2687  2687 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-25 20:53:12.876  2687  2687 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-25 20:53:12.876   876  1318 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-25 20:53:12.876  1362  1362 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-25 20:53:12.877  1362  1362 D PanProfile: Bluetooth service disconnected
08-25 20:53:12.877  1362  1362 D BluetoothMap: Proxy object disconnected
08-25 20:53:12.877  1362  1362 D MapProfile: Bluetooth service disconnected
,08-25 20:53:12.878  2687  2687 D BluetoothMapService: MAP Service closeService in
08-25 20:53:12.878  2687  2687 V BluetoothAdapterState: isTurningOff()=true
08-25 20:53:12.878  2687  2687 V BluetoothAdapterState: isTurningOn()=false
08-25 20:53:12.878  2687  2687 V BluetoothAdapterState: isBleTurningOn()=false
08-25 20:53:12.878  2687  2687 V BluetoothAdapterState: isBleTurningOff()=false
08-25 20:53:12.878  2687  2687 D BluetoothMapService: cleanup()
08-25 20:53:12.878  2687  2687 D BluetoothMapService: MAP Service closeService in
,08-25 20:53:12.878  2687  2704 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-25 20:53:12.879  2687  2704 D BluetoothAdapterProperties: Setting state to 15
08-25 20:53:12.879  2687  2704 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-25 20:53:12.879  2687  2704 I BluetoothAdapterState: Entering BleOnState
08-25 20:53:12.880  1362  1373 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-25 20:53:12.880   876   893 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 20:53:12.880  1362  2088 D BluetoothPbap: onBluetoothStateChange: up=false
08-25 20:53:12.882   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 20:53:12.882  1943  2168 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 20:53:12.882  1362  1379 D BluetoothPan: onBluetoothStateChange on: false
08-25 20:53:12.882   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 20:53:12.882  1362  1373 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-25 20:53:12.883  1362  2088 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-25 20:53:12.883   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 20:53:12.883  1362  1379 D BluetoothMap: onBluetoothStateChange: up=false
,08-25 20:53:12.884  2687  2704 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-25 20:53:12.884  2687  2704 D BluetoothAdapterProperties: Setting state to 16
08-25 20:53:12.884  2687  2704 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-25 20:53:12.884  2687  2704 D BluetoothAdapterProperties: onBleDisable
08-25 20:53:12.884  2687  2704 I BluetoothAdapterState: Entering PendingCommandState
08-25 20:53:12.885  2687  2705 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-25 20:53:12.886  2687  2709 D BluetoothAdapterProperties: Scan Mode:20
08-25 20:53:12.886  2687  2846 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-25 20:53:12.886  2687  2846 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 20:53:12.887  3987  3987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 20:53:12.887  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:53:12.887  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:53:12.887  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 20:53:12.887  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 20:53:12.887  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 20:53:12.887  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 20:53:12.887  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 20:53:12.887  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 20:53:12.894  3987  3987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:53:12.894  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:53:12.894  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:53:12.894  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 20:53:12.894  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 20:53:12.894  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 20:53:12.894  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 20:53:12.894  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 20:53:12.894  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 20:53:12.895  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:53:12.896  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 20:53:12.916   876   885 I art     : Background partial concurrent mark sweep GC freed 47304(2MB) AllocSpace objects, 13(348KB) LOS objects, 33% free, 29MB/44MB, paused 2.138ms total 120.366ms
,08-25 20:53:12.918   374   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 20:53:12.936  4057  4057 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-25 20:53:12.937   374   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 20:53:12.938   876  1320 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-25 20:53:12.938   876  1320 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-25 20:53:12.940   876   893 D Tethering: MasterInitialState.processMessage what=3
08-25 20:53:12.942  3611  3611 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@93f22e8 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-25 20:53:12.942  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:53:12.943  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 20:53:12.954  4057  4057 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 20:53:12.959  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 20:53:12.960   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@82956fd:true
,08-25 20:53:12.971   876  1958 I ActivityManager: Start proc 4078:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-25 20:53:12.979  4057  4057 D LocalBluetoothProfileManager: Adding local MAP profile
,08-25 20:53:12.981  4057  4057 D BluetoothMap: Create BluetoothMap proxy object
,08-25 20:53:12.988  4057  4057 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-25 20:53:12.992   374   874 E Netd    : netlink response contains error (No such file or directory)
08-25 20:53:12.993   876  1320 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-25 20:53:12.993   876  1320 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-25 20:53:13.002  4078  4078 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-25 20:53:13.005  4057  4057 D DockEventReceiver: finishStartingService: stopping service
,08-25 20:53:13.009   876  1522 I ActivityManager: Killing 3193:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-25 20:53:13.097  2687  2709 I bt_hci  : shut_down
,08-25 20:53:13.098  2687  2715 D bt_hwcfg: hw_epilog_process
,08-25 20:53:13.099  2687  2715 I bt_vendor: low_power_mode_cb
,08-25 20:53:13.128  2687  2715 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-25 20:53:13.128  2687  2715 I bt_vendor: epilog_cb
,08-25 20:53:13.128  2687  2715 I bt_hci  : epilog_finished_callback
,08-25 20:53:13.137  2687  2709 I bt_hci_h4: hal_close
,08-25 20:53:13.137  2687  2709 I bt_userial_vendor: device fd = 51 close
,08-25 20:53:13.180  4078  4078 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 20:53:13.180  4078  4078 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at java.io.File.exists(File.java:361)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 20:53:13.180  4078  4078 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 20:53:13.180  4078  4078 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 20:53:13.180  4078  4078 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 20:53:13.181  4078  4078 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.base.app.,a.a(PG:244)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 20:53:13.181  4078  4078 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.r.e.b(PG:170)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityTh,read.java)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 20:53:13.181  4078  4078 D StrictMode: StrictMode policy violation; ~duration=88 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.r.k.d(PG:583)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.r.e.b(PG:170)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 20:53:13.181  4078  4078 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at java.io.File.exists(File.java:361)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 20:53:13.181  4078  4078 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at java.io.File.exists(File.java:361)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 20:53:13.181  4078  4078 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 20:53:13.181  4078  4078 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 20:53:13.214   876  1986 I ActivityManager: Start proc 4109:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
08-25 20:53:13.215   876  1986 I ActivityManager: Killing 3611:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-25 20:53:13.241  3987  3987 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 20:53:13.301  2687  2705 D bt_stack_manager: event_shut_down_stack finished.
08-25 20:53:13.301  2687  2704 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-25 20:53:13.305  2687  2704 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-25 20:53:13.305  2687  2687 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 20:53:13.306  2687  2687 D BtGatt.GattService: Received stop request...Stopping profile...
08-25 20:53:13.307  2687  2687 D BtGatt.GattService: stop()
08-25 20:53:13.307  2687  2687 D BtGatt.AdvertiseManager: advertise clients cleared
,08-25 20:53:13.312  2687  2687 V BluetoothAdapterState: isTurningOff()=false
08-25 20:53:13.312  2687  2687 V BluetoothAdapterState: isTurningOn()=false
,08-25 20:53:13.312  2687  2687 V BluetoothAdapterState: isBleTurningOn()=false
08-25 20:53:13.312  2687  2687 V BluetoothAdapterState: isBleTurningOff()=true
,08-25 20:53:13.313  2687  2704 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-25 20:53:13.313  2687  2704 D BluetoothAdapterProperties: Setting state to 10
08-25 20:53:13.313  2687  2704 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-25 20:53:13.314  4109  4109 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
08-25 20:53:13.315  2687  2704 I BluetoothAdapterState: Entering OffState
,08-25 20:53:13.316   876   893 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-25 20:53:13.338  2687  2687 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-25 20:53:13.338  2687  2687 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-25 20:53:13.338  2687  2705 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-25 20:53:13.340  2687  2705 D bt_stack_manager: event_clean_up_stack finished.
,08-25 20:53:13.340  2687  2687 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-25 20:53:13.347  2687  2687 I art     : System.exit called, status: 0
,08-25 20:53:13.348  2687  2687 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-25 20:53:13.412   876  1986 I ActivityManager: Process com.android.bluetooth (pid 2687) has died
,08-25 20:53:13.440  4109  4109 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-25 20:53:13.464  4057  4057 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 20:53:13.480  4078  4106 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-25 20:53:13.498   876  1522 I ActivityManager: Start proc 4137:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-25 20:53:13.501  4057  4057 D DockEventReceiver: finishStartingService: stopping service
,08-25 20:53:13.529   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c4217dd:true
,08-25 20:53:13.576  4137  4137 D AdapterServiceConfig: Adding HeadsetService
08-25 20:53:13.576  4137  4137 D AdapterServiceConfig: Adding A2dpService
08-25 20:53:13.576  4137  4137 D AdapterServiceConfig: Adding HidService
08-25 20:53:13.576  4137  4137 D AdapterServiceConfig: Adding HealthService
08-25 20:53:13.576  4137  4137 D AdapterServiceConfig: Adding PanService
08-25 20:53:13.576  4137  4137 D AdapterServiceConfig: Adding GattService
08-25 20:53:13.576  4137  4137 D AdapterServiceConfig: Adding BluetoothMapService
,08-25 20:53:13.578   876  1986 I ActivityManager: Killing 3656:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-25 20:53:13.625  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 20:53:13.658  1717  1717 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-25 20:53:13.665  1717  1717 D SystemUpdateService: onCreate
,08-25 20:53:13.669  1717  1717 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-25 20:53:13.672  1717  4149 I SystemUpdateService: active receiver: enabled
,08-25 20:53:13.676  1717  4149 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-25 20:53:13.678  1717  4149 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,08-25 20:53:13.678  1717  4149 I SystemUpdateService: now status is 0 (complete)
08-25 20:53:13.678  1717  4149 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-25 20:53:13.678  1717  4149 I SystemUpdateService: file has been verified
08-25 20:53:13.679  1717  4149 I SystemUpdateService: OTA package size = 12249756
,08-25 20:53:13.682  1717  4149 I SystemUpdateService: showing system update notification
,08-25 20:53:13.692  1717  1717 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-25 20:53:13.697  1717  2506 I iu.UploadsManager: num queued entries: 0
,08-25 20:53:13.699  1717  1717 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-25 20:53:13.700  1717  1717 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-25 20:53:13.702  1717  1717 D SystemUpdateService: onDestroy
,08-25 20:53:13.702  1717  2506 I iu.UploadsManager: num updated entries: 0
,08-25 20:53:13.703  1717  2506 I iu.SyncManager: NEXT; no task
,08-25 20:53:13.717   876  1956 I ActivityManager: Start proc 4151:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-25 20:53:13.755  4151  4151 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-25 20:53:13.757  4151  4151 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-25 20:53:13.767  4151  4151 D SprintDMHelper: simOperator: 
,08-25 20:53:13.767  4151  4151 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-25 20:53:13.779   876  1522 I ActivityManager: Start proc 4163:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-25 20:53:13.779   876  1522 I ActivityManager: Killing 1703:android.process.acore/u0a5 (adj 15): empty #17
,08-25 20:53:13.911   876  1986 I ActivityManager: Start proc 4178:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-25 20:53:13.914  2900  4177 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-25 20:53:13.917   876  1715 I ActivityManager: Killing 3844:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-25 20:53:13.978  4178  4178 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-25 20:53:14.031  4178  4178 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-25 20:53:14.031  4178  4178 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-25 20:53:14.031  4178  4178 I GAv4    :   adb logcat -s GAv4
,08-25 20:53:14.043  4178  4178 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-25 20:53:14.050  4178  4178 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-25 20:53:14.080  4178  4195 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-25 20:53:14.168  4178  4178 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-25 20:53:14.210  4178  4178 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-25 20:53:14.217  4178  4178 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 6989-6991)
,08-25 20:53:14.217  4178  4178 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-25 20:53:14.229  4178  4178 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6f51618}
,08-25 20:53:14.230  4178  4178 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-25 20:53:14.230  4178  4178 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-25 20:53:14.236  4178  4178 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-25 20:53:14.238  4178  4178 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-25 20:53:14.254  4178  4178 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-25 20:53:14.265  4178  4178 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-25 20:53:14.266  4178  4178 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-25 20:53:14.266  4178  4178 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-25 20:53:14.266  4178  4178 I Adreno  : Build Date                       : 10/20/15
08-25 20:53:14.266  4178  4178 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-25 20:53:14.266  4178  4178 I Adreno  : Local Branch                     : M14
08-25 20:53:14.266  4178  4178 I Adreno  : Remote Branch                    : 
08-25 20:53:14.266  4178  4178 I Adreno  : Remote Branch                    : 
08-25 20:53:14.266  4178  4178 I Adreno  : Reconstruct Branch               : 
,08-25 20:53:14.321  4178  4178 I NSApplication: Starting up...
,08-25 20:53:14.330  4178  4224 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-25 20:53:14.361   876  1956 I ActivityManager: Start proc 4229:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-25 20:53:14.362   876  1956 I ActivityManager: Killing 3859:com.android.musicfx/u0a18 (adj 15): empty #17
,08-25 20:53:14.482  4229  4229 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-25 20:53:14.687   876   887 I ActivityManager: Killing 2222:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-25 20:53:15.816   876   886 D WifiService: setWifiEnabled: true pid=3987, uid=10000
08-25 20:53:15.816   876   886 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 20:53:15.829   876  1318 D WifiConfigStore: Loading config and enabling all networks 
,08-25 20:53:15.839  3987  3987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 20:53:15.839  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:53:15.839  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:53:15.839  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 20:53:15.839  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:53:15.839  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 20:53:15.839  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 20:53:15.839  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 20:53:15.839  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 20:53:15.840  3987  3987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 20:53:15.840  3987  3987 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 20:53:15.842  3987  3987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:53:15.842  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:53:15.842  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:53:15.842  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 20:53:15.842  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:53:15.842  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 20:53:15.842  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 20:53:15.842  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 20:53:15.842  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 20:53:15.843  3987  3987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 20:53:15.843  3987  3987 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 20:53:15.852   876  1318 D WifiConfigStore: loaded 0 passpoint configs
,08-25 20:53:15.853   876  1318 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-25 20:53:15.854   876  1318 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-25 20:53:15.855   876  1318 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-25 20:53:15.856   876  1318 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-25 20:53:15.856   876  1318 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-25 20:53:15.856   876  1318 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-25 20:53:15.872   374   874 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-25 20:53:15.874   374   874 D CommandListener: Setting iface cfg
08-25 20:53:15.874   876  1318 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=10.25 rxSuccessRate=14.50 delta 1000 -> 994
08-25 20:53:15.875   876  1317 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '129 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 129 Failed to set address (No such device)'
,08-25 20:53:15.875   876  1317 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-25 20:53:15.883   876  1318 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-25 20:53:15.883   876  1318 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 20:53:15.890   876  1318 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-25 20:53:15.918   876  1317 D WifiNative-HAL: p2pGetDeviceAddress
,08-25 20:53:15.918   876  1317 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-25 20:53:15.948   876  1318 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-25 20:53:15.950  1468  1468 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-25 20:53:16.373  1468  1468 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-25 20:53:16.419  1468  1468 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-25 20:53:16.420  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-25 20:53:16.428   876  1318 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 20:53:16.442   876  1318 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-25 20:53:16.442   876  1318 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 20:53:16.442   876  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-25 20:53:16.463   876  1318 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 20:53:16.475   374   874 D CommandListener: Setting iface cfg
08-25 20:53:16.476   876  1318 D WifiStateMachine: Start Dhcp Watchdog 2
,08-25 20:53:16.501   876  1320 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-25 20:53:16.508   876  1318 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-25 20:53:16.533   876  4255 D DhcpClient: Receive thread started
,08-25 20:53:16.620   876  1318 E native  : do suspend false
,08-25 20:53:16.641   876  2084 D DhcpClient: Broadcasting DHCPDISCOVER
,08-25 20:53:16.657   876  4255 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172684, domain null
,08-25 20:53:16.659   876  2084 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172684 seconds
,08-25 20:53:16.662   876  2084 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-25 20:53:16.676   876  4255 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-25 20:53:16.677   876  2084 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-25 20:53:16.682   374   874 D CommandListener: Setting iface cfg
,08-25 20:53:16.693   876  1318 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-25 20:53:16.694   876  2084 D DhcpClient: Scheduling renewal in 86399s
,08-25 20:53:16.709   876  1318 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-25 20:53:16.710   876  1318 D WifiConfigStore: No blacklist allowed without epno enabled
08-25 20:53:16.711   876  1320 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-25 20:53:16.711   876  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-25 20:53:16.714   876  1320 D ConnectivityService: Adding iface wlan0 to network 101
,08-25 20:53:16.721   876  1318 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-25 20:53:16.769   876  1320 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-25 20:53:16.769   876  1320 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-25 20:53:16.770   876  1320 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-25 20:53:16.771   876  1320 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-25 20:53:16.772   876  1320 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-25 20:53:16.778   876  1320 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-25 20:53:16.783   876  1320 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-25 20:53:16.784   876  1320 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-25 20:53:16.784   876  1320 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-25 20:53:16.784   876  1320 D ConnectivityService:    accepting network in place of null
,08-25 20:53:16.785   876  1318 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-25 20:53:16.786   876  1320 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-25 20:53:16.786   876  1318 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-25 20:53:16.791   876  4254 D NetlinkSocketObserver: NeighborEvent{elapsedMs=139566, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-25 20:53:16.814   374   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 20:53:16.846   374   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 20:53:16.853   876  1320 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-25 20:53:16.853   876  1320 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 20:53:16.858   876  4253 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.174,2a00:1450:4001:814::200e
,08-25 20:53:16.859   876  1320 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-25 20:53:16.860   876   893 D Tethering: MasterInitialState.processMessage what=3
,08-25 20:53:16.880  3987  3987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 20:53:16.880  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:53:16.880  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:53:16.880  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 20:53:16.880  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:53:16.880  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 20:53:16.880  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 20:53:16.880  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 20:53:16.880  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 20:53:16.881  3987  3987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:53:16.881  3987  3987 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 20:53:16.883  3987  3987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 20:53:16.883  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:53:16.883  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:53:16.883  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 20:53:16.883  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:53:16.883  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 20:53:16.883  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e,
08-25 20:53:16.883  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 20:53:16.883  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 20:53:16.883  3987  3987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 20:53:16.884  3987  3987 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 20:53:16.892  1717  1717 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-25 20:53:16.895  1717  1717 D SystemUpdateService: onCreate
,08-25 20:53:16.899  1717  1717 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-25 20:53:16.902  1717  4266 I SystemUpdateService: active receiver: enabled
,08-25 20:53:16.911  1717  4266 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-25 20:53:16.913  1717  4266 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,08-25 20:53:16.914  1717  4266 I SystemUpdateService: now status is 0 (complete)
08-25 20:53:16.914  1717  4266 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-25 20:53:16.914  1717  4266 I SystemUpdateService: file has been verified
08-25 20:53:16.914  1717  4266 I SystemUpdateService: OTA package size = 12249756
,08-25 20:53:16.917  1717  1717 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-25 20:53:16.922  1717  4266 I SystemUpdateService: showing system update notification
,08-25 20:53:16.923  1717  2506 I iu.UploadsManager: num queued entries: 0
,08-25 20:53:16.924  1717  4270 I MDM     : [177] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-25 20:53:16.924  1717  4270 W BaseAppContext: Using Auth Proxy for data requests.
,08-25 20:53:16.925  1717  4270 V GoogleAuthProtoRequest: [177] a.<init>: mAccountName set to: thalitester@gmail.com
,08-25 20:53:16.926  1717  2506 I iu.UploadsManager: num updated entries: 0
,08-25 20:53:16.929  1717  1717 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-25 20:53:16.931  1717  1717 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-25 20:53:16.931  1717  2506 I iu.SyncManager: NEXT; no task
,08-25 20:53:16.935  4151  4151 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-25 20:53:16.935  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 20:53:16.937  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-25 20:53:16.939  1717  1717 D SystemUpdateService: onDestroy
08-25 20:53:16.940   876  4253 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 18:53:16 GMT], X-Android-Received-Millis=[1472151196940], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472151196910]}
,08-25 20:53:16.941   876  1320 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-25 20:53:16.941   876  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-25 20:53:16.941   876  1320 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-25 20:53:16.942   876  1320 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-25 20:53:16.946  4151  4151 D SprintDMHelper: simOperator: 
,08-25 20:53:16.946  4151  4151 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-25 20:53:16.972  1508  2042 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-25 20:53:16.972  1508  2042 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-25 20:53:16.972  1508  2042 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 20:53:16.972  1508  2042 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 20:53:16.989  1717  4270 E MDM     : [177] SitrepService.a: Error sending sitrep.
,08-25 20:53:17.070  2900  4273 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-25 20:53:17.852   876  1320 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-25 20:53:18.577   876   886 I ActivityManager: Killing 3882:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-25 20:53:18.822   876  1956 D WifiService: setWifiEnabled: false pid=3987, uid=10000
,08-25 20:53:18.822   876  1956 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 20:53:18.855  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-25 20:53:18.860   876  1318 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-25 20:53:18.860   876  1318 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-25 20:53:18.860   876  1318 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-25 20:53:18.860   876  1318 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 20:53:18.885   374   874 D CommandListener: Clearing all IP addresses on wlan0
,08-25 20:53:18.885   876  2084 D DhcpClient: Clearing IP address
,08-25 20:53:18.890   374   874 D CommandListener: Setting iface cfg
,08-25 20:53:18.894  1508  4279 V NativeCrypto: Read error: ssl=0x9a77d000: I/O error during system call, Connection timed out
,08-25 20:53:18.899  1508  4279 V NativeCrypto: SSL shutdown failed: ssl=0x9a77d000: I/O error during system call, Broken pipe
,08-25 20:53:18.904   876  4255 D DhcpClient: Receive thread stopped
,08-25 20:53:18.905   876  1998 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,08-25 20:53:18.906   876  4253 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,08-25 20:53:18.907   876  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-25 20:53:18.907   876  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-25 20:53:18.915   397   397 E Parcel  : Reading a NULL string not supported here.
,08-25 20:53:18.919   876  1320 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-25 20:53:18.919   876  4253 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,08-25 20:53:18.921   876  1318 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-25 20:53:18.924   876  1318 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-25 20:53:18.955   374   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 20:53:18.986   374   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 20:53:18.987   876  1320 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-25 20:53:18.987   876  1320 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 20:53:18.987   374   874 D CommandListener: Clearing all IP addresses on wlan0
,08-25 20:53:18.995   876   893 D Tethering: MasterInitialState.processMessage what=3
,08-25 20:53:19.001  3987  3987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 20:53:19.002  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:53:19.002  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:53:19.002  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 20:53:19.002  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:53:19.002  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 20:53:19.002  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 20:53:19.002  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 20:53:19.002  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 20:53:19.002  3987  3987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 20:53:19.002  3987  3987 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 20:53:19.003  3987  3987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:53:19.003  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:53:19.003  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:53:19.003  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 20:53:19.003  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:53:19.003  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 20:53:19.003  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 20:53:19.003  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 20:53:19.003  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 20:53:19.003  3987  3987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:53:19.003  3987  3987 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 20:53:19.007   876  1318 D WifiConfigStore: Retrieve network priorities after PNO.
08-25 20:53:19.011   876  1318 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-25 20:53:19.015  3987  3987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:53:19.015  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:53:19.015  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:53:19.015  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 20:53:19.015  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 20:53:19.015  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 20:53:19.015  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 20:53:19.015  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 20:53:19.015  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 20:53:19.015  3987  3987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:53:19.016  3987  3987 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 20:53:19.018  1717  1717 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-25 20:53:19.019  3987  3987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:53:19.019  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:53:19.019  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:53:19.019  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 20:53:19.019  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 20:53:19.019  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 20:53:19.019  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 20:53:19.019  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 20:53:19.019  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 20:53:19.019  3987  3987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:53:19.019  3987  3987 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 20:53:19.020  2029  2326 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 20:53:19.023  1717  1717 D SystemUpdateService: onCreate
,08-25 20:53:19.031  1717  1717 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-25 20:53:19.040  1717  1717 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-25 20:53:19.049  1717  1717 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-25 20:53:19.050  1717  1717 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-25 20:53:19.052  4151  4151 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-25 20:53:19.056  4151  4151 D SprintDMHelper: simOperator: 
,08-25 20:53:19.056  4151  4151 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-25 20:53:19.071   374   874 E Netd    : netlink response contains error (No such file or directory)
,08-25 20:53:19.072  1717  2506 I iu.UploadsManager: num queued entries: 0
08-25 20:53:19.072  1717  2506 I iu.UploadsManager: num updated entries: 0
08-25 20:53:19.072   876  1320 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-25 20:53:19.073   876  1320 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-25 20:53:19.073  1717  2506 I iu.SyncManager: NEXT; no task
,08-25 20:53:19.075  2900  4294 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-25 20:53:19.080  1717  4290 I SystemUpdateService: active receiver: enabled
,08-25 20:53:19.089  1717  4290 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-25 20:53:19.098  4178  4178 I art     : Waiting for a blocking GC DisableMovingGc
,08-25 20:53:19.098  1717  4290 I SystemUpdateService: network: null; metered: false; mobile allowed: false
08-25 20:53:19.098  1717  4290 I SystemUpdateService: now status is 0 (complete)
08-25 20:53:19.099  1717  4290 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-25 20:53:19.099  1717  4290 I SystemUpdateService: file has been verified
,08-25 20:53:19.101  4178  4178 I art     : Starting a blocking GC DisableMovingGc
,08-25 20:53:19.107  1717  4290 I SystemUpdateService: OTA package size = 12249756
,08-25 20:53:19.136  1717  4290 I SystemUpdateService: showing system update notification
,08-25 20:53:19.144  1717  1717 D SystemUpdateService: onDestroy
,08-25 20:53:21.859   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b338d4:true
,08-25 20:53:21.859  4137  4137 D BluetoothAdapterState: make() - Creating AdapterState
,08-25 20:53:21.865  4137  4137 I bt_bluedroid: init
,08-25 20:53:21.865  4137  4297 I BluetoothAdapterState: Entering OffState
,08-25 20:53:21.871  4137  4298 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-25 20:53:21.872  4137  4298 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-25 20:53:21.872  4137  4298 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-25 20:53:21.872  4137  4298 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-25 20:53:21.874  4137  4137 I bt_bluedroid: get_profile_interface socket
,08-25 20:53:21.876  4137  4137 I bt_bluedroid: get_profile_interface sdp
,08-25 20:53:21.880  4137  4301 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-25 20:53:21.884  4137  4148 I bt_bluedroid: config_hci_snoop_log
,08-25 20:53:21.884  4137  4301 D BluetoothAdapterProperties: Name is: Nexus 6
,08-25 20:53:21.885   876   893 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-25 20:53:21.891  4137  4297 D BluetoothAdapterState: Current state: OFF, message: 0
,08-25 20:53:21.891  4137  4297 D BluetoothAdapterProperties: Setting state to 14
,08-25 20:53:21.891  4137  4297 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-25 20:53:21.893  4137  4297 D BluetoothBondStateMachine: make
,08-25 20:53:21.895  4137  4302 I BluetoothBondStateMachine: StableState(): Entering Off State
08-25 20:53:21.898  4137  4297 I BluetoothAdapterState: Entering PendingCommandState
08-25 20:53:21.901  4137  4137 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-25 20:53:21.908  4137  4137 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04b20e
,08-25 20:53:21.909  4137  4137 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 20:53:21.909  4137  4137 D BtGatt.GattService: Received start request. Starting profile...
08-25 20:53:21.910  4137  4137 D BtGatt.GattService: start()
08-25 20:53:21.910  4137  4137 I bt_bluedroid: get_profile_interface gatt
,08-25 20:53:21.911  4137  4137 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04b20e
08-25 20:53:21.911  4137  4137 D BtGatt.AdvertiseManager: advertise manager created
,08-25 20:53:21.916  4137  4137 V BluetoothAdapterState: isTurningOff()=false
,08-25 20:53:21.916  4137  4137 V BluetoothAdapterState: isTurningOn()=false
08-25 20:53:21.916  4137  4137 V BluetoothAdapterState: isBleTurningOn()=true
08-25 20:53:21.916  4137  4137 V BluetoothAdapterState: isBleTurningOff()=false
08-25 20:53:21.917  4137  4297 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-25 20:53:21.917  4137  4297 I bt_bluedroid: enable
,08-25 20:53:21.917  4137  4298 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-25 20:53:21.918  4137  4298 I bt_hci  : start_up
,08-25 20:53:21.924  4137  4298 I bt_vendor: alloc value 0xb39e9189
,08-25 20:53:21.924  4137  4298 I bt_vendor: init
08-25 20:53:21.924  4137  4298 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-25 20:53:21.924  4137  4298 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-25 20:53:22.039  4137  4298 D bt_hci  : start_up starting async portion
,08-25 20:53:22.040  4137  4305 I bt_hci  : event_finish_startup
08-25 20:53:22.040  4137  4305 I bt_hci_h4: hal_open
08-25 20:53:22.040  4137  4305 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-25 20:53:22.046  4137  4305 I bt_userial_vendor: device fd = 51 open
,08-25 20:53:22.075  4137  4305 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-25 20:53:22.107  4137  4305 D bt_hwcfg: Chipset BCM4354A2
,08-25 20:53:22.108  4137  4305 D bt_hwcfg: Target name = [BCM4354A2]
,08-25 20:53:22.108  4137  4305 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-25 20:53:22.775  4137  4305 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-25 20:53:22.777  4137  4305 D bt_hwcfg: Settlement delay -- 100 ms
08-25 20:53:22.777  4137  4305 I bt_hwcfg: Setting fw settlement delay to 100 
,08-25 20:53:22.893  4137  4305 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-25 20:53:22.895  4137  4305 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-25 20:53:22.924  4137  4305 I bt_hwcfg: vendor lib fwcfg completed
,08-25 20:53:22.924  4137  4305 I bt_vendor: firmware callback
,08-25 20:53:22.924  4137  4305 I bt_hci  : firmware_config_callback
,08-25 20:53:22.935  4137  4307 I bt_btu  : btu_task pending for preload complete event
,08-25 20:53:22.935  4137  4307 I bt_btu_task: Bluetooth chip preload is complete
,08-25 20:53:22.936  4137  4307 I bt_btu  : btu_task received preload complete event
,08-25 20:53:22.947  4137  4307 I         : BTE_InitTraceLevels -- TRC_HCI
08-25 20:53:22.947  4137  4307 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-25 20:53:22.947  4137  4307 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-25 20:53:22.948  4137  4307 I         : BTE_InitTraceLevels -- TRC_AVDT
08-25 20:53:22.948  4137  4307 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-25 20:53:22.948  4137  4307 I         : BTE_InitTraceLevels -- TRC_A2D
08-25 20:53:22.949  4137  4307 I         : BTE_InitTraceLevels -- TRC_BNEP
08-25 20:53:22.949  4137  4307 I         : BTE_InitTraceLevels -- TRC_BTM
,08-25 20:53:22.949  4137  4307 I         : BTE_InitTraceLevels -- TRC_GAP
,08-25 20:53:22.949  4137  4307 I         : BTE_InitTraceLevels -- TRC_PAN
,08-25 20:53:22.950  4137  4307 I         : BTE_InitTraceLevels -- TRC_SDP
08-25 20:53:22.950  4137  4307 I         : BTE_InitTraceLevels -- TRC_GATT
08-25 20:53:22.950  4137  4307 I         : BTE_InitTraceLevels -- TRC_SMP
08-25 20:53:22.950  4137  4307 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-25 20:53:22.951  4137  4307 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-25 20:53:23.083  4137  4307 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3966d9d
,08-25 20:53:23.084  4137  4307 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3966d9d 
,08-25 20:53:23.096  4137  4301 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-25 20:53:23.097  4137  4301 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-25 20:53:23.099  4137  4301 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-25 20:53:23.103  4137  4301 D BluetoothAdapterProperties: Name is: Nexus 6
,08-25 20:53:23.106  4137  4301 D BluetoothAdapterProperties: Scan Mode:20
,08-25 20:53:23.106  4137  4301 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 20:53:23.107  4137  4301 D bt_hci  : do_postload posting postload work item
,08-25 20:53:23.107  4137  4305 I bt_hci  : event_postload
08-25 20:53:23.108  4137  4305 I bt_vendor: sco_config_cb
,08-25 20:53:23.108  4137  4305 I bt_hci  : sco_config_callback postload finished.
,08-25 20:53:23.110  4137  4301 D bt_bte_conf: Device ID record 1 : primary
,08-25 20:53:23.110  4137  4301 D bt_bte_conf:   vendorId            = 000f
,08-25 20:53:23.111  4137  4301 D bt_bte_conf:   vendorIdSource      = 0001
08-25 20:53:23.111  4137  4301 D bt_bte_conf:   product             = 1200,
,08-25 20:53:23.111  4137  4301 D bt_bte_conf:   version             = 1436
,08-25 20:53:23.111  4137  4301 D bt_bte_conf:   clientExecutableURL = 
,08-25 20:53:23.112  4137  4301 D bt_bte_conf:   serviceDescription  = 
,08-25 20:53:23.112  4137  4301 D bt_bte_conf:   documentationURL    = 
,08-25 20:53:23.112  4137  4301 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-25 20:53:23.112  4137  4298 D bt_stack_manager: event_start_up_stack finished
08-25 20:53:23.113  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:53:23.113  4137  4297 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-25 20:53:23.114  4137  4297 D BluetoothAdapterProperties: Setting state to 15
08-25 20:53:23.114  4137  4297 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-25 20:53:23.115  4137  4305 I bt_vendor: low_power_mode_cb
08-25 20:53:23.116  4137  4297 I BluetoothAdapterState: Entering BleOnState
08-25 20:53:23.120  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:53:23.122  4137  4297 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-25 20:53:23.122  4137  4297 D BluetoothAdapterProperties: Setting state to 11
08-25 20:53:23.123  4137  4297 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-25 20:53:23.131  4137  4137 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04b20e
,08-25 20:53:23.137  4137  4137 D HeadsetService: Received start request. Starting profile...
08-25 20:53:23.137  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:53:23.139  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:53:23.141  4137  4137 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 20:53:23.141  4137  4137 D HeadsetStateMachine: make
,08-25 20:53:23.159  4137  4137 D HeadsetStateMachine: max_hf_connections = 1
,08-25 20:53:23.160  4137  4137 I bt_bluedroid: get_profile_interface handsfree
08-25 20:53:23.160  4137  4301 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-25 20:53:23.160  4137  4301 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-25 20:53:23.168  4137  4297 I BluetoothAdapterState: Entering PendingCommandState
,08-25 20:53:23.169  4137  4137 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04b20e
08-25 20:53:23.169  4137  4137 D A2dpService: Received start request. Starting profile...
08-25 20:53:23.170  4137  4137 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-25 20:53:23.170  4137  4137 I bt_bluedroid: get_profile_interface avrcp
,08-25 20:53:23.176  4137  4137 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-25 20:53:23.176  4137  4137 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-25 20:53:23.177  4137  4137 D A2dpStateMachine: make
,08-25 20:53:23.178  4137  4137 I bt_bluedroid: get_profile_interface a2dp
,08-25 20:53:23.179  4137  4301 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-25 20:53:23.181  4137  4316 D A2dpStateMachine: Enter Disconnected: -2
,08-25 20:53:23.182  4137  4137 I BluetoothHidServiceJni: classInitNative: succeeds
08-25 20:53:23.183  4137  4137 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04b20e
08-25 20:53:23.185  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 20:53:23.185  4057  4057 D BluetoothInputDevice: Proxy object connected
08-25 20:53:23.186  4057  4057 D HidProfile: Bluetooth service connected
,08-25 20:53:23.186  4137  4137 D HidService: Received start request. Starting profile...
08-25 20:53:23.187  4137  4137 I bt_bluedroid: get_profile_interface hidhost
08-25 20:53:23.187  4137  4301 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39483e5
08-25 20:53:23.187  4137  4301 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-25 20:53:23.187  4137  4137 D HidService: setHidService(): set to: null
08-25 20:53:23.188  4137  4137 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-25 20:53:23.190  4137  4137 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04b20e
,08-25 20:53:23.191  4137  4137 D HealthService: Received start request. Starting profile...
,08-25 20:53:23.193  4137  4137 I bt_bluedroid: get_profile_interface health
,08-25 20:53:23.196  4137  4137 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-25 20:53:23.197  4137  4137 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04b20e
,08-25 20:53:23.199  4057  4057 D BluetoothPan: BluetoothPAN Proxy object connected
,08-25 20:53:23.199  4137  4137 D PanService: Received start request. Starting profile...
08-25 20:53:23.199  4137  4137 D BluetoothPanServiceJni: initializeNative(L110): pan
08-25 20:53:23.199  4137  4137 I bt_bluedroid: get_profile_interface pan
08-25 20:53:23.199  4137  4301 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-25 20:53:23.200  4057  4057 D PanProfile: Bluetooth service connected
,08-25 20:53:23.203  4137  4314 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-25 20:53:23.205  4137  4137 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04b20e
,08-25 20:53:23.205  4137  4137 V BluetoothAdapterState: isTurningOff()=false
08-25 20:53:23.205  4137  4137 V BluetoothAdapterState: isTurningOn()=true
,08-25 20:53:23.205  4137  4137 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 20:53:23.205  4137  4137 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 20:53:23.210  4057  4057 D BluetoothMap: Proxy object connected
,08-25 20:53:23.210  4137  4137 D BluetoothMapService: Received start request. Starting profile...
,08-25 20:53:23.210  4137  4137 D BluetoothMapService: start()
08-25 20:53:23.210  4057  4057 D MapProfile: Bluetooth service connected
,08-25 20:53:23.210  4057  4057 D BluetoothMap: getConnectedDevices(),
08-25 20:53:23.211  4057  4057 D BluetoothMap: Bluetooth is Not enabled
,08-25 20:53:23.212  4137  4137 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-25 20:53:23.213  4137  4137 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-25 20:53:23.213  4137  4137 D BluetoothMapAppObserver: createReceiver()
,08-25 20:53:23.215  4137  4137 D BluetoothMapAppObserver: initObservers()
,08-25 20:53:23.215  4137  4137 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-25 20:53:23.225  4137  4137 V BluetoothAdapterState: isTurningOff()=false
,08-25 20:53:23.225  4137  4137 V BluetoothAdapterState: isTurningOn()=true
08-25 20:53:23.225  4137  4137 V BluetoothAdapterState: isBleTurningOn()=false
08-25 20:53:23.225  4137  4137 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 20:53:23.225  4137  4137 V BluetoothAdapterState: isTurningOff()=false
,08-25 20:53:23.225  4137  4137 V BluetoothAdapterState: isTurningOn()=true
,08-25 20:53:23.226  4137  4137 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 20:53:23.226  4137  4137 V BluetoothAdapterState: isBleTurningOff()=false
08-25 20:53:23.226  4137  4137 V BluetoothAdapterState: isTurningOff()=false
08-25 20:53:23.226  4137  4137 V BluetoothAdapterState: isTurningOn()=true
,08-25 20:53:23.226  4137  4137 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 20:53:23.227  4137  4137 V BluetoothAdapterState: isBleTurningOff()=false
08-25 20:53:23.227  4137  4137 V BluetoothAdapterState: isTurningOff()=false
,08-25 20:53:23.227  4137  4137 V BluetoothAdapterState: isTurningOn()=true
08-25 20:53:23.227  4137  4137 V BluetoothAdapterState: isBleTurningOn()=false
08-25 20:53:23.227  4137  4137 V BluetoothAdapterState: isBleTurningOff()=false
08-25 20:53:23.227  4137  4137 V BluetoothAdapterState: isTurningOff()=false
08-25 20:53:23.227  4137  4137 V BluetoothAdapterState: isTurningOn()=true
08-25 20:53:23.227  4137  4137 V BluetoothAdapterState: isBleTurningOn()=false
08-25 20:53:23.227  4137  4137 V BluetoothAdapterState: isBleTurningOff()=false
08-25 20:53:23.228  4137  4297 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-25 20:53:23.228  4137  4297 D BluetoothAdapterProperties: ScanMode =  20
,08-25 20:53:23.228  4137  4297 D BluetoothAdapterProperties: State =  11
08-25 20:53:23.232  4137  4301 D BluetoothAdapterProperties: Scan Mode:21
08-25 20:53:23.232  4137  4297 D BluetoothAdapterProperties: Setting state to 12
08-25 20:53:23.232  4137  4297 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-25 20:53:23.232  4137  4301 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 20:53:23.233  4137  4297 I BluetoothAdapterState: Entering OnState
08-25 20:53:23.233  1362  1379 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 20:53:23.235  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:53:23.235  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:53:23.235  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 20:53:23.235  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 20:53:23.235  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 20:53:23.235  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 20:53:23.235  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 20:53:23.235  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 20:53:23.235   876   893 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 20:53:23.236  3987  3987 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 20:53:23.238  1362  1373 D BluetoothPbap: onBluetoothStateChange: up=true
,08-25 20:53:23.238   876   876 D BluetoothA2dp: Proxy object connected
,08-25 20:53:23.239  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:53:23.239  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:53:23.239  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 20:53:23.239  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 20:53:23.239  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 20:53:23.239  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 20:53:23.239  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 20:53:23.239  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 20:53:23.240   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 20:53:23.241  4057  4069 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-25 20:53:23.241  1943  1959 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 20:53:23.241  3987  3987 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 20:53:23.242  1362  2088 D BluetoothPan: onBluetoothStateChange on: true
,08-25 20:53:23.243  1362  1362 D BluetoothPan: BluetoothPAN Proxy object connected
,08-25 20:53:23.243  1362  1362 D PanProfile: Bluetooth service connected
08-25 20:53:23.243   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 20:53:23.244  1362  1373 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-25 20:53:23.245  1362  1362 D BluetoothInputDevice: Proxy object connected
08-25 20:53:23.245  1362  1362 D HidProfile: Bluetooth service connected
08-25 20:53:23.245  4057  4070 D BluetoothPan: onBluetoothStateChange on: true
08-25 20:53:23.246  1362  2088 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 20:53:23.246  4137  4137 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-25 20:53:23.246  4137  4137 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-25 20:53:23.247  1362  1362 D BluetoothA2dp: Proxy object connected
08-25 20:53:23.247  4057  4069 D BluetoothMap: onBluetoothStateChange: up=true
08-25 20:53:23.247   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 20:53:23.247  1362  1373 D BluetoothMap: onBluetoothStateChange: up=true
,08-25 20:53:23.247  4137  4137 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 20:53:23.249  1362  1362 D BluetoothMap: Proxy object connected
08-25 20:53:23.249  1362  1362 D MapProfile: Bluetooth service connected
,08-25 20:53:23.249  1362  1362 D BluetoothMap: getConnectedDevices()
,08-25 20:53:23.249  4057  4070 D BluetoothPbap: onBluetoothStateChange: up=true
08-25 20:53:23.250  4137  4137 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 20:53:23.251   876   876 I Telecom : BluetoothPhoneService: queryPhoneState
,08-25 20:53:23.252  4137  4137 D ObexServerSockets: Succeed to create listening sockets 
08-25 20:53:23.252  4137  4137 D ObexServerSockets0: startAccept()
08-25 20:53:23.252  4137  4137 D ObexServerSockets0: prepareForNewConnect()
,08-25 20:53:23.254  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:53:23.254  4137  4137 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-25 20:53:23.254  4057  4057 D LocalBluetoothProfileManager: Adding local A2DP profile
08-25 20:53:23.255  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 20:53:23.255  4137  4137 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-25 20:53:23.255  4137  4137 D BluetoothMapService: onReceive
08-25 20:53:23.255  4137  4137 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:53:23.255  4137  4137 D BluetoothMapService: STATE_ON
,08-25 20:53:23.255  4137  4322 D ObexServerSockets0: Accepting socket connection...
08-25 20:53:23.256  4137  4323 D ObexServerSockets0: Accepting socket connection...
08-25 20:53:23.259  4057  4057 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-25 20:53:23.264  4057  4057 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 20:53:23.268  4057  4057 D BluetoothA2dp: Proxy object connected
,08-25 20:53:23.270  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 20:53:23.274  4057  4057 D DockEventReceiver: finishStartingService: stopping service
,08-25 20:53:23.278  1362  1362 D BluetoothPbap: Proxy object connected
,08-25 20:53:23.278  1362  1362 D PbapServerProfile: Bluetooth service connected
,08-25 20:53:23.278  4057  4057 D BluetoothPbap: Proxy object connected
,08-25 20:53:23.278  4057  4057 D PbapServerProfile: Bluetooth service connected
,08-25 20:53:23.283  4137  4137 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-25 20:53:23.283  4137  4137 D ObexServerSockets0: prepareForNewConnect()
,08-25 20:53:23.287  4137  4327 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 20:53:23.299  4137  4331 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 20:53:23.302  4137  4331 I BtOppRfcommListener: Accept thread started.
,08-25 20:53:23.341   876   893 D BluetoothHeadset: Proxy object connected
,08-25 20:53:23.342  1362  1379 D BluetoothHeadset: Proxy object connected
,08-25 20:53:23.342  1362  1362 D HeadsetProfile: Bluetooth service connected
08-25 20:53:23.343   876   876 D BluetoothHeadset: Proxy object connected
08-25 20:53:23.343  1943  2168 D BluetoothHeadset: Proxy object connected
08-25 20:53:23.343   876   876 D BluetoothHeadset: Proxy object connected
08-25 20:53:23.343  1943  2212 D BluetoothHeadset: Proxy object connected
08-25 20:53:23.343   876   876 D BluetoothHeadset: Proxy object connected
,08-25 20:53:23.344   876   893 D BluetoothHeadset: Proxy object connected
,08-25 20:53:23.347   876   893 D BluetoothHeadset: Proxy object connected
,08-25 20:53:23.361  4057  4070 D BluetoothHeadset: Proxy object connected
,08-25 20:53:23.363  4057  4057 D HeadsetProfile: Bluetooth service connected
,08-25 20:53:24.789   876  1320 D ConnectivityService: handlePromptUnvalidated 101
,08-25 20:53:24.842  4137  4297 D BluetoothAdapterState: Current state: ON, message: 23
,08-25 20:53:24.842  4137  4297 D BluetoothAdapterProperties: Setting state to 13
,08-25 20:53:24.843  4137  4297 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-25 20:53:24.844  4137  4297 D BluetoothAdapterProperties: onBluetoothDisable()
,08-25 20:53:24.847  4137  4297 I BluetoothAdapterState: Entering PendingCommandState
,08-25 20:53:24.858  4137  4137 D BluetoothMapService: onReceive
,08-25 20:53:24.858  4137  4137 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-25 20:53:24.858  4137  4137 D BluetoothMapService: STATE_TURNING_OFF
,08-25 20:53:24.859  3987  3987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:53:24.859  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:53:24.859  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:53:24.859  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 20:53:24.859  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 20:53:24.859  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false,
08-25 20:53:24.859  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 20:53:24.859  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 20:53:24.859  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 20:53:24.859  4137  4137 D BluetoothMapService: MAP Service closeService in
08-25 20:53:24.860  4137  4137 D BluetoothMapMasInstance0: MAP Service shutdown
08-25 20:53:24.860  4137  4137 D ObexServerSockets0: shutdown(block = true)
08-25 20:53:24.861  4137  4322 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-25 20:53:24.864  4137  4301 D BluetoothAdapterProperties: Scan Mode:20
08-25 20:53:24.864  3987  3987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:53:24.864  3987  3987 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 20:53:24.864  4137  4297 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-25 20:53:24.867  4137  4137 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-25 20:53:24.867  4137  4309 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-25 20:53:24.868  4137  4137 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-25 20:53:24.868  4137  4323 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-25 20:53:24.869  4137  4137 I BtOppRfcommListener: stopping Accept Thread
08-25 20:53:24.869  4137  4331 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 20:53:24.870  4137  4331 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-25 20:53:24.870  4057  4057 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-25 20:53:24.871  3987  3987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 20:53:24.871  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:53:24.871  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:53:24.871  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 20:53:24.871  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 20:53:24.871  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 20:53:24.871  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 20:53:24.871  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 20:53:24.871  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 20:53:24.872  3987  3987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:53:24.872  3987  3987 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 20:53:24.874  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 20:53:24.874  4137  4137 D HeadsetService: Received stop request...Stopping profile...
08-25 20:53:24.875  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 20:53:24.878  4057  4069 D BluetoothHeadset: Proxy object disconnected
08-25 20:53:24.878  1362  2088 D BluetoothHeadset: Proxy object disconnected
,08-25 20:53:24.878  4137  4137 D A2dpService: Received stop request...Stopping profile...
,08-25 20:53:24.878  4137  4316 D A2dpStateMachine: Exit Disconnected: -1
08-25 20:53:24.879   876   876 D BluetoothHeadset: Proxy object disconnected
,08-25 20:53:24.879   876   876 D BluetoothHeadset: Proxy object disconnected
08-25 20:53:24.879  1943  1957 D BluetoothHeadset: Proxy object disconnected
08-25 20:53:24.879   876   876 D BluetoothHeadset: Proxy object disconnected
,08-25 20:53:24.880   876   876 D BluetoothA2dp: Proxy object disconnected
08-25 20:53:24.881  4137  4137 D HidService: Received stop request...Stopping profile...
08-25 20:53:24.881  4137  4137 D HidService: Stopping Bluetooth HidService
08-25 20:53:24.881  4057  4057 D DockEventReceiver: finishStartingService: stopping service,
08-25 20:53:24.883  4057  4057 D HeadsetProfile: Bluetooth service disconnected
08-25 20:53:24.883  4057  4057 D BluetoothA2dp: Proxy object disconnected
08-25 20:53:24.884  4137  4137 D HealthService: Received stop request...Stopping profile...
08-25 20:53:24.884  1362  1362 D HeadsetProfile: Bluetooth service disconnected
,08-25 20:53:24.886  4057  4057 D BluetoothInputDevice: Proxy object disconnected
08-25 20:53:24.886  4057  4057 D HidProfile: Bluetooth service disconnected
08-25 20:53:24.886  1362  1362 D BluetoothA2dp: Proxy object disconnected
,08-25 20:53:24.886  1362  1362 D BluetoothInputDevice: Proxy object disconnected
,08-25 20:53:24.887  1362  1362 D HidProfile: Bluetooth service disconnected
,08-25 20:53:24.888  4137  4137 D PanService: Received stop request...Stopping profile...
08-25 20:53:24.889  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 20:53:24.890  1362  1362 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-25 20:53:24.890  1362  1362 D PanProfile: Bluetooth service disconnected
08-25 20:53:24.891  4057  4057 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-25 20:53:24.891  4057  4057 D PanProfile: Bluetooth service disconnected
08-25 20:53:24.892  4137  4137 V BluetoothAdapterState: isTurningOff()=true
08-25 20:53:24.892  4137  4137 V BluetoothAdapterState: isTurningOn()=false
08-25 20:53:24.892  4137  4137 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 20:53:24.892  4137  4137 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 20:53:24.894  4137  4137 D BluetoothMapService: Received stop request...Stopping profile...
08-25 20:53:24.894  4137  4137 D BluetoothMapService: stop()
08-25 20:53:24.894  4137  4137 D BluetoothMapAppObserver: deinitObservers()
08-25 20:53:24.895  4137  4137 D BluetoothMapAppObserver: removeReceiver()
,08-25 20:53:24.896  4057  4057 D BluetoothMap: Proxy object disconnected
08-25 20:53:24.896  4057  4057 D MapProfile: Bluetooth service disconnected
08-25 20:53:24.896  1362  1362 D BluetoothMap: Proxy object disconnected
08-25 20:53:24.896  1362  1362 D MapProfile: Bluetooth service disconnected
08-25 20:53:24.897  4137  4137 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-25 20:53:24.897  4137  4137 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 20:53:24.898  4137  4307 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-25 20:53:24.898  4137  4307 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 20:53:24.898  4137  4307 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 20:53:24.898  4137  4301 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-25 20:53:24.898  4137  4301 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
08-25 20:53:24.899  4137  4137 V BluetoothAdapterState: isTurningOff()=true
08-25 20:53:24.900  4137  4137 V BluetoothAdapterState: isTurningOn()=false
,08-25 20:53:24.900  4137  4137 V BluetoothAdapterState: isBleTurningOn()=false
08-25 20:53:24.900  4137  4137 V BluetoothAdapterState: isBleTurningOff()=false
08-25 20:53:24.901  4137  4301 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-25 20:53:24.901  4137  4307 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 20:53:24.901  4137  4307 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 20:53:24.901  4137  4307 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-25 20:53:24.901  4137  4307 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 20:53:24.901  4137  4307 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 20:53:24.901  4137  4307 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 20:53:24.902  4137  4137 V BluetoothAdapterState: isTurningOff()=true
08-25 20:53:24.902  4137  4137 V BluetoothAdapterState: isTurningOn()=false
,08-25 20:53:24.902  4137  4137 V BluetoothAdapterState: isBleTurningOn()=false
08-25 20:53:24.902  4137  4137 V BluetoothAdapterState: isBleTurningOff()=false
08-25 20:53:24.902  4137  4137 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 20:53:24.902  4137  4137 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 20:53:24.902  4137  4301 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-25 20:53:24.903  4137  4137 V BluetoothAdapterState: isTurningOff()=true
,08-25 20:53:24.903  4137  4137 V BluetoothAdapterState: isTurningOn()=false
,08-25 20:53:24.903  4137  4137 V BluetoothAdapterState: isBleTurningOn()=false
08-25 20:53:24.903  4137  4137 V BluetoothAdapterState: isBleTurningOff()=false
08-25 20:53:24.903  4137  4137 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-25 20:53:24.903  4137  4301 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-25 20:53:24.903  4137  4137 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 20:53:24.906  4137  4137 V BluetoothAdapterState: isTurningOff()=true
08-25 20:53:24.906  4137  4137 V BluetoothAdapterState: isTurningOn()=false
08-25 20:53:24.906  4137  4137 V BluetoothAdapterState: isBleTurningOn()=false
08-25 20:53:24.906  4137  4137 V BluetoothAdapterState: isBleTurningOff()=false
08-25 20:53:24.906  1362  1362 D BluetoothPbap: Proxy object disconnected
08-25 20:53:24.906  1362  1362 D PbapServerProfile: Bluetooth service disconnected
,08-25 20:53:24.906  4137  4137 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-25 20:53:24.907  4137  4137 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-25 20:53:24.907  4137  4137 D BluetoothMapService: MAP Service closeService in
08-25 20:53:24.908  4137  4137 V BluetoothAdapterState: isTurningOff()=true
08-25 20:53:24.908  4137  4137 V BluetoothAdapterState: isTurningOn()=false
08-25 20:53:24.908  4137  4137 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 20:53:24.908  4137  4137 V BluetoothAdapterState: isBleTurningOff()=false
08-25 20:53:24.908  4137  4297 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-25 20:53:24.908  4137  4297 D BluetoothAdapterProperties: Setting state to 15
08-25 20:53:24.908  4137  4297 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-25 20:53:24.909  4137  4297 I BluetoothAdapterState: Entering BleOnState
08-25 20:53:24.910  1362  2088 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 20:53:24.910   876   893 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 20:53:24.910  1362  2088 D BluetoothPbap: onBluetoothStateChange: up=false
08-25 20:53:24.911  4057  4057 D BluetoothPbap: Proxy object disconnected
,08-25 20:53:24.911  4057  4057 D PbapServerProfile: Bluetooth service disconnected
08-25 20:53:24.911   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 20:53:24.911  4137  4137 D BluetoothMapService: cleanup()
08-25 20:53:24.911  4137  4137 D BluetoothMapService: MAP Service closeService in
,08-25 20:53:24.912  4057  4070 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-25 20:53:24.914  1943  1959 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 20:53:24.914  1362  1373 D BluetoothPan: onBluetoothStateChange on: false
08-25 20:53:24.915   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-25 20:53:24.915  4057  4069 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 20:53:24.917  1362  2088 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-25 20:53:24.918  4057  4070 D BluetoothPan: onBluetoothStateChange on: false
,08-25 20:53:24.918  1362  1379 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 20:53:24.919  4057  4069 D BluetoothMap: onBluetoothStateChange: up=false
,08-25 20:53:24.919   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 20:53:24.920  1362  1373 D BluetoothMap: onBluetoothStateChange: up=false
,08-25 20:53:24.920  4057  4070 D BluetoothPbap: onBluetoothStateChange: up=false
08-25 20:53:24.921  4057  4069 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 20:53:24.922  4137  4297 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-25 20:53:24.922  4137  4297 D BluetoothAdapterProperties: Setting state to 16
08-25 20:53:24.922  4137  4297 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-25 20:53:24.922  4137  4297 D BluetoothAdapterProperties: onBleDisable
,08-25 20:53:24.924  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:53:24.924  4137  4298 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-25 20:53:24.924  4137  4297 I BluetoothAdapterState: Entering PendingCommandState
08-25 20:53:24.925  4137  4307 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-25 20:53:24.925  4137  4307 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-25 20:53:24.925  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:53:24.926  4057  4057 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-25 20:53:24.927  4137  4301 D BluetoothAdapterProperties: Scan Mode:20
08-25 20:53:24.932  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:53:24.932  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 20:53:24.933  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:53:24.934  4057  4057 D DockEventReceiver: finishStartingService: stopping service
,08-25 20:53:25.127  4137  4301 I bt_hci  : shut_down
,08-25 20:53:25.137  4137  4305 I bt_vendor: low_power_mode_cb
,08-25 20:53:25.137  4137  4305 D bt_hwcfg: hw_epilog_process
,08-25 20:53:25.155  4137  4305 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-25 20:53:25.155  4137  4305 I bt_vendor: epilog_cb
,08-25 20:53:25.156  4137  4305 I bt_hci  : epilog_finished_callback
,08-25 20:53:25.163  4137  4301 I bt_hci_h4: hal_close
,08-25 20:53:25.165  4137  4301 I bt_userial_vendor: device fd = 51 close
,08-25 20:53:25.287  4137  4298 D bt_stack_manager: event_shut_down_stack finished.
,08-25 20:53:25.288  4137  4297 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-25 20:53:25.294  4137  4137 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 20:53:25.294  4137  4297 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-25 20:53:25.296  4137  4137 D BtGatt.GattService: Received stop request...Stopping profile...
08-25 20:53:25.296  4137  4137 D BtGatt.GattService: stop()
08-25 20:53:25.296  4137  4137 D BtGatt.AdvertiseManager: advertise clients cleared
,08-25 20:53:25.301  4137  4137 V BluetoothAdapterState: isTurningOff()=false
,08-25 20:53:25.302  4137  4137 V BluetoothAdapterState: isTurningOn()=false
08-25 20:53:25.302  4137  4137 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 20:53:25.302  4137  4137 V BluetoothAdapterState: isBleTurningOff()=true
,08-25 20:53:25.303  4137  4297 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-25 20:53:25.304  4137  4297 D BluetoothAdapterProperties: Setting state to 10
,08-25 20:53:25.304  4137  4297 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-25 20:53:25.305  4137  4297 I BluetoothAdapterState: Entering OffState
,08-25 20:53:25.307   876   893 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-25 20:53:25.329  4137  4137 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-25 20:53:25.329  4137  4137 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-25 20:53:25.329  4137  4298 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-25 20:53:25.332  4137  4298 D bt_stack_manager: event_clean_up_stack finished.
,08-25 20:53:25.333  4137  4137 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-25 20:53:25.335  4137  4137 I art     : System.exit called, status: 0
,08-25 20:53:25.335  4137  4137 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-25 20:53:25.395   876  1715 I ActivityManager: Process com.android.bluetooth (pid 4137) has died
,08-25 20:53:27.381   876   896 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-25 20:53:27.392  1871  1871 I Keyboard.Facilitator: onFinishInput()
,08-25 20:53:27.399   876   896 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-25 20:53:27.399   876   896 I Adreno  : Build Date                       : 10/20/15
08-25 20:53:27.399   876   896 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-25 20:53:27.399   876   896 I Adreno  : Local Branch                     : M14
08-25 20:53:27.399   876   896 I Adreno  : Remote Branch                    : 
08-25 20:53:27.399   876   896 I Adreno  : Remote Branch                    : 
08-25 20:53:27.399   876   896 I Adreno  : Reconstruct Branch               : 
,08-25 20:53:27.437   281   294 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (181 us)
,08-25 20:53:27.839  3987  4038 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 20:53:27.840  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 20:53:28.122  3987  3987 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-25 20:53:28.122  3987  3987 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-25 20:53:28.175   876   896 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-25 20:53:28.176  3987  3987 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@55de11a Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@637d994, 16908290=android.view.AbsSavedState$1@637d994}, android:focusedViewId=100}]}]
,08-25 20:53:28.176  3987  3987 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-25 20:53:28.176  3987  3987 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-25 20:53:28.176  3987  3987 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-25 20:53:28.186   876   896 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-25 20:53:28.190   876   894 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-25 20:53:28.190   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
08-25 20:53:28.190   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-25 20:53:28.216   876   885 I art     : Background partial concurrent mark sweep GC freed 7720(502KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/43MB, paused 6.435ms total 117.192ms
,08-25 20:53:28.427   281   344 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-25 20:53:28.431   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
08-25 20:53:28.431   876  1342 D SurfaceControl: Excessive delay in setPowerMode(): 241ms
,08-25 20:53:28.435   876   896 I DreamManagerService: Entering dreamland.
,08-25 20:53:28.436   876   896 I PowerManagerService: Dozing...
,08-25 20:53:28.438   876   891 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-25 20:53:28.513   378   378 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-25 20:53:28.513   378   378 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-25 20:53:28.524   876  1318 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 20:53:28.530   876  1318 E native  : do suspend false
,08-25 20:53:28.539  1928  4343 D NfcService: Discovery configuration equal, not updating.
,08-25 20:53:28.567   876  1318 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 20:53:28.574   876  1318 E native  : do suspend true
,08-25 20:53:28.646   378  1326 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-25 20:53:28.647   378  1326 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-25 20:53:30.847  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 20:53:30.848  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@68aec3d added. We now have 6 listener(s)
,08-25 20:53:30.848  3987  4038 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 20:53:30.852  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 20:53:30.853  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@14f5c32 added. We now have 7 listener(s)
08-25 20:53:30.854  3987  4038 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 20:53:30.855  3987  4038 I System.out: IsBluetoothEnabled
,08-25 20:53:30.869  3987  4038 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 20:53:30.922   876   893 I ActivityManager: Start proc 4349:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-25 20:53:31.044  4349  4349 D AdapterServiceConfig: Adding HeadsetService
,08-25 20:53:31.044  4349  4349 D AdapterServiceConfig: Adding A2dpService
,08-25 20:53:31.045  4349  4349 D AdapterServiceConfig: Adding HidService
,08-25 20:53:31.045  4349  4349 D AdapterServiceConfig: Adding HealthService
08-25 20:53:31.045  4349  4349 D AdapterServiceConfig: Adding PanService
08-25 20:53:31.045  4349  4349 D AdapterServiceConfig: Adding GattService
08-25 20:53:31.045  4349  4349 D AdapterServiceConfig: Adding BluetoothMapService
,08-25 20:53:31.062   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@19cc72c:true
,08-25 20:53:31.064  4349  4349 D BluetoothAdapterState: make() - Creating AdapterState
,08-25 20:53:31.075  4349  4361 I BluetoothAdapterState: Entering OffState
08-25 20:53:31.075  4349  4349 I bt_bluedroid: init
,08-25 20:53:31.078  4349  4362 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-25 20:53:31.078  4349  4362 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-25 20:53:31.078  4349  4362 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-25 20:53:31.078  4349  4362 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-25 20:53:31.079  4349  4349 I bt_bluedroid: get_profile_interface socket
,08-25 20:53:31.081  4349  4349 I bt_bluedroid: get_profile_interface sdp
,08-25 20:53:31.085  4349  4360 I bt_bluedroid: config_hci_snoop_log
,08-25 20:53:31.086   876   893 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-25 20:53:31.088  4349  4365 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-25 20:53:31.091  4349  4365 D BluetoothAdapterProperties: Name is: Nexus 6
,08-25 20:53:31.094  4349  4361 D BluetoothAdapterState: Current state: OFF, message: 0
,08-25 20:53:31.094  4349  4361 D BluetoothAdapterProperties: Setting state to 14
08-25 20:53:31.095  4349  4361 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-25 20:53:31.101  4349  4361 D BluetoothBondStateMachine: make
,08-25 20:53:31.105  4349  4366 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-25 20:53:31.113  4349  4361 I BluetoothAdapterState: Entering PendingCommandState
,08-25 20:53:31.116  4349  4349 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-25 20:53:31.124  4349  4349 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04b20e
,08-25 20:53:31.126  4349  4349 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 20:53:31.128  4349  4349 D BtGatt.GattService: Received start request. Starting profile...
,08-25 20:53:31.128  4349  4349 D BtGatt.GattService: start()
08-25 20:53:31.129  4349  4349 I bt_bluedroid: get_profile_interface gatt
,08-25 20:53:31.130  4349  4349 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04b20e
,08-25 20:53:31.131  4349  4349 D BtGatt.AdvertiseManager: advertise manager created
,08-25 20:53:31.142  4349  4349 V BluetoothAdapterState: isTurningOff()=false
,08-25 20:53:31.142  4349  4349 V BluetoothAdapterState: isTurningOn()=false
08-25 20:53:31.142  4349  4349 V BluetoothAdapterState: isBleTurningOn()=true
08-25 20:53:31.142  4349  4349 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 20:53:31.143  4349  4361 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-25 20:53:31.143  4349  4361 I bt_bluedroid: enable,
,08-25 20:53:31.143  4349  4362 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-25 20:53:31.144  4349  4362 I bt_hci  : start_up
,08-25 20:53:31.152  4349  4362 I bt_vendor: alloc value 0xb3a39189
,08-25 20:53:31.153  4349  4362 I bt_vendor: init,
,08-25 20:53:31.153  4349  4362 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-25 20:53:31.153  4349  4362 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-25 20:53:31.258  4349  4362 D bt_hci  : start_up starting async portion
,08-25 20:53:31.259  4349  4369 I bt_hci  : event_finish_startup
,08-25 20:53:31.259  4349  4369 I bt_hci_h4: hal_open
,08-25 20:53:31.259  4349  4369 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
08-25 20:53:31.266  4349  4369 I bt_userial_vendor: device fd = 51 open
,08-25 20:53:31.302  4349  4369 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-25 20:53:31.334  4349  4369 D bt_hwcfg: Chipset BCM4354A2
08-25 20:53:31.334  4349  4369 D bt_hwcfg: Target name = [BCM4354A2]
,08-25 20:53:31.334  4349  4369 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-25 20:53:31.984  4349  4369 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-25 20:53:31.985  4349  4369 D bt_hwcfg: Settlement delay -- 100 ms
08-25 20:53:31.986  4349  4369 I bt_hwcfg: Setting fw settlement delay to 100 
,08-25 20:53:32.102  4349  4369 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-25 20:53:32.104  4349  4369 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-25 20:53:32.133  4349  4369 I bt_hwcfg: vendor lib fwcfg completed
,08-25 20:53:32.133  4349  4369 I bt_vendor: firmware callback
08-25 20:53:32.134  4349  4369 I bt_hci  : firmware_config_callback
,08-25 20:53:32.144  4349  4371 I bt_btu  : btu_task pending for preload complete event
,08-25 20:53:32.145  4349  4371 I bt_btu_task: Bluetooth chip preload is complete
08-25 20:53:32.145  4349  4371 I bt_btu  : btu_task received preload complete event
,08-25 20:53:32.155  4349  4371 I         : BTE_InitTraceLevels -- TRC_HCI
,08-25 20:53:32.155  4349  4371 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-25 20:53:32.155  4349  4371 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-25 20:53:32.156  4349  4371 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-25 20:53:32.156  4349  4371 I         : BTE_InitTraceLevels -- TRC_AVRC
08-25 20:53:32.156  4349  4371 I         : BTE_InitTraceLevels -- TRC_A2D
,08-25 20:53:32.157  4349  4371 I         : BTE_InitTraceLevels -- TRC_BNEP
08-25 20:53:32.157  4349  4371 I         : BTE_InitTraceLevels -- TRC_BTM
08-25 20:53:32.157  4349  4371 I         : BTE_InitTraceLevels -- TRC_GAP
,08-25 20:53:32.157  4349  4371 I         : BTE_InitTraceLevels -- TRC_PAN
08-25 20:53:32.158  4349  4371 I         : BTE_InitTraceLevels -- TRC_SDP
08-25 20:53:32.158  4349  4371 I         : BTE_InitTraceLevels -- TRC_GATT
,08-25 20:53:32.158  4349  4371 I         : BTE_InitTraceLevels -- TRC_SMP
08-25 20:53:32.158  4349  4371 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-25 20:53:32.159  4349  4371 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-25 20:53:32.293  4349  4371 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39b6d9d
,08-25 20:53:32.293  4349  4371 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39b6d9d 
,08-25 20:53:32.318  4349  4365 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-25 20:53:32.319  4349  4365 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-25 20:53:32.320  4349  4365 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-25 20:53:32.324  4349  4365 D BluetoothAdapterProperties: Name is: Nexus 6
,08-25 20:53:32.329  4349  4365 D BluetoothAdapterProperties: Scan Mode:20
,08-25 20:53:32.330  4349  4365 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 20:53:32.331  4349  4365 D bt_hci  : do_postload posting postload work item
,08-25 20:53:32.331  4349  4369 I bt_hci  : event_postload
08-25 20:53:32.331  4349  4369 I bt_vendor: sco_config_cb
,08-25 20:53:32.332  4349  4369 I bt_hci  : sco_config_callback postload finished.
08-25 20:53:32.335  4349  4365 D bt_bte_conf: Device ID record 1 : primary
08-25 20:53:32.335  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 20:53:32.335  4349  4365 D bt_bte_conf:   vendorId            = 000f
08-25 20:53:32.335  4349  4365 D bt_bte_conf:   vendorIdSource      = 0001
08-25 20:53:32.336  4349  4365 D bt_bte_conf:   product             = 1200
,08-25 20:53:32.336  4349  4365 D bt_bte_conf:   version             = 1436
08-25 20:53:32.336  4349  4365 D bt_bte_conf:   clientExecutableURL = 
08-25 20:53:32.336  4349  4365 D bt_bte_conf:   serviceDescription  = 
,08-25 20:53:32.336  4349  4365 D bt_bte_conf:   documentationURL    = 
08-25 20:53:32.336  4349  4365 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-25 20:53:32.337  4349  4362 D bt_stack_manager: event_start_up_stack finished
08-25 20:53:32.339  4349  4361 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-25 20:53:32.340  4349  4369 I bt_vendor: low_power_mode_cb
08-25 20:53:32.341  4349  4361 D BluetoothAdapterProperties: Setting state to 15
08-25 20:53:32.341  4349  4361 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-25 20:53:32.344  4349  4361 I BluetoothAdapterState: Entering BleOnState
,08-25 20:53:32.347  4349  4361 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-25 20:53:32.347  4349  4361 D BluetoothAdapterProperties: Setting state to 11
,08-25 20:53:32.348  4349  4361 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-25 20:53:32.356  4349  4349 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04b20e
08-25 20:53:32.360  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:53:32.360  4349  4349 D HeadsetService: Received start request. Starting profile...
,08-25 20:53:32.371  4349  4349 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 20:53:32.372  4349  4349 D HeadsetStateMachine: make
,08-25 20:53:32.374  4349  4361 I BluetoothAdapterState: Entering PendingCommandState
,08-25 20:53:32.381  4349  4349 D HeadsetStateMachine: max_hf_connections = 1
,08-25 20:53:32.381  4349  4349 I bt_bluedroid: get_profile_interface handsfree
08-25 20:53:32.381  4349  4365 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-25 20:53:32.382  4349  4365 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-25 20:53:32.386  4349  4349 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04b20e
,08-25 20:53:32.386  4349  4349 D A2dpService: Received start request. Starting profile...
,08-25 20:53:32.387  4349  4349 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-25 20:53:32.387  4349  4349 I bt_bluedroid: get_profile_interface avrcp
,08-25 20:53:32.393  4349  4349 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-25 20:53:32.393  4349  4349 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-25 20:53:32.393  4349  4349 D A2dpStateMachine: make
08-25 20:53:32.394  4349  4349 I bt_bluedroid: get_profile_interface a2dp
,08-25 20:53:32.394  4349  4365 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-25 20:53:32.396  4349  4380 D A2dpStateMachine: Enter Disconnected: -2
,08-25 20:53:32.397  4349  4349 I BluetoothHidServiceJni: classInitNative: succeeds
08-25 20:53:32.398  4349  4349 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04b20e
08-25 20:53:32.398  4349  4349 D HidService: Received start request. Starting profile...
08-25 20:53:32.398  4349  4349 I bt_bluedroid: get_profile_interface hidhost
08-25 20:53:32.399  4349  4365 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39983e5
08-25 20:53:32.399  4349  4365 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-25 20:53:32.399  4349  4349 D HidService: setHidService(): set to: null
08-25 20:53:32.400  4349  4349 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-25 20:53:32.402  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 20:53:32.402  4349  4349 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04b20e
08-25 20:53:32.403  4349  4349 D HealthService: Received start request. Starting profile...
,08-25 20:53:32.404  4349  4349 I bt_bluedroid: get_profile_interface health
,08-25 20:53:32.405  4349  4349 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-25 20:53:32.405  4349  4349 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04b20e
,08-25 20:53:32.406  4349  4349 D PanService: Received start request. Starting profile...
08-25 20:53:32.406  4349  4349 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-25 20:53:32.406  4349  4349 I bt_bluedroid: get_profile_interface pan
08-25 20:53:32.407  4349  4365 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-25 20:53:32.409  4349  4349 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04b20e
,08-25 20:53:32.409  4349  4349 D BluetoothMapService: Received start request. Starting profile...
08-25 20:53:32.409  4349  4349 D BluetoothMapService: start()
,08-25 20:53:32.411  4349  4349 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-25 20:53:32.412  4349  4349 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-25 20:53:32.412  4349  4349 D BluetoothMapAppObserver: createReceiver()
,08-25 20:53:32.413  4349  4349 D BluetoothMapAppObserver: initObservers()
08-25 20:53:32.413  4349  4349 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-25 20:53:32.420  4349  4349 V BluetoothAdapterState: isTurningOff()=false
,08-25 20:53:32.420  4349  4349 V BluetoothAdapterState: isTurningOn()=true
08-25 20:53:32.420  4349  4349 V BluetoothAdapterState: isBleTurningOn()=false
08-25 20:53:32.420  4349  4349 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 20:53:32.422  4349  4378 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-25 20:53:32.422  4349  4349 V BluetoothAdapterState: isTurningOff()=false
08-25 20:53:32.422  4349  4349 V BluetoothAdapterState: isTurningOn()=true
08-25 20:53:32.422  4349  4349 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 20:53:32.422  4349  4349 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 20:53:32.423  4349  4349 V BluetoothAdapterState: isTurningOff()=false
,08-25 20:53:32.423  4349  4349 V BluetoothAdapterState: isTurningOn()=true
,08-25 20:53:32.423  4349  4349 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 20:53:32.423  4349  4349 V BluetoothAdapterState: isBleTurningOff()=false
08-25 20:53:32.423  4349  4349 V BluetoothAdapterState: isTurningOff()=false
,08-25 20:53:32.423  4349  4349 V BluetoothAdapterState: isTurningOn()=true
,08-25 20:53:32.423  4349  4349 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 20:53:32.423  4349  4349 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 20:53:32.424  4349  4349 V BluetoothAdapterState: isTurningOff()=false
,08-25 20:53:32.424  4349  4349 V BluetoothAdapterState: isTurningOn()=true,
,08-25 20:53:32.424  4349  4349 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 20:53:32.424  4349  4349 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 20:53:32.424  4349  4349 V BluetoothAdapterState: isTurningOff()=false
,08-25 20:53:32.424  4349  4349 V BluetoothAdapterState: isTurningOn()=true,
08-25 20:53:32.424  4349  4349 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 20:53:32.424  4349  4349 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 20:53:32.424  4349  4361 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-25 20:53:32.425  4349  4361 D BluetoothAdapterProperties: ScanMode =  20
,08-25 20:53:32.425  4349  4361 D BluetoothAdapterProperties: State =  11
,08-25 20:53:32.428  4349  4365 D BluetoothAdapterProperties: Scan Mode:21
,08-25 20:53:32.429  4349  4365 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 20:53:32.429  4349  4361 D BluetoothAdapterProperties: Setting state to 12
,08-25 20:53:32.429  4349  4361 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-25 20:53:32.429  4349  4361 I BluetoothAdapterState: Entering OnState
08-25 20:53:32.430  1362  2088 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 20:53:32.431   876   893 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 20:53:32.432  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:53:32.432  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:53:32.432  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 20:53:32.432  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 20:53:32.432  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 20:53:32.432  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 20:53:32.432  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 20:53:32.432  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 20:53:32.434  3987  3987 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 20:53:32.434  1362  1379 D BluetoothPbap: onBluetoothStateChange: up=true
,08-25 20:53:32.435   876   876 D BluetoothA2dp: Proxy object connected
08-25 20:53:32.437   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 20:53:32.437  4057  4069 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-25 20:53:32.438  4349  4349 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-25 20:53:32.439  4349  4349 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-25 20:53:32.440  1943  1957 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 20:53:32.440  4349  4349 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 20:53:32.441  1362  1373 D BluetoothPan: onBluetoothStateChange on: true
08-25 20:53:32.442  4349  4349 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 20:53:32.443  4349  4349 D ObexServerSockets: Succeed to create listening sockets 
08-25 20:53:32.443  4349  4349 D ObexServerSockets0: startAccept()
08-25 20:53:32.443  4349  4349 D ObexServerSockets0: prepareForNewConnect()
08-25 20:53:32.443   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 20:53:32.444  4057  4070 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 20:53:32.445  4349  4349 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-25 20:53:32.445  4349  4349 D BluetoothSdpJni: SDP Create record success - handle: 0
08-25 20:53:32.445  4349  4385 D ObexServerSockets0: Accepting socket connection...
08-25 20:53:32.446  4349  4386 D ObexServerSockets0: Accepting socket connection...
08-25 20:53:32.447  1362  1362 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 20:53:32.447  4057  4057 D BluetoothInputDevice: Proxy object connected
08-25 20:53:32.447  1362  1362 D PanProfile: Bluetooth service connected
08-25 20:53:32.447  4057  4057 D HidProfile: Bluetooth service connected
08-25 20:53:32.448  1362  2088 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-25 20:53:32.449  1362  1362 D BluetoothInputDevice: Proxy object connected
08-25 20:53:32.449  1362  1362 D HidProfile: Bluetooth service connected
08-25 20:53:32.449  4057  4069 D BluetoothPan: onBluetoothStateChange on: true
08-25 20:53:32.450  4057  4057 D BluetoothA2dp: Proxy object connected
08-25 20:53:32.451  1362  1373 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 20:53:32.453  1362  1362 D BluetoothA2dp: Proxy object connected
08-25 20:53:32.453  4057  4387 D BluetoothMap: onBluetoothStateChange: up=true
08-25 20:53:32.454  4057  4057 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 20:53:32.454  4057  4057 D PanProfile: Bluetooth service connected
08-25 20:53:32.455   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 20:53:32.455  1362  1379 D BluetoothMap: onBluetoothStateChange: up=true
08-25 20:53:32.456  4057  4057 D BluetoothMap: Proxy object connected
08-25 20:53:32.456  4057  4057 D MapProfile: Bluetooth service connected
08-25 20:53:32.456  4057  4057 D BluetoothMap: getConnectedDevices()
08-25 20:53:32.457  1362  1362 D BluetoothMap: Proxy object connected
08-25 20:53:32.457  1362  1362 D MapProfile: Bluetooth service connected
08-25 20:53:32.457  1362  1362 D BluetoothMap: getConnectedDevices()
08-25 20:53:32.457  4057  4069 D BluetoothPbap: onBluetoothStateChange: up=true
08-25 20:53:32.459  4057  4387 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 20:53:32.463  4349  4349 D BluetoothMapService: onReceive
08-25 20:53:32.463  4349  4349 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:53:32.463  4349  4349 D BluetoothMapService: STATE_ON
08-25 20:53:32.463   876   876 I Telecom : BluetoothPhoneService: queryPhoneState
08-25 20:53:32.464  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:53:32.468  4057  4057 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.star,tService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 20:53:32.478  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 20:53:32.479  4057  4057 D DockEventReceiver: finishStartingService: stopping service
,08-25 20:53:32.490  4057  4057 D BluetoothPbap: Proxy object connected
,08-25 20:53:32.490  4057  4057 D PbapServerProfile: Bluetooth service connected
08-25 20:53:32.490  1362  1362 D BluetoothPbap: Proxy object connected
08-25 20:53:32.490  1362  1362 D PbapServerProfile: Bluetooth service connected
,08-25 20:53:32.499  4349  4349 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-25 20:53:32.499  4349  4349 D ObexServerSockets0: prepareForNewConnect()
,08-25 20:53:32.505  4349  4393 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 20:53:32.523  4349  4397 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 20:53:32.526  4349  4397 I BtOppRfcommListener: Accept thread started.
,08-25 20:53:32.533  4057  4069 D BluetoothHeadset: Proxy object connected
,08-25 20:53:32.533  4057  4057 D HeadsetProfile: Bluetooth service connected
,08-25 20:53:32.533  1362  1379 D BluetoothHeadset: Proxy object connected
08-25 20:53:32.533  1362  1362 D HeadsetProfile: Bluetooth service connected
,08-25 20:53:32.534   876   876 D BluetoothHeadset: Proxy object connected
08-25 20:53:32.534   876   876 D BluetoothHeadset: Proxy object connected
,08-25 20:53:32.534  1943  1959 D BluetoothHeadset: Proxy object connected
08-25 20:53:32.534   876   876 D BluetoothHeadset: Proxy object connected
,08-25 20:53:32.537   876   893 D BluetoothHeadset: Proxy object connected
,08-25 20:53:32.540  1943  2168 D BluetoothHeadset: Proxy object connected
,08-25 20:53:32.544   876   893 D BluetoothHeadset: Proxy object connected
,08-25 20:53:32.555   876   893 D BluetoothHeadset: Proxy object connected
,08-25 20:53:32.561  4057  4387 D BluetoothHeadset: Proxy object connected
,08-25 20:53:32.561  4057  4057 D HeadsetProfile: Bluetooth service connected
,08-25 20:53:32.893  3987  4038 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:53:32.893  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:53:32.893  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 20:53:32.893  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 20:53:32.893  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 20:53:32.893  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 20:53:32.893  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 20:53:32.893  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 20:53:32.899  3987  4038 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 20:53:32.903  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 20:53:32.903  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d8dad83 added. We now have 8 listener(s)
08-25 20:53:32.904  3987  4038 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 20:53:32.910   876  1986 D WifiService: setWifiEnabled: false pid=3987, uid=10000
,08-25 20:53:32.910   876  1986 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 20:53:32.924  3987  4038 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 20:53:32.925   876  1998 D WifiService: setWifiEnabled: true pid=3987, uid=10000
08-25 20:53:32.926   876  1998 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 20:53:32.942   876  1318 D WifiConfigStore: Loading config and enabling all networks 
,08-25 20:53:32.959  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:53:32.959  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:53:32.959  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 20:53:32.959  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:53:32.959  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 20:53:32.959  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 20:53:32.959  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 20:53:32.959  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 20:53:32.965  3987  3987 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 20:53:32.974   876  1318 D WifiConfigStore: loaded 0 passpoint configs
,08-25 20:53:32.975   876  1318 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-25 20:53:32.976   876  1318 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-25 20:53:32.976   876  1318 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-25 20:53:32.977   876  1318 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-25 20:53:32.977   876  1318 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-25 20:53:32.977   876  1318 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-25 20:53:32.989   374   874 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-25 20:53:32.990   876  1318 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.21 rxSuccessRate=0.27 delta 1000 -> 1000
,08-25 20:53:32.990   876  1318 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-25 20:53:32.991   374   874 D CommandListener: Setting iface cfg
08-25 20:53:32.992   876  1317 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '154 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 154 Failed to set address (No such device)'
08-25 20:53:32.992   876  1317 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-25 20:53:33.002   876  1318 E native  : do suspend true
,08-25 20:53:33.002   876  1317 D WifiNative-HAL: p2pGetDeviceAddress
,08-25 20:53:33.008   876  1317 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-25 20:53:33.014   876  1318 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-25 20:53:33.014   876  1318 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 20:53:33.024   876  1318 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-25 20:53:33.105   876  1318 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-25 20:53:33.108  1468  1468 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-25 20:53:33.540  1468  1468 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-25 20:53:33.579  1468  1468 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-25 20:53:33.580  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-25 20:53:33.582   876  1318 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 20:53:33.587   876  1318 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-25 20:53:33.588   876  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-25 20:53:33.588   876  1318 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 20:53:33.604   876  1318 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 20:53:33.614   374   874 D CommandListener: Setting iface cfg
,08-25 20:53:33.615   876  1318 D WifiStateMachine: Start Dhcp Watchdog 3
,08-25 20:53:33.624   876  1318 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-25 20:53:33.641   876  4406 D DhcpClient: Receive thread started
,08-25 20:53:33.727   876  1318 E native  : do suspend false
,08-25 20:53:33.749   876  2084 D DhcpClient: Broadcasting DHCPDISCOVER
,08-25 20:53:33.763   876  4406 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-25 20:53:33.765   876  2084 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-25 20:53:33.768   876  2084 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-25 20:53:33.783   876  4406 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-25 20:53:33.784   876  2084 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-25 20:53:33.789   374   874 D CommandListener: Setting iface cfg
,08-25 20:53:33.802   876  2084 D DhcpClient: Scheduling renewal in 86399s
,08-25 20:53:33.801   876  1318 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-25 20:53:33.807   876  1318 E native  : do suspend true
,08-25 20:53:33.830   876  1318 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-25 20:53:33.833   876  1318 D WifiConfigStore: No blacklist allowed without epno enabled
,08-25 20:53:33.834   876  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-25 20:53:33.838   876  1320 D ConnectivityService: Adding iface wlan0 to network 102
,08-25 20:53:33.849   876  1318 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-25 20:53:33.915   876  1320 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-25 20:53:33.916   876  1320 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-25 20:53:33.918   876  1320 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-25 20:53:33.919   876  1320 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-25 20:53:33.920   876  1320 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-25 20:53:33.935   876  1320 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-25 20:53:33.942  3987  4038 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:53:33.942  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:53:33.942  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 20:53:33.942  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:53:33.942  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 20:53:33.942  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 20:53:33.942  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 20:53:33.942  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 20:53:33.944  3987  4038 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 20:53:33.948  3987  4038 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-25 20:53:33.948   876  1320 D ConnectivityService: scheduleUnvalidatedPrompt 102
08-25 20:53:33.949   876  1320 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-25 20:53:33.949  3987  4038 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-25 20:53:33.949   876  1318 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-25 20:53:33.951  3987  4038 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@55de11a Bundle[{}]
,08-25 20:53:33.951   876  1318 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-25 20:53:33.952  3987  4038 I io.jxcore.node.LifeCycleMonitor: start: OK
08-25 20:53:33.952  3987  4038 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-25 20:53:33.952   876  1320 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-25 20:53:33.952   876  1320 D ConnectivityService:    accepting network in place of null
,08-25 20:53:33.953  3987  4038 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-25 20:53:33.953  3987  4038 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-25 20:53:33.954  3987  4038 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-25 20:53:33.954  3987  4038 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-25 20:53:33.956   876  1320 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-25 20:53:33.959  3987  4038 I System.out: Running OutgoingSocketThread
,08-25 20:53:33.961  3987  4411 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 464)
,08-25 20:53:33.962  3987  4411 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 40328
,08-25 20:53:33.962  3987  4411 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-25 20:53:33.963   876  4405 D NetlinkSocketObserver: NeighborEvent{elapsedMs=156738, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-25 20:53:33.996   374   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 20:53:34.036   876  4404 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.174,2a00:1450:4001:814::200e
,08-25 20:53:34.047   374   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 20:53:34.051   876  1320 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-25 20:53:34.051   876  1320 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-25 20:53:34.053   876  1320 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-25 20:53:34.058   876   893 D Tethering: MasterInitialState.processMessage what=3
,08-25 20:53:34.084  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:53:34.084  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:53:34.084  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 20:53:34.084  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:53:34.084  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 20:53:34.084  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 20:53:34.084  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 20:53:34.084  3987  3987 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 20:53:34.086  3987  3987 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 20:53:34.091  1717  1717 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-25 20:53:34.097  1717  1717 D SystemUpdateService: onCreate
,08-25 20:53:34.101  1717  1717 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-25 20:53:34.111   876  4404 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 18:53:34 GMT], X-Android-Received-Millis=[1472151214110], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472151214083]}
,08-25 20:53:34.112   876  1320 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-25 20:53:34.113   876  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,08-25 20:53:34.113   876  1320 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-25 20:53:34.114   876  1320 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-25 20:53:34.118  1717  4416 I SystemUpdateService: active receiver: enabled
,08-25 20:53:34.126  1717  1717 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-25 20:53:34.131  1717  4416 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-25 20:53:34.134  1717  1717 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-25 20:53:34.133  1717  2506 I iu.UploadsManager: num queued entries: 0
,08-25 20:53:34.137  1717  1717 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-25 20:53:34.138  1717  4416 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,08-25 20:53:34.136  1717  2506 I iu.UploadsManager: num updated entries: 0
,08-25 20:53:34.139  4151  4151 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-25 20:53:34.142  1717  4416 I SystemUpdateService: now status is 0 (complete)
08-25 20:53:34.142  1717  4416 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-25 20:53:34.142  1717  4416 I SystemUpdateService: file has been verified
,08-25 20:53:34.145  1717  4420 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-25 20:53:34.145  1717  4420 W BaseAppContext: Using Auth Proxy for data requests.
,08-25 20:53:34.147  1717  4416 I SystemUpdateService: OTA package size = 12249756
,08-25 20:53:34.147  1717  4420 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,08-25 20:53:34.149  4151  4151 D SprintDMHelper: simOperator: 
,08-25 20:53:34.149  4151  4151 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-25 20:53:34.157  1717  2506 I iu.SyncManager: NEXT; no task
,08-25 20:53:34.163  1717  4416 I SystemUpdateService: showing system update notification
,08-25 20:53:34.166  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 20:53:34.169  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 20:53:34.187  1717  1717 D SystemUpdateService: onDestroy
,08-25 20:53:34.216  1508  2413 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-25 20:53:34.216  1508  2413 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-25 20:53:34.216  1508  2413 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 20:53:34.216  1508  2413 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 20:53:34.247  1717  4420 E MDM     : [183] SitrepService.a: Error sending sitrep.
,08-25 20:53:34.279  2900  4422 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-25 20:53:34.963  3987  4038 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 465)
,08-25 20:53:34.963  3987  4038 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 465)
,08-25 20:53:34.972  3987  4038 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 470)
,08-25 20:53:34.975  3987  4038 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-25 20:53:34.975  3987  4038 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 471)
,08-25 20:53:34.980  3987  4038 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 20:53:34.980  3987  4038 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@682fb00 added. We now have 2 listener(s)
,08-25 20:53:34.982  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 20:53:34.982  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 20:53:34.983  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 20:53:34.983  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 20:53:34.983  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f0f39 added. We now have 9 listener(s)
08-25 20:53:34.983  3987  4038 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 20:53:34.984  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 20:53:34.987  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 20:53:34.997  3987  4038 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 20:53:34.997  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:53:34.997  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 20:53:34.997  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:53:34.997  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 20:53:34.997  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 20:53:34.997  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 20:53:34.997  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 20:53:35.000  3987  4038 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 20:53:35.000  3987  4038 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 20:53:35.001  3987  4038 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 20:53:35.002  3987  4038 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f39edf added. We now have 3 listener(s)
,08-25 20:53:35.006  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 20:53:35.007  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 20:53:35.008  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 20:53:35.008  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 20:53:35.008  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 20:53:35.009  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19cc72c added. We now have 10 listener(s)
,08-25 20:53:35.009  3987  4038 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 20:53:35.010  3987  4038 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:53:35.010  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:53:35.010  3987  4038 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:53:35.010  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 20:53:35.010  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:35.011  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 20:53:35.011  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 20:53:35.011  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:53:35.011  3987  4038 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@682fb00 removed from the list
,08-25 20:53:35.011  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:35.012  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f0f39 removed from the list
08-25 20:53:35.012  3987  4038 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 20:53:35.012  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:35.013  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 20:53:35.013  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:35.014  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:53:35.014  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:53:35.014  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:35.014  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f0f39 not in the list
08-25 20:53:35.014  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:35.014  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:35.015  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:53:35.016  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:53:35.016  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:35.016  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19cc72c removed from the list
08-25 20:53:35.016  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:53:35.016  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:35.016  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:35.016  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 20:53:35.016  3987  4038 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f39edf removed from the list
,08-25 20:53:35.017  3987  4038 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 20:53:35.017  3987  4038 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7865f5 added. We now have 2 listener(s)
08-25 20:53:35.019  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 20:53:35.019  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 20:53:35.019  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 20:53:35.019  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 20:53:35.019  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed23f8a added. We now have 9 listener(s)
08-25 20:53:35.019  3987  4038 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 20:53:35.020  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 20:53:35.023  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 20:53:35.029  3987  4038 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 20:53:35.029  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:53:35.029  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 20:53:35.029  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:53:35.029  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 20:53:35.029  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 20:53:35.029  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 20:53:35.029  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 20:53:35.031  3987  4038 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 20:53:35.032  3987  4038 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 20:53:35.032  3987  4038 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 20:53:35.032  3987  4038 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ba52a18 added. We now have 3 listener(s)
08-25 20:53:35.034  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 20:53:35.034  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 20:53:35.034  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 20:53:35.034  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 20:53:35.034  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eb66c71 ,added. We now have 10 listener(s)
08-25 20:53:35.034  3987  4038 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 20:53:35.035  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 20:53:35.035  3987  4038 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 20:53:35.035  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 20:53:35.035  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 20:53:35.035  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 20:53:35.037  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 20:53:35.039  3987  4038 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-25 20:53:35.039  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 20:53:35.041  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 20:53:35.043  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 20:53:35.044  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-25 20:53:35.044  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 20:53:35.048  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 20:53:35.048  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 20:53:35.048  3987  4038 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-25 20:53:35.049  3987  4038 D BluetoothAdapter: STATE_ON
,08-25 20:53:35.052   876  1320 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-25 20:53:35.052  4349  4389 D BtGatt.GattService: registerClient() - UUID=790e38d9-6768-44ca-bdf9-44e8029e0e97
,08-25 20:53:35.053  4349  4365 D BtGatt.GattService: onClientRegistered() - UUID=790e38d9-6768-44ca-bdf9-44e8029e0e97, clientIf=5
08-25 20:53:35.054  3987  3998 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-25 20:53:35.055  4349  4377 D BtGatt.GattService: start scan with filters
,08-25 20:53:35.060  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 20:53:35.060  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 20:53:35.060  4349  4368 D BtGatt.ScanManager: handling starting scan
,08-25 20:53:35.060  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 20:53:35.060  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-25 20:53:35.062  4349  4368 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04b20e
,08-25 20:53:35.063  3987  4038 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 20:53:35.063  3987  4038 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-25 20:53:35.065  3987  3987 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 20:53:35.065  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 20:53:35.068  3987  4038 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-25 20:53:35.068  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 20:53:35.068  3987  4038 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-25 20:53:35.068  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 20:53:35.068  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 20:53:35.069  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 20:53:35.069  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 20:53:35.069  3987  4038 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 20:53:35.069  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 20:53:35.069  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-25 20:53:35.069  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 20:53:35.070  3987  4038 D BluetoothAdapter: STATE_ON
08-25 20:53:35.070  4349  4365 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-25 20:53:35.070  4349  4365 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 20:53:35.071  4349  4389 D BtGatt.GattService: stopScan() - queue size =1
08-25 20:53:35.071  4349  4377 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-25 20:53:35.072  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 20:53:35.071  4349  4368 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-25 20:53:35.072  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 20:53:35.072  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 20:53:35.072  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-25 20:53:35.072  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-25 20:53:35.073  3987  4038 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 20:53:35.073  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 20:53:35.073  3987  4038 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 20:53:35.073  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 20:53:35.074  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 20:53:35.075  3987  3987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 20:53:35.075  3987  3987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 20:53:35.075  3987  3987 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 20:53:35.077  3987  4038 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:53:35.077  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 20:53:35.077  3987  4038 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:53:35.077  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 20:53:35.077  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 20:53:35.078  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 20:53:35.078  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 20:53:35.078  3987  4038 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7865f5 removed from the list
08-25 20:53:35.078  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 20:53:35.078  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed23f8a removed from the list
08-25 20:53:35.078  3987  4038 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:53:35.078  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 20:53:35.079  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:35.079  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:35.080  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 20:53:35.080  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:53:35.081  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 20:53:35.081  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed23f8a not in the list
,08-25 20:53:35.081  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 20:53:35.081  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 20:53:35.082  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 20:53:35.082  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:53:35.082  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 20:53:35.082  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eb66c71 removed from the list
,08-25 20:53:35.082  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 20:53:35.082  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:35.082  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,08-25 20:53:35.082  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-25 20:53:35.082  3987  4038 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ba52a18 removed from the list
08-25 20:53:35.083  3987  4038 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 20:53:35.083  3987  4038 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f45ead added. We now have 2 listener(s)
08-25 20:53:35.085  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 20:53:35.085  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 20:53:35.086  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 20:53:35.086  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 20:53:35.086  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb335e2 added. We now have 9 listener(s)
08-25 20:53:35.086  3987  4038 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 20:53:35.086  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 20:53:35.089  4349  4365 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-25 20:53:35.089  4349  4365 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 20:53:35.090  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 20:53:35.090  4349  4368 D BtGatt.ScanManager: Starting BLE batch scan
08-25 20:53:35.090  4349  4368 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-25 20:53:35.095  3987  4038 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 20:53:35.095  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:53:35.095  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 20:53:35.095  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:53:35.095  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 20:53:35.095  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 20:53:35.095  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 20:53:35.095  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 20:53:35.097  3987  4038 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 20:53:35.097  3987  4038 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 20:53:35.098  3987  4038 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 20:53:35.100  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-25 20:53:35.100  3987  4038 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bcb2430 added. We now have 3 listener(s)
,08-25 20:53:35.102  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 20:53:35.106  4349  4365 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-25 20:53:35.106  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 20:53:35.106  4349  4365 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 20:53:35.107  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 20:53:35.107  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 20:53:35.108  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 20:53:35.108  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a538a9 added. We now have 10 listener(s)
,08-25 20:53:35.109  3987  4038 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 20:53:35.109  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 20:53:35.110  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
,08-25 20:53:35.111  3987  4038 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 20:53:35.111  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-25 20:53:35.111  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 20:53:35.112  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 20:53:35.114  4349  4365 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-25 20:53:35.114  4349  4365 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 20:53:35.119  3987  4038 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-25 20:53:35.119  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 20:53:35.123  4349  4365 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-25 20:53:35.123  4349  4365 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 20:53:35.123  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 20:53:35.123  4349  4368 D BtGatt.ScanManager: stopping BLe Batch
,08-25 20:53:35.124  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-25 20:53:35.124  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 20:53:35.128  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 20:53:35.128  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-25 20:53:35.128  3987  4038 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-25 20:53:35.129  3987  4038 D BluetoothAdapter: STATE_ON
,08-25 20:53:35.131  4349  4365 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-25 20:53:35.131  4349  4365 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 20:53:35.131  4349  4360 D BtGatt.GattService: registerClient() - UUID=8d3f7a9f-6444-449c-875f-047df66fe15d
08-25 20:53:35.132  4349  4368 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-25 20:53:35.132  4349  4365 D BtGatt.GattService: onClientRegistered() - UUID=8d3f7a9f-6444-449c-875f-047df66fe15d, clientIf=5
,08-25 20:53:35.132  3987  3999 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-25 20:53:35.133  4349  4388 D BtGatt.GattService: start scan with filters
,08-25 20:53:35.135  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-25 20:53:35.135  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 20:53:35.136  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 20:53:35.136  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 20:53:35.139  4349  4365 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-25 20:53:35.139  4349  4365 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 20:53:35.139  3987  4038 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 20:53:35.139  3987  4038 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-25 20:53:35.139  3987  3987 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 20:53:35.140  4349  4368 D BtGatt.ScanManager: handling starting scan
08-25 20:53:35.141  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 20:53:35.143  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 20:53:35.143  3987  4038 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-25 20:53:35.144  3987  4038 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:53:35.144  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 20:53:35.144  3987  4038 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:53:35.144  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:53:35.144  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:35.144  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 20:53:35.145  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-25 20:53:35.145  3987  4038 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f45ead removed from the list
08-25 20:53:35.145  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:35.145  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb335e2 removed from the list
08-25 20:53:35.145  3987  4038 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:53:35.145  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 20:53:35.145  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:35.145  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-25 20:53:35.146  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:35.146  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 20:53:35.147  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 20:53:35.147  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:53:35.148  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:35.148  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb335e2 not in the list
,08-25 20:53:35.148  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-25 20:53:35.148  3987  4038 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 20:53:35.148  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 20:53:35.148  4349  4365 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-25 20:53:35.148  4349  4365 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 20:53:35.148  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 20:53:35.148  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 20:53:35.148  4349  4368 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-25 20:53:35.149  3987  4038 D BluetoothAdapter: STATE_ON
08-25 20:53:35.149  4349  4388 D BtGatt.GattService: stopScan() - queue size =1
08-25 20:53:35.150  4349  4359 D BtGatt.GattService: unregisterClient() - clientIf=5
08-25 20:53:35.150  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-25 20:53:35.150  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 20:53:35.151  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 20:53:35.151  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 20:53:35.151  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 20:53:35.152  3987  4038 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 20:53:35.152  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 20:53:35.152  3987  4038 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-25 20:53:35.152  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 20:53:35.153  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 20:53:35.154  3987  3987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 20:53:35.154  3987  3987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 20:53:35.154  3987  3987 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 20:53:35.154  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:53:35.155  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 20:53:35.155  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:35.155  4349  4365 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-25 20:53:35.155  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a538a9 removed from the list
08-25 20:53:35.155  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 20:53:35.155  4349  4365 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 20:53:35.155  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:35.155  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:35.155  4349  4368 D BtGatt.ScanManager: Starting BLE batch scan
08-25 20:53:35.155  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 20:53:35.155  4349  4368 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-25 20:53:35.155  3987  4038 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bcb2430 removed from the list
08-25 20:53:35.156  3987  4038 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 20:53:35.156  3987  4038 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16fb665 added. We now have 2 listener(s)
08-25 20:53:35.158  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 20:53:35.158  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 20:53:35.158  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 20:53:35.159  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 20:53:35.159  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d419f3a added. We now have 9 listener(s)
08-25 20:53:35.159  3987  4038 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 20:53:35.159  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 20:53:35.162  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 20:53:35.166  3987  4038 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 20:53:35.166  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:53:35.166  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 20:53:35.166  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:53:35.166  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 20:53:35.166  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 20:53:35.166  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 20:53:35.166  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 20:53:35.168  4349  4365 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-25 20:53:35.168  4349  4365 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 20:53:35.169  3987  4038 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 20:53:35.169  3987  4038 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 20:53:35.169  3987  4038 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 20:53:35.169  3987  4038 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4434948 added. We now have 3 listener(s)
08-25 20:53:35.171  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 20:53:35.171  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 20:53:35.171  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 20:53:35.171  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 20:53:35.171  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6aa53e1 added. We now have 10 listener(s)
08-25 20:53:35.172  3987  4038 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 20:53:35.172  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 20:53:35.172  3987  4038 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 20:53:35.172  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 20:53:35.172  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 20:53:35.172  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 20:53:35.174  4349  4365 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-25 20:53:35.174  4349  4365 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 20:53:35.176  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:53:35.177  3987  4038 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-25 20:53:35.178  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 20:53:35.178  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:53:35.182  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 20:53:35.182  4349  4365 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-25 20:53:35.182  4349  4365 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 20:53:35.182  4349  4368 D BtGatt.ScanManager: stopping BLe Batch
08-25 20:53:35.183  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-25 20:53:35.183  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 20:53:35.187  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-25 20:53:35.187  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 20:53:35.187  3987  4038 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-25 20:53:35.188  3987  4038 D BluetoothAdapter: STATE_ON
08-25 20:53:35.189  4349  4365 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-25 20:53:35.189  4349  4365 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 20:53:35.189  4349  4368 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-25 20:53:35.190  4349  4359 D BtGatt.GattService: registerClient() - UUID=a84fdd16-36c1-4ce7-b7a3-19f91d07b9f8
08-25 20:53:35.190  4349  4365 D BtGatt.GattService: onClientRegistered() - UUID=a84fdd16-36c1-4ce7-b7a3-19f91d07b9f8, clientIf=5
08-25 20:53:35.191  3987  3998 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-25 20:53:35.191  4349  4389 D BtGatt.GattService: start scan with filters
08-25 20:53:35.193  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 20:53:35.194  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 20:53:35.194  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 20:53:35.194  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-25 20:53:35.197  3987  4038 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 20:53:35.197  3987  3987 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 20:53:35.197  3987  4038 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-25 20:53:35.199  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-25 20:53:35.200  4349  4365 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
08-25 20:53:35.200  4349  4365 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 20:53:35.200  4349  4365 D BtGatt.GattService: current time is 157975963610
08-25 20:53:35.201  4349  4365 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -92, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-25 20:53:35.202  4349  4365 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-25 20:53:35.203  4349  4368 D BtGatt.ScanManager: handling starting scan
08-25 20:53:35.204  3987  4038 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:53:35.204  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:53:35.204  3987  4038 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:53:35.205  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:53:35.205  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:35.205  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 20:53:35.205  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 20:53:35.205  3987  4038 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16fb665 removed from the list
08-25 20:53:35.205  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:35.205  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d419f3a removed from the list
08-25 20:53:35.205  3987  4038 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:53:35.205  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 20:53:35.206  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:35.206  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-25 20:53:35.206  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:35.206  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 20:53:35.207  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:53:35.207  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:53:35.207  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:53:35.207  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d419f3a not in the list
08-25 20:53:35.207  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 20:53:35.207  3987  4038 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 20:53:35.207  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 20:53:35.207  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-25 20:53:35.207  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 20:53:35.208  3987  4038 D BluetoothAdapter: STATE_ON
08-25 20:53:35.208  4349  4359 D BtGatt.GattService: stopScan() - queue size =1
,08-25 20:53:35.209  4349  4389 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-25 20:53:35.210  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-25 20:53:35.210  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-25 20:53:35.210  4349  4365 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-25 20:53:35.210  4349  4365 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 20:53:35.210  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-25 20:53:35.210  4349  4368 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-25 20:53:35.210  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-25 20:53:35.210  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 20:53:35.211  3987  4038 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 20:53:35.212  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-25 20:53:35.212  3987  4038 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 20:53:35.212  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 20:53:35.212  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 20:53:35.213  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 20:53:35.213  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 20:53:35.213  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 20:53:35.213  3987  3987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 20:53:35.214  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6aa53e1 removed from the list
,08-25 20:53:35.214  3987  3987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 20:53:35.214  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 20:53:35.214  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:53:35.214  3987  3987 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 20:53:35.214  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:35.214  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-25 20:53:35.214  3987  4038 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4434948 removed from the list
,08-25 20:53:35.215  3987  4038 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 20:53:35.215  3987  4038 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c974d1d added. We now have 2 listener(s)
,08-25 20:53:35.216  4349  4365 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
,08-25 20:53:35.216  4349  4365 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 20:53:35.216  4349  4368 D BtGatt.ScanManager: Starting BLE batch scan
,08-25 20:53:35.216  4349  4368 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-25 20:53:35.217  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 20:53:35.217  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 20:53:35.217  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 20:53:35.218  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 20:53:35.218  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@758db92 added. We now have 9 listener(s)
,08-25 20:53:35.218  3987  4038 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 20:53:35.218  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 20:53:35.221  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
08-25 20:53:35.229  3987  4038 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 20:53:35.229  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:53:35.229  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 20:53:35.229  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true,
08-25 20:53:35.229  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 20:53:35.229  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 20:53:35.229  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 20:53:35.229  3987  4038 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 20:53:35.232  3987  4038 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
08-25 20:53:35.232  3987  4038 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 20:53:35.232  4349  4365 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-25 20:53:35.232  4349  4365 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 20:53:35.232  3987  4038 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 20:53:35.232  3987  4038 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c7f960 added. We now have 3 listener(s)
,08-25 20:53:35.234  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 20:53:35.234  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 20:53:35.234  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 20:53:35.234  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 20:53:35.234  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 20:53:35.234  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@609e19 added. We now have 10 listener(s)
08-25 20:53:35.234  3987  4038 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 20:53:35.235  3987  4038 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:53:35.235  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 20:53:35.235  3987  4038 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 20:53:35.235  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:53:35.235  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 20:53:35.236  3987  3987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 20:53:35.237  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 20:53:35.237  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 20:53:35.237  3987  4038 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c974d1d removed from the list
,08-25 20:53:35.237  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 20:53:35.237  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@758db92 removed from the list
,08-25 20:53:35.237  3987  4038 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 20:53:35.237  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:35.237  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-25 20:53:35.237  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:35.239  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 20:53:35.239  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:53:35.239  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-25 20:53:35.239  3987  4038 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@758db92 not in the list
,08-25 20:53:35.239  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 20:53:35.239  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 20:53:35.240  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:53:35.240  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 20:53:35.240  3987  4038 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 20:53:35.240  3987  4038 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@609e19 removed from the list
08-25 20:53:35.240  3987  4038 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:53:35.240  3987  4038 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 20:53:35.241  3987  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:53:35.241  3987  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 20:53:35.241  3987  4038 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c7f960 removed from the list
08-25 20:53:35.241  4349  4365 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-25 20:53:35.241  4349  4365 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 20:53:35.242  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-25 20:53:35.242  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-25 20:53:35.242  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-25 20:53:35.242  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 20:53:35.242  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-25 20:53:35.242  3987  4038 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 20:53:35.249  3987  4428 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 478, name: My test thread name)
08-25 20:53:35.249  3987  4428 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 478, thread name: My test thread name)
08-25 20:53:35.249  3987  4428 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 478, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-25 20:53:35.249  4349  4365 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-25 20:53:35.250  4349  4365 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 20:53:35.250  4349  4368 D BtGatt.ScanManager: stopping BLe Batch
08-25 20:53:35.251  3987  4429 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 480, name: My test thread name)
08-25 20:53:35.251  3987  4429 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 480, thread name: My test thread name)
08-25 20:53:35.251  3987  4429 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 480, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-25 20:53:35.254  3987  4038 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-25 20:53:35.254  3987  4038 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,08-25 20:53:35.254  3987  4038 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-25 20:53:35.254  3987  4038 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-25 20:53:35.254  3987  4038 D com.test.thalitest.ThaliTestRunner: Total duration: 22924 ms
08-25 20:53:35.256  3987  4038 I jxcore-log: *Native tests were executed*
08-25 20:53:35.256  3987  4038 I jxcore-log: 
08-25 20:53:35.256  3987  4038 I jxcore-log: Total number of executed tests:  80
08-25 20:53:35.256  3987  4038 I jxcore-log: 
,08-25 20:53:35.256  3987  4038 I jxcore-log: Number of passed tests:  80
08-25 20:53:35.256  3987  4038 I jxcore-log: 
08-25 20:53:35.256  3987  4038 I jxcore-log: Number of failed tests:  0
08-25 20:53:35.256  3987  4038 I jxcore-log: 
08-25 20:53:35.256  4349  4365 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-25 20:53:35.256  3987  4038 I jxcore-log: Number of ignored tests:  0
08-25 20:53:35.256  3987  4038 I jxcore-log: 
08-25 20:53:35.256  4349  4365 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 20:53:35.257  4349  4368 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-25 20:53:35.257  3987  4038 I jxcore-log: Total duration:  22924
08-25 20:53:35.257  3987  4038 I jxcore-log: 
08-25 20:53:35.257  3987  4038 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-25 20:53:35.257  3987  4038 I jxcore-log: 
,08-25 20:53:35.262  4349  4365 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-25 20:53:35.262  4349  4365 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 20:53:35.265  3987  3987 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-25 20:53:35.266  3987  4038 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 20:53:35.266  3987  4038 I jxcore-log: 
08-25 20:53:35.268  3987  4038 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 20:53:35.268  3987  4038 I jxcore-log: 
08-25 20:53:35.269  3987  4038 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 20:53:35.269  3987  4038 I jxcore-log: 
08-25 20:53:35.270  3987  4038 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 20:53:35.270  3987  4038 I jxcore-log: 
08-25 20:53:35.271  3987  4038 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 20:53:35.271  3987  4038 I jxcore-log: 
08-25 20:53:35.272  3987  4038 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 20:53:35.272  3987  4038 I jxcore-log: 
08-25 20:53:35.274  3987  4038 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 20:53:35.274  3987  4038 I jxcore-log: 
08-25 20:53:35.276  3987  4038 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 20:53:35.276  3987  4038 I jxcore-log: 
08-25 20:53:35.277  3987  4038 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 20:53:35.277  3987  4038 I jxcore-log: 
08-25 20:53:35.278  3987  4038 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 20:53:35.278  3987  4038 I jxcore-log: 
08-25 20:53:35.279  3987  4038 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 20:53:35.279  3987  4038 I jxcore-log: 
08-25 20:53:35.280  3987  4038 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 20:53:35.280  3987  4038 I jxcore-log: 
08-25 20:53:35.281  3987  4038 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 20:53:35.281  3987  4038 I jxcore-log: 
08-25 20:53:35.281  3987  4038 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 20:53:35.281  3987  4038 I jxcore-log: 
08-25 20:53:35.282  3987  4038 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 20:53:35.282  3987  4038 I jxcore-log: 
08-25 20:53:35.283  3987  4038 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 20:53:35.283  3987  4038 I jxcore-log: 
08-25 20:53:35.283  3987  4038 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 20:53:35.283  3987  4038 I jxcore-log: 
08-25 20:53:35.284  3987  4038 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 20:53:35.284  3987  4038 I jxcore-log: 
08-25 20:53:35.285  3987  4038 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 20:53:35.285  3987  4038 I jxcore-log: 
08-25 20:53:35.286  3987  4038 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 20:53:35.286  3987  4038 I jxcore-log: 
08-25 20:53:35.286  3987  4038 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 20:53:35.286  3987  4038 I jxcore-log: 
08-25 20:53:35.287  3987  4038 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 20:53:35.287  3987  4038 I jxcore-log: 
08-25 20:53:35.289  3987  4038 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 20:53:35.289  3987  4038 I jxcore-log: 
08-25 20:53:35.289  3987  4038 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 20:53:35.289  3987  4038 I jxcore-log: 
08-25 20:53:35.290  3987  4038 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 20:53:35.290  3987  4038 I jxcore-log: 
08-25 20:53:35.290  3987  4038 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 20:53:35.290  3987  4038 I jxcore-log: 
08-25 20:53:35.291  3987  4038 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 20:53:35.291  3987  4038 I jxcore-log: 
08-25 20:53:35.292  3987  4038 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 20:53:35.292  3987  4038 I jxcore-log: 
08-25 20:53:35.292  3987  4038 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 20:53:35.292  3987  4038 I jxcore-log: 
08-25 20:53:35.293  3987  4038 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 20:53:35.293  3987  4038 I jxcore-log: 
08-25 20:53:35.294  3987  4038 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 20:53:35.294  3987  4038 I jxcore-log: 
08-25 20:53:35.294  3987  4038 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 20:53:35.294  3987  4038 I jxcore-log: 
,08-25 20:53:35.576  3987  3987 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-25 20:53:35.577  3987  4038 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 20:53:35.577  3987  4038 I jxcore-log: 
,08-25 20:53:35.655  3987  3987 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 20:53:35.656  3987  4038 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 20:53:35.656  3987  4038 I jxcore-log: 
,08-25 20:53:35.715  3987  3987 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 20:53:35.717  3987  4038 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 20:53:35.717  3987  4038 I jxcore-log: 
,08-25 20:53:36.005  4431  4431 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-25 20:53:36.011  4431  4431 D AndroidRuntime: CheckJNI is OFF
,08-25 20:53:36.055  4431  4431 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-25 20:53:36.103  4431  4431 I Radio-JNI: register_android_hardware_Radio DONE
,08-25 20:53:36.129  4431  4431 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-25 20:53:36.143   876   889 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-25 20:53:36.143   876   889 I ActivityManager: Killing 3987:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-25 20:53:36.260   876  1522 D GraphicsStats: Buffer count: 2
,08-25 20:53:36.260   876   886 I WindowState: WIN DEATH: Window{f0a0a6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-25 20:53:36.261   876  1319 D WifiService: Client connection lost with reason: 4
,08-25 20:53:36.309   876   899 W PackageSettings: Skipping PackageSetting{51dd863 com.example.hello/10273} due to missing metadata
,08-25 20:53:36.345   876   889 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-25 20:53:36.345   876   889 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-25 20:53:36.346   876   889 E ActivityManager: Failure starting process com.test.thalitest
08-25 20:53:36.346   876   889 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-25 20:53:36.346   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-25 20:53:36.346   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-25 20:53:36.346   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-25 20:53:36.346   876   889 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-25 20:53:36.346   876   889 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-25 20:53:36.346   876   889 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-25 20:53:36.346   876   889 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-25 20:53:36.346   876   889 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-25 20:53:36.346   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-25 20:53:36.346   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-25 20:53:36.346   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-25 20:53:36.346   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-25 20:53:36.346   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-25 20:53:36.346   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-25 20:53:36.346   876   889 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 20:53:36.346   876   889 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-25 20:53:36.346   876   889 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 20:53:36.346   876   889 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-25 20:53:36.346   876   889 I ActivityManager:   Force finishing activity ActivityRecord{2dc5b0f u0 com.test.thalitest/.MainActivity t2}
08-25 20:53:36.350   876   899 I art     : Starting a blocking GC Explicit
,08-25 20:53:36.361   876  1522 W ActivityManager: Spurious death for ProcessRecord{1c62c81 0:com.test.thalitest/u0a0}, curProc for 3987: null,
,08-25 20:53:36.395   876   899 I art     : Explicit concurrent mark sweep GC freed 14030(974KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 713us total 44.959ms
,08-25 20:53:36.427   876   899 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-25 20:53:36.433  4431  4431 I art     : System.exit called, status: 0
,08-25 20:53:36.433  4431  4431 I AndroidRuntime: VM exiting with result code 0.
,08-25 20:53:36.438   876   899 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-25 20:53:36.466   876   889 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-25 20:53:36.474  4349  4349 D BluetoothMapAppObserver: onReceive
08-25 20:53:36.474  4349  4349 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-25 20:53:36.474  2029  2302 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-25 20:53:36.477   876  1308 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-25 20:53:36.480  3830  3830 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-25 20:53:36.474  1871  1871 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-25 20:53:36.501  1871  4443 I Keyboard.Facilitator.DecoderInitializer: run()
,08-25 20:53:36.506   876  1998 I ActivityManager: Start proc 4446:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-25 20:53:36.527  1943  1943 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-25 20:53:36.530  1871  4443 I Decoder : createOrResetDecoder
,08-25 20:53:36.553  1508  1508 I ConfigService: onCreate
,08-25 20:53:36.557  4446  4446 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-25 20:53:36.570   876  1958 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3987 uid 10000
,08-25 20:53:36.573  1871  1871 I Keyboard.Facilitator: onFinishInput(),
,08-25 20:53:36.590   876   876 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-25 20:53:36.590  1871  4443 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-25 20:53:36.620  1962  2068 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-25 20:53:36.620   876   888 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-25 20:53:36.621   876   888 E PackageManager: Failed to write settings, restoring backup
08-25 20:53:36.621   876   888 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-25 20:53:36.621   876   888 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
,08-25 20:53:36.621   876   888 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-25 20:53:36.621   876   888 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-25 20:53:36.621   876   888 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-25 20:53:36.621   876   888 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 20:53:36.621   876   888 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-25 20:53:36.621   876   888 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-25 20:53:36.624   876   889 E DropBoxManagerService: Can't write: system_server_wtf
08-25 20:53:36.624   876   889 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-25 20:53:36.624   876   889 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 20:53:36.624   876   889 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 20:53:36.624   876   889 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 20:53:36.624   876   889 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 20:53:36.624   876   889 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 20:53:36.624   876   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 20:53:36.624   876   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-25 20:53:36.624   876   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-25 20:53:36.624   876   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-25 20:53:36.624   876   889 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 20:53:36.624   876   889 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 20:53:36.624   876   889 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-25 20:53:36.624   876   889 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 20:53:36.624   876   889 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-25 20:53:36.624   876   889 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 20:53:36.624   876   889 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 20:53:36.624   876   889 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 20:53:36.624   876   889 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 20:53:36.624   876   889 E DropBoxManagerService: 	... 13 more
,08-25 20:53:36.633   876  1716 I ActivityManager: Start proc 4461:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-25 20:53:36.633  1962  2068 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-25 20:53:36.633  1962  2068 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1962
08-25 20:53:36.633  1962  2068 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-25 20:53:36.633  1962  2068 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-25 20:53:36.633  1962  2068 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-25 20:53:36.633  1962  2068 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-25 20:53:36.633  1962  2068 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-25 20:53:36.633  1962  2068 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-25 20:53:36.633  1962  2068 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-25 20:53:36.633  1962  2068 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-25 20:53:36.633  1962  2068 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 20:53:36.633  1962  2068 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 20:53:36.633  1962  2068 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-25 20:53:36.633  1962  2068 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-25 20:53:36.636   876  1380 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-25 20:53:36.636   876  4469 E DropBoxManagerService: Can't write: system_app_crash
08-25 20:53:36.636   876  4469 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-25 20:53:36.636   876  4469 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452),
08-25 20:53:36.636   876  4469 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 20:53:36.636   876  4469 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 20:53:36.636   876  4469 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 20:53:36.636   876  4469 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 20:53:36.636   876  4469 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 20:53:36.636   876  4469 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 20:53:36.636   876  4469 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 20:53:36.636   876  4469 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 20:53:36.636   876  4469 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 20:53:36.636   876  4469 E DropBoxManagerService: 	... 5 more
,08-25 20:53:36.639  1962  2068 I Process : Sending signal. PID: 1962 SIG: 9
,08-25 20:53:36.687  2029  2850 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-25 20:53:36.774   876  1318 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,08-25 20:53:36.849  4446  4446 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-25 20:53:36.854  1871  4443 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-25 20:53:36.857  1871  4443 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-25 20:53:36.857  1871  4443 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-25 20:53:36.861  1871  4443 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-25 20:53:36.861  1871  4443 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-25 20:53:36.861  1871  4443 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-25 20:53:36.862  1871  4443 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-25 20:53:36.872  1871  4443 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-25 20:53:36.872  1871  4443 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-25 20:53:36.872  1871  4443 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-25 20:53:36.873  1871  4443 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-25 20:53:36.873  1871  4443 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,08-25 20:53:36.873  1871  4443 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-25 20:53:36.892  4446  4477 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-25 20:53:36.904  4446  4460 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-25 20:53:36.904  4446  4460 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 20:53:36.904  4446  4460 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 20:53:36.904  4446  4460 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 20:53:36.904  4446  4460 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 20:53:36.904  4446  4460 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 20:53:36.904  4446  4460 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 20:53:36.904  4446  4460 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 20:53:36.904  4446  4460 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 20:53:36.904  4446  4460 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 20:53:36.904  4446  4460 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 20:53:36.904  4446  4460 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 20:53:36.904  4446  4460 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 20:53:36.904  4446  4460 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 20:53:36.904  4446  4460 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 20:53:36.904  4446  4460 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-25 20:53:36.904  4446  4460 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-25 20:53:36.904  4446  4460 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-25 20:53:36.904  4446  4460 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-25 20:53:36.904  4446  4460 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 20:53:36.904  4446  4460 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-25 20:53:36.904  4446  4460 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-25 20:53:36.904  4446  4460 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-25 20:53:36.904  4446  4460 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 20:53:36.904  4446  4460 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 20:53:36.904  4446  4460 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 20:53:36.904  4446  4460 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 20:53:36.904  4446  4460 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 20:53:36.904  4446  4460 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 20:53:36.904  4446  4460 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 20:53:36.904  4446  4460 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 20:53:36.904  4446  4460 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 20:53:36.904  4446  4460 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 20:53:36.904  4446  4460 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 20:53:36.904  4446  4460 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 20:53:36.904  4446  4460 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 20:53:36.904  4446  4460 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 20:53:36.904  4446  4460 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-25 20:53:36.904  4446  4460 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-25 20:53:36.904  4446  4460 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-25 20:53:36.904  4446  4460 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-25 20:53:36.904  4446  4460 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 20:53:36.904  4446  4460 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-25 20:53:36.904  4446  4460 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-25 20:53:36.919   876  1956 I ActivityManager: Start proc 4478:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-25 20:53:36.923   876  1522 I WindowState: WIN DEATH: Window{edb9e9 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-25 20:53:36.923   876  1380 D GraphicsStats: Buffer count: 1
,08-25 20:53:36.928   876   887 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1962) has died
08-25 20:53:36.929   876   887 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-25 20:53:36.939   876   887 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-25 20:53:36.959  4446  4460 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT,
08-25 20:53:36.961   876   889 I ActivityManager: Start proc 4491:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL

```
