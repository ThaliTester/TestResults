#### Test 81418577e915171_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-16 13:18:29.739  1549  1549 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 13:18:29.752  1549  1549 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-16 13:18:29.759  1549  1549 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-16 13:18:29.831  1549  2352 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-16 13:18:29.831  1549  2352 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-16 13:18:29.832  1549  2352 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 13:18:29.832  1549  2352 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-16 13:18:29.858  3493  3493 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-16 13:18:29.858  3493  3493 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-16 13:18:29.859  3493  3493 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
08-16 13:18:30.412  3774  3774 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-16 13:18:30.420  3774  3774 D AndroidRuntime: CheckJNI is OFF
08-16 13:18:30.466  3774  3774 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-16 13:18:30.508  3774  3774 I Radio-JNI: register_android_hardware_Radio DONE
08-16 13:18:30.529  3774  3774 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-16 13:18:30.534   875  1934 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-16 13:18:30.573  2001  2016 W SearchService: Abort, client detached.
08-16 13:18:30.574  3774  3774 D AndroidRuntime: Shutting down VM
08-16 13:18:30.579  2001  2335 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@8374e39
08-16 13:18:30.579  2001  2001 I HotwordDetector: Closing mic
08-16 13:18:30.580  2001  2346 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-16 13:18:30.608   875   885 I ActivityManager: Start proc 3784:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-16 13:18:30.639   376  2348 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-16 13:18:30.641   376  2348 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-16 13:18:30.653   376  1276 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-16 13:18:30.656  2001  2343 I MicroRecognitionRnrImpl: Detection finished
08-16 13:18:30.657  2001  2341 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-16 13:18:30.704  3784  3784 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-16 13:18:30.742  3784  3784 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-16 13:18:30.764  3784  3784 I LibraryLoader: Time to load native libraries: 8 ms (timestamps 9102-9110)
08-16 13:18:30.764  3784  3784 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 13:18:30.790  3784  3784 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1c70cf7}
08-16 13:18:30.791  3784  3784 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 13:18:30.791  3784  3784 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 13:18:30.800  3784  3784 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-16 13:18:30.802  3784  3784 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-16 13:18:30.828  3784  3784 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-16 13:18:30.843  3784  3784 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-16 13:18:30.843  3784  3784 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 13:18:30.843  3784  3784 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 13:18:30.843  3784  3784 I Adreno  : Build Date                       : 10/20/15
08-16 13:18:30.843  3784  3784 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 13:18:30.843  3784  3784 I Adreno  : Local Branch                     : M14
08-16 13:18:30.843  3784  3784 I Adreno  : Remote Branch                    : 
08-16 13:18:30.843  3784  3784 I Adreno  : Remote Branch                    : 
08-16 13:18:30.843  3784  3784 I Adreno  : Reconstruct Branch               : 
,08-16 13:18:30.931   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@51741ed:true
,08-16 13:18:30.984  3784  3784 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-16 13:18:31.000  3784  3784 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-16 13:18:31.052  3784  3824 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-16 13:18:31.077  3784  3810 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-16 13:18:31.115  3784  3824 I OpenGLRenderer: Initialized EGL, version 1.4
,08-16 13:18:31.202   875   893 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +616ms
,08-16 13:18:31.210  1856  1856 I Keyboard.Facilitator: onFinishInput()
,08-16 13:18:31.289  3784  3784 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3784
,08-16 13:18:31.440   875   885 I ActivityManager: Killing 2963:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-16 13:18:31.442  3784  3784 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-16 13:18:31.524   875   885 I ActivityManager: Killing 3182:com.google.android.gm/u0a78 (adj 15): empty #18
,08-16 13:18:31.646  3784  3826 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1677985488
,08-16 13:18:31.657  3784  3826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-16 13:18:31.657  3784  3826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-16 13:18:31.657  3784  3826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-16 13:18:31.657  3784  3826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-16 13:18:31.657  3784  3826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-16 13:18:31.657  3784  3826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b24aa9a added. We now have 1 listener(s)
,08-16 13:18:31.663  3784  3826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-16 13:18:31.664  3784  3826 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 13:18:31.665  3784  3826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 13:18:31.666  3784  3826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 13:18:31.672  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-16 13:18:31.672  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-16 13:18:31.672  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-16 13:18:31.672  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-16 13:18:31.672  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-16 13:18:31.672  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-16 13:18:31.672  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-16 13:18:31.672  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-16 13:18:31.672  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-16 13:18:31.672  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-16 13:18:31.672  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-16 13:18:31.672  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-16 13:18:31.672  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-16 13:18:31.672  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-16 13:18:31.672  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26bdec1 added. We now have 1 listener(s)
,08-16 13:18:31.673  3784  3826 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 13:18:31.677   875  1307 D WifiService: New client listening to asynchronous messages
,08-16 13:18:31.680  3784  3826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 13:18:31.680  3784  3826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-16 13:18:31.680  3784  3826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-16 13:18:31.680  3784  3826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3,
,08-16 13:18:31.681  3784  3826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-16 13:18:31.692  3784  3826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 13:18:31.693  3784  3826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-16 13:18:31.706  3784  3826 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-16 13:18:31.707  3784  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:18:31.707  3784  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:18:31.707  3784  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:18:31.707  3784  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:18:31.707  3784  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:18:31.707  3784  3826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:18:31.707  3784  3826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:18:31.707  3784  3826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:18:31.707  3784  3826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-16 13:18:31.707  3784  3826 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 13:18:31.711  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:18:31.711  3784  3826 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-16 13:18:31.714  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:18:31.905  3784  3784 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-16 13:18:32.785  3784  3835 W jxcore-log: Initializing JXcore engine
,08-16 13:18:32.785  3784  3835 W jxcore-log: JXcore engine is ready
,08-16 13:18:32.851  3835  3835 W Thread-329: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8957 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-16 13:18:32.851  3835  3835 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9963]" dev="sockfs" ino=9963 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-16 13:18:32.851  3835  3835 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-16 13:18:32.851  3835  3835 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25164]" dev="sockfs" ino=25164 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-16 13:18:32.868  3784  3835 W jxcore-log: Starting JXcore engine
,08-16 13:18:32.995  3784  3835 W jxcore-log: Platform android
08-16 13:18:32.995  3784  3835 W jxcore-log: 
,08-16 13:18:32.996  3784  3835 W jxcore-log: Process ARCH arm
08-16 13:18:32.996  3784  3835 W jxcore-log: 
,08-16 13:18:33.160  3784  3835 I jxcore-log: JXcore Cordova bridge is ready!
08-16 13:18:33.160  3784  3835 I jxcore-log: 
,08-16 13:18:33.160  3784  3835 W jxcore-log: JXcore engine is started
,08-16 13:18:33.167  3784  3826 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-16 13:18:33.173  3784  3784 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-16 13:18:33.610   875  1306 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-16 13:18:35.011   875  1872 D NetlinkSocketObserver: NeighborEvent{elapsedMs=123357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 13:18:36.758  1549  1549 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 13:18:36.759  1549  1549 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 13:18:36.775  1549  2351 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 13:18:36.775  1549  2351 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 13:18:36.775  1549  2351 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 13:18:36.775  1549  2351 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 13:18:36.790  3532  3842 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-16 13:18:36.790  3532  3842 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 13:18:36.790  3532  3842 E HttpOperation: 	at jdm.a(PG:82)
08-16 13:18:36.790  3532  3842 E HttpOperation: 	at jcs.o(PG:406)
08-16 13:18:36.790  3532  3842 E HttpOperation: 	at jcn.a(PG:1379)
08-16 13:18:36.790  3532  3842 E HttpOperation: 	at jcs.i(PG:143)
08-16 13:18:36.790  3532  3842 E HttpOperation: 	at blb.a(PG:3937)
08-16 13:18:36.790  3532  3842 E HttpOperation: 	at czp.a(PG:18188)
08-16 13:18:36.790  3532  3842 E HttpOperation: 	at czp.a(PG:9081)
08-16 13:18:36.790  3532  3842 E HttpOperation: 	at czq.run(PG:1686)
08-16 13:18:36.790  3532  3842 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 13:18:36.790  3532  3842 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 13:18:36.790  3532  3842 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 13:18:36.790  3532  3842 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 13:18:36.790  3532  3842 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 13:18:36.790  3532  3842 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 13:18:36.790  3532  3842 E HttpOperation: 	at jdj.a(PG:4091)
08-16 13:18:36.790  3532  3842 E HttpOperation: 	at jdj.a(PG:1125)
08-16 13:18:36.790  3532  3842 E HttpOperation: 	at jdm.a(PG:77)
08-16 13:18:36.790  3532  3842 E HttpOperation: 	... 12 more
08-16 13:18:36.790  3532  3842 E HttpOperation: Caused by: faj: BadAuthentication
08-16 13:18:36.790  3532  3842 E HttpOperation: 	at fal.a(PG:38)
08-16 13:18:36.790  3532  3842 E HttpOperation: 	at jdj.a(PG:4089)
08-16 13:18:36.790  3532  3842 E HttpOperation: 	... 14 more
,08-16 13:18:36.826  1549  3181 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 13:18:36.826  1549  3181 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 13:18:36.827  1549  3181 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 13:18:36.827  1549  3181 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 13:18:36.841  3532  3842 E HttpOperation: [getmobileexperiments] Unexpected exception
08-16 13:18:36.841  3532  3842 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 13:18:36.841  3532  3842 E HttpOperation: 	at jdm.a(PG:82)
08-16 13:18:36.841  3532  3842 E HttpOperation: 	at jcs.o(PG:406)
08-16 13:18:36.841  3532  3842 E HttpOperation: 	at jcn.a(PG:1379)
08-16 13:18:36.841  3532  3842 E HttpOperation: 	at jcs.i(PG:143)
08-16 13:18:36.841  3532  3842 E HttpOperation: 	at hec.a(PG:42)
08-16 13:18:36.841  3532  3842 E HttpOperation: 	at hee.a(PG:102)
08-16 13:18:36.841  3532  3842 E HttpOperation: 	at czr.a(PG:65)
08-16 13:18:36.841  3532  3842 E HttpOperation: 	at kka.a(PG:108)
08-16 13:18:36.841  3532  3842 E HttpOperation: 	at czp.a(PG:19176)
08-16 13:18:36.841  3532  3842 E HttpOperation: 	at czp.a(PG:9081)
08-16 13:18:36.841  3532  3842 E HttpOperation: 	at czq.run(PG:1686)
08-16 13:18:36.841  3532  3842 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 13:18:36.841  3532  3842 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 13:18:36.841  3532  3842 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 13:18:36.841  3532  3842 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 13:18:36.841  3532  3842 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 13:18:36.841  3532  3842 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 13:18:36.841  3532  3842 E HttpOperation: 	at jdj.a(PG:4091)
08-16 13:18:36.841  3532  3842 E HttpOperation: 	at jdj.a(PG:1125)
08-16 13:18:36.841  3532  3842 E HttpOperation: 	at jdm.a(PG:77)
08-16 13:18:36.841  3532  3842 E HttpOperation: 	... 15 more
08-16 13:18:36.841  3532  3842 E HttpOperation: Caused by: faj: BadAuthentication
08-16 13:18:36.841  3532  3842 E HttpOperation: 	at fal.a(PG:38)
08-16 13:18:36.841  3532  3842 E HttpOperation: 	at jdj.a(PG:4089)
08-16 13:18:36.841  3532  3842 E HttpOperation: 	... 17 more
,08-16 13:18:36.842  3532  3842 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-16 13:18:36.842  3532  3842 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-16 13:18:36.842  3532  3842 E ExperimentLoader: 	at jdm.a(PG:82)
08-16 13:18:36.842  3532  3842 E ExperimentLoader: 	at jcs.o(PG:406)
08-16 13:18:36.842  3532  3842 E ExperimentLoader: 	at jcn.a(PG:1379)
08-16 13:18:36.842  3532  3842 E ExperimentLoader: 	at jcs.i(PG:143)
08-16 13:18:36.842  3532  3842 E ExperimentLoader: 	at hec.a(PG:42)
08-16 13:18:36.842  3532  3842 E ExperimentLoader: 	at hee.a(PG:102)
08-16 13:18:36.842  3532  3842 E ExperimentLoader: 	at czr.a(PG:65)
08-16 13:18:36.842  3532  3842 E ExperimentLoader: 	at kka.a(PG:108)
08-16 13:18:36.842  3532  3842 E ExperimentLoader: 	at czp.a(PG:19176)
08-16 13:18:36.842  3532  3842 E ExperimentLoader: 	at czp.a(PG:9081)
08-16 13:18:36.842  3532  3842 E ExperimentLoader: 	at czq.run(PG:1686)
08-16 13:18:36.842  3532  3842 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 13:18:36.842  3532  3842 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 13:18:36.842  3532  3842 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 13:18:36.842  3532  3842 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 13:18:36.842  3532  3842 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-16 13:18:36.842  3532  3842 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 13:18:36.842  3532  3842 E ExperimentLoader: 	at jdj.a(PG:4091)
08-16 13:18:36.842  3532  3842 E ExperimentLoader: 	at jdj.a(PG:1125)
08-16 13:18:36.842  3532  3842 E ExperimentLoader: 	at jdm.a(PG:77)
08-16 13:18:36.842  3532  3842 E ExperimentLoader: 	... 15 more
08-16 13:18:36.842  3532  3842 E ExperimentLoader: Caused by: faj: BadAuthentication
08-16 13:18:36.842  3532  3842 E ExperimentLoader: 	at fal.a(PG:38)
08-16 13:18:36.842  3532  3842 E ExperimentLoader: 	at jdj.a(PG:4089)
08-16 13:18:36.842  3532  3842 E ExperimentLoader: 	... 17 more
,08-16 13:18:36.939   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 124959, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-16 13:18:43.375  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-16 13:18:43.375  3784  3835 I jxcore-log: 
,08-16 13:18:43.378  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-16 13:18:43.378  3784  3835 I jxcore-log: 
,08-16 13:18:43.388  3784  3835 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:18:43.388  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:18:43.388  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:18:43.388  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:18:43.388  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:18:43.388  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:18:43.388  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:18:43.388  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 13:18:43.392  3784  3835 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 13:18:43.394  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-16 13:18:43.394  3784  3835 I jxcore-log: 
,08-16 13:18:43.396  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-16 13:18:43.396  3784  3835 I jxcore-log: 
,08-16 13:18:43.728  3784  3835 D ExecuteNativeTests: Running unit tests
,08-16 13:18:43.787  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 13:18:43.787  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4098519 added. We now have 2 listener(s)
08-16 13:18:43.788  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 13:18:43.788  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 13:18:43.788  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 13:18:43.788  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:18:43.788  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de added. We now have 2 listener(s)
08-16 13:18:43.788  3784  3835 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 13:18:43.789  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 13:18:43.792  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 13:18:43.809  3784  3835 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:18:43.809  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:18:43.809  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:18:43.809  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:18:43.809  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:18:43.809  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:18:43.809  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:18:43.809  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 13:18:43.815  3784  3835 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 13:18:43.815  3784  3835 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 13:18:43.818  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 13:18:43.818  3784  3835 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 13:18:43.823  3784  3835 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 13:18:43.826  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:18:43.827  3784  3835 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-16 13:18:43.828  3784  3835 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 13:18:43.828  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 13:18:43.829  3784  3835 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-16 13:18:43.829  3784  3835 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-16 13:18:43.832  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:18:43.836  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 13:18:43.837  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:18:43.837  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:18:43.838  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:18:43.838  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:18:43.839  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:18:43.839  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 13:18:43.839  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4098519 removed from the list
08-16 13:18:43.839  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:18:43.840  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de removed from the list
08-16 13:18:43.840  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:18:43.840  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 13:18:43.842  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:43.842  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 13:18:43.844  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 13:18:43.844  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 13:18:43.844  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:18:43.845  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
,08-16 13:18:43.851  3784  3835 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-16 13:18:43.853  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 13:18:43.853  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:18:43.853  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:18:43.854  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:18:43.854  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:18:43.854  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:43.855  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4098519 not in the list
08-16 13:18:43.855  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:18:43.855  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
08-16 13:18:43.855  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 13:18:43.855  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:43.856  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:43.856  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:43.856  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 13:18:43.859  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:18:43.859  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 13:18:43.859  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:18:43.860  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
,08-16 13:18:43.880  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-16 13:18:43.880  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 13:18:43.880  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 13:18:43.881  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 13:18:43.881  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 13:18:43.881  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 13:18:43.881  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 13:18:43.882  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 13:18:43.882  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 13:18:43.882  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 13:18:43.882  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 13:18:43.883  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 13:18:43.883  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-16 13:18:43.883  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 13:18:43.883  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 13:18:43.884  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 13:18:43.884  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 13:18:43.884  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 13:18:43.884  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 13:18:43.885  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 13:18:43.885  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-16 13:18:43.885  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 13:18:43.885  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 13:18:43.886  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 13:18:43.886  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 13:18:43.886  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 13:18:43.886  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 13:18:43.887  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 13:18:43.887  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-16 13:18:43.887  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 13:18:43.888  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 13:18:43.888  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:18:43.888  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:18:43.888  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:18:43.889  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:18:43.889  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:43.889  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:43.889  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4098519 not in the list
08-16 13:18:43.890  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:18:43.890  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
08-16 13:18:43.890  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:18:43.891  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:43.891  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:43.891  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:43.891  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:43.892  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:18:43.892  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:18:43.892  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:18:43.892  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
08-16 13:18:43.893  3784  3835 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 13:18:43.894  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:18:43.907  3784  3835 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:18:43.907  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:18:43.907  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:18:43.907  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:18:43.907  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:18:43.907  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:18:43.907  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:18:43.907  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:18:43.910  3784  3835 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 13:18:43.910  3784  3835 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 13:18:43.910  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 13:18:43.910  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 13:18:43.910  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 13:18:43.911  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:18:43.911  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 13:18:43.918  3784  3835 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 13:18:43.918  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 13:18:43.918  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:18:43.921  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:18:43.926  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 13:18:43.931  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 13:18:43.934  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 13:18:43.941  3784  3835 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-16 13:18:43.946  3784  3835 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-16 13:18:43.946  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 13:18:43.947  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 13:18:43.948  3784  3835 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 13:18:43.950  3784  3835 D BluetoothAdapter: STATE_ON
,08-16 13:18:43.965  2691  2875 D BtGatt.GattService: registerClient() - UUID=1ff411d0-52de-47ac-90b2-4a0a1a5bc18f
,08-16 13:18:43.967  2691  2743 D BtGatt.GattService: onClientRegistered() - UUID=1ff411d0-52de-47ac-90b2-4a0a1a5bc18f, clientIf=5
,08-16 13:18:43.968  3784  3795 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 13:18:43.971  2691  2705 D BtGatt.GattService: start scan with filters
,08-16 13:18:43.978  2691  2759 D BtGatt.ScanManager: handling starting scan
08-16 13:18:43.978  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 13:18:43.979  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 13:18:43.979  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-16 13:18:43.980  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 13:18:43.981  2691  2759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b66a9c9
08-16 13:18:43.984  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 13:18:43.984  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 13:18:43.985  3784  3784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 13:18:43.986  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 13:18:43.994  2691  2743 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 13:18:43.994  2691  2743 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:18:43.996  2691  2759 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 13:18:43.997  3784  3835 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 13:18:44.005  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:18:44.005  3784  3835 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 13:18:44.005  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 13:18:44.006  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 13:18:44.006  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:18:44.006  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 13:18:44.006  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 13:18:44.006  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 13:18:44.006  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 13:18:44.007  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 13:18:44.008  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-16 13:18:44.008  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 13:18:44.009  3784  3835 D BluetoothAdapter: STATE_ON
08-16 13:18:44.011  2691  2875 D BtGatt.GattService: stopScan() - queue size =1
08-16 13:18:44.011  2691  2743 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 13:18:44.012  2691  2743 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 13:18:44.013  2691  2759 D BtGatt.ScanManager: Starting BLE batch scan
08-16 13:18:44.013  2691  2759 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-16 13:18:44.013  2691  2705 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 13:18:44.018  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:18:44.018  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 13:18:44.018  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 13:18:44.019  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 13:18:44.019  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 13:18:44.021  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 13:18:44.021  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 13:18:44.022  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-16 13:18:44.022  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 13:18:44.024  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:18:44.026  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:18:44.026  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:18:44.026  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:18:44.027  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4098519 not in the list
,08-16 13:18:44.027  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:18:44.026  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 13:18:44.027  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
08-16 13:18:44.027  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:18:44.027  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.028  3784  3835 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 13:18:44.027  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 13:18:44.029  3784  3784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 13:18:44.031  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 13:18:44.039  3784  3835 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:18:44.039  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:18:44.039  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:18:44.039  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:18:44.039  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:18:44.039  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:18:44.039  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:18:44.039  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 13:18:44.041  2691  2743 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 13:18:44.042  2691  2743 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 13:18:44.043  3784  3835 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 13:18:44.043  3784  3835 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 13:18:44.044  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 13:18:44.044  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 13:18:44.045  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-16 13:18:44.045  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:18:44.045  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 13:18:44.046  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:18:44.049  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:18:44.052  2691  2743 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 13:18:44.052  2691  2743 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:18:44.053  3784  3835 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 13:18:44.053  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 13:18:44.059  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 13:18:44.061  2691  2743 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 13:18:44.062  2691  2743 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:18:44.062  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 13:18:44.062  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 13:18:44.062  2691  2759 D BtGatt.ScanManager: stopping BLe Batch
,08-16 13:18:44.068  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 13:18:44.068  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 13:18:44.068  3784  3835 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 13:18:44.069  2691  2743 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-16 13:18:44.069  2691  2743 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:18:44.069  3784  3835 D BluetoothAdapter: STATE_ON
08-16 13:18:44.069  2691  2759 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 13:18:44.073  2691  2706 D BtGatt.GattService: registerClient() - UUID=9fde8dd2-bc1f-408f-b6c8-ce4638e83103
,08-16 13:18:44.074  2691  2743 D BtGatt.GattService: onClientRegistered() - UUID=9fde8dd2-bc1f-408f-b6c8-ce4638e83103, clientIf=5
,08-16 13:18:44.074  3784  3795 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 13:18:44.075  2691  2875 D BtGatt.GattService: start scan with filters
,08-16 13:18:44.079  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 13:18:44.079  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 13:18:44.079  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-16 13:18:44.079  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 13:18:44.082  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 13:18:44.082  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 13:18:44.083  3784  3784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 13:18:44.084  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-16 13:18:44.085  2691  2743 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,08-16 13:18:44.085  2691  2743 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:18:44.085  2691  2743 D BtGatt.GattService: current time is 132431568982,
08-16 13:18:44.085  2691  2743 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -84, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-16 13:18:44.087  3784  3835 I io.jxcore.node.ConnectionHelper: start: OK
08-16 13:18:44.087  2691  2743 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-16 13:18:44.088  2691  2759 D BtGatt.ScanManager: handling starting scan
,08-16 13:18:44.090  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 13:18:44.090  3784  3835 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 13:18:44.090  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 13:18:44.090  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 13:18:44.090  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:18:44.090  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 13:18:44.091  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 13:18:44.091  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 13:18:44.091  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 13:18:44.091  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 13:18:44.091  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 13:18:44.091  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 13:18:44.092  3784  3835 D BluetoothAdapter: STATE_ON
08-16 13:18:44.093  2691  2706 D BtGatt.GattService: stopScan() - queue size =1
08-16 13:18:44.094  2691  2875 D BtGatt.GattService: unregisterClient() - clientIf=5
08-16 13:18:44.094  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:18:44.094  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-16 13:18:44.094  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 13:18:44.094  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 13:18:44.094  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 13:18:44.097  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 13:18:44.097  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 13:18:44.097  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 13:18:44.097  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 13:18:44.097  2691  2743 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 13:18:44.097  2691  2743 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:18:44.098  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:18:44.098  2691  2759 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-16 13:18:44.099  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 13:18:44.099  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:18:44.099  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:18:44.099  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 13:18:44.099  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4098519 not in the list
,08-16 13:18:44.099  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:18:44.099  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
08-16 13:18:44.099  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:18:44.099  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 13:18:44.099  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.099  3784  3784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 13:18:44.100  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.100  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.102  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:18:44.102  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:18:44.102  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:18:44.102  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
,08-16 13:18:44.103  3784  3835 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 13:18:44.104  2691  2743 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 13:18:44.105  2691  2743 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:18:44.105  2691  2759 D BtGatt.ScanManager: Starting BLE batch scan
08-16 13:18:44.105  2691  2759 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-16 13:18:44.106  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 13:18:44.114  3784  3835 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:18:44.114  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:18:44.114  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:18:44.114  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:18:44.114  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:18:44.114  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:18:44.114  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:18:44.114  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 13:18:44.117  3784  3835 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 13:18:44.118  3784  3835 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 13:18:44.119  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
,08-16 13:18:44.120  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 13:18:44.120  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-16 13:18:44.120  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:18:44.120  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 13:18:44.120  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:18:44.121  2691  2743 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 13:18:44.121  2691  2743 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:18:44.123  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:18:44.126  3784  3835 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 13:18:44.127  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 13:18:44.131  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 13:18:44.132  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 13:18:44.132  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 13:18:44.133  2691  2743 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 13:18:44.133  2691  2743 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,08-16 13:18:44.136  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 13:18:44.136  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 13:18:44.136  3784  3835 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 13:18:44.137  3784  3835 D BluetoothAdapter: STATE_ON
,08-16 13:18:44.140  2691  2705 D BtGatt.GattService: registerClient() - UUID=e03c6dab-d5d7-4f6e-81a7-ece7adaecd8f
,08-16 13:18:44.141  2691  2743 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 13:18:44.141  2691  2743 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 13:18:44.141  2691  2759 D BtGatt.ScanManager: stopping BLe Batch
08-16 13:18:44.141  2691  2743 D BtGatt.GattService: onClientRegistered() - UUID=e03c6dab-d5d7-4f6e-81a7-ece7adaecd8f, clientIf=5
08-16 13:18:44.141  3784  3796 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 13:18:44.142  2691  2706 D BtGatt.GattService: start scan with filters
,08-16 13:18:44.145  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 13:18:44.145  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-16 13:18:44.145  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-16 13:18:44.146  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-16 13:18:44.147  2691  2743 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 13:18:44.147  2691  2743 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:18:44.148  2691  2759 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 13:18:44.149  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 13:18:44.149  3784  3784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 13:18:44.149  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 13:18:44.151  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 13:18:44.153  2691  2743 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 13:18:44.153  2691  2743 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:18:44.154  3784  3835 I io.jxcore.node.ConnectionHelper: start: OK
08-16 13:18:44.154  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 13:18:44.154  3784  3835 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 13:18:44.154  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 13:18:44.154  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 13:18:44.154  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.154  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 13:18:44.155  2691  2759 D BtGatt.ScanManager: handling starting scan
08-16 13:18:44.155  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 13:18:44.155  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 13:18:44.155  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 13:18:44.155  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 13:18:44.155  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 13:18:44.155  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 13:18:44.156  3784  3835 D BluetoothAdapter: STATE_ON
,08-16 13:18:44.156  2691  2706 D BtGatt.GattService: stopScan() - queue size =1
08-16 13:18:44.157  2691  2875 D BtGatt.GattService: unregisterClient() - clientIf=5
08-16 13:18:44.157  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:18:44.157  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-16 13:18:44.157  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 13:18:44.157  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 13:18:44.158  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 13:18:44.158  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 13:18:44.159  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 13:18:44.159  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 13:18:44.159  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 13:18:44.159  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:18:44.161  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 13:18:44.161  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 13:18:44.161  3784  3784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 13:18:44.161  2691  2743 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 13:18:44.161  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:18:44.161  2691  2743 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:18:44.161  3784  3835 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 13:18:44.161  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:18:44.161  2691  2759 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-16 13:18:44.161  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 13:18:44.162  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:18:44.162  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.162  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:18:44.162  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4098519 not in the list
08-16 13:18:44.162  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:18:44.162  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
,08-16 13:18:44.162  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:18:44.162  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.163  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.163  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.164  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:18:44.164  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:18:44.164  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:18:44.164  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
,08-16 13:18:44.165  3784  3835 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-16 13:18:44.166  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:18:44.166  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:18:44.166  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:18:44.166  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 13:18:44.166  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.166  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.166  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4098519 not in the list
08-16 13:18:44.166  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:18:44.166  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
08-16 13:18:44.167  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:18:44.167  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.167  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.167  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.167  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.167  2691  2743 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 13:18:44.167  2691  2743 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:18:44.167  2691  2759 D BtGatt.ScanManager: Starting BLE batch scan
08-16 13:18:44.167  2691  2759 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-16 13:18:44.168  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:18:44.168  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:18:44.168  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:18:44.168  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
08-16 13:18:44.169  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-16 13:18:44.169  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:18:44.169  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:18:44.169  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:18:44.170  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:18:44.170  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.170  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.170  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4098519 not in the list
,08-16 13:18:44.170  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:18:44.170  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
08-16 13:18:44.170  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:18:44.170  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.170  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.170  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.170  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 13:18:44.172  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:18:44.172  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:18:44.172  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:18:44.172  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
08-16 13:18:44.172  3784  3835 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-16 13:18:44.173  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:18:44.173  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:18:44.173  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:18:44.173  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:18:44.173  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.173  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.173  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4098519 not in the list
08-16 13:18:44.173  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:18:44.174  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
08-16 13:18:44.174  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:18:44.174  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.174  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.174  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.174  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.175  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 13:18:44.175  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:18:44.175  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:18:44.175  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
08-16 13:18:44.176  3784  3835 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-16 13:18:44.176  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:18:44.176  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 13:18:44.176  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:18:44.176  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:18:44.176  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.176  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.176  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4098519 not in the list
08-16 13:18:44.176  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:18:44.177  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
08-16 13:18:44.177  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:18:44.177  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.177  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.178  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:18:44.178  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 13:18:44.178  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:18:44.178  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:18:44.178  2691  2743 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 13:18:44.178  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:18:44.178  2691  2743 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:18:44.178  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
08-16 13:18:44.179  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 13:18:44.179  3784  3835 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 13:18:44.179  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 13:18:44.179  3784  3835 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 13:18:44.179  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 13:18:44.179  3784  3835 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 13:18:44.179  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:18:44.180  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:18:44.180  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:18:44.180  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:18:44.180  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:18:44.180  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.180  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4098519 not in the list
08-16 13:18:44.180  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:18:44.180  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
08-16 13:18:44.180  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:18:44.180  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.180  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.180  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.180  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.181  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:18:44.181  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 13:18:44.181  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:18:44.181  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
08-16 13:18:44.182  3784  3835 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 13:18:44.182  3784  3835 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 13:18:44.182  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 13:18:44.184  2691  2743 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 13:18:44.184  2691  2743 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:18:44.184  3784  3835 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 13:18:44.185  3784  3835 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,08-16 13:18:44.185  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 13:18:44.185  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 13:18:44.185  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 13:18:44.185  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 13:18:44.185  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 13:18:44.185  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 13:18:44.185  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 13:18:44.185  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 13:18:44.185  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-16 13:18:44.185  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 13:18:44.185  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 13:18:44.185  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-16 13:18:44.185  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 13:18:44.185  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 13:18:44.185  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 13:18:44.185  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 13:18:44.185  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 13:18:44.186  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 13:18:44.186  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 13:18:44.186  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-16 13:18:44.186  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 13:18:44.186  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 13:18:44.186  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 13:18:44.186  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 13:18:44.186  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 13:18:44.186  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-16 13:18:44.186  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 13:18:44.186  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 13:18:44.186  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 13:18:44.186  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 13:18:44.186  3784  3835 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-16 13:18:44.187  3784  3835 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-16 13:18:44.187  3784  3835 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,08-16 13:18:44.187  3784  3835 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 13:18:44.187  3784  3835 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 13:18:44.187  3784  3835 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-16 13:18:44.187  3784  3835 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 13:18:44.187  3784  3835 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 13:18:44.187  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-16 13:18:44.190  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-16 13:18:44.191  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-16 13:18:44.191  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-16 13:18:44.191  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-16 13:18:44.191  2691  2743 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 13:18:44.191  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-16 13:18:44.191  2691  2743 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:18:44.191  3784  3835 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-16 13:18:44.192  2691  2759 D BtGatt.ScanManager: stopping BLe Batch
08-16 13:18:44.192  3784  3835 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 13:18:44.192  3784  3835 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-16 13:18:44.192  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 13:18:44.193  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:18:44.193  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:18:44.193  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:18:44.193  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.193  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.193  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-16 13:18:44.194  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4098519 not in the list
08-16 13:18:44.194  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:18:44.194  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
,08-16 13:18:44.194  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:18:44.194  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.194  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.194  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.194  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.195  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:18:44.195  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:18:44.195  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:18:44.195  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
08-16 13:18:44.195  3784  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 393
08-16 13:18:44.196  3784  3835 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-16 13:18:44.196  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:18:44.196  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:18:44.196  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:18:44.197  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:18:44.197  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.197  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 13:18:44.197  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4098519 not in the list
08-16 13:18:44.197  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:18:44.197  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
08-16 13:18:44.197  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:18:44.197  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.197  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.197  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.197  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.198  2691  2743 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 13:18:44.198  2691  2743 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:18:44.199  2691  2759 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-16 13:18:44.199  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:18:44.199  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 13:18:44.199  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:18:44.199  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
08-16 13:18:44.200  3784  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 393)
08-16 13:18:44.200  3784  3835 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-16 13:18:44.201  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:18:44.201  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:18:44.201  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:18:44.201  3784  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 393)
08-16 13:18:44.201  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:18:44.201  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.201  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 13:18:44.202  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4098519 not in the list
08-16 13:18:44.202  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:18:44.202  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
08-16 13:18:44.202  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:18:44.202  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.202  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 13:18:44.202  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.202  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.203  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:18:44.203  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 13:18:44.203  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:18:44.203  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
08-16 13:18:44.204  3784  3835 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-16 13:18:44.204  3784  3835 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-16 13:18:44.204  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 13:18:44.204  3784  3835 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-16 13:18:44.204  3784  3835 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 13:18:44.204  2691  2743 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 13:18:44.204  3784  3835 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-16 13:18:44.204  2691  2743 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:18:44.204  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 13:18:44.204  3784  3835 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-16 13:18:44.204  3784  3835 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 13:18:44.204  3784  3835 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 13:18:44.204  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 13:18:44.205  3784  3835 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-16 13:18:44.205  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:18:44.205  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:18:44.205  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 13:18:44.205  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:18:44.205  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.205  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.205  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4098519 not in the list
08-16 13:18:44.205  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:18:44.205  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
08-16 13:18:44.205  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:18:44.205  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.205  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.205  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.205  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.206  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:18:44.206  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:18:44.206  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:18:44.206  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
08-16 13:18:44.207  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:18:44.207  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.207  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.207  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4098519 not in the list
08-16 13:18:44.208  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:18:44.208  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
08-16 13:18:44.208  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:18:44.208  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.208  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.209  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:18:44.209  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
08-16 13:18:44.209  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:18:44.209  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:18:44.209  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.210  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4098519 not in the list
08-16 13:18:44.210  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:18:44.210  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:18:44.210  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:18:44.210  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:18:44.210  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.210  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.210  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4098519 not in the list
08-16 13:18:44.211  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:18:44.211  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
08-16 13:18:44.211  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:18:44.211  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:18:44.211  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.211  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.211  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.212  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:18:44.212  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:18:44.212  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:18:44.212  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
08-16 13:18:44.213  3784  3835 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 13:18:44.213  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:18:44.214  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-16 13:18:44.214  3784  3835 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-16 13:18:44.214  3784  3835 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-16 13:18:44.215  3784  3784 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 13:18:44.215  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 13:18:44.215  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 13:18:44.215  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:18:44.215  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 13:18:44.215  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 13:18:44.215  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-16 13:18:44.215  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.215  3784  3835 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 13:18:44.216  3784  3784 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-16 13:18:44.216  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4098519 not in the list
08-16 13:18:44.216  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:18:44.216  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 13:18:44.217  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 13:18:44.217  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 13:18:44.216  3784  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 13:18:44.217  3784  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-16 13:18:44.217  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.217  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.218  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 13:18:44.218  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 13:18:44.218  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 13:18:44.218  3784  3784 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-16 13:18:44.218  3784  3784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 13:18:44.219  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
08-16 13:18:44.219  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:18:44.219  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:18:44.219  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:18:44.219  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:18:44.219  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.219  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.219  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4098519 not in the list
,08-16 13:18:44.219  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:18:44.219  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
08-16 13:18:44.219  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:18:44.219  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.219  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.219  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.219  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.220  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:18:44.220  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:18:44.220  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:18:44.220  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
,08-16 13:18:44.221  3784  3835 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-16 13:18:44.221  3784  3835 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 13:18:44.222  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 13:18:44.222  3784  3835 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 13:18:44.222  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:18:44.222  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:18:44.222  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:18:44.222  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:18:44.222  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.222  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 13:18:44.222  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4098519 not in the list
08-16 13:18:44.222  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:18:44.222  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
08-16 13:18:44.222  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:18:44.222  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.222  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.222  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.223  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.223  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:18:44.223  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:18:44.224  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:18:44.224  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
,08-16 13:18:44.226  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 13:18:44.226  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:18:44.226  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:18:44.227  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:18:44.227  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.227  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.227  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4098519 not in the list
08-16 13:18:44.227  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:18:44.227  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
,08-16 13:18:44.227  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:18:44.227  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.227  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.227  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.227  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.228  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:18:44.228  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:18:44.228  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:18:44.228  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
,08-16 13:18:44.228  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:18:44.228  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:18:44.228  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:18:44.229  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:18:44.229  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.229  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.229  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4098519 not in the list
08-16 13:18:44.229  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:18:44.229  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
08-16 13:18:44.229  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:18:44.229  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.229  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.229  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:18:44.229  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:18:44.230  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:18:44.230  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:18:44.230  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:18:44.230  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f179de not in the list
,08-16 13:18:44.231  3784  3835 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-16 13:18:44.231  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 13:18:44.231  3784  3835 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-16 13:18:44.231  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 13:18:44.231  3784  3835 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-16 13:18:44.231  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-16 13:18:44.232  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 13:18:44.232  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-16 13:18:44.233  3784  3835 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-16 13:18:44.233  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 13:18:44.233  3784  3835 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-16 13:18:44.233  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 13:18:44.233  3784  3835 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-16 13:18:44.233  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-16 13:18:44.233  3784  3835 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-16 13:18:44.234  3784  3835 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-16 13:18:44.234  3784  3835 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-16 13:18:44.234  3784  3835 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-16 13:18:44.234  3784  3835 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-16 13:18:44.234  3784  3835 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-16 13:18:44.235  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:18:44.235  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b7b5d90 added. We now have 2 listener(s)
08-16 13:18:44.235  3784  3835 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 13:18:44.236  3784  3835 D BluetoothAdapter: enable(): BT is already enabled..!
08-16 13:18:44.236   875  1699 D WifiService: setWifiEnabled: true pid=3784, uid=10000
08-16 13:18:44.236   875  1699 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 13:18:44.237  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:18:44.237  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@768e689 added. We now have 3 listener(s)
08-16 13:18:44.237  3784  3835 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 13:18:44.240  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 13:18:44.240  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4de168e added. We now have 4 listener(s)
08-16 13:18:44.240  3784  3835 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 13:18:44.241  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:18:44.241  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d430eaf added. We now have 5 listener(s)
08-16 13:18:44.241  3784  3835 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 13:18:44.243   875  1936 D WifiService: setWifiEnabled: false pid=3784, uid=10000
08-16 13:18:44.243   875  1936 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 13:18:44.246  2691  2738 D BluetoothAdapterState: Current state: ON, message: 23
08-16 13:18:44.246  2691  2738 D BluetoothAdapterProperties: Setting state to 13
08-16 13:18:44.246  2691  2738 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-16 13:18:44.247  2691  2738 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 13:18:44.247  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 13:18:44.248  2691  2738 I BluetoothAdapterState: Entering PendingCommandState
,08-16 13:18:44.249  2691  2691 D BluetoothMapService: onReceive
08-16 13:18:44.250  2691  2691 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:18:44.250  2691  2691 D BluetoothMapService: STATE_TURNING_OFF
08-16 13:18:44.250  2691  2691 D BluetoothMapService: MAP Service closeService in
08-16 13:18:44.250  2691  2691 D BluetoothMapMasInstance0: MAP Service shutdown
08-16 13:18:44.250  2691  2691 D ObexServerSockets0: shutdown(block = true)
08-16 13:18:44.250  2691  2691 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 13:18:44.251  2691  2691 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 13:18:44.251  2691  2872 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-16 13:18:44.251  2691  2896 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-16 13:18:44.252  2691  2895 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-16 13:18:44.252  2691  2691 I BtOppRfcommListener: stopping Accept Thread
08-16 13:18:44.252  2691  3405 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 13:18:44.252  2691  3405 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 13:18:44.252  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:18:44.253  3784  3835 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:18:44.253  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:18:44.253  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:18:44.253  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:18:44.253  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:18:44.253  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:18:44.253  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:18:44.253  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:18:44.254  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:18:44.254  3784  3835 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 13:18:44.254  3784  3835 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 13:18:44.256  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:18:44.259  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:18:44.262  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:18:44.263  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:18:44.263  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:18:44.263  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:18:44.263  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:18:44.263  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:18:44.263  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:18:44.263  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:18:44.263  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 13:18:44.263  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:18:44.264  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 13:18:44.265   875   888 I ActivityManager: Start proc 3854:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-16 13:18:44.266  2691  2743 D BluetoothAdapterProperties: Scan Mode:20
,08-16 13:18:44.266  2691  2738 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-16 13:18:44.265  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 13:18:44.267  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:18:44.270  2691  2691 D HeadsetService: Received stop request...Stopping profile...
08-16 13:18:44.272   875   875 D BluetoothHeadset: Proxy object disconnected
08-16 13:18:44.274  1919  1935 D BluetoothHeadset: Proxy object disconnected
08-16 13:18:44.277  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:18:44.270   875  1306 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 13:18:44.277   875  1306 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-16 13:18:44.277   875  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 13:18:44.278   875  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 13:18:44.278   875   875 D BluetoothHeadset: Proxy object disconnected
08-16 13:18:44.278  1361  1718 D BluetoothHeadset: Proxy object disconnected
08-16 13:18:44.279   875   875 D BluetoothHeadset: Proxy object disconnected
,08-16 13:18:44.279  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:18:44.279  2691  2691 D A2dpService: Received stop request...Stopping profile...
08-16 13:18:44.279  2691  2878 D A2dpStateMachine: Exit Disconnected: -1
08-16 13:18:44.280   875   875 D BluetoothA2dp: Proxy object disconnected
08-16 13:18:44.281  1361  1361 D HeadsetProfile: Bluetooth service disconnected
08-16 13:18:44.282  1361  1361 D BluetoothA2dp: Proxy object disconnected
08-16 13:18:44.283  2691  2691 D HidService: Received stop request...Stopping profile...
08-16 13:18:44.283  2691  2691 D HidService: Stopping Bluetooth HidService
08-16 13:18:44.284  1361  1361 D BluetoothInputDevice: Proxy object disconnected
08-16 13:18:44.284  1361  1361 D HidProfile: Bluetooth service disconnected
08-16 13:18:44.286  2691  2691 D HealthService: Received stop request...Stopping profile...
08-16 13:18:44.288  2691  2691 D PanService: Received stop request...Stopping profile...
08-16 13:18:44.289  1361  1361 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 13:18:44.289  1361  1361 D PanProfile: Bluetooth service disconnected
08-16 13:18:44.290  2691  2691 V BluetoothAdapterState: isTurningOff()=true
08-16 13:18:44.290  2691  2691 V BluetoothAdapterState: isTurningOn()=false
08-16 13:18:44.290  2691  2691 V BluetoothAdapterState: isBleTurningOn()=false
08-16 13:18:44.290  2691  2691 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 13:18:44.290   372   874 D CommandListener: Clearing all IP addresses on wlan0
08-16 13:18:44.290   875  1873 D DhcpClient: Clearing IP address
08-16 13:18:44.290  2691  2691 D BluetoothMapService: Received stop request...Stopping profile...
08-16 13:18:44.291  2691  2691 D BluetoothMapService: stop()
,08-16 13:18:44.292  2691  2691 D BluetoothMapAppObserver: deinitObservers()
,08-16 13:18:44.292  2691  2691 D BluetoothMapAppObserver: removeReceiver()
,08-16 13:18:44.292   372   874 D CommandListener: Setting iface cfg
08-16 13:18:44.296   875  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-16 13:18:44.296   875  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-16 13:18:44.298  1549  2458 V NativeCrypto: Read error: ssl=0x9b1cda00: I/O error during system call, Connection timed out
08-16 13:18:44.299   403   403 E Parcel  : Reading a NULL string not supported here.
08-16 13:18:44.299   875  1306 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-16 13:18:44.299   875  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 13:18:44.301   875  1308 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-16 13:18:44.302  2691  2691 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 13:18:44.303  2691  2691 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 13:18:44.303  1549  2458 V NativeCrypto: SSL shutdown failed: ssl=0x9b1cda00: I/O error during system call, Broken pipe
08-16 13:18:44.303  2691  2691 V BluetoothAdapterState: isTurningOff()=true
,08-16 13:18:44.303  2691  2691 V BluetoothAdapterState: isTurningOn()=false
,08-16 13:18:44.303  2691  2691 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 13:18:44.303  2691  2691 V BluetoothAdapterState: isBleTurningOff()=false
08-16 13:18:44.304  2691  2868 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-16 13:18:44.304  2691  2868 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 13:18:44.304  2691  2868 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-16 13:18:44.304   372   874 D CommandListener: Clearing all IP addresses on wlan0
08-16 13:18:44.304  2691  2743 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-16 13:18:44.304  2691  2743 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-16 13:18:44.305  2691  2691 V BluetoothAdapterState: isTurningOff()=true
08-16 13:18:44.305  2691  2868 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 13:18:44.305  2691  2691 V BluetoothAdapterState: isTurningOn()=false
08-16 13:18:44.305  2691  2691 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 13:18:44.305  2691  2868 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 13:18:44.305  2691  2691 V BluetoothAdapterState: isBleTurningOff()=false
08-16 13:18:44.305  2691  2868 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-16 13:18:44.305  2691  2691 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 13:18:44.306  2691  2868 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-16 13:18:44.306  2691  2691 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-16 13:18:44.306  2691  2868 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 13:18:44.306  2691  2868 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-16 13:18:44.306  2691  2691 V BluetoothAdapterState: isTurningOff()=true
08-16 13:18:44.306  2691  2743 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-16 13:18:44.306  2691  2691 V BluetoothAdapterState: isTurningOn()=false
08-16 13:18:44.306  2691  2691 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 13:18:44.306  2691  2691 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 13:18:44.306  2691  2743 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-16 13:18:44.306  2691  2691 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-16 13:18:44.306  2691  2743 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-16 13:18:44.306  1361  1361 D BluetoothMap: Proxy object disconnected
,08-16 13:18:44.309  1361  1361 D MapProfile: Bluetooth service disconnected
,08-16 13:18:44.311  2691  2691 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 13:18:44.314   875  1306 D WifiConfigStore: Retrieve network priorities after PNO.
08-16 13:18:44.312  2691  2691 V BluetoothAdapterState: isTurningOff()=true
08-16 13:18:44.314  2691  2691 V BluetoothAdapterState: isTurningOn()=false
08-16 13:18:44.314  2691  2691 V BluetoothAdapterState: isBleTurningOn()=false
08-16 13:18:44.314  2691  2691 V BluetoothAdapterState: isBleTurningOff()=false
08-16 13:18:44.315   875  1876 D DhcpClient: Receive thread stopped
08-16 13:18:44.315  2691  2691 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 13:18:44.315   875  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 13:18:44.315  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:18:44.316  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:18:44.316  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:18:44.316  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:18:44.316  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:18:44.316  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:18:44.316  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:18:44.316  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:18:44.316  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:18:44.316  2691  2691 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 13:18:44.316  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:18:44.316  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:18:44.317  2691  2691 D BluetoothMapService: MAP Service closeService in
08-16 13:18:44.317  2691  2691 V BluetoothAdapterState: isTurningOff()=true
08-16 13:18:44.317  2691  2691 V BluetoothAdapterState: isTurningOn()=false
08-16 13:18:44.317  2691  2691 V BluetoothAdapterState: isBleTurningOn()=false
08-16 13:18:44.317  2691  2691 V BluetoothAdapterState: isBleTurningOff()=false
08-16 13:18:44.318  2691  2738 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-16 13:18:44.318  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:18:44.318  2691  2738 D BluetoothAdapterProperties: Setting state to 15
08-16 13:18:44.318  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:18:44.318  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:18:44.318  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:18:44.318  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:18:44.318  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:18:44.318  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:18:44.318  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:18:44.318  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:18:44.318  2691 , 2738 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-16 13:18:44.318  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:18:44.318  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:18:44.318  2691  2691 D BluetoothMapService: cleanup()
08-16 13:18:44.318  2691  2691 D BluetoothMapService: MAP Service closeService in
08-16 13:18:44.319   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 13:18:44.319  1361  1374 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 13:18:44.319  2691  2738 I BluetoothAdapterState: Entering BleOnState
08-16 13:18:44.319  2102  2309 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:18:44.320  1361  1375 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 13:18:44.320   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 13:18:44.320  1361  1718 D BluetoothMap: onBluetoothStateChange: up=false
08-16 13:18:44.321   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 13:18:44.321  1361  1374 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 13:18:44.322  1361  1375 D BluetoothPan: onBluetoothStateChange on: false
08-16 13:18:44.322  1919  2061 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 13:18:44.322  1361  1718 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 13:18:44.323   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 13:18:44.323  2691  2738 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-16 13:18:44.323  2691  2738 D BluetoothAdapterProperties: Setting state to 16
08-16 13:18:44.323  2691  2738 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-16 13:18:44.323  2691  2738 D BluetoothAdapterProperties: onBleDisable
08-16 13:18:44.324  2691  2738 I BluetoothAdapterState: Entering PendingCommandState
08-16 13:18:44.324  2691  2739 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-16 13:18:44.325  2691  2868 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-16 13:18:44.325  2691  2868 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 13:18:44.326  2691  2743 D BluetoothAdapterProperties: Scan Mode:20
08-16 13:18:44.327  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:18:44.328  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:18:44.329  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:18:44.329  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:18:44.354   372   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 13:18:44.362  3854  3854 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-16 13:18:44.370   372   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 13:18:44.371  3854  3854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 13:18:44.371   875  1308 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-16 13:18:44.371   875  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 13:18:44.373   875   892 D Tethering: MasterInitialState.processMessage what=3
08-16 13:18:44.376  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:18:44.377  3373  3373 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@63fc789 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-16 13:18:44.377  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:18:44.384  1549  1549 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 13:18:44.388   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@dad8260:true
,08-16 13:18:44.397   875  1698 I ActivityManager: Start proc 3872:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-16 13:18:44.406  3854  3854 D LocalBluetoothProfileManager: Adding local MAP profile
,08-16 13:18:44.408  3854  3854 D BluetoothMap: Create BluetoothMap proxy object
,08-16 13:18:44.417  3854  3854 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-16 13:18:44.421   372   874 E Netd    : netlink response contains error (No such file or directory)
08-16 13:18:44.422   875  1308 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-16 13:18:44.428  3872  3872 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-16 13:18:44.431  3854  3854 D DockEventReceiver: finishStartingService: stopping service
,08-16 13:18:44.439   875   886 I ActivityManager: Killing 3373:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-16 13:18:44.525  2691  2743 I bt_hci  : shut_down
,08-16 13:18:44.526  2691  2761 D bt_hwcfg: hw_epilog_process
,08-16 13:18:44.537  2691  2761 I bt_vendor: low_power_mode_cb
,08-16 13:18:44.558  2691  2761 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-16 13:18:44.558  2691  2761 I bt_vendor: epilog_cb
08-16 13:18:44.558  2691  2761 I bt_hci  : epilog_finished_callback
,08-16 13:18:44.561  2691  2743 I bt_hci_h4: hal_close
,08-16 13:18:44.562  2691  2743 I bt_userial_vendor: device fd = 51 close
,08-16 13:18:44.649  3872  3872 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 13:18:44.649  3872  3872 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 13:18:44.649  3872  3872 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 13:18:44.649  3872  3872 D StrictMode: StrictMode policy violation; ~duration=101 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-16 13:18:44.649  3,872  3872 D StrictMode: 	at com.google.r.e.b(PG:170)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 13:18:44.649  3872  3872 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.r.k.d(PG:583)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.r.e.b(PG:170)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 13,:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 13:18:44.649  3872  3872 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 13:18:44.649  3872  3872 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 13:18:44.649  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 13:18:44.650  3872  3872 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 13:18:44.650  3872  3872 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 13:18:44.650  3872  3872 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-16 13:18:44.650  3872  3872 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-16 13:18:44.650  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-16 13:18:44.650  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 13:18:44.650  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 13:18:44.650  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 13:18:44.650  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 13:18:44.650  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 13:18:44.650  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 13:18:44.650  3872  3872 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 13:18:44.650  3872  3872 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 13:18:44.650  3872  3872 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 13:18:44.650  3872  3872 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 13:18:44.650  3872  3872 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:18:44.650  3872  3872 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:18:44.650  3872  3872 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 13:18:44.650  3872  3872 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:18:44.650  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 13:18:44.650  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 13:18:44.692   875  1934 I ActivityManager: Start proc 3904:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
08-16 13:18:44.693   875  1934 I ActivityManager: Killing 2389:com.google.android.talk/u0a61 (adj 15): empty #17
08-16 13:18:44.720  3784  3784 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 13:18:44.841  3904  3904 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-16 13:18:44.856  2691  2739 D bt_stack_manager: event_shut_down_stack finished.
,08-16 13:18:44.857  2691  2738 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-16 13:18:44.858  2691  2691 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 13:18:44.858  2691  2738 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-16 13:18:44.859  2691  2691 D BtGatt.GattService: Received stop request...Stopping profile...
,08-16 13:18:44.859  2691  2691 D BtGatt.GattService: stop()
08-16 13:18:44.859  2691  2691 D BtGatt.AdvertiseManager: advertise clients cleared
08-16 13:18:44.860  2691  2691 V BluetoothAdapterState: isTurningOff()=false
08-16 13:18:44.860  2691  2691 V BluetoothAdapterState: isTurningOn()=false
,08-16 13:18:44.860  2691  2691 V BluetoothAdapterState: isBleTurningOn()=false
08-16 13:18:44.860  2691  2691 V BluetoothAdapterState: isBleTurningOff()=true
,08-16 13:18:44.860  2691  2738 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-16 13:18:44.861  2691  2738 D BluetoothAdapterProperties: Setting state to 10
,08-16 13:18:44.861  2691  2738 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-16 13:18:44.861  2691  2738 I BluetoothAdapterState: Entering OffState
,08-16 13:18:44.862   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-16 13:18:44.868  2691  2691 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-16 13:18:44.868  2691  2691 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-16 13:18:44.868  2691  2691 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-16 13:18:44.869  2691  2739 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-16 13:18:44.872  2691  2739 D bt_stack_manager: event_clean_up_stack finished.
,08-16 13:18:44.888  2691  2691 I art     : System.exit called, status: 0
,08-16 13:18:44.888  2691  2691 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 13:18:44.932  3904  3904 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-16 13:18:44.962  3872  3891 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-16 13:18:44.976   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@82a22fd:true
,08-16 13:18:45.001   875  1936 I ActivityManager: Start proc 3932:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-16 13:18:45.004   875   885 I ActivityManager: Process com.android.bluetooth (pid 2691) has died
,08-16 13:18:45.063  3932  3932 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-16 13:18:45.210  3932  3949 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
08-16 13:18:45.210  3932  3949 I Babel_SMS: MmsConfig.loadMmsSettings
08-16 13:18:45.212  3932  3949 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-16 13:18:45.212  3932  3949 I Babel_SMS: MmsConfig.loadFromDatabase
,08-16 13:18:45.250  3932  3949 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-16 13:18:45.250  3932  3949 I Babel_SMS: MmsConfig.loadFromResources
08-16 13:18:45.252  3932  3949 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-16 13:18:45.252  3932  3949 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-16 13:18:45.282  3932  3932 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 13:18:45.284  3932  3932 I Babel_Crash: startup - clean
,08-16 13:18:45.308  3932  3932 I Babel_telephony: TeleModule.launchCompleted
,08-16 13:18:45.320   875  1373 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-16 13:18:45.332  3932  3932 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-16 13:18:45.339  3932  3932 W Babel   : BAM#gBA: invalid account id: -1
08-16 13:18:45.339  3932  3932 W Babel   : BAM#gBA: invalid account id: -1
,08-16 13:18:45.340  3932  3932 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-16 13:18:45.343  3932  3954 I Babel   : deleted: false for 0
,08-16 13:18:45.347   875   885 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-16 13:18:45.360  3854  3854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 13:18:45.389   875   886 I ActivityManager: Start proc 3957:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-16 13:18:45.403  3854  3854 D DockEventReceiver: finishStartingService: stopping service
,08-16 13:18:45.432  3932  3932 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 13:18:45.503  3932  3932 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-16 13:18:45.527  3932  3932 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 13:18:45.531  3957  3957 D AdapterServiceConfig: Adding HeadsetService
08-16 13:18:45.531  3957  3957 D AdapterServiceConfig: Adding A2dpService
08-16 13:18:45.531  3957  3957 D AdapterServiceConfig: Adding HidService
,08-16 13:18:45.531  3957  3957 D AdapterServiceConfig: Adding HealthService
,08-16 13:18:45.533  3957  3957 D AdapterServiceConfig: Adding PanService
08-16 13:18:45.533  3957  3957 D AdapterServiceConfig: Adding GattService
08-16 13:18:45.533  3957  3957 D AdapterServiceConfig: Adding BluetoothMapService
08-16 13:18:45.533  3932  3932 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 13:18:45.540   875  1625 I ActivityManager: Killing 3549:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-16 13:18:45.548  3932  3932 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 13:18:45.567  3932  3932 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 13:18:45.609  1549  1549 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 13:18:45.615  3932  3932 I vclib   : onServiceConnected
,08-16 13:18:45.618   875  1625 I ActivityManager: Killing 3585:com.google.android.apps.books/u0a34 (adj 15): empty #17
,08-16 13:18:45.702  1726  1726 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 13:18:45.705  1726  1726 D SystemUpdateService: onCreate
,08-16 13:18:45.708  1726  1726 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 13:18:45.718  1726  3969 I SystemUpdateService: active receiver: enabled
,08-16 13:18:45.721  1726  3969 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 13:18:45.723  1726  3969 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-16 13:18:45.723  1726  3969 I SystemUpdateService: now status is 0 (complete)
08-16 13:18:45.723  1726  3969 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 13:18:45.723  1726  3969 I SystemUpdateService: file has been verified
08-16 13:18:45.723  1726  3969 I SystemUpdateService: OTA package size = 12249756
,08-16 13:18:45.731  1726  3969 I SystemUpdateService: showing system update notification
,08-16 13:18:45.743  1726  1726 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-16 13:18:45.749  1726  2436 I iu.UploadsManager: num queued entries: 0
,08-16 13:18:45.750  1726  2436 I iu.UploadsManager: num updated entries: 0
,08-16 13:18:45.753  1726  1726 D SystemUpdateService: onDestroy
,08-16 13:18:45.753  1726  2436 I iu.SyncManager: NEXT; no task
,08-16 13:18:45.758  1726  1726 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 13:18:45.760  1726  1726 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 13:18:45.778   875   885 I ActivityManager: Start proc 3971:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-16 13:18:45.822  3971  3971 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-16 13:18:45.825  3971  3971 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 13:18:45.831  3971  3971 D SprintDMHelper: simOperator: 
08-16 13:18:45.831  3971  3971 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 13:18:45.871   875  1698 I ActivityManager: Start proc 3983:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-16 13:18:45.872   875  1698 I ActivityManager: Killing 3427:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-16 13:18:46.050   875  1625 I ActivityManager: Start proc 3999:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-16 13:18:46.052  3932  3997 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-16 13:18:46.059   875  1373 I ActivityManager: Killing 3475:android.process.acore/u0a5 (adj 15): empty #17
,08-16 13:18:46.103  3999  3999 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-16 13:18:46.165  3999  3999 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-16 13:18:46.165  3999  3999 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-16 13:18:46.165  3999  3999 I GAv4    :   adb logcat -s GAv4
,08-16 13:18:46.182  3999  3999 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-16 13:18:46.189  3999  3999 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-16 13:18:46.220  3999  4016 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-16 13:18:46.331  3999  3999 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-16 13:18:46.367  3999  3999 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-16 13:18:46.379  3999  3999 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4722-4725)
08-16 13:18:46.379  3999  3999 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 13:18:46.390  3999  3999 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e1831bb}
,08-16 13:18:46.390  3999  3999 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 13:18:46.392  3999  3999 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-16 13:18:46.407  3999  3999 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-16 13:18:46.409  3999  3999 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-16 13:18:46.422  3999  3999 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-16 13:18:46.436  3999  3999 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 13:18:46.436  3999  3999 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 13:18:46.437  3999  3999 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 13:18:46.437  3999  3999 I Adreno  : Build Date                       : 10/20/15
08-16 13:18:46.437  3999  3999 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 13:18:46.437  3999  3999 I Adreno  : Local Branch                     : M14
08-16 13:18:46.437  3999  3999 I Adreno  : Remote Branch                    : 
08-16 13:18:46.437  3999  3999 I Adreno  : Remote Branch                    : 
08-16 13:18:46.437  3999  3999 I Adreno  : Reconstruct Branch               : 
,08-16 13:18:46.501  3999  3999 I NSApplication: Starting up...
,08-16 13:18:46.512  3999  4045 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-16 13:18:46.550   875  1625 I ActivityManager: Start proc 4050:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-16 13:18:46.551   875  1625 I ActivityManager: Killing 3666:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-16 13:18:46.636  4050  4050 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-16 13:18:46.822   875  1373 I ActivityManager: Killing 3682:com.android.musicfx/u0a18 (adj 15): empty #17
,08-16 13:18:47.256   875   885 D WifiService: setWifiEnabled: true pid=3784, uid=10000
,08-16 13:18:47.257   875   885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 13:18:47.274   875  1306 D WifiConfigStore: Loading config and enabling all networks 
,08-16 13:18:47.285  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 13:18:47.285  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:18:47.285  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:18:47.285  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:18:47.285  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:18:47.285  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:18:47.285  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:18:47.285  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:18:47.285  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 13:18:47.286  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 13:18:47.286  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:18:47.289  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:18:47.289  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:18:47.289  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:18:47.289  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:18:47.289  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:18:47.289  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:18:47.289  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:18:47.289  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:18:47.289  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:18:47.289  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 13:18:47.289  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 13:18:47.321   875  1306 D WifiConfigStore: loaded 0 passpoint configs
,08-16 13:18:47.322   875  1306 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-16 13:18:47.322   875  1306 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-16 13:18:47.323   875  1306 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-16 13:18:47.323   875  1306 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-16 13:18:47.324   875  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-16 13:18:47.324   875  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-16 13:18:47.335   372   874 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-16 13:18:47.335   875  1306 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.12 rxSuccessRate=23.38 delta 1000 -> 994
,08-16 13:18:47.336   372   874 D CommandListener: Setting iface cfg
,08-16 13:18:47.338   875  1305 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '127 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 127 Failed to set address (No such device)'
,08-16 13:18:47.338   875  1305 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-16 13:18:47.344   875  1306 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-16 13:18:47.345   875  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 13:18:47.355   875  1306 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-16 13:18:47.357   875  1305 D WifiNative-HAL: p2pGetDeviceAddress
,08-16 13:18:47.414   875  1305 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-16 13:18:47.457   875  1306 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-16 13:18:47.462  1457  1457 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-16 13:18:47.883  1457  1457 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 13:18:47.926  1457  1457 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-16 13:18:47.927  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-16 13:18:47.932   875  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 13:18:47.947   875  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 13:18:47.948   875  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 13:18:47.949   875  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-16 13:18:47.969   875  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 13:18:47.982   372   874 D CommandListener: Setting iface cfg
,08-16 13:18:47.983   875  1306 D WifiStateMachine: Start Dhcp Watchdog 2
,08-16 13:18:47.999   875  1308 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-16 13:18:48.002   875  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-16 13:18:48.024   875  4075 D DhcpClient: Receive thread started
,08-16 13:18:48.108   875  1306 E native  : do suspend false
,08-16 13:18:48.131   875  1873 D DhcpClient: Broadcasting DHCPDISCOVER
,08-16 13:18:48.144   875  4075 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172685, domain null
,08-16 13:18:48.147   875  1873 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172685 seconds
,08-16 13:18:48.152   875  1873 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-16 13:18:48.165   875  4075 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-16 13:18:48.167   875  1873 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-16 13:18:48.175   372   874 D CommandListener: Setting iface cfg
,08-16 13:18:48.186   875  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-16 13:18:48.188   875  1873 D DhcpClient: Scheduling renewal in 86399s
,08-16 13:18:48.205   875  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-16 13:18:48.208   875  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-16 13:18:48.208   875  1306 D WifiConfigStore: No blacklist allowed without epno enabled
,08-16 13:18:48.209   875  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-16 13:18:48.211   875  1308 D ConnectivityService: Adding iface wlan0 to network 101
,08-16 13:18:48.220   875  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 13:18:48.266   875  1308 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-16 13:18:48.266   875  1308 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-16 13:18:48.269   875  1308 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-16 13:18:48.272   875  1308 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-16 13:18:48.276   875  1308 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-16 13:18:48.287   875  1308 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-16 13:18:48.293   875  1308 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-16 13:18:48.293   875  1308 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-16 13:18:48.294   875  1306 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-16 13:18:48.294   875  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 13:18:48.295   875  1308 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-16 13:18:48.295   875  1308 D ConnectivityService:    accepting network in place of null
08-16 13:18:48.297   875  1308 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -55]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} },
,08-16 13:18:48.305   875  4074 D NetlinkSocketObserver: NeighborEvent{elapsedMs=136651, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 13:18:48.333   372   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 13:18:48.374   875  4073 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.174,2a00:1450:4001:815::200e
,08-16 13:18:48.409   372   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 13:18:48.415   875  1308 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 13:18:48.415   875  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 13:18:48.420   875  1308 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-16 13:18:48.423   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-16 13:18:48.443  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:18:48.443  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:18:48.443  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:18:48.443  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:18:48.443  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:18:48.443  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:18:48.443  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:18:48.443  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:18:48.443  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 13:18:48.443  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:18:48.444  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 13:18:48.446  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 13:18:48.446  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:18:48.446  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:18:48.446  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:18:48.446  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:18:48.446  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:18:48.446  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:18:48.446  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:18:48.446  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:18:48.446  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:18:48.446  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 13:18:48.453  1726  1726 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 13:18:48.457  1726  1726 D SystemUpdateService: onCreate
08-16 13:18:48.457   875  4073 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 11:18:48 GMT], X-Android-Received-Millis=[1471346328456], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471346328424]}
,08-16 13:18:48.462   875  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-16 13:18:48.462   875  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed,
08-16 13:18:48.462   875  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-16 13:18:48.464  1726  1726 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 13:18:48.467  1726  4087 I SystemUpdateService: active receiver: enabled
,08-16 13:18:48.469   875  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-16 13:18:48.473  1726  4087 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 13:18:48.476  1726  4087 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-16 13:18:48.477  1726  4087 I SystemUpdateService: now status is 0 (complete)
08-16 13:18:48.477  1726  4087 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 13:18:48.477  1726  4087 I SystemUpdateService: file has been verified
,08-16 13:18:48.477  1726  4087 I SystemUpdateService: OTA package size = 12249756
,08-16 13:18:48.483  1726  4087 I SystemUpdateService: showing system update notification
,08-16 13:18:48.488  1726  1726 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-16 13:18:48.490  1726  2436 I iu.UploadsManager: num queued entries: 0
,08-16 13:18:48.490  1726  2436 I iu.UploadsManager: num updated entries: 0
,08-16 13:18:48.494  1726  2436 I iu.SyncManager: NEXT; no task
,08-16 13:18:48.496  1726  1726 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 13:18:48.497  1726  1726 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-16 13:18:48.497  1726  4091 I MDM     : [176] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-16 13:18:48.497  1726  4091 W BaseAppContext: Using Auth Proxy for data requests.
,08-16 13:18:48.498  1726  4091 V GoogleAuthProtoRequest: [176] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 13:18:48.499  3971  3971 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 13:18:48.504  3971  3971 D SprintDMHelper: simOperator: 
08-16 13:18:48.504  3971  3971 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 13:18:48.509  1549  1549 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 13:18:48.510  1726  1726 D SystemUpdateService: onDestroy
,08-16 13:18:48.513  1549  1549 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 13:18:48.537   875   887 I ActivityManager: Start proc 4095:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,08-16 13:18:48.558  1549  1564 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-16 13:18:48.560  1549  1564 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-16 13:18:48.560  1549  1564 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 13:18:48.560  1549  1564 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 13:18:48.578  1726  4091 E MDM     : [176] SitrepService.a: Error sending sitrep.
,08-16 13:18:48.583  4095  4095 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,08-16 13:18:48.605  3008  4107 V KeepSync: Connecting to GoogleApiClient
,08-16 13:18:48.605   875  1966 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-16 13:18:48.624  3932  4093 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-16 13:18:48.664  1549  1570 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-16 13:18:48.664  1549  1570 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-16 13:18:48.664  1549  1570 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 13:18:48.664  1549  1570 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 13:18:48.677  1726  4115 V BaseAuthAsyncOperation: access token request failed
,08-16 13:18:48.678  3008  4107 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-16 13:18:48.693  4095  4095 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-16 13:18:48.705  4095  4095 I BooksApp: Created application version: 3.6.9 (30609)
,08-16 13:18:48.728  1549  1564 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-16 13:18:48.728  1549  1564 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-16 13:18:48.728  1549  1564 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 13:18:48.728  1549  1564 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 13:18:48.756  3008  4107 E KeepSync: IOException
08-16 13:18:48.756  3008  4107 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-16 13:18:48.756  3008  4107 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-16 13:18:48.756  3008  4107 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-16 13:18:48.756  3008  4107 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-16 13:18:48.756  3008  4107 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-16 13:18:48.756  3008  4107 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-16 13:18:48.756  3008  4107 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-16 13:18:48.756  3008  4107 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-16 13:18:48.756  3008  4107 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-16 13:18:48.756  3008  4107 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-16 13:18:48.756  3008  4107 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-16 13:18:48.756  3008  4107 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-16 13:18:48.756  3008  4107 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-16 13:18:48.756  3008  4107 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-16 13:18:48.756  3008  4107 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 13:18:48.756  3008  4107 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 13:18:48.756  3008  4107 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-16 13:18:48.756  3008  4107 E KeepSync: 	... 10 more
,08-16 13:18:48.756  3008  4107 W KeepSync: Sync result 2
,08-16 13:18:48.770   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 130088, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 13:18:48.778  4095  4119 I BooksSync: Starting books sync for 61035162, extras: ade
,08-16 13:18:48.906  4095  4125 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-16 13:18:48.982  1549  2352 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 13:18:48.982  1549  2352 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 13:18:48.982  1549  2352 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 13:18:48.982  1549  2352 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 13:18:49.051  1549  1986 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-16 13:18:49.051  1549  1986 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 13:18:49.051  1549  1986 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 13:18:49.051  1549  1986 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 13:18:49.075  4095  4125 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-16 13:18:49.078  4095  4119 E BooksSync: Soft error
08-16 13:18:49.078  4095  4119 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 13:18:49.078  4095  4119 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-16 13:18:49.078  4095  4119 E BooksSync: Sync error
08-16 13:18:49.078  4095  4119 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 13:18:49.078  4095  4119 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-16 13:18:49.078  4095  4119 I BooksSync: Finished books sync
,08-16 13:18:49.090   875  1699 I ActivityManager: Killing 2226:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-16 13:18:49.092   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 125731, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 13:18:49.417   875  1308 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-16 13:18:50.219  1549  1549 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 13:18:50.268   875  1373 D WifiService: setWifiEnabled: false pid=3784, uid=10000
,08-16 13:18:50.269   875  1373 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 13:18:50.274  1549  1564 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-16 13:18:50.274  1549  1564 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-16 13:18:50.275  1549  1564 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 13:18:50.275  1549  1564 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 13:18:50.284  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-16 13:18:50.286   875  1306 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 13:18:50.286   875  1306 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-16 13:18:50.286   875  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 13:18:50.286   875  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 13:18:50.292  3493  3493 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-16 13:18:50.293  3493  3493 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-16 13:18:50.293  3493  3493 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-16 13:18:50.302   875  1873 D DhcpClient: Clearing IP address
,08-16 13:18:50.303   372   874 D CommandListener: Clearing all IP addresses on wlan0
08-16 13:18:50.303   875  1625 I ActivityManager: Killing 3704:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-16 13:18:50.305   372   874 D CommandListener: Setting iface cfg
,08-16 13:18:50.311  1549  4111 V NativeCrypto: Read error: ssl=0x9af2c000: I/O error during system call, Connection timed out
,08-16 13:18:50.313  1549  4111 V NativeCrypto: SSL shutdown failed: ssl=0x9af2c000: I/O error during system call, Broken pipe
,08-16 13:18:50.314   875  1373 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,08-16 13:18:50.314   875  4073 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
08-16 13:18:50.315   875  4073 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.174,2a00:1450:4001:815::200e
,08-16 13:18:50.319   875  4073 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:815::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,08-16 13:18:50.321   875  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
,08-16 13:18:50.321   875  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-16 13:18:50.330   875  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-16 13:18:50.351   875  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-16 13:18:50.352   875  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-16 13:18:50.355   875  1306 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-16 13:18:50.356   875  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 13:18:50.358   372   874 D CommandListener: Clearing all IP addresses on wlan0
08-16 13:18:50.359   403   403 E Parcel  : Reading a NULL string not supported here.
,08-16 13:18:50.361   875  1308 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-16 13:18:50.363   875  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 13:18:50.367   875  4075 D DhcpClient: Receive thread stopped
08-16 13:18:50.368  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:18:50.368  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:18:50.368  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:18:50.368  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:18:50.368  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:18:50.368  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:18:50.368  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:18:50.368  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:18:50.368  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:18:50.368   875  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 13:18:50.368  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:18:50.368  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:18:50.369  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 13:18:50.369  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:18:50.369  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:18:50.369  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:18:50.369  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:18:50.369  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:18:50.369  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:18:50.369  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:18:50.369  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:18:50.369  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:18:50.369  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 13:18:50.371  2102  2309 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 13:18:50.395   372   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 13:18:50.419   372   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 13:18:50.419   875  1308 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 13:18:50.420   875  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 13:18:50.421   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-16 13:18:50.424  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:18:50.424  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:18:50.443  1726  1726 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 13:18:50.448  1726  1726 D SystemUpdateService: onCreate
,08-16 13:18:50.451  1726  1726 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 13:18:50.455  1726  4135 I SystemUpdateService: active receiver: enabled
,08-16 13:18:50.457  1726  4135 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 13:18:50.460  1726  4135 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-16 13:18:50.460  1726  4135 I SystemUpdateService: now status is 0 (complete)
08-16 13:18:50.460  1726  4135 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 13:18:50.460  1726  4135 I SystemUpdateService: file has been verified
08-16 13:18:50.460  1726  4135 I SystemUpdateService: OTA package size = 12249756
,08-16 13:18:50.464  1726  1726 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-16 13:18:50.465  1726  2436 I iu.UploadsManager: num queued entries: 0
08-16 13:18:50.465  1726  2436 I iu.UploadsManager: num updated entries: 0
,08-16 13:18:50.485  1726  1726 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-16 13:18:50.486  1726  1726 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 13:18:50.488  3971  3971 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 13:18:50.493  3971  3971 D SprintDMHelper: simOperator: 
,08-16 13:18:50.494  3971  3971 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 13:18:50.520  1726  4135 I SystemUpdateService: showing system update notification
,08-16 13:18:50.530  3932  4138 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-16 13:18:50.541  1726  2436 I iu.SyncManager: NEXT; no task
,08-16 13:18:50.544   372   874 E Netd    : netlink response contains error (No such file or directory)
,08-16 13:18:50.545   875  1308 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-16 13:18:50.545   875  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-16 13:18:50.549  1726  1726 D SystemUpdateService: onDestroy
,08-16 13:18:53.316   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6a8a2fc:true
,08-16 13:18:53.316  3957  3957 D BluetoothAdapterState: make() - Creating AdapterState
,08-16 13:18:53.322  3957  3957 I bt_bluedroid: init
,08-16 13:18:53.323  3957  4143 I BluetoothAdapterState: Entering OffState
,08-16 13:18:53.328  3957  4144 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-16 13:18:53.329  3957  4144 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 13:18:53.329  3957  4144 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-16 13:18:53.329  3957  4144 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-16 13:18:53.331  3957  3957 I bt_bluedroid: get_profile_interface socket
,08-16 13:18:53.334  3957  3957 I bt_bluedroid: get_profile_interface sdp
,08-16 13:18:53.336  3957  4147 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 13:18:53.339  3957  4147 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 13:18:53.340  3957  3967 I bt_bluedroid: config_hci_snoop_log
,08-16 13:18:53.344   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-16 13:18:53.351  3957  4143 D BluetoothAdapterState: Current state: OFF, message: 0
,08-16 13:18:53.352  3957  4143 D BluetoothAdapterProperties: Setting state to 14
,08-16 13:18:53.352  3957  4143 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-16 13:18:53.356  3957  4143 D BluetoothBondStateMachine: make
,08-16 13:18:53.361  3957  4148 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 13:18:53.368  3957  4143 I BluetoothAdapterState: Entering PendingCommandState
,08-16 13:18:53.371  3957  3957 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-16 13:18:53.376  3957  3957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b66a9c9
,08-16 13:18:53.377  3957  3957 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 13:18:53.379  3957  3957 D BtGatt.GattService: Received start request. Starting profile...
08-16 13:18:53.380  3957  3957 D BtGatt.GattService: start()
,08-16 13:18:53.380  3957  3957 I bt_bluedroid: get_profile_interface gatt
08-16 13:18:53.381  3957  3957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b66a9c9
,08-16 13:18:53.382  3957  3957 D BtGatt.AdvertiseManager: advertise manager created
,08-16 13:18:53.395  3957  3957 V BluetoothAdapterState: isTurningOff()=false
,08-16 13:18:53.395  3957  3957 V BluetoothAdapterState: isTurningOn()=false
08-16 13:18:53.395  3957  3957 V BluetoothAdapterState: isBleTurningOn()=true
,08-16 13:18:53.395  3957  3957 V BluetoothAdapterState: isBleTurningOff()=false
08-16 13:18:53.396  3957  4143 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-16 13:18:53.396  3957  4143 I bt_bluedroid: enable
,08-16 13:18:53.397  3957  4144 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-16 13:18:53.398  3957  4144 I bt_hci  : start_up
,08-16 13:18:53.407  3957  4144 I bt_vendor: alloc value 0xb39b9189
,08-16 13:18:53.408  3957  4144 I bt_vendor: init
08-16 13:18:53.408  3957  4144 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-16 13:18:53.408  3957  4144 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-16 13:18:53.516  3957  4144 D bt_hci  : start_up starting async portion
,08-16 13:18:53.517  3957  4151 I bt_hci  : event_finish_startup
,08-16 13:18:53.517  3957  4151 I bt_hci_h4: hal_open
08-16 13:18:53.517  3957  4151 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-16 13:18:53.527  3957  4151 I bt_userial_vendor: device fd = 51 open
,08-16 13:18:53.558  3957  4151 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 13:18:53.590  3957  4151 D bt_hwcfg: Chipset BCM4354A2
,08-16 13:18:53.590  3957  4151 D bt_hwcfg: Target name = [BCM4354A2]
,08-16 13:18:53.591  3957  4151 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-16 13:18:53.683  4095  4117 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-16 13:18:54.188  3957  4151 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-16 13:18:54.190  3957  4151 D bt_hwcfg: Settlement delay -- 100 ms
,08-16 13:18:54.191  3957  4151 I bt_hwcfg: Setting fw settlement delay to 100 
,08-16 13:18:54.307  3957  4151 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 13:18:54.309  3957  4151 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-16 13:18:54.338  3957  4151 I bt_hwcfg: vendor lib fwcfg completed
,08-16 13:18:54.338  3957  4151 I bt_vendor: firmware callback
08-16 13:18:54.338  3957  4151 I bt_hci  : firmware_config_callback
,08-16 13:18:54.349  3957  4155 I bt_btu  : btu_task pending for preload complete event
,08-16 13:18:54.350  3957  4155 I bt_btu_task: Bluetooth chip preload is complete
,08-16 13:18:54.350  3957  4155 I bt_btu  : btu_task received preload complete event
,08-16 13:18:54.362  3957  4155 I         : BTE_InitTraceLevels -- TRC_HCI
,08-16 13:18:54.362  3957  4155 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 13:18:54.363  3957  4155 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-16 13:18:54.363  3957  4155 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 13:18:54.363  3957  4155 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-16 13:18:54.363  3957  4155 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 13:18:54.364  3957  4155 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 13:18:54.365  3957  4155 I         : BTE_InitTraceLevels -- TRC_BTM
,08-16 13:18:54.365  3957  4155 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 13:18:54.365  3957  4155 I         : BTE_InitTraceLevels -- TRC_PAN
,08-16 13:18:54.365  3957  4155 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 13:18:54.366  3957  4155 I         : BTE_InitTraceLevels -- TRC_GATT
,08-16 13:18:54.366  3957  4155 I         : BTE_InitTraceLevels -- TRC_SMP
,08-16 13:18:54.366  3957  4155 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-16 13:18:54.366  3957  4155 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 13:18:54.499  3957  4155 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3936d9d
,08-16 13:18:54.499  3957  4155 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3936d9d 
,08-16 13:18:54.510  3957  4147 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false,
08-16 13:18:54.511  3957  4147 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-16 13:18:54.512  3957  4147 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 13:18:54.515  3957  4147 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 13:18:54.519  3957  4147 D BluetoothAdapterProperties: Scan Mode:20
,08-16 13:18:54.519  3957  4147 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 13:18:54.520  3957  4147 D bt_hci  : do_postload posting postload work item
08-16 13:18:54.521  3957  4151 I bt_hci  : event_postload
,08-16 13:18:54.521  3957  4151 I bt_vendor: sco_config_cb
08-16 13:18:54.521  3957  4151 I bt_hci  : sco_config_callback postload finished.
,08-16 13:18:54.524  3957  4147 D bt_bte_conf: Device ID record 1 : primary
08-16 13:18:54.524  3957  4147 D bt_bte_conf:   vendorId            = 000f
08-16 13:18:54.525  3957  4147 D bt_bte_conf:   vendorIdSource      = 0001
,08-16 13:18:54.525  3957  4147 D bt_bte_conf:   product             = 1200
08-16 13:18:54.525  3957  4147 D bt_bte_conf:   version             = 1436
08-16 13:18:54.525  3957  4147 D bt_bte_conf:   clientExecutableURL = 
,08-16 13:18:54.525  3957  4147 D bt_bte_conf:   serviceDescription  = 
08-16 13:18:54.525  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:18:54.526  3957  4147 D bt_bte_conf:   documentationURL    = 
,08-16 13:18:54.526  3957  4147 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-16 13:18:54.526  3957  4144 D bt_stack_manager: event_start_up_stack finished
08-16 13:18:54.529  3957  4143 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-16 13:18:54.529  3957  4151 I bt_vendor: low_power_mode_cb
08-16 13:18:54.529  3957  4143 D BluetoothAdapterProperties: Setting state to 15
08-16 13:18:54.530  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:18:54.530  3957  4143 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-16 13:18:54.531  3957  4143 I BluetoothAdapterState: Entering BleOnState
,08-16 13:18:54.539  3957  4143 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-16 13:18:54.540  3957  4143 D BluetoothAdapterProperties: Setting state to 11
08-16 13:18:54.540  3957  4143 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-16 13:18:54.546  3957  3957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b66a9c9
08-16 13:18:54.547  3957  3957 D HeadsetService: Received start request. Starting profile...
08-16 13:18:54.553  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:18:54.552  3957  3957 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 13:18:54.553  3957  3957 D HeadsetStateMachine: make
08-16 13:18:54.555  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:18:54.567  3957  4143 I BluetoothAdapterState: Entering PendingCommandState
,08-16 13:18:54.568  3957  3957 D HeadsetStateMachine: max_hf_connections = 1
,08-16 13:18:54.569  3957  3957 I bt_bluedroid: get_profile_interface handsfree
08-16 13:18:54.569  3957  4147 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-16 13:18:54.569  3957  4147 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-16 13:18:54.576  3957  3957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b66a9c9
,08-16 13:18:54.576  3957  3957 D A2dpService: Received start request. Starting profile...
,08-16 13:18:54.577  3957  3957 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 13:18:54.577  3957  3957 I bt_bluedroid: get_profile_interface avrcp
,08-16 13:18:54.584  3957  3957 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 13:18:54.584  3957  3957 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 13:18:54.584  3957  3957 D A2dpStateMachine: make
,08-16 13:18:54.586  3957  3957 I bt_bluedroid: get_profile_interface a2dp
,08-16 13:18:54.587  3957  4147 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-16 13:18:54.591  3957  4164 D A2dpStateMachine: Enter Disconnected: -2
,08-16 13:18:54.592  3957  3957 I BluetoothHidServiceJni: classInitNative: succeeds
,08-16 13:18:54.593  3957  3957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b66a9c9
,08-16 13:18:54.594  1549  1549 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 13:18:54.595  3957  3957 D HidService: Received start request. Starting profile...
,08-16 13:18:54.595  3854  3854 D BluetoothInputDevice: Proxy object connected
08-16 13:18:54.595  3957  3957 I bt_bluedroid: get_profile_interface hidhost
08-16 13:18:54.595  3957  3957 D HidService: setHidService(): set to: null
08-16 13:18:54.595  3957  4147 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39183e5
08-16 13:18:54.596  3957  4147 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-16 13:18:54.596  3854  3854 D HidProfile: Bluetooth service connected
,08-16 13:18:54.596  3957  3957 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 13:18:54.597  3957  3957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b66a9c9
08-16 13:18:54.597  3957  3957 D HealthService: Received start request. Starting profile...
,08-16 13:18:54.600  3957  3957 I bt_bluedroid: get_profile_interface health
,08-16 13:18:54.602  3957  3957 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-16 13:18:54.602  3957  3957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b66a9c9
,08-16 13:18:54.604  3957  3957 D PanService: Received start request. Starting profile...
08-16 13:18:54.604  3957  3957 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 13:18:54.604  3854  3854 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 13:18:54.604  3957  3957 I bt_bluedroid: get_profile_interface pan
08-16 13:18:54.604  3854  3854 D PanProfile: Bluetooth service connected
08-16 13:18:54.605  3957  4147 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-16 13:18:54.612  3957  3957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b66a9c9
,08-16 13:18:54.614  3854  3854 D BluetoothMap: Proxy object connected
,08-16 13:18:54.615  3854  3854 D MapProfile: Bluetooth service connected
,08-16 13:18:54.615  3854  3854 D BluetoothMap: getConnectedDevices()
08-16 13:18:54.616  3957  3957 D BluetoothMapService: Received start request. Starting profile...
08-16 13:18:54.616  3854  3854 D BluetoothMap: Bluetooth is Not enabled
,08-16 13:18:54.616  3957  3957 D BluetoothMapService: start()
,08-16 13:18:54.621  3957  3957 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-16 13:18:54.622  3957  3957 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-16 13:18:54.622  3957  3957 D BluetoothMapAppObserver: createReceiver()
,08-16 13:18:54.624  3957  3957 D BluetoothMapAppObserver: initObservers()
,08-16 13:18:54.624  3957  3957 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-16 13:18:54.636  3957  3957 V BluetoothAdapterState: isTurningOff()=false
08-16 13:18:54.636  3957  3957 V BluetoothAdapterState: isTurningOn()=true
,08-16 13:18:54.636  3957  3957 V BluetoothAdapterState: isBleTurningOn()=false
08-16 13:18:54.637  3957  4162 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 13:18:54.637  3957  3957 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 13:18:54.638  3957  3957 V BluetoothAdapterState: isTurningOff()=false
08-16 13:18:54.638  3957  3957 V BluetoothAdapterState: isTurningOn()=true
08-16 13:18:54.638  3957  3957 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 13:18:54.638  3957  3957 V BluetoothAdapterState: isBleTurningOff()=false
08-16 13:18:54.639  3957  3957 V BluetoothAdapterState: isTurningOff()=false
08-16 13:18:54.639  3957  3957 V BluetoothAdapterState: isTurningOn()=true
,08-16 13:18:54.639  3957  3957 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 13:18:54.639  3957  3957 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 13:18:54.641  3957  3957 V BluetoothAdapterState: isTurningOff()=false
,08-16 13:18:54.641  3957  3957 V BluetoothAdapterState: isTurningOn()=true
08-16 13:18:54.641  3957  3957 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 13:18:54.641  3957  3957 V BluetoothAdapterState: isBleTurningOff()=false
08-16 13:18:54.641  3957  3957 V BluetoothAdapterState: isTurningOff()=false
,08-16 13:18:54.641  3957  3957 V BluetoothAdapterState: isTurningOn()=true
,08-16 13:18:54.642  3957  3957 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 13:18:54.642  3957  3957 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 13:18:54.642  3957  3957 V BluetoothAdapterState: isTurningOff()=false
,08-16 13:18:54.642  3957  3957 V BluetoothAdapterState: isTurningOn()=true
,08-16 13:18:54.642  3957  3957 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 13:18:54.642  3957  3957 V BluetoothAdapterState: isBleTurningOff()=false
08-16 13:18:54.642  3957  4143 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-16 13:18:54.643  3957  4143 D BluetoothAdapterProperties: ScanMode =  20
08-16 13:18:54.643  3957  4143 D BluetoothAdapterProperties: State =  11
08-16 13:18:54.644  3957  4143 D BluetoothAdapterProperties: Setting state to 12
08-16 13:18:54.644  3957  4143 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 13:18:54.646   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 13:18:54.648  3957  4143 I BluetoothAdapterState: Entering OnState
08-16 13:18:54.648  1361  1718 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 13:18:54.649   875   875 D BluetoothA2dp: Proxy object connected
08-16 13:18:54.650  3957  4147 D BluetoothAdapterProperties: Scan Mode:21
08-16 13:18:54.650  3957  4147 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 13:18:54.654  3854  3864 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 13:18:54.655  3854  3864 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 13:18:54.655  3854  3864 D BluetoothPan: onBluetoothStateChange on: true
08-16 13:18:54.656  1361  1375 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 13:18:54.657  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:18:54.657  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:18:54.657  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:18:54.657  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:18:54.657  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:18:54.657  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:18:54.657  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:18:54.657  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:18:54.662  1361  1361 D BluetoothA2dp: Proxy object connected
08-16 13:18:54.663  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:18:54.663  3957  3957 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-16 13:18:54.662   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 13:18:54.664  1361  1718 D BluetoothMap: onBluetoothStateChange: up=true
08-16 13:18:54.664  3957  3957 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-16 13:18:54.666  1361  1361 D BluetoothMap: Proxy object connected
,08-16 13:18:54.666  1361  1361 D MapProfile: Bluetooth service connected
08-16 13:18:54.666  1361  1361 D BluetoothMap: getConnectedDevices()
08-16 13:18:54.666   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 13:18:54.666  3957  3957 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 13:18:54.666  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:18:54.666  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:18:54.666  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:18:54.666  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:18:54.666  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:18:54.666  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:18:54.666  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:18:54.666  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 13:18:54.667  1361  1375 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 13:18:54.669  1361  1374 D BluetoothPan: onBluetoothStateChange on: true
08-16 13:18:54.669  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:18:54.670  3957  3957 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 13:18:54.670  1361  1361 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 13:18:54.670  1361  1361 D PanProfile: Bluetooth service connected
,08-16 13:18:54.671  3854  3865 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 13:18:54.672  3957  3957 D ObexServerSockets: Succeed to create listening sockets 
,08-16 13:18:54.672  3957  3957 D ObexServerSockets0: startAccept()
08-16 13:18:54.672  3957  3957 D ObexServerSockets0: prepareForNewConnect()
08-16 13:18:54.672  1919  1932 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 13:18:54.673  1361  1375 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 13:18:54.674  3957  3957 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-16 13:18:54.674  3957  3957 D BluetoothSdpJni: SDP Create record success - handle: 0
08-16 13:18:54.675  1361  1361 D BluetoothInputDevice: Proxy object connected
,08-16 13:18:54.675  1361  1361 D HidProfile: Bluetooth service connected
08-16 13:18:54.676   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 13:18:54.677  3957  4171 D ObexServerSockets0: Accepting socket connection...
,08-16 13:18:54.677  3957  4170 D ObexServerSockets0: Accepting socket connection...
,08-16 13:18:54.677   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
08-16 13:18:54.679  3957  3957 D BluetoothMapService: onReceive
,08-16 13:18:54.679  3957  3957 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:18:54.679  3957  3957 D BluetoothMapService: STATE_ON
08-16 13:18:54.681  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:18:54.682  3854  3854 D LocalBluetoothProfileManager: Adding local A2DP profile
08-16 13:18:54.683  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:18:54.686  3854  3854 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-16 13:18:54.693  3854  3854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 13:18:54.696  3854  3854 D BluetoothA2dp: Proxy object connected
,08-16 13:18:54.699  1549  1549 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 13:18:54.708  1361  1361 D BluetoothPbap: Proxy object connected
,08-16 13:18:54.708  1361  1361 D PbapServerProfile: Bluetooth service connected
08-16 13:18:54.708  3957  3957 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-16 13:18:54.708  3957  3957 D ObexServerSockets0: prepareForNewConnect()
,08-16 13:18:54.709  3854  3854 D DockEventReceiver: finishStartingService: stopping service
,08-16 13:18:54.710  3854  3854 D BluetoothPbap: Proxy object connected
,08-16 13:18:54.710  3854  3854 D PbapServerProfile: Bluetooth service connected
,08-16 13:18:54.717  3957  4176 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 13:18:54.735  3957  4180 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 13:18:54.738  3957  4180 I BtOppRfcommListener: Accept thread started.
,08-16 13:18:54.750   875   875 D BluetoothHeadset: Proxy object connected
,08-16 13:18:54.750  1919  2212 D BluetoothHeadset: Proxy object connected
08-16 13:18:54.750   875   875 D BluetoothHeadset: Proxy object connected
,08-16 13:18:54.750  1361  1374 D BluetoothHeadset: Proxy object connected
,08-16 13:18:54.751   875   875 D BluetoothHeadset: Proxy object connected
08-16 13:18:54.751  1361  1361 D HeadsetProfile: Bluetooth service connected
,08-16 13:18:54.763   875   892 D BluetoothHeadset: Proxy object connected
,08-16 13:18:54.767   875   892 D BluetoothHeadset: Proxy object connected
,08-16 13:18:54.773  1919  2061 D BluetoothHeadset: Proxy object connected
,08-16 13:18:54.776   875   892 D BluetoothHeadset: Proxy object connected
,08-16 13:18:54.791  3854  3864 D BluetoothHeadset: Proxy object connected
,08-16 13:18:54.793  3854  3854 D HeadsetProfile: Bluetooth service connected
,08-16 13:18:56.284  3957  4143 D BluetoothAdapterState: Current state: ON, message: 23
,08-16 13:18:56.284  3957  4143 D BluetoothAdapterProperties: Setting state to 13
,08-16 13:18:56.285  3957  4143 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-16 13:18:56.286  3957  4143 D BluetoothAdapterProperties: onBluetoothDisable()
,08-16 13:18:56.291  3957  4143 I BluetoothAdapterState: Entering PendingCommandState
08-16 13:18:56.293  3957  3957 D BluetoothMapService: onReceive
,08-16 13:18:56.295  3957  3957 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-16 13:18:56.295  3957  3957 D BluetoothMapService: STATE_TURNING_OFF
08-16 13:18:56.296  3957  3957 D BluetoothMapService: MAP Service closeService in
08-16 13:18:56.296  3957  3957 D BluetoothMapMasInstance0: MAP Service shutdown
08-16 13:18:56.296  3957  3957 D ObexServerSockets0: shutdown(block = true)
08-16 13:18:56.297   875  1308 D ConnectivityService: handlePromptUnvalidated 101
,08-16 13:18:56.297  3957  4170 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-16 13:18:56.301  3957  4147 D BluetoothAdapterProperties: Scan Mode:20
08-16 13:18:56.302  3957  3957 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-16 13:18:56.303  3957  4171 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-16 13:18:56.304  3957  4143 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-16 13:18:56.306  3957  4157 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-16 13:18:56.306  3957  3957 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 13:18:56.307  3957  3957 I BtOppRfcommListener: stopping Accept Thread
08-16 13:18:56.308  3957  4180 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-16 13:18:56.308  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:18:56.308  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:18:56.308  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:18:56.308  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:18:56.308  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:18:56.308  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:18:56.308  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:18:56.308  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:18:56.308  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:18:56.311  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:18:56.311  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:18:56.312  3957  4180 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-16 13:18:56.314  3957  3957 D HeadsetService: Received stop request...Stopping profile...
08-16 13:18:56.315  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:18:56.315  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:18:56.315  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:18:56.315  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:18:56.315  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:18:56.315  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:18:56.315  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:18:56.315  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:18:56.315  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:18:56.316  3854  3854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 13:18:56.316  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:18:56.316  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:18:56.319  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:18:56.320   875   875 D BluetoothHeadset: Proxy object disconnected
08-16 13:18:56.320  1919  1935 D BluetoothHeadset: Proxy object disconnected
08-16 13:18:56.321   875   875 D BluetoothHeadset: Proxy object disconnected
08-16 13:18:56.321  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:18:56.321  1361  1375 D BluetoothHeadset: Proxy object disconnected
08-16 13:18:56.322  3854  3864 D BluetoothHeadset: Proxy object disconnected
,08-16 13:18:56.322   875   875 D BluetoothHeadset: Proxy object disconnected
08-16 13:18:56.322  1361  1361 D HeadsetProfile: Bluetooth service disconnected
08-16 13:18:56.324  3957  3957 D A2dpService: Received stop request...Stopping profile...
08-16 13:18:56.324  3957  4164 D A2dpStateMachine: Exit Disconnected: -1
08-16 13:18:56.326   875   875 D BluetoothA2dp: Proxy object disconnected
,08-16 13:18:56.326  1361  1361 D BluetoothA2dp: Proxy object disconnected
08-16 13:18:56.327  3957  3957 D HidService: Received stop request...Stopping profile...
08-16 13:18:56.327  3957  3957 D HidService: Stopping Bluetooth HidService
,08-16 13:18:56.327  1361  1361 D BluetoothInputDevice: Proxy object disconnected
08-16 13:18:56.328  1361  1361 D HidProfile: Bluetooth service disconnected
08-16 13:18:56.328  3957  3957 D HealthService: Received stop request...Stopping profile...
08-16 13:18:56.329  3957  3957 V BluetoothAdapterState: isTurningOff()=true
08-16 13:18:56.329  3957  3957 V BluetoothAdapterState: isTurningOn()=false
08-16 13:18:56.329  3957  3957 V BluetoothAdapterState: isBleTurningOn()=false
08-16 13:18:56.329  3957  3957 V BluetoothAdapterState: isBleTurningOff()=false
08-16 13:18:56.331  3957  3957 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 13:18:56.331  3854  3854 D DockEventReceiver: finishStartingService: stopping service
08-16 13:18:56.331  3957  4147 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-16 13:18:56.331  3957  4155 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 13:18:56.332  3957  3957 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 13:18:56.332  3957  4155 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 13:18:56.332  3957  4155 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 13:18:56.332  3957  4147 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
08-16 13:18:56.332  3957  3957 D PanService: Received stop request...Stopping profile...
08-16 13:18:56.333  1361  1361 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 13:18:56.333  3854  3854 D HeadsetProfile: Bluetooth service disconnected
08-16 13:18:56.333  1361  1361 D PanProfile: Bluetooth service disconnected
08-16 13:18:56.334  3854  3854 D BluetoothA2dp: Proxy object disconnected
08-16 13:18:56.334  3854  3854 D BluetoothInputDevice: Proxy object disconnected
08-16 13:18:56.334  3854  3854 D HidProfile: Bluetooth service disconnected
08-16 13:18:56.335  3957  3957 D BluetoothMapService: Received stop request...Stopping profile...
08-16 13:18:56.335  3957  3957 D BluetoothMapService: stop()
08-16 13:18:56.337  3957  3957 D BluetoothMapAppObserver: deinitObservers()
08-16 13:18:56.337  3957  3957 D BluetoothMapAppObserver: removeReceiver()
08-16 13:18:56.340  1549  1549 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 13:18:56.344  3854  3854 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 13:18:56.344  1361  1361 D BluetoothMap: Proxy object disconnected
08-16 13:18:56.344  1361  1361 D MapProfile: Bluetooth service disconnected
08-16 13:18:56.344  3957  3957 V BluetoothAdapterState: isTurningOff()=true
08-16 13:18:56.344  3957  3957 V BluetoothAdapterState: isTurningOn()=false
,08-16 13:18:56.344  3957  3957 V BluetoothAdapterState: isBleTurningOn()=false
08-16 13:18:56.344  3854  3854 D PanProfile: Bluetooth service disconnected
,08-16 13:18:56.344  3957  3957 V BluetoothAdapterState: isBleTurningOff()=false
08-16 13:18:56.345  3854  3854 D BluetoothMap: Proxy object disconnected
08-16 13:18:56.345  3854  3854 D MapProfile: Bluetooth service disconnected
08-16 13:18:56.345  3957  4147 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-16 13:18:56.345  3957  4155 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 13:18:56.346  3957  4155 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 13:18:56.346  3957  4155 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 13:18:56.346  3957  4155 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 13:18:56.346  3957  4155 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-16 13:18:56.346  3957  4155 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 13:18:56.346  3957  3957 V BluetoothAdapterState: isTurningOff()=true
08-16 13:18:56.346  3957  3957 V BluetoothAdapterState: isTurningOn()=false
08-16 13:18:56.346  3957  3957 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 13:18:56.346  3957  3957 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 13:18:56.346  3957  3957 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 13:18:56.347  3957  4147 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-16 13:18:56.347  3957  3957 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 13:18:56.347  3957  3957 V BluetoothAdapterState: isTurningOff()=true
08-16 13:18:56.347  3957  3957 V BluetoothAdapterState: isTurningOn()=false
,08-16 13:18:56.347  3957  3957 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 13:18:56.347  3957  3957 V BluetoothAdapterState: isBleTurningOff()=false
08-16 13:18:56.349  3957  3957 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 13:18:56.349  3957  4147 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-16 13:18:56.349  3957  3957 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 13:18:56.350  3957  3957 V BluetoothAdapterState: isTurningOff()=true
,08-16 13:18:56.350  3957  3957 V BluetoothAdapterState: isTurningOn()=false
08-16 13:18:56.350  3957  3957 V BluetoothAdapterState: isBleTurningOn()=false
08-16 13:18:56.350  3957  3957 V BluetoothAdapterState: isBleTurningOff()=false
08-16 13:18:56.351  3957  3957 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 13:18:56.351  3957  3957 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-16 13:18:56.353  3854  3854 D BluetoothPbap: Proxy object disconnected
,08-16 13:18:56.353  3854  3854 D PbapServerProfile: Bluetooth service disconnected
,08-16 13:18:56.353  1361  1361 D BluetoothPbap: Proxy object disconnected
08-16 13:18:56.353  1361  1361 D PbapServerProfile: Bluetooth service disconnected
08-16 13:18:56.354  3957  3957 D BluetoothMapService: MAP Service closeService in
,08-16 13:18:56.354  3957  3957 V BluetoothAdapterState: isTurningOff()=true
08-16 13:18:56.354  3957  3957 V BluetoothAdapterState: isTurningOn()=false
08-16 13:18:56.354  3957  3957 V BluetoothAdapterState: isBleTurningOn()=false
08-16 13:18:56.354  3957  3957 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 13:18:56.354  3957  4143 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-16 13:18:56.354  3957  4143 D BluetoothAdapterProperties: Setting state to 15
08-16 13:18:56.354  3957  4143 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-16 13:18:56.355  3957  4143 I BluetoothAdapterState: Entering BleOnState,
08-16 13:18:56.355   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 13:18:56.355  1361  1718 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-16 13:18:56.356  3854  3865 D BluetoothMap: onBluetoothStateChange: up=false
08-16 13:18:56.357  3854  3864 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-16 13:18:56.358  3957  3957 D BluetoothMapService: cleanup()
08-16 13:18:56.358  3957  3957 D BluetoothMapService: MAP Service closeService in
08-16 13:18:56.359  3854  3865 D BluetoothPan: onBluetoothStateChange on: false
08-16 13:18:56.360  1361  1375 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 13:18:56.361  3854  3864 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 13:18:56.361   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 13:18:56.361  1361  1374 D BluetoothMap: onBluetoothStateChange: up=false
,08-16 13:18:56.362   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-16 13:18:56.362  1361  1718 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 13:18:56.362  1361  1375 D BluetoothPan: onBluetoothStateChange on: false
08-16 13:18:56.363  3854  3865 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 13:18:56.364  3854  3864 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 13:18:56.364  1919  1932 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-16 13:18:56.364  1361  1374 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-16 13:18:56.365   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 13:18:56.365  3957  4143 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-16 13:18:56.365  3957  4143 D BluetoothAdapterProperties: Setting state to 16
,08-16 13:18:56.365  3957  4143 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-16 13:18:56.368  3957  4143 D BluetoothAdapterProperties: onBleDisable
,08-16 13:18:56.368  3957  4143 I BluetoothAdapterState: Entering PendingCommandState
08-16 13:18:56.368  3957  4144 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-16 13:18:56.370  3957  4155 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-16 13:18:56.370  3957  4147 D BluetoothAdapterProperties: Scan Mode:20,
08-16 13:18:56.370  3957  4155 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 13:18:56.371  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:18:56.373  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:18:56.373  3854  3854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 13:18:56.375  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:18:56.376  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:18:56.378  1549  1549 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 13:18:56.379  3854  3854 D DockEventReceiver: finishStartingService: stopping service
,08-16 13:18:56.576  3957  4147 I bt_hci  : shut_down
,08-16 13:18:56.577  3957  4151 D bt_hwcfg: hw_epilog_process
,08-16 13:18:56.579  3957  4151 I bt_vendor: low_power_mode_cb
,08-16 13:18:56.606  3957  4151 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-16 13:18:56.606  3957  4151 I bt_vendor: epilog_cb
08-16 13:18:56.607  3957  4151 I bt_hci  : epilog_finished_callback
,08-16 13:18:56.616  3957  4147 I bt_hci_h4: hal_close
,08-16 13:18:56.618  3957  4147 I bt_userial_vendor: device fd = 51 close
,08-16 13:18:56.742  3957  4144 D bt_stack_manager: event_shut_down_stack finished.
,08-16 13:18:56.743  3957  4143 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-16 13:18:56.749  3957  4143 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-16 13:18:56.750  3957  3957 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 13:18:56.751  3957  3957 D BtGatt.GattService: Received stop request...Stopping profile...
,08-16 13:18:56.751  3957  3957 D BtGatt.GattService: stop()
08-16 13:18:56.752  3957  3957 D BtGatt.AdvertiseManager: advertise clients cleared
,08-16 13:18:56.758  3957  3957 V BluetoothAdapterState: isTurningOff()=false
,08-16 13:18:56.758  3957  3957 V BluetoothAdapterState: isTurningOn()=false
,08-16 13:18:56.759  3957  3957 V BluetoothAdapterState: isBleTurningOn()=false
08-16 13:18:56.759  3957  3957 V BluetoothAdapterState: isBleTurningOff()=true
08-16 13:18:56.760  3957  4143 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-16 13:18:56.762  3957  4143 D BluetoothAdapterProperties: Setting state to 10
08-16 13:18:56.762  3957  4143 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-16 13:18:56.764  3957  4143 I BluetoothAdapterState: Entering OffState
,08-16 13:18:56.768   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-16 13:18:56.794  3957  3957 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-16 13:18:56.794  3957  3957 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-16 13:18:56.795  3957  4144 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-16 13:18:56.804  3957  4144 D bt_stack_manager: event_clean_up_stack finished.
,08-16 13:18:56.798  3957  3957 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-16 13:18:56.810  3957  3957 I art     : System.exit called, status: 0
,08-16 13:18:56.810  3957  3957 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 13:18:56.854   875  1936 I ActivityManager: Process com.android.bluetooth (pid 3957) has died
,08-16 13:18:58.791  3493  3568 D Finsky  : [294] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,08-16 13:18:58.807  1549  1549 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 13:18:58.823  1549  1549 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 13:18:58.828  1549  1549 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 13:18:58.895  1549  2352 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-16 13:18:58.896  1549  2352 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-16 13:18:58.896  1549  2352 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 13:18:58.896  1549  2352 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 13:18:58.949  3493  3568 D Finsky  : [294] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,08-16 13:18:59.280  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 13:18:59.281  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 13:19:01.922   875   895 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-16 13:19:01.933  1856  1856 I Keyboard.Facilitator: onFinishInput()
,08-16 13:19:01.936   875   895 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 13:19:01.936   875   895 I Adreno  : Build Date                       : 10/20/15
08-16 13:19:01.936   875   895 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 13:19:01.936   875   895 I Adreno  : Local Branch                     : M14
08-16 13:19:01.936   875   895 I Adreno  : Remote Branch                    : 
08-16 13:19:01.936   875   895 I Adreno  : Remote Branch                    : 
08-16 13:19:01.936   875   895 I Adreno  : Reconstruct Branch               : 
,08-16 13:19:01.977   282   302 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (247 us)
,08-16 13:19:02.288  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 13:19:02.289  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3f06245 added. We now have 6 listener(s)
08-16 13:19:02.289  3784  3835 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 13:19:02.293  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 13:19:02.293  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1a90d9a added. We now have 7 listener(s)
08-16 13:19:02.294  3784  3835 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 13:19:02.295  3784  3835 I System.out: IsBluetoothEnabled
,08-16 13:19:02.309  3784  3835 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:19:02.354   875   892 I ActivityManager: Start proc 4194:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-16 13:19:02.556  3784  3784 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-16 13:19:02.557  3784  3784 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-16 13:19:02.592   875   895 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-16 13:19:02.597   875   895 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
08-16 13:19:02.597  3784  3784 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f271985 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@63be6cb, 16908290=android.view.AbsSavedState$1@63be6cb}, android:focusedViewId=100}]}]
08-16 13:19:02.597  3784  3784 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-16 13:19:02.599  3784  3784 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-16 13:19:02.599  3784  3784 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-16 13:19:02.601   875   893 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-16 13:19:02.607   282   282 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
,08-16 13:19:02.607   282   282 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-16 13:19:02.612  4194  4194 D AdapterServiceConfig: Adding HeadsetService
,08-16 13:19:02.612  4194  4194 D AdapterServiceConfig: Adding A2dpService
,08-16 13:19:02.612  4194  4194 D AdapterServiceConfig: Adding HidService
,08-16 13:19:02.613  4194  4194 D AdapterServiceConfig: Adding HealthService
,08-16 13:19:02.613  4194  4194 D AdapterServiceConfig: Adding PanService
08-16 13:19:02.613  4194  4194 D AdapterServiceConfig: Adding GattService
08-16 13:19:02.613  4194  4194 D AdapterServiceConfig: Adding BluetoothMapService
08-16 13:19:02.623   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6c7d916:true
,08-16 13:19:02.624  4194  4194 D BluetoothAdapterState: make() - Creating AdapterState
,08-16 13:19:02.628  4194  4194 I bt_bluedroid: init
08-16 13:19:02.628  4194  4214 I BluetoothAdapterState: Entering OffState
,08-16 13:19:02.630  4194  4215 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-16 13:19:02.630  4194  4215 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 13:19:02.630  4194  4215 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 13:19:02.630  4194  4215 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-16 13:19:02.631  4194  4194 I bt_bluedroid: get_profile_interface socket
08-16 13:19:02.632  4194  4218 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-16 13:19:02.632  4194  4194 I bt_bluedroid: get_profile_interface sdp
,08-16 13:19:02.633  4194  4218 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 13:19:02.634  4194  4204 I bt_bluedroid: config_hci_snoop_log
,08-16 13:19:02.635   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-16 13:19:02.638  4194  4214 D BluetoothAdapterState: Current state: OFF, message: 0
,08-16 13:19:02.638  4194  4214 D BluetoothAdapterProperties: Setting state to 14
,08-16 13:19:02.638  4194  4214 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-16 13:19:02.639  4194  4214 D BluetoothBondStateMachine: make
,08-16 13:19:02.640  4194  4219 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 13:19:02.642  4194  4214 I BluetoothAdapterState: Entering PendingCommandState
,08-16 13:19:02.643  4194  4194 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-16 13:19:02.645  4194  4194 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b66a9c9
,08-16 13:19:02.645  4194  4194 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 13:19:02.646  4194  4194 D BtGatt.GattService: Received start request. Starting profile...
,08-16 13:19:02.646  4194  4194 D BtGatt.GattService: start()
08-16 13:19:02.646  4194  4194 I bt_bluedroid: get_profile_interface gatt
08-16 13:19:02.646  4194  4194 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b66a9c9
,08-16 13:19:02.647  4194  4194 D BtGatt.AdvertiseManager: advertise manager created
,08-16 13:19:02.650  4194  4194 V BluetoothAdapterState: isTurningOff()=false
08-16 13:19:02.650  4194  4194 V BluetoothAdapterState: isTurningOn()=false
08-16 13:19:02.650  4194  4194 V BluetoothAdapterState: isBleTurningOn()=true
,08-16 13:19:02.650  4194  4194 V BluetoothAdapterState: isBleTurningOff()=false
08-16 13:19:02.651  4194  4214 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-16 13:19:02.651  4194  4214 I bt_bluedroid: enable
,08-16 13:19:02.651  4194  4215 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-16 13:19:02.652  4194  4215 I bt_hci  : start_up
,08-16 13:19:02.656  4194  4215 I bt_vendor: alloc value 0xb3a28189
,08-16 13:19:02.656  4194  4215 I bt_vendor: init
08-16 13:19:02.657  4194  4215 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-16 13:19:02.657  4194  4215 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-16 13:19:02.766  4194  4215 D bt_hci  : start_up starting async portion
,08-16 13:19:02.766  4194  4222 I bt_hci  : event_finish_startup
,08-16 13:19:02.767  4194  4222 I bt_hci_h4: hal_open
08-16 13:19:02.768  4194  4222 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-16 13:19:02.776  4194  4222 I bt_userial_vendor: device fd = 51 open
,08-16 13:19:02.808  4194  4222 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 13:19:02.847   282   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-16 13:19:02.848  4194  4222 D bt_hwcfg: Chipset BCM4354A2
08-16 13:19:02.849  4194  4222 D bt_hwcfg: Target name = [BCM4354A2]
,08-16 13:19:02.849  4194  4222 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-16 13:19:02.850   282   282 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-16 13:19:02.857   875  1330 D SurfaceControl: Excessive delay in setPowerMode(): 256ms
,08-16 13:19:02.863   875   895 I DreamManagerService: Entering dreamland.
,08-16 13:19:02.864   875   895 I PowerManagerService: Dozing...
,08-16 13:19:02.864   875   890 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-16 13:19:02.906   376  1277 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-16 13:19:02.906   376  1277 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-16 13:19:02.912   875  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 13:19:02.915   875  1306 E native  : do suspend false
,08-16 13:19:02.916  1906  4225 D NfcService: Discovery configuration equal, not updating.
,08-16 13:19:02.934   875  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 13:19:02.939   875  1306 E native  : do suspend true
,08-16 13:19:03.050   376   376 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-16 13:19:03.050   376   376 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-16 13:19:03.264  1549  2120 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-16 13:19:03.493  4194  4222 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-16 13:19:03.495  4194  4222 D bt_hwcfg: Settlement delay -- 100 ms
08-16 13:19:03.495  4194  4222 I bt_hwcfg: Setting fw settlement delay to 100 
,08-16 13:19:03.613  4194  4222 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 13:19:03.615  4194  4222 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-16 13:19:03.643  4194  4222 I bt_hwcfg: vendor lib fwcfg completed
,08-16 13:19:03.643  4194  4222 I bt_vendor: firmware callback
,08-16 13:19:03.643  4194  4222 I bt_hci  : firmware_config_callback
,08-16 13:19:03.658  4194  4229 I bt_btu  : btu_task pending for preload complete event
,08-16 13:19:03.659  4194  4229 I bt_btu_task: Bluetooth chip preload is complete
08-16 13:19:03.659  4194  4229 I bt_btu  : btu_task received preload complete event
,08-16 13:19:03.671  4194  4229 I         : BTE_InitTraceLevels -- TRC_HCI
,08-16 13:19:03.671  4194  4229 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-16 13:19:03.671  4194  4229 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-16 13:19:03.672  4194  4229 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-16 13:19:03.672  4194  4229 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-16 13:19:03.672  4194  4229 I         : BTE_InitTraceLevels -- TRC_A2D
,08-16 13:19:03.674  4194  4229 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 13:19:03.674  4194  4229 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 13:19:03.675  4194  4229 I         : BTE_InitTraceLevels -- TRC_GAP
,08-16 13:19:03.676  4194  4229 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 13:19:03.677  4194  4229 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 13:19:03.678  4194  4229 I         : BTE_InitTraceLevels -- TRC_GATT
,08-16 13:19:03.678  4194  4229 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 13:19:03.678  4194  4229 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 13:19:03.679  4194  4229 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 13:19:03.811  4194  4229 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39a5d9d
,08-16 13:19:03.811  4194  4229 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39a5d9d 
,08-16 13:19:03.825  4194  4218 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-16 13:19:03.827  4194  4218 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000,
08-16 13:19:03.828  4194  4218 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 13:19:03.833  4194  4218 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 13:19:03.837  4194  4218 D BluetoothAdapterProperties: Scan Mode:20
,08-16 13:19:03.837  4194  4218 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 13:19:03.837  4194  4218 D bt_hci  : do_postload posting postload work item
08-16 13:19:03.838  4194  4222 I bt_hci  : event_postload
,08-16 13:19:03.838  4194  4222 I bt_vendor: sco_config_cb
08-16 13:19:03.838  4194  4222 I bt_hci  : sco_config_callback postload finished.
,08-16 13:19:03.839  4194  4218 D bt_bte_conf: Device ID record 1 : primary
,08-16 13:19:03.839  4194  4218 D bt_bte_conf:   vendorId            = 000f
08-16 13:19:03.839  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:19:03.840  4194  4218 D bt_bte_conf:   vendorIdSource      = 0001
,08-16 13:19:03.840  4194  4218 D bt_bte_conf:   product             = 1200
08-16 13:19:03.840  4194  4218 D bt_bte_conf:   version             = 1436
08-16 13:19:03.840  4194  4218 D bt_bte_conf:   clientExecutableURL = 
,08-16 13:19:03.840  4194  4218 D bt_bte_conf:   serviceDescription  = 
08-16 13:19:03.840  4194  4218 D bt_bte_conf:   documentationURL    = 
08-16 13:19:03.840  4194  4218 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-16 13:19:03.840  4194  4215 D bt_stack_manager: event_start_up_stack finished
08-16 13:19:03.841  4194  4214 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-16 13:19:03.841  4194  4214 D BluetoothAdapterProperties: Setting state to 15
08-16 13:19:03.841  4194  4214 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-16 13:19:03.842  4194  4214 I BluetoothAdapterState: Entering BleOnState
08-16 13:19:03.845  4194  4222 I bt_vendor: low_power_mode_cb
,08-16 13:19:03.849  4194  4214 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-16 13:19:03.849  4194  4214 D BluetoothAdapterProperties: Setting state to 11
,08-16 13:19:03.849  4194  4214 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-16 13:19:03.861  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:19:03.863  4194  4194 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b66a9c9
,08-16 13:19:03.868  4194  4194 D HeadsetService: Received start request. Starting profile...
,08-16 13:19:03.874  4194  4214 I BluetoothAdapterState: Entering PendingCommandState
,08-16 13:19:03.877  4194  4194 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-16 13:19:03.878  4194  4194 D HeadsetStateMachine: make
,08-16 13:19:03.886  4194  4194 D HeadsetStateMachine: max_hf_connections = 1
,08-16 13:19:03.886  4194  4194 I bt_bluedroid: get_profile_interface handsfree
,08-16 13:19:03.886  4194  4218 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-16 13:19:03.887  4194  4218 E bt_btif : btif_hf_upstreams_evt: Invalid index -1,
,08-16 13:19:03.891  4194  4194 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b66a9c9
,08-16 13:19:03.892  4194  4194 D A2dpService: Received start request. Starting profile...
,08-16 13:19:03.892  4194  4194 I BluetoothAvrcpServiceJni: classInitNative: succeeds,
,08-16 13:19:03.893  4194  4194 I bt_bluedroid: get_profile_interface avrcp
,08-16 13:19:03.900  4194  4194 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-16 13:19:03.900  4194  4194 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 13:19:03.900  4194  4194 D A2dpStateMachine: make
,08-16 13:19:03.902  4194  4194 I bt_bluedroid: get_profile_interface a2dp
,08-16 13:19:03.903  4194  4218 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-16 13:19:03.904  4194  4238 D A2dpStateMachine: Enter Disconnected: -2
,08-16 13:19:03.905  4194  4194 I BluetoothHidServiceJni: classInitNative: succeeds
,08-16 13:19:03.906  4194  4194 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b66a9c9
,08-16 13:19:03.907  4194  4194 D HidService: Received start request. Starting profile...
,08-16 13:19:03.907  4194  4194 I bt_bluedroid: get_profile_interface hidhost
08-16 13:19:03.907  4194  4194 D HidService: setHidService(): set to: null
,08-16 13:19:03.908  4194  4218 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39873e5
08-16 13:19:03.908  4194  4218 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-16 13:19:03.908  4194  4194 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 13:19:03.909  4194  4194 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b66a9c9
,08-16 13:19:03.910  4194  4194 D HealthService: Received start request. Starting profile...
,08-16 13:19:03.912  4194  4194 I bt_bluedroid: get_profile_interface health
,08-16 13:19:03.914  4194  4194 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-16 13:19:03.915  4194  4194 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b66a9c9
08-16 13:19:03.915  4194  4194 D PanService: Received start request. Starting profile...
08-16 13:19:03.916  4194  4194 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-16 13:19:03.916  4194  4194 I bt_bluedroid: get_profile_interface pan
08-16 13:19:03.916  1549  1549 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 13:19:03.917  4194  4218 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-16 13:19:03.921  4194  4194 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b66a9c9
,08-16 13:19:03.922  4194  4194 D BluetoothMapService: Received start request. Starting profile...
08-16 13:19:03.922  4194  4194 D BluetoothMapService: start()
08-16 13:19:03.924  4194  4194 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-16 13:19:03.925  4194  4194 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-16 13:19:03.926  4194  4194 D BluetoothMapAppObserver: createReceiver()
,08-16 13:19:03.928  4194  4194 D BluetoothMapAppObserver: initObservers()
,08-16 13:19:03.928  4194  4194 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-16 13:19:03.941  4194  4236 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-16 13:19:03.942  4194  4194 V BluetoothAdapterState: isTurningOff()=false
08-16 13:19:03.942  4194  4194 V BluetoothAdapterState: isTurningOn()=true
,08-16 13:19:03.943  4194  4194 V BluetoothAdapterState: isBleTurningOn()=false
08-16 13:19:03.943  4194  4194 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 13:19:03.946  4194  4194 V BluetoothAdapterState: isTurningOff()=false
,08-16 13:19:03.946  4194  4194 V BluetoothAdapterState: isTurningOn()=true
08-16 13:19:03.946  4194  4194 V BluetoothAdapterState: isBleTurningOn()=false
08-16 13:19:03.946  4194  4194 V BluetoothAdapterState: isBleTurningOff()=false
08-16 13:19:03.946  4194  4194 V BluetoothAdapterState: isTurningOff()=false
,08-16 13:19:03.946  4194  4194 V BluetoothAdapterState: isTurningOn()=true
08-16 13:19:03.947  4194  4194 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 13:19:03.947  4194  4194 V BluetoothAdapterState: isBleTurningOff()=false
08-16 13:19:03.947  4194  4194 V BluetoothAdapterState: isTurningOff()=false
08-16 13:19:03.947  4194  4194 V BluetoothAdapterState: isTurningOn()=true
08-16 13:19:03.947  4194  4194 V BluetoothAdapterState: isBleTurningOn()=false
08-16 13:19:03.947  4194  4194 V BluetoothAdapterState: isBleTurningOff()=false
08-16 13:19:03.948  4194  4194 V BluetoothAdapterState: isTurningOff()=false
08-16 13:19:03.948  4194  4194 V BluetoothAdapterState: isTurningOn()=true
08-16 13:19:03.948  4194  4194 V BluetoothAdapterState: isBleTurningOn()=false
08-16 13:19:03.948  4194  4194 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 13:19:03.949  4194  4194 V BluetoothAdapterState: isTurningOff()=false
08-16 13:19:03.949  4194  4194 V BluetoothAdapterState: isTurningOn()=true
08-16 13:19:03.949  4194  4194 V BluetoothAdapterState: isBleTurningOn()=false
08-16 13:19:03.949  4194  4194 V BluetoothAdapterState: isBleTurningOff()=false
08-16 13:19:03.951  4194  4214 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-16 13:19:03.951  4194  4214 D BluetoothAdapterProperties: ScanMode =  20
08-16 13:19:03.951  4194  4214 D BluetoothAdapterProperties: State =  11
,08-16 13:19:03.951  4194  4214 D BluetoothAdapterProperties: Setting state to 12
,08-16 13:19:03.951  4194  4214 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 13:19:03.952   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 13:19:03.952  4194  4214 I BluetoothAdapterState: Entering OnState
08-16 13:19:03.953  1361  1374 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 13:19:03.954  4194  4218 D BluetoothAdapterProperties: Scan Mode:21
08-16 13:19:03.954  4194  4218 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 13:19:03.955  3854  3864 D BluetoothMap: onBluetoothStateChange: up=true
08-16 13:19:03.955   875   875 D BluetoothA2dp: Proxy object connected
08-16 13:19:03.958  4194  4194 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-16 13:19:03.960  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:19:03.960  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:19:03.960  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:19:03.960  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:19:03.960  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:19:03.960  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:19:03.960  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:19:03.960  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 13:19:03.964  3854  4213 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 13:19:03.965  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 13:19:03.966  4194  4194 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-16 13:19:03.968  4194  4194 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 13:19:03.969  3854  3865 D BluetoothPan: onBluetoothStateChange on: true
,08-16 13:19:03.972  4194  4194 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 13:19:03.973  1361  1718 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 13:19:03.974  4194  4194 D ObexServerSockets: Succeed to create listening sockets 
,08-16 13:19:03.975  4194  4194 D ObexServerSockets0: startAccept()
,08-16 13:19:03.975  4194  4194 D ObexServerSockets0: prepareForNewConnect()
08-16 13:19:03.975  1361  1361 D BluetoothA2dp: Proxy object connected
,08-16 13:19:03.975  3854  3864 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 13:19:03.977  3854  3854 D BluetoothA2dp: Proxy object connected
08-16 13:19:03.977   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 13:19:03.978  1361  1375 D BluetoothMap: onBluetoothStateChange: up=true
08-16 13:19:03.979  4194  4194 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-16 13:19:03.979   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 13:19:03.980  1361  1718 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 13:19:03.980  4194  4194 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-16 13:19:03.981  4194  4244 D ObexServerSockets0: Accepting socket connection...
,08-16 13:19:03.982  1361  4210 D BluetoothPan: onBluetoothStateChange on: true
,08-16 13:19:03.982  1361  1361 D BluetoothMap: Proxy object connected
,08-16 13:19:03.982  1361  1361 D MapProfile: Bluetooth service connected
08-16 13:19:03.982  1361  1361 D BluetoothMap: getConnectedDevices()
,08-16 13:19:03.984  3854  3864 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 13:19:03.985  3854  3865 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 13:19:03.986  1361  1361 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 13:19:03.986  1361  1361 D PanProfile: Bluetooth service connected
08-16 13:19:03.987  1919  1935 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 13:19:03.987  4194  4245 D ObexServerSockets0: Accepting socket connection...
,08-16 13:19:03.988  1361  1374 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 13:19:03.989  1361  1361 D BluetoothInputDevice: Proxy object connected
,08-16 13:19:03.989   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 13:19:03.989  1361  1361 D HidProfile: Bluetooth service connected
08-16 13:19:03.991  3854  3854 D BluetoothMap: Proxy object connected
08-16 13:19:03.991  3854  3854 D MapProfile: Bluetooth service connected
08-16 13:19:03.992  3854  3854 D BluetoothMap: getConnectedDevices()
,08-16 13:19:03.992   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
08-16 13:19:03.993  4194  4194 D BluetoothMapService: onReceive
08-16 13:19:03.993  4194  4194 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:19:03.994  4194  4194 D BluetoothMapService: STATE_ON
08-16 13:19:03.995  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:19:03.996  3854  3854 D BluetoothInputDevice: Proxy object connected
08-16 13:19:03.996  3854  3854 D HidProfile: Bluetooth service connected
08-16 13:19:03.998  3854  3854 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 13:19:03.998  3854  3854 D PanProfile: Bluetooth service connected
,08-16 13:19:04.004  3854  3854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 13:19:04.013  3854  3854 D DockEventReceiver: finishStartingService: stopping service
,08-16 13:19:04.013  1549  1549 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 13:19:04.032  1361  1361 D BluetoothPbap: Proxy object connected
,08-16 13:19:04.032  3854  3854 D BluetoothPbap: Proxy object connected
08-16 13:19:04.032  1361  1361 D PbapServerProfile: Bluetooth service connected
,08-16 13:19:04.032  3854  3854 D PbapServerProfile: Bluetooth service connected
08-16 13:19:04.032  4194  4194 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-16 13:19:04.032  4194  4194 D ObexServerSockets0: prepareForNewConnect()
,08-16 13:19:04.040  4194  4250 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 13:19:04.058   875   875 D BluetoothHeadset: Proxy object connected
,08-16 13:19:04.058  4194  4254 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 13:19:04.059  1919  1932 D BluetoothHeadset: Proxy object connected
,08-16 13:19:04.059   875   875 D BluetoothHeadset: Proxy object connected
08-16 13:19:04.059  1361  1374 D BluetoothHeadset: Proxy object connected
,08-16 13:19:04.059  3854  3864 D BluetoothHeadset: Proxy object connected
08-16 13:19:04.059  1361  1361 D HeadsetProfile: Bluetooth service connected
08-16 13:19:04.060   875   875 D BluetoothHeadset: Proxy object connected
08-16 13:19:04.060  4194  4254 I BtOppRfcommListener: Accept thread started.
,08-16 13:19:04.060  3854  3854 D HeadsetProfile: Bluetooth service connected
,08-16 13:19:04.077   875   892 D BluetoothHeadset: Proxy object connected
,08-16 13:19:04.079   875   892 D BluetoothHeadset: Proxy object connected
,08-16 13:19:04.086  3854  3865 D BluetoothHeadset: Proxy object connected
,08-16 13:19:04.086  3854  3854 D HeadsetProfile: Bluetooth service connected
,08-16 13:19:04.087  1919  2212 D BluetoothHeadset: Proxy object connected
,08-16 13:19:04.089   875   892 D BluetoothHeadset: Proxy object connected
,08-16 13:19:04.334  3784  3835 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:19:04.334  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:19:04.334  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:19:04.334  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:19:04.334  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:19:04.334  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:19:04.334  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:19:04.334  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 13:19:04.341  3784  3835 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 13:19:04.344  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 13:19:04.344  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3d54ea8 added. We now have 8 listener(s)
,08-16 13:19:04.345  3784  3835 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 13:19:04.350   875  1699 D WifiService: setWifiEnabled: false pid=3784, uid=10000
,08-16 13:19:04.350   875  1699 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 13:19:04.362  3784  3835 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:19:04.363   875  1984 D WifiService: setWifiEnabled: true pid=3784, uid=10000
,08-16 13:19:04.364   875  1984 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 13:19:04.376   875  1306 D WifiConfigStore: Loading config and enabling all networks 
,08-16 13:19:04.387  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:19:04.387  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:19:04.387  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:19:04.387  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:19:04.387  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:19:04.387  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:19:04.387  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:19:04.387  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 13:19:04.391  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 13:19:04.409   875  1306 D WifiConfigStore: loaded 0 passpoint configs
,08-16 13:19:04.410   875  1306 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-16 13:19:04.411   875  1306 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-16 13:19:04.412   875  1306 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-16 13:19:04.412   875  1306 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-16 13:19:04.412   875  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-16 13:19:04.412   875  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-16 13:19:04.426   372   874 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-16 13:19:04.427   875  1306 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.04 rxSuccessRate=0.10 delta 1000 -> 1000
,08-16 13:19:04.427   875  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 13:19:04.427   372   874 D CommandListener: Setting iface cfg
08-16 13:19:04.428   875  1305 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
,08-16 13:19:04.428   875  1305 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-16 13:19:04.443   875  1306 E native  : do suspend true
08-16 13:19:04.443   875  1305 D WifiNative-HAL: p2pGetDeviceAddress
,08-16 13:19:04.450   875  1305 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-16 13:19:04.460   875  1306 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-16 13:19:04.460   875  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 13:19:04.478   875  1306 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-16 13:19:04.552   875  1306 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-16 13:19:04.556  1457  1457 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-16 13:19:04.995  1457  1457 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 13:19:05.035  1457  1457 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-16 13:19:05.035  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-16 13:19:05.043   875  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 13:19:05.051   875  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 13:19:05.052   875  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-16 13:19:05.052   875  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 13:19:05.079   875  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 13:19:05.100   372   874 D CommandListener: Setting iface cfg
,08-16 13:19:05.104   875  1306 D WifiStateMachine: Start Dhcp Watchdog 3
,08-16 13:19:05.111   875  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-16 13:19:05.127   875  4264 D DhcpClient: Receive thread started
,08-16 13:19:05.215   875  1306 E native  : do suspend false
,08-16 13:19:05.236   875  1873 D DhcpClient: Broadcasting DHCPDISCOVER
,08-16 13:19:05.249   875  4264 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-16 13:19:05.252   875  1873 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-16 13:19:05.257   875  1873 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-16 13:19:05.270   875  4264 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-16 13:19:05.272   875  1873 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-16 13:19:05.279   372   874 D CommandListener: Setting iface cfg
,08-16 13:19:05.290   875  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-16 13:19:05.293   875  1873 D DhcpClient: Scheduling renewal in 86399s
,08-16 13:19:05.293   875  1306 E native  : do suspend true
,08-16 13:19:05.315   875  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-16 13:19:05.318   875  1306 D WifiConfigStore: No blacklist allowed without epno enabled
,08-16 13:19:05.319   875  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-16 13:19:05.321   875  1308 D ConnectivityService: Adding iface wlan0 to network 102
,08-16 13:19:05.333   875  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 13:19:05.380   875  1308 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-16 13:19:05.381   875  1308 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-16 13:19:05.385  3784  3835 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:19:05.385  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:19:05.385  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:19:05.385  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:19:05.385  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:19:05.385  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:19:05.385  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:19:05.385  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 13:19:05.386   875  1308 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-16 13:19:05.388   875  1308 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-16 13:19:05.389   875  1308 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-16 13:19:05.394  3784  3835 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 13:19:05.400   875  1308 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-16 13:19:05.405  3784  3835 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-16 13:19:05.405   875  1308 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-16 13:19:05.405   875  1308 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-16 13:19:05.405   875  1306 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-16 13:19:05.406   875  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 13:19:05.406   875  1308 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-16 13:19:05.406   875  1308 D ConnectivityService:    accepting network in place of null
08-16 13:19:05.406  3784  3835 D io.jxcore.node.LifeCycleMonitor: onActivityResumed,
08-16 13:19:05.408   875  1308 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 13:19:05.409  3784  3835 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f271985 Bundle[{}]
,08-16 13:19:05.410  3784  3835 I io.jxcore.node.LifeCycleMonitor: start: OK
08-16 13:19:05.410  3784  3835 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-16 13:19:05.411  3784  3835 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-16 13:19:05.411  3784  3835 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-16 13:19:05.412  3784  3835 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-16 13:19:05.412  3784  3835 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 13:19:05.416  3784  3835 I System.out: Running OutgoingSocketThread
,08-16 13:19:05.417   875  4263 D NetlinkSocketObserver: NeighborEvent{elapsedMs=153763, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 13:19:05.418  3784  4269 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 424),
,08-16 13:19:05.419  3784  4269 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 37881
08-16 13:19:05.419  3784  4269 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-16 13:19:05.441   372   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 13:19:05.479   372   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 13:19:05.483   875  1308 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-16 13:19:05.484   875  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 13:19:05.484   875  4261 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.46,2a00:1450:4001:816::200e
,08-16 13:19:05.487   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-16 13:19:05.492   875  1308 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-16 13:19:05.497  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:19:05.497  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:19:05.497  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:19:05.497  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:19:05.497  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:19:05.497  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:19:05.497  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:19:05.497  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:19:05.504  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 13:19:05.513  1726  1726 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 13:19:05.518  1726  1726 D SystemUpdateService: onCreate
,08-16 13:19:05.526  1726  1726 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 13:19:05.532  1726  4274 I SystemUpdateService: active receiver: enabled
,08-16 13:19:05.541  1726  4274 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 13:19:05.546  1726  4274 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-16 13:19:05.546  1726  4274 I SystemUpdateService: now status is 0 (complete)
08-16 13:19:05.546  1726  4274 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 13:19:05.546  1726  4274 I SystemUpdateService: file has been verified
08-16 13:19:05.546  1726  4274 I SystemUpdateService: OTA package size = 12249756
,08-16 13:19:05.550  1726  1726 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-16 13:19:05.556  1726  2436 I iu.UploadsManager: num queued entries: 0
,08-16 13:19:05.556  1726  2436 I iu.UploadsManager: num updated entries: 0
,08-16 13:19:05.564  1726  4274 I SystemUpdateService: showing system update notification
,08-16 13:19:05.567  1726  2436 I iu.SyncManager: NEXT; no task
,08-16 13:19:05.568   875  4261 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 11:19:05 GMT], X-Android-Received-Millis=[1471346345566], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471346345535]}
,08-16 13:19:05.569  1726  1726 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 13:19:05.570   875  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-16 13:19:05.570   875  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-16 13:19:05.571   875  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-16 13:19:05.571  1726  1726 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-16 13:19:05.573   875  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-16 13:19:05.575  3971  3971 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 13:19:05.585  1726  4277 I MDM     : [182] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-16 13:19:05.585  1726  4277 W BaseAppContext: Using Auth Proxy for data requests.
,08-16 13:19:05.586  3971  3971 D SprintDMHelper: simOperator: 
,08-16 13:19:05.586  3971  3971 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 13:19:05.590  1726  4277 V GoogleAuthProtoRequest: [182] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 13:19:05.607  1549  1549 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 13:19:05.617  1726  1726 D SystemUpdateService: onDestroy
,08-16 13:19:05.618  1549  1549 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 13:19:05.678  1549  4208 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-16 13:19:05.678  1549  4208 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-16 13:19:05.678  1549  4208 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 13:19:05.678  1549  4208 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 13:19:05.689  1726  4277 E MDM     : [182] SitrepService.a: Error sending sitrep.
,08-16 13:19:05.719  3932  4280 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-16 13:19:06.420  3784  3835 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 425)
,08-16 13:19:06.421  3784  3835 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 425)
,08-16 13:19:06.430  3784  3835 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 430)
,08-16 13:19:06.432  3784  3835 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-16 13:19:06.433  3784  3835 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 431)
,08-16 13:19:06.439  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 13:19:06.439  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db9ddc1 added. We now have 2 listener(s)
,08-16 13:19:06.441  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 13:19:06.441  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 13:19:06.441  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 13:19:06.441  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 13:19:06.441  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dfa6966 added. We now have 9 listener(s)
08-16 13:19:06.441  3784  3835 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 13:19:06.442  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 13:19:06.446  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 13:19:06.455  3784  3835 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:19:06.455  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:19:06.455  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:19:06.455  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:19:06.455  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:19:06.455  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:19:06.455  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:19:06.455  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 13:19:06.457  3784  3835 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 13:19:06.458  3784  3835 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 13:19:06.460  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 13:19:06.461  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@184ad54 added. We now have 3 listener(s)
08-16 13:19:06.462  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:19:06.465  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:19:06.470  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 13:19:06.470  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 13:19:06.471  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 13:19:06.472  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:19:06.472  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@54594fd added. We now have 10 listener(s)
,08-16 13:19:06.473  3784  3835 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 13:19:06.474  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 13:19:06.475  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 13:19:06.476  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 13:19:06.478  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:19:06.478  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:19:06.478  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:19:06.478  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 13:19:06.479  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db9ddc1 removed from the list
,08-16 13:19:06.479  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:19:06.479  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dfa6966 removed from the list
08-16 13:19:06.479  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 13:19:06.479  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:19:06.480  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:19:06.480  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 13:19:06.482  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 13:19:06.482  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:19:06.482  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:19:06.483  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dfa6966 not in the list
08-16 13:19:06.483  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:19:06.483  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:19:06.484   875  1308 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-16 13:19:06.485  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:19:06.485  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:19:06.486  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:19:06.486  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@54594fd removed from the list
08-16 13:19:06.486  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 13:19:06.486  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:19:06.486  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 13:19:06.487  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 13:19:06.487  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@184ad54 removed from the list
,08-16 13:19:06.488  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 13:19:06.489  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab3b5f2 added. We now have 2 listener(s)
,08-16 13:19:06.493  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 13:19:06.493  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 13:19:06.493  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 13:19:06.494  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:19:06.494  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b206443 added. We now have 9 listener(s)
08-16 13:19:06.494  3784  3835 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 13:19:06.495  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 13:19:06.501  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 13:19:06.508  3784  3835 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:19:06.508  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:19:06.508  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:19:06.508  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:19:06.508  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:19:06.508  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:19:06.508  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:19:06.508  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 13:19:06.511  3784  3835 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 13:19:06.512  3784  3835 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 13:19:06.512  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 13:19:06.512  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8db83f9 added. We now have 3 listener(s)
08-16 13:19:06.514  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 13:19:06.514  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 13:19:06.514  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 13:19:06.514  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 13:19:06.514  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3433f3e added. We now have 10 listener(s)
08-16 13:19:06.514  3784  3835 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 13:19:06.514  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 13:19:06.515  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 13:19:06.515  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-16 13:19:06.515  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:19:06.515  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 13:19:06.516  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:19:06.519  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:19:06.521  3784  3835 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 13:19:06.521  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 13:19:06.527  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 13:19:06.528  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 13:19:06.528  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 13:19:06.533  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 13:19:06.533  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 13:19:06.533  3784  3835 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 13:19:06.535  3784  3835 D BluetoothAdapter: STATE_ON
,08-16 13:19:06.539  4194  4205 D BtGatt.GattService: registerClient() - UUID=dc272a2c-cc51-4d0b-a365-983687962233
,08-16 13:19:06.541  4194  4218 D BtGatt.GattService: onClientRegistered() - UUID=dc272a2c-cc51-4d0b-a365-983687962233, clientIf=5
,08-16 13:19:06.542  3784  3795 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 13:19:06.543  4194  4235 D BtGatt.GattService: start scan with filters
,08-16 13:19:06.549  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 13:19:06.549  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 13:19:06.549  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-16 13:19:06.549  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-16 13:19:06.549  4194  4221 D BtGatt.ScanManager: handling starting scan
,08-16 13:19:06.551  4194  4221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b66a9c9
,08-16 13:19:06.554  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 13:19:06.554  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 13:19:06.554  3784  3784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 13:19:06.556  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 13:19:06.559  4194  4218 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 13:19:06.559  4194  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:19:06.561  4194  4221 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 13:19:06.561  3784  3835 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-16 13:19:06.562  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 13:19:06.562  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-16 13:19:06.562  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:19:06.562  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 13:19:06.562  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 13:19:06.562  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 13:19:06.562  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 13:19:06.563  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 13:19:06.563  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 13:19:06.563  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 13:19:06.565  3784  3835 D BluetoothAdapter: STATE_ON
08-16 13:19:06.566  4194  4235 D BtGatt.GattService: stopScan() - queue size =1
,08-16 13:19:06.567  4194  4246 D BtGatt.GattService: unregisterClient() - clientIf=5
08-16 13:19:06.567  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:19:06.568  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 13:19:06.568  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-16 13:19:06.568  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 13:19:06.568  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 13:19:06.570  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 13:19:06.570  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 13:19:06.570  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 13:19:06.570  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 13:19:06.572  4194  4218 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 13:19:06.572  4194  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 13:19:06.572  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:19:06.573  4194  4221 D BtGatt.ScanManager: Starting BLE batch scan
08-16 13:19:06.574  4194  4221 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 13:19:06.575  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 13:19:06.575  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 13:19:06.576  3784  3784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 13:19:06.580  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 13:19:06.581  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 13:19:06.581  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:19:06.581  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 13:19:06.581  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:19:06.581  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:19:06.582  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-16 13:19:06.582  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab3b5f2 removed from the list
,08-16 13:19:06.582  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:19:06.582  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b206443 removed from the list
08-16 13:19:06.582  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:19:06.583  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:19:06.584  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:19:06.584  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 13:19:06.586  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:19:06.586  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:19:06.586  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:19:06.586  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b206443 not in the list
,08-16 13:19:06.586  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:19:06.586  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 13:19:06.588  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:19:06.588  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:19:06.588  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:19:06.588  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3433f3e removed from the list
08-16 13:19:06.588  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:19:06.588  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:19:06.588  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 13:19:06.589  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 13:19:06.589  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8db83f9 removed from the list
,08-16 13:19:06.590  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 13:19:06.590  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b0114a added. We now have 2 listener(s)
,08-16 13:19:06.594  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 13:19:06.594  4194  4218 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 13:19:06.594  4194  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:19:06.594  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 13:19:06.595  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 13:19:06.595  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:19:06.595  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e7818bb added. We now have 9 listener(s)
,08-16 13:19:06.595  3784  3835 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 13:19:06.596  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 13:19:06.599  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 13:19:06.603  4194  4218 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 13:19:06.603  4194  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 13:19:06.606  3784  3835 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:19:06.606  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:19:06.606  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:19:06.606  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:19:06.606  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:19:06.606  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:19:06.606  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:19:06.606  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 13:19:06.609  3784  3835 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 13:19:06.609  3784  3835 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 13:19:06.609  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 13:19:06.610  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e54b931 added. We now have 3 listener(s)
,08-16 13:19:06.613  4194  4218 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
08-16 13:19:06.613  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 13:19:06.613  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:19:06.613  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 13:19:06.613  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 13:19:06.614  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:19:06.614  4194  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:19:06.614  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@765f816 added. We now have 10 listener(s)
08-16 13:19:06.614  3784  3835 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 13:19:06.614  4194  4221 D BtGatt.ScanManager: stopping BLe Batch
08-16 13:19:06.614  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 13:19:06.615  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 13:19:06.615  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 13:19:06.616  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-16 13:19:06.617  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:19:06.616  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:19:06.617  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 13:19:06.621  3784  3835 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 13:19:06.622  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 13:19:06.622  4194  4218 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 13:19:06.622  4194  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:19:06.623  4194  4221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 13:19:06.627  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 13:19:06.628  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 13:19:06.628  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 13:19:06.631  4194  4218 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 13:19:06.631  4194  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:19:06.632  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 13:19:06.632  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-16 13:19:06.633  3784  3835 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 13:19:06.634  3784  3835 D BluetoothAdapter: STATE_ON
,08-16 13:19:06.637  4194  4235 D BtGatt.GattService: registerClient() - UUID=bda9363d-189f-49f0-82d4-c291491ddccd
,08-16 13:19:06.637  4194  4218 D BtGatt.GattService: onClientRegistered() - UUID=bda9363d-189f-49f0-82d4-c291491ddccd, clientIf=5
08-16 13:19:06.637  3784  3998 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 13:19:06.638  4194  4204 D BtGatt.GattService: start scan with filters
,08-16 13:19:06.641  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 13:19:06.641  4194  4221 D BtGatt.ScanManager: handling starting scan
08-16 13:19:06.641  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 13:19:06.641  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 13:19:06.642  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 13:19:06.645  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 13:19:06.646  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 13:19:06.646  3784  3784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 13:19:06.649  4194  4218 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 13:19:06.649  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-16 13:19:06.649  4194  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 13:19:06.649  4194  4221 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 13:19:06.653  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 13:19:06.653  3784  3835 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-16 13:19:06.653  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:19:06.653  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 13:19:06.653  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:19:06.654  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:19:06.654  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:19:06.654  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 13:19:06.654  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 13:19:06.654  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b0114a removed from the list
08-16 13:19:06.654  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:19:06.654  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e7818bb removed from the list
08-16 13:19:06.655  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:19:06.655  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:19:06.655  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-16 13:19:06.656  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-16 13:19:06.656  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:19:06.656  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:19:06.657  4194  4218 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-16 13:19:06.657  4194  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:19:06.657  4194  4221 D BtGatt.ScanManager: Starting BLE batch scan
08-16 13:19:06.657  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:19:06.657  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:19:06.657  4194  4221 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-16 13:19:06.658  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:19:06.658  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e7818bb not in the list
08-16 13:19:06.658  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 13:19:06.658  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 13:19:06.658  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 13:19:06.658  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 13:19:06.658  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 13:19:06.659  3784  3835 D BluetoothAdapter: STATE_ON
08-16 13:19:06.660  4194  4246 D BtGatt.GattService: stopScan() - queue size =1
08-16 13:19:06.661  4194  4243 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 13:19:06.661  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:19:06.661  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 13:19:06.662  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-16 13:19:06.662  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 13:19:06.662  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 13:19:06.663  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 13:19:06.663  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 13:19:06.663  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 13:19:06.664  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 13:19:06.664  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 13:19:06.666  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 13:19:06.666  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:19:06.666  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:19:06.666  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 13:19:06.666  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@765f816 removed from the list
,08-16 13:19:06.666  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 13:19:06.666  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 13:19:06.667  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:19:06.667  3784  3784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 13:19:06.667  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:19:06.667  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 13:19:06.667  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e54b931 removed from the list
,08-16 13:19:06.668  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 13:19:06.668  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ec17fa2 added. We now have 2 listener(s)
,08-16 13:19:06.671  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 13:19:06.671  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 13:19:06.671  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 13:19:06.671  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:19:06.671  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@692e433 added. We now have 9 listener(s)
08-16 13:19:06.671  3784  3835 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 13:19:06.672  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 13:19:06.675  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 13:19:06.677  4194  4218 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 13:19:06.677  4194  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 13:19:06.681  3784  3835 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:19:06.681  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:19:06.681  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:19:06.681  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:19:06.681  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:19:06.681  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:19:06.681  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:19:06.681  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 13:19:06.684  4194  4218 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 13:19:06.684  4194  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:19:06.684  3784  3835 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 13:19:06.685  3784  3835 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 13:19:06.686  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 13:19:06.686  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a85d69 added. We now have 3 listener(s)
,08-16 13:19:06.688  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:19:06.690  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:19:06.692  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 13:19:06.692  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 13:19:06.692  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 13:19:06.693  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 13:19:06.693  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95bf3ee added. We now have 10 listener(s)
,08-16 13:19:06.693  3784  3835 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 13:19:06.694  4194  4218 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 13:19:06.694  4194  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 13:19:06.694  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 13:19:06.694  4194  4221 D BtGatt.ScanManager: stopping BLe Batch
08-16 13:19:06.694  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 13:19:06.694  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-16 13:19:06.695  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:19:06.695  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 13:19:06.701  3784  3835 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 13:19:06.701  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 13:19:06.702  4194  4218 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 13:19:06.702  4194  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:19:06.702  4194  4221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 13:19:06.706  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 13:19:06.707  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 13:19:06.707  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 13:19:06.710  4194  4218 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 13:19:06.710  4194  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 13:19:06.712  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 13:19:06.712  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 13:19:06.712  3784  3835 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 13:19:06.713  3784  3835 D BluetoothAdapter: STATE_ON
,08-16 13:19:06.716  4194  4204 D BtGatt.GattService: registerClient() - UUID=9e1781e0-c004-4dca-a787-ecdaa363015f
,08-16 13:19:06.716  4194  4218 D BtGatt.GattService: onClientRegistered() - UUID=9e1781e0-c004-4dca-a787-ecdaa363015f, clientIf=5
08-16 13:19:06.716  3784  3998 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 13:19:06.717  4194  4243 D BtGatt.GattService: start scan with filters
,08-16 13:19:06.721  4194  4221 D BtGatt.ScanManager: handling starting scan
,08-16 13:19:06.721  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 13:19:06.721  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 13:19:06.722  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-16 13:19:06.722  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 13:19:06.726  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 13:19:06.726  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 13:19:06.726  3784  3784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 13:19:06.729  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 13:19:06.730  4194  4218 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 13:19:06.730  4194  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 13:19:06.730  4194  4221 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 13:19:06.737  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:19:06.737  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 13:19:06.737  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:19:06.737  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:19:06.738  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:19:06.738  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 13:19:06.738  4194  4218 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 13:19:06.738  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-16 13:19:06.738  4194  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 13:19:06.738  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ec17fa2 removed from the list
08-16 13:19:06.738  4194  4221 D BtGatt.ScanManager: Starting BLE batch scan
08-16 13:19:06.738  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:19:06.738  4194  4221 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-16 13:19:06.739  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@692e433 removed from the list
08-16 13:19:06.739  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 13:19:06.739  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:19:06.740  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-16 13:19:06.740  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-16 13:19:06.740  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:19:06.740  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:19:06.742  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:19:06.742  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:19:06.742  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:19:06.742  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@692e433 not in the list
08-16 13:19:06.743  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 13:19:06.743  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 13:19:06.743  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 13:19:06.743  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 13:19:06.743  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 13:19:06.745  3784  3835 D BluetoothAdapter: STATE_ON
08-16 13:19:06.746  4194  4204 D BtGatt.GattService: stopScan() - queue size =1
08-16 13:19:06.747  4194  4243 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 13:19:06.747  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:19:06.748  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 13:19:06.748  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-16 13:19:06.748  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 13:19:06.748  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 13:19:06.749  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 13:19:06.750  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 13:19:06.750  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 13:19:06.750  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 13:19:06.751  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 13:19:06.753  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 13:19:06.753  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 13:19:06.753  3784  3784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 13:19:06.753  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 13:19:06.754  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 13:19:06.754  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:19:06.754  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95bf3ee removed from the list
08-16 13:19:06.754  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
,08-16 13:19:06.754  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:19:06.754  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:19:06.754  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-16 13:19:06.754  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a85d69 removed from the list
08-16 13:19:06.755  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 13:19:06.756  4194  4218 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 13:19:06.756  4194  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 13:19:06.755  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1760fa added. We now have 2 listener(s)
08-16 13:19:06.759  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 13:19:06.759  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 13:19:06.759  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 13:19:06.759  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 13:19:06.759  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7dca6ab added. We now have 9 listener(s)
08-16 13:19:06.759  3784  3835 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 13:19:06.760  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 13:19:06.763  4194  4218 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 13:19:06.763  4194  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 13:19:06.763  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 13:19:06.770  3784  3835 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:19:06.770  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:19:06.770  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:19:06.770  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:19:06.770  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:19:06.770  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:19:06.770  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:19:06.770  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 13:19:06.772  3784  3835 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 13:19:06.772  4194  4218 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 13:19:06.772  4194  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 13:19:06.773  3784  3835 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 13:19:06.773  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 13:19:06.773  4194  4221 D BtGatt.ScanManager: stopping BLe Batch
,08-16 13:19:06.773  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d550a1 added. We now have 3 listener(s)
08-16 13:19:06.776  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 13:19:06.776  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:19:06.776  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 13:19:06.776  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 13:19:06.777  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 13:19:06.777  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ea92c6 added. We now have 10 listener(s)
08-16 13:19:06.777  3784  3835 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 13:19:06.777  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:19:06.777  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 13:19:06.777  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 13:19:06.778  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:19:06.778  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:19:06.778  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:19:06.778  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 13:19:06.778  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1760fa removed from the list
08-16 13:19:06.778  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:19:06.778  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7dca6ab removed from the list
,08-16 13:19:06.779  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:19:06.779  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:19:06.779  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 13:19:06.780  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:19:06.780  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 13:19:06.781  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:19:06.781  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 13:19:06.781  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:19:06.781  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7dca6ab not in the list
08-16 13:19:06.781  4194  4218 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 13:19:06.781  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:19:06.781  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 13:19:06.781  4194  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:19:06.782  4194  4221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-16 13:19:06.785  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:19:06.786  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 13:19:06.786  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:19:06.786  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ea92c6 removed from the list
08-16 13:19:06.786  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:19:06.786  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:19:06.786  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 13:19:06.786  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 13:19:06.786  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d550a1 removed from the list
08-16 13:19:06.787  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-16 13:19:06.787  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-16 13:19:06.787  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-16 13:19:06.788  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 13:19:06.788  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-16 13:19:06.788  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 13:19:06.795  3784  4286 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 438, name: My test thread name)
,08-16 13:19:06.795  3784  4286 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 438, thread name: My test thread name)
,08-16 13:19:06.795  3784  4286 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 438, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-16 13:19:06.796  4194  4218 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 13:19:06.797  4194  4218 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:19:06.797  3784  4287 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 440, name: My test thread name)
,08-16 13:19:06.798  3784  4287 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 440, thread name: My test thread name)
08-16 13:19:06.798  3784  4287 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 440, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-16 13:19:06.800  3784  3835 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-16 13:19:06.800  3784  3835 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-16 13:19:06.800  3784  3835 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-16 13:19:06.800  3784  3835 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,08-16 13:19:06.800  3784  3835 D com.test.thalitest.ThaliTestRunner: Total duration: 23015 ms
,08-16 13:19:06.802  3784  3835 I jxcore-log: Total number of executed tests:  80
08-16 13:19:06.802  3784  3835 I jxcore-log: 
,08-16 13:19:06.803  3784  3835 I jxcore-log: Number of passed tests:  80
08-16 13:19:06.803  3784  3835 I jxcore-log: 
,08-16 13:19:06.803  3784  3835 I jxcore-log: Number of failed tests:  0
08-16 13:19:06.803  3784  3835 I jxcore-log: 
08-16 13:19:06.803  3784  3835 I jxcore-log: Number of ignored tests:  0
08-16 13:19:06.803  3784  3835 I jxcore-log: 
,08-16 13:19:06.803  3784  3835 I jxcore-log: Total duration:  23015
08-16 13:19:06.803  3784  3835 I jxcore-log: 
08-16 13:19:06.804  3784  3835 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-16 13:19:06.804  3784  3835 I jxcore-log: ,
08-16 13:19:06.808  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:19:06.808  3784  3835 I jxcore-log: 
08-16 13:19:06.811  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:19:06.811  3784  3835 I jxcore-log: 
08-16 13:19:06.812  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:19:06.812  3784  3835 I jxcore-log: 
08-16 13:19:06.813  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:19:06.813  3784  3835 I jxcore-log: 
08-16 13:19:06.814  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:19:06.814  3784  3835 I jxcore-log: 
08-16 13:19:06.816  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:19:06.816  3784  3835 I jxcore-log: 
08-16 13:19:06.816  3784  3784 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-16 13:19:06.819  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:19:06.819  3784  3835 I jxcore-log: 
08-16 13:19:06.821  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 13:19:06.821  3784  3835 I jxcore-log: 
08-16 13:19:06.822  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 13:19:06.822  3784  3835 I jxcore-log: 
08-16 13:19:06.823  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 13:19:06.823  3784  3835 I jxcore-log: 
,08-16 13:19:06.825  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 13:19:06.825  3784  3835 I jxcore-log: 
,08-16 13:19:06.826  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 13:19:06.826  3784  3835 I jxcore-log: 
,08-16 13:19:06.827  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:19:06.827  3784  3835 I jxcore-log: 
,08-16 13:19:06.828  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:19:06.828  3784  3835 I jxcore-log: 
,08-16 13:19:06.829  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 13:19:06.829  3784  3835 I jxcore-log: 
,08-16 13:19:06.830  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 13:19:06.830  3784  3835 I jxcore-log: 
,08-16 13:19:06.831  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 13:19:06.831  3784  3835 I jxcore-log: 
,08-16 13:19:06.832  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 13:19:06.832  3784  3835 I jxcore-log: 
,08-16 13:19:06.832  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 13:19:06.832  3784  3835 I jxcore-log: 
,08-16 13:19:06.833  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
08-16 13:19:06.833  3784  3835 I jxcore-log: 
,08-16 13:19:06.834  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 13:19:06.834  3784  3835 I jxcore-log: 
,08-16 13:19:06.835  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 13:19:06.835  3784  3835 I jxcore-log: 
,08-16 13:19:06.836  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 13:19:06.836  3784  3835 I jxcore-log: 
,08-16 13:19:06.838  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 13:19:06.838  3784  3835 I jxcore-log: 
,08-16 13:19:06.838  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:19:06.838  3784  3835 I jxcore-log: 
,08-16 13:19:06.839  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
08-16 13:19:06.839  3784  3835 I jxcore-log: 
,08-16 13:19:06.840  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:19:06.840  3784  3835 I jxcore-log: 
,08-16 13:19:06.840  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:19:06.840  3784  3835 I jxcore-log: 
08-16 13:19:06.841  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:19:06.841  3784  3835 I jxcore-log: 
,08-16 13:19:06.841  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,08-16 13:19:06.841  3784  3835 I jxcore-log: 
,08-16 13:19:07.020  2102  2634 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-16 13:19:07.076  3784  3784 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 13:19:07.080  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 13:19:07.080  3784  3835 I jxcore-log: 
,08-16 13:19:07.168  3784  3784 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 13:19:07.171  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 13:19:07.171  3784  3835 I jxcore-log: 
,08-16 13:19:07.255  3784  3784 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 13:19:07.258  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 13:19:07.258  3784  3835 I jxcore-log: 
,08-16 13:19:07.419  4288  4288 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-16 13:19:07.425  4288  4288 D AndroidRuntime: CheckJNI is OFF
,08-16 13:19:07.468  4288  4288 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-16 13:19:07.516  4288  4288 I Radio-JNI: register_android_hardware_Radio DONE
,08-16 13:19:07.539  4288  4288 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-16 13:19:07.552   875   888 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-16 13:19:07.553   875   888 I ActivityManager: Killing 3784:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-16 13:19:07.679   875   885 D GraphicsStats: Buffer count: 2
,08-16 13:19:07.680   875  1715 I WindowState: WIN DEATH: Window{1d9805d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 13:19:07.680   875  1307 D WifiService: Client connection lost with reason: 4
,08-16 13:19:07.699   875   898 W PackageSettings: Skipping PackageSetting{1305152 com.example.hello/10273} due to missing metadata
,08-16 13:19:07.732   875   888 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-16 13:19:07.732   875   888 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-16 13:19:07.733   875   888 E ActivityManager: Failure starting process com.test.thalitest
08-16 13:19:07.733   875   888 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-16 13:19:07.733   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-16 13:19:07.733   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-16 13:19:07.733   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-16 13:19:07.733   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-16 13:19:07.733   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-16 13:19:07.733   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-16 13:19:07.733   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-16 13:19:07.733   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-16 13:19:07.733   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-16 13:19:07.733   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-16 13:19:07.733   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-16 13:19:07.733   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-16 13:19:07.733   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-16 13:19:07.733   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-16 13:19:07.733   875   888 E ActivityManager: 	,at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:19:07.733   875   888 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:19:07.733   875   888 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 13:19:07.733   875   888 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-16 13:19:07.733   875   888 I ActivityManager:   Force finishing activity ActivityRecord{79b561a u0 com.test.thalitest/.MainActivity t2}
,08-16 13:19:07.737   875   885 W ActivityManager: Spurious death for ProcessRecord{234953b 0:com.test.thalitest/u0a0}, curProc for 3784: null
,08-16 13:19:07.739   875   898 I art     : Starting a blocking GC Explicit
,08-16 13:19:07.784   875   898 I art     : Explicit concurrent mark sweep GC freed 13837(963KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 753us total 45.550ms
,08-16 13:19:07.815   875   898 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-16 13:19:07.817  4288  4288 I art     : System.exit called, status: 0
08-16 13:19:07.817  4288  4288 I AndroidRuntime: VM exiting with result code 0.
,08-16 13:19:07.836   875   898 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-16 13:19:07.870   875   888 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-16 13:19:07.875   875  1294 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 13:19:07.879  1856  1856 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-16 13:19:07.881  4194  4194 D BluetoothMapAppObserver: onReceive
08-16 13:19:07.881  4194  4194 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-16 13:19:07.888  2102  2272 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-16 13:19:07.894  3652  3652 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-16 13:19:07.909  1856  4301 I Keyboard.Facilitator.DecoderInitializer: run()
,08-16 13:19:07.918  1856  4301 I Decoder : createOrResetDecoder
,08-16 13:19:07.929   875  1373 I ActivityManager: Start proc 4303:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-16 13:19:07.932  1919  1919 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-16 13:19:07.940  1549  1549 I ConfigService: onCreate
,08-16 13:19:07.949  1549  4314 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-16 13:19:07.949  1549  4314 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 13:19:07.949  1549  4314 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 13:19:07.949  1549  4314 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 13:19:07.949  1549  4314 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 13:19:07.949  1549  4314 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 13:19:07.949  1549  4314 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 13:19:07.949  1549  4314 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 13:19:07.949  1549  4314 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 13:19:07.949  1549  4314 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 13:19:07.949  1549  4314 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 13:19:07.949  1549  4314 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 13:19:07.949  1549  4314 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 13:19:07.949  1549  4314 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 13:19:07.949  1549  4314 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 13:19:07.949  1549  4314 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-16 13:19:07.949  1549  4314 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-16 13:19:07.949  1549  4314 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-16 13:19:07.949  1549  4314 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-16 13:19:07.949  1549  4314 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 13:19:07.949  1549  4314 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 13:19:07.949  1549  4314 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 13:19:07.949  1549  4314 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 13:19:07.949  1549  4314 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 13:19:07.949  1549  4314 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 13:19:07.949  1549  4314 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 13:19:07.949  1549  4314 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 13:19:07.949  1549  4314 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 13:19:07.949  1549  4314 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 13:19:07.949  1549  4314 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 13:19:07.949  1549  4314 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 13:19:07.949  1549  4314 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 13:19:07.949  1549  4314 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 13:19:07.949  1549  4314 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-16 13:19:07.949  1549  4314 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-16 13:19:07.949  1549  4314 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,08-16 13:19:07.953  1549  4314 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-16 13:19:07.964  1856  4301 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-16 13:19:07.990   875   886 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3784 uid 10000
,08-16 13:19:07.991  1856  1856 I Keyboard.Facilitator: onFinishInput()
,08-16 13:19:07.998  4303  4303 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-16 13:19:08.001   875   875 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-16 13:19:08.014   875   887 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-16 13:19:08.014   875   887 E PackageManager: Failed to write settings, restoring backup
08-16 13:19:08.014   875   887 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-16 13:19:08.014   875   887 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-16 13:19:08.014   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-16 13:19:08.014   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-16 13:19:08.014   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-16 13:19:08.014   875   887 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:19:08.014   875   887 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:19:08.014   875   887 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 13:19:08.020   875   888 E DropBoxManagerService: Can't write: system_server_wtf
08-16 13:19:08.020   875   888 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-16 13:19:08.020   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 13:19:08.020   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 13:19:08.020   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 13:19:08.020   875   888 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 13:19:08.020   875   888 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 13:19:08.020   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 13:19:08.020   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-16 13:19:08.020   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-16 13:19:08.020   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-16 13:19:08.020   875   888 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 13:19:08.020   875   888 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 13:19:08.020   875   888 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:19:08.020   875   888 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 13:19:08.020   875   888 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-16 13:19:08.020   875   888 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 13:19:08.020   875   888 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 13:19:08.020   875   888 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 13:19:08.020   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 13:19:08.020   875   888 E DropBoxManagerService: 	... 13 more
,08-16 13:19:08.024  1856  4301 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-16 13:19:08.025  1940  2018 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-16 13:19:08.026  1856  4301 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-16 13:19:08.026  1856  4301 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-16 13:19:08.027  1856  4301 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-16 13:19:08.028  1856  4301 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-16 13:19:08.036  1856  4301 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-16 13:19:08.036  1856  4301 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-16 13:19:08.037  1856  4301 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-16 13:19:08.037  1856  4301 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-16 13:19:08.039   875  1934 I ActivityManager: Start proc 4317:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-16 13:19:08.040  1940  2018 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-16 13:19:08.040  1940  2018 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1940
08-16 13:19:08.040  1940  2018 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 13:19:08.040  1940  2018 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-16 13:19:08.040  1940  2018 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-16 13:19:08.040  1940  2018 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-16 13:19:08.040  1940  2018 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-16 13:19:08.040  1940  2018 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-16 13:19:08.040  1940  2018 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-16 13:19:08.040  1940  2018 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-16 13:19:08.040  1940  2018 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 13:19:08.040  1940  2018 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 13:19:08.040  1940  2018 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:19:08.040  1940  2018 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 13:19:08.042   875  1699 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-16 13:19:08.042   875  4326 E DropBoxManagerService: Can't write: system_app_crash
08-16 13:19:08.042   875  4326 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
08-16 13:19:08.042   875  4326 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 13:19:08.042   875  4326 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 13:19:08.042   875  4326 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 13:19:08.042   875  4326 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 13:19:08.042   875  4326 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 13:19:08.042   875  4326 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 13:19:08.042   875  4326 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 13:19:08.042   875  4326 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 13:19:08.042   875  4326 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 13:19:08.042   875  4326 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 13:19:08.042   875  4326 E DropBoxManagerService: 	... 5 more
,08-16 13:19:08.037  1856  4301 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-16 13:19:08.043  1856  4301 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-16 13:19:08.043  1856  4301 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,08-16 13:19:08.043  1856  4301 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-16 13:19:08.047  1940  2018 I Process : Sending signal. PID: 1940 SIG: 9
,08-16 13:19:08.083  4303  4303 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-16 13:19:08.089  4303  4331 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-16 13:19:08.089  4303  4331 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 13:19:08.089  4303  4331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 13:19:08.089  4303  4331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 13:19:08.089  4303  4331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 13:19:08.089  4303  4331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 13:19:08.089  4303  4331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 13:19:08.089  4303  4331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 13:19:08.089  4303  4331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 13:19:08.089  4303  4331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 13:19:08.089  4303  4331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 13:19:08.089  4303  4331 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 13:19:08.089  4303  4331 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 13:19:08.089  4303  4331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 13:19:08.089  4303  4331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 13:19:08.089  4303  4331 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-16 13:19:08.089  4303  4331 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-16 13:19:08.089  4303  4331 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-16 13:19:08.089  4303  4331 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-16 13:19:08.089  4303  4331 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:19:08.089  4303  4331 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:19:08.089  4303  4331 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 13:19:08.099   875  1699 D GraphicsStats: Buffer count: 1
,08-16 13:19:08.099   875  1934 I WindowState: WIN DEATH: Window{63afce7 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-16 13:19:08.103   875  1984 I ActivityManager: Start proc 4334:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-16 13:19:08.107  4303  4331 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-16 13:19:08.107  4303  4331 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 13:19:08.107  4303  4331 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 13:19:08.107  4303  4331 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 13:19:08.107  4303  4331 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 13:19:08.107  4303  4331 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 13:19:08.107  4303  4331 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 13:19:08.107  4303  4331 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 13:19:08.107  4303  4331 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 13:19:08.107  4303  4331 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 13:19:08.107  4303  4331 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 13:19:08.107  4303  4331 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 13:19:08.107  4303  4331 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 13:19:08.107  4303  4331 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 13:19:08.107  4303  4331 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 13:19:08.107  4303  4331 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-16 13:19:08.107  4303  4331 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-16 13:19:08.107  4303  4331 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-16 13:19:08.107  4303  4331 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-16 13:19:08.107  4303  4331 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:19:08.107  4303  4331 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:19:08.107  4303  4331 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 13:19:08.114   875  1699 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1940) has died
,08-16 13:19:08.115   875  1699 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-16 13:19:08.116   875  1699 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-16 13:19:08.108  4303  4333 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-16 13:19:08.135   875   888 I ActivityManager: Start proc 4347:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-16 13:19:08.163  4334  4334 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-16 13:19:08.182  4347  4347 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-16 13:19:08.182  4347  4347 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 13:19:08.182  4347  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 13:19:08.182  4347  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 13:19:08.182  4347  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 13:19:08.182  4347  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 13:19:08.182  4347  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 13:19:08.182  4347  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 13:19:08.182  4347  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 13:19:08.182  4347  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 13:19:08.182  4347  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 13:19:08.182  4347  4347 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 13:19:08.182  4347  4347 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 13:19:08.182  4347  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 13:19:08.182  4347  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 13:19:08.182  4347  4347 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-16 13:19:08.182  4347  4347 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-16 13:19:08.182  4347  4347 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-16 13:19:08.182  4347  4347 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-16 13:19:08.182  4347  4347 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-16 13:19:08.182  4347  4347 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-16 13:19:08.182  4347  4347 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-16 13:19:08.182  4347  4347 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 13:19:08.182  4347  4347 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 13:19:08.182  4347  4347 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:19:08.182  4347  4347 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:19:08.182  4347  4347 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 13:19:08.182  4347  4347 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:19:08.182  4347  4347 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 13:19:08.182  4347  4347 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 13:19:08.183  4347  4347 D AndroidRuntime: Shutting down VM
08-16 13:19:08.183  1549  1549 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-16 13:19:08.184  1549  1549 D AndroidRuntime: Shutting down VM
,08-16 13:19:08.185  1549  1549 E AndroidRuntime: FATAL EXCEPTION: main
08-16 13:19:08.185  1549  1549 E AndroidRuntime: Process: com.google.process.gapps, PID: 1549
08-16 13:19:08.185  1549  1549 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 13:19:08.185  1549  1549 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-16 13:19:08.185  1549  1549 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-16 13:19:08.185  1549  1549 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-16 13:19:08.185  1549  1549 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:19:08.185  1549  1549 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:19:08.185  1549  1549 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 13:19:08.185  1549  1549 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:19:08.185  1549  1549 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 13:19:08.185  1549  1549 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 13:19:08.185  1549  1549 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 13:19:08.185  1549  1549 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-16 13:19:08.185  1549  1549 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-16 13:19:08.185  1549  1549 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-16 13:19:08.185  1549  1549 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-16 13:19:08.185  1549  1549 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-16 13:19:08.185  1549  1549 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-16 13:19:08.185  1549  1549 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-16 13:19:08.185  1549  1549 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-16 13:19:08.185  1549  1549 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-16 13:19:08.185  1549  1549 E AndroidRuntime: 	... 8 more
,08-16 13:19:08.188  4347  4347 E AndroidRuntime: FATAL EXCEPTION: main
08-16 13:19:08.188  4347  4347 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4347
08-16 13:19:08.188  4347  4347 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 13:19:08.188  4347  4347 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-16 13:19:08.188  4347  4347 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-16 13:19:08.188  4347  4347 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-16 13:19:08.188  4347  4347 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 13:19:08.188  4347  4347 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 13:19:08.188  4347  4347 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:19:08.188  4347  4347 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:19:08.188  4347  4347 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 13:19:08.188  4347  4347 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:19:08.188  4347  4347 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 13:19:08.188  4347  4347 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 13:19:08.188  4347  4347 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 13:19:08.188  4347  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 13:19:08.188  4347  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 13:19:08.188  4347  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 13:19:08.188  4347  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 13:19:08.188  4347  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 13:19:08.188  4347  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 13:19:08.188  4347  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 13:19:08.188  4347  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 13:19:08.188  4347  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 13:19:08.188  4347  4347 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 13:19:08.188  4347  4347 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 13:19:08.188  4347  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 13:19:08.188  4347  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 13:19:08.188  4347  4347 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-16 13:19:08.188  4347  4347 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-16 13:19:08.188  4347  4347 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-16 13:19:08.188  4347  4347 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-16 13:19:08.188  4347  4347 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-16 13:19:08.188  4347  4347 E AndroidRuntime: 	... 10 more
08-16 13:19:08.192  1549  1549 I Process : Sending signal. PID: 1549 SIG: 9
08-16 13:19:08.192   875  1699 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-16 13:19:08.192   875  4362 E DropBoxManagerService: Can't write: system_app_crash
08-16 13:19:08.192   875  4362 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-16 13:19:08.192   875  4362 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 13:19:08.192   875  4362 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 13:19:08.192   875  4362 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 13:19:08.192   875  4362 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 13:19:08.192   875  4362 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 13:19:08.192   875  4362 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 13:19:08.192   875  4362 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 13:19:08.192   875  4362 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 13:19:08.192   875  4362 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 13:19:08.192   875  4362 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 13:19:08.192   875  4362 E DropBoxManagerService: 	... 5 more
08-16 13:19:08.193  4347  4347 I Process : Sending signal. PID: 4347 SIG: 9
,08-16 13:19:08.196   875  4363 E DropBoxManagerService: Can't write: system_app_crash
08-16 13:19:08.196   875  4363 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-16 13:19:08.196   875  4363 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 13:19:08.196   875  4363 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 13:19:08.196   875  4363 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 13:19:08.196   875  4363 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 13:19:08.196   875  4363 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 13:19:08.196   875  4363 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 13:19:08.196   875  4363 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 13:19:08.196   875  4363 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 13:19:08.196   875  4363 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 13:19:08.196   875  4363 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 13:19:08.196   875  4363 E DropBoxManagerService: 	... 5 more
,08-16 13:19:08.225  4303  4331 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-16 13:19:08.229   875  1625 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4347) has died
,08-16 13:19:08.229  4303  4333 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-16 13:19:08.229  4303  4333 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 13:19:08.229  4303  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 13:19:08.229  4303  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 13:19:08.229  4303  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 13:19:08.229  4303  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 13:19:08.229  4303  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 13:19:08.229  4303  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 13:19:08.229  4303  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 13:19:08.229  4303  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 13:19:08.229  4303  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 13:19:08.229  4303  4333 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 13:19:08.229  4303  4333 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 13:19:08.229  4303  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 13:19:08.229  4303  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 13:19:08.229  4303  4333 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-16 13:19:08.229  4303  4333 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-16 13:19:08.229  4303  4333 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-16 13:19:08.229  4303  4333 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-16 13:19:08.229  4303  4333 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-16 13:19:08.229  4303  4333 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-16 13:19:08.229  4303  4333 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-16 13:19:08.229  4303  4333 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:19:08.229  4303  4333 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:19:08.229  4303  4333 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 13:19:08.230  4303  4333 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-16 13:19:08.230  4303  4333 E AndroidRuntime: Process: android.process.acore, PID: 4303
08-16 13:19:08.230  4303  4333 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 13:19:08.230  4303  4333 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 13:19:08.230  4303  4333 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 13:19:08.230  4303  4333 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 13:19:08.230  4303  4333 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 13:19:08.230  4303  4333 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 13:19:08.230  4303  4333 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 13:19:08.230  4303  4333 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 13:19:08.230  4303  4333 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 13:19:08.230  4303  4333 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 13:19:08.230  4303  4333 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 13:19:08.230  4303  4333 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 13:19:08.230  4303  4333 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 13:19:08.230  4303  4333 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 13:19:08.230  4303  4333 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-16 13:19:08.230  4303  4333 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-16 13:19:08.230  4303  4333 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-16 13:19:08.230  4303  4333 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-16 13:19:08.230  4303  4333 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-16 13:19:08.230  4303  4333 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-16 13:19:08.230  4303  4333 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-16 13:19:08.230  4303  4333 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:19:08.230  4303  4333 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:19:08.230  4303  4333 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 13:19:08.230   875  1625 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-16 13:19:08.231   875  1307 D WifiService: Client connection lost with reason: 4
,08-16 13:19:08.236   875  1699 I ActivityManager: Process com.google.process.gapps (pid 1549) has died
,08-16 13:19:08.237   875  1699 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
08-16 13:19:08.237   875  1699 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
08-16 13:19:08.237   875  1699 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 21000ms
,08-16 13:19:08.237   875  1699 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 31000ms
,08-16 13:19:08.242  1726  4364 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@5c195c6
,08-16 13:19:08.243  1726  1726 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-16 13:19:08.250   875   888 I ActivityManager: Start proc 4366:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-16 13:19:08.266   875  1306 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,08-16 13:19:08.286  4303  4331 I Process : Sending signal. PID: 4303 SIG: 9
,08-16 13:19:08.291   875   886 I ActivityManager: Start proc 4378:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
,08-16 13:19:08.292  4366  4366 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-16 13:19:08.292  4366  4366 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 13:19:08.292  4366  4366 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 13:19:08.292  4366  4366 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 13:19:08.292  4366  4366 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 13:19:08.292  4366  4366 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 13:19:08.292  4366  4366 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 13:19:08.292  4366  4366 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 13:19:08.292  4366  4366 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 13:19:08.292  4366  4366 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 13:19:08.292  4366  4366 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 13:19:08.292  4366  4366 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 13:19:08.292  4366  4366 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 13:19:08.292  4366  4366 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 13:19:08.292  4366  4366 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 13:19:08.292  4366  4366 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-16 13:19:08.292  4366  4366 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-16 13:19:08.292  4366  4366 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-16 13:19:08.292  4366  4366 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-16 13:19:08.292  4366  4366 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-16 13:19:08.292  4366  4366 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-16 13:19:08.292  4366  4366 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-16 13:19:08.292  4366  4366 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 13:19:08.292  4366  4366 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 13:19:08.292  4366  4366 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:19:08.292  4366  4366 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:19:08.292  4366  4366 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 13:19:08.292  4366  4366 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:19:08.292  4366  4366 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 13:19:08.292  4366  4366 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 13:19:08.292  4366  4366 D AndroidRuntime: Shutting down VM
08-16 13:19:08.296   875  4384 E DropBoxManagerService: Can't write: system_app_crash
08-16 13:19:08.296   875  4384 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-16 13:19:08.296   875  4384 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 13:19:08.296   875  4384 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 13:19:08.296   875  4384 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 13:19:08.296   875  4384 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 13:19:08.296   875  4384 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 13:19:08.296   875  4384 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 13:19:08.296   875  4384 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 13:19:08.296   875  4384 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 13:19:08.296   875  4384 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 13:19:08.296   875  4384 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 13:19:08.296   875  4384 E DropBoxManagerService: 	... 5 more
,08-16 13:19:08.308  4366  4366 E AndroidRuntime: FATAL EXCEPTION: main
08-16 13:19:08.308  4366  4366 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4366
08-16 13:19:08.308  4366  4366 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 13:19:08.308  4366  4366 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-16 13:19:08.308  4366  4366 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-16 13:19:08.308  4366  4366 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-16 13:19:08.308  4366  4366 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 13:19:08.308  4366  4366 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 13:19:08.308  4366  4366 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:19:08.308  4366  4366 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:19:08.308  4366  4366 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 13:19:08.308  4366  4366 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:19:08.308  4366  4366 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 13:19:08.308  4366  4366 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 13:19:08.308  4366  4366 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 13:19:08.308  4366  4366 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 13:19:08.308  4366  4366 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 13:19:08.308  4366  4366 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 13:19:08.308  4366  4366 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 13:19:08.308  4366  4366 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 13:19:08.308  4366  4366 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 13:19:08.308  4366  4366 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 13:19:08.308  4366  4366 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 13:19:08.308  4366  4366 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 13:19:08.308  4366  4366 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 13:19:08.308  4366  4366 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 13:19:08.308  4366  4366 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 13:19:08.308  4366  4366 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 13:19:08.308  4366  4366 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-16 13:19:08.308  4366  4366 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-16 13:19:08.308  4366  4366 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-16 13:19:08.308  4366  4366 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-16 13:19:08.308  4366  4366 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-16 13:19:08.308  4366  4366 E AndroidRuntime: 	... 10 more
08-16 13:19:08.309   875  1698 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-16 13:19:08.310  4366  4366 I Process : Sending signal. PID: 4366 SIG: 9
,08-16 13:19:08.310   875  4392 E DropBoxManagerService: Can't write: system_app_crash
08-16 13:19:08.310   875  4392 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-16 13:19:08.310   875  4392 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 13:19:08.310   875  4392 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 13:19:08.310   875  4392 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 13:19:08.310   875  4392 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 13:19:08.310   875  4392 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 13:19:08.310   875  4392 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 13:19:08.310   875  4392 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 13:19:08.310   875  4392 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 13:19:08.310   875  4392 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 13:19:08.310   875  4392 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 13:19:08.310   875  4392 E DropBoxManagerService: 	... 5 more
,08-16 13:19:08.324  1726  1726 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-16 13:19:08.324  1726  1726 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-16 13:19:08.327   282   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
