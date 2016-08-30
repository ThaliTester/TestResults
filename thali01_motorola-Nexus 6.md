#### Test 82865362403aafb_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-30 12:19:37.829   873  1836 D NetlinkSocketObserver: NeighborEvent{elapsedMs=115890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 12:19:38.509  3783  3783 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-30 12:19:38.514  3783  3783 D AndroidRuntime: CheckJNI is OFF
08-30 12:19:38.559  3783  3783 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-30 12:19:38.611  3783  3783 I Radio-JNI: register_android_hardware_Radio DONE
08-30 12:19:38.633  3783  3783 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-30 12:19:38.639   873  1925 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 12:19:38.684  2021  2034 W SearchService: Abort, client detached.
08-30 12:19:38.685  3783  3783 D AndroidRuntime: Shutting down VM
08-30 12:19:38.692  2021  2021 I HotwordDetector: Closing mic
08-30 12:19:38.692  2021  2341 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@210fac8
08-30 12:19:38.693  2021  2353 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-30 12:19:38.708   873  3738 I ActivityManager: Start proc 3792:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-30 12:19:38.749   376  2355 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-30 12:19:38.750   376  2355 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-30 12:19:38.755   376  1278 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-30 12:19:38.757  2021  2346 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-30 12:19:38.758  2021  2352 I MicroRecognitionRnrImpl: Detection finished
08-30 12:19:38.794  3792  3792 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-30 12:19:38.816  3792  3792 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-30 12:19:38.822  3792  3792 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 6881-6883)
08-30 12:19:38.822  3792  3792 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 12:19:38.836  3792  3792 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {334ba75}
08-30 12:19:38.836  3792  3792 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 12:19:38.837  3792  3792 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 12:19:38.842  3792  3792 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-30 12:19:38.843  3792  3792 E SysUtils: ApplicationContext is null in ApplicationStatus
08-30 12:19:38.865  3792  3792 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-30 12:19:38.875  3792  3792 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 12:19:38.875  3792  3792 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 12:19:38.875  3792  3792 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 12:19:38.875  3792  3792 I Adreno  : Build Date                       : 10/20/15
08-30 12:19:38.875  3792  3792 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 12:19:38.875  3792  3792 I Adreno  : Local Branch                     : M14
08-30 12:19:38.875  3792  3792 I Adreno  : Remote Branch                    : 
08-30 12:19:38.875  3792  3792 I Adreno  : Remote Branch                    : 
08-30 12:19:38.875  3792  3792 I Adreno  : Reconstruct Branch               : 
08-30 12:19:38.927   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@96c3f23:true
,08-30 12:19:38.968  3792  3792 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-30 12:19:38.979  3792  3792 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-30 12:19:39.039  3792  3831 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-30 12:19:39.044  3792  3817 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-30 12:19:39.066  3792  3831 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 12:19:39.123   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +434ms
,08-30 12:19:39.128  1870  1870 I Keyboard.Facilitator: onFinishInput()
,08-30 12:19:39.213  3792  3792 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3792
,08-30 12:19:39.308  3792  3792 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 12:19:39.452  3792  3834 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1699743440
,08-30 12:19:39.457  3792  3834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 12:19:39.457  3792  3834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 12:19:39.457  3792  3834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 12:19:39.457  3792  3834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 12:19:39.457  3792  3834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-30 12:19:39.457  3792  3834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3aa0f70 added. We now have 1 listener(s)
,08-30 12:19:39.460  3792  3834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-30 12:19:39.461  3792  3834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 12:19:39.461  3792  3834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 12:19:39.461  3792  3834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 12:19:39.465  3792  3834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 12:19:39.465  3792  3834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 12:19:39.465  3792  3834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 12:19:39.465  3792  3834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-30 12:19:39.465  3792  3834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 12:19:39.465  3792  3834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 12:19:39.465  3792  3834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 12:19:39.465  3792  3834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 12:19:39.465  3792  3834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 12:19:39.465  3792  3834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 12:19:39.465  3792  3834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 12:19:39.465  3792  3834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 12:19:39.465  3792  3834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 12:19:39.465  3792  3834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-30 12:19:39.465  3792  3834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b47520f added. We now have 1 listener(s)
,08-30 12:19:39.465  3792  3834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:19:39.471   873  1307 D WifiService: New client listening to asynchronous messages
,08-30 12:19:39.473  3792  3834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 12:19:39.473  3792  3834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-30 12:19:39.475  3792  3834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-30 12:19:39.475  3792  3834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 12:19:39.475  3792  3834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-30 12:19:39.484  3792  3834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 12:19:39.485  3792  3834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-30 12:19:39.511  3792  3834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-30 12:19:39.511  3792  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:19:39.511  3792  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:19:39.511  3792  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:19:39.511  3792  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:19:39.511  3792  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:19:39.511  3792  3834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:19:39.511  3792  3834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:19:39.511  3792  3834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:19:39.512  3792  3834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-30 12:19:39.512  3792  3834 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:19:39.512  3792  3834 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 12:19:39.514  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:19:39.516  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:19:39.535   873  1976 I ActivityManager: Killing 2974:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-30 12:19:39.550  3792  3792 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 12:19:39.577   873  1976 I ActivityManager: Killing 3196:com.google.android.gm/u0a78 (adj 15): empty #18
,08-30 12:19:40.515  3792  3841 W jxcore-log: Initializing JXcore engine
,08-30 12:19:40.515  3792  3841 W jxcore-log: JXcore engine is ready
,08-30 12:19:40.582  3841  3841 W Thread-329: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8945 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-30 12:19:40.582  3841  3841 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12012]" dev="sockfs" ino=12012 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-30 12:19:40.582  3841  3841 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-30 12:19:40.582  3841  3841 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24232]" dev="sockfs" ino=24232 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-30 12:19:40.599  3792  3841 W jxcore-log: Starting JXcore engine
,08-30 12:19:40.700  3792  3841 W jxcore-log: Platform android
08-30 12:19:40.700  3792  3841 W jxcore-log: 
,08-30 12:19:40.700  3792  3841 W jxcore-log: Process ARCH arm
08-30 12:19:40.700  3792  3841 W jxcore-log: 
,08-30 12:19:40.970  3792  3841 I jxcore-log: JXcore Cordova bridge is ready!
08-30 12:19:40.970  3792  3841 I jxcore-log: 
,08-30 12:19:40.971  3792  3841 W jxcore-log: JXcore engine is started
,08-30 12:19:40.978  3792  3834 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 12:19:40.981  3792  3792 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 12:19:44.226   873  1306 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-30 12:19:46.955   873  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-30 12:19:48.920  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:19:48.925  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:19:48.927  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:19:48.943  1509  2256 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-30 12:19:48.943  1509  2256 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-30 12:19:48.943  1509  2256 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 12:19:48.943  1509  2256 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 12:19:48.956  3508  3508 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-30 12:19:48.956  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-30 12:19:48.956  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-30 12:19:49.984   873  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-30 12:19:50.287  1509  3628 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-30 12:19:50.287  1509  3628 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-30 12:19:50.288  1509  3628 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 12:19:50.289  1509  3628 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 12:19:50.331  3547  3854 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-30 12:19:50.331  3547  3854 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 12:19:50.331  3547  3854 E HttpOperation: 	at jdm.a(PG:82)
08-30 12:19:50.331  3547  3854 E HttpOperation: 	at jcs.o(PG:406)
08-30 12:19:50.331  3547  3854 E HttpOperation: 	at jcn.a(PG:1379)
08-30 12:19:50.331  3547  3854 E HttpOperation: 	at jcs.i(PG:143)
08-30 12:19:50.331  3547  3854 E HttpOperation: 	at blb.a(PG:3937)
08-30 12:19:50.331  3547  3854 E HttpOperation: 	at czp.a(PG:18188)
08-30 12:19:50.331  3547  3854 E HttpOperation: 	at czp.a(PG:9081)
08-30 12:19:50.331  3547  3854 E HttpOperation: 	at czq.run(PG:1686)
08-30 12:19:50.331  3547  3854 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 12:19:50.331  3547  3854 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 12:19:50.331  3547  3854 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 12:19:50.331  3547  3854 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 12:19:50.331  3547  3854 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 12:19:50.331  3547  3854 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 12:19:50.331  3547  3854 E HttpOperation: 	at jdj.a(PG:4091)
08-30 12:19:50.331  3547  3854 E HttpOperation: 	at jdj.a(PG:1125)
08-30 12:19:50.331  3547  3854 E HttpOperation: 	at jdm.a(PG:77)
08-30 12:19:50.331  3547  3854 E HttpOperation: 	... 12 more
08-30 12:19:50.331  3547  3854 E HttpOperation: Caused by: faj: BadAuthentication
08-30 12:19:50.331  3547  3854 E HttpOperation: 	at fal.a(PG:38)
08-30 12:19:50.331  3547  3854 E HttpOperation: 	at jdj.a(PG:4089)
08-30 12:19:50.331  3547  3854 E HttpOperation: 	... 14 more
,08-30 12:19:50.410  1509  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 12:19:50.410  1509  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-30 12:19:50.410  1509  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 12:19:50.411  1509  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 12:19:50.429  3547  3854 E HttpOperation: [getmobileexperiments] Unexpected exception
08-30 12:19:50.429  3547  3854 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 12:19:50.429  3547  3854 E HttpOperation: 	at jdm.a(PG:82)
08-30 12:19:50.429  3547  3854 E HttpOperation: 	at jcs.o(PG:406)
08-30 12:19:50.429  3547  3854 E HttpOperation: 	at jcn.a(PG:1379)
08-30 12:19:50.429  3547  3854 E HttpOperation: 	at jcs.i(PG:143)
08-30 12:19:50.429  3547  3854 E HttpOperation: 	at hec.a(PG:42)
08-30 12:19:50.429  3547  3854 E HttpOperation: 	at hee.a(PG:102)
08-30 12:19:50.429  3547  3854 E HttpOperation: 	at czr.a(PG:65)
08-30 12:19:50.429  3547  3854 E HttpOperation: 	at kka.a(PG:108)
08-30 12:19:50.429  3547  3854 E HttpOperation: 	at czp.a(PG:19176)
08-30 12:19:50.429  3547  3854 E HttpOperation: 	at czp.a(PG:9081)
08-30 12:19:50.429  3547  3854 E HttpOperation: 	at czq.run(PG:1686)
08-30 12:19:50.429  3547  3854 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 12:19:50.429  3547  3854 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 12:19:50.429  3547  3854 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 12:19:50.429  3547  3854 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 12:19:50.429  3547  3854 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 12:19:50.429  3547  3854 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 12:19:50.429  3547  3854 E HttpOperation: 	at jdj.a(PG:4091)
08-30 12:19:50.429  3547  3854 E HttpOperation: 	at jdj.a(PG:1125)
08-30 12:19:50.429  3547  3854 E HttpOperation: 	at jdm.a(PG:77)
08-30 12:19:50.429  3547  3854 E HttpOperation: 	... 15 more
08-30 12:19:50.429  3547  3854 E HttpOperation: Caused by: faj: BadAuthentication
08-30 12:19:50.429  3547  3854 E HttpOperation: 	at fal.a(PG:38)
08-30 12:19:50.429  3547  3854 E HttpOperation: 	at jdj.a(PG:4089)
08-30 12:19:50.429  3547  3854 E HttpOperation: 	... 17 more
,08-30 12:19:50.430  3547  3854 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-30 12:19:50.430  3547  3854 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-30 12:19:50.430  3547  3854 E ExperimentLoader: 	at jdm.a(PG:82)
08-30 12:19:50.430  3547  3854 E ExperimentLoader: 	at jcs.o(PG:406)
08-30 12:19:50.430  3547  3854 E ExperimentLoader: 	at jcn.a(PG:1379)
08-30 12:19:50.430  3547  3854 E ExperimentLoader: 	at jcs.i(PG:143)
08-30 12:19:50.430  3547  3854 E ExperimentLoader: 	at hec.a(PG:42)
08-30 12:19:50.430  3547  3854 E ExperimentLoader: 	at hee.a(PG:102)
08-30 12:19:50.430  3547  3854 E ExperimentLoader: 	at czr.a(PG:65)
08-30 12:19:50.430  3547  3854 E ExperimentLoader: 	at kka.a(PG:108)
08-30 12:19:50.430  3547  3854 E ExperimentLoader: 	at czp.a(PG:19176)
08-30 12:19:50.430  3547  3854 E ExperimentLoader: 	at czp.a(PG:9081)
08-30 12:19:50.430  3547  3854 E ExperimentLoader: 	at czq.run(PG:1686)
08-30 12:19:50.430  3547  3854 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 12:19:50.430  3547  3854 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 12:19:50.430  3547  3854 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 12:19:50.430  3547  3854 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 12:19:50.430  3547  3854 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-30 12:19:50.430  3547  3854 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 12:19:50.430  3547  3854 E ExperimentLoader: 	at jdj.a(PG:4091)
08-30 12:19:50.430  3547  3854 E ExperimentLoader: 	at jdj.a(PG:1125)
08-30 12:19:50.430  3547  3854 E ExperimentLoader: 	at jdm.a(PG:77)
08-30 12:19:50.430  3547  3854 E ExperimentLoader: 	... 15 more
08-30 12:19:50.430  3547  3854 E ExperimentLoader: Caused by: faj: BadAuthentication
08-30 12:19:50.430  3547  3854 E ExperimentLoader: 	at fal.a(PG:38)
08-30 12:19:50.430  3547  3854 E ExperimentLoader: 	at jdj.a(PG:4089)
08-30 12:19:50.430  3547  3854 E ExperimentLoader: 	... 17 more
,08-30 12:19:50.549   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 128089, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-30 12:19:55.266  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 12:19:55.266  3792  3841 I jxcore-log: 
,08-30 12:19:55.269  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 12:19:55.269  3792  3841 I jxcore-log: 
,08-30 12:19:55.283  3792  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:19:55.283  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:19:55.283  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:19:55.283  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:19:55.283  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:19:55.283  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:19:55.283  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:19:55.283  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:19:55.292  3792  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:19:55.299  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 12:19:55.299  3792  3841 I jxcore-log: 
,08-30 12:19:55.307  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 12:19:55.307  3792  3841 I jxcore-log: 
,08-30 12:19:55.695  3792  3841 I jxcore-log: Running unit tests
08-30 12:19:55.695  3792  3841 I jxcore-log: 
,08-30 12:19:55.696  3792  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 12:19:55.696  3792  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d73bb1c added. We now have 2 listener(s)
,08-30 12:19:55.697  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 12:19:55.697  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 12:19:55.698  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 12:19:55.698  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:19:55.698  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f16325 added. We now have 2 listener(s)
,08-30 12:19:55.698  3792  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 12:19:55.699  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 12:19:55.705  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 12:19:55.716  3792  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:19:55.716  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:19:55.716  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:19:55.716  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:19:55.716  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:19:55.716  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:19:55.716  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:19:55.716  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:19:55.722  3792  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:19:55.723  3792  3841 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 12:19:55.724  3792  3841 D executeNativeTests: Running unit tests
,08-30 12:19:55.730  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:19:55.737  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:19:55.819  3792  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 12:19:55.819  3792  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d6ec9b added. We now have 3 listener(s)
,08-30 12:19:55.820  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 12:19:55.821  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 12:19:55.821  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 12:19:55.821  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:19:55.821  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 added. We now have 3 listener(s)
,08-30 12:19:55.821  3792  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:19:55.822  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 12:19:55.830  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 12:19:55.844  3792  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:19:55.844  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:19:55.844  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:19:55.844  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:19:55.844  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:19:55.844  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:19:55.844  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:19:55.844  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:19:55.849  3792  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:19:55.850  3792  3841 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 12:19:55.857  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-30 12:19:55.858  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:19:55.857  3792  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 12:19:55.860  3792  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 12:19:55.860  3792  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 12:19:55.864  3792  3841 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-30 12:19:55.865  3792  3841 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-30 12:19:55.865  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-30 12:19:55.866  3792  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 12:19:55.866  3792  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-30 12:19:55.866  3792  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 12:19:55.868  3792  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:19:55.869  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:19:55.869  3792  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:19:55.869  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:19:55.869  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:19:55.869  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 12:19:55.870  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 12:19:55.870  3792  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d6ec9b removed from the list
08-30 12:19:55.870  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 12:19:55.870  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 removed from the list
08-30 12:19:55.872  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:19:55.873  3792  3841 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:19:55.873  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:19:55.873  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:19:55.873  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:19:55.874  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:19:55.875  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:19:55.875  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:19:55.875  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
08-30 12:19:55.877  3792  3841 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-30 12:19:55.877  3792  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:19:55.877  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:19:55.877  3792  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:19:55.877  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 12:19:55.878  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:19:55.878  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:19:55.878  3792  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d6ec9b not in the list
08-30 12:19:55.878  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:19:55.878  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
,08-30 12:19:55.878  3792  3841 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:19:55.878  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:19:55.878  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:19:55.878  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:19:55.878  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:19:55.879  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:19:55.879  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:19:55.879  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:19:55.879  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
,08-30 12:19:55.887  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 12:19:55.887  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-30 12:19:55.887  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 12:19:55.887  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 12:19:55.887  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-30 12:19:55.887  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 12:19:55.887  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 12:19:55.887  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 12:19:55.887  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 12:19:55.887  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 12:19:55.887  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 12:19:55.887  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 12:19:55.887  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-30 12:19:55.887  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 12:19:55.887  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 12:19:55.887  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 12:19:55.888  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 12:19:55.888  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 12:19:55.888  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 12:19:55.888  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 12:19:55.888  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 12:19:55.888  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-30 12:19:55.888  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-30 12:19:55.888  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 12:19:55.888  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 12:19:55.888  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 12:19:55.888  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 12:19:55.888  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 12:19:55.888  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 12:19:55.888  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-30 12:19:55.888  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 12:19:55.888  3792  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:19:55.888  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:19:55.888  3792  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:19:55.889  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:19:55.889  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:19:55.889  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:19:55.889  3792  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d6ec9b not in the list
,08-30 12:19:55.889  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:19:55.889  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
08-30 12:19:55.889  3792  3841 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:19:55.889  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:19:55.889  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:19:55.889  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:19:55.889  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:19:55.890  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:19:55.890  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:19:55.890  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:19:55.890  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
,08-30 12:19:55.891  3792  3841 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 12:19:55.892  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 12:19:55.897  3792  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:19:55.897  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:19:55.897  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:19:55.897  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:19:55.897  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:19:55.897  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:19:55.897  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:19:55.897  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:19:55.899  3792  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:19:55.899  3792  3841 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 12:19:55.900  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 12:19:55.901  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:19:55.900  3792  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-30 12:19:55.901  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-30 12:19:55.902  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:19:55.902  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 12:19:55.903  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:19:55.905  3792  3841 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 12:19:55.905  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 12:19:55.910  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 12:19:55.912  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 12:19:55.912  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 12:19:55.914  3792  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-30 12:19:55.918  3792  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-30 12:19:55.918  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 12:19:55.918  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 12:19:55.919  3792  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 12:19:55.921  3792  3841 D BluetoothAdapter: STATE_ON
,08-30 12:19:55.927  2663  2807 D BtGatt.GattService: registerClient() - UUID=019a5185-d5c0-4c0d-b1a9-efee8ab444a5
,08-30 12:19:55.928  2663  2684 D BtGatt.GattService: onClientRegistered() - UUID=019a5185-d5c0-4c0d-b1a9-efee8ab444a5, clientIf=5
,08-30 12:19:55.929  3792  3803 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 12:19:55.930  2663  2674 D BtGatt.GattService: start scan with filters
,08-30 12:19:55.932  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 12:19:55.933  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 12:19:55.933  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-30 12:19:55.933  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-30 12:19:55.933  2663  2696 D BtGatt.ScanManager: handling starting scan
,08-30 12:19:55.936  3792  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 12:19:55.937  3792  3792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 12:19:55.938  3792  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 12:19:55.938  2663  2696 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7523b57
,08-30 12:19:55.939  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 12:19:55.944  3792  3841 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 12:19:55.950  2663  2684 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 12:19:55.950  2663  2684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:19:55.951  2663  2696 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 12:19:55.959  2663  2684 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 12:19:55.960  2663  2684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:19:55.961  2663  2696 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 12:19:55.961  2663  2696 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 12:19:55.984  2663  2684 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 12:19:55.984  2663  2684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:19:55.992  2663  2684 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 12:19:55.992  2663  2684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:19:56.439  3792  3792 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-30 12:19:56.439  3792  3792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 12:19:56.439  3792  3792 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 12:19:57.498  2663  2663 D BtGatt.ScanManager: awakened up at time 135560
,08-30 12:19:57.501  2663  2696 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 12:19:57.539  2663  2684 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
08-30 12:19:57.539  2663  2684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:19:57.540  2663  2684 D BtGatt.GattService: current time is 135601645393
,08-30 12:19:57.541  2663  2684 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -82, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -78, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -83, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -87, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -92, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -95, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-30 12:19:57.545  2663  2684 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-30 12:19:57.547  2663  2684 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-30 12:19:57.548  2663  2684 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-30 12:19:57.549  2663  2684 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-30 12:19:57.550  2663  2684 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-30 12:19:57.550  2663  2684 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-30 12:19:59.047  2663  2663 D BtGatt.ScanManager: awakened up at time 137108
,08-30 12:19:59.050  2663  2696 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 12:19:59.081  2663  2684 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,08-30 12:19:59.082  2663  2684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 12:19:59.082  2663  2684 D BtGatt.GattService: current time is 137144205680
08-30 12:19:59.083  2663  2684 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -82, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -78, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -89, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -91, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0]
,08-30 12:19:59.084  2663  2684 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-30 12:19:59.086  2663  2684 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-30 12:19:59.088  2663  2684 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-30 12:19:59.089  2663  2684 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,08-30 12:20:00.583  2663  2663 D BtGatt.ScanManager: awakened up at time 138645
08-30 12:20:00.585  2663  2696 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 12:20:00.596  2663  2684 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 12:20:00.597  2663  2684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:20:00.954  3792  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 12:20:00.955  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 12:20:00.955  3792  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 12:20:00.957  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:20:00.958  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-30 12:20:00.958  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 12:20:00.959  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 12:20:00.959  3792  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 12:20:00.959  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 12:20:00.961  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 12:20:00.961  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
08-30 12:20:00.964  3792  3841 D BluetoothAdapter: STATE_ON
08-30 12:20:00.966  2663  2675 D BtGatt.GattService: stopScan() - queue size =1
08-30 12:20:00.968  2663  2807 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 12:20:00.969  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 12:20:00.970  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 12:20:00.970  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 12:20:00.972  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 12:20:00.972  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 12:20:00.976  3792  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 12:20:00.978  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 12:20:00.978  3792  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 12:20:00.979  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 12:20:00.980  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 12:20:00.983  3792  3792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 12:20:00.983  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:20:00.984  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:20:00.984  3792  3792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 12:20:00.984  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:20:00.984  3792  3792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 12:20:00.984  3792  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d6ec9b not in the list
08-30 12:20:00.984  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:20:00.985  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
08-30 12:20:00.985  3792  3841 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:20:00.986  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:20:00.986  2663  2684 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 12:20:00.987  2663  2684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 12:20:00.987  2663  2696 D BtGatt.ScanManager: stopping BLe Batch
,08-30 12:20:00.996  2663  2684 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-30 12:20:00.996  2663  2684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 12:20:00.996  2663  2696 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 12:20:01.004  2663  2684 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-30 12:20:01.004  2663  2684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:20:01.485  3792  3792 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 12:20:05.987  3792  3841 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-30 12:20:05.992  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 12:20:06.002  3792  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:20:06.002  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:20:06.002  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:20:06.002  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:20:06.002  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:20:06.002  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:20:06.002  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:20:06.002  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:20:06.008  3792  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:20:06.009  3792  3841 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 12:20:06.010  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 12:20:06.010  3792  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-30 12:20:06.010  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 12:20:06.011  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:20:06.011  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 12:20:06.018  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:20:06.022  3792  3841 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 12:20:06.022  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 12:20:06.026  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:20:06.032  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 12:20:06.033  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 12:20:06.034  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 12:20:06.038  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 12:20:06.038  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 12:20:06.038  3792  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 12:20:06.039  3792  3841 D BluetoothAdapter: STATE_ON
,08-30 12:20:06.041  2663  2786 D BtGatt.GattService: registerClient() - UUID=feb36810-017e-44c2-abec-379540fdd148
08-30 12:20:06.042  2663  2684 D BtGatt.GattService: onClientRegistered() - UUID=feb36810-017e-44c2-abec-379540fdd148, clientIf=5
08-30 12:20:06.043  3792  3803 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 12:20:06.043  2663  2675 D BtGatt.GattService: start scan with filters
,08-30 12:20:06.046  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 12:20:06.046  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 12:20:06.046  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 12:20:06.046  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 12:20:06.047  2663  2696 D BtGatt.ScanManager: handling starting scan
,08-30 12:20:06.049  3792  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 12:20:06.050  3792  3792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 12:20:06.050  3792  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 12:20:06.052  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 12:20:06.055  3792  3841 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 12:20:06.055  2663  2684 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 12:20:06.055  2663  2684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:20:06.056  2663  2696 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 12:20:06.057  3792  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 12:20:06.057  3792  3841 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-30 12:20:06.057  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 12:20:06.058  3792  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 12:20:06.058  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:20:06.058  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-30 12:20:06.058  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-30 12:20:06.058  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 12:20:06.058  3792  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 12:20:06.058  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 12:20:06.058  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 12:20:06.058  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 12:20:06.059  3792  3841 D BluetoothAdapter: STATE_ON
,08-30 12:20:06.060  2663  2807 D BtGatt.GattService: stopScan() - queue size =1
,08-30 12:20:06.061  2663  2786 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 12:20:06.061  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 12:20:06.061  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-30 12:20:06.061  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 12:20:06.061  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED],
08-30 12:20:06.062  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 12:20:06.063  3792  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 12:20:06.064  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
08-30 12:20:06.064  3792  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 12:20:06.064  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 12:20:06.066  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 12:20:06.066  2663  2684 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 12:20:06.067  2663  2684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 12:20:06.067  2663  2696 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 12:20:06.067  2663  2696 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-30 12:20:06.069  3792  3792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 12:20:06.069  3792  3792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 12:20:06.070  3792  3792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 12:20:06.070  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:20:06.071  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:06.071  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 12:20:06.071  3792  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d6ec9b not in the list
08-30 12:20:06.071  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:20:06.071  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
08-30 12:20:06.071  3792  3841 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 12:20:06.072  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:20:06.073  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:06.073  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-30 12:20:06.074  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 12:20:06.074  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:20:06.074  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:20:06.074  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
,08-30 12:20:06.075  3792  3841 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 12:20:06.077  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:20:06.082  3792  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:20:06.082  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true,
08-30 12:20:06.082  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:20:06.082  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:20:06.082  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:20:06.082  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:20:06.082  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:20:06.082  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true,
08-30 12:20:06.085  3792  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:20:06.086  3792  3841 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:20:06.087  2663  2684 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 12:20:06.087  2663  2684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 12:20:06.087  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 12:20:06.090  3792  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-30 12:20:06.090  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:20:06.090  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 12:20:06.091  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 12:20:06.095  2663  2684 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 12:20:06.095  2663  2684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-30 12:20:06.096  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 12:20:06.096  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:20:06.102  3792  3841 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 12:20:06.102  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 12:20:06.105  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 12:20:06.106  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 12:20:06.106  2663  2684 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-30 12:20:06.107  2663  2684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:20:06.107  2663  2696 D BtGatt.ScanManager: stopping BLe Batch
08-30 12:20:06.107  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,08-30 12:20:06.110  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 12:20:06.110  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 12:20:06.110  3792  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 12:20:06.111  3792  3841 D BluetoothAdapter: STATE_ON
,08-30 12:20:06.113  2663  2675 D BtGatt.GattService: registerClient() - UUID=587338a2-d7e3-452d-b56d-b09b55429b85
08-30 12:20:06.113  2663  2684 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 12:20:06.113  2663  2684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 12:20:06.114  2663  2696 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 12:20:06.114  2663  2684 D BtGatt.GattService: onClientRegistered() - UUID=587338a2-d7e3-452d-b56d-b09b55429b85, clientIf=5
,08-30 12:20:06.114  3792  3804 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 12:20:06.114  2663  2674 D BtGatt.GattService: start scan with filters
,08-30 12:20:06.117  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 12:20:06.117  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 12:20:06.117  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 12:20:06.117  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-30 12:20:06.119  2663  2684 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 12:20:06.119  3792  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 12:20:06.120  3792  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 12:20:06.120  3792  3792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 12:20:06.120  2663  2684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 12:20:06.121  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 12:20:06.121  2663  2696 D BtGatt.ScanManager: handling starting scan
,08-30 12:20:06.125  3792  3841 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 12:20:06.127  2663  2684 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 12:20:06.127  2663  2684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:20:06.127  2663  2696 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 12:20:06.132  2663  2684 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-30 12:20:06.132  2663  2684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 12:20:06.133  2663  2696 D BtGatt.ScanManager: Starting BLE batch scan
08-30 12:20:06.133  2663  2696 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 12:20:06.143  2663  2684 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 12:20:06.144  2663  2684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:20:06.150  2663  2684 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 12:20:06.150  2663  2684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:20:06.621  3792  3792 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-30 12:20:06.621  3792  3792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 12:20:06.621  3792  3792 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 12:20:07.658  2663  2663 D BtGatt.ScanManager: awakened up at time 145719
,08-30 12:20:07.660  2663  2696 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 12:20:07.697  2663  2684 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,08-30 12:20:07.697  2663  2684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 12:20:07.697  2663  2684 D BtGatt.GattService: current time is 145759224009
08-30 12:20:07.699  2663  2684 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -81, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -78, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -83, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -88, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -90, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -84, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 53, 33, -121, 80, 73, -44, 1, 0, -107, 22, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -59, -60, 94, 117, -73, -4, -67, 70, -2, -72, -18, 2, 2, -29, 21, 63, -1, -107, 123, 28, 6, 8, 116, 105, 115, 54, 69, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
08-30 12:20:07.700  2663  2684 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-30 12:20:07.702  2663  2684 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-30 12:20:07.704  2663  2684 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-30 12:20:07.706  2663  2684 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-30 12:20:07.707  2663  2684 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-30 12:20:07.709  2663  2684 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-30 12:20:07.710  2663  2684 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -59, -60, 94, 117, -73, -4, -67, 70, -2, -72, -18, 2, 2, -29, 21, 63, -1, -107, 123, 6, 8, 116, 105, 115, 54, 69, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
,08-30 12:20:09.203  2663  2663 D BtGatt.ScanManager: awakened up at time 147264
,08-30 12:20:09.206  2663  2696 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 12:20:09.255  2663  2684 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-30 12:20:09.256  2663  2684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:20:09.256  2663  2684 D BtGatt.GattService: current time is 147318228736
,08-30 12:20:09.257  2663  2684 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -81, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -78, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -66, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -91, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -76, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0]
08-30 12:20:09.258  2663  2684 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-30 12:20:09.259  2663  2684 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-30 12:20:09.260  2663  2684 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
08-30 12:20:09.261  2663  2684 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
08-30 12:20:09.262  2663  2684 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,08-30 12:20:10.771  2663  2663 D BtGatt.ScanManager: awakened up at time 148833
,08-30 12:20:10.774  2663  2696 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 12:20:10.821  2663  2684 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-30 12:20:10.821  2663  2684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:20:11.074  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:20:11.101  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:20:11.107  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:20:11.127  3792  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 12:20:11.128  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything,
08-30 12:20:11.128  3792  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 12:20:11.128  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:20:11.129  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 12:20:11.129  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-30 12:20:11.129  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 12:20:11.129  3792  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 12:20:11.130  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 12:20:11.130  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 12:20:11.130  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 12:20:11.133  3792  3841 D BluetoothAdapter: STATE_ON
08-30 12:20:11.134  2663  2675 D BtGatt.GattService: stopScan() - queue size =1
,08-30 12:20:11.136  2663  2674 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 12:20:11.137  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 12:20:11.137  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 12:20:11.138  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 12:20:11.138  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-30 12:20:11.138  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 12:20:11.141  3792  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 12:20:11.142  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 12:20:11.142  3792  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 12:20:11.142  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 12:20:11.143  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 12:20:11.149  3792  3792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 12:20:11.150  3792  3792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 12:20:11.150  3792  3792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 12:20:11.158  2663  2684 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-30 12:20:11.158  2663  2684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:20:11.158  2663  2696 D BtGatt.ScanManager: stopping BLe Batch
,08-30 12:20:11.167   873  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-30 12:20:11.170  2663  2684 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-30 12:20:11.170  2663  2684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 12:20:11.170  2663  2696 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 12:20:11.175  1509  1529 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 12:20:11.175  1509  1529 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-30 12:20:11.176  1509  1529 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 12:20:11.176  1509  1529 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 12:20:11.184  2663  2684 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-30 12:20:11.184  2663  2684 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:20:11.203  3508  3508 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-30 12:20:11.203  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-30 12:20:11.206  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-30 12:20:11.650  3792  3792 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 12:20:11.650  3792  3792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
,08-30 12:20:11.651  3792  3792 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 12:20:11.935   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-30 12:20:11.943  1870  1870 I Keyboard.Facilitator: onFinishInput()
,08-30 12:20:11.960   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 12:20:11.960   873   893 I Adreno  : Build Date                       : 10/20/15
08-30 12:20:11.960   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 12:20:11.960   873   893 I Adreno  : Local Branch                     : M14
08-30 12:20:11.960   873   893 I Adreno  : Remote Branch                    : 
08-30 12:20:11.960   873   893 I Adreno  : Remote Branch                    : 
08-30 12:20:11.960   873   893 I Adreno  : Reconstruct Branch               : 
,08-30 12:20:11.996   283   308 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (195 us)
,08-30 12:20:12.604  3792  3792 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 12:20:12.604  3792  3792 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-30 12:20:12.655   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-30 12:20:12.657  3792  3792 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@45535f3 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@8c305a, 16908290=android.view.AbsSavedState$1@8c305a}, android:focusedViewId=100}]}]
,08-30 12:20:12.658  3792  3792 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-30 12:20:12.658  3792  3792 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-30 12:20:12.659  3792  3792 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-30 12:20:12.660   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-30 12:20:12.665   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-30 12:20:12.668   283   283 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
,08-30 12:20:12.668   283   283 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-30 12:20:12.902   283   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-30 12:20:12.906   283   283 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-30 12:20:12.907   873  1329 D SurfaceControl: Excessive delay in setPowerMode(): 241ms
,08-30 12:20:12.912   873   893 I DreamManagerService: Entering dreamland.
,08-30 12:20:12.914   873   893 I PowerManagerService: Dozing...
,08-30 12:20:12.915   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-30 12:20:12.981   376   376 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
08-30 12:20:12.981   376   376 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-30 12:20:12.995   873  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 12:20:13.005  1927  3863 D NfcService: Discovery configuration equal, not updating.
,08-30 12:20:13.011   873  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-30 12:20:13.014   873  1306 E native  : do suspend false
,08-30 12:20:13.035   873  1306 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 12:20:13.048   873  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 12:20:13.051   873  1306 E native  : do suspend true
,08-30 12:20:13.120   376  1279 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-30 12:20:13.120   376  1279 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-30 12:20:13.500   873  1306 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,08-30 12:20:16.150  3792  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 12:20:16.151  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 12:20:16.152  3792  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:20:16.152  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:20:16.152  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:20:16.153  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:20:16.153  3792  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d6ec9b not in the list
08-30 12:20:16.153  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 12:20:16.154  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
,08-30 12:20:16.154  3792  3841 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:20:16.154  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:20:16.156  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:20:16.156  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:20:16.162  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:20:16.163  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:20:16.163  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:20:16.163  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
,08-30 12:20:16.166  3792  3841 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-30 12:20:16.168  3792  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 12:20:16.168  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 12:20:16.169  3792  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 12:20:16.170  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:20:16.170  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:20:16.170  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:20:16.170  3792  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d6ec9b not in the list
08-30 12:20:16.170  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:20:16.170  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
08-30 12:20:16.170  3792  3841 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:20:16.170  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:20:16.170  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:20:16.170  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:16.170  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:20:16.172  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:20:16.172  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:20:16.172  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:20:16.172  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
,08-30 12:20:16.174  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 12:20:16.174  3792  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:20:16.174  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:20:16.174  3792  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 12:20:16.175  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:20:16.175  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:16.175  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:20:16.175  3792  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d6ec9b not in the list
,08-30 12:20:16.176  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:20:16.176  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
08-30 12:20:16.176  3792  3841 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:20:16.176  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:16.176  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:20:16.176  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:20:16.176  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:20:16.178  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:20:16.178  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:20:16.178  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:20:16.179  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
,08-30 12:20:16.180  3792  3841 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-30 12:20:16.181  3792  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:20:16.181  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 12:20:16.181  3792  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:20:16.182  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:20:16.182  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:16.182  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:20:16.183  3792  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d6ec9b not in the list
08-30 12:20:16.183  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:20:16.183  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
,08-30 12:20:16.183  3792  3841 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:20:16.183  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:16.184  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:20:16.184  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:20:16.184  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:20:16.186  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 12:20:16.187  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:20:16.187  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:20:16.187  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
,08-30 12:20:16.189  3792  3841 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-30 12:20:16.189  3792  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:20:16.190  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 12:20:16.190  3792  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:20:16.190  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 12:20:16.190  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:16.191  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:20:16.191  3792  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d6ec9b not in the list
08-30 12:20:16.191  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:20:16.191  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
,08-30 12:20:16.192  3792  3841 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:20:16.192  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:16.192  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:20:16.192  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:16.193  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:20:16.195  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 12:20:16.195  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:20:16.196  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 12:20:16.196  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
,08-30 12:20:16.198  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-30 12:20:16.198  3792  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 12:20:16.198  3792  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 12:20:16.199  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 12:20:16.199  3792  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-30 12:20:16.199  3792  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 12:20:16.200  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-30 12:20:16.200  3792  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 12:20:16.200  3792  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 12:20:16.201  3792  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 12:20:16.201  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:20:16.201  3792  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 12:20:16.201  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 12:20:16.203  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:16.204  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:20:16.204  3792  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d6ec9b not in the list
08-30 12:20:16.204  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 12:20:16.205  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
,08-30 12:20:16.205  3792  3841 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:20:16.206  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:16.206  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:20:16.206  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:20:16.207  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:20:16.210  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 12:20:16.210  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:20:16.210  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:20:16.210  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
08-30 12:20:16.213  3792  3841 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 12:20:16.213  3792  3841 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 12:20:16.213  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-30 12:20:16.218  3792  3841 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-30 12:20:16.219  3792  3841 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-30 12:20:16.219  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 12:20:16.219  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 12:20:16.219  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 12:20:16.220  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-30 12:20:16.220  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 12:20:16.220  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 12:20:16.220  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 12:20:16.220  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-30 12:20:16.220  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 12:20:16.220  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 12:20:16.220  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 12:20:16.220  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-30 12:20:16.221  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 12:20:16.221  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 12:20:16.221  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 12:20:16.221  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 12:20:16.221  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 12:20:16.221  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-30 12:20:16.221  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-30 12:20:16.222  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-30 12:20:16.222  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-30 12:20:16.222  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 12:20:16.223  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 12:20:16.223  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 12:20:16.223  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 12:20:16.223  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 12:20:16.223  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-30 12:20:16.223  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-30 12:20:16.224  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 12:20:16.224  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 12:20:16.224  3792  3841 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,08-30 12:20:16.225  3792  3841 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 12:20:16.226  3792  3841 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-30 12:20:16.226  3792  3841 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 12:20:16.226  3792  3841 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-30 12:20:16.226  3792  3841 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,08-30 12:20:16.226  3792  3841 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 12:20:16.226  3792  3841 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 12:20:16.227  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-30 12:20:16.233  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-30 12:20:16.235  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,08-30 12:20:16.235  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-30 12:20:16.236  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-30 12:20:16.237  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-30 12:20:16.237  3792  3841 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-30 12:20:16.237  3792  3841 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 12:20:16.237  3792  3841 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-30 12:20:16.238  3792  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 12:20:16.238  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:20:16.238  3792  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:20:16.238  3792  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 394)
,08-30 12:20:16.238  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:20:16.238  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:16.238  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:20:16.239  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-30 12:20:16.239  3792  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d6ec9b not in the list
,08-30 12:20:16.240  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:20:16.240  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
08-30 12:20:16.240  3792  3841 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 12:20:16.240  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:20:16.240  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:20:16.240  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:16.240  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:20:16.241  3792  3867 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 12:20:16.241  3792  3868 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 394
08-30 12:20:16.242  3792  3868 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 394)
08-30 12:20:16.242  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:20:16.242  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 12:20:16.243  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:20:16.242  3792  3868 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 394)
08-30 12:20:16.243  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
08-30 12:20:16.246  3792  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 394)
,08-30 12:20:16.247  3792  3841 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-30 12:20:16.248  3792  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 12:20:16.249  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:20:16.249  3792  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 12:20:16.249  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 12:20:16.249  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:16.249  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:20:16.249  3792  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d6ec9b not in the list
08-30 12:20:16.249  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:20:16.249  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
08-30 12:20:16.249  3792  3841 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:20:16.249  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:16.249  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:20:16.249  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:16.250  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:20:16.251  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:20:16.251  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:20:16.251  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:20:16.251  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
08-30 12:20:16.252  3792  3841 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-30 12:20:16.252  3792  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 12:20:16.252  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:20:16.252  3792  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:20:16.252  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:20:16.252  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:16.252  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:20:16.253  3792  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d6ec9b not in the list
08-30 12:20:16.253  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:20:16.253  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
08-30 12:20:16.253  3792  3841 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 12:20:16.253  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:16.253  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:20:16.253  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:16.253  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:20:16.254  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:20:16.254  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:20:16.254  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:20:16.254  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
,08-30 12:20:16.255  3792  3841 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-30 12:20:16.255  3792  3841 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-30 12:20:16.255  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 12:20:16.255  3792  3841 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-30 12:20:16.256  3792  3841 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 12:20:16.256  3792  3841 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-30 12:20:16.256  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 12:20:16.256  3792  3841 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,08-30 12:20:16.256  3792  3841 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 12:20:16.256  3792  3841 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 12:20:16.256  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 12:20:16.256  3792  3841 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-30 12:20:16.256  3792  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:20:16.256  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:20:16.256  3792  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:20:16.257  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 12:20:16.257  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:16.257  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:20:16.257  3792  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d6ec9b not in the list
08-30 12:20:16.257  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:20:16.257  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
08-30 12:20:16.257  3792  3841 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:20:16.257  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:16.257  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:20:16.257  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:20:16.257  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:20:16.258  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:20:16.259  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:20:16.259  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 12:20:16.259  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
08-30 12:20:16.259  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:20:16.259  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:16.259  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:20:16.259  3792  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d6ec9b not in the list
08-30 12:20:16.260  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:20:16.260  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
08-30 12:20:16.260  3792  3841 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:20:16.260  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:16.260  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:20:18.104  2069  2647 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-30 12:20:20.763  3018  3870 V KeepSync: Connecting to GoogleApiClient
,08-30 12:20:20.765   873  1966 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-30 12:20:20.847  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:20:20.853  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:20:20.893  1509  2256 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-30 12:20:20.894  1509  2256 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-30 12:20:20.894  1509  2256 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 12:20:20.895  1509  2256 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 12:20:20.928  1727  3871 V BaseAuthAsyncOperation: access token request failed
08-30 12:20:20.930  3018  3870 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-30 12:20:21.012  1509  2986 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-30 12:20:21.012  1509  2986 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-30 12:20:21.013  1509  2986 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 12:20:21.013  1509  2986 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 12:20:21.040  3018  3870 E KeepSync: IOException
08-30 12:20:21.040  3018  3870 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-30 12:20:21.040  3018  3870 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-30 12:20:21.040  3018  3870 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-30 12:20:21.040  3018  3870 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-30 12:20:21.040  3018  3870 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-30 12:20:21.040  3018  3870 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-30 12:20:21.040  3018  3870 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-30 12:20:21.040  3018  3870 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-30 12:20:21.040  3018  3870 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-30 12:20:21.040  3018  3870 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-30 12:20:21.040  3018  3870 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-30 12:20:21.040  3018  3870 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-30 12:20:21.040  3018  3870 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-30 12:20:21.040  3018  3870 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-30 12:20:21.040  3018  3870 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 12:20:21.040  3018  3870 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 12:20:21.040  3018  3870 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-30 12:20:21.040  3018  3870 E KeepSync: 	... 10 more
,08-30 12:20:21.040  3018  3870 W KeepSync: Sync result 2
,08-30 12:20:21.053   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 129434, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 12:20:21.261  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:20:21.261  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
08-30 12:20:21.262  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:20:21.262  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:21.262  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:20:21.263  3792  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d6ec9b not in the list
,08-30 12:20:21.263  3792  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 12:20:21.263  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 12:20:21.264  3792  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 12:20:21.264  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 12:20:21.264  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:20:21.265  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:20:21.265  3792  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d6ec9b not in the list
08-30 12:20:21.265  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 12:20:21.266  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
08-30 12:20:21.266  3792  3841 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 12:20:21.266  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:21.267  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:20:21.267  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:20:21.267  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:20:21.271  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 12:20:21.271  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:20:21.271  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:20:21.272  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
08-30 12:20:21.276  3792  3841 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-30 12:20:21.277  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:20:21.280  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 12:20:21.282  3792  3841 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 12:20:21.283  3792  3841 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-30 12:20:21.283  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 12:20:21.283  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 12:20:21.283  3792  3792 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 12:20:21.284  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:20:21.284  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-30 12:20:21.284  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 12:20:21.284  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 12:20:21.284  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:20:21.284  3792  3841 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-30 12:20:21.284  3792  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d6ec9b not in the list
,08-30 12:20:21.284  3792  3792 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-30 12:20:21.284  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:20:21.284  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 12:20:21.284  3792  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 12:20:21.284  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 12:20:21.285  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:20:21.285  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:20:21.288  3792  3872 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback,
08-30 12:20:21.288  3792  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 12:20:21.289  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
,08-30 12:20:21.289  3792  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 12:20:21.289  3792  3792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 12:20:21.289  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 12:20:21.289  3792  3792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 12:20:21.289  3792  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:20:21.289  3792  3792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 12:20:21.289  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:20:21.289  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:21.289  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:20:21.289  3792  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d6ec9b not in the list
08-30 12:20:21.289  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:20:21.289  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
08-30 12:20:21.290  3792  3841 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:20:21.290  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:21.290  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:20:21.290  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:21.290  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:20:21.291  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:20:21.291  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:20:21.291  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:20:21.291  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
08-30 12:20:21.292  3792  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-30 12:20:21.292  3792  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 12:20:21.292  3792  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 12:20:21.292  3792  3792 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 12:20:21.293  3792  3841 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-30 12:20:21.293  3792  3841 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 12:20:21.293  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 12:20:21.294  3792  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 12:20:21.294  3792  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 12:20:21.294  3792  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:20:21.294  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:20:21.294  3792  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:20:21.294  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:20:21.294  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:21.294  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:20:21.295  3792  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d6ec9b not in the list
08-30 12:20:21.295  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:20:21.295  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
,08-30 12:20:21.295  3792  3841 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:20:21.295  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:21.295  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:20:21.295  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:21.295  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:20:21.297  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:20:21.297  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:20:21.297  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:20:21.297  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
08-30 12:20:21.301  3792  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:20:21.301  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:20:21.301  3792  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:20:21.301  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:20:21.301  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:21.302  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:20:21.302  3792  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d6ec9b not in the list
08-30 12:20:21.302  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:20:21.302  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
08-30 12:20:21.302  3792  3841 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:20:21.302  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:21.302  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:20:21.302  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:21.302  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:20:21.303  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:20:21.304  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:20:21.304  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:20:21.304  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
08-30 12:20:21.305  3792  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:20:21.305  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:20:21.305  3792  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:20:21.305  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:20:21.305  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:21.305  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:20:21.305  3792  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d6ec9b not in the list
08-30 12:20:21.305  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:20:21.305  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
08-30 12:20:21.306  3792  3841 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:20:21.306  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:21.306  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:20:21.306  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:21.306  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:20:21.307  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:20:21.307  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:20:21.307  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:20:21.307  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c2838 not in the list
08-30 12:20:21.309  3792  3841 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-30 12:20:21.309  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 12:20:21.309  3792  3841 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-30 12:20:21.309  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 12:20:21.309  3792  3841 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-30 12:20:21.309  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 12:20:21.312  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 12:20:21.312  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-30 12:20:21.313  3792  3841 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-30 12:20:21.313  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 12:20:21.313  3792  3841 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-30 12:20:21.313  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 12:20:21.314  3792  3841 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-30 12:20:21.314  3792  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-30 12:20:21.314  3792  3841 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-30 12:20:21.314  3792  3841 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-30 12:20:21.315  3792  3841 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-30 12:20:21.315  3792  3841 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-30 12:20:21.315  3792  3841 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-30 12:20:21.315  3792  3841 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-30 12:20:21.316  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:20:21.317  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@208328b added. We now have 3 listener(s)
08-30 12:20:21.317  3792  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 12:20:21.319  3792  3841 D BluetoothAdapter: enable(): BT is already enabled..!
08-30 12:20:21.319   873  1935 D WifiService: setWifiEnabled: true pid=3792, uid=10000
08-30 12:20:21.319   873  1935 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 12:20:21.372  2663  2764 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
08-30 12:20:21.372  2663  2783 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,08-30 12:20:21.790  3792  3792 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 12:20:24.242   873  1306 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,08-30 12:20:26.326  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 12:20:26.327  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f660f68 added. We now have 4 listener(s)
08-30 12:20:26.327  3792  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:20:26.343  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:20:26.343  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f660f68 removed from the list
,08-30 12:20:26.344  3792  3841 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 12:20:26.344  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:20:26.344  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:20:26.347  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:20:26.347  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9966f81 added. We now have 4 listener(s)
,08-30 12:20:26.347  3792  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:20:26.351  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 12:20:26.351  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9966f81 removed from the list
08-30 12:20:26.352  3792  3841 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 12:20:26.352  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:26.352  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:20:26.354  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:20:26.356  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9ccf826 added. We now have 4 listener(s)
,08-30 12:20:26.356  3792  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 12:20:26.364   873  3738 D WifiService: setWifiEnabled: false pid=3792, uid=10000
08-30 12:20:26.364   873  3738 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 12:20:26.377  2663  2680 D BluetoothAdapterState: Current state: ON, message: 23
,08-30 12:20:26.378  2663  2680 D BluetoothAdapterProperties: Setting state to 13
,08-30 12:20:26.378  2663  2680 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-30 12:20:26.380  2663  2680 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 12:20:26.378  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 12:20:26.384  2663  2680 I BluetoothAdapterState: Entering PendingCommandState
,08-30 12:20:26.387  2663  2684 D BluetoothAdapterProperties: Scan Mode:20
,08-30 12:20:26.387  2663  2680 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-30 12:20:26.390  2663  2663 D HeadsetService: Received stop request...Stopping profile...
,08-30 12:20:26.391  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 12:20:26.392  3792  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:20:26.392  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:20:26.392  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:20:26.392  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:20:26.392  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:20:26.392  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:20:26.392  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:20:26.392  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:20:26.395  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:20:26.395  3792  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:20:26.395  3792  3841 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:20:26.401  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:20:26.404  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:20:26.408  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 12:20:26.408  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:20:26.408  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:20:26.408  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:20:26.408  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:20:26.408  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:20:26.408  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:20:26.408  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:20:26.408  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:20:26.409  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 12:20:26.409  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:20:26.410  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-30 12:20:26.412   873  1306 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-30 12:20:26.412   873  1306 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-30 12:20:26.412   873  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 12:20:26.412   873  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 12:20:26.413  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 12:20:26.413  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:20:26.413  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:20:26.413  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:20:26.413  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:20:26.413  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:20:26.413  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:20:26.413  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:20:26.413  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:20:26.414  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 12:20:26.414  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:20:26.417  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:20:26.419  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:20:26.422   873   886 I ActivityManager: Start proc 3876:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-30 12:20:26.425  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:20:26.424   873   873 D BluetoothHeadset: Proxy object disconnected
,08-30 12:20:26.425   873   873 D BluetoothHeadset: Proxy object disconnected
08-30 12:20:26.426  1362  2057 D BluetoothHeadset: Proxy object disconnected
08-30 12:20:26.426  1362  1362 D HeadsetProfile: Bluetooth service disconnected
08-30 12:20:26.426  1940  2133 D BluetoothHeadset: Proxy object disconnected
08-30 12:20:26.427   873   873 D BluetoothHeadset: Proxy object disconnected
,08-30 12:20:26.427  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:20:26.428  2663  2663 D A2dpService: Received stop request...Stopping profile...
08-30 12:20:26.429  2663  2801 D A2dpStateMachine: Exit Disconnected: -1
08-30 12:20:26.430   873   873 D BluetoothA2dp: Proxy object disconnected
,08-30 12:20:26.432  2663  2663 D BluetoothMapService: onReceive
08-30 12:20:26.432  2663  2663 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:20:26.432  2663  2663 D BluetoothMapService: STATE_TURNING_OFF
08-30 12:20:26.432  2663  2663 V BluetoothAdapterState: isTurningOff()=true
08-30 12:20:26.433  2663  2663 V BluetoothAdapterState: isTurningOn()=false
08-30 12:20:26.433  2663  2663 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:20:26.432  1362  1362 D BluetoothA2dp: Proxy object disconnected
08-30 12:20:26.433  2663  2663 V BluetoothAdapterState: isBleTurningOff()=false,
,08-30 12:20:26.433  2663  2663 D HidService: Received stop request...Stopping profile...
,08-30 12:20:26.433  2663  2663 D HidService: Stopping Bluetooth HidService
08-30 12:20:26.434   873  1306 E native  : do suspend true
08-30 12:20:26.434  1362  1362 D BluetoothInputDevice: Proxy object disconnected
08-30 12:20:26.435  1362  1362 D HidProfile: Bluetooth service disconnected
08-30 12:20:26.436  2663  2663 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 12:20:26.436  2663  2684 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-30 12:20:26.436  2663  2663 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 12:20:26.436  2663  2764 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 12:20:26.436  2663  2764 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 12:20:26.436  2663  2764 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 12:20:26.437  2663  2684 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-30 12:20:26.437  2663  2663 D HealthService: Received stop request...Stopping profile...
,08-30 12:20:26.441  2663  2663 D PanService: Received stop request...Stopping profile...
08-30 12:20:26.442  1362  1362 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 12:20:26.442  1362  1362 D PanProfile: Bluetooth service disconnected
,08-30 12:20:26.443  2663  2663 D BluetoothMapService: Received stop request...Stopping profile...
,08-30 12:20:26.443  2663  2663 D BluetoothMapService: stop()
,08-30 12:20:26.444  2663  2663 D BluetoothMapAppObserver: deinitObservers()
,08-30 12:20:26.444  2663  2663 D BluetoothMapAppObserver: removeReceiver()
08-30 12:20:26.444   873  1842 D DhcpClient: Clearing IP address
,08-30 12:20:26.444   372   871 D CommandListener: Clearing all IP addresses on wlan0
08-30 12:20:26.446  1362  1362 D BluetoothMap: Proxy object disconnected
,08-30 12:20:26.446  1362  1362 D MapProfile: Bluetooth service disconnected
08-30 12:20:26.446  2663  2663 V BluetoothAdapterState: isTurningOff()=true
,08-30 12:20:26.446  2663  2663 V BluetoothAdapterState: isTurningOn()=false
,08-30 12:20:26.446  2663  2663 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 12:20:26.446  2663  2663 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:20:26.448   372   871 D CommandListener: Setting iface cfg
,08-30 12:20:26.451  2663  2684 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-30 12:20:26.451  2663  2764 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 12:20:26.452  2663  2764 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 12:20:26.452  2663  2764 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 12:20:26.452  2663  2764 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 12:20:26.452  2663  2764 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 12:20:26.452  2663  2764 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 12:20:26.452   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-30 12:20:26.452   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-30 12:20:26.453  2663  2663 I BtOppRfcommListener: stopping Accept Thread
08-30 12:20:26.453  2663  3424 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 12:20:26.454   873  1306 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-30 12:20:26.454   873  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 12:20:26.454   873  1306 E native  : do suspend true
08-30 12:20:26.455  2663  3424 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-30 12:20:26.456   396   396 E Parcel  : Reading a NULL string not supported here.
08-30 12:20:26.458  1509  2461 V NativeCrypto: Read error: ssl=0x9ae42c00: I/O error during system call, Connection timed out
08-30 12:20:26.460  2663  2663 V BluetoothAdapterState: isTurningOff()=true
08-30 12:20:26.460  2663  2663 V BluetoothAdapterState: isTurningOn()=false
,08-30 12:20:26.460  2663  2663 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 12:20:26.460  2663  2663 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:20:26.460  2663  2663 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 12:20:26.460   873  1308 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-30 12:20:26.460  2663  2663 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 12:20:26.460  2663  2684 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-30 12:20:26.460  2663  2663 V BluetoothAdapterState: isTurningOff()=true
08-30 12:20:26.460  2663  2663 V BluetoothAdapterState: isTurningOn()=false
08-30 12:20:26.461  2663  2663 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:20:26.463  2663  2663 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 12:20:26.463  1509  2461 V NativeCrypto: SSL shutdown failed: ssl=0x9ae42c00: I/O error during system call, Broken pipe
08-30 12:20:26.464  2663  2663 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 12:20:26.464  2663  2684 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-30 12:20:26.465  2663  2663 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 12:20:26.465  2663  2663 V BluetoothAdapterState: isTurningOff()=true
08-30 12:20:26.465  2663  2663 V BluetoothAdapterState: isTurningOn()=false
08-30 12:20:26.465  2663  2663 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 12:20:26.465  2663  2663 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:20:26.466  2663  2663 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 12:20:26.466  2663  2663 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 12:20:26.467  2663  2663 D BluetoothMapService: MAP Service closeService in
08-30 12:20:26.467  2663  2663 D BluetoothMapMasInstance0: MAP Service shutdown
08-30 12:20:26.467  2663  2663 D ObexServerSockets0: shutdown(block = true)
08-30 12:20:26.467  2663  2821 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-30 12:20:26.468  2663  2663 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 12:20:26.468  2663  2783 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-30 12:20:26.468  2663  2822 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-30 12:20:26.469  2663  2663 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 12:20:26.469  2663  2663 V BluetoothAdapterState: isTurningOff()=true
08-30 12:20:26.469  2663  2663 V BluetoothAdapterState: isTurningOn()=false
08-30 12:20:26.469  2663  2663 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:20:26.469  2663  2663 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 12:20:26.469  2663  2680 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-30 12:20:26.469  2663  2680 D BluetoothAdapterProperties: Setting state to 15
08-30 12:20:26.469  2663  2680 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-30 12:20:26.470  2663  2680 I BluetoothAdapterState: Entering BleOnState
08-30 12:20:26.470   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 12:20:26.470   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:20:26.470  2663  2663 D BluetoothMapService: cleanup()
08-30 12:20:26.470  2663  2663 D BluetoothMapService: MAP Service closeService in
08-30 12:20:26.470  1362  2057 D BluetoothPan: onBluetoothStateChange on: false
08-30 12:20:26.471  1940  1952 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:20:26.471  1362  1375 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 12:20:26.472   873  1847 D DhcpClient: Receive thread stopped
08-30 12:20:26.473  1362  1376 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:20:26.473   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:20:26.473  1362  2057 D BluetoothMap: onBluetoothStateChange: up=false
,08-30 12:20:26.474   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:20:26.474  1362  1375 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 12:20:26.474  1362  1376 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 12:20:26.475  2663  2680 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-30 12:20:26.475  2663  2680 D BluetoothAdapterProperties: Setting state to 16
08-30 12:20:26.475  2663  2680 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-30 12:20:26.475  2663  2680 D BluetoothAdapterProperties: onBleDisable
08-30 12:20:26.476  2663  2680 I BluetoothAdapterState: Entering PendingCommandState
08-30 12:20:26.476  2663  2681 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-30 12:20:26.477  2663  2684 D BluetoothAdapterProperties: Scan Mode:20
08-30 12:20:26.477  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:20:26.477  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:20:26.477  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:20:26.477  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:20:26.477  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:20:26.477  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:20:26.477  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:20:26.477  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:20:26.477  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:20:26.478  2663  2764 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-30 12:20:26.478  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 12:20:26.478  2663  2764 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 12:20:26.478  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:20:26.479  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:20:26.480  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:20:26.480  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:20:26.480  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:20:26.480  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:20:26.480  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:20:26.480  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:20:26.480  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:20:26.480  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:20:26.480  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:20:26.480  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:20:26.482  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:20:26.482  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:20:26.482  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:20:26.482  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:20:26.482  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:20:26.482  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:20:26.482  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:20:26.482  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:20:26.482  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:20:26.482  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:20:26.482  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:20:26.484  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:20:26.485  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:20:26.485  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:20:26.493   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 12:20:26.498  3876  3876 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-30 12:20:26.508  3876  3876 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 12:20:26.511   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 12:20:26.511   372   871 D CommandListener: Clearing all IP addresses on wlan0
08-30 12:20:26.512   873  1308 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-30 12:20:26.512   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 12:20:26.515   873   890 D Tethering: MasterInitialState.processMessage what=3
08-30 12:20:26.516  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:20:26.517  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:20:26.518   873  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-30 12:20:26.518  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:20:26.521  3394  3394 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@bce2e9 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-30 12:20:26.522  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 12:20:26.528   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bb19ca6:true
,08-30 12:20:26.535   873  1925 I ActivityManager: Start proc 3894:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-30 12:20:26.537   873  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 12:20:26.539   873  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 12:20:26.539  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:20:26.540  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:20:26.540  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:20:26.540  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:20:26.540  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:20:26.540  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:20:26.540  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:20:26.540  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:20:26.540  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:20:26.540  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:20:26.540  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:20:26.541  2069  2311 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:20:26.542  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 12:20:26.542  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:20:26.542  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:20:26.542  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:20:26.542  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:20:26.542  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:20:26.542  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:20:26.542  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:20:26.542  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:20:26.542  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:20:26.542  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:20:26.544  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:20:26.544  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:20:26.544  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:20:26.544  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:20:26.544  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:20:26.544  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:20:26.544  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:20:26.544  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:20:26.544  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 12:20:26.544  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:20:26.544  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 12:20:26.572   372   871 E Netd    : netlink response contains error (No such file or directory)
,08-30 12:20:26.573   873  1308 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-30 12:20:26.576  3894  3894 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-30 12:20:26.577  3876  3876 D LocalBluetoothProfileManager: Adding local MAP profile
,08-30 12:20:26.579  3876  3876 D BluetoothMap: Create BluetoothMap proxy object
,08-30 12:20:26.587  3876  3876 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-30 12:20:26.599  3876  3876 D DockEventReceiver: finishStartingService: stopping service
,08-30 12:20:26.607   873   884 I ActivityManager: Killing 3394:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-30 12:20:26.682  2663  2684 I bt_hci  : shut_down
,08-30 12:20:26.704  2663  2701 I bt_vendor: low_power_mode_cb
,08-30 12:20:26.707  2663  2701 D bt_hwcfg: hw_epilog_process
,08-30 12:20:26.726  2663  2701 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-30 12:20:26.727  2663  2701 I bt_vendor: epilog_cb
,08-30 12:20:26.727  2663  2701 I bt_hci  : epilog_finished_callback
,08-30 12:20:26.730  2663  2684 I bt_hci_h4: hal_close
,08-30 12:20:26.731  2663  2684 I bt_userial_vendor: device fd = 51 close
,08-30 12:20:26.778  3894  3894 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 12:20:26.778  3894  3894 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:20:26.778  3894  3894 D StrictMode: ,	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 12:20:26.778  3894  3894 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 12:20:26.778  3894  3894 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 12:20:26.778  3894  3894 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 12:20:26.778  3894  3894 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.shared.f,.a.a(PG:48)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:20:26.778  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726),
08-30 12:20:26.778  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 12:20:26.779  3894  3894 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 12:20:26.779  3894  3894 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
,08-30 12:20:26.779  3894  3894 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
,08-30 12:20:26.779  3894  3894 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-30 12:20:26.779  3894  3894 D StrictMode: ,	at com.google.r.k.a(PG:2107)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-30 12:20:26.779  3894  3894 D StrictMode: 	,at com.google.w.a.a.do.a(PG:405)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-30 12:20:26.779  3894  3894 D StrictMode: ,	at com.google.r.e.b(PG:170)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-30 12:20:26.779  3894  3894 D StrictMode: 	,at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48),
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
,08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 12:20:26.779  3894  3894 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 12:20:26.779  3894  3894 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.r.k.d(PG:583)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013),
08-30 12:20:26.779  3894  3894 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
,08-30 12:20:26.779  3894  3894 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,08-30 12:20:26.779  3894  3894 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 12:20:26.779  3894  3894 D StrictMode: 	,at java.lang.reflect.Method.invoke(Native Method)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 12:20:26.779  3894  3894 D StrictMode: StrictMode policy violation; ~duration=61 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 12:20:26.779  3894  3894 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263),
08-30 12:20:26.779  3894  3894 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at java.io.File.doAccess(File.java:281)
,08-30 12:20:26.779  3894  3894 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-30 12:20:26.779  3894  3894 D StrictMode: ,	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-30 12:20:26.779  3894  3894 D StrictMode: 	,at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
,08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 12:20:26.779  3894  3894 D StrictMode: 	,at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013),
08-30 12:20:26.779  3894  3894 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 12:20:26.779  3894  3894 D StrictMode: ,	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:20:26.779  3894  3894 D StrictMode: 	,at android.os.Looper.loop(Looper.java:148)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method),
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 12:20:26.779  3894  3894 D StrictMode: StrictMode policy violation; ~duration=61 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 12:20:26.779  3894  3894 D StrictMode: 	,at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at java.io.File.doAccess(File.java:281),
08-30 12:20:26.779  3894  3894 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
,08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 12:20:26.779  3894  3894 D StrictMode: ,	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206),
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
,08-30 12:20:26.779  3894  3894 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 12:20:26.779  3894  3894 D StrictMode: 	,at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at android.os.Looper.loop(Looper.java:148),
08-30 12:20:26.779  3894  3894 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 12:20:26.779  3894  3894 D StrictMode: StrictMode policy violation; ~duration=60 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 12:20:26.779  3894  3894 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 12:20:26.779  3894  3894 D StrictMode: 	,at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 12:20:26.779  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 12:20:26.785  3876  3876 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 12:20:26.796  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 12:20:26.808  3876  3876 D DockEventReceiver: finishStartingService: stopping service
,08-30 12:20:26.851  2663  2681 D bt_stack_manager: event_shut_down_stack finished.
,08-30 12:20:26.852  2663  2680 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-30 12:20:26.855  2663  2680 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-30 12:20:26.856  2663  2663 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 12:20:26.857  2663  2663 D BtGatt.GattService: Received stop request...Stopping profile...
,08-30 12:20:26.857  2663  2663 D BtGatt.GattService: stop()
08-30 12:20:26.857  2663  2663 D BtGatt.AdvertiseManager: advertise clients cleared
,08-30 12:20:26.860  2663  2663 V BluetoothAdapterState: isTurningOff()=false
,08-30 12:20:26.861  2663  2663 V BluetoothAdapterState: isTurningOn()=false
,08-30 12:20:26.861  2663  2663 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 12:20:26.861  2663  2663 V BluetoothAdapterState: isBleTurningOff()=true
,08-30 12:20:26.862  2663  2680 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-30 12:20:26.862  2663  2680 D BluetoothAdapterProperties: Setting state to 10
08-30 12:20:26.862  2663  2680 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-30 12:20:26.863  2663  2680 I BluetoothAdapterState: Entering OffState
,08-30 12:20:26.865   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
08-30 12:20:26.875   873  1953 I ActivityManager: Killing 3567:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-30 12:20:26.951  1727  1727 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 12:20:26.955  1727  1727 D SystemUpdateService: onCreate
,08-30 12:20:26.959  1727  1727 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 12:20:26.961  2663  2663 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-30 12:20:26.961  2663  2663 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-30 12:20:26.961  2663  2681 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-30 12:20:26.961  2663  2663 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-30 12:20:26.969  2663  2681 D bt_stack_manager: event_clean_up_stack finished.
,08-30 12:20:26.973  2663  2663 I art     : System.exit called, status: 0
,08-30 12:20:26.973  2663  2663 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 12:20:26.976  1727  1727 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-30 12:20:26.981  1727  2423 I iu.UploadsManager: num queued entries: 0
,08-30 12:20:26.981  1727  2423 I iu.UploadsManager: num updated entries: 0
,08-30 12:20:26.985  1727  1727 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 12:20:26.993  1727  3928 I SystemUpdateService: active receiver: enabled
,08-30 12:20:27.012  1727  1727 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 12:20:27.015  1727  2423 I iu.SyncManager: NEXT; no task
,08-30 12:20:27.019  1727  3928 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 12:20:27.023  1727  3928 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-30 12:20:27.023  1727  3928 I SystemUpdateService: now status is 0 (complete)
08-30 12:20:27.023  1727  3928 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-30 12:20:27.024  1727  3928 I SystemUpdateService: file has been verified
,08-30 12:20:27.025  1727  3928 I SystemUpdateService: OTA package size = 12249756
,08-30 12:20:27.038  1727  3928 I SystemUpdateService: showing system update notification
,08-30 12:20:27.039  3894  3922 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-30 12:20:27.053   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@24d8af4:true
,08-30 12:20:27.057   873  1995 I ActivityManager: Start proc 3931:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-30 12:20:27.071   873  1976 I ActivityManager: Process com.android.bluetooth (pid 2663) has died
,08-30 12:20:27.081  1727  1727 D SystemUpdateService: onDestroy
,08-30 12:20:27.101  3931  3931 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-30 12:20:27.109  3931  3931 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:20:27.115  3931  3931 D SprintDMHelper: simOperator: 
08-30 12:20:27.115  3931  3931 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 12:20:27.136   873  1935 I ActivityManager: Start proc 3944:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-30 12:20:27.220  2464  3958 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-30 12:20:27.250   873  1966 I ActivityManager: Start proc 3959:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-30 12:20:27.252   873  1395 I ActivityManager: Killing 3449:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-30 12:20:27.348  3959  3959 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-30 12:20:27.409  3959  3959 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-30 12:20:27.409  3959  3959 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-30 12:20:27.409  3959  3959 I GAv4    :   adb logcat -s GAv4
,08-30 12:20:27.428  3959  3959 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-30 12:20:27.436  3959  3959 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-30 12:20:27.463  3959  3976 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-30 12:20:27.578  3959  3959 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-30 12:20:27.632  3959  3959 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-30 12:20:27.640  3959  3959 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 5698-5701)
,08-30 12:20:27.640  3959  3959 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 12:20:27.653  3959  3959 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8d75859}
,08-30 12:20:27.653  3959  3959 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 12:20:27.654  3959  3959 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 12:20:27.662  3959  3959 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-30 12:20:27.664  3959  3959 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-30 12:20:27.687  3959  3959 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-30 12:20:27.700  3959  3959 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-30 12:20:27.700  3959  3959 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-30 12:20:27.700  3959  3959 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 12:20:27.700  3959  3959 I Adreno  : Build Date                       : 10/20/15
08-30 12:20:27.700  3959  3959 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 12:20:27.700  3959  3959 I Adreno  : Local Branch                     : M14
08-30 12:20:27.700  3959  3959 I Adreno  : Remote Branch                    : 
08-30 12:20:27.700  3959  3959 I Adreno  : Remote Branch                    : 
08-30 12:20:27.700  3959  3959 I Adreno  : Reconstruct Branch               : 
,08-30 12:20:27.760  3959  3959 I NSApplication: Starting up...
,08-30 12:20:27.769  3959  4005 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-30 12:20:27.811   873  1935 I ActivityManager: Start proc 4010:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-30 12:20:27.812   873  1935 I ActivityManager: Killing 3492:android.process.acore/u0a5 (adj 15): empty #17
,08-30 12:20:27.912  4010  4010 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-30 12:20:28.138   873  1935 I ActivityManager: Killing 3651:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-30 12:20:28.222   873  1925 I ActivityManager: Start proc 4024:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-30 12:20:28.274  4024  4024 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-30 12:20:28.316  4024  4024 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-30 12:20:28.371   873  2035 I ActivityManager: Killing 3666:com.android.musicfx/u0a18 (adj 15): empty #17
,08-30 12:20:29.993  1509  2202 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-30 12:20:31.400   873  1966 D WifiService: setWifiEnabled: true pid=3792, uid=10000
08-30 12:20:31.400   873  1966 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 12:20:31.412   873  1306 D WifiConfigStore: Loading config and enabling all networks 
,08-30 12:20:31.420  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 12:20:31.420  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:20:31.420  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:20:31.420  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:20:31.420  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:20:31.420  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:20:31.420  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:20:31.420  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:20:31.420  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:20:31.420  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:20:31.420  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:20:31.429  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:20:31.429  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:20:31.429  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:20:31.429  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:20:31.429  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:20:31.429  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:20:31.429  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:20:31.429  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:20:31.429  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:20:31.429  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:20:31.430  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:20:31.431  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:20:31.431  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:20:31.431  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:20:31.431  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:20:31.431  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:20:31.431  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:20:31.431  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:20:31.431  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:20:31.431  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:20:31.432  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetoot,h is disabled - will return stored value
08-30 12:20:31.432  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:20:31.451   873  1306 D WifiConfigStore: loaded 0 passpoint configs
08-30 12:20:31.452   873  1306 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-30 12:20:31.453   873  1306 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-30 12:20:31.454   873  1306 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-30 12:20:31.455   873  1306 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-30 12:20:31.455   873  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-30 12:20:31.455   873  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-30 12:20:31.478   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-30 12:20:31.479   372   871 D CommandListener: Setting iface cfg
,08-30 12:20:31.479   873  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-30 12:20:31.480   873  1305 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '131 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 131 Failed to set address (No such device)'
08-30 12:20:31.480   873  1305 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 12:20:31.490   873  1306 E native  : do suspend true
,08-30 12:20:31.503   873  1306 D WifiConfigStore: Retrieve network priorities after PNO.
08-30 12:20:31.505   873  1305 D WifiNative-HAL: p2pGetDeviceAddress
,08-30 12:20:31.505   873  1305 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-30 12:20:32.175   873  2035 I ActivityManager: Killing 2222:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-30 12:20:32.903   873  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 12:20:32.979   873  1306 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=3.38 rxSuccessRate=3.94 delta 1000 -> 1000
,08-30 12:20:32.981   873  1306 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-30 12:20:32.981   873  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 12:20:32.995   873  1306 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-30 12:20:33.048   873  1306 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-30 12:20:33.051  1457  1457 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-30 12:20:33.507  1457  1457 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 12:20:33.597  1457  1457 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-30 12:20:33.600  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-30 12:20:33.607   873  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 12:20:33.624   873  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 12:20:33.624   873  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 12:20:33.625   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-30 12:20:33.644   873  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 12:20:33.664   372   871 D CommandListener: Setting iface cfg
,08-30 12:20:33.665   873  1306 D WifiStateMachine: Start Dhcp Watchdog 2
,08-30 12:20:33.679   873  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-30 12:20:33.707   873  4059 D DhcpClient: Receive thread started
,08-30 12:20:33.792   873  1306 E native  : do suspend false
,08-30 12:20:33.811   873  1842 D DhcpClient: Broadcasting DHCPDISCOVER
,08-30 12:20:33.834   873  4059 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172651, domain null
,08-30 12:20:33.836   873  1842 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172651 seconds
08-30 12:20:33.839   873  1842 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-30 12:20:33.866   873  4059 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-30 12:20:33.867   873  1842 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-30 12:20:33.872   372   871 D CommandListener: Setting iface cfg
,08-30 12:20:33.884   873  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-30 12:20:33.884   873  1842 D DhcpClient: Scheduling renewal in 86399s
,08-30 12:20:33.887   873  1306 E native  : do suspend true
,08-30 12:20:33.907   873  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-30 12:20:33.908   873  1306 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 12:20:33.908   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-30 12:20:33.914   873  1308 D ConnectivityService: Adding iface wlan0 to network 101
,08-30 12:20:33.916   873  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 12:20:33.979   873  1308 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-30 12:20:33.980   873  1308 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-30 12:20:33.983   873  1308 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-30 12:20:33.985   873  1308 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-30 12:20:33.988   873  1308 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-30 12:20:34.006   873  1308 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-30 12:20:34.017   873  1308 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-30 12:20:34.018   873  1308 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-30 12:20:34.018   873  1308 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-30 12:20:34.018   873  1308 D ConnectivityService:    accepting network in place of null
08-30 12:20:34.018   873  1306 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-30 12:20:34.019   873  1308 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 12:20:34.020   873  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 12:20:34.079   873  4058 D NetlinkSocketObserver: NeighborEvent{elapsedMs=172140, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 12:20:34.085   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 12:20:34.121   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 12:20:34.131   873  1308 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-30 12:20:34.131   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:20:34.140   873  1308 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-30 12:20:34.144   873   890 D Tethering: MasterInitialState.processMessage what=3
08-30 12:20:34.156  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:20:34.156  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:20:34.156  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:20:34.156  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:20:34.156  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:20:34.156  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:20:34.156  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:20:34.156  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:20:34.156  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:20:34.156  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:20:34.156  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:20:34.160  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:20:34.160  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:20:34.160  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:20:34.160  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:20:34.160  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:20:34.160  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:20:34.160  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:20:34.160  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:20:34.160  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:20:34.160  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:20:34.161  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:20:34.163  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 12:20:34.163  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:20:34.163  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:20:34.163  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:20:34.163  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:20:34.163  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:20:34.163  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:20:34.163  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:20:34.163  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:20:34.164  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:20:34.164  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:20:34.170   873  4057 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,08-30 12:20:34.179  1727  1727 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 12:20:34.186  1727  1727 D SystemUpdateService: onCreate
,08-30 12:20:34.192  1727  1727 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 12:20:34.196  3749  4070 I BooksSync: Starting books sync for 61035162, extras: ade
,08-30 12:20:34.201  1727  4071 I SystemUpdateService: active receiver: enabled
,08-30 12:20:34.209  1727  4071 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 12:20:34.228  1727  4071 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-30 12:20:34.229  1727  4071 I SystemUpdateService: now status is 0 (complete)
08-30 12:20:34.229  1727  4071 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 12:20:34.229  1727  4071 I SystemUpdateService: file has been verified
08-30 12:20:34.229  1727  4071 I SystemUpdateService: OTA package size = 12249756
,08-30 12:20:34.239  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:20:34.245  1727  1727 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-30 12:20:34.258  1727  4074 I MDM     : [177] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-30 12:20:34.258  1727  4074 W BaseAppContext: Using Auth Proxy for data requests.
08-30 12:20:34.259  1727  4074 V GoogleAuthProtoRequest: [177] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 12:20:34.283  1727  2423 I iu.UploadsManager: num queued entries: 0
,08-30 12:20:34.283  1727  2423 I iu.UploadsManager: num updated entries: 0
,08-30 12:20:34.287  1727  1727 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 12:20:34.288  1727  1727 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 12:20:34.290  3931  3931 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:20:34.292   873  4057 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 10:20:34 GMT], X-Android-Received-Millis=[1472552434290], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472552434229]}
08-30 12:20:34.295  3931  3931 D SprintDMHelper: simOperator: 
08-30 12:20:34.295  3931  3931 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-30 12:20:34.296   873  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-30 12:20:34.296   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-30 12:20:34.297   873  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-30 12:20:34.300   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-30 12:20:34.334  1727  4071 I SystemUpdateService: showing system update notification
,08-30 12:20:34.352  1727  2423 I iu.SyncManager: NEXT; no task
,08-30 12:20:34.357  3749  4081 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-30 12:20:34.376  1727  1727 D SystemUpdateService: onDestroy
,08-30 12:20:34.393  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:20:34.395  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:20:34.446  1509  4083 I VacuumService: Vacuum at: now=1472552434446 tag=VacuumService
,08-30 12:20:34.465  1509  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 12:20:34.465  1509  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 12:20:34.465  1509  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 12:20:34.465  1509  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 12:20:34.504  1509  3627 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 12:20:34.504  1509  3627 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 12:20:34.505  1509  3627 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 12:20:34.505  1509  3627 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 12:20:34.517  3749  4081 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-30 12:20:34.518  3749  4070 E BooksSync: Soft error
08-30 12:20:34.518  3749  4070 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 12:20:34.518  3749  4070 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-30 12:20:34.518  3749  4070 E BooksSync: Sync error
08-30 12:20:34.518  3749  4070 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 12:20:34.518  3749  4070 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-30 12:20:34.518  3749  4070 I BooksSync: Finished books sync
,08-30 12:20:34.524   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 160710, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 12:20:34.577  2464  4079 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-30 12:20:34.592  1509  2986 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-30 12:20:34.592  1509  2986 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-30 12:20:34.592  1509  2986 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 12:20:34.592  1509  2986 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 12:20:34.668  1509  4084 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-30 12:20:34.672  1509  4084 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-30 12:20:34.786  1727  4074 E MDM     : [177] SitrepService.a: Error sending sitrep.
,08-30 12:20:35.130   873  1308 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-30 12:20:36.409   873  1976 D WifiService: setWifiEnabled: false pid=3792, uid=10000
08-30 12:20:36.409   873  1976 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 12:20:36.449  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-30 12:20:36.456   873  1306 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-30 12:20:36.457   873  1306 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-30 12:20:36.457   873  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 12:20:36.458   873  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 12:20:36.496   873  1306 E native  : do suspend true
,08-30 12:20:36.511   873  1842 D DhcpClient: Clearing IP address
,08-30 12:20:36.511   372   871 D CommandListener: Clearing all IP addresses on wlan0
,08-30 12:20:36.516   372   871 D CommandListener: Setting iface cfg
,08-30 12:20:36.524   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-30 12:20:36.524   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-30 12:20:36.520  1509  4085 V NativeCrypto: Read error: ssl=0x9ae42c00: I/O error during system call, Connection timed out
,08-30 12:20:36.533   396   396 E Parcel  : Reading a NULL string not supported here.
,08-30 12:20:36.535   873  4059 D DhcpClient: Receive thread stopped
08-30 12:20:36.536   873  1306 D WifiStateMachine: Start Disconnecting Watchdog 2
08-30 12:20:36.537   873  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 12:20:36.537   873  1306 E native  : do suspend true
,08-30 12:20:36.539   873  1308 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-30 12:20:36.548  1509  4085 V NativeCrypto: SSL shutdown failed: ssl=0x9ae42c00: I/O error during system call, Broken pipe
,08-30 12:20:36.572   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 12:20:36.600   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 12:20:36.600   372   871 D CommandListener: Clearing all IP addresses on wlan0
,08-30 12:20:36.602   873  1308 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-30 12:20:36.602   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:20:36.611   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-30 12:20:36.629   873  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-30 12:20:36.630  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:20:36.630  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:20:36.630  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:20:36.630  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:20:36.630  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:20:36.630  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:20:36.630  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:20:36.630  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:20:36.630  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:20:36.631  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:20:36.631  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 12:20:36.636  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:20:36.636  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:20:36.636  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:20:36.636  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:20:36.636  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:20:36.636  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:20:36.636  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:20:36.636  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:20:36.636  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:20:36.636  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 12:20:36.636  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:20:36.637  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:20:36.637  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:20:36.637  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:20:36.637  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:20:36.637  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:20:36.637  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:20:36.637  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:20:36.637  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:20:36.637  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:20:36.637  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 12:20:36.637  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 12:20:36.647  1727  1727 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 12:20:36.648   873  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 12:20:36.651  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 12:20:36.651  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:20:36.651  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:20:36.651  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:20:36.651  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:20:36.651  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:20:36.651  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:20:36.651  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:20:36.651  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 12:20:36.651  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:20:36.651  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:20:36.651  2069  2311 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:20:36.652  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:20:36.652  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:20:36.652  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:20:36.652  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:20:36.652  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:20:36.652  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:20:36.652  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:20:36.652  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:20:36.652  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:20:36.652  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:20:36.652  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:20:36.653  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 12:20:36.654  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:20:36.654  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:20:36.654  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:20:36.654  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:20:36.654  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:20:36.654  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:20:36.654  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:20:36.654  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:20:36.654  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:20:36.654  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:20:36.654  1727  1727 D SystemUpdateService: onCreate
,08-30 12:20:36.657   873  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-30 12:20:36.659  1727  1727 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 12:20:36.671  1727  1727 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-30 12:20:36.676  1727  2423 I iu.UploadsManager: num queued entries: 0
,08-30 12:20:36.677  1727  1727 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 12:20:36.678  1727  1727 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 12:20:36.681  3931  3931 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:20:36.688  1727  2423 I iu.UploadsManager: num updated entries: 0
08-30 12:20:36.688  3931  3931 D SprintDMHelper: simOperator: 
08-30 12:20:36.688  3931  3931 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 12:20:36.691   372   871 E Netd    : netlink response contains error (No such file or directory)
,08-30 12:20:36.693   873  1308 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-30 12:20:36.703  1727  4104 I SystemUpdateService: active receiver: enabled
,08-30 12:20:36.716  1727  2423 I iu.SyncManager: NEXT; no task
,08-30 12:20:36.716  2464  4108 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-30 12:20:36.728  1727  4104 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 12:20:36.735  1727  4104 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-30 12:20:36.735  1727  4104 I SystemUpdateService: now status is 0 (complete)
,08-30 12:20:36.735  1727  4104 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 12:20:36.735  1727  4104 I SystemUpdateService: file has been verified
08-30 12:20:36.735  1727  4104 I SystemUpdateService: OTA package size = 12249756
,08-30 12:20:36.739  1727  4104 I SystemUpdateService: showing system update notification
,08-30 12:20:36.749  1727  1727 D SystemUpdateService: onDestroy
,08-30 12:20:39.790  1509  4084 D Uploader: Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,08-30 12:20:39.966  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:20:39.977  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:20:39.980  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:20:40.021  1509  2116 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 12:20:40.022  1509  2116 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-30 12:20:40.022  1509  2116 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 12:20:40.022  1509  2116 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 12:20:40.047  3508  3508 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-30 12:20:40.047  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-30 12:20:40.047  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-30 12:20:41.463   873   890 I ActivityManager: Start proc 4114:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-30 12:20:41.573  4114  4114 D AdapterServiceConfig: Adding HeadsetService
,08-30 12:20:41.574  4114  4114 D AdapterServiceConfig: Adding A2dpService,
,08-30 12:20:41.574  4114  4114 D AdapterServiceConfig: Adding HidService
,08-30 12:20:41.574  4114  4114 D AdapterServiceConfig: Adding HealthService
,08-30 12:20:41.574  4114  4114 D AdapterServiceConfig: Adding PanService
08-30 12:20:41.574  4114  4114 D AdapterServiceConfig: Adding GattService
,08-30 12:20:41.574  4114  4114 D AdapterServiceConfig: Adding BluetoothMapService
,08-30 12:20:41.589  4114  4114 D BluetoothAdapterState: make() - Creating AdapterState
,08-30 12:20:41.589   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cf8200d:true
,08-30 12:20:41.594  4114  4114 I bt_bluedroid: init
,08-30 12:20:41.594  4114  4126 I BluetoothAdapterState: Entering OffState
,08-30 12:20:41.601  4114  4127 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-30 12:20:41.601  4114  4127 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-30 12:20:41.601  4114  4127 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found,
,08-30 12:20:41.602  4114  4127 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-30 12:20:41.603  4114  4114 I bt_bluedroid: get_profile_interface socket
,08-30 12:20:41.607  4114  4130 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 12:20:41.608  4114  4114 I bt_bluedroid: get_profile_interface sdp
,08-30 12:20:41.609  4114  4130 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 12:20:41.615  4114  4125 I bt_bluedroid: config_hci_snoop_log
,08-30 12:20:41.618   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-30 12:20:41.626  4114  4126 D BluetoothAdapterState: Current state: OFF, message: 0
,08-30 12:20:41.626  4114  4126 D BluetoothAdapterProperties: Setting state to 14
,08-30 12:20:41.627  4114  4126 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-30 12:20:41.632  4114  4126 D BluetoothBondStateMachine: make
,08-30 12:20:41.635  4114  4131 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 12:20:41.644  4114  4126 I BluetoothAdapterState: Entering PendingCommandState
,08-30 12:20:41.646  4114  4114 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-30 12:20:41.655  4114  4114 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7523b57
,08-30 12:20:41.657  4114  4114 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 12:20:41.659  4114  4114 D BtGatt.GattService: Received start request. Starting profile...
,08-30 12:20:41.659  4114  4114 D BtGatt.GattService: start()
08-30 12:20:41.659  4114  4114 I bt_bluedroid: get_profile_interface gatt
,08-30 12:20:41.662  4114  4114 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7523b57
,08-30 12:20:41.662  4114  4114 D BtGatt.AdvertiseManager: advertise manager created
,08-30 12:20:41.676  4114  4114 V BluetoothAdapterState: isTurningOff()=false
08-30 12:20:41.677  4114  4114 V BluetoothAdapterState: isTurningOn()=false
08-30 12:20:41.677  4114  4114 V BluetoothAdapterState: isBleTurningOn()=true
,08-30 12:20:41.677  4114  4114 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:20:41.678  4114  4126 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-30 12:20:41.678  4114  4126 I bt_bluedroid: enable
08-30 12:20:41.679  4114  4127 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-30 12:20:41.680  4114  4127 I bt_hci  : start_up
,08-30 12:20:41.692  4114  4127 I bt_vendor: alloc value 0xb39d7189
,08-30 12:20:41.692  4114  4127 I bt_vendor: init,
08-30 12:20:41.692  4114  4127 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf,
08-30 12:20:41.692  4114  4127 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-30 12:20:41.799  4114  4127 D bt_hci  : start_up starting async portion
,08-30 12:20:41.800  4114  4134 I bt_hci  : event_finish_startup
,08-30 12:20:41.802  4114  4134 I bt_hci_h4: hal_open
08-30 12:20:41.802  4114  4134 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-30 12:20:41.816  4114  4134 I bt_userial_vendor: device fd = 51 open
,08-30 12:20:41.842  4114  4134 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 12:20:41.874  4114  4134 D bt_hwcfg: Chipset BCM4354A2
,08-30 12:20:41.874  4114  4134 D bt_hwcfg: Target name = [BCM4354A2]
08-30 12:20:41.875  4114  4134 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-30 12:20:42.023   873  1308 D ConnectivityService: handlePromptUnvalidated 101
,08-30 12:20:42.532  4114  4134 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-30 12:20:42.534  4114  4134 D bt_hwcfg: Settlement delay -- 100 ms
,08-30 12:20:42.534  4114  4134 I bt_hwcfg: Setting fw settlement delay to 100 
,08-30 12:20:42.650  4114  4134 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 12:20:42.652  4114  4134 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-30 12:20:42.681  4114  4134 I bt_hwcfg: vendor lib fwcfg completed
,08-30 12:20:42.681  4114  4134 I bt_vendor: firmware callback
08-30 12:20:42.682  4114  4134 I bt_hci  : firmware_config_callback
,08-30 12:20:42.693  4114  4136 I bt_btu  : btu_task pending for preload complete event
,08-30 12:20:42.693  4114  4136 I bt_btu_task: Bluetooth chip preload is complete
,08-30 12:20:42.693  4114  4136 I bt_btu  : btu_task received preload complete event
,08-30 12:20:42.703  4114  4136 I         : BTE_InitTraceLevels -- TRC_HCI
08-30 12:20:42.703  4114  4136 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-30 12:20:42.704  4114  4136 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 12:20:42.704  4114  4136 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 12:20:42.704  4114  4136 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 12:20:42.704  4114  4136 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 12:20:42.705  4114  4136 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 12:20:42.705  4114  4136 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 12:20:42.705  4114  4136 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 12:20:42.706  4114  4136 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 12:20:42.706  4114  4136 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 12:20:42.706  4114  4136 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 12:20:42.706  4114  4136 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 12:20:42.707  4114  4136 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 12:20:42.707  4114  4136 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 12:20:42.845  4114  4136 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3954d9d
,08-30 12:20:42.846  4114  4136 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3954d9d 
,08-30 12:20:42.872  4114  4130 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false,
,08-30 12:20:42.873  4114  4130 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000,
,08-30 12:20:42.874  4114  4130 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 12:20:42.876  4114  4130 D BluetoothAdapterProperties: Name is: Nexus 6
08-30 12:20:42.877  4114  4130 D BluetoothAdapterProperties: Scan Mode:20
08-30 12:20:42.878  4114  4130 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 12:20:42.878  4114  4130 D bt_hci  : do_postload posting postload work item
,08-30 12:20:42.878  4114  4134 I bt_hci  : event_postload
08-30 12:20:42.878  4114  4134 I bt_vendor: sco_config_cb
08-30 12:20:42.878  4114  4134 I bt_hci  : sco_config_callback postload finished.
08-30 12:20:42.880  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:20:42.880  4114  4130 D bt_bte_conf: Device ID record 1 : primary
08-30 12:20:42.880  4114  4130 D bt_bte_conf:   vendorId            = 000f
08-30 12:20:42.881  4114  4130 D bt_bte_conf:   vendorIdSource      = 0001
08-30 12:20:42.881  4114  4130 D bt_bte_conf:   product             = 1200
08-30 12:20:42.881  4114  4130 D bt_bte_conf:   version             = 1436
,08-30 12:20:42.883  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:20:42.883  4114  4130 D bt_bte_conf:   clientExecutableURL = 
08-30 12:20:42.884  4114  4130 D bt_bte_conf:   serviceDescription  = 
,08-30 12:20:42.886  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:20:42.886  4114  4130 D bt_bte_conf:   documentationURL    = 
,08-30 12:20:42.888  4114  4134 I bt_vendor: low_power_mode_cb
,08-30 12:20:42.887  4114  4130 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-30 12:20:42.889  4114  4127 D bt_stack_manager: event_start_up_stack finished
,08-30 12:20:42.890  4114  4126 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-30 12:20:42.890  4114  4126 D BluetoothAdapterProperties: Setting state to 15
08-30 12:20:42.890  4114  4126 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-30 12:20:42.891  4114  4126 I BluetoothAdapterState: Entering BleOnState
,08-30 12:20:42.895  4114  4126 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-30 12:20:42.895  4114  4126 D BluetoothAdapterProperties: Setting state to 11
08-30 12:20:42.895  4114  4126 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-30 12:20:42.900  4114  4114 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7523b57
,08-30 12:20:42.900  4114  4114 D HeadsetService: Received start request. Starting profile...
08-30 12:20:42.904  4114  4114 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-30 12:20:42.904  4114  4114 D HeadsetStateMachine: make
08-30 12:20:42.909  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:20:42.913  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:20:42.915  4114  4114 D HeadsetStateMachine: max_hf_connections = 1
08-30 12:20:42.915  4114  4114 I bt_bluedroid: get_profile_interface handsfree
,08-30 12:20:42.915  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:20:42.915  4114  4130 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-30 12:20:42.915  4114  4130 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-30 12:20:42.917  4114  4126 I BluetoothAdapterState: Entering PendingCommandState
08-30 12:20:42.920  4114  4114 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7523b57
08-30 12:20:42.921  4114  4114 D A2dpService: Received start request. Starting profile...
08-30 12:20:42.922  4114  4114 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 12:20:42.922  4114  4114 I bt_bluedroid: get_profile_interface avrcp
,08-30 12:20:42.930  4114  4114 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-30 12:20:42.931  4114  4114 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-30 12:20:42.931  4114  4114 D A2dpStateMachine: make
,08-30 12:20:42.933  4114  4114 I bt_bluedroid: get_profile_interface a2dp
,08-30 12:20:42.934  4114  4130 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-30 12:20:42.938  4114  4146 D A2dpStateMachine: Enter Disconnected: -2
,08-30 12:20:42.939  4114  4114 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 12:20:42.942  4114  4114 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7523b57
,08-30 12:20:42.944  4114  4114 D HidService: Received start request. Starting profile...
,08-30 12:20:42.944  3876  3876 D BluetoothInputDevice: Proxy object connected
08-30 12:20:42.946  4114  4114 I bt_bluedroid: get_profile_interface hidhost
,08-30 12:20:42.949  4114  4130 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39363e5
08-30 12:20:42.949  4114  4130 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-30 12:20:42.949  4114  4114 D HidService: setHidService(): set to: null
08-30 12:20:42.949  3876  3876 D HidProfile: Bluetooth service connected
,08-30 12:20:42.950  4114  4114 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-30 12:20:42.952  4114  4114 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7523b57
,08-30 12:20:42.954  4114  4114 D HealthService: Received start request. Starting profile...
,08-30 12:20:42.956  4114  4114 I bt_bluedroid: get_profile_interface health
,08-30 12:20:42.959  4114  4114 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 12:20:42.961  4114  4114 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7523b57
,08-30 12:20:42.964  3876  3876 D BluetoothPan: BluetoothPAN Proxy object connected
,08-30 12:20:42.964  3876  3876 D PanProfile: Bluetooth service connected
08-30 12:20:42.965  4114  4114 D PanService: Received start request. Starting profile...
,08-30 12:20:42.965  4114  4114 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 12:20:42.966  4114  4114 I bt_bluedroid: get_profile_interface pan
08-30 12:20:42.966  4114  4130 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-30 12:20:42.968  4114  4114 V BluetoothAdapterState: isTurningOff()=false
08-30 12:20:42.968  4114  4114 V BluetoothAdapterState: isTurningOn()=true
,08-30 12:20:42.969  4114  4114 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:20:42.969  4114  4114 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 12:20:42.973  4114  4114 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7523b57
,08-30 12:20:42.974  4114  4114 D BluetoothMapService: Received start request. Starting profile...
,08-30 12:20:42.974  4114  4114 D BluetoothMapService: start()
,08-30 12:20:42.977  4114  4114 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-30 12:20:42.978  4114  4114 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-30 12:20:42.978  4114  4114 D BluetoothMapAppObserver: createReceiver()
08-30 12:20:42.980  4114  4114 D BluetoothMapAppObserver: initObservers()
08-30 12:20:42.980  4114  4114 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-30 12:20:42.985  3876  3876 D BluetoothMap: Proxy object connected
08-30 12:20:42.986  3876  3876 D MapProfile: Bluetooth service connected
,08-30 12:20:42.986  3876  3876 D BluetoothMap: getConnectedDevices()
,08-30 12:20:42.989  4114  4142 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-30 12:20:42.989  3876  3876 D BluetoothMap: Bluetooth is Not enabled
,08-30 12:20:42.992  4114  4114 V BluetoothAdapterState: isTurningOff()=false
08-30 12:20:42.992  4114  4114 V BluetoothAdapterState: isTurningOn()=true
,08-30 12:20:42.992  4114  4114 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:20:42.993  4114  4114 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:20:42.993  4114  4114 V BluetoothAdapterState: isTurningOff()=false
,08-30 12:20:42.993  4114  4114 V BluetoothAdapterState: isTurningOn()=true
08-30 12:20:42.993  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 12:20:42.994  4114  4114 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 12:20:42.994  4114  4114 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:20:42.994  4114  4114 V BluetoothAdapterState: isTurningOff()=false
,08-30 12:20:42.995  4114  4114 V BluetoothAdapterState: isTurningOn()=true
08-30 12:20:42.995  4114  4114 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:20:42.995  4114  4114 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 12:20:42.996  4114  4114 V BluetoothAdapterState: isTurningOff()=false
08-30 12:20:42.996  4114  4114 V BluetoothAdapterState: isTurningOn()=true
,08-30 12:20:42.997  4114  4114 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:20:42.997  4114  4114 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:20:42.997  4114  4114 V BluetoothAdapterState: isTurningOff()=false
,08-30 12:20:42.997  4114  4114 V BluetoothAdapterState: isTurningOn()=true
08-30 12:20:42.998  4114  4114 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:20:42.998  4114  4114 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:20:42.999  4114  4126 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-30 12:20:42.999  4114  4126 D BluetoothAdapterProperties: ScanMode =  20
,08-30 12:20:42.999  4114  4126 D BluetoothAdapterProperties: State =  11
,08-30 12:20:43.000  4114  4126 D BluetoothAdapterProperties: Setting state to 12
08-30 12:20:43.000  4114  4126 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-30 12:20:43.001  4114  4126 I BluetoothAdapterState: Entering OnState
,08-30 12:20:43.002   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true,
08-30 12:20:43.002   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 12:20:43.003  4114  4130 D BluetoothAdapterProperties: Scan Mode:21
08-30 12:20:43.003  1362  1375 D BluetoothPan: onBluetoothStateChange on: true,
08-30 12:20:43.003  4114  4130 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 12:20:43.005  1362  1362 D BluetoothPan: BluetoothPAN Proxy object connected
,08-30 12:20:43.005  1362  1362 D PanProfile: Bluetooth service connected
,08-30 12:20:43.006   873   873 D BluetoothA2dp: Proxy object connected
08-30 12:20:43.009  1940  2247 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 12:20:43.011  1362  1376 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 12:20:43.012  4114  4114 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-30 12:20:43.013  4114  4114 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-30 12:20:43.014  4114  4114 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 12:20:43.015  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:20:43.015  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:20:43.015  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:20:43.015  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:20:43.015  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:20:43.015  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:20:43.015  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:20:43.015  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:20:43.017  4114  4114 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 12:20:43.017  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:20:43.019  1362  2057 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 12:20:43.020  3876  3887 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 12:20:43.021   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 12:20:43.021  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:20:43.021  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:20:43.021  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:20:43.021  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:20:43.021  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:20:43.021  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:20:43.021  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:20:43.021  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:20:43.021  1362  1375 D BluetoothMap: onBluetoothStateChange: up=true
08-30 12:20:43.023  1362  1362 D BluetoothMap: Proxy object connected
08-30 12:20:43.023  1362  1362 D MapProfile: Bluetooth service connected
,08-30 12:20:43.023  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:20:43.023  1362  1362 D BluetoothMap: getConnectedDevices()
08-30 12:20:43.025  4114  4114 D ObexServerSockets: Succeed to create listening sockets 
,08-30 12:20:43.025  4114  4114 D ObexServerSockets0: startAccept()
08-30 12:20:43.025  4114  4114 D ObexServerSockets0: prepareForNewConnect()
08-30 12:20:43.026  3876  3886 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 12:20:43.026   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 12:20:43.026  3876  3887 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 12:20:43.027  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:20:43.027  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:20:43.027  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:20:43.027  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:20:43.027  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:20:43.027  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:20:43.027  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:20:43.027  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 12:20:43.027  4114  4114 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-30 12:20:43.027  4114  4114 D BluetoothSdpJni: SDP Create record success - handle: 0
08-30 12:20:43.028  1362  2057 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 12:20:43.028  4114  4151 D ObexServerSockets0: Accepting socket connection...
08-30 12:20:43.029  4114  4152 D ObexServerSockets0: Accepting socket connection...
08-30 12:20:43.029  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 12:20:43.031  1362  1362 D BluetoothA2dp: Proxy object connected
08-30 12:20:43.031  3876  3886 D BluetoothPan: onBluetoothStateChange on: true
08-30 12:20:43.032  1362  1375 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-30 12:20:43.034  1362  1362 D BluetoothInputDevice: Proxy object connected
,08-30 12:20:43.034  1362  1362 D HidProfile: Bluetooth service connected
,08-30 12:20:43.037   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-30 12:20:43.037  4114  4114 D BluetoothMapService: onReceive
,08-30 12:20:43.038  4114  4114 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 12:20:43.038  4114  4114 D BluetoothMapService: STATE_ON
,08-30 12:20:43.039  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:20:43.040  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:20:43.041  3876  3876 D LocalBluetoothProfileManager: Adding local A2DP profile
08-30 12:20:43.041  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:20:43.045  3876  3876 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-30 12:20:43.053  3876  3876 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 12:20:43.057  3876  3876 D BluetoothA2dp: Proxy object connected
,08-30 12:20:43.059  4114  4114 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-30 12:20:43.059  4114  4114 D ObexServerSockets0: prepareForNewConnect()
,08-30 12:20:43.062  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 12:20:43.068  3876  3876 D DockEventReceiver: finishStartingService: stopping service
,08-30 12:20:43.072  1362  1362 D BluetoothPbap: Proxy object connected
,08-30 12:20:43.072  3876  3876 D BluetoothPbap: Proxy object connected
08-30 12:20:43.072  1362  1362 D PbapServerProfile: Bluetooth service connected
08-30 12:20:43.073  3876  3876 D PbapServerProfile: Bluetooth service connected
,08-30 12:20:43.082  4114  4157 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 12:20:43.099  4114  4161 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 12:20:43.100  4114  4161 I BtOppRfcommListener: Accept thread started.
,08-30 12:20:43.104   873   873 D BluetoothHeadset: Proxy object connected
,08-30 12:20:43.104   873   873 D BluetoothHeadset: Proxy object connected
08-30 12:20:43.104  1362  1375 D BluetoothHeadset: Proxy object connected
08-30 12:20:43.104  1362  1362 D HeadsetProfile: Bluetooth service connected
08-30 12:20:43.105  1940  1954 D BluetoothHeadset: Proxy object connected
,08-30 12:20:43.105   873   873 D BluetoothHeadset: Proxy object connected
,08-30 12:20:43.110  1940  2133 D BluetoothHeadset: Proxy object connected
,08-30 12:20:43.120  1362  1376 D BluetoothHeadset: Proxy object connected
,08-30 12:20:43.120  1362  1362 D HeadsetProfile: Bluetooth service connected
08-30 12:20:43.120   873   890 D BluetoothHeadset: Proxy object connected
,08-30 12:20:43.126   873   890 D BluetoothHeadset: Proxy object connected
,08-30 12:20:43.149  3876  3887 D BluetoothHeadset: Proxy object connected
,08-30 12:20:43.153  3876  3876 D HeadsetProfile: Bluetooth service connected
,08-30 12:20:46.429  4114  4126 D BluetoothAdapterState: Current state: ON, message: 23
08-30 12:20:46.430  4114  4126 D BluetoothAdapterProperties: Setting state to 13
,08-30 12:20:46.430  4114  4126 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 12:20:46.432  4114  4126 D BluetoothAdapterProperties: onBluetoothDisable()
,08-30 12:20:46.436  4114  4126 I BluetoothAdapterState: Entering PendingCommandState
,08-30 12:20:46.450  4114  4114 D BluetoothMapService: onReceive
,08-30 12:20:46.450  4114  4114 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:20:46.450  4114  4114 D BluetoothMapService: STATE_TURNING_OFF
,08-30 12:20:46.451  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:20:46.451  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:20:46.451  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,08-30 12:20:46.451  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:20:46.451  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:20:46.451  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:20:46.451  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:20:46.451  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:20:46.451  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 12:20:46.451  4114  4114 D BluetoothMapService: MAP Service closeService in
,08-30 12:20:46.451  4114  4114 D BluetoothMapMasInstance0: MAP Service shutdown
08-30 12:20:46.452  4114  4114 D ObexServerSockets0: shutdown(block = true)
08-30 12:20:46.452  4114  4151 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-30 12:20:46.454  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:20:46.454  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:20:46.455  4114  4114 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 12:20:46.456  4114  4152 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-30 12:20:46.456  4114  4138 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-30 12:20:46.456  4114  4114 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 12:20:46.457  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:20:46.457  4114  4114 I BtOppRfcommListener: stopping Accept Thread
,08-30 12:20:46.457  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:20:46.457  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:20:46.457  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:20:46.457  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:20:46.457  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:20:46.457  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:20:46.457  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:20:46.457  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:20:46.457  4114  4161 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 12:20:46.458  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:20:46.458  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:20:46.459  4114  4161 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 12:20:46.460  4114  4130 D BluetoothAdapterProperties: Scan Mode:20
,08-30 12:20:46.462  3876  3876 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 12:20:46.462  4114  4126 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-30 12:20:46.462  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:20:46.463  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:20:46.463  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:20:46.463  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:20:46.463  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:20:46.463  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:20:46.463  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:20:46.463  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:20:46.463  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:20:46.466  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:20:46.466  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 12:20:46.467  4114  4114 D HeadsetService: Received stop request...Stopping profile...
08-30 12:20:46.470   873   873 D BluetoothHeadset: Proxy object disconnected
08-30 12:20:46.470   873   873 D BluetoothHeadset: Proxy object disconnected
08-30 12:20:46.471  1362  1376 D BluetoothHeadset: Proxy object disconnected
08-30 12:20:46.471  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:20:46.471  1362  1362 D HeadsetProfile: Bluetooth service disconnected
08-30 12:20:46.471  1940  1952 D BluetoothHeadset: Proxy object disconnected
,08-30 12:20:46.472   873   873 D BluetoothHeadset: Proxy object disconnected
08-30 12:20:46.472  3876  3887 D BluetoothHeadset: Proxy object disconnected
,08-30 12:20:46.473  4114  4114 D A2dpService: Received stop request...Stopping profile...
,08-30 12:20:46.473  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:20:46.474  4114  4146 D A2dpStateMachine: Exit Disconnected: -1
08-30 12:20:46.476   873   873 D BluetoothA2dp: Proxy object disconnected
08-30 12:20:46.476  1362  1362 D BluetoothA2dp: Proxy object disconnected
08-30 12:20:46.476  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:20:46.478  4114  4114 V BluetoothAdapterState: isTurningOff()=true
08-30 12:20:46.479  4114  4114 V BluetoothAdapterState: isTurningOn()=false
,08-30 12:20:46.480  4114  4114 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:20:46.480  4114  4114 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:20:46.480  4114  4114 D HidService: Received stop request...Stopping profile...
08-30 12:20:46.480  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 12:20:46.480  4114  4114 D HidService: Stopping Bluetooth HidService
08-30 12:20:46.479  3876  3876 D DockEventReceiver: finishStartingService: stopping service
08-30 12:20:46.481  3876  3876 D HeadsetProfile: Bluetooth service disconnected
,08-30 12:20:46.482  3876  3876 D BluetoothA2dp: Proxy object disconnected
08-30 12:20:46.483  1362  1362 D BluetoothInputDevice: Proxy object disconnected
08-30 12:20:46.483  1362  1362 D HidProfile: Bluetooth service disconnected
,08-30 12:20:46.484  3876  3876 D BluetoothInputDevice: Proxy object disconnected
08-30 12:20:46.484  3876  3876 D HidProfile: Bluetooth service disconnected
08-30 12:20:46.485  4114  4114 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...,
08-30 12:20:46.486  4114  4114 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 12:20:46.486  4114  4130 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-30 12:20:46.486  4114  4136 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 12:20:46.486  4114  4136 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 12:20:46.486  4114  4136 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 12:20:46.486  4114  4130 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-30 12:20:46.486  4114  4114 D HealthService: Received stop request...Stopping profile...
,08-30 12:20:46.489  4114  4114 D PanService: Received stop request...Stopping profile...
,08-30 12:20:46.490  1362  1362 D BluetoothPan: BluetoothPAN Proxy object disconnected,
08-30 12:20:46.490  1362  1362 D PanProfile: Bluetooth service disconnected
,08-30 12:20:46.490  3876  3876 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-30 12:20:46.491  4114  4114 D BluetoothMapService: Received stop request...Stopping profile...
08-30 12:20:46.491  3876  3876 D PanProfile: Bluetooth service disconnected
,08-30 12:20:46.491  4114  4114 D BluetoothMapService: stop()
,08-30 12:20:46.491  4114  4114 D BluetoothMapAppObserver: deinitObservers()
08-30 12:20:46.492  4114  4114 D BluetoothMapAppObserver: removeReceiver()
08-30 12:20:46.493  3876  3876 D BluetoothMap: Proxy object disconnected
08-30 12:20:46.493  4114  4114 V BluetoothAdapterState: isTurningOff()=true
08-30 12:20:46.493  3876  3876 D MapProfile: Bluetooth service disconnected
08-30 12:20:46.493  4114  4114 V BluetoothAdapterState: isTurningOn()=false
08-30 12:20:46.493  4114  4114 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:20:46.493  1362  1362 D BluetoothMap: Proxy object disconnected
08-30 12:20:46.493  1362  1362 D MapProfile: Bluetooth service disconnected
08-30 12:20:46.493  4114  4114 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:20:46.495  4114  4136 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 12:20:46.495  4114  4130 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-30 12:20:46.495  4114  4136 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 12:20:46.495  4114  4136 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 12:20:46.496  4114  4136 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 12:20:46.496  4114  4136 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 12:20:46.496  4114  4136 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-30 12:20:46.499  1362  1362 D BluetoothPbap: Proxy object disconnected
08-30 12:20:46.499  1362  1362 D PbapServerProfile: Bluetooth service disconnected
08-30 12:20:46.500  4114  4114 V BluetoothAdapterState: isTurningOff()=true
,08-30 12:20:46.500  4114  4114 V BluetoothAdapterState: isTurningOn()=false
08-30 12:20:46.500  4114  4114 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:20:46.500  3876  3876 D BluetoothPbap: Proxy object disconnected
08-30 12:20:46.500  3876  3876 D PbapServerProfile: Bluetooth service disconnected
08-30 12:20:46.500  4114  4114 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 12:20:46.503  4114  4114 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-30 12:20:46.503  4114  4114 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 12:20:46.503  4114  4130 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-30 12:20:46.503  4114  4114 V BluetoothAdapterState: isTurningOff()=true
08-30 12:20:46.503  4114  4114 V BluetoothAdapterState: isTurningOn()=false
08-30 12:20:46.503  4114  4114 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 12:20:46.503  4114  4114 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:20:46.503  4114  4114 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 12:20:46.504  4114  4130 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-30 12:20:46.504  4114  4114 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 12:20:46.504  4114  4114 V BluetoothAdapterState: isTurningOff()=true
,08-30 12:20:46.504  4114  4114 V BluetoothAdapterState: isTurningOn()=false
08-30 12:20:46.504  4114  4114 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:20:46.505  4114  4114 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:20:46.505  4114  4114 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-30 12:20:46.506  4114  4114 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 12:20:46.507  4114  4114 D BluetoothMapService: MAP Service closeService in
08-30 12:20:46.507  4114  4114 V BluetoothAdapterState: isTurningOff()=true
08-30 12:20:46.507  4114  4114 V BluetoothAdapterState: isTurningOn()=false
,08-30 12:20:46.508  4114  4114 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 12:20:46.508  4114  4114 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:20:46.508  4114  4126 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-30 12:20:46.508  4114  4126 D BluetoothAdapterProperties: Setting state to 15
,08-30 12:20:46.508  4114  4114 D BluetoothMapService: cleanup()
08-30 12:20:46.508  4114  4126 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-30 12:20:46.508  4114  4114 D BluetoothMapService: MAP Service closeService in
08-30 12:20:46.509  4114  4126 I BluetoothAdapterState: Entering BleOnState
08-30 12:20:46.509   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 12:20:46.509   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:20:46.510  1362  1375 D BluetoothPan: onBluetoothStateChange on: false
,08-30 12:20:46.510  1940  2247 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:20:46.510  1362  1376 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 12:20:46.511  1362  2057 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 12:20:46.512  3876  3886 D BluetoothMap: onBluetoothStateChange: up=false
,08-30 12:20:46.513  3876  3887 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 12:20:46.514   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 12:20:46.514  1362  1375 D BluetoothMap: onBluetoothStateChange: up=false
08-30 12:20:46.514  3876  3886 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-30 12:20:46.515   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 12:20:46.515  3876  3887 D BluetoothPbap: onBluetoothStateChange: up=false
,08-30 12:20:46.516  1362  1376 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 12:20:46.517  3876  3886 D BluetoothPan: onBluetoothStateChange on: false
,08-30 12:20:46.517  1362  2057 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 12:20:46.518  3876  3887 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:20:46.518  4114  4126 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-30 12:20:46.518  4114  4126 D BluetoothAdapterProperties: Setting state to 16
,08-30 12:20:46.519  4114  4126 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-30 12:20:46.519  4114  4126 D BluetoothAdapterProperties: onBleDisable
08-30 12:20:46.519  4114  4126 I BluetoothAdapterState: Entering PendingCommandState
08-30 12:20:46.519  4114  4127 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-30 12:20:46.520  4114  4136 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-30 12:20:46.520  4114  4136 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 12:20:46.523  4114  4130 D BluetoothAdapterProperties: Scan Mode:20
,08-30 12:20:46.523  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:20:46.525  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:20:46.527  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:20:46.528  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:20:46.529  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:20:46.530  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:20:46.540  3876  3876 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 12:20:46.544  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 12:20:46.551  3876  3876 D DockEventReceiver: finishStartingService: stopping service
,08-30 12:20:46.730  4114  4130 I bt_hci  : shut_down
,08-30 12:20:46.746  4114  4134 D bt_hwcfg: hw_epilog_process
,08-30 12:20:46.746  4114  4134 I bt_vendor: low_power_mode_cb
,08-30 12:20:46.762  4114  4134 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-30 12:20:46.762  4114  4134 I bt_vendor: epilog_cb
08-30 12:20:46.762  4114  4134 I bt_hci  : epilog_finished_callback
,08-30 12:20:46.769  4114  4130 I bt_hci_h4: hal_close
08-30 12:20:46.770  4114  4130 I bt_userial_vendor: device fd = 51 close
,08-30 12:20:46.892  4114  4127 D bt_stack_manager: event_shut_down_stack finished.,
,08-30 12:20:46.892  4114  4126 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-30 12:20:46.898  4114  4126 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-30 12:20:46.899  4114  4114 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 12:20:46.901  4114  4114 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 12:20:46.901  4114  4114 D BtGatt.GattService: stop()
,08-30 12:20:46.902  4114  4114 D BtGatt.AdvertiseManager: advertise clients cleared
,08-30 12:20:46.907  4114  4114 V BluetoothAdapterState: isTurningOff()=false
,08-30 12:20:46.907  4114  4114 V BluetoothAdapterState: isTurningOn()=false
08-30 12:20:46.908  4114  4114 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 12:20:46.908  4114  4114 V BluetoothAdapterState: isBleTurningOff()=true
,08-30 12:20:46.909  4114  4126 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-30 12:20:46.909  4114  4126 D BluetoothAdapterProperties: Setting state to 10
08-30 12:20:46.910  4114  4126 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-30 12:20:46.911  4114  4126 I BluetoothAdapterState: Entering OffState
08-30 12:20:46.913   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-30 12:20:46.945  4114  4114 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-30 12:20:46.946  4114  4114 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-30 12:20:46.946  4114  4127 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-30 12:20:46.956  4114  4127 D bt_stack_manager: event_clean_up_stack finished.
,08-30 12:20:46.956  4114  4114 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-30 12:20:46.962  4114  4114 I art     : System.exit called, status: 0
,08-30 12:20:46.962  4114  4114 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 12:20:47.024   873  1976 I ActivityManager: Process com.android.bluetooth (pid 4114) has died
,08-30 12:20:51.427  3792  3841 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 12:20:51.428  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:20:51.433  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 12:20:51.433  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9ccf826 removed from the list
08-30 12:20:51.433  3792  3841 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 12:20:51.434  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:51.434  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:20:51.437  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:20:51.437  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a40ba14 added. We now have 4 listener(s)
,08-30 12:20:51.438  3792  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:20:51.439  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:20:51.440  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a40ba14 removed from the list
,08-30 12:20:51.440  3792  3841 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:20:51.440  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:20:51.440  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:20:51.442  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:20:51.443  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5b982bd added. We now have 4 listener(s)
08-30 12:20:51.443  3792  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:20:56.454  3792  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:20:56.504   873   890 I ActivityManager: Start proc 4172:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-30 12:20:56.657  4172  4172 D AdapterServiceConfig: Adding HeadsetService
,08-30 12:20:56.657  4172  4172 D AdapterServiceConfig: Adding A2dpService
08-30 12:20:56.657  4172  4172 D AdapterServiceConfig: Adding HidService
,08-30 12:20:56.657  4172  4172 D AdapterServiceConfig: Adding HealthService
08-30 12:20:56.657  4172  4172 D AdapterServiceConfig: Adding PanService
,08-30 12:20:56.658  4172  4172 D AdapterServiceConfig: Adding GattService
08-30 12:20:56.658  4172  4172 D AdapterServiceConfig: Adding BluetoothMapService
,08-30 12:20:56.674  4172  4172 D BluetoothAdapterState: make() - Creating AdapterState
,08-30 12:20:56.674   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7b794f6:true
,08-30 12:20:56.679  4172  4172 I bt_bluedroid: init
,08-30 12:20:56.680  4172  4184 I BluetoothAdapterState: Entering OffState
,08-30 12:20:56.686  4172  4185 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-30 12:20:56.687  4172  4185 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 12:20:56.687  4172  4185 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-30 12:20:56.687  4172  4185 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-30 12:20:56.689  4172  4172 I bt_bluedroid: get_profile_interface socket
,08-30 12:20:56.692  4172  4172 I bt_bluedroid: get_profile_interface sdp
,08-30 12:20:56.695  4172  4188 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 12:20:56.698  4172  4183 I bt_bluedroid: config_hci_snoop_log
,08-30 12:20:56.699  4172  4188 D BluetoothAdapterProperties: Name is: Nexus 6
08-30 12:20:56.700   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-30 12:20:56.712  4172  4184 D BluetoothAdapterState: Current state: OFF, message: 0
,08-30 12:20:56.713  4172  4184 D BluetoothAdapterProperties: Setting state to 14
08-30 12:20:56.713  4172  4184 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-30 12:20:56.718  4172  4184 D BluetoothBondStateMachine: make
,08-30 12:20:56.723  4172  4189 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 12:20:56.732  4172  4184 I BluetoothAdapterState: Entering PendingCommandState
,08-30 12:20:56.735  4172  4172 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-30 12:20:56.743  4172  4172 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7523b57
,08-30 12:20:56.746  4172  4172 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 12:20:56.747  4172  4172 D BtGatt.GattService: Received start request. Starting profile...
08-30 12:20:56.747  4172  4172 D BtGatt.GattService: start()
,08-30 12:20:56.747  4172  4172 I bt_bluedroid: get_profile_interface gatt
,08-30 12:20:56.750  4172  4172 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7523b57
08-30 12:20:56.751  4172  4172 D BtGatt.AdvertiseManager: advertise manager created
,08-30 12:20:56.766  4172  4172 V BluetoothAdapterState: isTurningOff()=false
,08-30 12:20:56.767  4172  4172 V BluetoothAdapterState: isTurningOn()=false
08-30 12:20:56.767  4172  4172 V BluetoothAdapterState: isBleTurningOn()=true
08-30 12:20:56.767  4172  4172 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 12:20:56.770  4172  4184 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-30 12:20:56.770  4172  4184 I bt_bluedroid: enable
,08-30 12:20:56.771  4172  4185 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-30 12:20:56.772  4172  4185 I bt_hci  : start_up
,08-30 12:20:56.793  4172  4185 I bt_vendor: alloc value 0xb39d7189
,08-30 12:20:56.794  4172  4185 I bt_vendor: init
08-30 12:20:56.794  4172  4185 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-30 12:20:56.794  4172  4185 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-30 12:20:56.904  4172  4185 D bt_hci  : start_up starting async portion
08-30 12:20:56.905  4172  4192 I bt_hci  : event_finish_startup
08-30 12:20:56.905  4172  4192 I bt_hci_h4: hal_open
08-30 12:20:56.906  4172  4192 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-30 12:20:56.918  4172  4192 I bt_userial_vendor: device fd = 51 open,
,08-30 12:20:56.947  4172  4192 I bt_hwcfg: bt vendor lib: set UART baud 3000000,
,08-30 12:20:56.979  4172  4192 D bt_hwcfg: Chipset BCM4354A2,
08-30 12:20:56.979  4172  4192 D bt_hwcfg: Target name = [BCM4354A2]
08-30 12:20:56.980  4172  4192 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-30 12:20:57.826  4172  4192 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-30 12:20:57.827  4172  4192 D bt_hwcfg: Settlement delay -- 100 ms
,08-30 12:20:57.827  4172  4192 I bt_hwcfg: Setting fw settlement delay to 100 
,08-30 12:20:57.946  4172  4192 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 12:20:57.947  4172  4192 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-30 12:20:57.975  4172  4192 I bt_hwcfg: vendor lib fwcfg completed
08-30 12:20:57.975  4172  4192 I bt_vendor: firmware callback
,08-30 12:20:57.975  4172  4192 I bt_hci  : firmware_config_callback
,08-30 12:20:57.988  4172  4194 I bt_btu  : btu_task pending for preload complete event
08-30 12:20:57.988  4172  4194 I bt_btu_task: Bluetooth chip preload is complete
08-30 12:20:57.988  4172  4194 I bt_btu  : btu_task received preload complete event
,08-30 12:20:57.998  4172  4194 I         : BTE_InitTraceLevels -- TRC_HCI
08-30 12:20:57.999  4172  4194 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-30 12:20:57.999  4172  4194 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 12:20:57.999  4172  4194 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 12:20:58.000  4172  4194 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 12:20:58.000  4172  4194 I         : BTE_InitTraceLevels -- TRC_A2D
,08-30 12:20:58.000  4172  4194 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 12:20:58.000  4172  4194 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 12:20:58.001  4172  4194 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 12:20:58.001  4172  4194 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 12:20:58.001  4172  4194 I         : BTE_InitTraceLevels -- TRC_SDP
,08-30 12:20:58.001  4172  4194 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 12:20:58.002  4172  4194 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 12:20:58.002  4172  4194 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 12:20:58.002  4172  4194 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 12:20:58.150  4172  4194 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3954d9d
08-30 12:20:58.150  4172  4194 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3954d9d 
,08-30 12:20:58.174  4172  4188 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-30 12:20:58.176  4172  4188 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-30 12:20:58.177  4172  4188 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-30 12:20:58.180  4172  4188 D BluetoothAdapterProperties: Name is: Nexus 6
08-30 12:20:58.186  4172  4188 D BluetoothAdapterProperties: Scan Mode:20
08-30 12:20:58.187  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:20:58.189  4172  4188 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 12:20:58.189  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:20:58.189  4172  4188 D bt_hci  : do_postload posting postload work item
08-30 12:20:58.190  4172  4192 I bt_hci  : event_postload
08-30 12:20:58.190  4172  4192 I bt_vendor: sco_config_cb
08-30 12:20:58.190  4172  4192 I bt_hci  : sco_config_callback postload finished.
,08-30 12:20:58.192  4172  4188 D bt_bte_conf: Device ID record 1 : primary
,08-30 12:20:58.193  4172  4188 D bt_bte_conf:   vendorId            = 000f
08-30 12:20:58.193  4172  4188 D bt_bte_conf:   vendorIdSource      = 0001
08-30 12:20:58.193  4172  4188 D bt_bte_conf:   product             = 1200
08-30 12:20:58.193  4172  4188 D bt_bte_conf:   version             = 1436
08-30 12:20:58.193  4172  4188 D bt_bte_conf:   clientExecutableURL = 
08-30 12:20:58.194  4172  4188 D bt_bte_conf:   serviceDescription  = 
08-30 12:20:58.194  4172  4188 D bt_bte_conf:   documentationURL    = 
,08-30 12:20:58.194  4172  4188 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-30 12:20:58.194  4172  4185 D bt_stack_manager: event_start_up_stack finished
,08-30 12:20:58.196  4172  4184 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-30 12:20:58.196  4172  4192 I bt_vendor: low_power_mode_cb
08-30 12:20:58.197  4172  4184 D BluetoothAdapterProperties: Setting state to 15
08-30 12:20:58.197  4172  4184 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-30 12:20:58.198  4172  4184 I BluetoothAdapterState: Entering BleOnState
,08-30 12:20:58.203  4172  4184 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-30 12:20:58.203  4172  4184 D BluetoothAdapterProperties: Setting state to 11
,08-30 12:20:58.203  4172  4184 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-30 12:20:58.211  4172  4172 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7523b57
,08-30 12:20:58.212  4172  4172 D HeadsetService: Received start request. Starting profile...
08-30 12:20:58.216  4172  4172 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-30 12:20:58.216  4172  4172 D HeadsetStateMachine: make
,08-30 12:20:58.223  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:20:58.227  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:20:58.247  4172  4172 D HeadsetStateMachine: max_hf_connections = 1
08-30 12:20:58.247  4172  4172 I bt_bluedroid: get_profile_interface handsfree
08-30 12:20:58.248  4172  4188 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-30 12:20:58.248  4172  4188 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
08-30 12:20:58.251  4172  4184 I BluetoothAdapterState: Entering PendingCommandState
08-30 12:20:58.254  4172  4172 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7523b57
,08-30 12:20:58.255  4172  4172 D A2dpService: Received start request. Starting profile...
,08-30 12:20:58.256  4172  4172 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-30 12:20:58.257  4172  4172 I bt_bluedroid: get_profile_interface avrcp
,08-30 12:20:58.264  4172  4172 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-30 12:20:58.265  4172  4172 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-30 12:20:58.265  4172  4172 D A2dpStateMachine: make
08-30 12:20:58.267  4172  4172 I bt_bluedroid: get_profile_interface a2dp
,08-30 12:20:58.268  4172  4188 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-30 12:20:58.270  4172  4203 D A2dpStateMachine: Enter Disconnected: -2
,08-30 12:20:58.274  4172  4172 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 12:20:58.274  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 12:20:58.276  4172  4172 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7523b57
,08-30 12:20:58.276  4172  4172 D HidService: Received start request. Starting profile...
,08-30 12:20:58.276  4172  4172 I bt_bluedroid: get_profile_interface hidhost
,08-30 12:20:58.276  4172  4172 D HidService: setHidService(): set to: null
,08-30 12:20:58.277  4172  4188 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39363e5
,08-30 12:20:58.277  4172  4188 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-30 12:20:58.278  4172  4172 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-30 12:20:58.279  4172  4172 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7523b57
,08-30 12:20:58.280  4172  4172 D HealthService: Received start request. Starting profile...
,08-30 12:20:58.283  4172  4172 I bt_bluedroid: get_profile_interface health
08-30 12:20:58.284  4172  4172 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-30 12:20:58.285  4172  4172 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7523b57
08-30 12:20:58.285  4172  4172 D PanService: Received start request. Starting profile...
08-30 12:20:58.286  4172  4172 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-30 12:20:58.286  4172  4172 I bt_bluedroid: get_profile_interface pan
08-30 12:20:58.287  4172  4188 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 12:20:58.289  4172  4172 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7523b57
08-30 12:20:58.289  4172  4172 D BluetoothMapService: Received start request. Starting profile...
08-30 12:20:58.289  4172  4172 D BluetoothMapService: start()
,08-30 12:20:58.292  4172  4172 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-30 12:20:58.293  4172  4172 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-30 12:20:58.293  4172  4172 D BluetoothMapAppObserver: createReceiver()
,08-30 12:20:58.294  4172  4172 D BluetoothMapAppObserver: initObservers()
,08-30 12:20:58.294  4172  4172 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-30 12:20:58.300  4172  4172 V BluetoothAdapterState: isTurningOff()=false
,08-30 12:20:58.300  4172  4172 V BluetoothAdapterState: isTurningOn()=true,
,08-30 12:20:58.300  4172  4172 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 12:20:58.301  4172  4172 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 12:20:58.303  4172  4200 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-30 12:20:58.303  4172  4172 V BluetoothAdapterState: isTurningOff()=false
,08-30 12:20:58.303  4172  4172 V BluetoothAdapterState: isTurningOn()=true
,08-30 12:20:58.303  4172  4172 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:20:58.303  4172  4172 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:20:58.304  4172  4172 V BluetoothAdapterState: isTurningOff()=false
08-30 12:20:58.304  4172  4172 V BluetoothAdapterState: isTurningOn()=true
08-30 12:20:58.304  4172  4172 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:20:58.304  4172  4172 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 12:20:58.304  4172  4172 V BluetoothAdapterState: isTurningOff()=false
08-30 12:20:58.305  4172  4172 V BluetoothAdapterState: isTurningOn()=true
08-30 12:20:58.305  4172  4172 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:20:58.305  4172  4172 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:20:58.305  4172  4172 V BluetoothAdapterState: isTurningOff()=false
,08-30 12:20:58.305  4172  4172 V BluetoothAdapterState: isTurningOn()=true
08-30 12:20:58.305  4172  4172 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:20:58.306  4172  4172 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 12:20:58.306  4172  4172 V BluetoothAdapterState: isTurningOff()=false
,08-30 12:20:58.306  4172  4172 V BluetoothAdapterState: isTurningOn()=true
08-30 12:20:58.306  4172  4172 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 12:20:58.306  4172  4172 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:20:58.306  4172  4184 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-30 12:20:58.306  4172  4184 D BluetoothAdapterProperties: ScanMode =  20
08-30 12:20:58.306  4172  4184 D BluetoothAdapterProperties: State =  11
08-30 12:20:58.307  4172  4184 D BluetoothAdapterProperties: Setting state to 12
,08-30 12:20:58.307  4172  4184 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 12:20:58.307   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 12:20:58.308  4172  4188 D BluetoothAdapterProperties: Scan Mode:21
08-30 12:20:58.308  4172  4188 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 12:20:58.308   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 12:20:58.308  1362  1376 D BluetoothPan: onBluetoothStateChange on: true
,08-30 12:20:58.310   873   873 D BluetoothA2dp: Proxy object connected
,08-30 12:20:58.311  4172  4184 I BluetoothAdapterState: Entering OnState
,08-30 12:20:58.312  1940  2133 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 12:20:58.313  1362  1375 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 12:20:58.314  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-30 12:20:58.314  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:20:58.314  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:20:58.314  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:20:58.314  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:20:58.314  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:20:58.314  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:20:58.314  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 12:20:58.315  1362  2057 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 12:20:58.316  3876  3886 D BluetoothMap: onBluetoothStateChange: up=true
08-30 12:20:58.317  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 12:20:58.317  1362  1362 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 12:20:58.317  1362  1362 D PanProfile: Bluetooth service connected
08-30 12:20:58.318  3876  3887 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 12:20:58.320  4172  4172 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-30 12:20:58.320   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 12:20:58.321  3876  3876 D BluetoothMap: Proxy object connected
08-30 12:20:58.321  4172  4172 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-30 12:20:58.321  3876  3876 D MapProfile: Bluetooth service connected
08-30 12:20:58.321  3876  3876 D BluetoothMap: getConnectedDevices()
,08-30 12:20:58.322  1362  1375 D BluetoothMap: onBluetoothStateChange: up=true
08-30 12:20:58.324  1362  1362 D BluetoothMap: Proxy object connected
08-30 12:20:58.324  1362  1362 D MapProfile: Bluetooth service connected
08-30 12:20:58.324  1362  1362 D BluetoothMap: getConnectedDevices()
08-30 12:20:58.324  3876  3887 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 12:20:58.324  4172  4172 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 12:20:58.325  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:20:58.325  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:20:58.325  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:20:58.325  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:20:58.325  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:20:58.325  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:20:58.325  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:20:58.325  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:20:58.327   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 12:20:58.328  3876  3886 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 12:20:58.328  3876  3876 D BluetoothA2dp: Proxy object connected
08-30 12:20:58.328  4172  4172 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 12:20:58.329  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:20:58.330  1362  1376 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 12:20:58.330  4172  4172 D ObexServerSockets: Succeed to create listening sockets 
08-30 12:20:58.330  4172  4172 D ObexServerSockets0: startAccept()
08-30 12:20:58.331  4172  4172 D ObexServerSockets0: prepareForNewConnect()
,08-30 12:20:58.332  1362  1362 D BluetoothA2dp: Proxy object connected
,08-30 12:20:58.332  3876  4209 D BluetoothPan: onBluetoothStateChange on: true
,08-30 12:20:58.334  1362  1375 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 12:20:58.334  3876  3876 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 12:20:58.334  3876  3876 D PanProfile: Bluetooth service connected
08-30 12:20:58.335  3876  3886 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 12:20:58.336  4172  4172 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-30 12:20:58.337  4172  4172 D BluetoothSdpJni: SDP Create record success - handle: 0
08-30 12:20:58.337   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-30 12:20:58.340  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:20:58.341  4172  4211 D ObexServerSockets0: Accepting socket connection...
,08-30 12:20:58.342  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:20:58.343  4172  4172 D BluetoothMapService: onReceive
08-30 12:20:58.343  1362  1362 D BluetoothInputDevice: Proxy object connected
08-30 12:20:58.343  1362  1362 D HidProfile: Bluetooth service connected
08-30 12:20:58.343  4172  4172 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 12:20:58.344  4172  4172 D BluetoothMapService: STATE_ON
08-30 12:20:58.344  4172  4210 D ObexServerSockets0: Accepting socket connection...
08-30 12:20:58.346  3876  3876 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 12:20:58.350  3876  3876 D BluetoothInputDevice: Proxy object connected
,08-30 12:20:58.350  3876  3876 D HidProfile: Bluetooth service connected
08-30 12:20:58.354  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 12:20:58.364  3876  3876 D DockEventReceiver: finishStartingService: stopping service
,08-30 12:20:58.371  3876  3876 D BluetoothPbap: Proxy object connected
08-30 12:20:58.371  3876  3876 D PbapServerProfile: Bluetooth service connected
08-30 12:20:58.371  1362  1362 D BluetoothPbap: Proxy object connected
08-30 12:20:58.371  1362  1362 D PbapServerProfile: Bluetooth service connected
,08-30 12:20:58.378  4172  4172 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-30 12:20:58.378  4172  4172 D ObexServerSockets0: prepareForNewConnect()
,08-30 12:20:58.381  4172  4215 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 12:20:58.401  4172  4219 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 12:20:58.402  4172  4219 I BtOppRfcommListener: Accept thread started.
,08-30 12:20:58.410   873   873 D BluetoothHeadset: Proxy object connected
08-30 12:20:58.410   873   873 D BluetoothHeadset: Proxy object connected
,08-30 12:20:58.411  1362  1376 D BluetoothHeadset: Proxy object connected
08-30 12:20:58.411  1362  1362 D HeadsetProfile: Bluetooth service connected
08-30 12:20:58.411  1940  1952 D BluetoothHeadset: Proxy object connected
,08-30 12:20:58.411   873   873 D BluetoothHeadset: Proxy object connected
,08-30 12:20:58.412  3876  4209 D BluetoothHeadset: Proxy object connected
08-30 12:20:58.413  1940  2247 D BluetoothHeadset: Proxy object connected
08-30 12:20:58.414  3876  3876 D HeadsetProfile: Bluetooth service connected
,08-30 12:20:58.416  1362  1375 D BluetoothHeadset: Proxy object connected
,08-30 12:20:58.417  1362  1362 D HeadsetProfile: Bluetooth service connected
,08-30 12:20:58.421   873   890 D BluetoothHeadset: Proxy object connected
,08-30 12:20:58.428   873   890 D BluetoothHeadset: Proxy object connected
,08-30 12:20:58.436  3876  3886 D BluetoothHeadset: Proxy object connected
,08-30 12:20:58.437  3876  3876 D HeadsetProfile: Bluetooth service connected
,08-30 12:21:00.312  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:21:00.324  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:21:00.326  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:21:00.382  1509  1529 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 12:21:00.383  1509  1529 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-30 12:21:00.383  1509  1529 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 12:21:00.383  1509  1529 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 12:21:00.439  3508  3508 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-30 12:21:00.440  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-30 12:21:00.441  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-30 12:21:01.474  3792  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:21:01.474  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:21:01.474  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:21:01.474  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:21:01.474  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:21:01.474  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:21:01.474  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:21:01.474  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 12:21:01.481  3792  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 12:21:01.482  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:21:01.482  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5b982bd removed from the list
,08-30 12:21:01.483  3792  3841 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:21:01.483  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:21:01.483  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:21:01.486  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:21:01.486  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@10070b2 added. We now have 4 listener(s)
,08-30 12:21:01.487  3792  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:21:01.490   873  1976 D WifiService: setWifiEnabled: false pid=3792, uid=10000
08-30 12:21:01.491   873  1976 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 12:21:06.505  3792  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:21:06.507   873  1966 D WifiService: setWifiEnabled: true pid=3792, uid=10000
08-30 12:21:06.507   873  1966 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 12:21:06.523   873  1306 D WifiConfigStore: Loading config and enabling all networks 
,08-30 12:21:06.542  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:21:06.542  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:21:06.542  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:21:06.542  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:21:06.542  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:21:06.542  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:21:06.542  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:21:06.542  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 12:21:06.545  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 12:21:06.550  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:21:06.550  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:21:06.550  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:21:06.550  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:21:06.550  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:21:06.550  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:21:06.550  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:21:06.550  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 12:21:06.553  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 12:21:06.558   873  1306 D WifiConfigStore: loaded 0 passpoint configs
,08-30 12:21:06.560   873  1306 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-30 12:21:06.561   873  1306 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-30 12:21:06.562   873  1306 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-30 12:21:06.562   873  1306 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-30 12:21:06.562   873  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-30 12:21:06.562   873  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-30 12:21:06.576   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-30 12:21:06.577   873  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-30 12:21:06.577   372   871 D CommandListener: Setting iface cfg
08-30 12:21:06.578   873  1305 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '156 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 156 Failed to set address (No such device)'
08-30 12:21:06.578   873  1305 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 12:21:06.634   873  1305 D WifiNative-HAL: p2pGetDeviceAddress
,08-30 12:21:06.634   873  1305 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-30 12:21:06.635   873  1306 E native  : do suspend true
,08-30 12:21:06.679   873  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 12:21:08.053   873  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 12:21:08.191   873  1306 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=5.19 rxSuccessRate=5.50 delta 1000 -> 994
08-30 12:21:08.192   873  1306 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-30 12:21:08.192   873  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 12:21:08.215   873  1306 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-30 12:21:08.286   873  1306 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-30 12:21:08.288  1457  1457 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-30 12:21:08.776  1457  1457 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 12:21:08.820  1457  1457 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 12:21:08.821  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-30 12:21:08.830   873  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 12:21:08.847   873  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 12:21:08.848   873  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 12:21:08.848   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-30 12:21:08.874   873  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 12:21:08.893   372   871 D CommandListener: Setting iface cfg
,08-30 12:21:08.893   873  1306 D WifiStateMachine: Start Dhcp Watchdog 3
,08-30 12:21:08.908   873  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-30 12:21:08.930   873  4229 D DhcpClient: Receive thread started
,08-30 12:21:09.021   873  1306 E native  : do suspend false
,08-30 12:21:09.047   873  1842 D DhcpClient: Broadcasting DHCPDISCOVER
,08-30 12:21:09.080   873  4229 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,08-30 12:21:09.081   873  1842 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,08-30 12:21:09.086   873  1842 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-30 12:21:09.101   873  4229 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-30 12:21:09.103   873  1842 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-30 12:21:09.109   372   871 D CommandListener: Setting iface cfg
,08-30 12:21:09.120   873  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-30 12:21:09.121   873  1842 D DhcpClient: Scheduling renewal in 86399s
08-30 12:21:09.122   873  1306 E native  : do suspend true
,08-30 12:21:09.146   873  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-30 12:21:09.148   873  1306 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 12:21:09.150   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-30 12:21:09.153   873  1308 D ConnectivityService: Adding iface wlan0 to network 102
,08-30 12:21:09.159   873  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 12:21:09.214   873  1308 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-30 12:21:09.214   873  1308 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-30 12:21:09.219   873  1308 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-30 12:21:09.221   873  1308 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-30 12:21:09.223   873  1308 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-30 12:21:09.242   873  1308 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-30 12:21:09.254   873  1308 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-30 12:21:09.254   873  1308 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-30 12:21:09.255   873  1306 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-30 12:21:09.255   873  1308 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-30 12:21:09.255   873  1308 D ConnectivityService:    accepting network in place of null
08-30 12:21:09.256   873  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 12:21:09.257   873  1308 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 12:21:09.306   873  4228 D NetlinkSocketObserver: NeighborEvent{elapsedMs=207367, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 12:21:09.322   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 12:21:09.353   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 12:21:09.360   873  1308 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-30 12:21:09.360   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:21:09.362   873  1308 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-30 12:21:09.366   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-30 12:21:09.387  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:21:09.387  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:21:09.387  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:21:09.387  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:21:09.387  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:21:09.387  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:21:09.387  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:21:09.387  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:21:09.393  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:21:09.396  1727  1727 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 12:21:09.399  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:21:09.399  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:21:09.399  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:21:09.399  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:21:09.399  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:21:09.399  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:21:09.399  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:21:09.399  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:21:09.402  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:21:09.405  1727  1727 D SystemUpdateService: onCreate,
,08-30 12:21:09.411  1727  1727 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 12:21:09.418  3749  4238 I BooksSync: Starting books sync for 61035162, extras: ade
,08-30 12:21:09.423   873  4227 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,08-30 12:21:09.425  1727  4239 I SystemUpdateService: active receiver: enabled
,08-30 12:21:09.432  1727  4239 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 12:21:09.436  1727  1727 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
08-30 12:21:09.438  1727  2423 I iu.UploadsManager: num queued entries: 0
,08-30 12:21:09.444  1727  4239 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-30 12:21:09.444  1727  4239 I SystemUpdateService: now status is 0 (complete)
08-30 12:21:09.444  1727  4239 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 12:21:09.444  1727  4239 I SystemUpdateService: file has been verified
,08-30 12:21:09.444  1727  4239 I SystemUpdateService: OTA package size = 12249756
,08-30 12:21:09.449  1727  2423 I iu.UploadsManager: num updated entries: 0
,08-30 12:21:09.449  1727  2423 I iu.SyncManager: NEXT; no task
,08-30 12:21:09.452  1727  4239 I SystemUpdateService: showing system update notification
,08-30 12:21:09.457  1727  1727 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 12:21:09.458  1727  1727 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 12:21:09.460  3931  3931 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:21:09.466  1727  4242 I MDM     : [184] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-30 12:21:09.467  1727  4242 W BaseAppContext: Using Auth Proxy for data requests.
08-30 12:21:09.468  1727  4242 V GoogleAuthProtoRequest: [184] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 12:21:09.470  3931  3931 D SprintDMHelper: simOperator: 
,08-30 12:21:09.470  3931  3931 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 12:21:09.491  3749  4244 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-30 12:21:09.492   873  4227 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 10:21:09 GMT], X-Android-Received-Millis=[1472552469491], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472552469463]}
,08-30 12:21:09.498  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 12:21:09.498   873  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-30 12:21:09.498   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-30 12:21:09.499   873  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-30 12:21:09.501   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-30 12:21:09.513  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:21:09.555  1509  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-30 12:21:09.555  1509  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 12:21:09.555  1509  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 12:21:09.555  1509  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 12:21:09.586  1509  3627 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-30 12:21:09.586  1509  3627 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-30 12:21:09.586  1509  3627 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 12:21:09.586  1509  3627 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 12:21:09.596  3749  4244 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-30 12:21:09.597  3749  4238 E BooksSync: Soft error
08-30 12:21:09.597  3749  4238 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 12:21:09.597  3749  4238 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-30 12:21:09.597  3749  4238 E BooksSync: Sync error
08-30 12:21:09.597  3749  4238 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 12:21:09.597  3749  4238 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-30 12:21:09.597  3749  4238 I BooksSync: Finished books sync
,08-30 12:21:09.614   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 205257, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 12:21:09.628  1727  1727 D SystemUpdateService: onDestroy
,08-30 12:21:09.641  1509  2256 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-30 12:21:09.641  1509  2256 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-30 12:21:09.641  1509  2256 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 12:21:09.641  1509  2256 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 12:21:09.654  1727  4242 E MDM     : [184] SitrepService.a: Error sending sitrep.
,08-30 12:21:09.725  2464  4245 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-30 12:21:10.362   873  1308 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-30 12:21:11.534  3792  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:21:11.534  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:21:11.534  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:21:11.534  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:21:11.534  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:21:11.534  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:21:11.534  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:21:11.534  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:21:11.542  3792  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:21:11.543  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:21:11.543  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@10070b2 removed from the list
08-30 12:21:11.544  3792  3841 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 12:21:11.544  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:21:11.544  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:21:11.556  3792  4252 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-30 12:21:11.557  3792  4252 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-30 12:21:11.988  1870  1977 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-30 12:21:11.988  1870  1977 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-30 12:21:12.018  1509  1509 I ConfigService: onCreate
,08-30 12:21:14.565  3792  4252 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-30 12:21:14.565  3792  4254 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,08-30 12:21:14.566  3792  4252 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,08-30 12:21:14.567  3792  4254 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-30 12:21:14.567  3792  4252 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 12:21:14.568  3792  4254 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 12:21:14.569  3792  4252 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 12:21:14.570  3792  4254 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 12:21:14.572  3792  4256 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 425, name: OutgoingSocketThread/Sender)
,08-30 12:21:14.573  3792  4252 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-30 12:21:14.576  3792  4257 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 426, name: IncomingSocketThread/Sender)
,08-30 12:21:14.576  3792  4254 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-30 12:21:14.580  3792  4258 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 427, name: OutgoingSocketThread/Receiver)
,08-30 12:21:14.581  3792  4258 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 427, thread name: OutgoingSocketThread/Receiver)
08-30 12:21:14.581  3792  4258 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-30 12:21:14.582  3792  4258 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 427, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-30 12:21:14.585  3792  4259 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 428, name: IncomingSocketThread/Receiver)
,08-30 12:21:14.587  3792  4259 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 428, thread name: IncomingSocketThread/Receiver)
,08-30 12:21:14.587  3792  4259 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,08-30 12:21:14.589  3792  4259 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 428, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-30 12:21:17.058  1509  1509 I ConfigService: onDestroy
,08-30 12:21:17.262   873  1308 D ConnectivityService: handlePromptUnvalidated 102
,08-30 12:21:17.563  3792  3841 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-30 12:21:17.566  3792  3841 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-30 12:21:17.574  3792  3841 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@45535f3 Bundle[{}]
08-30 12:21:17.575  3792  3841 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 12:21:17.575  3792  3841 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-30 12:21:17.575  3792  3841 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-30 12:21:17.576  3792  3841 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-30 12:21:17.576  3792  3841 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-30 12:21:17.577  3792  3841 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 12:21:17.581  3792  3841 I System.out: Running OutgoingSocketThread
,08-30 12:21:17.585  3792  4261 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-30 12:21:17.585  3792  4261 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-30 12:21:20.593  3792  4262 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,08-30 12:21:20.594  3792  4262 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-30 12:21:20.594  3792  4262 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 12:21:20.595  3792  4261 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-30 12:21:20.595  3792  4261 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-30 12:21:20.596  3792  4262 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 12:21:20.596  3792  4261 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 12:21:20.599  3792  4264 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 437, name: IncomingSocketThread/Sender)
08-30 12:21:20.599  3792  4261 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 12:21:20.602  3792  4261 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-30 12:21:20.606  3792  4262 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-30 12:21:20.609  3792  4265 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 439, name: OutgoingSocketThread/Sender)
08-30 12:21:20.612  3792  4266 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 440, name: OutgoingSocketThread/Receiver)
08-30 12:21:20.614  3792  4266 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 440, thread name: OutgoingSocketThread/Receiver)
08-30 12:21:20.614  3792  4266 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-30 12:21:20.614  3792  4266 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 440, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-30 12:21:20.615  3792  4267 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 438, name: IncomingSocketThread/Receiver)
08-30 12:21:20.617  3792  4267 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 438, thread name: IncomingSocketThread/Receiver)
08-30 12:21:20.617  3792  4267 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-30 12:21:20.618  3792  4267 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 438, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-30 12:21:23.596  3792  3841 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 449)
,08-30 12:21:23.599  3792  3841 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-30 12:21:23.599  3792  3841 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 450)
,08-30 12:21:23.608  3792  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 12:21:23.608  3792  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b326803 added. We now have 3 listener(s)
,08-30 12:21:23.609  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 12:21:23.610  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 12:21:23.610  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 12:21:23.610  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 12:21:23.610  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5796380 added. We now have 4 listener(s)
08-30 12:21:23.610  3792  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:21:23.611  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 12:21:23.616  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 12:21:23.629  3792  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:21:23.629  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:21:23.629  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:21:23.629  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:21:23.629  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:21:23.629  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:21:23.629  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:21:23.629  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:21:23.633  3792  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:21:23.634  3792  3841 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:21:23.634  3792  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 12:21:23.634  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:21:23.634  3792  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:21:23.634  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 12:21:23.635  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:21:23.635  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 12:21:23.635  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 12:21:23.635  3792  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b326803 removed from the list
08-30 12:21:23.635  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:21:23.635  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5796380 removed from the list
08-30 12:21:23.640  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:21:23.643  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:21:23.644  3792  3841 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:21:23.644  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:21:23.644  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:21:23.644  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:21:23.645  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 12:21:23.645  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:21:23.645  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 12:21:23.646  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5796380 not in the list
,08-30 12:21:23.646  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:21:23.646  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:21:23.647  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 12:21:23.647  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:21:23.647  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:21:23.647  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5796380 not in the list
08-30 12:21:23.647  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:21:23.647  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:21:23.647  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:21:23.647  3792  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b326803 not in the list
08-30 12:21:23.648  3792  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 12:21:23.648  3792  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f80e5fe added. We now have 3 listener(s)
08-30 12:21:23.650  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 12:21:23.650  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 12:21:23.650  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 12:21:23.650  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-30 12:21:23.651  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69815f added. We now have 4 listener(s)
08-30 12:21:23.651  3792  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-30 12:21:23.651  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 12:21:23.660  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-30 12:21:23.671  3792  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-30 12:21:23.671  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:21:23.671  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:21:23.671  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:21:23.671  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:21:23.671  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:21:23.671  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:21:23.671  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:21:23.676  3792  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:21:23.677  3792  3841 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:21:23.677  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 12:21:23.678  3792  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-30 12:21:23.678  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-30 12:21:23.678  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 12:21:23.678  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 12:21:23.680  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:21:23.685  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:21:23.685  3792  3841 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 12:21:23.686  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 12:21:23.697  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 12:21:23.698  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 12:21:23.699  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 12:21:23.705  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 12:21:23.705  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 12:21:23.705  3792  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 12:21:23.706  3792  3841 D BluetoothAdapter: STATE_ON
,08-30 12:21:23.711  4172  4183 D BtGatt.GattService: registerClient() - UUID=d575be47-779b-4d82-8f95-2c9577da93e8
,08-30 12:21:23.712  4172  4188 D BtGatt.GattService: onClientRegistered() - UUID=d575be47-779b-4d82-8f95-2c9577da93e8, clientIf=5
08-30 12:21:23.714  3792  3804 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 12:21:23.715  4172  4208 D BtGatt.GattService: start scan with filters
,08-30 12:21:23.721  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 12:21:23.722  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 12:21:23.722  4172  4191 D BtGatt.ScanManager: handling starting scan
08-30 12:21:23.722  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 12:21:23.722  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 12:21:23.726  4172  4191 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7523b57
,08-30 12:21:23.736  3792  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 12:21:23.737  3792  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 12:21:23.737  3792  3792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 12:21:23.741  4172  4188 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 12:21:23.741  4172  4188 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:21:23.742  4172  4191 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 12:21:23.745  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 12:21:23.754  3792  3841 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 12:21:23.754  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 12:21:23.754  3792  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 12:21:23.754  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:21:23.755  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 12:21:23.756  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-30 12:21:23.756  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 12:21:23.756  3792  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 12:21:23.756  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 12:21:23.756  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 12:21:23.756  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 12:21:23.758  3792  3841 D BluetoothAdapter: STATE_ON
,08-30 12:21:23.759  4172  4208 D BtGatt.GattService: stopScan() - queue size =1
,08-30 12:21:23.760  4172  4188 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 12:21:23.760  4172  4188 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 12:21:23.761  4172  4191 D BtGatt.ScanManager: Starting BLE batch scan
08-30 12:21:23.761  4172  4191 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-30 12:21:23.760  4172  4201 D BtGatt.GattService: unregisterClient() - clientIf=5,
08-30 12:21:23.763  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 12:21:23.763  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-30 12:21:23.763  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 12:21:23.764  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 12:21:23.764  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 12:21:23.768  3792  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 12:21:23.768  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 12:21:23.769  3792  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 12:21:23.769  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 12:21:23.770  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 12:21:23.773  3792  3792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 12:21:23.773  3792  3792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 12:21:23.774  3792  3792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 12:21:23.794  4172  4188 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 12:21:23.794  4172  4188 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:21:23.817  4172  4188 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 12:21:23.817  4172  4188 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:21:23.845  4172  4188 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 12:21:23.846  4172  4188 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:21:23.847  4172  4191 D BtGatt.ScanManager: stopping BLe Batch
,08-30 12:21:23.870  4172  4188 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-30 12:21:23.870  4172  4188 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 12:21:23.871  4172  4191 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 12:21:23.892  4172  4188 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-30 12:21:23.893  4172  4188 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:21:24.274  3792  3792 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 12:21:24.275  3792  3792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:21:24.275  3792  3792 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 12:21:26.773  3792  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 12:21:26.774  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:21:26.774  3792  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 12:21:26.775  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:21:26.775  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:21:26.775  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:21:26.776  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 12:21:26.776  3792  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f80e5fe removed from the list
,08-30 12:21:26.776  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:21:26.777  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69815f removed from the list
08-30 12:21:26.777  3792  3841 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 12:21:26.778  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:21:26.780  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:21:26.780  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:21:26.784  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 12:21:26.784  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:21:26.784  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:21:26.784  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69815f not in the list
08-30 12:21:26.785  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:21:26.785  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:21:26.789  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 12:21:26.790  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:21:26.790  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-30 12:21:26.790  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69815f not in the list
08-30 12:21:26.790  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:21:26.791  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:21:26.791  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:21:26.791  3792  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f80e5fe not in the list
08-30 12:21:26.793  3792  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 12:21:26.794  3792  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f02298 added. We now have 3 listener(s)
,08-30 12:21:26.800  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 12:21:26.800  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 12:21:26.800  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 12:21:26.801  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 12:21:26.801  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e593af1 added. We now have 4 listener(s)
08-30 12:21:26.801  3792  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:21:26.803  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 12:21:26.810  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 12:21:26.816  3792  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:21:26.816  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:21:26.816  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:21:26.816  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:21:26.816  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:21:26.816  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:21:26.816  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:21:26.816  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:21:26.819  3792  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:21:26.820  3792  3841 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 12:21:26.820  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-30 12:21:26.821  3792  3841 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-30 12:21:26.821  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-30 12:21:26.821  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-30 12:21:26.821  3792  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-30 12:21:26.821  3792  3841 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 12:21:26.822  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:21:26.823  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-30 12:21:26.823  3792  3841 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 12:21:26.824  3792  3841 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-30 12:21:26.824  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 12:21:26.824  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-30 12:21:26.824  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:21:26.824  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 12:21:26.824  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:21:26.827  3792  4268 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 12:21:26.831  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:21:26.832  3792  3792 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 12:21:26.835  3792  4268 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-30 12:21:26.835  3792  3841 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 12:21:26.836  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 12:21:26.845  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 12:21:26.847  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 12:21:26.847  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 12:21:26.851  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-30 12:21:26.852  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 12:21:26.853  3792  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,08-30 12:21:26.856  3792  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-30 12:21:26.856  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-30 12:21:26.856  3792  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,08-30 12:21:26.857  3792  3841 D BluetoothAdapter: STATE_ON
,08-30 12:21:26.860  4172  4182 D BtGatt.GattService: registerClient() - UUID=e3dcd415-9f10-4e1b-a402-2ef99a815694
,08-30 12:21:26.861  4172  4188 D BtGatt.GattService: onClientRegistered() - UUID=e3dcd415-9f10-4e1b-a402-2ef99a815694, clientIf=5
08-30 12:21:26.861  3792  3803 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-30 12:21:26.864  4172  4190 D BtGatt.AdvertiseManager: message : 0
,08-30 12:21:26.867  4172  4190 D BtGatt.AdvertiseManager: starting multi advertising
,08-30 12:21:26.900  4172  4188 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-30 12:21:26.920  4172  4188 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-30 12:21:26.922  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-30 12:21:26.923  3792  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 12:21:26.930  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 12:21:26.934  3792  3792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-30 12:21:26.935  3792  3792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,08-30 12:21:26.935  3792  3792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-30 12:21:26.935  3792  3792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,08-30 12:21:26.936  3792  3792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,08-30 12:21:26.936  3792  3792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
08-30 12:21:26.941  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-30 12:21:26.947  3792  3792 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-30 12:21:26.948  3792  3792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-30 12:21:27.449  3792  3792 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-30 12:21:27.450  3792  3792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 12:21:27.450  3792  3792 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 12:21:29.943  3792  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 12:21:29.944  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,08-30 12:21:29.944  3792  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 12:21:29.944  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-30 12:21:29.945  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 12:21:29.945  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 12:21:29.948  3792  4268 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-30 12:21:29.948  3792  4268 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-30 12:21:29.949  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 12:21:29.949  3792  4268 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 12:21:29.949  3792  3841 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 12:21:29.949  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 12:21:29.949  3792  3792 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 12:21:29.950  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 12:21:29.950  3792  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 12:21:29.950  3792  3792 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 12:21:29.950  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 12:21:29.950  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 12:21:29.953  3792  3841 D BluetoothAdapter: STATE_ON
08-30 12:21:29.953  3792  3841 D BluetoothLeScanner: could not find callback wrapper
08-30 12:21:29.953  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 12:21:29.954  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,08-30 12:21:29.957  4172  4190 D BtGatt.AdvertiseManager: message : 1
08-30 12:21:29.958  4172  4190 D BtGatt.AdvertiseManager: stop advertise for client 5
08-30 12:21:29.967  4172  4188 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
08-30 12:21:29.967  4172  4188 D BtGatt.GattService: Client app is not null!
,08-30 12:21:29.969  4172  4208 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 12:21:29.970  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 12:21:29.970  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-30 12:21:29.970  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-30 12:21:29.971  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-30 12:21:29.971  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-30 12:21:29.974  3792  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 12:21:29.974  3792  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 12:21:29.974  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 12:21:29.975  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 12:21:29.978  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 12:21:29.979  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:21:29.979  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:21:29.979  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 12:21:29.979  3792  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f02298 removed from the list
08-30 12:21:29.980  3792  3792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 12:21:29.980  3792  3792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 12:21:29.980  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:21:29.980  3792  3792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 12:21:29.980  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e593af1 removed from the list
08-30 12:21:29.981  3792  3841 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 12:21:29.981  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:21:29.983  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:21:29.983  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:21:29.986  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 12:21:29.986  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:21:29.986  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:21:29.986  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e593af1 not in the list
08-30 12:21:29.986  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:21:29.986  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:21:29.988  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:21:29.988  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 12:21:29.988  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:21:29.989  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e593af1 not in the list
08-30 12:21:29.989  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:21:29.989  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:21:29.989  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:21:29.990  3792  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f02298 not in the list
,08-30 12:21:29.991  3792  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 12:21:29.991  3792  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e126a62 added. We now have 3 listener(s)
,08-30 12:21:29.996  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 12:21:29.996  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 12:21:29.996  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 12:21:29.996  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:21:29.997  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40d57f3 added. We now have 4 listener(s)
08-30 12:21:29.997  3792  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:21:29.998  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 12:21:30.003  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 12:21:30.011  3792  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:21:30.011  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:21:30.011  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:21:30.011  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:21:30.011  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:21:30.011  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:21:30.011  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:21:30.011  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:21:30.014  3792  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:21:30.014  3792  3841 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:21:30.015  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 12:21:30.015  3792  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 12:21:30.015  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 12:21:30.015  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:21:30.016  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 12:21:30.019  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:21:30.021  3792  3841 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 12:21:30.021  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 12:21:30.024  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:21:30.030  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 12:21:30.032  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 12:21:30.032  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 12:21:30.038  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 12:21:30.038  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 12:21:30.038  3792  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 12:21:30.039  3792  3841 D BluetoothAdapter: STATE_ON
,08-30 12:21:30.043  4172  4201 D BtGatt.GattService: registerClient() - UUID=39ea4c2d-3f84-4037-bf78-f92f53027469
,08-30 12:21:30.044  4172  4188 D BtGatt.GattService: onClientRegistered() - UUID=39ea4c2d-3f84-4037-bf78-f92f53027469, clientIf=5
08-30 12:21:30.045  3792  3803 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 12:21:30.045  4172  4183 D BtGatt.GattService: start scan with filters
,08-30 12:21:30.052  4172  4191 D BtGatt.ScanManager: handling starting scan
,08-30 12:21:30.052  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 12:21:30.052  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 12:21:30.052  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-30 12:21:30.053  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 12:21:30.058  3792  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 12:21:30.059  3792  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 12:21:30.059  3792  3792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 12:21:30.062  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 12:21:30.073  4172  4188 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 12:21:30.073  4172  4188 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 12:21:30.074  4172  4191 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 12:21:30.089  4172  4188 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 12:21:30.090  4172  4188 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:21:30.090  4172  4191 D BtGatt.ScanManager: Starting BLE batch scan
08-30 12:21:30.090  4172  4191 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 12:21:30.121  4172  4188 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 12:21:30.121  4172  4188 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:21:30.141  4172  4188 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 12:21:30.141  4172  4188 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:21:30.481  3792  3792 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 12:21:30.559  3792  3792 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-30 12:21:30.560  3792  3792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 12:21:30.560  3792  3792 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 12:21:31.645  4172  4172 D BtGatt.ScanManager: awakened up at time 229706
,08-30 12:21:31.648  4172  4191 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 12:21:31.712  4172  4188 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=9
08-30 12:21:31.712  4172  4188 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 12:21:31.712  4172  4188 D BtGatt.GattService: current time is 229774271055
08-30 12:21:31.713  4172  4188 D BtGatt.GattService: Batch record : [56, 33, 126, 102, -83, 97, 1, -128, -88, 21, 0, 23, 2, 1, 26, 19, -1, 76, 0, 12, 14, 0, 48, 62, -125, -121, 10, 34, -40, 47, -109, -95, -75, -67, 55, 0, 95, -41, -70, -73, -96, 122, 1, -128, -88, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 96, -125, 52, 37, -41, -58, 0, 35, 97, 126, -92, 22, -56, 1, -128, -83, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -97, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -84, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -83, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 56, 33, 126, 102, -83, 97, 1, -128, -88, 0, 0, 23, 2, 1, 26, 19, -1, 76, 0, 12, 14, 0, 49, 62, -114, 126, -50, 81, 15, -72, -16, -72, -51, -85, -79, 0, 71, -122, -77, 84, 69, -12, 1, -128, -88, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 56, 33, 126, 102, -83, 97, 1, -128, -90, 1, 0, 23, 2, 1, 26, 19, -1, 76, 0, 12, 14, 0, 49, 62, -114, 126, -50, 81, 15, -72, -16, -72, -51, -85, -79, 0]
,08-30 12:21:31.714  4172  4188 D BtGatt.GattService: ScanRecord : [2, 1, 26, 19, -1, 76, 0, 12, 14, 0, 48, 62, -125, -121, 10, 34, -40, 47, -109, -95, -75, -67, 55]
08-30 12:21:31.715  4172  4188 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 96, -125, 52, 37, -41, -58]
,08-30 12:21:31.715  4172  4188 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-30 12:21:31.715  4172  4188 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-30 12:21:31.716  4172  4188 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-30 12:21:31.716  4172  4188 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-30 12:21:31.716  4172  4188 D BtGatt.GattService: ScanRecord : [2, 1, 26, 19, -1, 76, 0, 12, 14, 0, 49, 62, -114, 126, -50, 81, 15, -72, -16, -72, -51, -85, -79]
,08-30 12:21:31.716  4172  4188 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-30 12:21:31.716  4172  4188 D BtGatt.GattService: ScanRecord : [2, 1, 26, 19, -1, 76, 0, 12, 14, 0, 49, 62, -114, 126, -50, 81, 15, -72, -16, -72, -51, -85, -79]
,08-30 12:21:31.726  3792  3792 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 60:83:34:25:D7:C6 1], added - the peer count is 1
,08-30 12:21:31.728  3792  3792 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 60:83:34:25:D7:C6 1], Bluetooth address: 60:83:34:25:D7:C6, device name: '', device address: ''
,08-30 12:21:33.076  3792  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 12:21:33.077  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 12:21:33.077  3792  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 12:21:33.077  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:21:33.078  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-30 12:21:33.078  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-30 12:21:33.078  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 12:21:33.078  3792  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 12:21:33.079  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 12:21:33.079  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 12:21:33.079  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 12:21:33.082  3792  3841 D BluetoothAdapter: STATE_ON
,08-30 12:21:33.083  4172  4183 D BtGatt.GattService: stopScan() - queue size =1
08-30 12:21:33.086  4172  4208 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 12:21:33.087  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 12:21:33.088  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-30 12:21:33.088  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 12:21:33.089  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-30 12:21:33.089  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 12:21:33.092  3792  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 12:21:33.093  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 12:21:33.093  3792  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 12:21:33.094  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 12:21:33.095  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 12:21:33.096  3792  3841 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
08-30 12:21:33.098  4172  4172 D BtGatt.ScanManager: awakened up at time 231160
08-30 12:21:33.101  3792  3792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 12:21:33.101  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:21:33.101  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:21:33.102  3792  3792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 12:21:33.102  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:21:33.102  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 12:21:33.102  3792  3792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 12:21:33.102  3792  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e126a62 removed from the list
08-30 12:21:33.102  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:21:33.103  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40d57f3 removed from the list
08-30 12:21:33.103  3792  3841 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 12:21:33.103  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:21:33.104  4172  4188 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 12:21:33.104  4172  4188 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 12:21:33.104  4172  4191 D BtGatt.ScanManager: stopping BLe Batch
08-30 12:21:33.105  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:21:33.105  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:21:33.108  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:21:33.108  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 12:21:33.109  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 12:21:33.109  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40d57f3 not in the list
08-30 12:21:33.109  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:21:33.109  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:21:33.110  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:21:33.110  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 12:21:33.110  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:21:33.110  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40d57f3 not in the list
08-30 12:21:33.110  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:21:33.111  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:21:33.111  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:21:33.111  3792  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e126a62 not in the list
08-30 12:21:33.112  3792  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 12:21:33.112  3792  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9d13ce5 added. We now have 3 listener(s)
08-30 12:21:33.114  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 12:21:33.114  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 12:21:33.114  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 12:21:33.114  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:21:33.114  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc2e3ba added. We now have 4 listener(s)
08-30 12:21:33.114  3792  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 12:21:33.114  4172  4188 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 12:21:33.114  4172  4188 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 12:21:33.115  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 12:21:33.115  4172  4191 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 12:21:33.117  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 12:21:33.123  3792  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:21:33.123  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:21:33.123  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:21:33.123  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:21:33.123  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:21:33.123  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:21:33.123  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:21:33.123  3792  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:21:33.125  3792  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:21:33.125  3792  3841 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 12:21:33.126  3792  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:21:33.126  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:21:33.126  3792  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 12:21:33.126  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:21:33.126  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:21:33.128  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 12:21:33.128  3792  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 12:21:33.128  3792  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9d13ce5 removed from the list
08-30 12:21:33.128  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:21:33.128  3792  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc2e3ba removed from the list
08-30 12:21:33.128  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:21:33.128  3792  3841 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 12:21:33.128  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:21:33.129  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:21:33.129  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:21:33.130  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:21:33.130  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:21:33.130  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 12:21:33.130  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc2e3ba not in the list
08-30 12:21:33.131  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:21:33.131  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:21:33.131  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:21:33.133  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:21:33.134  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 12:21:33.134  3792  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:21:33.134  4172  4188 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
08-30 12:21:33.134  4172  4188 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 12:21:33.134  3792  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc2e3ba not in the list
08-30 12:21:33.135  4172  4188 D BtGatt.GattService: current time is 231196394610
,08-30 12:21:33.135  4172  4188 D BtGatt.GattService: Batch record : [56, 33, 126, 102, -83, 97, 1, -128, -93, 27, 0, 23, 2, 1, 26, 19, -1, 76, 0, 12, 14, 0, 49, 62, -114, 126, -50, 81, 15, -72, -16, -72, -51, -85, -79, 0, 95, -41, -70, -73, -96, 122, 1, -128, -88, 28, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 96, -125, 52, 37, -41, -58, 0]
08-30 12:21:33.135  3792  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:21:33.135  4172  4188 D BtGatt.GattService: ScanRecord : [2, 1, 26, 19, -1, 76, 0, 12, 14, 0, 49, 62, -114, 126, -50, 81, 15, -72, -16, -72, -51, -85, -79]
08-30 12:21:33.135  3792  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:21:33.135  4172  4188 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 96, -125, 52, 37, -41, -58]
08-30 12:21:33.135  3792  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:21:33.135  3792  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9d13ce5 not in the list
,08-30 12:21:33.138  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-30 12:21:33.138  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 12:21:33.139  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-30 12:21:33.139  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 12:21:33.139  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-30 12:21:33.140  3792  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 12:21:33.603  3792  3792 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 12:21:35.161  3792  4270 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 459, name: My test thread name)
,08-30 12:21:37.159  3792  3841 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 459
,08-30 12:21:37.160  3792  3841 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 459, name: My test thread name)
,08-30 12:21:37.166  3792  4271 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 460, name: My test thread name)
,08-30 12:21:37.167  3792  4271 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 460, thread name: My test thread name)
08-30 12:21:37.167  3792  4271 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 460, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-30 12:21:37.171  3792  3841 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 12:21:37.180  3792  4272 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 464, name: My test thread name)
,08-30 12:21:37.181  3792  4272 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 464, thread name: My test thread name): Test exception.
08-30 12:21:37.181  3792  4272 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 464, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-30 12:21:37.188  3792  3841 I jxcore-log: Total number of executed tests:  82
08-30 12:21:37.188  3792  3841 I jxcore-log: 
,08-30 12:21:37.190  3792  3841 I jxcore-log: Number of passed tests:  82
08-30 12:21:37.190  3792  3841 I jxcore-log: 
,08-30 12:21:37.190  3792  3841 I jxcore-log: Number of failed tests:  0
08-30 12:21:37.190  3792  3841 I jxcore-log: 
08-30 12:21:37.191  3792  3841 I jxcore-log: Number of ignored tests:  0
08-30 12:21:37.191  3792  3841 I jxcore-log: 
08-30 12:21:37.192  3792  3841 I jxcore-log: Total duration:  101366
08-30 12:21:37.192  3792  3841 I jxcore-log: 
,08-30 12:21:37.201  3792  3841 I jxcore-log: Unit Test app is loaded
08-30 12:21:37.201  3792  3841 I jxcore-log: 
,08-30 12:21:37.210  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:21:37.210  3792  3841 I jxcore-log: 
,08-30 12:21:37.214  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:21:37.214  3792  3841 I jxcore-log: 
,08-30 12:21:37.216  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:21:37.216  3792  3841 I jxcore-log: 
,08-30 12:21:37.217  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:21:37.217  3792  3841 I jxcore-log: 
,08-30 12:21:37.219  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-30 12:21:37.219  3792  3841 I jxcore-log: 
,08-30 12:21:37.220  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 12:21:37.220  3792  3841 I jxcore-log: 
,08-30 12:21:37.223  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:21:37.223  3792  3841 I jxcore-log: 
,08-30 12:21:37.225  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:21:37.225  3792  3841 I jxcore-log: 
,08-30 12:21:37.226  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-30 12:21:37.226  3792  3841 I jxcore-log: 
,08-30 12:21:37.227  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 12:21:37.227  3792  3841 I jxcore-log: 
,08-30 12:21:37.228  3792  3792 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-30 12:21:37.228  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 12:21:37.228  3792  3841 I jxcore-log: 
,08-30 12:21:37.229  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:21:37.229  3792  3841 I jxcore-log: 
08-30 12:21:37.230  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:21:37.230  3792  3841 I jxcore-log: 
,08-30 12:21:37.231  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:21:37.231  3792  3841 I jxcore-log: 
08-30 12:21:37.232  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 12:21:37.232  3792  3841 I jxcore-log: 
08-30 12:21:37.233  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 12:21:37.233  3792  3841 I jxcore-log: 
,08-30 12:21:37.234  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 12:21:37.234  3792  3841 I jxcore-log: 
08-30 12:21:37.236  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
08-30 12:21:37.236  3792  3841 I jxcore-log: 
08-30 12:21:37.237  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 12:21:37.237  3792  3841 I jxcore-log: 
,08-30 12:21:37.237  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 12:21:37.237  3792  3841 I jxcore-log: 
08-30 12:21:37.238  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 12:21:37.238  3792  3841 I jxcore-log: 
08-30 12:21:37.239  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 12:21:37.239  3792  3841 I jxcore-log: 
08-30 12:21:37.240  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 12:21:37.240  3792  3841 I jxcore-log: 
08-30 12:21:37.241  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:21:37.241  3792  3841 I jxcore-log: 
,08-30 12:21:37.242  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:21:37.242  3792  3841 I jxcore-log: 
08-30 12:21:37.243  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:21:37.243  3792  3841 I jxcore-log: 
,08-30 12:21:37.244  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 12:21:37.244  3792  3841 I jxcore-log: 
08-30 12:21:37.244  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 12:21:37.244  3792  3841 I jxcore-log: 
,08-30 12:21:37.245  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 12:21:37.245  3792  3841 I jxcore-log: 
08-30 12:21:37.245  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 12:21:37.245  3792  3841 I jxcore-log: 
08-30 12:21:37.246  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 12:21:37.246  3792  3841 I jxcore-log: 
,08-30 12:21:37.246  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 12:21:37.246  3792  3841 I jxcore-log: 
08-30 12:21:37.247  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 12:21:37.247  3792  3841 I jxcore-log: 
08-30 12:21:37.247  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 12:21:37.247  3792  3841 I jxcore-log: 
,08-30 12:21:37.248  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 12:21:37.248  3792  3841 I jxcore-log: 
08-30 12:21:37.249  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 12:21:37.249  3792  3841 I jxcore-log: 
08-30 12:21:37.249  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 12:21:37.249  3792  3841 I jxcore-log: 
,08-30 12:21:37.250  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 12:21:37.250  3792  3841 I jxcore-log: 
08-30 12:21:37.250  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 12:21:37.250  3792  3841 I jxcore-log: 
,08-30 12:21:37.251  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 12:21:37.251  3792  3841 I jxcore-log: 
08-30 12:21:37.251  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 12:21:37.251  3792  3841 I jxcore-log: 
08-30 12:21:37.252  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 12:21:37.252  3792  3841 I jxcore-log: 
,08-30 12:21:37.252  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 12:21:37.252  3792  3841 I jxcore-log: 
08-30 12:21:37.253  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:21:37.253  3792  3841 I jxcore-log: 
08-30 12:21:37.253  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:21:37.253  3792  3841 I jxcore-log: 
,08-30 12:21:37.254  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:21:37.254  3792  3841 I jxcore-log: 
08-30 12:21:37.254  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:21:37.254  3792  3841 I jxcore-log: 
,08-30 12:21:37.255  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:21:37.255  3792  3841 I jxcore-log: 
08-30 12:21:37.255  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 12:21:37.255  3792  3841 I jxcore-log: 
08-30 12:21:37.256  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:21:37.256  3792  3841 I jxcore-log: 
,08-30 12:21:37.256  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-30 12:21:37.256  3792  3841 I jxcore-log: 
08-30 12:21:37.257  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:21:37.257  3792  3841 I jxcore-log: 
08-30 12:21:37.258  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 12:21:37.258  3792  3841 I jxcore-log: 
08-30 12:21:37.258  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-30 12:21:37.258  3792  3841 I jxcore-log: 
,08-30 12:21:37.259  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
08-30 12:21:37.259  3792  3841 I jxcore-log: 
08-30 12:21:37.260  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:21:37.260  3792  3841 I jxcore-log: 
,08-30 12:21:37.260  3792  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 12:21:37.260  3792  3841 I jxcore-log: 
,08-30 12:21:37.263  3792  3841 I jxcore-log: My device name is: motorola-Nexus 6
08-30 12:21:37.263  3792  3841 I jxcore-log: 
,08-30 12:21:37.264  3792  3841 I jxcore-log: WARN testUtils: myNameCallback not set!
08-30 12:21:37.264  3792  3841 I jxcore-log: 
,08-30 12:21:37.300  3792  4270 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 459, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,08-30 12:21:39.858  3792  3841 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-30 12:21:39.858  3792  3841 I jxcore-log: 
,08-30 12:21:40.330  3792  3841 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-30 12:21:40.330  3792  3841 I jxcore-log: 
,08-30 12:21:40.357  3792  3841 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-30 12:21:40.357  3792  3841 I jxcore-log: 
,08-30 12:21:41.630  3749  4273 I BooksSync: Starting books sync for 61035162, extras: ade
,08-30 12:21:41.667  3749  4274 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-30 12:21:41.679  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:21:41.681  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:21:41.714  1509  2256 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 12:21:41.714  1509  2256 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 12:21:41.714  1509  2256 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 12:21:41.714  1509  2256 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 12:21:41.742  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:21:41.744  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:21:41.773  1509  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 12:21:41.773  1509  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 12:21:41.774  1509  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 12:21:41.774  1509  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 12:21:41.793  3749  4274 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-30 12:21:41.794  3749  4273 E BooksSync: Soft error
08-30 12:21:41.794  3749  4273 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 12:21:41.794  3749  4273 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-30 12:21:41.794  3749  4273 E BooksSync: Sync error
08-30 12:21:41.794  3749  4273 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 12:21:41.794  3749  4273 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-30 12:21:41.794  3749  4273 I BooksSync: Finished books sync
,08-30 12:21:41.804   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 239557, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 12:21:41.876  3792  3841 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-30 12:21:41.876  3792  3841 I jxcore-log: 
,08-30 12:21:42.125  3792  3841 I jxcore-log: ERROR runTests: 
08-30 12:21:42.125  3792  3841 I jxcore-log: 
,08-30 12:21:42.128  3792  3841 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 12:21:42.128  3792  3841 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-30 12:21:42.129  3792  3841 I jxcore-log: WARN testUtils: logCallback not set!
08-30 12:21:42.129  3792  3841 I jxcore-log: 
,08-30 12:21:42.139  3792  3841 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 12:21:42.139  3792  3841 I jxcore-log:     _functionName: 'loadFile',
08-30 12:21:42.139  3792  3841 I jxcore-log:     _lineNumber: '26',
08-30 12:21:42.139  3792  3841 I jxcore-log:     _columnNumber: '11',
08-30 12:21:42.139  3792  3841 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-30 12:21:42.139  3792  3841 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 12:21:42.139  3792  3841 I jxcore-log:     _functionName: '',
08-30 12:21:42.139  3792  3841 I jxcore-log:     _lineNumber: '38',
08-30 12:21:42.139  3792  3841 I jxcore-log:     _columnNumber: '7',
08-30 12:21:42.139  3792  3841 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-30 12:21:42.139  3792  3841 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 12:21:42.139  3792  3841 I jxcore-log:     _functionName: '',
08-30 12:21:42.139  3792  3841 I jxcore-log:     _lineNumber: '35',
08-30 12:21:42.139  3792  3841 I jxcore-log:     _columnNumber: '3',
08-30 12:21:42.139  3792  3841 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-30 12:21:42.139  3792  3841 I jxcore-log:   { _fileName: 'module.js',
08-30 12:21:42.139  3792  3841 I jxcore-log:     _functionName: '$w.prototype._compile',
08-30 12:21:42.139  3792  3841 I jxcore-log:     _lineNumber: '621',
08-30 12:21:42.139  3792  3841 I jxcore-log:     _columnNumber: '8',
08-30 12:21:42.139  3792  3841 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-30 12:21:42.139  3792  3841 I jxcore-log:   { _fileName: 'module.js',
08-30 12:21:42.139  3792  3841 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-30 12:21:42.139  3792  3841 I jxcore-log:     _lineNumber: '651',
08-30 12:21:42.139  3792  3841 I jxcore-log:     _columnNumber: '1',
08-30 12:21:42.139  3792  3841 I jxcore-log:    
,08-30 12:21:42.139  3792  3841 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-30 12:21:42.139  3792  3841 I jxcore-log: 
,08-30 12:21:42.139  3792  3841 E jxcore-log: Error: 
08-30 12:21:42.139  3792  3841 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 12:21:42.140  3792  3841 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-30 12:21:42.140  3792  3841 E jxcore-log: 
,08-30 12:21:42.815  4275  4275 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-30 12:21:42.823  4275  4275 D AndroidRuntime: CheckJNI is OFF
,08-30 12:21:42.865  4275  4275 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-30 12:21:42.913  4275  4275 I Radio-JNI: register_android_hardware_Radio DONE
,08-30 12:21:42.935  4275  4275 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 12:21:42.949   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-30 12:21:42.950   873   886 I ActivityManager: Killing 3792:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-30 12:21:43.059   873   896 W PackageSettings: Skipping PackageSetting{48275e8 com.example.hello/10273} due to missing metadata
,08-30 12:21:43.084   873  1995 I WindowState: WIN DEATH: Window{a7b3713 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 12:21:43.084   873  1307 D WifiService: Client connection lost with reason: 4
08-30 12:21:43.085   873  1953 D GraphicsStats: Buffer count: 2
,08-30 12:21:43.112   873   896 I art     : Starting a blocking GC Explicit
,08-30 12:21:43.117   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-30 12:21:43.117   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-30 12:21:43.120   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-30 12:21:43.120   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-30 12:21:43.120   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-30 12:21:43.120   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231),
08-30 12:21:43.120   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-30 12:21:43.120   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
,08-30 12:21:43.120   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-30 12:21:43.120   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
,08-30 12:21:43.120   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-30 12:21:43.120   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-30 12:21:43.120   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-30 12:21:43.120   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-30 12:21:43.120   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-30 12:21:43.120   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-30 12:21:43.120   873   886 E ActivityManager: 	,at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-30 12:21:43.120   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-30 12:21:43.120   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:21:43.120   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:21:43.120   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 12:21:43.120   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-30 12:21:43.125   873   886 I ActivityManager:   Force finishing activity ActivityRecord{2cc24d8 u0 com.test.thalitest/.MainActivity t2}
,08-30 12:21:43.133   873  2035 W ActivityManager: Spurious death for ProcessRecord{4156b61 0:com.test.thalitest/u0a0}, curProc for 3792: null
,08-30 12:21:43.161   873   896 I art     : Explicit concurrent mark sweep GC freed 31983(2003KB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 29MB/43MB, paused 986us total 47.345ms
,08-30 12:21:43.190   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-30 12:21:43.195  4275  4275 I art     : System.exit called, status: 0
,08-30 12:21:43.195  4275  4275 I AndroidRuntime: VM exiting with result code 0.
,08-30 12:21:43.199   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-30 12:21:43.218   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-30 12:21:43.223  4172  4172 D BluetoothMapAppObserver: onReceive
08-30 12:21:43.223  4172  4172 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-30 12:21:43.233  1870  1870 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-30 12:21:43.235  2069  2280 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-30 12:21:43.240   873  1296 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 12:21:43.250  3637  3637 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-30 12:21:43.266  1940  1940 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-30 12:21:43.279  1870  4286 I Keyboard.Facilitator.DecoderInitializer: run()
,08-30 12:21:43.283  1870  4286 I Decoder : createOrResetDecoder
,08-30 12:21:43.302   873  3738 I ActivityManager: Start proc 4289:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-30 12:21:43.306   873  1304 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,08-30 12:21:43.316  1509  1509 I ConfigService: onCreate
,08-30 12:21:43.321  1509  4297 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-30 12:21:43.321  1509  4297 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:21:43.321  1509  4297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 12:21:43.321  1509  4297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 12:21:43.321  1509  4297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 12:21:43.321  1509  4297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 12:21:43.321  1509  4297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 12:21:43.321  1509  4297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 12:21:43.321  1509  4297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 12:21:43.321  1509  4297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 12:21:43.321  1509  4297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 12:21:43.321  1509  4297 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 12:21:43.321  1509  4297 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 12:21:43.321  1509  4297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 12:21:43.321  1509  4297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 12:21:43.321  1509  4297 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-30 12:21:43.321  1509  4297 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-30 12:21:43.321  1509  4297 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-30 12:21:43.323  1509  4297 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-30 12:21:43.323  1509  4297 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:21:43.323  1509  4297 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 12:21:43.323  1509  4297 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 12:21:43.323  1509  4297 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 12:21:43.323  1509  4297 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 12:21:43.323  1509  4297 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 12:21:43.323  1509  4297 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 12:21:43.323  1509  4297 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 12:21:43.323  1509  4297 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 12:21:43.323  1509  4297 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 12:21:43.323  1509  4297 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 12:21:43.323  1509  4297 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 12:21:43.323  1509  4297 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 12:21:43.323  1509  4297 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 12:21:43.323  1509  4297 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-30 12:21:43.323  1509  4297 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-30 12:21:43.323  1509  4297 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-30 12:21:43.325  1509  4297 W SQLiteOpenHelper: Opened config.db in read-only mode
08-30 12:21:43.327   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-30 12:21:43.338  1870  4286 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-30 12:21:43.375  4289  4289 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-30 12:21:43.382   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-30 12:21:43.382   873   885 E PackageManager: Failed to write settings, restoring backup
08-30 12:21:43.382   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-30 12:21:43.382   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-30 12:21:43.382   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-30 12:21:43.382   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-30 12:21:43.382   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-30 12:21:43.382   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:21:43.382   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:21:43.382   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 12:21:43.385   873  2035 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3792 uid 10000
,08-30 12:21:43.385  1870  4286 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-30 12:21:43.386   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-30 12:21:43.386   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-30 12:21:43.386   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 12:21:43.386   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 12:21:43.386   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 12:21:43.386   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 12:21:43.386   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 12:21:43.386   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 12:21:43.386   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-30 12:21:43.386   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-30 12:21:43.386   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-30 12:21:43.386   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 12:21:43.386   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 12:21:43.386   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:21:43.386   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 12:21:43.386   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 12:21:43.386   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 12:21:43.386   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 12:21:43.386   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 12:21:43.386   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 12:21:43.386   873   886 E DropBoxManagerService: 	... 13 more
08-30 12:21:43.386  1870  1870 I Keyboard.Facilitator: onFinishInput()
08-30 12:21:43.387  1955  2045 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-30 12:21:43.389  1870  4286 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-30 12:21:43.389  1870  4286 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-30 12:21:43.392  1870  4286 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-30 12:21:43.392  1870  4286 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-30 12:21:43.399  1870  4286 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-30 12:21:43.399  1870  4286 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-30 12:21:43.400  1870  4286 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-30 12:21:43.400  1870  4286 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-30 12:21:43.400  1870  4286 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-30 12:21:43.400  1870  4286 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-30 12:21:43.400  1870  4286 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-30 12:21:43.400  1870  4286 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-30 12:21:43.404   873  1953 I ActivityManager: Start proc 4303:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-30 12:21:43.405  1955  2045 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-30 12:21:43.405  1955  2045 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1955
08-30 12:21:43.405  1955  2045 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 12:21:43.405  1955  2045 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 12:21:43.405  1955  2045 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 12:21:43.405  1955  2045 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 12:21:43.405  1955  2045 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 12:21:43.405  1955  2045 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 12:21:43.405  1955  2045 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-30 12:21:43.405  1955  2045 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-30 12:21:43.405  1955  2045 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 12:21:43.405  1955  2045 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 12:21:43.405  1955  2045 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:21:43.405  1955  2045 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 12:21:43.410   873  4313 E DropBoxManagerService: Can't write: system_app_crash
08-30 12:21:43.410   873  4313 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-30 12:21:43.410   873  4313 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 12:21:43.410   873  4313 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 12:21:43.410   873  4313 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 12:21:43.410   873  4313 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 12:21:43.410   873  4313 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 12:21:43.410   873  4313 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 12:21:43.410   873  4313 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 12:21:43.410   873  4313 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 12:21:43.410   873  4313 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 12:21:43.410   873  4313 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 12:21:43.410   873  4313 E DropBoxManagerService: 	... 5 more
,08-30 12:21:43.412   873  3738 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 12:21:43.420  1955  2045 I Process : Sending signal. PID: 1955 SIG: 9
,08-30 12:21:43.463  4289  4289 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-30 12:21:43.466   873  2035 I WindowState: WIN DEATH: Window{d141e86 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-30 12:21:43.466   873  1995 D GraphicsStats: Buffer count: 1
,08-30 12:21:43.477   873  1995 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1955) has died
08-30 12:21:43.477   873  1995 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-30 12:21:43.478   873  1995 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-30 12:21:43.497  4289  4317 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-30 12:21:43.497  4289  4317 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:21:43.497  4289  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 12:21:43.497  4289  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 12:21:43.497  4289  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 12:21:43.497  4289  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 12:21:43.497  4289  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 12:21:43.497  4289  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 12:21:43.497  4289  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 12:21:43.497  4289  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 12:21:43.497  4289  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 12:21:43.497  4289  4317 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 12:21:43.497  4289  4317 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 12:21:43.497  4289  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 12:21:43.497  4289  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 12:21:43.497  4289  4317 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-30 12:21:43.497  4289  4317 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-30 12:21:43.497  4289  4317 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-30 12:21:43.497  4289  4317 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-30 12:21:43.497  4289  4317 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:21:43.497  4289  4317 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:21:43.497  4289  4317 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 12:21:43.497  4289  4317 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-30 12:21:43.497  4289  4317 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:21:43.497  4289  4317 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 12:21:43.497  4289  4317 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 12:21:43.497  4289  4317 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 12:21:43.497  4289  4317 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 12:21:43.497  4289  4317 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 12:21:43.497  4289  4317 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 12:21:43.497  4289  4317 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 12:21:43.497  4289  4317 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 12:21:43.497  4289  4317 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 12:21:43.497  4289  4317 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 12:21:43.497  4289  4317 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 12:21:43.497  4289  4317 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 12:21:43.497  4289  4317 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 12:21:43.497  4289  4317 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-30 12:21:43.497  4289  4317 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-30 12:21:43.497  4289  4317 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-30 12:21:43.497  4289  4317 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-30 12:21:43.497  4289  4317 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:21:43.497  4289  4317 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:21:43.497  4289  4317 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 12:21:43.506   873   886 I ActivityManager: Start proc 4320:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 12:21:43.524  4289  4332 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-30 12:21:43.525   873  3738 I ActivityManager: Start proc 4333:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-30 12:21:43.556  4333  4333 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-30 12:21:43.568  4320  4320 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-30 12:21:43.568  4320  4320 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:21:43.568  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 12:21:43.568  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 12:21:43.568  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 12:21:43.568  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 12:21:43.568  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 12:21:43.568  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 12:21:43.568  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 12:21:43.568  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 12:21:43.568  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 12:21:43.568  4320  4320 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 12:21:43.568  4320  4320 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 12:21:43.568  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 12:21:43.568  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 12:21:43.568  4320  4320 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 12:21:43.568  4320  4320 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 12:21:43.568  4320  4320 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 12:21:43.568  4320  4320 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 12:21:43.568  4320  4320 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 12:21:43.568  4320  4320 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 12:21:43.568  4320  4320 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 12:21:43.568  4320  4320 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 12:21:43.568  4320  4320 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 12:21:43.568  4320  4320 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:21:43.568  4320  4320 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:21:43.568  4320  4320 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 12:21:43.568  4320  4320 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:21:43.568  4320  4320 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 12:21:43.568  4320  4320 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 12:21:43.569  4320  4320 D AndroidRuntime: Shutting down VM
,08-30 12:21:43.577  4320  4320 E AndroidRuntime: FATAL EXCEPTION: main
08-30 12:21:43.577  4320  4320 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4320
08-30 12:21:43.577  4320  4320 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:21:43.577  4320  4320 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 12:21:43.577  4320  4320 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 12:21:43.577  4320  4320 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 12:21:43.577  4320  4320 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 12:21:43.577  4320  4320 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 12:21:43.577  4320  4320 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:21:43.577  4320  4320 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:21:43.577  4320  4320 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 12:21:43.577  4320  4320 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:21:43.577  4320  4320 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 12:21:43.577  4320  4320 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 12:21:43.577  4320  4320 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:21:43.577  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 12:21:43.577  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 12:21:43.577  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 12:21:43.577  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 12:21:43.577  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 12:21:43.577  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 12:21:43.577  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 12:21:43.577  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 12:21:43.577  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 12:21:43.577  4320  4320 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 12:21:43.577  4320  4320 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 12:21:43.577  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 12:21:43.577  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 12:21:43.577  4320  4320 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 12:21:43.577  4320  4320 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 12:21:43.577  4320  4320 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 12:21:43.577  4320  4320 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-30 12:21:43.577  4320  4320 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 12:21:43.577  4320  4320 E AndroidRuntime: 	... 10 more
,08-30 12:21:43.578   873  1953 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 12:21:43.580  4320  4320 I Process : Sending signal. PID: 4320 SIG: 9
,08-30 12:21:43.580   873  4348 E DropBoxManagerService: Can't write: system_app_crash
08-30 12:21:43.580   873  4348 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-30 12:21:43.580   873  4348 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 12:21:43.580   873  4348 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 12:21:43.580   873  4348 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 12:21:43.580   873  4348 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 12:21:43.580   873  4348 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 12:21:43.580   873  4348 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 12:21:43.580   873  4348 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 12:21:43.580   873  4348 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 12:21:43.580   873  4348 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 12:21:43.580   873  4348 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 12:21:43.580   873  4348 E DropBoxManagerService: 	... 5 more
,08-30 12:21:43.601  1727  4346 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-30 12:21:43.603  1727  4346 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-30 12:21:43.607  1727  4346 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-30 12:21:43.608  1727  4346 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-30 12:21:43.613  1509  1509 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-30 12:21:43.614  1509  1509 D AndroidRuntime: Shutting down VM
,08-30 12:21:43.615  1509  1509 E AndroidRuntime: FATAL EXCEPTION: main
08-30 12:21:43.615  1509  1509 E AndroidRuntime: Process: com.google.process.gapps, PID: 1509
08-30 12:21:43.615  1509  1509 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 12:21:43.615  1509  1509 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-30 12:21:43.615  1509  1509 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-30 12:21:43.615  1509  1509 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-30 12:21:43.615  1509  1509 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:21:43.615  1509  1509 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:21:43.615  1509  1509 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 12:21:43.615  1509  1509 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:21:43.615  1509  1509 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 12:21:43.615  1509  1509 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 12:21:43.615  1509  1509 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 12:21:43.615  1509  1509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 12:21:43.615  1509  1509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 12:21:43.615  1509  1509 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 12:21:43.615  1509  1509 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 12:21:43.615  1509  1509 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 12:21:43.615  1509  1509 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-30 12:21:43.615  1509  1509 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-30 12:21:43.615  1509  1509 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-30 12:21:43.615  1509  1509 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-30 12:21:43.615  1509  1509 E AndroidRuntime: 	... 8 more
,08-30 12:21:43.616   873  1953 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4320) has died
08-30 12:21:43.617   873  1953 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-30 12:21:43.631   873   886 I ActivityManager: Start proc 4351:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 12:21:43.636   873  1395 I ActivityManager: Killing 3689:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-30 12:21:43.636   873  4359 E DropBoxManagerService: Can't write: system_app_crash
08-30 12:21:43.636   873  4359 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-30 12:21:43.636   873  4359 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 12:21:43.636   873  4359 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 12:21:43.636   873  4359 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 12:21:43.636   873  4359 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 12:21:43.636   873  4359 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 12:21:43.636   873  4359 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 12:21:43.636   873  4359 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 12:21:43.636   873  4359 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 12:21:43.636   873  4359 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 12:21:43.636   873  4359 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 12:21:43.636   873  4359 E DropBoxManagerService: 	... 5 more
,08-30 12:21:43.637  1509  1509 I Process : Sending signal. PID: 1509 SIG: 9
,08-30 12:21:43.655  4289  4317 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-30 12:21:43.669  4289  4332 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-30 12:21:43.669  4289  4332 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:21:43.669  4289  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 12:21:43.669  4289  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 12:21:43.669  4289  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 12:21:43.669  4289  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 12:21:43.669  4289  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 12:21:43.669  4289  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 12:21:43.669  4289  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 12:21:43.669  4289  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 12:21:43.669  4289  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 12:21:43.669  4289  4332 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 12:21:43.669  4289  4332 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 12:21:43.669  4289  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 12:21:43.669  4289  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 12:21:43.669  4289  4332 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-30 12:21:43.669  4289  4332 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-30 12:21:43.669  4289  4332 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-30 12:21:43.669  4289  4332 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-30 12:21:43.669  4289  4332 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-30 12:21:43.669  4289  4332 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-30 12:21:43.669  4289  4332 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 12:21:43.669  4289  4332 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:21:43.669  4289  4332 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:21:43.669  4289  4332 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 12:21:43.669  4289  4332 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-30 12:21:43.669  4289  4332 E AndroidRuntime: Process: android.process.acore, PID: 4289
08-30 12:21:43.669  4289  4332 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:21:43.669  4289  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 12:21:43.669  4289  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 12:21:43.669  4289  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
,08-30 12:21:43.669  4289  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 12:21:43.669  4289  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 12:21:43.669  4289  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 12:21:43.669  4289  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 12:21:43.669  4289  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 12:21:43.669  4289  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 12:21:43.669  4289  4332 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 12:21:43.669  4289  4332 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 12:21:43.669  4289  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 12:21:43.669  4289  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 12:21:43.669  4289  4332 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-30 12:21:43.669  4289  4332 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-30 12:21:43.669  4289  4332 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-30 12:21:43.669  4289  4332 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-30 12:21:43.669  4289  4332 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-30 12:21:43.669  4289  4332 E AndroidRuntime: 	,at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-30 12:21:43.669  4289  4332 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 12:21:43.669  4289  4332 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:21:43.669  4289  4332 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:21:43.669  4289  4332 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 12:21:43.670  4289  4317 I Process : Sending signal. PID: 4289 SIG: 9
,08-30 12:21:43.680   873  1307 D WifiService: Client connection lost with reason: 4
,08-30 12:21:43.683   283   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
