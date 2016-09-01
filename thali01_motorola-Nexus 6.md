#### Test 8359176442466a2_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-01 11:14:59.922  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 11:14:59.935  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-01 11:14:59.940  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-01 11:14:59.981  1514  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-01 11:14:59.981  1514  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-01 11:14:59.981  1514  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 11:14:59.981  1514  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-01 11:15:00.007  3477  3477 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-01 11:15:00.007  3477  3477 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-01 11:15:00.008  3477  3477 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
09-01 11:15:00.537  3775  3775 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-01 11:15:00.542  3775  3775 D AndroidRuntime: CheckJNI is OFF
09-01 11:15:00.585  3775  3775 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-01 11:15:00.636  3775  3775 I Radio-JNI: register_android_hardware_Radio DONE
09-01 11:15:00.658  3775  3775 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-01 11:15:00.663   875   885 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-01 11:15:00.710  2013  2432 W SearchService: Abort, client detached.
09-01 11:15:00.713  2013  2013 I HotwordDetector: Closing mic
09-01 11:15:00.713  2013  2333 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@91eb8d8
09-01 11:15:00.713  2013  2339 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-01 11:15:00.727  3775  3775 D AndroidRuntime: Shutting down VM
09-01 11:15:00.748   875  1982 I ActivityManager: Start proc 3784:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-01 11:15:00.774   378  2341 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-01 11:15:00.775   378  2341 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-01 11:15:00.779   378  1276 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-01 11:15:00.781  2013  2336 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-01 11:15:00.781  2013  2338 I MicroRecognitionRnrImpl: Detection finished
09-01 11:15:00.823  3784  3784 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-01 11:15:00.851  3784  3784 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-01 11:15:00.858  3784  3784 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8635-8638)
09-01 11:15:00.858  3784  3784 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-01 11:15:00.874  3784  3784 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {96d5b6d}
09-01 11:15:00.875  3784  3784 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-01 11:15:00.875  3784  3784 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-01 11:15:00.881  3784  3784 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-01 11:15:00.882  3784  3784 E SysUtils: ApplicationContext is null in ApplicationStatus
09-01 11:15:00.902  3784  3784 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-01 11:15:00.913  3784  3784 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-01 11:15:00.913  3784  3784 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-01 11:15:00.913  3784  3784 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-01 11:15:00.913  3784  3784 I Adreno  : Build Date                       : 10/20/15
09-01 11:15:00.913  3784  3784 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-01 11:15:00.913  3784  3784 I Adreno  : Local Branch                     : M14
09-01 11:15:00.913  3784  3784 I Adreno  : Remote Branch                    : 
09-01 11:15:00.913  3784  3784 I Adreno  : Remote Branch                    : 
09-01 11:15:00.913  3784  3784 I Adreno  : Reconstruct Branch               : 
,09-01 11:15:00.966   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e4148:true
,09-01 11:15:01.024  3784  3784 W AwContents: onDetachedFromWindow called when already detached. Ignoring,
,09-01 11:15:01.036  3784  3784 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-01 11:15:01.100  3784  3822 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-01 11:15:01.108  3784  3809 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-01 11:15:01.143  3784  3822 I OpenGLRenderer: Initialized EGL, version 1.4
,09-01 11:15:01.205   875   893 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +480ms
,09-01 11:15:01.208  1871  1871 I Keyboard.Facilitator: onFinishInput()
,09-01 11:15:01.289  3784  3784 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3784
,09-01 11:15:01.373  3784  3784 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-01 11:15:01.539   875  1949 I ActivityManager: Killing 2248:com.google.android.talk/u0a61 (adj 15): empty #17
,09-01 11:15:01.547  3784  3826 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1713768144
,09-01 11:15:01.554  3784  3826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-01 11:15:01.554  3784  3826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-01 11:15:01.554  3784  3826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-01 11:15:01.554  3784  3826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-01 11:15:01.554  3784  3826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-01 11:15:01.554  3784  3826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ceba9c8 added. We now have 1 listener(s)
,09-01 11:15:01.558  3784  3826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-01 11:15:01.560  3784  3826 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-01 11:15:01.560  3784  3826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:15:01.561  3784  3826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-01 11:15:01.564  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-01 11:15:01.564  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-01 11:15:01.564  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-01 11:15:01.564  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-01 11:15:01.564  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-01 11:15:01.564  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-01 11:15:01.564  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-01 11:15:01.564  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-01 11:15:01.564  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-01 11:15:01.564  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-01 11:15:01.564  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-01 11:15:01.564  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-01 11:15:01.564  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-01 11:15:01.564  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-01 11:15:01.565  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fa1247 added. We now have 1 listener(s)
,09-01 11:15:01.565  3784  3826 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 11:15:01.568   875  1307 D WifiService: New client listening to asynchronous messages
,09-01 11:15:01.569  3784  3826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-01 11:15:01.569  3784  3826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-01 11:15:01.570  3784  3826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-01 11:15:01.571  3784  3826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,09-01 11:15:01.571  3784  3826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-01 11:15:01.587   875  1949 I ActivityManager: Killing 3363:com.google.android.music:main/u0a66 (adj 15): empty #18
,09-01 11:15:01.629  3784  3826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:15:01.630  3784  3826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-01 11:15:01.636  3784  3826 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-01 11:15:01.636  3784  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:15:01.636  3784  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:01.636  3784  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:01.636  3784  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:15:01.636  3784  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:15:01.636  3784  3826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:15:01.636  3784  3826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:15:01.636  3784  3826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 11:15:01.636  3784  3826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-01 11:15:01.636  3784  3826 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:15:01.637  3784  3826 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-01 11:15:01.730  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:01.732  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:15:01.734  3784  3784 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-01 11:15:02.545  3784  3836 W jxcore-log: Initializing JXcore engine
09-01 11:15:02.545  3784  3836 W jxcore-log: JXcore engine is ready
,09-01 11:15:02.582  3836  3836 W Thread-330: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8934 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-01 11:15:02.582  3836  3836 W Thread-330: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10675]" dev="sockfs" ino=10675 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-01 11:15:02.582  3836  3836 W Thread-330: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-01 11:15:02.582  3836  3836 W Thread-330: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25386]" dev="sockfs" ino=25386 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-01 11:15:02.596  3784  3836 W jxcore-log: Starting JXcore engine
,09-01 11:15:02.675  3784  3836 W jxcore-log: Platform android
09-01 11:15:02.675  3784  3836 W jxcore-log: 
,09-01 11:15:02.675  3784  3836 W jxcore-log: Process ARCH arm
09-01 11:15:02.675  3784  3836 W jxcore-log: 
,09-01 11:15:02.879  3784  3836 I jxcore-log: JXcore Cordova bridge is ready!
09-01 11:15:02.879  3784  3836 I jxcore-log: 
,09-01 11:15:02.879  3784  3836 W jxcore-log: JXcore engine is started
,09-01 11:15:02.888  3784  3826 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-01 11:15:02.893  3784  3784 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-01 11:15:05.075   875  1306 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-01 11:15:08.800  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 11:15:08.805  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 11:15:08.851  1514  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-01 11:15:08.852  1514  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-01 11:15:08.852  1514  1526 I GLSUser : [GLSUser] Extracting token using key: Auth,
09-01 11:15:08.852  1514  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 11:15:08.880  3517  3844 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-01 11:15:08.880  3517  3844 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-01 11:15:08.880  3517  3844 E HttpOperation: 	at jdm.a(PG:82)
09-01 11:15:08.880  3517  3844 E HttpOperation: 	at jcs.o(PG:406)
09-01 11:15:08.880  3517  3844 E HttpOperation: 	at jcn.a(PG:1379)
09-01 11:15:08.880  3517  3844 E HttpOperation: 	at jcs.i(PG:143)
09-01 11:15:08.880  3517  3844 E HttpOperation: 	at blb.a(PG:3937)
09-01 11:15:08.880  3517  3844 E HttpOperation: 	at czp.a(PG:18188)
09-01 11:15:08.880  3517  3844 E HttpOperation: 	at czp.a(PG:9081)
09-01 11:15:08.880  3517  3844 E HttpOperation: 	at czq.run(PG:1686)
09-01 11:15:08.880  3517  3844 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-01 11:15:08.880  3517  3844 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-01 11:15:08.880  3517  3844 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-01 11:15:08.880  3517  3844 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-01 11:15:08.880  3517  3844 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-01 11:15:08.880  3517  3844 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-01 11:15:08.880  3517  3844 E HttpOperation: 	at jdj.a(PG:4091)
09-01 11:15:08.880  3517  3844 E HttpOperation: 	at jdj.a(PG:1125)
09-01 11:15:08.880  3517  3844 E HttpOperation: 	at jdm.a(PG:77)
09-01 11:15:08.880  3517  3844 E HttpOperation: 	... 12 more
09-01 11:15:08.880  3517  3844 E HttpOperation: Caused by: faj: BadAuthentication
09-01 11:15:08.880  3517  3844 E HttpOperation: 	at fal.a(PG:38)
09-01 11:15:08.880  3517  3844 E HttpOperation: 	at jdj.a(PG:4089)
09-01 11:15:08.880  3517  3844 E HttpOperation: 	... 14 more
,09-01 11:15:08.957  1514  2045 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-01 11:15:08.957  1514  2045 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-01 11:15:08.958  1514  2045 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 11:15:08.958  1514  2045 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 11:15:08.985  3517  3844 E HttpOperation: [getmobileexperiments] Unexpected exception
09-01 11:15:08.985  3517  3844 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-01 11:15:08.985  3517  3844 E HttpOperation: 	at jdm.a(PG:82)
09-01 11:15:08.985  3517  3844 E HttpOperation: 	at jcs.o(PG:406)
09-01 11:15:08.985  3517  3844 E HttpOperation: 	at jcn.a(PG:1379)
09-01 11:15:08.985  3517  3844 E HttpOperation: 	at jcs.i(PG:143)
09-01 11:15:08.985  3517  3844 E HttpOperation: 	at hec.a(PG:42)
09-01 11:15:08.985  3517  3844 E HttpOperation: 	at hee.a(PG:102)
09-01 11:15:08.985  3517  3844 E HttpOperation: 	at czr.a(PG:65)
09-01 11:15:08.985  3517  3844 E HttpOperation: 	at kka.a(PG:108)
09-01 11:15:08.985  3517  3844 E HttpOperation: 	at czp.a(PG:19176)
09-01 11:15:08.985  3517  3844 E HttpOperation: 	at czp.a(PG:9081)
09-01 11:15:08.985  3517  3844 E HttpOperation: 	at czq.run(PG:1686)
09-01 11:15:08.985  3517  3844 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-01 11:15:08.985  3517  3844 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-01 11:15:08.985  3517  3844 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-01 11:15:08.985  3517  3844 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-01 11:15:08.985  3517  3844 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-01 11:15:08.985  3517  3844 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-01 11:15:08.985  3517  3844 E HttpOperation: 	at jdj.a(PG:4091)
09-01 11:15:08.985  3517  3844 E HttpOperation: 	at jdj.a(PG:1125)
09-01 11:15:08.985  3517  3844 E HttpOperation: 	at jdm.a(PG:77)
09-01 11:15:08.985  3517  3844 E HttpOperation: 	... 15 more
09-01 11:15:08.985  3517  3844 E HttpOperation: Caused by: faj: BadAuthentication
09-01 11:15:08.985  3517  3844 E HttpOperation: 	at fal.a(PG:38)
09-01 11:15:08.985  3517  3844 E HttpOperation: 	at jdj.a(PG:4089)
09-01 11:15:08.985  3517  3844 E HttpOperation: 	... 17 more
09-01 11:15:08.985  3517  3844 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-01 11:15:08.985  3517  3844 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-01 11:15:08.985  3517  3844 E ExperimentLoader: 	at jdm.a(PG:82)
09-01 11:15:08.985  3517  3844 E ExperimentLoader: 	at jcs.o(PG:406)
09-01 11:15:08.985  3517  3844 E ExperimentLoader: 	at jcn.a(PG:1379)
09-01 11:15:08.985  3517  3844 E ExperimentLoader: 	at jcs.i(PG:143)
09-01 11:15:08.985  3517  3844 E ExperimentLoader: 	at hec.a(PG:42)
09-01 11:15:08.985  3517  3844 E ExperimentLoader: 	at hee.a(PG:102)
09-01 11:15:08.985  3517  3844 E ExperimentLoader: 	at czr.a(PG:65)
09-01 11:15:08.985  3517  3844 E ExperimentLoader: 	at kka.a(PG:108)
09-01 11:15:08.985  3517  3844 E ExperimentLoader: 	at czp.a(PG:19176)
09-01 11:15:08.985  3517  3844 E ExperimentLoader: 	at czp.a(PG:9081)
09-01 11:15:08.985  3517  3844 E ExperimentLoader: 	at czq.run(PG:1686)
09-01 11:15:08.985  3517  3844 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-01 11:15:08.985  3517  3844 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-01 11:15:08.985  3517  3844 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-01 11:15:08.985  3517  3844 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-01 11:15:08.985  3517  3844 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-01 11:15:08.985  3517  3844 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-01 11:15:08.985  3517  3844 E ExperimentLoader: 	at jdj.a(PG:4091)
09-01 11:15:08.985  3517  3844 E ExperimentLoader: 	at jdj.a(PG:1,125)
09-01 11:15:08.985  3517  3844 E ExperimentLoader: 	at jdm.a(PG:77)
09-01 11:15:08.985  3517  3844 E ExperimentLoader: 	... 15 more
09-01 11:15:08.985  3517  3844 E ExperimentLoader: Caused by: faj: BadAuthentication
09-01 11:15:08.985  3517  3844 E ExperimentLoader: 	at fal.a(PG:38)
09-01 11:15:08.985  3517  3844 E ExperimentLoader: 	at jdj.a(PG:4089)
09-01 11:15:08.985  3517  3844 E ExperimentLoader: 	... 17 more
,09-01 11:15:09.131   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 126231, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-01 11:15:12.963  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-01 11:15:12.963  3784  3836 I jxcore-log: 
,09-01 11:15:12.966  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-01 11:15:12.966  3784  3836 I jxcore-log: 
,09-01 11:15:12.977  3784  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:15:12.977  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:12.977  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:12.977  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:15:12.977  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:15:12.977  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:15:12.977  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:15:12.977  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 11:15:12.983  3784  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 11:15:12.986  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-01 11:15:12.986  3784  3836 I jxcore-log: 
,09-01 11:15:12.988  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-01 11:15:12.988  3784  3836 I jxcore-log: 
,09-01 11:15:13.475  3784  3836 D executeNativeTests: Running unit tests
,09-01 11:15:13.533  3784  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:15:13.533  3784  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ac66f1 added. We now have 2 listener(s)
,09-01 11:15:13.534  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-01 11:15:13.534  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:15:13.534  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-01 11:15:13.534  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:15:13.534  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 added. We now have 2 listener(s)
,09-01 11:15:13.534  3784  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:15:13.535  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-01 11:15:13.537  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:15:13.550  3784  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:15:13.550  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:13.550  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:13.550  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:15:13.550  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:15:13.550  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:15:13.550  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:15:13.550  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 11:15:13.555  3784  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:15:13.556  3784  3836 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 11:15:13.563  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-01 11:15:13.564  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:13.565  3784  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
09-01 11:15:13.566  3784  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-01 11:15:13.566  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:13.570  3784  3836 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-01 11:15:13.571  3784  3836 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-01 11:15:13.571  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-01 11:15:13.572  3784  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-01 11:15:13.572  3784  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 11:15:13.574  3784  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:15:13.576  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:13.577  3784  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:13.577  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:13.578  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.578  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 11:15:13.578  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:15:13.579  3784  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ac66f1 removed from the list
09-01 11:15:13.579  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 11:15:13.579  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 removed from the list
09-01 11:15:13.580  3784  3836 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:13.580  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.581  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.581  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.582  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:13.582  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:13.582  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.582  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
,09-01 11:15:13.584  3784  3836 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-01 11:15:13.585  3784  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:15:13.585  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:13.585  3784  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:13.585  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:13.585  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.585  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.585  3784  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ac66f1 not in the list
09-01 11:15:13.585  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.585  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
09-01 11:15:13.585  3784  3836 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:13.585  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.585  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.586  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.586  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.587  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:13.587  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:13.587  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.587  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
,09-01 11:15:13.592  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-01 11:15:13.592  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-01 11:15:13.592  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-01 11:15:13.592  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-01 11:15:13.592  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-01 11:15:13.592  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-01 11:15:13.592  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-01 11:15:13.592  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-01 11:15:13.592  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-01 11:15:13.592  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-01 11:15:13.592  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-01 11:15:13.592  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-01 11:15:13.592  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-01 11:15:13.592  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-01 11:15:13.592  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-01 11:15:13.592  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-01 11:15:13.592  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-01 11:15:13.593  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-01 11:15:13.593  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-01 11:15:13.593  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-01 11:15:13.593  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-01 11:15:13.593  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-01 11:15:13.593  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-01 11:15:13.593  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-01 11:15:13.593  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-01 11:15:13.593  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-01 11:15:13.593  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-01 11:15:13.593  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-01 11:15:13.593  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-01 11:15:13.593  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-01 11:15:13.593  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-01 11:15:13.593  3784  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:15:13.593  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:13.593  3784  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:13.594  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:13.594  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.594  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.594  3784  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ac66f1 not in the list
09-01 11:15:13.594  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.594  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
,09-01 11:15:13.594  3784  3836 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:13.594  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.594  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.594  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.594  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.595  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:13.595  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:13.595  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.595  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
09-01 11:15:13.596  3784  3836 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-01 11:15:13.597  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:15:13.601  3784  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:15:13.601  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:13.601  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:13.601  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:15:13.601  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:15:13.601  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:15:13.601  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:15:13.601  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 11:15:13.604  3784  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:15:13.604  3784  3836 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 11:15:13.605  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-01 11:15:13.605  3784  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 11:15:13.605  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 11:15:13.605  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:15:13.605  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 11:15:13.606  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:13.608  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:13.609  3784  3836 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-01 11:15:13.609  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-01 11:15:13.615  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-01 11:15:13.616  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-01 11:15:13.617  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-01 11:15:13.620  3784  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-01 11:15:13.623  3784  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-01 11:15:13.623  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-01 11:15:13.623  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-01 11:15:13.624  3784  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-01 11:15:13.625  3784  3836 D BluetoothAdapter: STATE_ON
,09-01 11:15:13.630  2653  2664 D BtGatt.GattService: registerClient() - UUID=6c89f742-58c2-420c-ae51-54bf037ac4c0
09-01 11:15:13.631  2653  2675 D BtGatt.GattService: onClientRegistered() - UUID=6c89f742-58c2-420c-ae51-54bf037ac4c0, clientIf=5
,09-01 11:15:13.631  3784  3796 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-01 11:15:13.632  2653  2666 D BtGatt.GattService: start scan with filters
,09-01 11:15:13.635  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-01 11:15:13.635  2653  2678 D BtGatt.ScanManager: handling starting scan
,09-01 11:15:13.635  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-01 11:15:13.635  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-01 11:15:13.635  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-01 11:15:13.636  2653  2678 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b148f
09-01 11:15:13.637  3784  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-01 11:15:13.637  3784  3784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-01 11:15:13.638  3784  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-01 11:15:13.639  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-01 11:15:13.641  3784  3836 I io.jxcore.node.ConnectionHelper: start: OK
,09-01 11:15:13.643  2653  2675 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-01 11:15:13.643  2653  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:15:13.644  2653  2678 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-01 11:15:13.646  3784  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:15:13.647  3784  3836 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-01 11:15:13.647  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:13.647  3784  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-01 11:15:13.647  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.647  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-01 11:15:13.647  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-01 11:15:13.647  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 11:15:13.647  3784  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-01 11:15:13.647  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-01 11:15:13.648  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-01 11:15:13.648  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-01 11:15:13.649  3784  3836 D BluetoothAdapter: STATE_ON
09-01 11:15:13.649  2653  2666 D BtGatt.GattService: stopScan() - queue size =1
09-01 11:15:13.650  2653  2764 D BtGatt.GattService: unregisterClient() - clientIf=5
09-01 11:15:13.650  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:15:13.651  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-01 11:15:13.651  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-01 11:15:13.651  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-01 11:15:13.651  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-01 11:15:13.652  2653  2675 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-01 11:15:13.652  2653  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:15:13.652  2653  2678 D BtGatt.ScanManager: Starting BLE batch scan
09-01 11:15:13.652  2653  2678 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-01 11:15:13.653  3784  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 11:15:13.653  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-01 11:15:13.653  3784  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-01 11:15:13.653  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-01 11:15:13.654  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:15:13.655  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 11:15:13.655  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 11:15:13.655  3784  3784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 11:15:13.655  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-01 11:15:13.655  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.655  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:15:13.655  3784  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ac66f1 not in the list
09-01 11:15:13.655  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.655  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
09-01 11:15:13.655  3784  3836 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:13.656  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.656  3784  3836 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-01 11:15:13.657  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:15:13.661  2653  2675 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-01 11:15:13.661  2653  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:15:13.661  3784  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:15:13.661  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:13.661  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:13.661  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:15:13.661  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:15:13.661  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:15:13.661  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:15:13.661  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:15:13.664  3784  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 11:15:13.664  3784  3836 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:15:13.664  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 11:15:13.664  3784  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 11:15:13.664  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 11:15:13.665  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:15:13.665  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 11:15:13.666  2653  2675 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-01 11:15:13.666  2653  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:15:13.667  3784  3836 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-01 11:15:13.667  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-01 11:15:13.667  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:15:13.670  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:15:13.671  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-01 11:15:13.671  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-01 11:15:13.672  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-01 11:15:13.674  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-01 11:15:13.674  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-01 11:15:13.675  3784  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-01 11:15:13.676  3784  3836 D BluetoothAdapter: STATE_ON
09-01 11:15:13.676  2653  2675 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-01 11:15:13.676  2653  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:15:13.677  2653  2678 D BtGatt.ScanManager: stopping BLe Batch
09-01 11:15:13.679  2653  2664 D BtGatt.GattService: registerClient() - UUID=e40a9e1d-97d2-41b0-8c37-affd40850c01
09-01 11:15:13.680  2653  2675 D BtGatt.GattService: onClientRegistered() - UUID=e40a9e1d-97d2-41b0-8c37-affd40850c01, clientIf=5
09-01 11:15:13.680  3784  3832 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-01 11:15:13.681  2653  2764 D BtGatt.GattService: start scan with filters
,09-01 11:15:13.682  2653  2675 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-01 11:15:13.683  2653  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:15:13.683  2653  2678 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-01 11:15:13.684  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-01 11:15:13.684  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-01 11:15:13.684  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-01 11:15:13.684  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-01 11:15:13.688  2653  2675 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-01 11:15:13.688  2653  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:15:13.689  3784  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-01 11:15:13.689  3784  3784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-01 11:15:13.689  3784  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-01 11:15:13.690  2653  2678 D BtGatt.ScanManager: handling starting scan
,09-01 11:15:13.692  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-01 11:15:13.695  2653  2675 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-01 11:15:13.695  2653  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:15:13.695  2653  2678 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-01 11:15:13.697  3784  3836 I io.jxcore.node.ConnectionHelper: start: OK
,09-01 11:15:13.701  2653  2675 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-01 11:15:13.701  2653  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:15:13.701  2653  2678 D BtGatt.ScanManager: Starting BLE batch scan
09-01 11:15:13.701  2653  2678 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-01 11:15:13.701  3784  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:15:13.701  3784  3836 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-01 11:15:13.702  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-01 11:15:13.702  3784  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-01 11:15:13.702  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 11:15:13.702  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-01 11:15:13.702  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-01 11:15:13.702  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 11:15:13.702  3784  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
09-01 11:15:13.702  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 11:15:13.703  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-01 11:15:13.703  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-01 11:15:13.704  3784  3836 D BluetoothAdapter: STATE_ON
,09-01 11:15:13.705  2653  2764 D BtGatt.GattService: stopScan() - queue size =1
,09-01 11:15:13.706  2653  2666 D BtGatt.GattService: unregisterClient() - clientIf=5
09-01 11:15:13.706  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:15:13.707  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-01 11:15:13.707  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-01 11:15:13.707  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-01 11:15:13.707  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-01 11:15:13.709  2653  2675 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-01 11:15:13.709  2653  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-01 11:15:13.710  3784  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 11:15:13.710  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-01 11:15:13.710  3784  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-01 11:15:13.711  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-01 11:15:13.712  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:15:13.713  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:13.713  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 11:15:13.713  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-01 11:15:13.713  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:15:13.713  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 11:15:13.713  3784  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ac66f1 not in the list
09-01 11:15:13.713  3784  3784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 11:15:13.713  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.713  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
09-01 11:15:13.713  3784  3836 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:13.714  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.714  2653  2675 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-01 11:15:13.714  2653  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:15:13.714  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.714  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.715  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:13.715  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:13.715  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.715  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
09-01 11:15:13.716  3784  3836 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-01 11:15:13.717  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:15:13.719  2653  2675 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-01 11:15:13.719  2653  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:15:13.719  2653  2678 D BtGatt.ScanManager: stopping BLe Batch
09-01 11:15:13.723  3784  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:15:13.723  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:13.723  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:13.723  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:15:13.723  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:15:13.723  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:15:13.723  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:15:13.723  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:15:13.724  2653  2675 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-01 11:15:13.724  2653  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:15:13.724  2653  2678 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-01 11:15:13.726  3784  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 11:15:13.726  3784  3836 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 11:15:13.726  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-01 11:15:13.727  3784  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 11:15:13.727  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 11:15:13.727  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:15:13.727  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 11:15:13.727  2653  2675 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-01 11:15:13.728  2653  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-01 11:15:13.728  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:15:13.729  3784  3836 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-01 11:15:13.729  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-01 11:15:13.730  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:15:13.732  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-01 11:15:13.733  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-01 11:15:13.733  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-01 11:15:13.735  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-01 11:15:13.735  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-01 11:15:13.735  3784  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-01 11:15:13.735  3784  3836 D BluetoothAdapter: STATE_ON
,09-01 11:15:13.737  2653  2666 D BtGatt.GattService: registerClient() - UUID=38dd778d-884f-4ac1-b557-00a71c2f2bd4
,09-01 11:15:13.737  2653  2675 D BtGatt.GattService: onClientRegistered() - UUID=38dd778d-884f-4ac1-b557-00a71c2f2bd4, clientIf=5
09-01 11:15:13.737  3784  3832 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-01 11:15:13.738  2653  2765 D BtGatt.GattService: start scan with filters
,09-01 11:15:13.739  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-01 11:15:13.739  2653  2678 D BtGatt.ScanManager: handling starting scan
09-01 11:15:13.739  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-01 11:15:13.739  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-01 11:15:13.739  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-01 11:15:13.743  3784  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 11:15:13.743  3784  3784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-01 11:15:13.743  3784  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-01 11:15:13.744  2653  2675 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-01 11:15:13.744  2653  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-01 11:15:13.744  2653  2678 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-01 11:15:13.744  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-01 11:15:13.745  3784  3836 I io.jxcore.node.ConnectionHelper: start: OK
09-01 11:15:13.746  3784  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:15:13.746  3784  3836 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-01 11:15:13.746  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:13.746  3784  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-01 11:15:13.746  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.746  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-01 11:15:13.746  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-01 11:15:13.746  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 11:15:13.746  3784  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-01 11:15:13.746  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-01 11:15:13.746  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-01 11:15:13.746  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-01 11:15:13.747  3784  3836 D BluetoothAdapter: STATE_ON
09-01 11:15:13.747  2653  2765 D BtGatt.GattService: stopScan() - queue size =1
09-01 11:15:13.747  2653  2664 D BtGatt.GattService: unregisterClient() - clientIf=5
09-01 11:15:13.747  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:15:13.747  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-01 11:15:13.748  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-01 11:15:13.748  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-01 11:15:13.748  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-01 11:15:13.748  3784  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 11:15:13.748  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-01 11:15:13.748  3784  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-01 11:15:13.748  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-01 11:15:13.749  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 11:15:13.749  2653  2675 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-01 11:15:13.749  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 11:15:13.749  2653  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:15:13.749  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-01 11:15:13.750  3784  3784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 11:15:13.750  2653  2678 D BtGatt.ScanManager: Starting BLE batch scan
,09-01 11:15:13.750  2653  2678 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-01 11:15:13.750  3784  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 11:15:13.750  3784  3836 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-01 11:15:13.750  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:13.750  3784  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:13.750  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:13.750  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.750  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:15:13.750  3784  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ac66f1 not in the list
,09-01 11:15:13.750  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.750  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
09-01 11:15:13.750  3784  3836 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:13.750  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.751  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.751  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:15:13.751  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:13.751  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:13.751  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.751  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
09-01 11:15:13.752  3784  3836 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-01 11:15:13.752  3784  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:15:13.752  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:13.752  3784  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:13.753  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-01 11:15:13.753  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.753  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.753  3784  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ac66f1 not in the list
09-01 11:15:13.753  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.753  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
09-01 11:15:13.753  3784  3836 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:13.753  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.753  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.753  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.753  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.754  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:13.754  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-01 11:15:13.754  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.754  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
09-01 11:15:13.754  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-01 11:15:13.756  3784  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:15:13.756  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:13.756  3784  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:13.756  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:13.756  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.756  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:15:13.756  3784  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ac66f1 not in the list
09-01 11:15:13.756  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.757  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
09-01 11:15:13.757  3784  3836 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:13.757  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.757  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.757  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.757  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.758  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:13.758  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-01 11:15:13.758  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.758  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
09-01 11:15:13.758  3784  3836 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-01 11:15:13.758  3784  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:15:13.758  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:13.759  3784  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:13.759  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:13.759  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.759  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.759  3784  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ac66f1 not in the list
09-01 11:15:13.759  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.759  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
09-01 11:15:13.759  3784  3836 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:13.759  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.759  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.759  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.759  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.760  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:13.760  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:13.760  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.760  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
09-01 11:15:13.760  3784  3836 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-01 11:15:13.760  3784  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:15:13.760  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:13.760  3784  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:13.761  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:13.761  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 1,1:15:13.761  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.761  3784  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ac66f1 not in the list
09-01 11:15:13.761  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.761  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
09-01 11:15:13.761  3784  3836 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:13.761  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.761  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.761  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.761  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.762  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:13.762  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:13.762  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.762  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
09-01 11:15:13.762  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-01 11:15:13.763  2653  2675 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-01 11:15:13.763  2653  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:15:13.763  3784  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-01 11:15:13.763  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-01 11:15:13.763  3784  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 11:15:13.763  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-01 11:15:13.763  3784  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-01 11:15:13.763  3784  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:15:13.764  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:13.764  3784  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:13.764  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:13.764  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.764  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.764  3784  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ac66f1 not in the list
09-01 11:15:13.764  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.764  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
09-01 11:15:13.764  3784  3836 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:13.764  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.764  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.765  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.765  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.765  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:13.765  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:13.765  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.765  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
09-01 11:15:13.766  3784  3836 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 11:15:13.766  3784  3836 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-01 11:15:13.766  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-01 11:15:13.770  3784  3836 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 11:15:13.771  3784  3836 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-01 11:15:13.771  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-01 11:15:13.772  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-01 11:15:13.772  2653  2675 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-01 11:15:13.772  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-01 11:15:13.772  2653  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:15:13.772  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-01 11:15:13.772  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-01 11:15:13.772  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-01 11:15:13.772  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-01 11:15:13.773  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-01 11:15:13.773  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-01 11:15:13.773  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-01 11:15:13.773  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-01 11:15:13.773  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-01 11:15:13.773  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-01 11:15:13.774  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-01 11:15:13.774  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-01 11:15:13.775  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-01 11:15:13.775  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-01 11:15:13.775  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-01 11:15:13.775  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-01 11:15:13.775  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-01 11:15:13.775  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-01 11:15:13.775  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-01 11:15:13.775  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-01 11:15:13.775  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-01 11:15:13.775  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-01 11:15:13.775  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-01 11:15:13.775  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-01 11:15:13.777  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-01 11:15:13.777  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-01 11:15:13.777  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-01 11:15:13.777  3784  3836 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-01 11:15:13.777  3784  3836 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-01 11:15:13.778  3784  3836 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-01 11:15:13.778  3784  3836 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 11:15:13.778  3784  3836 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-01 11:15:13.778  3784  3836 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-01 11:15:13.778  3784  3836 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 11:15:13.778  3784  3836 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-01 11:15:13.778  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-01 11:15:13.780  2653  2675 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-01 11:15:13.780  2653  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:15:13.780  2653  2678 D BtGatt.ScanManager: stopping BLe Batch
09-01 11:15:13.782  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-01 11:15:13.784  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-01 11:15:13.784  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-01 11:15:13.786  3784  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 394)
09-01 11:15:13.786  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-01 11:15:13.786  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-01 11:15:13.786  2653  2675 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-01 11:15:13.787  2653  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:15:13.787  2653  2678 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-01 11:15:13.787  3784  3836 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-01 11:15:13.787  3784  3836 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 11:15:13.788  3784  3836 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-01 11:15:13.789  3784  3850 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:15:13.789  3784  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:15:13.789  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:13.789  3784  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:13.790  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:13.790  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.790  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.790  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-01 11:15:13.790  3784  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ac66f1 not in the list
09-01 11:15:13.790  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.791  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
09-01 11:15:13.791  3784  3836 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:13.791  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.791  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.791  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.791  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.791  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:13.791  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:13.791  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.792  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
09-01 11:15:13.792  3784  3836 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-01 11:15:13.793  3784  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:15:13.793  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:13.793  3784  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:13.793  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:13.793  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.793  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.793  3784  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ac66f1 not in the list
09-01 11:15:13.793  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.793  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
09-01 11:15:13.793  3784  3836 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:13.793  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.793  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.793  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.793  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.793  3784  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 394
09-01 11:15:13.794  3784  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 394)
09-01 11:15:13.794  2653  2759 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
09-01 11:15:13.794  3784  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 394)
09-01 11:15:13.794  3784  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 394)
09-01 11:15:13.794  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:13.794  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:13.794  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.794  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
09-01 11:15:13.795  3784  3836 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-01 11:15:13.795  3784  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:15:13.795  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:13.795  3784  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:13.795  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:13.795  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 11:15:13.795  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.795  3784  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ac66f1 not in the list
09-01 11:15:13.795  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.795  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
09-01 11:15:13.795  3784  3836 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:13.795  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.796  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.796  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.796  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.797  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:13.797  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:13.797  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.797  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
09-01 11:15:13.797  3784  3836 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-01 11:15:13.797  3784  3836 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-01 11:15:13.797  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-01 11:15:13.797  3784  3836 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-01 11:15:13.797  3784  3836 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-01 11:15:13.798  2653  2675 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-01 11:15:13.798  2653  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:15:13.798  3784  3836 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-01 11:15:13.798  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-01 11:15:13.798  3784  3836 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-01 11:15:13.798  3784  3836 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-01 11:15:13.798  3784  3836 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-01 11:15:13.798  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-01 11:15:13.798  3784  3836 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-01 11:15:13.798  3784  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:15:13.798  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:13.798  3784  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:13.798  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:13.799  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.799  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.799  3784  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ac66f1 not in the list
09-01 11:15:13.799  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.799  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
09-01 11:15:13.799  3784  3836 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:13.799  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.799  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.799  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.799  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.800  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:13.800  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:13.800  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.800  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
09-01 11:15:13.800  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:13.801  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.801  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.801  3784  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ac66f1 not in the list
09-01 11:15:13.801  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.801  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
09-01 11:15:13.801  3784  3836 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:13.801  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.801  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.801  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.801  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
09-01 11:15:13.801  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:13.801  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.801  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.801  3784  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ac66f1 not in the list
09-01 11:15:13.801  3784  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:15:13.801  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:13.801  3784  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:13.802  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:13.802  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.802  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.802  3784  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ac66f1 not in the list
09-01 11:15:13.802  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.802  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
09-01 11:15:13.802  3784  3836 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:13.802  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.802  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.802  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.802  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.803  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:13.803  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:13.803  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.803  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
09-01 11:15:13.804  3784  3836 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-01 11:15:13.804  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:15:13.804  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-01 11:15:13.805  3784  3836 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-01 11:15:13.805  3784  3836 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-01 11:15:13.805  3784  3784 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-01 11:15:13.805  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-01 11:15:13.805  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-01 11:15:13.806  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:13.806  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-01 11:15:13.806  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-01 11:15:13.806  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-01 11:15:13.806  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.806  3784  3836 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-01 11:15:13.806  3784  3784 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-01 11:15:13.806  3784  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ac66f1 not in the list
09-01 11:15:13.806  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.806  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 11:15:13.806  3784  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-01 11:15:13.806  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 11:15:13.807  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.807  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.807  3784  3852 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:15:13.808  3784  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 11:15:13.808  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 11:15:13.808  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 11:15:13.808  3784  3784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 11:15:13.808  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
09-01 11:15:13.808  3784  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:15:13.808  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:13.808  3784  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:13.808  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:13.808  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.808  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.808  3784  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ac66f1 not in the list
09-01 11:15:13.808  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.808  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
09-01 11:15:13.809  3784  3836 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:13.809  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.809  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.809  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.809  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.809  3784  3852 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-01 11:15:13.809  3784  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-01 11:15:13.809  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:13.809  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:13.809  3784  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-01 11:15:13.809  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.809  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
09-01 11:15:13.810  3784  3784 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-01 11:15:13.810  3784  3836 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-01 11:15:13.811  3784  3836 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-01 11:15:13.811  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-01 11:15:13.812  3784  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 11:15:13.812  3784  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:15:13.812  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:13.812  3784  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:13.812  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:13.813  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.813  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.813  3784  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ac66f1 not in the list
09-01 11:15:13.813  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.813  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
09-01 11:15:13.813  3784  3836 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:13.813  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.813  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.813  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.813  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.814  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:13.814  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:13.814  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.814  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
09-01 11:15:13.816  3784  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:15:13.816  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:13.816  3784  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:13.816  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:13.816  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.816  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.816  3784  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ac66f1 not in the list
09-01 11:15:13.817  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.817  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
09-01 11:15:13.817  3784  3836 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:13.817  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.817  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.817  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.817  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.818  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:13.818  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:13.818  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.818  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
09-01 11:15:13.818  3784  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:15:13.818  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:13.818  3784  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:13.818  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:13.819  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.819  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.819  3784  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ac66f1 not in the list
09-01 11:15:13.819  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.819  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
09-01 11:15:13.819  3784  3836 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:13.819  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.819  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.819  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:13.819  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:13.820  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:13.820  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:13.820  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:13.820  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b72d6 not in the list
09-01 11:15:13.820  3784  3836 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-01 11:15:13.820  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-01 11:15:13.820  3784  3836 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-01 11:15:13.821  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-01 11:15:13.821  3784  3836 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-01 11:15:13.821  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-01 11:15:13.822  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-01 11:15:13.822  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-01 11:15:13.822  3784  3836 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-01 11:15:13.822  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-01 11:15:13.823  3784  3836 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-01 11:15:13.823  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-01 11:15:13.823  3784  3836 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-01 11:15:13.823  3784  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-01 11:15:13.823  3784  3836 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-01 11:15:13.823  3784  3836 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-01 11:15:13.824  3784  3836 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-01 11:15:13.824  3784  3836 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-01 11:15:13.824  3784  3836 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-01 11:15:13.824  3784  3836 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-01 11:15:13.824  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:15:13.824  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@380bdc8 added. We now have 2 listener(s)
09-01 11:15:13.824  3784  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:15:13.826  3784  3836 D BluetoothAdapter: enable(): BT is already enabled..!
09-01 11:15:13.826   875   886 D WifiService: setWifiEnabled: true pid=3784, uid=10000
09-01 11:15:13.826   875   886 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-01 11:15:13.826  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:15:13.827  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@853ee61 added. We now have 3 listener(s)
09-01 11:15:13.827  3784  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:15:13.830  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:15:13.830  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e643d86 added. We now have 4 listener(s)
09-01 11:15:13.830  3784  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:15:13.831  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:15:13.831  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7113647 added. We now have 5 listener(s)
09-01 11:15:13.831  3784  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:15:13.832   875  1949 D WifiService: setWifiEnabled: false pid=3784, uid=10000
09-01 11:15:13.832   875  1949 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-01 11:15:13.835  2653  2670 D BluetoothAdapterState: Current state: ON, message: 23
,09-01 11:15:13.835  2653  2670 D BluetoothAdapterProperties: Setting state to 13
09-01 11:15:13.835  2653  2670 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-01 11:15:13.835  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:15:13.836  2653  2670 D BluetoothAdapterProperties: onBluetoothDisable()
09-01 11:15:13.837  2653  2675 D BluetoothAdapterProperties: Scan Mode:20
09-01 11:15:13.838  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:15:13.838  3784  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:15:13.838  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:13.838  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:13.838  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:15:13.838  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:15:13.838  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:15:13.838  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:15:13.838  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:15:13.838  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:15:13.838  2653  2670 I BluetoothAdapterState: Entering PendingCommandState
09-01 11:15:13.838  3784  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:15:13.839  2653  2670 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-01 11:15:13.839  3784  3836 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:15:13.840  2653  2653 D BluetoothMapService: onReceive
09-01 11:15:13.840  2653  2653 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:15:13.841  2653  2653 D BluetoothMapService: STATE_TURNING_OFF
09-01 11:15:13.841  2653  2653 D BluetoothMapService: MAP Service closeService in
09-01 11:15:13.841  2653  2653 D BluetoothMapMasInstance0: MAP Service shutdown
09-01 11:15:13.841  2653  2653 D ObexServerSockets0: shutdown(block = true)
09-01 11:15:13.841  2653  2653 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-01 11:15:13.842  2653  2798 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-01 11:15:13.842  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:15:13.842  2653  2653 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-01 11:15:13.842  2653  2759 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-01 11:15:13.842  2653  2799 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-01 11:15:13.843  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:15:13.844  2653  2653 I BtOppRfcommListener: stopping Accept Thread
09-01 11:15:13.844  2653  3416 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-01 11:15:13.844  2653  3416 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-01 11:15:13.846  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:15:13.846  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:15:13.846  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:13.846  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:13.846  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:15:13.846  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:15:13.846  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:15:13.846  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:15:13.846  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:15:13.847  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:15:13.847  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:15:13.848  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:15:13.850   875   888 I ActivityManager: Start proc 3855:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-01 11:15:13.851  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-01 11:15:13.851  2653  2653 D HeadsetService: Received stop request...Stopping profile...
09-01 11:15:13.852  1937  2080 D BluetoothHeadset: Proxy object disconnected
09-01 11:15:13.853  2653  2653 V BluetoothAdapterState: isTurningOff()=true
09-01 11:15:13.853  2653  2653 V BluetoothAdapterState: isTurningOn()=false
09-01 11:15:13.853  2653  2653 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:15:13.853  2653  2653 V BluetoothAdapterState: isBleTurningOff()=false
09-01 11:15:13.853  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:15:13.853   875  1306 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-01 11:15:13.853   875  1306 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-01 11:15:13.853   875  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-01 11:15:13.853   875  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-01 11:15:13.854  1345  2051 D BluetoothHeadset: Proxy object disconnected
09-01 11:15:13.854   875   875 D BluetoothHeadset: Proxy object disconnected
09-01 11:15:13.854   875   875 D BluetoothHeadset: Proxy object disconnected
09-01 11:15:13.854   875   875 D BluetoothHeadset: Proxy object disconnected
09-01 11:15:13.855  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:15:13.855  1345  1345 D HeadsetProfile: Bluetooth service disconnected
09-01 11:15:13.857  2653  2653 D A2dpService: Received stop request...Stopping profile...
09-01 11:15:13.858  2653  2781 D A2dpStateMachine: Exit Disconnected: -1
09-01 11:15:13.858   875   875 D BluetoothA2dp: Proxy object disconnected
09-01 11:15:13.863  2653  2653 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-01 11:15:13.863  2653  2653 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-01 11:15:13.864  2653  2653 D HidService: Received stop request...Stopping profile...
,09-01 11:15:13.864  2653  2753 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-01 11:15:13.864  2653  2653 D HidService: Stopping Bluetooth HidService
09-01 11:15:13.864  2653  2753 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 11:15:13.864  2653  2753 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 11:15:13.864  2653  2675 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-01 11:15:13.864  2653  2675 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-01 11:15:13.865  2653  2653 D HealthService: Received stop request...Stopping profile...
09-01 11:15:13.867  2653  2653 D PanService: Received stop request...Stopping profile...
09-01 11:15:13.868  2653  2653 D BluetoothMapService: Received stop request...Stopping profile...
09-01 11:15:13.868  2653  2653 D BluetoothMapService: stop()
,09-01 11:15:13.868  2653  2653 D BluetoothMapAppObserver: deinitObservers()
09-01 11:15:13.868  2653  2653 D BluetoothMapAppObserver: removeReceiver()
09-01 11:15:13.870  2653  2653 V BluetoothAdapterState: isTurningOff()=true
,09-01 11:15:13.870  2653  2653 V BluetoothAdapterState: isTurningOn()=false
,09-01 11:15:13.870   374   873 D CommandListener: Clearing all IP addresses on wlan0
,09-01 11:15:13.870  2653  2653 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:15:13.870  2653  2653 V BluetoothAdapterState: isBleTurningOff()=false
09-01 11:15:13.873   875  1890 D DhcpClient: Clearing IP address
09-01 11:15:13.874  2653  2675 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-01 11:15:13.874  2653  2753 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 11:15:13.874  2653  2753 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 11:15:13.874  2653  2753 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 11:15:13.874  2653  2753 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 11:15:13.874  2653  2753 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 11:15:13.874  2653  2753 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 11:15:13.874  2653  2653 V BluetoothAdapterState: isTurningOff()=true
09-01 11:15:13.874  2653  2653 V BluetoothAdapterState: isTurningOn()=false
,09-01 11:15:13.874  2653  2653 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:15:13.874  2653  2653 V BluetoothAdapterState: isBleTurningOff()=false
09-01 11:15:13.875  2653  2653 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-01 11:15:13.875  2653  2675 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-01 11:15:13.875  2653  2653 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-01 11:15:13.875  2653  2653 V BluetoothAdapterState: isTurningOff()=true
09-01 11:15:13.875  2653  2653 V BluetoothAdapterState: isTurningOn()=false
,09-01 11:15:13.875  2653  2653 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:15:13.875  2653  2653 V BluetoothAdapterState: isBleTurningOff()=false
09-01 11:15:13.876  2653  2653 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-01 11:15:13.876  2653  2675 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-01 11:15:13.876  2653  2653 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-01 11:15:13.876  1514  2483 V NativeCrypto: Read error: ssl=0x9b267c00: I/O error during system call, Connection timed out
09-01 11:15:13.876  2653  2653 V BluetoothAdapterState: isTurningOff()=true
09-01 11:15:13.876  2653  2653 V BluetoothAdapterState: isTurningOn()=false
09-01 11:15:13.876  2653  2653 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:15:13.876  2653  2653 V BluetoothAdapterState: isBleTurningOff()=false
09-01 11:15:13.877  1514  2483 V NativeCrypto: SSL shutdown failed: ssl=0x9b267c00: I/O error during system call, Broken pipe
09-01 11:15:13.879   875  2233 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
09-01 11:15:13.879   875  1879 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
09-01 11:15:13.880   374   873 D CommandListener: Setting iface cfg
09-01 11:15:13.881   875  1892 D DhcpClient: Receive thread stopped
09-01 11:15:13.882   875  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-01 11:15:13.882   875  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-01 11:15:13.884   402   402 E Parcel  : Reading a NULL string not supported here.
09-01 11:15:13.886   875  1306 D WifiStateMachine: Start Disconnecting Watchdog 1
,09-01 11:15:13.887  2653  2653 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-01 11:15:13.887  2653  2653 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-01 11:15:13.887   875  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-01 11:15:13.887  2653  2653 D BluetoothMapService: MAP Service closeService in
09-01 11:15:13.888  2653  2653 V BluetoothAdapterState: isTurningOff()=true
09-01 11:15:13.888  2653  2653 V BluetoothAdapterState: isTurningOn()=false
09-01 11:15:13.888  2653  2653 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:15:13.888  2653  2653 V BluetoothAdapterState: isBleTurningOff()=false
09-01 11:15:13.888  2653  2670 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-01 11:15:13.888  2653  2670 D BluetoothAdapterProperties: Setting state to 15
09-01 11:15:13.888  2653  2670 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-01 11:15:13.888   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:15:13.888  1345  1359 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:15:13.889   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:15:13.889   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-01 11:15:13.889  2653  2670 I BluetoothAdapterState: Entering BleOnState
09-01 11:15:13.889  1345  1364 D BluetoothPan: onBluetoothStateChange on: false
09-01 11:15:13.889  2653  2653 D BluetoothMapService: cleanup()
09-01 11:15:13.889  1345  2008 D BluetoothPbap: onBluetoothStateChange: up=false
09-01 11:15:13.889  2653  2653 D BluetoothMapService: MAP Service closeService in
09-01 11:15:13.890  1937  2080 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-01 11:15:13.891  1345  2051 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-01 11:15:13.891  1345  1345 D BluetoothA2dp: Proxy object disconnected
09-01 11:15:13.891  1345  1345 D BluetoothMap: Proxy object disconnected
09-01 11:15:13.891  1345  1345 D MapProfile: Bluetooth service disconnected
09-01 11:15:13.893   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:15:13.893  1345  2008 D BluetoothMap: onBluetoothStateChange: up=false
09-01 11:15:13.894   875  1308 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-01 11:15:13.894  1345  1359 D BluetoothA2dp: onBluetoothStateChange: up=false
09-01 11:15:13.896  2653  2670 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-01 11:15:13.896  2653  2670 D BluetoothAdapterProperties: Setting state to 16
09-01 11:15:13.896  2653  2670 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-01 11:15:13.897  2653  2670 D BluetoothAdapterProperties: onBleDisable
,09-01 11:15:13.897  2653  2670 I BluetoothAdapterState: Entering PendingCommandState
09-01 11:15:13.897  2653  2672 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-01 11:15:13.898  2653  2753 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-01 11:15:13.898   875  1879 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-01 11:15:13.898  2653  2753 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 11:15:13.902  2653  2675 D BluetoothAdapterProperties: Scan Mode:20
09-01 11:15:13.906  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:15:13.906  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:15:13.906  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:13.906  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:13.906  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:15:13.906  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:15:13.906  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:15:13.906  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:15:13.906  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:15:13.906  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 11:15:13.907  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:15:13.914  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:15:13.914  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:15:13.914  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:13.914  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:13.914  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:15:13.914  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:15:13.914  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:15:13.914  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:15:13.914  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:15:13.915  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:15:13.915  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:15:13.916  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:15:13.917  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:15:13.929   374   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-01 11:15:13.940  3855  3855 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-01 11:15:13.946   374   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-01 11:15:13.946   374   873 D CommandListener: Clearing all IP addresses on wlan0
,09-01 11:15:13.947   875  1308 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-01 11:15:13.947   875  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-01 11:15:13.953  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:13.953   875  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-01 11:15:13.954  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:15:13.954  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:15:13.954  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:13.954  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:13.954  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:15:13.954  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:15:13.954  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:15:13.954  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:15:13.954  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:15:13.955  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:15:13.955  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:15:13.956   875   892 D Tethering: MasterInitialState.processMessage what=3
09-01 11:15:13.958  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:15:13.958  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:15:13.958  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:13.958  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:13.958  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:15:13.958  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:15:13.958  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:15:13.958  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:15:13.958  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:15:13.959  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:15:13.959  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:15:13.960   875  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-01 11:15:13.960  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:13.964  2034  2302 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-01 11:15:13.971  3855  3855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-01 11:15:13.977  1514  1514 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 11:15:13.977   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@81a4402:true
,09-01 11:15:13.990   875  2245 I ActivityManager: Start proc 3876:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-01 11:15:14.010   374   873 E Netd    : netlink response contains error (No such file or directory)
,09-01 11:15:14.011   875  1308 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-01 11:15:14.011   875  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-01 11:15:14.012  3855  3855 D LocalBluetoothProfileManager: Adding local MAP profile
,09-01 11:15:14.015  3855  3855 D BluetoothMap: Create BluetoothMap proxy object
,09-01 11:15:14.022  3855  3855 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-01 11:15:14.028  3876  3876 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-01 11:15:14.037  3855  3855 D DockEventReceiver: finishStartingService: stopping service
,09-01 11:15:14.044   875  2233 I ActivityManager: Killing 1698:android.process.acore/u0a5 (adj 15): empty #17
,09-01 11:15:14.105  2653  2675 I bt_hci  : shut_down
,09-01 11:15:14.131  2653  2680 D bt_hwcfg: hw_epilog_process
,09-01 11:15:14.131  2653  2680 I bt_vendor: low_power_mode_cb
,09-01 11:15:14.151  2653  2680 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-01 11:15:14.151  2653  2680 I bt_vendor: epilog_cb
09-01 11:15:14.151  2653  2680 I bt_hci  : epilog_finished_callback
,09-01 11:15:14.154  2653  2675 I bt_hci_h4: hal_close
,09-01 11:15:14.155  2653  2675 I bt_userial_vendor: device fd = 51 close
,09-01 11:15:14.224  3876  3876 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at java.io.File.exists(File.java:361)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 11:15:14.224  3876  3876 D StrictMode: 	,at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-01 11:15:14.224  3876  3876 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-01 11:15:14.224  3876  3876 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-01 11:15:14.224  3876  3876 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.r.e.b(PG:170)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-01 11:15:14.224  3876  3876 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.r.k.d(PG:583)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.r.e.b(PG:170)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-01 11:15:14.224  3876  3876 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at java.io.File.exists(File.java:361)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 11:15:14.224  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-01 11:15:14.225  3876  3876 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 11:15:14.225  3876  3876 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 11:15:14.225  3876  3876 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-01 11:15:14.225  3876  3876 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-01 11:15:14.225  3876  3876 D StrictMode: 	at java.io.File.exists(File.java:361)
09-01 11:15:14.225  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-01 11:15:14.225  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 11:15:14.225  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 11:15:14.225  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 11:15:14.225  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 11:15:14.225  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 11:15:14.225  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 11:15:14.225  3876  3876 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 11:15:14.225  3876  3876 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 11:15:14.225  3876  3876 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 11:15:14.225  3876  3876 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 11:15:14.225  3876  3876 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:15:14.225  3876  3876 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 11:15:14.225  3876  3876 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 11:15:14.225  3876  3876 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:15:14.225  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 11:15:14.225  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-01 11:15:14.225  3876  3876 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 11:15:14.225  3876  3876 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 11:15:14.225  3876  3876 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-01 11:15:14.225  3876  3876 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-01 11:15:14.225  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-01 11:15:14.225  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 11:15:14.225  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 11:15:14.225  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 11:15:14.225  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 11:15:14.225  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 11:15:14.225  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 11:15:14.225  3876  3876 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 11:15:14.225  3876  3876 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 11:15:14.225  3876  3876 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 11:15:14.225  3876  3876 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 11:15:14.225  3876  3876 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:15:14.225  3876  3876 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 11:15:14.225  3876  3876 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 11:15:14.225  3876  3876 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:15:14.225  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 11:15:14.225  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-01 11:15:14.259   875   886 I ActivityManager: Start proc 3907:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,09-01 11:15:14.260   875   886 I ActivityManager: Killing 3606:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-01 11:15:14.309  3784  3784 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-01 11:15:14.324  2653  2672 D bt_stack_manager: event_shut_down_stack finished.
,09-01 11:15:14.324  2653  2670 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-01 11:15:14.328  2653  2653 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-01 11:15:14.328  2653  2670 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-01 11:15:14.328  2653  2653 D BtGatt.GattService: Received stop request...Stopping profile...
09-01 11:15:14.328  2653  2653 D BtGatt.GattService: stop()
,09-01 11:15:14.328  2653  2653 D BtGatt.AdvertiseManager: advertise clients cleared
09-01 11:15:14.329  2653  2653 V BluetoothAdapterState: isTurningOff()=false
09-01 11:15:14.329  2653  2653 V BluetoothAdapterState: isTurningOn()=false
09-01 11:15:14.330  2653  2653 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:15:14.330  2653  2653 V BluetoothAdapterState: isBleTurningOff()=true
09-01 11:15:14.330  2653  2670 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-01 11:15:14.331  2653  2670 D BluetoothAdapterProperties: Setting state to 10
09-01 11:15:14.331  2653  2670 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-01 11:15:14.332   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-01 11:15:14.332  2653  2670 I BluetoothAdapterState: Entering OffState
,09-01 11:15:14.345  2653  2653 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-01 11:15:14.345  2653  2653 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-01 11:15:14.345  2653  2653 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-01 11:15:14.346  2653  2672 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-01 11:15:14.348  2653  2672 D bt_stack_manager: event_clean_up_stack finished.
,09-01 11:15:14.351  3907  3907 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,09-01 11:15:14.357  2653  2653 I art     : System.exit called, status: 0
,09-01 11:15:14.357  2653  2653 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-01 11:15:14.436   875  1964 I ActivityManager: Process com.android.bluetooth (pid 2653) has died
,09-01 11:15:14.636  3907  3927 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,09-01 11:15:14.636  3907  3927 I Babel_SMS: MmsConfig.loadMmsSettings
,09-01 11:15:14.649  3907  3927 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-01 11:15:14.649  3907  3927 I Babel_SMS: MmsConfig.loadFromDatabase
,09-01 11:15:14.671  3907  3927 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,09-01 11:15:14.671  3907  3927 I Babel_SMS: MmsConfig.loadFromResources
,09-01 11:15:14.678  3907  3927 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-01 11:15:14.680  3907  3927 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-01 11:15:14.682  3876  3903 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-01 11:15:14.699  3907  3907 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-01 11:15:14.703  3907  3907 I Babel_Crash: startup - clean
,09-01 11:15:14.739  3907  3907 I Babel_telephony: TeleModule.launchCompleted
,09-01 11:15:14.752   875  1371 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-01 11:15:14.757  3907  3907 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,09-01 11:15:14.764  3907  3907 W Babel   : BAM#gBA: invalid account id: -1
,09-01 11:15:14.764  3907  3907 W Babel   : BAM#gBA: invalid account id: -1
,09-01 11:15:14.765  3907  3907 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,09-01 11:15:14.774   875  2233 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-01 11:15:14.778  3907  3932 I Babel   : deleted: false for 0
,09-01 11:15:14.800  3855  3855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-01 11:15:14.838   875  1954 I ActivityManager: Start proc 3935:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,09-01 11:15:14.843  3855  3855 D DockEventReceiver: finishStartingService: stopping service
,09-01 11:15:14.855  3907  3907 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-01 11:15:14.891   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7dc5f6b:true
,09-01 11:15:14.927  3907  3907 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-01 11:15:14.953  3907  3907 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-01 11:15:14.959  3907  3907 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-01 11:15:14.962  3907  3907 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-01 11:15:14.976  3907  3907 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-01 11:15:14.993  3907  3907 I vclib   : onServiceConnected
,09-01 11:15:15.011  3935  3935 D AdapterServiceConfig: Adding HeadsetService
,09-01 11:15:15.011  3935  3935 D AdapterServiceConfig: Adding A2dpService
09-01 11:15:15.011  3935  3935 D AdapterServiceConfig: Adding HidService
09-01 11:15:15.012  3935  3935 D AdapterServiceConfig: Adding HealthService
,09-01 11:15:15.012  3935  3935 D AdapterServiceConfig: Adding PanService
09-01 11:15:15.012  3935  3935 D AdapterServiceConfig: Adding GattService
,09-01 11:15:15.012  3935  3935 D AdapterServiceConfig: Adding BluetoothMapService
,09-01 11:15:15.017   875  1949 I ActivityManager: Killing 3621:com.android.musicfx/u0a18 (adj 15): empty #17
,09-01 11:15:15.067  1514  1514 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 11:15:15.085  1719  1719 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-01 11:15:15.089  1719  1719 D SystemUpdateService: onCreate
,09-01 11:15:15.097  1719  1719 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-01 11:15:15.104  1719  3947 I SystemUpdateService: active receiver: enabled
,09-01 11:15:15.111  1719  3947 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-01 11:15:15.116  1719  3947 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-01 11:15:15.116  1719  3947 I SystemUpdateService: now status is 0 (complete)
,09-01 11:15:15.116  1719  3947 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-01 11:15:15.116  1719  3947 I SystemUpdateService: file has been verified
,09-01 11:15:15.116  1719  1719 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-01 11:15:15.117  1719  3947 I SystemUpdateService: OTA package size = 12249756
,09-01 11:15:15.119  1719  2449 I iu.UploadsManager: num queued entries: 0
09-01 11:15:15.120  1719  2449 I iu.UploadsManager: num updated entries: 0
09-01 11:15:15.121  1719  2449 I iu.SyncManager: NEXT; no task,
,09-01 11:15:15.132  1719  3947 I SystemUpdateService: showing system update notification
,09-01 11:15:15.144  1719  1719 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-01 11:15:15.145  1719  1719 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-01 11:15:15.163   875  1964 I ActivityManager: Start proc 3949:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-01 11:15:15.165  1719  1719 D SystemUpdateService: onDestroy
,09-01 11:15:15.196  3949  3949 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-01 11:15:15.199  3949  3949 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-01 11:15:15.208  3949  3949 D SprintDMHelper: simOperator: 
09-01 11:15:15.208  3949  3949 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-01 11:15:15.229   875  1371 I ActivityManager: Start proc 3961:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-01 11:15:15.232   875  1371 I ActivityManager: Killing 2187:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-01 11:15:15.380   875  2245 I ActivityManager: Start proc 3976:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-01 11:15:15.388  3907  3975 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-01 11:15:15.393   875  1964 I ActivityManager: Killing 3644:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-01 11:15:15.485  3976  3976 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-01 11:15:15.554  3976  3976 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-01 11:15:15.554  3976  3976 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-01 11:15:15.554  3976  3976 I GAv4    :   adb logcat -s GAv4
,09-01 11:15:15.571  3976  3976 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-01 11:15:15.577  3976  3976 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-01 11:15:15.613  3976  3993 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-01 11:15:15.724  3976  3976 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-01 11:15:15.775  3976  3976 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-01 11:15:15.787  3976  3976 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 3563-3567)
,09-01 11:15:15.787  3976  3976 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-01 11:15:15.797  3976  3976 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {969add1}
,09-01 11:15:15.798  3976  3976 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-01 11:15:15.798  3976  3976 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-01 11:15:15.808  3976  3976 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-01 11:15:15.810  3976  3976 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-01 11:15:15.828  3976  3976 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-01 11:15:15.842  3976  3976 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-01 11:15:15.842  3976  3976 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-01 11:15:15.842  3976  3976 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-01 11:15:15.842  3976  3976 I Adreno  : Build Date                       : 10/20/15
09-01 11:15:15.842  3976  3976 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-01 11:15:15.842  3976  3976 I Adreno  : Local Branch                     : M14
09-01 11:15:15.842  3976  3976 I Adreno  : Remote Branch                    : 
09-01 11:15:15.842  3976  3976 I Adreno  : Remote Branch                    : 
09-01 11:15:15.842  3976  3976 I Adreno  : Reconstruct Branch               : 
,09-01 11:15:15.899  3976  3976 I NSApplication: Starting up...
,09-01 11:15:15.910  3976  4022 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-01 11:15:15.945   875  2233 I ActivityManager: Start proc 4027:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-01 11:15:15.947   875  2233 I ActivityManager: Killing 3570:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-01 11:15:16.028  4027  4027 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-01 11:15:16.216   875  1967 I ActivityManager: Killing 3705:com.google.android.apps.books/u0a34 (adj 15): empty #17
,09-01 11:15:16.324   875  1949 I ActivityManager: Start proc 4041:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-01 11:15:16.405  4041  4041 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-01 11:15:16.458  4041  4041 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-01 11:15:16.484   875  1982 I ActivityManager: Killing 2966:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-01 11:15:16.843   875   886 D WifiService: setWifiEnabled: true pid=3784, uid=10000
,09-01 11:15:16.844   875   886 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-01 11:15:16.857   875  1306 D WifiConfigStore: Loading config and enabling all networks 
,09-01 11:15:16.866  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 11:15:16.867  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:15:16.867  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:16.867  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:16.867  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:15:16.867  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:15:16.867  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:15:16.867  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:15:16.867  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:15:16.867  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 11:15:16.867  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-01 11:15:16.871  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 11:15:16.871  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:15:16.871  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:16.871  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:16.871  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:15:16.871  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:15:16.871  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:15:16.871  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:15:16.871  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 11:15:16.871  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:15:16.872  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-01 11:15:16.891   875  1306 D WifiConfigStore: loaded 0 passpoint configs
,09-01 11:15:16.892   875  1306 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-01 11:15:16.893   875  1306 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-01 11:15:16.894   875  1306 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-01 11:15:16.894   875  1306 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-01 11:15:16.894   875  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-01 11:15:16.895   875  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-01 11:15:16.909   374   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-01 11:15:16.909   875  1306 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.00 rxSuccessRate=11.00 delta 1000 -> 994
,09-01 11:15:16.911   374   873 D CommandListener: Setting iface cfg
,09-01 11:15:16.912   875  1305 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)',
09-01 11:15:16.913   875  1305 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-01 11:15:16.919   875  1305 D WifiNative-HAL: p2pGetDeviceAddress
,09-01 11:15:16.919   875  1306 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-01 11:15:16.919   875  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 11:15:16.920   875  1305 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-01 11:15:16.928   875  1306 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-01 11:15:16.996   875  1306 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-01 11:15:16.999  1463  1463 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-01 11:15:17.447  1463  1463 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-01 11:15:17.500  1463  1463 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-01 11:15:17.501  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-01 11:15:17.506   875  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-01 11:15:17.519   875  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-01 11:15:17.521   875  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-01 11:15:17.522   875  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 11:15:17.556   875  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 11:15:17.580   374   873 D CommandListener: Setting iface cfg
,09-01 11:15:17.581   875  1306 D WifiStateMachine: Start Dhcp Watchdog 2
,09-01 11:15:17.602   875  1308 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-01 11:15:17.607   875  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-01 11:15:17.621   875  4074 D DhcpClient: Receive thread started
,09-01 11:15:17.703   875  1306 E native  : do suspend false
,09-01 11:15:17.723   875  1890 D DhcpClient: Broadcasting DHCPDISCOVER
,09-01 11:15:17.739   875  4074 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172687, domain null
,09-01 11:15:17.740   875  1890 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172687 seconds
,09-01 11:15:17.744   875  1890 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-01 11:15:17.776   875  4074 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-01 11:15:17.778   875  1890 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-01 11:15:17.783   374   873 D CommandListener: Setting iface cfg
,09-01 11:15:17.793   875  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-01 11:15:17.794   875  1890 D DhcpClient: Scheduling renewal in 86399s
,09-01 11:15:17.807   875  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-01 11:15:17.810   875  1306 D WifiConfigStore: No blacklist allowed without epno enabled
,09-01 11:15:17.811   875  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-01 11:15:17.812   875  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-01 11:15:17.814   875  1308 D ConnectivityService: Adding iface wlan0 to network 101
,09-01 11:15:17.827   875  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-01 11:15:17.884   875  1308 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-01 11:15:17.884   875  1308 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-01 11:15:17.885   875  1308 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-01 11:15:17.886   875  1308 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-01 11:15:17.887   875  1308 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-01 11:15:17.893   875  1308 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-01 11:15:17.899   875  1308 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-01 11:15:17.899   875  1308 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-01 11:15:17.899   875  1308 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,09-01 11:15:17.899   875  1308 D ConnectivityService:    accepting network in place of null
09-01 11:15:17.900   875  1308 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-01 11:15:17.906   875  1306 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-01 11:15:17.908   875  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-01 11:15:17.932   374   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-01 11:15:17.963   374   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-01 11:15:17.968   875  1308 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-01 11:15:17.969   875  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-01 11:15:17.971   875  1308 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-01 11:15:17.973   875   892 D Tethering: MasterInitialState.processMessage what=3
09-01 11:15:17.978  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 11:15:17.978  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:15:17.978  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:17.978  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:17.978  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:15:17.978  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:15:17.978  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:15:17.978  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:15:17.978  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:15:17.979  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:15:17.979  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:15:17.984  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:15:17.984  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:15:17.984  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:17.984  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:17.984  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:15:17.984  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:15:17.984  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:15:17.984  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:15:17.984  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:15:17.984  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:15:17.985  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 11:15:18.001  1719  1719 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-01 11:15:18.010  1719  1719 D SystemUpdateService: onCreate
,09-01 11:15:18.018  1719  1719 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-01 11:15:18.022  1719  4083 I SystemUpdateService: active receiver: enabled
,09-01 11:15:18.027  1719  4083 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-01 11:15:18.029  1719  4083 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-01 11:15:18.031  1719  4083 I SystemUpdateService: now status is 0 (complete)
09-01 11:15:18.031  1719  4083 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-01 11:15:18.031  1719  4083 I SystemUpdateService: file has been verified
09-01 11:15:18.031  1719  4083 I SystemUpdateService: OTA package size = 12249756
,09-01 11:15:18.036  1719  4083 I SystemUpdateService: showing system update notification
,09-01 11:15:18.042  1719  1719 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-01 11:15:18.044  1719  4086 I MDM     : [175] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-01 11:15:18.044  1719  4086 W BaseAppContext: Using Auth Proxy for data requests.
,09-01 11:15:18.046  1719  4086 V GoogleAuthProtoRequest: [175] a.<init>: mAccountName set to: thalitester@gmail.com
,09-01 11:15:18.049  1719  1719 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-01 11:15:18.050  1719  2449 I iu.UploadsManager: num queued entries: 0
,09-01 11:15:18.051  1719  1719 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-01 11:15:18.051  1719  2449 I iu.UploadsManager: num updated entries: 0
,09-01 11:15:18.053  1719  2449 I iu.SyncManager: NEXT; no task
,09-01 11:15:18.054  1719  1719 D SystemUpdateService: onDestroy
09-01 11:15:18.057  3949  3949 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-01 11:15:18.059  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-01 11:15:18.061  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 11:15:18.061   875  4073 D NetlinkSocketObserver: NeighborEvent{elapsedMs=135842, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
09-01 11:15:18.062  3949  3949 D SprintDMHelper: simOperator: 
,09-01 11:15:18.062  3949  3949 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-01 11:15:18.093  1514  2045 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-01 11:15:18.093  1514  2045 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-01 11:15:18.093  1514  2045 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 11:15:18.093  1514  2045 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 11:15:18.108  1719  4086 E MDM     : [175] SitrepService.a: Error sending sitrep.
,09-01 11:15:18.969   875  1308 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-01 11:15:19.120   875  4072 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=89.25.215.83,2a00:1450:400d:806::200e
,09-01 11:15:19.637  3907  4088 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-01 11:15:19.648   875  1967 I ActivityManager: Killing 3751:com.qualcomm.timeservice/1000 (adj 15): empty #17
,09-01 11:15:19.852   875  2245 D WifiService: setWifiEnabled: false pid=3784, uid=10000
,09-01 11:15:19.852   875  2245 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-01 11:15:19.891  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-01 11:15:19.897   875  1306 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-01 11:15:19.898   875  1306 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-01 11:15:19.898   875  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-01 11:15:19.898   875  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 11:15:19.920   875  1890 D DhcpClient: Clearing IP address
,09-01 11:15:19.921   374   873 D CommandListener: Setting iface cfg
,09-01 11:15:19.927   374   873 D CommandListener: Clearing all IP addresses on wlan0
,09-01 11:15:19.928   875  4074 D DhcpClient: Receive thread stopped
,09-01 11:15:19.937   875  4072 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:806::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,09-01 11:15:19.938  1514  4095 V NativeCrypto: Read error: ssl=0x9a6c2400: I/O error during system call, Connection timed out
09-01 11:15:19.939   875  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
,09-01 11:15:19.940  1514  4095 V NativeCrypto: SSL shutdown failed: ssl=0x9a6c2400: I/O error during system call, Broken pipe
,09-01 11:15:19.946   875  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-01 11:15:19.946   875  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-01 11:15:19.955   402   402 E Parcel  : Reading a NULL string not supported here.
,09-01 11:15:19.956   875  1306 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-01 11:15:19.963   875  1308 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-01 11:15:19.968   875  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-01 11:15:20.000   374   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-01 11:15:20.024   374   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-01 11:15:20.024   374   873 D CommandListener: Clearing all IP addresses on wlan0
,09-01 11:15:20.025   875  1308 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-01 11:15:20.025   875  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-01 11:15:20.028   875   892 D Tethering: MasterInitialState.processMessage what=3
,09-01 11:15:20.030  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 11:15:20.030  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:15:20.030  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:20.030  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:20.030  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:15:20.030  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:15:20.030  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:15:20.030  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:15:20.030  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 11:15:20.030  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:15:20.031  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:15:20.031  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 11:15:20.032  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:15:20.032  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:20.032  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:20.032  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:15:20.032  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:15:20.032  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:15:20.032  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:15:20.032  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:15:20.032  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:15:20.032  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-01 11:15:20.040   875  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-01 11:15:20.045   875  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-01 11:15:20.049  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:15:20.049  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:15:20.049  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:20.049  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:20.049  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:15:20.049  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:15:20.049  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:15:20.049  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:15:20.049  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:15:20.049  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:15:20.050  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:15:20.050  2034  2302 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:15:20.051  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:15:20.051  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:15:20.051  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:20.051  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:20.051  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:15:20.051  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:15:20.051  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:15:20.051  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:15:20.051  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:15:20.051  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:15:20.051  1719  1719 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-01 11:15:20.051  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 11:15:20.056  1719  1719 D SystemUpdateService: onCreate
,09-01 11:15:20.059  1719  1719 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-01 11:15:20.073  1719  1719 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-01 11:15:20.075  1719  2449 I iu.UploadsManager: num queued entries: 0
09-01 11:15:20.076  1719  2449 I iu.UploadsManager: num updated entries: 0
,09-01 11:15:20.080  1719  1719 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-01 11:15:20.081  1719  1719 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-01 11:15:20.083  3949  3949 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-01 11:15:20.086  3949  3949 D SprintDMHelper: simOperator: 
,09-01 11:15:20.086  3949  3949 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-01 11:15:20.120   374   873 E Netd    : netlink response contains error (No such file or directory)
,09-01 11:15:20.120  1719  2449 I iu.SyncManager: NEXT; no task
,09-01 11:15:20.121   875  1308 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-01 11:15:20.121   875  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-01 11:15:20.124  3907  4108 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-01 11:15:20.126  1719  4105 I SystemUpdateService: active receiver: enabled
,09-01 11:15:20.131  1719  4105 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-01 11:15:20.132  1719  4105 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-01 11:15:20.133  1719  4105 I SystemUpdateService: now status is 0 (complete)
09-01 11:15:20.133  1719  4105 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-01 11:15:20.133  1719  4105 I SystemUpdateService: file has been verified
,09-01 11:15:20.133  1719  4105 I SystemUpdateService: OTA package size = 12249756
,09-01 11:15:20.136  1719  4105 I SystemUpdateService: showing system update notification
,09-01 11:15:20.145  1719  1719 D SystemUpdateService: onDestroy
,09-01 11:15:21.730  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 11:15:21.764  1514  2301 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-01 11:15:21.764  1514  2301 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-01 11:15:21.764  1514  2301 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 11:15:21.765  1514  2301 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 11:15:21.790  3477  3477 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-01 11:15:21.790  3477  3477 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-01 11:15:21.791  3477  3477 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-01 11:15:22.918   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@93305df:true
,09-01 11:15:22.920  3935  3935 D BluetoothAdapterState: make() - Creating AdapterState
,09-01 11:15:22.929  3935  3935 I bt_bluedroid: init
,09-01 11:15:22.929  3935  4119 I BluetoothAdapterState: Entering OffState
,09-01 11:15:22.935  3935  4120 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-01 11:15:22.936  3935  4120 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-01 11:15:22.936  3935  4120 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-01 11:15:22.936  3935  4120 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-01 11:15:22.938  3935  3935 I bt_bluedroid: get_profile_interface socket
,09-01 11:15:22.943  3935  3935 I bt_bluedroid: get_profile_interface sdp
,09-01 11:15:22.946  3935  4123 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-01 11:15:22.949  3935  3945 I bt_bluedroid: config_hci_snoop_log
,09-01 11:15:22.950   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-01 11:15:22.952  3935  4123 D BluetoothAdapterProperties: Name is: Nexus 6
,09-01 11:15:22.958  3935  4119 D BluetoothAdapterState: Current state: OFF, message: 0
,09-01 11:15:22.958  3935  4119 D BluetoothAdapterProperties: Setting state to 14
09-01 11:15:22.959  3935  4119 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-01 11:15:22.964  3935  4119 D BluetoothBondStateMachine: make
,09-01 11:15:22.969  3935  4124 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-01 11:15:22.976  3935  4119 I BluetoothAdapterState: Entering PendingCommandState
,09-01 11:15:22.978  3935  3935 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-01 11:15:22.984  3935  3935 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b148f
,09-01 11:15:22.986  3935  3935 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-01 11:15:22.987  3935  3935 D BtGatt.GattService: Received start request. Starting profile...
,09-01 11:15:22.987  3935  3935 D BtGatt.GattService: start()
09-01 11:15:22.988  3935  3935 I bt_bluedroid: get_profile_interface gatt
,09-01 11:15:22.989  3935  3935 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b148f
09-01 11:15:22.989  3935  3935 D BtGatt.AdvertiseManager: advertise manager created
,09-01 11:15:22.997  3935  3935 V BluetoothAdapterState: isTurningOff()=false
09-01 11:15:22.997  3935  3935 V BluetoothAdapterState: isTurningOn()=false
09-01 11:15:22.997  3935  3935 V BluetoothAdapterState: isBleTurningOn()=true
,09-01 11:15:22.997  3935  3935 V BluetoothAdapterState: isBleTurningOff()=false
09-01 11:15:22.998  3935  4119 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-01 11:15:22.999  3935  4119 I bt_bluedroid: enable
09-01 11:15:22.999  3935  4120 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-01 11:15:23.000  3935  4120 I bt_hci  : start_up
,09-01 11:15:23.020  3935  4120 I bt_vendor: alloc value 0xb3a39189
,09-01 11:15:23.020  3935  4120 I bt_vendor: init
09-01 11:15:23.021  3935  4120 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-01 11:15:23.021  3935  4120 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-01 11:15:23.131  3935  4120 D bt_hci  : start_up starting async portion
,09-01 11:15:23.132  3935  4127 I bt_hci  : event_finish_startup
09-01 11:15:23.133  3935  4127 I bt_hci_h4: hal_open
09-01 11:15:23.134  3935  4127 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-01 11:15:23.141  3935  4127 I bt_userial_vendor: device fd = 51 open
,09-01 11:15:23.171  3935  4127 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-01 11:15:23.202  3935  4127 D bt_hwcfg: Chipset BCM4354A2
,09-01 11:15:23.202  3935  4127 D bt_hwcfg: Target name = [BCM4354A2]
09-01 11:15:23.203  3935  4127 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-01 11:15:23.859  3935  4127 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-01 11:15:23.861  3935  4127 D bt_hwcfg: Settlement delay -- 100 ms
09-01 11:15:23.861  3935  4127 I bt_hwcfg: Setting fw settlement delay to 100 
,09-01 11:15:23.977  3935  4127 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-01 11:15:23.979  3935  4127 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-01 11:15:24.008  3935  4127 I bt_hwcfg: vendor lib fwcfg completed
,09-01 11:15:24.009  3935  4127 I bt_vendor: firmware callback
09-01 11:15:24.009  3935  4127 I bt_hci  : firmware_config_callback
,09-01 11:15:24.020  3935  4129 I bt_btu  : btu_task pending for preload complete event
,09-01 11:15:24.021  3935  4129 I bt_btu_task: Bluetooth chip preload is complete
09-01 11:15:24.021  3935  4129 I bt_btu  : btu_task received preload complete event
,09-01 11:15:24.032  3935  4129 I         : BTE_InitTraceLevels -- TRC_HCI
,09-01 11:15:24.033  3935  4129 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-01 11:15:24.033  3935  4129 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-01 11:15:24.033  3935  4129 I         : BTE_InitTraceLevels -- TRC_AVDT
09-01 11:15:24.034  3935  4129 I         : BTE_InitTraceLevels -- TRC_AVRC
09-01 11:15:24.034  3935  4129 I         : BTE_InitTraceLevels -- TRC_A2D
09-01 11:15:24.034  3935  4129 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-01 11:15:24.034  3935  4129 I         : BTE_InitTraceLevels -- TRC_BTM
09-01 11:15:24.035  3935  4129 I         : BTE_InitTraceLevels -- TRC_GAP
09-01 11:15:24.035  3935  4129 I         : BTE_InitTraceLevels -- TRC_PAN
09-01 11:15:24.035  3935  4129 I         : BTE_InitTraceLevels -- TRC_SDP
,09-01 11:15:24.035  3935  4129 I         : BTE_InitTraceLevels -- TRC_GATT
09-01 11:15:24.036  3935  4129 I         : BTE_InitTraceLevels -- TRC_SMP
09-01 11:15:24.036  3935  4129 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-01 11:15:24.036  3935  4129 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-01 11:15:24.170  3935  4129 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39b6d9d
09-01 11:15:24.170  3935  4129 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39b6d9d 
,09-01 11:15:24.194  3935  4123 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-01 11:15:24.195  3935  4123 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-01 11:15:24.196  3935  4123 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-01 11:15:24.198  3935  4123 D BluetoothAdapterProperties: Name is: Nexus 6
,09-01 11:15:24.201  3935  4123 D BluetoothAdapterProperties: Scan Mode:20
09-01 11:15:24.201  3935  4123 D BluetoothAdapterProperties: Discoverable Timeout:120
09-01 11:15:24.202  3935  4123 D bt_hci  : do_postload posting postload work item
,09-01 11:15:24.202  3935  4127 I bt_hci  : event_postload
09-01 11:15:24.202  3935  4127 I bt_vendor: sco_config_cb
09-01 11:15:24.202  3935  4127 I bt_hci  : sco_config_callback postload finished.
,09-01 11:15:24.204  3935  4123 D bt_bte_conf: Device ID record 1 : primary
09-01 11:15:24.204  3935  4123 D bt_bte_conf:   vendorId            = 000f
,09-01 11:15:24.204  3935  4123 D bt_bte_conf:   vendorIdSource      = 0001
09-01 11:15:24.204  3935  4123 D bt_bte_conf:   product             = 1200
09-01 11:15:24.204  3935  4123 D bt_bte_conf:   version             = 1436
09-01 11:15:24.204  3935  4123 D bt_bte_conf:   clientExecutableURL = 
09-01 11:15:24.204  3935  4123 D bt_bte_conf:   serviceDescription  = 
09-01 11:15:24.205  3935  4123 D bt_bte_conf:   documentationURL    = 
09-01 11:15:24.205  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:15:24.205  3935  4123 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-01 11:15:24.205  3935  4120 D bt_stack_manager: event_start_up_stack finished
09-01 11:15:24.207  3935  4119 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-01 11:15:24.207  3935  4119 D BluetoothAdapterProperties: Setting state to 15
09-01 11:15:24.207  3935  4119 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-01 11:15:24.209  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:15:24.210  3935  4119 I BluetoothAdapterState: Entering BleOnState
09-01 11:15:24.211  3935  4127 I bt_vendor: low_power_mode_cb
,09-01 11:15:24.213  3935  4119 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-01 11:15:24.214  3935  4119 D BluetoothAdapterProperties: Setting state to 11
09-01 11:15:24.214  3935  4119 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-01 11:15:24.220  3935  3935 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b148f
09-01 11:15:24.221  3935  3935 D HeadsetService: Received start request. Starting profile...
,09-01 11:15:24.223  3935  3935 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-01 11:15:24.224  3935  3935 D HeadsetStateMachine: make
09-01 11:15:24.235  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:15:24.238  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:15:24.240  3935  3935 D HeadsetStateMachine: max_hf_connections = 1
09-01 11:15:24.240  3935  3935 I bt_bluedroid: get_profile_interface handsfree
09-01 11:15:24.240  3935  4123 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-01 11:15:24.240  3935  4123 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-01 11:15:24.251  3935  4119 I BluetoothAdapterState: Entering PendingCommandState
,09-01 11:15:24.253  3935  3935 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b148f
,09-01 11:15:24.254  3935  3935 D A2dpService: Received start request. Starting profile...
09-01 11:15:24.254  3935  3935 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-01 11:15:24.255  3935  3935 I bt_bluedroid: get_profile_interface avrcp
,09-01 11:15:24.261  3935  3935 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-01 11:15:24.261  3935  3935 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-01 11:15:24.261  3935  3935 D A2dpStateMachine: make
,09-01 11:15:24.262  3935  3935 I bt_bluedroid: get_profile_interface a2dp
,09-01 11:15:24.263  3935  4123 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-01 11:15:24.264  3935  4138 D A2dpStateMachine: Enter Disconnected: -2
09-01 11:15:24.267  3935  3935 I BluetoothHidServiceJni: classInitNative: succeeds
09-01 11:15:24.268  3935  3935 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b148f
,09-01 11:15:24.269  3935  3935 D HidService: Received start request. Starting profile...
09-01 11:15:24.269  3855  3855 D BluetoothInputDevice: Proxy object connected
,09-01 11:15:24.269  3935  3935 I bt_bluedroid: get_profile_interface hidhost
09-01 11:15:24.269  3935  4123 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39983e5
09-01 11:15:24.269  3935  4123 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-01 11:15:24.269  3855  3855 D HidProfile: Bluetooth service connected
09-01 11:15:24.269  3935  3935 D HidService: setHidService(): set to: null
09-01 11:15:24.270  3935  3935 I BluetoothHealthServiceJni: classInitNative: succeeds
09-01 11:15:24.271  3935  3935 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b148f
,09-01 11:15:24.271  3935  3935 D HealthService: Received start request. Starting profile...
,09-01 11:15:24.273  3935  3935 I bt_bluedroid: get_profile_interface health
09-01 11:15:24.274  3935  3935 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-01 11:15:24.274  3935  3935 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b148f
,09-01 11:15:24.277  3935  3935 D PanService: Received start request. Starting profile...
,09-01 11:15:24.277  3855  3855 D BluetoothPan: BluetoothPAN Proxy object connected
09-01 11:15:24.277  3935  3935 D BluetoothPanServiceJni: initializeNative(L110): pan
09-01 11:15:24.277  3935  3935 I bt_bluedroid: get_profile_interface pan
09-01 11:15:24.277  3855  3855 D PanProfile: Bluetooth service connected
09-01 11:15:24.278  3935  4123 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-01 11:15:24.282  3935  3935 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b148f
,09-01 11:15:24.283  1514  1514 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 11:15:24.287  3855  3855 D BluetoothMap: Proxy object connected
,09-01 11:15:24.287  3935  3935 D BluetoothMapService: Received start request. Starting profile...
09-01 11:15:24.287  3935  3935 D BluetoothMapService: start()
09-01 11:15:24.287  3855  3855 D MapProfile: Bluetooth service connected
09-01 11:15:24.287  3855  3855 D BluetoothMap: getConnectedDevices()
09-01 11:15:24.288  3855  3855 D BluetoothMap: Bluetooth is Not enabled
09-01 11:15:24.289  3935  3935 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-01 11:15:24.290  3935  3935 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-01 11:15:24.290  3935  3935 D BluetoothMapAppObserver: createReceiver()
09-01 11:15:24.290  3935  3935 D BluetoothMapAppObserver: initObservers()
,09-01 11:15:24.291  3935  3935 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-01 11:15:24.296  3935  3935 V BluetoothAdapterState: isTurningOff()=false
,09-01 11:15:24.296  3935  3935 V BluetoothAdapterState: isTurningOn()=true
09-01 11:15:24.297  3935  3935 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:15:24.297  3935  4136 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-01 11:15:24.297  3935  3935 V BluetoothAdapterState: isBleTurningOff()=false
09-01 11:15:24.298  3935  3935 V BluetoothAdapterState: isTurningOff()=false
09-01 11:15:24.298  3935  3935 V BluetoothAdapterState: isTurningOn()=true
,09-01 11:15:24.298  3935  3935 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:15:24.298  3935  3935 V BluetoothAdapterState: isBleTurningOff()=false
09-01 11:15:24.298  3935  3935 V BluetoothAdapterState: isTurningOff()=false
09-01 11:15:24.298  3935  3935 V BluetoothAdapterState: isTurningOn()=true
09-01 11:15:24.298  3935  3935 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:15:24.299  3935  3935 V BluetoothAdapterState: isBleTurningOff()=false
09-01 11:15:24.299  3935  3935 V BluetoothAdapterState: isTurningOff()=false
09-01 11:15:24.299  3935  3935 V BluetoothAdapterState: isTurningOn()=true
09-01 11:15:24.299  3935  3935 V BluetoothAdapterState: isBleTurningOn()=false
,09-01 11:15:24.299  3935  3935 V BluetoothAdapterState: isBleTurningOff()=false
09-01 11:15:24.299  3935  3935 V BluetoothAdapterState: isTurningOff()=false
09-01 11:15:24.299  3935  3935 V BluetoothAdapterState: isTurningOn()=true
,09-01 11:15:24.299  3935  3935 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:15:24.299  3935  3935 V BluetoothAdapterState: isBleTurningOff()=false
09-01 11:15:24.301  3935  3935 V BluetoothAdapterState: isTurningOff()=false
09-01 11:15:24.301  3935  3935 V BluetoothAdapterState: isTurningOn()=true
09-01 11:15:24.301  3935  3935 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:15:24.301  3935  3935 V BluetoothAdapterState: isBleTurningOff()=false
09-01 11:15:24.302  3935  4119 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-01 11:15:24.302  3935  4119 D BluetoothAdapterProperties: ScanMode =  20
09-01 11:15:24.302  3935  4119 D BluetoothAdapterProperties: State =  11
09-01 11:15:24.304  3935  4123 D BluetoothAdapterProperties: Scan Mode:21
09-01 11:15:24.305  3935  4123 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-01 11:15:24.305  3935  4119 D BluetoothAdapterProperties: Setting state to 12
09-01 11:15:24.305  3935  4119 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-01 11:15:24.305  3855  3869 D BluetoothMap: onBluetoothStateChange: up=true
09-01 11:15:24.306   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-01 11:15:24.306  3935  4119 I BluetoothAdapterState: Entering OnState
09-01 11:15:24.306  1345  2008 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 11:15:24.307   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 11:15:24.307   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
09-01 11:15:24.307  1345  1364 D BluetoothPan: onBluetoothStateChange on: true
,09-01 11:15:24.308   875   875 D BluetoothA2dp: Proxy object connected
,09-01 11:15:24.309  1345  2051 D BluetoothPbap: onBluetoothStateChange: up=true
,09-01 11:15:24.309  1345  1345 D BluetoothPan: BluetoothPAN Proxy object connected
09-01 11:15:24.309  1345  1345 D PanProfile: Bluetooth service connected
09-01 11:15:24.310  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:15:24.310  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:24.310  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:24.310  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:15:24.310  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:15:24.310  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:15:24.310  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:15:24.310  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:15:24.310  3855  3866 D BluetoothPbap: onBluetoothStateChange: up=true
,09-01 11:15:24.312  1937  2235 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 11:15:24.312  1345  2008 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-01 11:15:24.312  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 11:15:24.314  1345  1345 D BluetoothInputDevice: Proxy object connected
09-01 11:15:24.314  1345  1345 D HidProfile: Bluetooth service connected
09-01 11:15:24.314   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 11:15:24.314  1345  1364 D BluetoothMap: onBluetoothStateChange: up=true
,09-01 11:15:24.316  3855  3869 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-01 11:15:24.316  1345  1345 D BluetoothMap: Proxy object connected
09-01 11:15:24.316  1345  1359 D BluetoothA2dp: onBluetoothStateChange: up=true
09-01 11:15:24.316  1345  1345 D MapProfile: Bluetooth service connected
,09-01 11:15:24.316  1345  1345 D BluetoothMap: getConnectedDevices()
09-01 11:15:24.317  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:15:24.317  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:24.317  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:24.317  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:15:24.317  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:15:24.317  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:15:24.317  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:15:24.317  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:15:24.318  3935  3935 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-01 11:15:24.318  3935  3935 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-01 11:15:24.319  3855  3866 D BluetoothPan: onBluetoothStateChange on: true
,09-01 11:15:24.320  3935  3935 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:15:24.320  1345  1345 D BluetoothA2dp: Proxy object connected
09-01 11:15:24.320  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 11:15:24.322   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
,09-01 11:15:24.324  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:24.326  3935  3935 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 11:15:24.327  3935  3935 D ObexServerSockets: Succeed to create listening sockets 
,09-01 11:15:24.327  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:15:24.327  3935  3935 D ObexServerSockets0: startAccept()
,09-01 11:15:24.327  3935  3935 D ObexServerSockets0: prepareForNewConnect()
,09-01 11:15:24.328  3855  3855 D LocalBluetoothProfileManager: Adding local A2DP profile
09-01 11:15:24.329  3935  3935 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-01 11:15:24.330  3935  3935 D BluetoothSdpJni: SDP Create record success - handle: 0
09-01 11:15:24.330  3935  3935 D BluetoothMapService: onReceive
,09-01 11:15:24.330  3935  3935 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:15:24.330  3935  3935 D BluetoothMapService: STATE_ON
09-01 11:15:24.331  3935  4146 D ObexServerSockets0: Accepting socket connection...
09-01 11:15:24.331  3935  4147 D ObexServerSockets0: Accepting socket connection...
,09-01 11:15:24.332  3855  3855 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-01 11:15:24.339  3855  3855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-01 11:15:24.341  3855  3855 D BluetoothA2dp: Proxy object connected
,09-01 11:15:24.345  1514  1514 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 11:15:24.350  3855  3855 D DockEventReceiver: finishStartingService: stopping service
,09-01 11:15:24.355  3855  3855 D BluetoothPbap: Proxy object connected
,09-01 11:15:24.355  1345  1345 D BluetoothPbap: Proxy object connected
09-01 11:15:24.356  1345  1345 D PbapServerProfile: Bluetooth service connected
09-01 11:15:24.356  3855  3855 D PbapServerProfile: Bluetooth service connected
,09-01 11:15:24.361  3935  3935 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-01 11:15:24.361  3935  3935 D ObexServerSockets0: prepareForNewConnect()
,09-01 11:15:24.364  3935  4151 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 11:15:24.378  3935  4155 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 11:15:24.380  3935  4155 I BtOppRfcommListener: Accept thread started.
,09-01 11:15:24.408  1937  1951 D BluetoothHeadset: Proxy object connected
,09-01 11:15:24.408  1345  2008 D BluetoothHeadset: Proxy object connected
09-01 11:15:24.408  1345  1345 D HeadsetProfile: Bluetooth service connected,
09-01 11:15:24.409   875   875 D BluetoothHeadset: Proxy object connected
,09-01 11:15:24.409   875   875 D BluetoothHeadset: Proxy object connected
,09-01 11:15:24.409   875   875 D BluetoothHeadset: Proxy object connected
09-01 11:15:24.412  1937  1948 D BluetoothHeadset: Proxy object connected
,09-01 11:15:24.414   875   892 D BluetoothHeadset: Proxy object connected,
,09-01 11:15:24.436  3855  3869 D BluetoothHeadset: Proxy object connected
,09-01 11:15:24.438  3855  3855 D HeadsetProfile: Bluetooth service connected
,09-01 11:15:25.870  3935  4119 D BluetoothAdapterState: Current state: ON, message: 23
09-01 11:15:25.871  3935  4119 D BluetoothAdapterProperties: Setting state to 13
09-01 11:15:25.871  3935  4119 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-01 11:15:25.873  3935  4119 D BluetoothAdapterProperties: onBluetoothDisable()
,09-01 11:15:25.875  3935  4119 I BluetoothAdapterState: Entering PendingCommandState
,09-01 11:15:25.880  3935  4123 D BluetoothAdapterProperties: Scan Mode:20
09-01 11:15:25.881  3935  4119 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-01 11:15:25.886  3935  3935 D BluetoothMapService: onReceive
,09-01 11:15:25.886  3935  3935 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:15:25.887  3935  3935 D BluetoothMapService: STATE_TURNING_OFF
09-01 11:15:25.887  3935  3935 D BluetoothMapService: MAP Service closeService in
09-01 11:15:25.888  3935  3935 D BluetoothMapMasInstance0: MAP Service shutdown
09-01 11:15:25.888  3935  3935 D ObexServerSockets0: shutdown(block = true)
09-01 11:15:25.889  3935  4146 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-01 11:15:25.890  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 11:15:25.890  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:15:25.890  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:25.890  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:25.890  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:15:25.890  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:15:25.890  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:15:25.890  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:15:25.890  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:15:25.891  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:15:25.891  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:15:25.892  3935  3935 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-01 11:15:25.892  3935  4147 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-01 11:15:25.893  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 11:15:25.894  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:15:25.894  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:25.894  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:25.894  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:15:25.894  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:15:25.894  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:15:25.894  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:15:25.894  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:15:25.894  3935  4131 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-01 11:15:25.894  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:15:25.894  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:15:25.898  3935  3935 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-01 11:15:25.899  3935  3935 I BtOppRfcommListener: stopping Accept Thread
,09-01 11:15:25.899  3935  4155 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-01 11:15:25.899  3855  3855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-01 11:15:25.900  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:15:25.900  3935  4155 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-01 11:15:25.902  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:15:25.903   875  1308 D ConnectivityService: handlePromptUnvalidated 101
09-01 11:15:25.905  3935  3935 D HeadsetService: Received stop request...Stopping profile...
,09-01 11:15:25.908  3935  3935 D A2dpService: Received stop request...Stopping profile...
09-01 11:15:25.908  1937  2080 D BluetoothHeadset: Proxy object disconnected
09-01 11:15:25.909  1345  2008 D BluetoothHeadset: Proxy object disconnected
09-01 11:15:25.909  3935  4138 D A2dpStateMachine: Exit Disconnected: -1
,09-01 11:15:25.909   875   875 D BluetoothHeadset: Proxy object disconnected
09-01 11:15:25.909   875   875 D BluetoothHeadset: Proxy object disconnected
09-01 11:15:25.910   875   875 D BluetoothHeadset: Proxy object disconnected
09-01 11:15:25.910  3855  3869 D BluetoothHeadset: Proxy object disconnected
,09-01 11:15:25.912   875   875 D BluetoothA2dp: Proxy object disconnected
,09-01 11:15:25.912  3935  3935 D HidService: Received stop request...Stopping profile...
09-01 11:15:25.913  3935  3935 D HidService: Stopping Bluetooth HidService
,09-01 11:15:25.914  3935  3935 D HealthService: Received stop request...Stopping profile...
,09-01 11:15:25.917  3855  3855 D DockEventReceiver: finishStartingService: stopping service
,09-01 11:15:25.917  3935  3935 D PanService: Received stop request...Stopping profile...
09-01 11:15:25.918  3855  3855 D HeadsetProfile: Bluetooth service disconnected
09-01 11:15:25.918  3855  3855 D BluetoothA2dp: Proxy object disconnected
,09-01 11:15:25.918  3855  3855 D BluetoothInputDevice: Proxy object disconnected
09-01 11:15:25.919  3855  3855 D HidProfile: Bluetooth service disconnected
09-01 11:15:25.919  1345  1345 D HeadsetProfile: Bluetooth service disconnected
,09-01 11:15:25.919  1345  1345 D BluetoothA2dp: Proxy object disconnected
09-01 11:15:25.920  1345  1345 D BluetoothInputDevice: Proxy object disconnected
,09-01 11:15:25.920  1345  1345 D HidProfile: Bluetooth service disconnected
,09-01 11:15:25.920  1345  1345 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-01 11:15:25.920  1345  1345 D PanProfile: Bluetooth service disconnected
,09-01 11:15:25.919  3855  3855 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-01 11:15:25.920  3855  3855 D PanProfile: Bluetooth service disconnected
,09-01 11:15:25.921  1514  1514 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 11:15:25.923  3935  3935 D BluetoothMapService: Received stop request...Stopping profile...
,09-01 11:15:25.923  3935  3935 D BluetoothMapService: stop()
09-01 11:15:25.924  3935  3935 D BluetoothMapAppObserver: deinitObservers()
09-01 11:15:25.924  3935  3935 D BluetoothMapAppObserver: removeReceiver()
,09-01 11:15:25.925  3935  3935 V BluetoothAdapterState: isTurningOff()=true
,09-01 11:15:25.925  3935  3935 V BluetoothAdapterState: isTurningOn()=false
09-01 11:15:25.925  3935  3935 V BluetoothAdapterState: isBleTurningOn()=false
,09-01 11:15:25.926  3935  3935 V BluetoothAdapterState: isBleTurningOff()=false
09-01 11:15:25.926  1345  1345 D BluetoothMap: Proxy object disconnected
09-01 11:15:25.926  1345  1345 D MapProfile: Bluetooth service disconnected
,09-01 11:15:25.926  3855  3855 D BluetoothMap: Proxy object disconnected
,09-01 11:15:25.926  3855  3855 D MapProfile: Bluetooth service disconnected
,09-01 11:15:25.927  3935  3935 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-01 11:15:25.927  3935  4123 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-01 11:15:25.927  3935  4129 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-01 11:15:25.927  3935  4129 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-01 11:15:25.927  3935  4129 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 11:15:25.929  3935  4123 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-01 11:15:25.929  3935  3935 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-01 11:15:25.930  3935  3935 V BluetoothAdapterState: isTurningOff()=true
09-01 11:15:25.930  3935  3935 V BluetoothAdapterState: isTurningOn()=false
09-01 11:15:25.930  3935  3935 V BluetoothAdapterState: isBleTurningOn()=false
,09-01 11:15:25.930  3935  3935 V BluetoothAdapterState: isBleTurningOff()=false
09-01 11:15:25.931  3935  4123 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-01 11:15:25.931  3935  4129 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 11:15:25.931  3935  4129 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 11:15:25.931  3935  4129 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 11:15:25.931  3935  4129 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-01 11:15:25.931  3935  4129 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-01 11:15:25.931  3935  4129 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 11:15:25.934  3935  3935 V BluetoothAdapterState: isTurningOff()=true
09-01 11:15:25.934  3935  3935 V BluetoothAdapterState: isTurningOn()=false
09-01 11:15:25.934  3935  3935 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:15:25.934  3935  3935 V BluetoothAdapterState: isBleTurningOff()=false
09-01 11:15:25.935  3935  3935 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-01 11:15:25.935  3935  4123 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-01 11:15:25.935  3935  3935 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-01 11:15:25.935  3935  3935 V BluetoothAdapterState: isTurningOff()=true
09-01 11:15:25.935  3935  3935 V BluetoothAdapterState: isTurningOn()=false
09-01 11:15:25.935  3935  3935 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:15:25.935  3935  3935 V BluetoothAdapterState: isBleTurningOff()=false
09-01 11:15:25.935  3935  3935 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-01 11:15:25.936  3935  4123 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-01 11:15:25.936  3935  3935 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-01 11:15:25.936  3935  3935 V BluetoothAdapterState: isTurningOff()=true
09-01 11:15:25.937  3935  3935 V BluetoothAdapterState: isTurningOn()=false
09-01 11:15:25.937  3935  3935 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:15:25.937  3935  3935 V BluetoothAdapterState: isBleTurningOff()=false
09-01 11:15:25.937  3935  3935 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-01 11:15:25.937  3935  3935 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-01 11:15:25.939  1345  1345 D BluetoothPbap: Proxy object disconnected
,09-01 11:15:25.939  1345  1345 D PbapServerProfile: Bluetooth service disconnected
09-01 11:15:25.943  3935  3935 D BluetoothMapService: MAP Service closeService in
09-01 11:15:25.943  3935  3935 V BluetoothAdapterState: isTurningOff()=true
09-01 11:15:25.943  3935  3935 V BluetoothAdapterState: isTurningOn()=false
09-01 11:15:25.943  3935  3935 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:15:25.943  3935  3935 V BluetoothAdapterState: isBleTurningOff()=false
,09-01 11:15:25.943  3935  4119 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-01 11:15:25.943  3935  4119 D BluetoothAdapterProperties: Setting state to 15
09-01 11:15:25.943  3935  4119 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-01 11:15:25.944  3935  3935 D BluetoothMapService: cleanup()
09-01 11:15:25.944  3935  3935 D BluetoothMapService: MAP Service closeService in
09-01 11:15:25.945  3935  4119 I BluetoothAdapterState: Entering BleOnState
,09-01 11:15:25.946  3855  3869 D BluetoothMap: onBluetoothStateChange: up=false
,09-01 11:15:25.947   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:15:25.947  1345  2051 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:15:25.947   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:15:25.947   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
09-01 11:15:25.948  1345  1364 D BluetoothPan: onBluetoothStateChange on: false
09-01 11:15:25.948  1345  1359 D BluetoothPbap: onBluetoothStateChange: up=false
09-01 11:15:25.948  3855  3855 D BluetoothPbap: Proxy object disconnected
,09-01 11:15:25.948  3855  3855 D PbapServerProfile: Bluetooth service disconnected
09-01 11:15:25.949  3855  3869 D BluetoothPbap: onBluetoothStateChange: up=false
09-01 11:15:25.949  1937  2235 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:15:25.949  1345  2008 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-01 11:15:25.950   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:15:25.950  1345  2051 D BluetoothMap: onBluetoothStateChange: up=false
09-01 11:15:25.951  3855  3866 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-01 11:15:25.952  3855  3869 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-01 11:15:25.953  1345  1364 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-01 11:15:25.953  3855  3866 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:15:25.954  3855  3869 D BluetoothPan: onBluetoothStateChange on: false
,09-01 11:15:25.954  3935  4119 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-01 11:15:25.955  3935  4119 D BluetoothAdapterProperties: Setting state to 16
09-01 11:15:25.955  3935  4119 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-01 11:15:25.955  3935  4119 D BluetoothAdapterProperties: onBleDisable
,09-01 11:15:25.955  3935  4119 I BluetoothAdapterState: Entering PendingCommandState
09-01 11:15:25.955  3935  4120 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-01 11:15:25.956  3935  4129 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-01 11:15:25.956  3935  4129 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 11:15:25.958  3935  4123 D BluetoothAdapterProperties: Scan Mode:20
09-01 11:15:25.960  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:25.960  3855  3855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-01 11:15:25.961  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:25.962  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:15:25.963  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:25.965  1514  1514 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 11:15:25.965  3855  3855 D DockEventReceiver: finishStartingService: stopping service
,09-01 11:15:26.157  3935  4123 I bt_hci  : shut_down
,09-01 11:15:26.166  3935  4127 I bt_vendor: low_power_mode_cb
,09-01 11:15:26.167  3935  4127 D bt_hwcfg: hw_epilog_process
,09-01 11:15:26.189  3935  4127 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-01 11:15:26.190  3935  4127 I bt_vendor: epilog_cb
09-01 11:15:26.190  3935  4127 I bt_hci  : epilog_finished_callback
,09-01 11:15:26.198  3935  4123 I bt_hci_h4: hal_close
,09-01 11:15:26.199  3935  4123 I bt_userial_vendor: device fd = 51 close
,09-01 11:15:26.322  3935  4120 D bt_stack_manager: event_shut_down_stack finished.
,09-01 11:15:26.325  3935  4119 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-01 11:15:26.332  3935  4119 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-01 11:15:26.332  3935  3935 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-01 11:15:26.334  3935  3935 D BtGatt.GattService: Received stop request...Stopping profile...
09-01 11:15:26.334  3935  3935 D BtGatt.GattService: stop()
,09-01 11:15:26.334  3935  3935 D BtGatt.AdvertiseManager: advertise clients cleared
,09-01 11:15:26.340  3935  3935 V BluetoothAdapterState: isTurningOff()=false
,09-01 11:15:26.340  3935  3935 V BluetoothAdapterState: isTurningOn()=false
,09-01 11:15:26.340  3935  3935 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:15:26.341  3935  3935 V BluetoothAdapterState: isBleTurningOff()=true
,09-01 11:15:26.342  3935  4119 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-01 11:15:26.343  3935  4119 D BluetoothAdapterProperties: Setting state to 10
,09-01 11:15:26.343  3935  4119 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-01 11:15:26.345  3935  4119 I BluetoothAdapterState: Entering OffState
,09-01 11:15:26.346   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-01 11:15:26.370  3935  3935 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-01 11:15:26.371  3935  3935 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-01 11:15:26.371  3935  3935 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-01 11:15:26.373  3935  4120 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-01 11:15:26.383  3935  4120 D bt_stack_manager: event_clean_up_stack finished.
,09-01 11:15:26.387  3935  3935 I art     : System.exit called, status: 0
,09-01 11:15:26.387  3935  3935 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-01 11:15:26.450   875  1954 I ActivityManager: Process com.android.bluetooth (pid 3935) has died
,09-01 11:15:28.869  3784  3836 D io.jxcore.node.ConnectivityMonitor: stop
,09-01 11:15:28.870  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:15:31.877  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-01 11:15:31.878  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b800f9d added. We now have 6 listener(s)
09-01 11:15:31.878  3784  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 11:15:31.882  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:15:31.883  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ab6ac12 added. We now have 7 listener(s)
,09-01 11:15:31.883  3784  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:15:31.884  3784  3836 I System.out: IsBluetoothEnabled
,09-01 11:15:31.894  3784  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:31.920   875   892 I ActivityManager: Start proc 4169:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-01 11:15:32.092  4169  4169 D AdapterServiceConfig: Adding HeadsetService
,09-01 11:15:32.092  4169  4169 D AdapterServiceConfig: Adding A2dpService
,09-01 11:15:32.092  4169  4169 D AdapterServiceConfig: Adding HidService
,09-01 11:15:32.093  4169  4169 D AdapterServiceConfig: Adding HealthService
,09-01 11:15:32.093  4169  4169 D AdapterServiceConfig: Adding PanService
,09-01 11:15:32.094  4169  4169 D AdapterServiceConfig: Adding GattService
,09-01 11:15:32.094  4169  4169 D AdapterServiceConfig: Adding BluetoothMapService
,09-01 11:15:32.111   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3c7d2c0:true
,09-01 11:15:32.111  4169  4169 D BluetoothAdapterState: make() - Creating AdapterState
,09-01 11:15:32.117  4169  4169 I bt_bluedroid: init
,09-01 11:15:32.118  4169  4181 I BluetoothAdapterState: Entering OffState
,09-01 11:15:32.123  4169  4182 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-01 11:15:32.123  4169  4182 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-01 11:15:32.124  4169  4182 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-01 11:15:32.124  4169  4182 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-01 11:15:32.126  4169  4169 I bt_bluedroid: get_profile_interface socket
,09-01 11:15:32.128  4169  4169 I bt_bluedroid: get_profile_interface sdp
,09-01 11:15:32.132  4169  4185 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-01 11:15:32.133  4169  4185 D BluetoothAdapterProperties: Name is: Nexus 6
,09-01 11:15:32.133  4169  4180 I bt_bluedroid: config_hci_snoop_log
09-01 11:15:32.136   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-01 11:15:32.146  4169  4181 D BluetoothAdapterState: Current state: OFF, message: 0
,09-01 11:15:32.147  4169  4181 D BluetoothAdapterProperties: Setting state to 14
,09-01 11:15:32.147  4169  4181 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-01 11:15:32.151  4169  4181 D BluetoothBondStateMachine: make
,09-01 11:15:32.157  4169  4186 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-01 11:15:32.165  4169  4181 I BluetoothAdapterState: Entering PendingCommandState
,09-01 11:15:32.167  4169  4169 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-01 11:15:32.177  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b148f
,09-01 11:15:32.180  4169  4169 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-01 11:15:32.182  4169  4169 D BtGatt.GattService: Received start request. Starting profile...
,09-01 11:15:32.182  4169  4169 D BtGatt.GattService: start()
,09-01 11:15:32.183  4169  4169 I bt_bluedroid: get_profile_interface gatt
,09-01 11:15:32.185  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b148f
,09-01 11:15:32.186  4169  4169 D BtGatt.AdvertiseManager: advertise manager created
09-01 11:15:32.204  4169  4169 V BluetoothAdapterState: isTurningOff()=false
,09-01 11:15:32.204  4169  4169 V BluetoothAdapterState: isTurningOn()=false
09-01 11:15:32.204  4169  4169 V BluetoothAdapterState: isBleTurningOn()=true
09-01 11:15:32.205  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
,09-01 11:15:32.207  4169  4181 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-01 11:15:32.208  4169  4181 I bt_bluedroid: enable
,09-01 11:15:32.208  4169  4182 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-01 11:15:32.209  4169  4182 I bt_hci  : start_up
,09-01 11:15:32.233  4169  4182 I bt_vendor: alloc value 0xb3a8a189
,09-01 11:15:32.234  4169  4182 I bt_vendor: init
09-01 11:15:32.234  4169  4182 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-01 11:15:32.234  4169  4182 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-01 11:15:32.340  4169  4182 D bt_hci  : start_up starting async portion
,09-01 11:15:32.341  4169  4189 I bt_hci  : event_finish_startup
09-01 11:15:32.341  4169  4189 I bt_hci_h4: hal_open
,09-01 11:15:32.341  4169  4189 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-01 11:15:32.350  4169  4189 I bt_userial_vendor: device fd = 51 open
,09-01 11:15:32.383  4169  4189 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-01 11:15:32.400   875   895 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-01 11:15:32.411  1871  1871 I Keyboard.Facilitator: onFinishInput()
,09-01 11:15:32.418   875   895 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-01 11:15:32.418   875   895 I Adreno  : Build Date                       : 10/20/15
09-01 11:15:32.418   875   895 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-01 11:15:32.418   875   895 I Adreno  : Local Branch                     : M14
09-01 11:15:32.418   875   895 I Adreno  : Remote Branch                    : 
09-01 11:15:32.418   875   895 I Adreno  : Remote Branch                    : 
09-01 11:15:32.418   875   895 I Adreno  : Reconstruct Branch               : 
,09-01 11:15:32.420  4169  4189 D bt_hwcfg: Chipset BCM4354A2
09-01 11:15:32.420  4169  4189 D bt_hwcfg: Target name = [BCM4354A2]
09-01 11:15:32.421  4169  4189 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-01 11:15:32.459   282  1301 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (209 us),
,09-01 11:15:33.036  4169  4189 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-01 11:15:33.037  4169  4189 D bt_hwcfg: Settlement delay -- 100 ms
,09-01 11:15:33.038  4169  4189 I bt_hwcfg: Setting fw settlement delay to 100 
,09-01 11:15:33.139  3784  3784 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-01 11:15:33.139  3784  3784 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-01 11:15:33.153  4169  4189 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-01 11:15:33.153  4169  4189 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-01 11:15:33.184  4169  4189 I bt_hwcfg: vendor lib fwcfg completed
,09-01 11:15:33.185  4169  4189 I bt_vendor: firmware callback
09-01 11:15:33.185  4169  4189 I bt_hci  : firmware_config_callback
,09-01 11:15:33.193   875   895 V KeyguardServiceDelegate: onScreenTurnedOff()
09-01 11:15:33.194  4169  4193 I bt_btu  : btu_task pending for preload complete event
09-01 11:15:33.194  4169  4193 I bt_btu_task: Bluetooth chip preload is complete
09-01 11:15:33.194  4169  4193 I bt_btu  : btu_task received preload complete event
09-01 11:15:33.197  4169  4193 I         : BTE_InitTraceLevels -- TRC_HCI
09-01 11:15:33.197  4169  4193 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-01 11:15:33.197  4169  4193 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-01 11:15:33.197  4169  4193 I         : BTE_InitTraceLevels -- TRC_AVDT
09-01 11:15:33.197  4169  4193 I         : BTE_InitTraceLevels -- TRC_AVRC
09-01 11:15:33.197  4169  4193 I         : BTE_InitTraceLevels -- TRC_A2D
09-01 11:15:33.197  4169  4193 I         : BTE_InitTraceLevels -- TRC_BNEP
09-01 11:15:33.197  4169  4193 I         : BTE_InitTraceLevels -- TRC_BTM
09-01 11:15:33.197  4169  4193 I         : BTE_InitTraceLevels -- TRC_GAP
09-01 11:15:33.197  4169  4193 I         : BTE_InitTraceLevels -- TRC_PAN
09-01 11:15:33.197  4169  4193 I         : BTE_InitTraceLevels -- TRC_SDP
09-01 11:15:33.197  4169  4193 I         : BTE_InitTraceLevels -- TRC_GATT
09-01 11:15:33.197  4169  4193 I         : BTE_InitTraceLevels -- TRC_SMP
09-01 11:15:33.197  4169  4193 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-01 11:15:33.197  4169  4193 I         : BTE_InitTraceLevels -- TRC_BTIF
09-01 11:15:33.198  3784  3784 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@6de6aab Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@20efe3, 16908290=android.view.AbsSavedState$1@20efe3}, android:focusedViewId=100}]}]
09-01 11:15:33.198  3784  3784 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-01 11:15:33.199  3784  3784 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-01 11:15:33.199  3784  3784 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-01 11:15:33.214   875   895 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-01 11:15:33.216   875   893 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-01 11:15:33.218   282   282 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
09-01 11:15:33.218   282   282 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-01 11:15:33.332  4169  4193 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3a07d9d
,09-01 11:15:33.333  4169  4193 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3a07d9d 
,09-01 11:15:33.342  4169  4185 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-01 11:15:33.343  4169  4185 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-01 11:15:33.345  4169  4185 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-01 11:15:33.350  4169  4185 D BluetoothAdapterProperties: Name is: Nexus 6
,09-01 11:15:33.353  4169  4185 D BluetoothAdapterProperties: Scan Mode:20
,09-01 11:15:33.354  4169  4185 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-01 11:15:33.354  4169  4185 D bt_hci  : do_postload posting postload work item
,09-01 11:15:33.355  4169  4189 I bt_hci  : event_postload
,09-01 11:15:33.355  4169  4189 I bt_vendor: sco_config_cb
,09-01 11:15:33.355  4169  4189 I bt_hci  : sco_config_callback postload finished.
,09-01 11:15:33.359  4169  4185 D bt_bte_conf: Device ID record 1 : primary
,09-01 11:15:33.359  4169  4185 D bt_bte_conf:   vendorId            = 000f
,09-01 11:15:33.359  4169  4185 D bt_bte_conf:   vendorIdSource      = 0001
,09-01 11:15:33.360  4169  4185 D bt_bte_conf:   product             = 1200
09-01 11:15:33.360  4169  4185 D bt_bte_conf:   version             = 1436
09-01 11:15:33.360  4169  4185 D bt_bte_conf:   clientExecutableURL = 
09-01 11:15:33.360  4169  4185 D bt_bte_conf:   serviceDescription  = 
09-01 11:15:33.360  4169  4189 I bt_vendor: low_power_mode_cb
09-01 11:15:33.360  4169  4185 D bt_bte_conf:   documentationURL    = 
09-01 11:15:33.360  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:15:33.361  4169  4185 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-01 11:15:33.361  4169  4182 D bt_stack_manager: event_start_up_stack finished
09-01 11:15:33.362  4169  4181 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-01 11:15:33.363  4169  4181 D BluetoothAdapterProperties: Setting state to 15
09-01 11:15:33.363  4169  4181 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-01 11:15:33.366  4169  4181 I BluetoothAdapterState: Entering BleOnState
09-01 11:15:33.369  4169  4181 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-01 11:15:33.369  4169  4181 D BluetoothAdapterProperties: Setting state to 11
09-01 11:15:33.370  4169  4181 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-01 11:15:33.383  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:15:33.384  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b148f
09-01 11:15:33.386  4169  4169 D HeadsetService: Received start request. Starting profile...
09-01 11:15:33.389  4169  4169 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-01 11:15:33.389  4169  4169 D HeadsetStateMachine: make
,09-01 11:15:33.395  4169  4181 I BluetoothAdapterState: Entering PendingCommandState,
,09-01 11:15:33.398  4169  4169 D HeadsetStateMachine: max_hf_connections = 1
,09-01 11:15:33.398  4169  4169 I bt_bluedroid: get_profile_interface handsfree
,09-01 11:15:33.399  4169  4185 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-01 11:15:33.399  4169  4185 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-01 11:15:33.403  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b148f
,09-01 11:15:33.405  4169  4169 D A2dpService: Received start request. Starting profile...
,09-01 11:15:33.405  4169  4169 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-01 11:15:33.406  4169  4169 I bt_bluedroid: get_profile_interface avrcp
,09-01 11:15:33.413  4169  4169 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-01 11:15:33.413  4169  4169 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-01 11:15:33.413  4169  4169 D A2dpStateMachine: make
,09-01 11:15:33.415  4169  4169 I bt_bluedroid: get_profile_interface a2dp
,09-01 11:15:33.416  4169  4185 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-01 11:15:33.417  4169  4205 D A2dpStateMachine: Enter Disconnected: -2
09-01 11:15:33.418  4169  4169 I BluetoothHidServiceJni: classInitNative: succeeds
,09-01 11:15:33.419  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b148f
09-01 11:15:33.420  4169  4169 D HidService: Received start request. Starting profile...
,09-01 11:15:33.420  4169  4169 I bt_bluedroid: get_profile_interface hidhost
09-01 11:15:33.420  4169  4169 D HidService: setHidService(): set to: null
09-01 11:15:33.420  4169  4185 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39e93e5
,09-01 11:15:33.421  4169  4185 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-01 11:15:33.421  4169  4169 I BluetoothHealthServiceJni: classInitNative: succeeds
09-01 11:15:33.422  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b148f
,09-01 11:15:33.423  4169  4169 D HealthService: Received start request. Starting profile...
,09-01 11:15:33.424  4169  4169 I bt_bluedroid: get_profile_interface health
,09-01 11:15:33.425  4169  4169 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-01 11:15:33.426  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b148f
,09-01 11:15:33.429  4169  4169 D PanService: Received start request. Starting profile...
,09-01 11:15:33.429  4169  4169 D BluetoothPanServiceJni: initializeNative(L110): pan
09-01 11:15:33.429  4169  4169 I bt_bluedroid: get_profile_interface pan
,09-01 11:15:33.430  4169  4185 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-01 11:15:33.437  1514  1514 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 11:15:33.440  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b148f
,09-01 11:15:33.441  4169  4169 D BluetoothMapService: Received start request. Starting profile...
,09-01 11:15:33.441  4169  4169 D BluetoothMapService: start()
,09-01 11:15:33.444  4169  4169 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-01 11:15:33.444  4169  4169 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-01 11:15:33.444  4169  4169 D BluetoothMapAppObserver: createReceiver()
,09-01 11:15:33.445  4169  4169 D BluetoothMapAppObserver: initObservers()
09-01 11:15:33.445  4169  4169 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-01 11:15:33.454  4169  4169 V BluetoothAdapterState: isTurningOff()=false
,09-01 11:15:33.454  4169  4203 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-01 11:15:33.454  4169  4169 V BluetoothAdapterState: isTurningOn()=true
09-01 11:15:33.454  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:15:33.455   282   344 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
09-01 11:15:33.455  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
09-01 11:15:33.456   282   282 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
09-01 11:15:33.457   875  1333 D SurfaceControl: Excessive delay in setPowerMode(): 240ms
,09-01 11:15:33.458   875   895 I DreamManagerService: Entering dreamland.
,09-01 11:15:33.459   875   895 I PowerManagerService: Dozing...
,09-01 11:15:33.460  4169  4169 V BluetoothAdapterState: isTurningOff()=false
,09-01 11:15:33.460  4169  4169 V BluetoothAdapterState: isTurningOn()=true
09-01 11:15:33.460  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:15:33.460  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
,09-01 11:15:33.460  4169  4169 V BluetoothAdapterState: isTurningOff()=false
,09-01 11:15:33.460   875   890 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-01 11:15:33.460  4169  4169 V BluetoothAdapterState: isTurningOn()=true
09-01 11:15:33.460  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:15:33.460  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
,09-01 11:15:33.461  4169  4169 V BluetoothAdapterState: isTurningOff()=false
09-01 11:15:33.463  4169  4169 V BluetoothAdapterState: isTurningOn()=true
09-01 11:15:33.463  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
,09-01 11:15:33.464  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
09-01 11:15:33.464  4169  4169 V BluetoothAdapterState: isTurningOff()=false
09-01 11:15:33.464  4169  4169 V BluetoothAdapterState: isTurningOn()=true
09-01 11:15:33.464  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
,09-01 11:15:33.464  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
09-01 11:15:33.465  4169  4169 V BluetoothAdapterState: isTurningOff()=false,
09-01 11:15:33.465  4169  4169 V BluetoothAdapterState: isTurningOn()=true,
09-01 11:15:33.466  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
09-01 11:15:33.466  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
09-01 11:15:33.467  4169  4181 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-01 11:15:33.468  4169  4181 D BluetoothAdapterProperties: ScanMode =  20
09-01 11:15:33.468  4169  4181 D BluetoothAdapterProperties: State =  11
,09-01 11:15:33.468  4169  4181 D BluetoothAdapterProperties: Setting state to 12
,09-01 11:15:33.468  4169  4181 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-01 11:15:33.470  4169  4181 I BluetoothAdapterState: Entering OnState
09-01 11:15:33.470  3855  3866 D BluetoothMap: onBluetoothStateChange: up=true
,09-01 11:15:33.471  4169  4185 D BluetoothAdapterProperties: Scan Mode:21
09-01 11:15:33.471  4169  4185 D BluetoothAdapterProperties: Discoverable Timeout:120,
09-01 11:15:33.471  4169  4169 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-01 11:15:33.472  4169  4169 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-01 11:15:33.472   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-01 11:15:33.473  1345  2051 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 11:15:33.473  4169  4169 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:15:33.473   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-01 11:15:33.473   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-01 11:15:33.474  1345  1359 D BluetoothPan: onBluetoothStateChange on: true
09-01 11:15:33.475  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:15:33.475  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:33.475  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:33.475  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:15:33.475  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:15:33.475  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:15:33.475  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:15:33.475  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:15:33.475  4169  4169 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:15:33.476  1345  4195 D BluetoothPbap: onBluetoothStateChange: up=true
,09-01 11:15:33.477  4169  4169 D ObexServerSockets: Succeed to create listening sockets 
09-01 11:15:33.477  4169  4169 D ObexServerSockets0: startAccept()
09-01 11:15:33.477  4169  4169 D ObexServerSockets0: prepareForNewConnect()
09-01 11:15:33.477  3855  4159 D BluetoothPbap: onBluetoothStateChange: up=true
09-01 11:15:33.478  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 11:15:33.478  1937  1948 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 11:15:33.479  4169  4169 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-01 11:15:33.479  4169  4169 D BluetoothSdpJni: SDP Create record success - handle: 0
09-01 11:15:33.479  1345  2008 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-01 11:15:33.480  4169  4211 D ObexServerSockets0: Accepting socket connection...
,09-01 11:15:33.481   875   875 D BluetoothA2dp: Proxy object connected
,09-01 11:15:33.481   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-01 11:15:33.481  3855  3855 D BluetoothMap: Proxy object connected
,09-01 11:15:33.481  3855  3855 D MapProfile: Bluetooth service connected
09-01 11:15:33.481  3855  3855 D BluetoothMap: getConnectedDevices()
,09-01 11:15:33.482  4169  4210 D ObexServerSockets0: Accepting socket connection...
,09-01 11:15:33.483  1345  2051 D BluetoothMap: onBluetoothStateChange: up=true
,09-01 11:15:33.485  3855  3866 D BluetoothA2dp: onBluetoothStateChange: up=true
09-01 11:15:33.486  1345  1345 D BluetoothPan: BluetoothPAN Proxy object connected
09-01 11:15:33.486  1345  1345 D PanProfile: Bluetooth service connected
,09-01 11:15:33.486  1345  1345 D BluetoothInputDevice: Proxy object connected
09-01 11:15:33.486  1345  1345 D HidProfile: Bluetooth service connected
09-01 11:15:33.487  1345  1345 D BluetoothMap: Proxy object connected
09-01 11:15:33.487  1345  1345 D MapProfile: Bluetooth service connected,
09-01 11:15:33.487  1345  1345 D BluetoothMap: getConnectedDevices()
,09-01 11:15:33.488  3855  3869 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-01 11:15:33.490  1345  4196 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-01 11:15:33.492  3855  3866 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 11:15:33.492  3855  4159 D BluetoothPan: onBluetoothStateChange on: true
09-01 11:15:33.495  3855  3855 D BluetoothA2dp: Proxy object connected
09-01 11:15:33.495  4169  4169 D BluetoothMapService: onReceive
,09-01 11:15:33.495  4169  4169 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-01 11:15:33.495  4169  4169 D BluetoothMapService: STATE_ON
09-01 11:15:33.496   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
09-01 11:15:33.497  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:15:33.497  3855  3855 D BluetoothInputDevice: Proxy object connected
,09-01 11:15:33.497  3855  3855 D HidProfile: Bluetooth service connected
,09-01 11:15:33.498  1345  1345 D BluetoothA2dp: Proxy object connected
09-01 11:15:33.498  3855  3855 D BluetoothPan: BluetoothPAN Proxy object connected
09-01 11:15:33.498  3855  3855 D PanProfile: Bluetooth service connected
,09-01 11:15:33.504   378  1314 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-01 11:15:33.504   378  1314 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
09-01 11:15:33.504  3855  3855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-01 11:15:33.510  1514  1514 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 11:15:33.513   875  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-01 11:15:33.513  3855  3855 D DockEventReceiver: finishStartingService: stopping service
,09-01 11:15:33.517   875  1306 E native  : do suspend false
,09-01 11:15:33.519  3855  3855 D BluetoothPbap: Proxy object connected
,09-01 11:15:33.519  3855  3855 D PbapServerProfile: Bluetooth service connected
,09-01 11:15:33.523  1345  1345 D BluetoothPbap: Proxy object connected
,09-01 11:15:33.523  1345  1345 D PbapServerProfile: Bluetooth service connected
,09-01 11:15:33.525  4169  4169 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-01 11:15:33.525  4169  4169 D ObexServerSockets0: prepareForNewConnect()
,09-01 11:15:33.527  4169  4217 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:15:33.536  1924  4218 D NfcService: Discovery configuration equal, not updating.
,09-01 11:15:33.545  4169  4223 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 11:15:33.546  4169  4223 I BtOppRfcommListener: Accept thread started.
,09-01 11:15:33.555   875  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-01 11:15:33.557   875  1306 E native  : do suspend true
,09-01 11:15:33.642   378   378 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-01 11:15:33.642   378   378 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-01 11:15:33.644  1937  2235 D BluetoothHeadset: Proxy object connected
,09-01 11:15:33.646  1345  2051 D BluetoothHeadset: Proxy object connected
,09-01 11:15:33.646  1345  1345 D HeadsetProfile: Bluetooth service connected
09-01 11:15:33.646   875   875 D BluetoothHeadset: Proxy object connected
,09-01 11:15:33.647   875   875 D BluetoothHeadset: Proxy object connected
,09-01 11:15:33.647   875   875 D BluetoothHeadset: Proxy object connected
09-01 11:15:33.647  3855  3866 D BluetoothHeadset: Proxy object connected
,09-01 11:15:33.660  3855  3855 D HeadsetProfile: Bluetooth service connected
,09-01 11:15:33.915  3784  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:15:33.915  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:33.915  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:33.915  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:15:33.915  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:15:33.915  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:15:33.915  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:15:33.915  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 11:15:33.922  3784  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 11:15:33.925  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-01 11:15:33.926  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3af7de0 added. We now have 8 listener(s)
,09-01 11:15:33.926  3784  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 11:15:33.931   875  1711 D WifiService: setWifiEnabled: false pid=3784, uid=10000
,09-01 11:15:33.932   875  1711 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-01 11:15:33.944  3784  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:33.945   875   885 D WifiService: setWifiEnabled: true pid=3784, uid=10000
09-01 11:15:33.946   875   885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-01 11:15:33.957   875  1306 D WifiConfigStore: Loading config and enabling all networks 
,09-01 11:15:33.974  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:15:33.974  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:33.974  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:33.974  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:15:33.974  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:15:33.974  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:15:33.974  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:15:33.974  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 11:15:33.982  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-01 11:15:33.991   875  1306 D WifiConfigStore: loaded 0 passpoint configs
,09-01 11:15:33.992   875  1306 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-01 11:15:33.993   875  1306 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-01 11:15:33.994   875  1306 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-01 11:15:33.994   875  1306 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-01 11:15:33.994   875  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-01 11:15:33.994   875  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-01 11:15:34.008   875  1306 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.04 rxSuccessRate=0.05 delta 1000 -> 1000
,09-01 11:15:34.008   875  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-01 11:15:34.008   374   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-01 11:15:34.011   374   873 D CommandListener: Setting iface cfg
,09-01 11:15:34.019   875  1305 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
,09-01 11:15:34.019   875  1305 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-01 11:15:34.020   875  1306 E native  : do suspend true
,09-01 11:15:34.034   875  1306 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-01 11:15:34.034   875  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 11:15:34.035   875  1305 D WifiNative-HAL: p2pGetDeviceAddress
,09-01 11:15:34.035   875  1305 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-01 11:15:34.045   875  1306 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-01 11:15:34.125   875  1306 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-01 11:15:34.127  1463  1463 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-01 11:15:34.559  1463  1463 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-01 11:15:34.603  1463  1463 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-01 11:15:34.603  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-01 11:15:34.607   875  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-01 11:15:34.614   875  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-01 11:15:34.614   875  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 11:15:34.615   875  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-01 11:15:34.632   875  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 11:15:34.644   374   873 D CommandListener: Setting iface cfg
,09-01 11:15:34.644   875  1306 D WifiStateMachine: Start Dhcp Watchdog 3
,09-01 11:15:34.650   875  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-01 11:15:34.676   875  4233 D DhcpClient: Receive thread started
,09-01 11:15:34.760   875  1306 E native  : do suspend false
,09-01 11:15:34.780   875  1890 D DhcpClient: Broadcasting DHCPDISCOVER
,09-01 11:15:34.793   875  4233 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,09-01 11:15:34.795   875  1890 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,09-01 11:15:34.800   875  1890 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-01 11:15:34.815   875  4233 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-01 11:15:34.816   875  1890 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-01 11:15:34.824   374   873 D CommandListener: Setting iface cfg
,09-01 11:15:34.834   875  1890 D DhcpClient: Scheduling renewal in 86399s
,09-01 11:15:34.835   875  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
09-01 11:15:34.837   875  1306 E native  : do suspend true
,09-01 11:15:34.855   875  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-01 11:15:34.858   875  1306 D WifiConfigStore: No blacklist allowed without epno enabled
,09-01 11:15:34.859   875  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-01 11:15:34.861   875  1308 D ConnectivityService: Adding iface wlan0 to network 102
,09-01 11:15:34.868   875  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-01 11:15:34.947   875  1308 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-01 11:15:34.948   875  1308 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-01 11:15:34.952   875  1308 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-01 11:15:34.954   875  1308 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-01 11:15:34.963  3784  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:15:34.963  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:34.963  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:34.963  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:15:34.963  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:15:34.963  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:15:34.963  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:15:34.963  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 11:15:34.963   875  1308 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-01 11:15:34.967  3784  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-01 11:15:34.977  3784  3836 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-01 11:15:34.978  3784  3836 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-01 11:15:34.980  3784  3836 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@6de6aab Bundle[{}]
09-01 11:15:34.980   875  1308 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-01 11:15:34.980  3784  3836 I io.jxcore.node.LifeCycleMonitor: start: OK
09-01 11:15:34.980  3784  3836 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-01 11:15:34.981  3784  3836 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-01 11:15:34.981  3784  3836 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-01 11:15:34.982  3784  3836 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-01 11:15:34.983  3784  3836 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-01 11:15:34.986   875  1308 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-01 11:15:34.986   875  1308 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-01 11:15:34.986   875  1308 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-01 11:15:34.986   875  1308 D ConnectivityService:    accepting network in place of null
,09-01 11:15:34.987   875  1306 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-01 11:15:34.987  3784  3836 I System.out: Running OutgoingSocketThread
09-01 11:15:34.987   875  1308 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-01 11:15:34.988   875  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-01 11:15:34.989  3784  4236 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 424)
,09-01 11:15:34.989  3784  4236 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 48526
09-01 11:15:34.990  3784  4236 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-01 11:15:35.017   875  4232 D NetlinkSocketObserver: NeighborEvent{elapsedMs=152797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-01 11:15:35.030   374   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-01 11:15:35.065   374   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-01 11:15:35.077   875  1308 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-01 11:15:35.078   875  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-01 11:15:35.086   875  1308 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-01 11:15:35.086   875   892 D Tethering: MasterInitialState.processMessage what=3
,09-01 11:15:35.103  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:15:35.103  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:35.103  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:35.103  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:15:35.103  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:15:35.103  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:15:35.103  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:15:35.103  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 11:15:35.107   875  4231 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:802::200e
,09-01 11:15:35.109  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 11:15:35.124  1719  1719 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-01 11:15:35.131  1719  1719 D SystemUpdateService: onCreate
,09-01 11:15:35.135  1719  1719 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-01 11:15:35.143  1719  4243 I SystemUpdateService: active receiver: enabled,
,09-01 11:15:35.153  1719  4243 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-01 11:15:35.159  1719  1719 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-01 11:15:35.168  1719  1719 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-01 11:15:35.170  1719  1719 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-01 11:15:35.171  1719  4243 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-01 11:15:35.172  3949  3949 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-01 11:15:35.174  1719  4243 I SystemUpdateService: now status is 0 (complete)
,09-01 11:15:35.174  1719  4243 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-01 11:15:35.174  1719  4243 I SystemUpdateService: file has been verified
,09-01 11:15:35.184   875  4231 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 01 Sep 2016 09:15:35 GMT], X-Android-Received-Millis=[1472721335182], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472721335158]}
,09-01 11:15:35.185  1719  4246 I MDM     : [180] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-01 11:15:35.185  1719  4246 W BaseAppContext: Using Auth Proxy for data requests.
09-01 11:15:35.186   875  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-01 11:15:35.187   875  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,09-01 11:15:35.187  3949  3949 D SprintDMHelper: simOperator: 
09-01 11:15:35.187  3949  3949 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-01 11:15:35.187   875  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-01 11:15:35.194   875  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-01 11:15:35.196  1719  4246 V GoogleAuthProtoRequest: [180] a.<init>: mAccountName set to: thalitester@gmail.com
,09-01 11:15:35.207  1719  4243 I SystemUpdateService: OTA package size = 12249756
,09-01 11:15:35.227  1719  2449 I iu.UploadsManager: num queued entries: 0
,09-01 11:15:35.227  1719  2449 I iu.UploadsManager: num updated entries: 0
,09-01 11:15:35.230  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 11:15:35.234  1719  2449 I iu.SyncManager: NEXT; no task
,09-01 11:15:35.236  1719  4243 I SystemUpdateService: showing system update notification
,09-01 11:15:35.238  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 11:15:35.278  1719  1719 D SystemUpdateService: onDestroy
,09-01 11:15:35.288  1514  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-01 11:15:35.289  1514  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-01 11:15:35.289  1514  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 11:15:35.289  1514  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 11:15:35.307  3907  4249 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-01 11:15:35.312  1719  4246 E MDM     : [180] SitrepService.a: Error sending sitrep.
,09-01 11:15:35.990  3784  3836 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 425)
,09-01 11:15:35.991  3784  3836 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 425)
,09-01 11:15:36.001  3784  3836 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 430)
,09-01 11:15:36.004  3784  3836 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-01 11:15:36.004  3784  3836 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 431)
,09-01 11:15:36.008  3784  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-01 11:15:36.009  3784  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5530899 added. We now have 2 listener(s)
,09-01 11:15:36.011  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-01 11:15:36.011  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:15:36.011  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-01 11:15:36.012  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:15:36.012  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f775e added. We now have 9 listener(s)
09-01 11:15:36.012  3784  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:15:36.013  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-01 11:15:36.018  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:15:36.025  3784  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:15:36.025  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:36.025  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:36.025  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:15:36.025  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:15:36.025  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:15:36.025  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:15:36.025  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 11:15:36.028  3784  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 11:15:36.029  3784  3836 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 11:15:36.030  3784  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:15:36.030  3784  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7be980c added. We now have 3 listener(s)
09-01 11:15:36.032  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:15:36.033  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-01 11:15:36.033  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:15:36.033  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:15:36.033  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:15:36.033  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c29555 added. We now have 10 listener(s)
09-01 11:15:36.033  3784  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 11:15:36.033  3784  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:15:36.034  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:36.034  3784  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:36.034  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-01 11:15:36.034  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:36.034  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:15:36.034  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:15:36.034  3784  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5530899 removed from the list
09-01 11:15:36.034  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 11:15:36.034  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f775e removed from the list
09-01 11:15:36.037  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:36.038  3784  3836 D io.jxcore.node.ConnectivityMonitor: stop
,09-01 11:15:36.038  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:15:36.038  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 11:15:36.038  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:15:36.039  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 11:15:36.039  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:36.040  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:36.040  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f775e not in the list
09-01 11:15:36.040  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:36.040  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:36.041  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:36.041  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 11:15:36.041  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:36.041  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c29555 removed from the list
09-01 11:15:36.041  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:36.041  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:36.041  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:36.041  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:15:36.041  3784  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7be980c removed from the list
,09-01 11:15:36.042  3784  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:15:36.042  3784  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@817ab6a added. We now have 2 listener(s)
09-01 11:15:36.044  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-01 11:15:36.044  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:15:36.044  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:15:36.045  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:15:36.045  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@64a785b added. We now have 9 listener(s)
09-01 11:15:36.045  3784  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 11:15:36.045  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-01 11:15:36.048  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:15:36.056  3784  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:15:36.056  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:36.056  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:36.056  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:15:36.056  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:15:36.056  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:15:36.056  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:15:36.056  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 11:15:36.060  3784  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 11:15:36.060  3784  3836 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 11:15:36.061  3784  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:15:36.061  3784  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46431d1 added. We now have 3 listener(s)
,09-01 11:15:36.064  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:36.067  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-01 11:15:36.067  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:15:36.067  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:15:36.067  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:15:36.068  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-01 11:15:36.068  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e7d1436 added. We now have 10 listener(s)
09-01 11:15:36.068  3784  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 11:15:36.069  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 11:15:36.069  3784  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 11:15:36.070  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 11:15:36.070  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:15:36.070  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-01 11:15:36.073   875  1308 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-01 11:15:36.076  3784  3836 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-01 11:15:36.076  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-01 11:15:36.086  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-01 11:15:36.087  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-01 11:15:36.088  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-01 11:15:36.095  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-01 11:15:36.095  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-01 11:15:36.095  3784  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-01 11:15:36.097  3784  3836 D BluetoothAdapter: STATE_ON
,09-01 11:15:36.103  4169  4180 D BtGatt.GattService: registerClient() - UUID=9cbe00e7-2d63-44f1-ab01-04961705e6d6
,09-01 11:15:36.105  4169  4185 D BtGatt.GattService: onClientRegistered() - UUID=9cbe00e7-2d63-44f1-ab01-04961705e6d6, clientIf=5
,09-01 11:15:36.106  3784  3795 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-01 11:15:36.108  4169  4202 D BtGatt.GattService: start scan with filters
,09-01 11:15:36.118  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-01 11:15:36.118  4169  4188 D BtGatt.ScanManager: handling starting scan
,09-01 11:15:36.118  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-01 11:15:36.119  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-01 11:15:36.119  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-01 11:15:36.122  4169  4188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b148f
,09-01 11:15:36.128  3784  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 11:15:36.129  3784  3784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 11:15:36.129  3784  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-01 11:15:36.131  4169  4185 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-01 11:15:36.131  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:15:36.133  4169  4188 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-01 11:15:36.138  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-01 11:15:36.144  3784  3836 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-01 11:15:36.144  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:36.144  3784  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-01 11:15:36.144  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:36.145  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-01 11:15:36.145  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-01 11:15:36.145  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 11:15:36.145  3784  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-01 11:15:36.145  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-01 11:15:36.146  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-01 11:15:36.146  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-01 11:15:36.148  3784  3836 D BluetoothAdapter: STATE_ON
09-01 11:15:36.150  4169  4180 D BtGatt.GattService: stopScan() - queue size =1
,09-01 11:15:36.153  4169  4185 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-01 11:15:36.153  4169  4202 D BtGatt.GattService: unregisterClient() - clientIf=5
09-01 11:15:36.153  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-01 11:15:36.154  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-01 11:15:36.154  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-01 11:15:36.154  4169  4188 D BtGatt.ScanManager: Starting BLE batch scan
,09-01 11:15:36.154  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-01 11:15:36.155  4169  4188 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-01 11:15:36.155  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-01 11:15:36.155  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-01 11:15:36.161  3784  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 11:15:36.161  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-01 11:15:36.162  3784  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-01 11:15:36.162  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-01 11:15:36.164  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 11:15:36.166  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-01 11:15:36.167  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 11:15:36.167  3784  3784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 11:15:36.172  3784  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 11:15:36.172  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-01 11:15:36.173  3784  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:36.173  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-01 11:15:36.173  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 11:15:36.174  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 11:15:36.174  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:15:36.174  3784  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@817ab6a removed from the list
,09-01 11:15:36.174  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:36.175  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@64a785b removed from the list
09-01 11:15:36.175  3784  3836 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:36.175  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:15:36.176  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:36.177  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:36.179  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:36.179  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-01 11:15:36.179  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 11:15:36.180  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@64a785b not in the list
09-01 11:15:36.180  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:36.180  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:36.183  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:36.183  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:36.183  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:36.183  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e7d1436 removed from the list
09-01 11:15:36.184  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-01 11:15:36.184  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 11:15:36.184  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:36.185  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-01 11:15:36.185  3784  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46431d1 removed from the list
,09-01 11:15:36.185  4169  4185 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-01 11:15:36.185  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-01 11:15:36.187  3784  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:15:36.187  3784  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fe3dc2 added. We now have 2 listener(s)
,09-01 11:15:36.194  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-01 11:15:36.194  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-01 11:15:36.195  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-01 11:15:36.195  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:15:36.196  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71d97d3 added. We now have 9 listener(s)
09-01 11:15:36.196  3784  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 11:15:36.197  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-01 11:15:36.203  4169  4185 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-01 11:15:36.203  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-01 11:15:36.205  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:15:36.218  3784  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:15:36.218  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:36.218  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:36.218  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:15:36.218  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:15:36.218  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:15:36.218  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:15:36.218  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 11:15:36.220  3784  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 11:15:36.220  3784  3836 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 11:15:36.221  3784  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-01 11:15:36.221  3784  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5da4a09 added. We now have 3 listener(s)
,09-01 11:15:36.223  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-01 11:15:36.223  4169  4185 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-01 11:15:36.223  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:15:36.223  4169  4188 D BtGatt.ScanManager: stopping BLe Batch
09-01 11:15:36.223  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:36.223  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:15:36.223  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:15:36.224  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:15:36.224  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c76740e added. We now have 10 listener(s)
,09-01 11:15:36.224  3784  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:15:36.225  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-01 11:15:36.225  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-01 11:15:36.225  3784  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 11:15:36.226  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 11:15:36.226  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:15:36.226  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 11:15:36.226  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:15:36.229  3784  3836 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-01 11:15:36.229  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-01 11:15:36.229  4169  4185 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-01 11:15:36.229  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-01 11:15:36.230  4169  4188 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-01 11:15:36.233  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-01 11:15:36.233  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-01 11:15:36.233  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-01 11:15:36.235  4169  4185 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-01 11:15:36.235  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:15:36.237  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-01 11:15:36.237  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-01 11:15:36.237  3784  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-01 11:15:36.238  3784  3836 D BluetoothAdapter: STATE_ON
,09-01 11:15:36.239  4169  4213 D BtGatt.GattService: registerClient() - UUID=182f12db-1d94-4a18-90f7-c54dc7590c83
09-01 11:15:36.240  4169  4185 D BtGatt.GattService: onClientRegistered() - UUID=182f12db-1d94-4a18-90f7-c54dc7590c83, clientIf=5
09-01 11:15:36.240  3784  3795 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-01 11:15:36.240  4169  4180 D BtGatt.GattService: start scan with filters
,09-01 11:15:36.242  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-01 11:15:36.242  4169  4188 D BtGatt.ScanManager: handling starting scan
09-01 11:15:36.243  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-01 11:15:36.243  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-01 11:15:36.243  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-01 11:15:36.245  3784  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 11:15:36.245  3784  3784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-01 11:15:36.245  3784  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-01 11:15:36.247  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-01 11:15:36.249  4169  4185 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-01 11:15:36.249  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:15:36.249  4169  4188 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-01 11:15:36.250  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-01 11:15:36.251  3784  3836 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-01 11:15:36.251  3784  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 11:15:36.251  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:36.251  3784  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:36.252  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-01 11:15:36.252  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:36.252  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-01 11:15:36.252  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-01 11:15:36.252  3784  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fe3dc2 removed from the list
09-01 11:15:36.252  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 11:15:36.252  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71d97d3 removed from the list
09-01 11:15:36.252  3784  3836 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:36.252  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 11:15:36.253  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:36.253  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-01 11:15:36.253  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 11:15:36.253  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 11:15:36.254  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 11:15:36.254  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:36.254  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:36.254  4169  4185 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-01 11:15:36.254  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71d97d3 not in the list
,09-01 11:15:36.254  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:15:36.254  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 11:15:36.254  3784  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-01 11:15:36.254  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 11:15:36.254  4169  4188 D BtGatt.ScanManager: Starting BLE batch scan
,09-01 11:15:36.254  4169  4188 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-01 11:15:36.255  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-01 11:15:36.255  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-01 11:15:36.255  3784  3836 D BluetoothAdapter: STATE_ON
09-01 11:15:36.256  4169  4180 D BtGatt.GattService: stopScan() - queue size =1
09-01 11:15:36.256  4169  4202 D BtGatt.GattService: unregisterClient() - clientIf=5
09-01 11:15:36.257  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:15:36.257  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-01 11:15:36.257  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-01 11:15:36.257  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-01 11:15:36.257  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-01 11:15:36.258  3784  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 11:15:36.258  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-01 11:15:36.258  3784  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-01 11:15:36.258  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-01 11:15:36.258  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:36.260  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 11:15:36.260  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-01 11:15:36.260  3784  3784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 11:15:36.260  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:36.260  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 11:15:36.260  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 11:15:36.260  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c76740e removed from the list
09-01 11:15:36.260  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:36.260  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:36.260  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:36.260  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:15:36.261  3784  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5da4a09 removed from the list
09-01 11:15:36.261  3784  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:15:36.261  3784  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a29c31a added. We now have 2 listener(s)
,09-01 11:15:36.263  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-01 11:15:36.263  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:15:36.263  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:15:36.263  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:15:36.263  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d562e4b added. We now have 9 listener(s)
09-01 11:15:36.263  3784  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:15:36.264  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-01 11:15:36.264  4169  4185 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-01 11:15:36.264  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:15:36.266  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:15:36.270  3784  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:15:36.270  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:36.270  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:36.270  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:15:36.270  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:15:36.270  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:15:36.270  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:15:36.270  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:15:36.270  4169  4185 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-01 11:15:36.270  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:15:36.272  3784  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 11:15:36.272  3784  3836 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 11:15:36.272  3784  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:15:36.273  3784  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5843141 added. We now have 3 listener(s)
,09-01 11:15:36.274  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:36.276  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-01 11:15:36.276  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:15:36.276  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:15:36.276  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:15:36.276  4169  4185 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-01 11:15:36.276  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:36.276  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@990f6e6 added. We now have 10 listener(s)
09-01 11:15:36.276  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:15:36.276  3784  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:15:36.276  4169  4188 D BtGatt.ScanManager: stopping BLe Batch
,09-01 11:15:36.276  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 11:15:36.276  3784  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 11:15:36.277  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 11:15:36.277  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:15:36.277  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-01 11:15:36.280  3784  3836 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-01 11:15:36.280  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-01 11:15:36.282  4169  4185 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-01 11:15:36.282  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:15:36.282  4169  4188 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-01 11:15:36.283  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-01 11:15:36.284  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-01 11:15:36.284  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-01 11:15:36.287  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-01 11:15:36.287  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-01 11:15:36.287  3784  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-01 11:15:36.287  4169  4185 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-01 11:15:36.287  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:15:36.288  3784  3836 D BluetoothAdapter: STATE_ON
,09-01 11:15:36.289  4169  4213 D BtGatt.GattService: registerClient() - UUID=4e1ac752-745c-4b89-bf4a-64a6fdd22854
,09-01 11:15:36.289  4169  4185 D BtGatt.GattService: onClientRegistered() - UUID=4e1ac752-745c-4b89-bf4a-64a6fdd22854, clientIf=5
,09-01 11:15:36.290  3784  3832 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-01 11:15:36.290  4169  4180 D BtGatt.GattService: start scan with filters
,09-01 11:15:36.292  4169  4188 D BtGatt.ScanManager: handling starting scan
,09-01 11:15:36.292  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-01 11:15:36.292  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-01 11:15:36.292  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-01 11:15:36.292  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-01 11:15:36.294  3784  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-01 11:15:36.295  3784  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-01 11:15:36.295  3784  3784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-01 11:15:36.296  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
,09-01 11:15:36.297  4169  4185 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-01 11:15:36.297  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:15:36.298  4169  4188 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-01 11:15:36.300  3784  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 11:15:36.301  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:36.301  3784  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:36.301  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:36.301  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:36.301  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-01 11:15:36.301  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:15:36.301  3784  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a29c31a removed from the list
09-01 11:15:36.301  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:36.301  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d562e4b removed from the list
09-01 11:15:36.301  3784  3836 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:36.301  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:15:36.302  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:36.302  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-01 11:15:36.302  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 11:15:36.302  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:15:36.302  4169  4185 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-01 11:15:36.302  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:15:36.303  4169  4188 D BtGatt.ScanManager: Starting BLE batch scan
,09-01 11:15:36.303  4169  4188 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-01 11:15:36.303  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:36.303  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:36.303  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:36.303  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d562e4b not in the list
09-01 11:15:36.303  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-01 11:15:36.303  3784  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-01 11:15:36.303  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 11:15:36.304  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-01 11:15:36.304  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-01 11:15:36.304  3784  3836 D BluetoothAdapter: STATE_ON
09-01 11:15:36.304  4169  4179 D BtGatt.GattService: stopScan() - queue size =1
,09-01 11:15:36.305  4169  4180 D BtGatt.GattService: unregisterClient() - clientIf=5
09-01 11:15:36.305  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:15:36.305  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-01 11:15:36.305  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-01 11:15:36.305  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-01 11:15:36.306  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-01 11:15:36.306  3784  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 11:15:36.306  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-01 11:15:36.307  3784  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-01 11:15:36.307  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-01 11:15:36.307  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:15:36.308  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-01 11:15:36.308  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:36.308  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:36.308  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 11:15:36.308  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@990f6e6 removed from the list
09-01 11:15:36.308  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:36.308  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:36.308  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 11:15:36.308  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:36.308  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-01 11:15:36.308  3784  3784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 11:15:36.308  3784  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5843141 removed from the list
09-01 11:15:36.309  3784  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:15:36.309  3784  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e59b72 added. We now have 2 listener(s)
,09-01 11:15:36.310  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-01 11:15:36.310  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:15:36.310  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:15:36.310  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:15:36.310  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34c1bc3 added. We now have 9 listener(s)
,09-01 11:15:36.311  3784  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:15:36.311  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-01 11:15:36.312  4169  4185 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-01 11:15:36.312  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-01 11:15:36.313  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:15:36.316  3784  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:15:36.316  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:36.316  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:36.316  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:15:36.316  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:15:36.316  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:15:36.316  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:15:36.316  3784  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 11:15:36.317  4169  4185 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-01 11:15:36.317  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-01 11:15:36.318  3784  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 11:15:36.318  3784  3836 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 11:15:36.318  3784  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-01 11:15:36.318  3784  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2cc779 added. We now have 3 listener(s)
,09-01 11:15:36.320  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:15:36.320  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-01 11:15:36.320  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-01 11:15:36.320  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:15:36.320  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:15:36.320  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e6dfcbe added. We now have 10 listener(s)
,09-01 11:15:36.320  3784  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:15:36.321  3784  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:15:36.321  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:36.321  3784  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-01 11:15:36.321  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:36.321  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:36.321  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:15:36.321  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:15:36.322  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:15:36.322  3784  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e59b72 removed from the list
09-01 11:15:36.322  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:36.322  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34c1bc3 removed from the list
,09-01 11:15:36.322  3784  3836 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:36.322  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:36.322  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:36.322  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:36.323  4169  4185 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-01 11:15:36.323  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:15:36.323  4169  4188 D BtGatt.ScanManager: stopping BLe Batch
09-01 11:15:36.323  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 11:15:36.323  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:36.323  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:36.323  3784  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34c1bc3 not in the list
09-01 11:15:36.324  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:36.324  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:36.325  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:36.325  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 11:15:36.325  3784  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:36.325  3784  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e6dfcbe removed from the list
09-01 11:15:36.325  3784  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:36.325  3784  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:36.325  3784  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:36.325  3784  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:15:36.325  3784  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2cc779 removed from the list
09-01 11:15:36.326  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-01 11:15:36.326  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-01 11:15:36.327  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-01 11:15:36.327  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 11:15:36.327  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-01 11:15:36.327  3784  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:36.328  4169  4185 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-01 11:15:36.328  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 11:15:36.328  4169  4188 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-01 11:15:36.332  3784  4255 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 438, name: My test thread name)
,09-01 11:15:36.332  3784  4255 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 438, thread name: My test thread name)
09-01 11:15:36.332  3784  4255 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 438, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-01 11:15:36.333  4169  4185 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-01 11:15:36.333  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-01 11:15:36.334  3784  4256 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 440, name: My test thread name)
09-01 11:15:36.334  3784  4256 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 440, thread name: My test thread name)
09-01 11:15:36.334  3784  4256 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 440, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-01 11:15:36.335  3784  3836 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,09-01 11:15:36.335  3784  3836 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-01 11:15:36.335  3784  3836 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-01 11:15:36.336  3784  3836 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-01 11:15:36.336  3784  3836 D com.test.thalitest.ThaliTestRunner: Total duration: 22804 ms
,09-01 11:15:36.337  3784  3836 I jxcore-log: *Native tests were executed*
09-01 11:15:36.337  3784  3836 I jxcore-log: 
,09-01 11:15:36.338  3784  3836 I jxcore-log: Total number of executed tests:  80
09-01 11:15:36.338  3784  3836 I jxcore-log: 
09-01 11:15:36.338  3784  3836 I jxcore-log: Number of passed tests:  80
09-01 11:15:36.338  3784  3836 I jxcore-log: 
09-01 11:15:36.338  3784  3836 I jxcore-log: Number of failed tests:  0
09-01 11:15:36.338  3784  3836 I jxcore-log: 
09-01 11:15:36.338  3784  3836 I jxcore-log: Number of ignored tests:  0
09-01 11:15:36.338  3784  3836 I jxcore-log: 
09-01 11:15:36.338  3784  3836 I jxcore-log: Total duration:  22804
09-01 11:15:36.338  3784  3836 I jxcore-log: 
09-01 11:15:36.338  3784  3836 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-01 11:15:36.338  3784  3836 I jxcore-log: 
,09-01 11:15:36.341  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:15:36.341  3784  3836 I jxcore-log: 
09-01 11:15:36.344  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:15:36.344  3784  3836 I jxcore-log: 
09-01 11:15:36.344  3784  3784 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-01 11:15:36.345  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:15:36.345  3784  3836 I jxcore-log: 
09-01 11:15:36.346  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:15:36.346  3784  3836 I jxcore-log: 
09-01 11:15:36.347  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:15:36.347  3784  3836 I jxcore-log: 
09-01 11:15:36.348  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:15:36.348  3784  3836 I jxcore-log: 
09-01 11:15:36.350  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:15:36.350  3784  3836 I jxcore-log: 
09-01 11:15:36.352  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-01 11:15:36.352  3784  3836 I jxcore-log: 
09-01 11:15:36.353  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-01 11:15:36.353  3784  3836 I jxcore-log: 
09-01 11:15:36.353  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 11:15:36.353  3784  3836 I jxcore-log: 
09-01 11:15:36.354  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 11:15:36.354  3784  3836 I jxcore-log: 
09-01 11:15:36.355  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-01 11:15:36.355  3784  3836 I jxcore-log: 
09-01 11:15:36.356  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-01 11:15:36.356  3784  3836 I jxcore-log: 
09-01 11:15:36.357  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-01 11:15:36.357  3784  3836 I jxcore-log: 
09-01 11:15:36.358  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:15:36.358  3784  3836 I jxcore-log: 
,09-01 11:15:36.358  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:15:36.358  3784  3836 I jxcore-log: 
09-01 11:15:36.359  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-01 11:15:36.359  3784  3836 I jxcore-log: 
09-01 11:15:36.360  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-01 11:15:36.360  3784  3836 I jxcore-log: 
09-01 11:15:36.360  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 11:15:36.360  3784  3836 I jxcore-log: 
,09-01 11:15:36.361  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 11:15:36.361  3784  3836 I jxcore-log: 
,09-01 11:15:36.362  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-01 11:15:36.362  3784  3836 I jxcore-log: 
,09-01 11:15:36.363  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-01 11:15:36.363  3784  3836 I jxcore-log: 
09-01 11:15:36.363  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 11:15:36.363  3784  3836 I jxcore-log: 
,09-01 11:15:36.364  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 11:15:36.364  3784  3836 I jxcore-log: 
,09-01 11:15:36.365  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-01 11:15:36.365  3784  3836 I jxcore-log: 
09-01 11:15:36.366  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-01 11:15:36.366  3784  3836 I jxcore-log: 
09-01 11:15:36.366  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-01 11:15:36.366  3784  3836 I jxcore-log: 
,09-01 11:15:36.367  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-01 11:15:36.367  3784  3836 I jxcore-log: 
,09-01 11:15:36.367  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:15:36.367  3784  3836 I jxcore-log: 
09-01 11:15:36.368  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:15:36.368  3784  3836 I jxcore-log: 
09-01 11:15:36.368  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:15:36.368  3784  3836 I jxcore-log: 
09-01 11:15:36.369  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:15:36.369  3784  3836 I jxcore-log: 
09-01 11:15:36.369  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:15:36.369  3784  3836 I jxcore-log: 
09-01 11:15:36.370  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:15:36.370  3784  3836 I jxcore-log: 
,09-01 11:15:36.668  3784  3784 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-01 11:15:36.673  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-01 11:15:36.673  3784  3836 I jxcore-log: 
,09-01 11:15:36.760  3784  3784 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-01 11:15:36.764  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-01 11:15:36.764  3784  3836 I jxcore-log: 
,09-01 11:15:36.809  3784  3784 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-01 11:15:36.812  3784  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-01 11:15:36.812  3784  3836 I jxcore-log: 
,09-01 11:15:37.004  4257  4257 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-01 11:15:37.009  4257  4257 D AndroidRuntime: CheckJNI is OFF
,09-01 11:15:37.051  4257  4257 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-01 11:15:37.098  4257  4257 I Radio-JNI: register_android_hardware_Radio DONE
,09-01 11:15:37.121  4257  4257 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-01 11:15:37.131   875   888 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
09-01 11:15:37.132   875   888 I ActivityManager: Killing 3784:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-01 11:15:37.224   875   898 W PackageSettings: Skipping PackageSetting{95c6f40 com.example.hello/10273} due to missing metadata
,09-01 11:15:37.245   875  1964 D GraphicsStats: Buffer count: 2
,09-01 11:15:37.246   875  1307 D WifiService: Client connection lost with reason: 4
09-01 11:15:37.245   875  1967 I WindowState: WIN DEATH: Window{3ff98b7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-01 11:15:37.271   875   898 I art     : Starting a blocking GC Explicit
,09-01 11:15:37.281   875   888 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-01 11:15:37.282   875   888 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-01 11:15:37.283   875   888 E ActivityManager: Failure starting process com.test.thalitest
09-01 11:15:37.283   875   888 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-01 11:15:37.283   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-01 11:15:37.283   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-01 11:15:37.283   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-01 11:15:37.283   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-01 11:15:37.283   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-01 11:15:37.283   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-01 11:15:37.283   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-01 11:15:37.283   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-01 11:15:37.283   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-01 11:15:37.283   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-01 11:15:37.283   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-01 11:15:37.283   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-01 11:15:37.283   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-01 11:15:37.283   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-01 11:15:37.283   875   888 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:15:37.283   875   888 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-01 11:15:37.283   875   888 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-01 11:15:37.283   875   888 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-01 11:15:37.285   875   888 I ActivityManager:   Force finishing activity ActivityRecord{dda3f2c u0 com.test.thalitest/.MainActivity t2}
,09-01 11:15:37.293   875  1371 W ActivityManager: Spurious death for ProcessRecord{3af6c40 0:com.test.thalitest/u0a0}, curProc for 3784: null
,09-01 11:15:37.332   875   898 I art     : Explicit concurrent mark sweep GC freed 57115(3MB) AllocSpace objects, 10(300KB) LOS objects, 33% free, 29MB/43MB, paused 862us total 60.374ms
,09-01 11:15:37.352   875   898 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-01 11:15:37.353  4257  4257 I art     : System.exit called, status: 0
,09-01 11:15:37.353  4257  4257 I AndroidRuntime: VM exiting with result code 0.
,09-01 11:15:37.371   875   898 I ActivityManager: Start proc 4267:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,09-01 11:15:37.372   875   898 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-01 11:15:37.395   875   888 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-01 11:15:37.402   875  1297 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-01 11:15:37.403  1871  1871 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-01 11:15:37.408  2034  2265 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-01 11:15:37.409  4169  4169 D BluetoothMapAppObserver: onReceive
,09-01 11:15:37.409  4169  4169 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-01 11:15:37.431  3592  3592 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,09-01 11:15:37.432  1871  4282 I Keyboard.Facilitator.DecoderInitializer: run()
,09-01 11:15:37.438  1871  4282 I Decoder : createOrResetDecoder
,09-01 11:15:37.459  1937  1937 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-01 11:15:37.478   875  1967 I ActivityManager: Start proc 4283:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-01 11:15:37.483  1514  1514 I ConfigService: onCreate
,09-01 11:15:37.490  1514  4289 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-01 11:15:37.490  1514  4289 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 11:15:37.490  1514  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-01 11:15:37.490  1514  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-01 11:15:37.490  1514  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-01 11:15:37.490  1514  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-01 11:15:37.490  1514  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-01 11:15:37.490  1514  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-01 11:15:37.490  1514  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-01 11:15:37.490  1514  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-01 11:15:37.490  1514  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-01 11:15:37.490  1514  4289 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-01 11:15:37.490  1514  4289 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-01 11:15:37.490  1514  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 11:15:37.490  1514  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-01 11:15:37.490  1514  4289 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-01 11:15:37.490  1514  4289 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-01 11:15:37.490  1514  4289 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,09-01 11:15:37.490  1514  4289 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-01 11:15:37.490  1514  4289 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 11:15:37.490  1514  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-01 11:15:37.490  1514  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-01 11:15:37.490  1514  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-01 11:15:37.490  1514  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-01 11:15:37.490  1514  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-01 11:15:37.490  1514  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-01 11:15:37.490  1514  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-01 11:15:37.490  1514  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-01 11:15:37.490  1514  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-01 11:15:37.490  1514  4289 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-01 11:15:37.490  1514  4289 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-01 11:15:37.490  1514  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 11:15:37.490  1514  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-01 11:15:37.490  1514  4289 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-01 11:15:37.490  1514  4289 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-01 11:15:37.490  1514  4289 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-01 11:15:37.490   875   875 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-01 11:15:37.494  1514  4289 W SQLiteOpenHelper: Opened config.db in read-only mode
,09-01 11:15:37.497   875   885 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3784 uid 10000
,09-01 11:15:37.498  1871  1871 I Keyboard.Facilitator: onFinishInput()
,09-01 11:15:37.510  1871  4282 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-01 11:15:37.528  4283  4283 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-01 11:15:37.531  1955  2033 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-01 11:15:37.532   875   887 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-01 11:15:37.533   875   887 E PackageManager: Failed to write settings, restoring backup
09-01 11:15:37.533   875   887 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-01 11:15:37.533   875   887 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-01 11:15:37.533   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-01 11:15:37.533   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-01 11:15:37.533   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-01 11:15:37.533   875   887 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:15:37.533   875   887 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-01 11:15:37.533   875   887 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-01 11:15:37.537   875   888 E DropBoxManagerService: Can't write: system_server_wtf
09-01 11:15:37.537   875   888 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-01 11:15:37.537   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-01 11:15:37.537   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-01 11:15:37.537   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-01 11:15:37.537   875   888 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-01 11:15:37.537   875   888 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-01 11:15:37.537   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-01 11:15:37.537   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-01 11:15:37.537   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-01 11:15:37.537   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-01 11:15:37.537   875   888 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-01 11:15:37.537   875   888 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-01 11:15:37.537   875   888 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-01 11:15:37.537   875   888 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-01 11:15:37.537   875   888 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-01 11:15:37.537   875   888 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-01 11:15:37.537   875   888 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-01 11:15:37.537   875   888 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-01 11:15:37.537   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-01 11:15:37.537   875   888 E DropBoxManagerService: 	... 13 more
,09-01 11:15:37.543  1871  4282 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-01 11:15:37.543   875  2233 I ActivityManager: Start proc 4297:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-01 11:15:37.544  1955  2033 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-01 11:15:37.544  1955  2033 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1955
09-01 11:15:37.544  1955  2033 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-01 11:15:37.544  1955  2033 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-01 11:15:37.544  1955  2033 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-01 11:15:37.544  1955  2033 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-01 11:15:37.544  1955  2033 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-01 11:15:37.544  1955  2033 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-01 11:15:37.544  1955  2033 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-01 11:15:37.544  1955  2033 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-01 11:15:37.544  1955  2033 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-01 11:15:37.544  1955  2033 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-01 11:15:37.544  1955  2033 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-01 11:15:37.544  1955  2033 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-01 11:15:37.546   875  1949 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-01 11:15:37.546   875  4303 E DropBoxManagerService: Can't write: system_app_crash
09-01 11:15:37.546   875  4303 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
09-01 11:15:37.546   875  4303 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-01 11:15:37.546   875  4303 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-01 11:15:37.546   875  4303 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-01 11:15:37.546   875  4303 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-01 11:15:37.546   875  4303 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-01 11:15:37.546   875  4303 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-01 11:15:37.546   875  4303 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-01 11:15:37.546   875  4303 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-01 11:15:37.546   875  4303 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-01 11:15:37.546   875  4303 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-01 11:15:37.546   875  4303 E DropBoxManagerService: 	... 5 more
,09-01 11:15:37.550  1955  2033 I Process : Sending signal. PID: 1955 SIG: 9
,09-01 11:15:37.552  1871  4282 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,09-01 11:15:37.552  1871  4282 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-01 11:15:37.554  1871  4282 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,09-01 11:15:37.554  1871  4282 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,09-01 11:15:37.555  1871  4282 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,09-01 11:15:37.555  1871  4282 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,09-01 11:15:37.557  1871  4282 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,09-01 11:15:37.557  1871  4282 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-01 11:15:37.557  1871  4282 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-01 11:15:37.557  1871  4282 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-01 11:15:37.557  1871  4282 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-01 11:15:37.557  1871  4282 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-01 11:15:37.673  4283  4283 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-01 11:15:37.690  4283  4317 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-01 11:15:37.704   875  1954 I ActivityManager: Start proc 4318:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-01 11:15:37.704  4283  4313 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-01 11:15:37.704  4283  4313 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 11:15:37.704  4283  4313 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-01 11:15:37.704  4283  4313 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-01 11:15:37.704  4283  4313 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-01 11:15:37.704  4283  4313 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-01 11:15:37.704  4283  4313 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-01 11:15:37.704  4283  4313 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-01 11:15:37.704  4283  4313 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-01 11:15:37.704  4283  4313 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-01 11:15:37.704  4283  4313 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-01 11:15:37.704  4283  4313 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-01 11:15:37.704  4283  4313 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-01 11:15:37.704  4283  4313 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 11:15:37.704  4283  4313 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-01 11:15:37.704  4283  4313 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-01 11:15:37.704  4283  4313 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-01 11:15:37.704  4283  4313 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-01 11:15:37.704  4283  4313 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-01 11:15:37.704  4283  4313 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:15:37.704  4283  4313 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-01 11:15:37.704  4283  4313 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-01 11:15:37.705  4283  4313 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-01 11:15:37.705  4283  4313 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 11:15:37.705  4283  4313 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-01 11:15:37.705  4283  4313 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-01 11:15:37.705  4283  4313 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-01 11:15:37.705  4283  4313 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-01 11:15:37.705  4283  4313 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-01 11:15:37.705  4283  4313 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-01 11:15:37.705  4283  4313 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-01 11:15:37.705  4283  4313 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-01 11:15:37.705  4283  4313 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-01 11:15:37.705  4283  4313 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-01 11:15:37.705  4283  4313 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-01 11:15:37.705  4283  4313 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 11:15:37.705  4283  4313 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-01 11:15:37.705  4283  4313 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-01 11:15:37.705  4283  4313 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-01 11:15:37.705  4283  4313 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-01 11:15:37.705  4283  4313 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-01 11:15:37.705  4283  4313 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:15:37.705  4283  4313 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-01 11:15:37.705  4283  4313 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-01 11:15:37.711   875  2245 I WindowState: WIN DEATH: Window{bb3274d u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-01 11:15:37.711   875   885 D GraphicsStats: Buffer count: 1
,09-01 11:15:37.727   875  1528 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1955) has died
,09-01 11:15:37.727   875  1528 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-01 11:15:37.728   875  1528 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-01 11:15:37.749   875   888 I ActivityManager: Start proc 4330:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-01 11:15:37.766  1719  4316 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,09-01 11:15:37.768  1719  4316 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,09-01 11:15:37.780  4318  4318 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-01 11:15:37.795  1514  1514 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-01 11:15:37.795  1514  1514 D AndroidRuntime: Shutting down VM
,09-01 11:15:37.796  1514  1514 E AndroidRuntime: FATAL EXCEPTION: main
09-01 11:15:37.796  1514  1514 E AndroidRuntime: Process: com.google.process.gapps, PID: 1514
09-01 11:15:37.796  1514  1514 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-01 11:15:37.796  1514  1514 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-01 11:15:37.796  1514  1514 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-01 11:15:37.796  1514  1514 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-01 11:15:37.796  1514  1514 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:15:37.796  1514  1514 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-01 11:15:37.796  1514  1514 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 11:15:37.796  1514  1514 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:15:37.796  1514  1514 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 11:15:37.796  1514  1514 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 11:15:37.796  1514  1514 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-01 11:15:37.796  1514  1514 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-01 11:15:37.796  1514  1514 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-01 11:15:37.796  1514  1514 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-01 11:15:37.796  1514  1514 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-01 11:15:37.796  1514  1514 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-01 11:15:37.796  1514  1514 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-01 11:15:37.796  1514  1514 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-01 11:15:37.796  1514  1514 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-01 11:15:37.796  1514  1514 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725),
09-01 11:15:37.796  1514  1514 E AndroidRuntime: 	... 8 more
,09-01 11:15:37.799   875  4345 E DropBoxManagerService: Can't write: system_app_crash
09-01 11:15:37.799   875  4345 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
09-01 11:15:37.799   875  4345 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-01 11:15:37.799   875  4345 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-01 11:15:37.799   875  4345 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-01 11:15:37.799   875  4345 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-01 11:15:37.799   875  4345 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-01 11:15:37.799   875  4345 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-01 11:15:37.799   875  4345 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-01 11:15:37.799   875  4345 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-01 11:15:37.799   875  4345 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-01 11:15:37.799   875  4345 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-01 11:15:37.799   875  4345 E DropBoxManagerService: 	... 5 more
,09-01 11:15:37.800  1514  1514 I Process : Sending signal. PID: 1514 SIG: 9
,09-01 11:15:37.807   875  1967 I ActivityManager: Killing 3433:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-01 11:15:37.807  4330  4330 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.,
09-01 11:15:37.807  4330  4330 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 11:15:37.807  4330  4330 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-01 11:15:37.807  4330  4330 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-01 11:15:37.807  4330  4330 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-01 11:15:37.807  4330  4330 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-01 11:15:37.807  4330  4330 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-01 11:15:37.807  4330  4330 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-01 11:15:37.807  4330  4330 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-01 11:15:37.807  4330  4330 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-01 11:15:37.807  4330  4330 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-01 11:15:37.807  4330  4330 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-01 11:15:37.807  4330  4330 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-01 11:15:37.807  4330  4330 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 11:15:37.807  4330  4330 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-01 11:15:37.807  4330  4330 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-01 11:15:37.807  4330  4330 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-01 11:15:37.807  4330  4330 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-01 11:15:37.807  4330  4330 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-01 11:15:37.807  4330  4330 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-01 11:15:37.807  4330  4330 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-01 11:15:37.807  4330  4330 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-01 11:15:37.807  4330  4330 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 11:15:37.807  4330  4330 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 11:15:37.807  4330  4330 E SQLiteDatabase: 	,at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:15:37.807  4330  4330 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-01 11:15:37.807  4330  4330 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 11:15:37.807  4330  4330 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:15:37.807  4330  4330 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 11:15:37.807  4330  4330 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-01 11:15:37.808  4330  4330 D AndroidRuntime: Shutting down VM
,09-01 11:15:37.828  4283  4313 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,09-01 11:15:37.832  4283  4317 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-01 11:15:37.832  4283  4317 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 11:15:37.832  4283  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-01 11:15:37.832  4283  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-01 11:15:37.832  4283  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-01 11:15:37.832  4283  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-01 11:15:37.832  4283  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-01 11:15:37.832  4283  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-01 11:15:37.832  4283  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-01 11:15:37.832  4283  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-01 11:15:37.832  4283  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-01 11:15:37.832  4283  4317 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-01 11:15:37.832  4283  4317 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-01 11:15:37.832  4283  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 11:15:37.832  4283  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-01 11:15:37.832  4283  4317 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-01 11:15:37.832  4283  4317 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-01 11:15:37.832  4283  4317 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-01 11:15:37.832  4283  4317 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-01 11:15:37.832  4283  4317 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-01 11:15:37.832  4283  4317 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-01 11:15:37.832  4283  4317 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-01 11:15:37.832  4283  4317 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:15:37.832  4283  4317 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-01 11:15:37.832  4283  4317 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-01 11:15:37.832  4283  4317 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-01 11:15:37.832  4283  4317 E AndroidRuntime: Process: android.process.acore, PID: 4283
09-01 11:15:37.832  4283  4317 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 11:15:37.832  4283  4317 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-01 11:15:37.832  4283  4317 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-01 11:15:37.832  4283  4317 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-01 11:15:37.832  4283  4317 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-01 11:15:37.832  4283  4317 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-01 11:15:37.832  4283  4317 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-01 11:15:37.832  4283  4317 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-01 11:15:37.832  4283  4317 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-01 11:15:37.832  4283  4317 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-01 11:15:37.832  4283  4317 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-01 11:15:37.832  4283  4317 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-01 11:15:37.832  4283  4317 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 11:15:37.832  4283  4317 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-01 11:15:37.832  4283  4317 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-01 11:15:37.832  4283  4317 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-01 11:15:37.832  4283  4317 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-01 11:15:37.832  4283  4317 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-01 11:15:37.832  4283  4317 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-01 11:15:37.832  4283  4317 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-01 11:15:37.832  4283  4317 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-01 11:15:37.832  4283  4317 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:15:37.832  4283  4317 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-01 11:15:37.832  4283  4317 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-01 11:15:37.833  4283  4313 I Process : Sending signal. PID: 4283 SIG: 9
,09-01 11:15:37.847   875  1307 D WifiService: Client connection lost with reason: 4
,09-01 11:15:37.851   875   886 I ActivityManager: Process com.google.process.gapps (pid 1514) has died
,09-01 11:15:37.852   875   886 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
,09-01 11:15:37.852   875   886 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
,09-01 11:15:37.852   875   886 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 21000ms
09-01 11:15:37.852   875   886 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 31000ms
,09-01 11:15:37.856   875  4346 E DropBoxManagerService: Can't write: system_app_crash
09-01 11:15:37.856   875  4346 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-01 11:15:37.856   875  4346 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-01 11:15:37.856   875  4346 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-01 11:15:37.856   875  4346 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-01 11:15:37.856   875  4346 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-01 11:15:37.856   875  4346 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-01 11:15:37.856   875  4346 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-01 11:15:37.856   875  4346 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-01 11:15:37.856   875  4346 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-01 11:15:37.856   875  4346 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-01 11:15:37.856   875  4346 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-01 11:15:37.856   875  4346 E DropBoxManagerService: 	... 5 more
,09-01 11:15:37.863  1719  1719 W RocketImpressions: ClearcutLogger connection suspended: 1
,09-01 11:15:37.863  4330  4330 E AndroidRuntime: FATAL EXCEPTION: main
09-01 11:15:37.863  4330  4330 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4330
09-01 11:15:37.863  4330  4330 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 11:15:37.863  4330  4330 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-01 11:15:37.863  4330  4330 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-01 11:15:37.863  4330  4330 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-01 11:15:37.863  4330  4330 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 11:15:37.863  4330  4330 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 11:15:37.863  4330  4330 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:15:37.863  4330  4330 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-01 11:15:37.863  4330  4330 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 11:15:37.863  4330  4330 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:15:37.863  4330  4330 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 11:15:37.863  4330  4330 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 11:15:37.863  4330  4330 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 11:15:37.863  4330  4330 E AndroidRuntime: ,	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-01 11:15:37.863  4330  4330 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-01 11:15:37.863  4330  4330 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-01 11:15:37.863  4330  4330 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-01 11:15:37.863  4330  4330 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-01 11:15:37.863  4330  4330 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-01 11:15:37.863  4330  4330 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-01 11:15:37.863  4330  4330 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-01 11:15:37.863  4330  4330 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-01 11:15:37.863  4330  4330 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-01 11:15:37.863  4330  4330 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-01 11:15:37.863  4330  4330 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 11:15:37.863  4330  4330 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-01 11:15:37.863  4330  4330 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-01 11:15:37.863  4330  4330 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-01 11:15:37.863  4330  4330 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-01 11:15:37.863  4330  4330 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-01 11:15:37.863  4330  4330 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-01 11:15:37.863  4330  4330 E AndroidRuntime: 	... 10 more
,09-01 11:15:37.868   875  2233 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-01 11:15:37.869   875  4347 E DropBoxManagerService: Can't write: system_app_crash
,09-01 11:15:37.869   875  4347 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-01 11:15:37.869   875  4347 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-01 11:15:37.869   875  4347 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-01 11:15:37.869   875  4347 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-01 11:15:37.869   875  4347 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-01 11:15:37.869   875  4347 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-01 11:15:37.869   875  4347 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-01 11:15:37.869   875  4347 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-01 11:15:37.869   875  4347 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-01 11:15:37.869   875  4347 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-01 11:15:37.869   875  4347 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-01 11:15:37.869   875  4347 E DropBoxManagerService: 	... 5 more
09-01 11:15:37.868  4330  4330 I Process : Sending signal. PID: 4330 SIG: 9
,09-01 11:15:37.871   282   344 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
